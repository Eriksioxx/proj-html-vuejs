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
          <div class="container d-flex justify-content-end">
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

      <!-- Navbar -->
      <nav class="container"></nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderBox",
  props: {},
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
      color: $shark-color;
    }
  }
  .fab,
  .fas {
    font-size: 20px;
  }
  .fa-chevron-down {
    font-size: 10px;
  }
  .cart {
    width: 200px;
    background-color: $shocking-color;
  }
}
</style>
