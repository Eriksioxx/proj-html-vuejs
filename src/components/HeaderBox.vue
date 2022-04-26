<template>
  <header class="sticky-top">
    <div class="container-header-box">
      <!-- Pre header -->
      <div class="container-fluid">
        <div class="container container-pre-header d-flex">
          <!-- SX -->
          <div class="d-flex ps-5 pt-3">
            <font-awesome-icon icon="fa-brands fa-facebook-f" class="mx-2" />
            <font-awesome-icon icon="fa-brands fa-twitter" class="mx-2" />
            <font-awesome-icon icon="fa-brands fa-instagram" class="mx-2" />
            <font-awesome-icon icon="fa-brands fa-youtube" class="mx-2" />
          </div>
          <!-- /SX -->

          <!-- DX -->
          <div class="dx-nav container d-flex justify-content-end">
            <div class="shopping">
              <p class="px-4 py-2">Shooping Cart</p>
            </div>
            <div class="my-account">
              <p class="px-4 py-2">
                My Account <font-awesome-icon icon="fa-solid fa-chevron-down" />
              </p>
            </div>
            <div class="cart">
              <p class="px-4 py-2 text-uppercase">
                <font-awesome-icon
                  icon="fa-solid fa-cart-shopping  py-1 px-1 me-2"
                />
                Cart
                <font-awesome-icon icon="fa-solid fa-chevron-down " />
              </p>
            </div>
          </div>
          <!-- /DX -->
        </div>
      </div>
      <!-- /Pre Header -->

      <!-- NAVBAR -->
      <nav class="container d-flex justify-content-between mt-3">
        <!-- Logo -->
        <div class="logo-container ms-5 py-2">
          <img src="@/assets/img/classic_shop_logo1x.png" />
        </div>
        <!-- /Logo -->

        <!-- Container Menu-->
        <div class="container-menu">
          <!-- Menu List -->
          <ul class="d-flex list-unstyled">
            <li class="px-4" v-for="item in navbar" :key="item.id">
              <a :href="item.url" class="text-secondary text-decoration-none">{{
                item.label
              }}</a>
              <font-awesome-icon icon="fa-solid fa-chevron-down" class="px-2" />
            </li>
          </ul>
          <!-- /Menu List -->
        </div>
        <!-- /Container Menu -->

        <!-- Container Button/Icon -->
        <div class="container-button-icon">
          <!-- Button -->
          <button
            type="button"
            class="btn text-light text-uppercase rounded-pill me-4"
          >
            Shop Now!
          </button>
          <!-- /Button -->

          <!-- Search Lens -->
          <a href="#"
            ><font-awesome-icon icon="fa-solid fa-magnifying-glass"
          /></a>
          <!-- /Search Lens -->
        </div>
        <!-- /Container Button/Icon -->
      </nav>
      <!-- /NAVBAR -->
    </div>
    <!-- CONTAINER HEADER-BOX -->
  </header>
</template>

<script>
export default {
  name: "HeaderBox",
  props: {
    navbar: Array,
  },
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

header {
  background-color: $white-color;
}
.container-fluid {
  border-bottom: 1px solid $edward-color;

  .container-pre-header {
    .shopping,
    .my-account {
      border-right: 1px solid $edward-color;

      p {
        color: $shark-color;
      }
    }
    .dx-nav {
      font-size: 15px;
    }

    .fab,
    .fas {
      font-size: 15px;
    }

    .fa-chevron-down {
      font-size: 10px;
    }

    .cart {
      width: 200px;
      background-color: #fafafa;
    }
  }
}

.container-menu {
  li {
    &:hover {
      border-top: 3px solid $havelockBlue-color;
    }
  }
}

.container-button-icon {
}

.fa-chevron-down {
  font-size: 10px;
}

button {
  background-color: $havelockBlue-color;
  font-size: 15px;

  &:hover {
    background-color: $shocking-color;
  }
}
</style>
