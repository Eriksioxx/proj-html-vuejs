<template>
  <div class="container-fluid container-footer">
    <div class="container">
      <div class="row">
        <!-- CONTACTS -->
        <div class="col-3">
          <div class="logo-box mt-5">
            <img src="@/assets/img/classic_shop_logo_footer.png" />
          </div>

          <div
            class="list-container mt-5 fw-bold"
            style="font-size: 13px; letter-spacing: 2px"
          >
            <ul
              class="list-unstyled"
              v-for="item in footerContacts"
              :key="item"
            >
              <li>
                <a class="text-white text-decoration-none">
                  {{ item.address }}
                </a>
              </li>
              <li>
                <a class="text-white text-decoration-none">
                  {{ item.city }}
                </a>
              </li>
              <li>
                <a class="text-white text-decoration-none">
                  Phone: {{ item.phoneNumber }}
                </a>
              </li>
              <li>
                <a class="text-white text-decoration-none">
                  Email: {{ item.mail }}
                </a>
              </li>
              <li>
                <a class="text-white text-decoration-none">
                  Web: {{ item.web }}
                </a>
              </li>
            </ul>
          </div>

          <!-- SOCIAL ICONS -->
          <div class="icon-brand pt-5 d-flex text-light fs-5">
            <font-awesome-icon
              icon="fa-brands fa-facebook-f"
              class="icon mx-2"
            />
            <font-awesome-icon icon="fa-brands fa-twitter" class="icon mx-2" />
            <font-awesome-icon
              icon="fa-brands fa-instagram"
              class="icon mx-2"
            />
            <font-awesome-icon icon="fa-brands fa-youtube" class="icon mx-2" />
          </div>
          <!-- / SOCIAL ICONS -->
        </div>
        <!-- / CONTACTS -->

        <!-- TOP RATED PRODUCTS -->
        <div class="col-3">
          <p class="text-uppercase text-white mt-5" style="font-size: 15px">
            top rated products
          </p>

          <div
            class="list-container"
            style="font-size: 13px; letter-spacing: 2px"
          >
            <ul
              class="list-unstyled d-flex justify-content-between"
              v-for="item in topRatedProducts"
              :key="item"
            >
              <li class="d-flex flex-column">
                <a class="text-white text-decoration-none">
                  {{ item.article }}
                </a>
                <p>
                  <font-awesome-icon icon="fa-solid fa-star" />
                  <font-awesome-icon icon="fa-solid fa-star" />
                  <font-awesome-icon icon="fa-solid fa-star" />
                  <font-awesome-icon icon="fa-solid fa-star" />
                  <font-awesome-icon icon="fa-solid fa-star" />
                </p>
                <a class="text-white text-decoration-none">
                  {{ item.price }}
                </a>
                <hr class="text-muted my-3" />
              </li>

              <li class="ps-5">
                <img
                  :src="item.image"
                  :alt="item.image"
                  width="80px"
                  class="mt-1"
                />
              </li>
            </ul>
          </div>
        </div>
        <!-- / TOP RATED PRODUCTS -->

        <!-- RECENT POSTS -->
        <div class="col-3">
          <p class="text-white mt-5" style="font-size: 15px">RECENTS POSTS</p>

          <div
            class="list-container mt-2"
            style="font-size: 13px; letter-spacing: 1px"
          >
            <ul class="list-unstyled" v-for="item in recentPosts" :key="item">
              <li>
                <i class="fas fa-chevron-right text-light me-2"></i>
                <a class="text-white text-decoration-none">
                  {{ item.post }}
                </a>
                <hr class="text-muted" />
              </li>
            </ul>
          </div>
        </div>
        <!-- / RECENT POSTS -->

        <!-- TAGS -->
        <div class="col-3 column-tags">
          <p class="text-white mt-5" style="font-size: 15px">TAGS</p>

          <div
            class="container-tag d-inline-flex text-light fs-6 mx-1 my-1 px-2"
            v-for="item in tagsList"
            :key="item"
          >
            {{ item.tag }}
          </div>
        </div>
        <!-- / TAGS -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterBox",
  props: {
    footerContacts: Array,
    topRatedProducts: Array,
    recentPosts: Array,
    tagsList: Array,
  },
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.container-footer {
  max-height: 750px;
  background-color: #2b2e32;

  .logo-box {
    width: 200px;
    padding-top: 15px;

    img {
      width: 100%;
    }
  }
  .container-tag {
    border: 1px solid $edward-color;
    cursor: pointer;
    font-size: 9px;

    &:hover {
      background-color: $shocking-color;
    }
  }
  .fa-star {
    color: #427ed1;
  }
}
.icon-brand .icon:hover {
  transform: scale(1.2);
  color: red;
}
</style>


