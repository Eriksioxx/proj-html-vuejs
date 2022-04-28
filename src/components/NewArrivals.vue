<template>
  <div class="container-fluid">
    <div class="margin-top">
      <div class="text-center">
        <div class="d-flex justify-content-center align-items-center">
          <!-- Border bottom SX -->
          <div class="border_bottom me-5"></div>

          <!-- Title -->
          <h1 class="fw-bold">New Arrivals</h1>

          <!-- Border bottom DX -->
          <div class="border_bottom ms-5"></div>
        </div>

        <!-- Details -->
        <p class="text-muted">Brand new products from top designers</p>
      </div>

      <!-- OUTFITS CONTAINER -->

      <div class="row row-cols-5 mt-5">
        <carousel
          class="col-12"
          :per-page="5"
          :navigate-to="someLocalProperty"
          :mouse-drag="true"
          :autoplay="true"
          :autoplayTimeout="2000"
          :loop="true"
        >
          <!-- Outfit 1 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/spring_printed_dress-400x520.jpg"
                  alt="spring_printed_dress"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 1 -->
          <!-- Outfit 2 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/modern_love_tee-400x520.jpg"
                  alt="modern_love_tee"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 2 -->
          <!-- Outfit 3 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/black_leather_jacket-400x520.jpg"
                  alt="black_leather_jacket"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 3 -->
          <!-- Outfit 4 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/black_elegant_leather_jacket-400x520.jpg"
                  alt="black_elegant_leather_jacket"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 4 -->
          <!-- Outfit 5 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/hipster_black_top-400x520.jpg"
                  alt="hipster_black_top"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 5 -->
          <!-- Outfit 6 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/black_leather_suit-400x520.jpg"
                  alt="black_leather_suit"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 6-->
          <!-- Outfit 7 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/blue_jacket_and_white_stripe_tee-400x520.jpg"
                  alt="blue_jacket_and_white_stripe_tee"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 7 -->
          <!-- Outfit 8 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/blue_leather_jacket-400x520.jpg"
                  alt="blue_leather_jacket"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 8 -->
          <!-- Outfit 9 -->
          <slide>
            <div class="col">
              <div class="container-outfit">
                <img
                  src="../assets/img/modern_black_leather_suit-400x520.jpg"
                  alt="modern_black_leather_suit"
                  class="img-fluid"
                />
              </div>
            </div>
          </slide>
          <!-- Outfit 9 -->
        </carousel>
      </div>

      <!-- / OUTFITS CONTAINER -->
    </div>
  </div>
</template>

<script>
export default {
  name: "NewArrivals",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.margin-top {
  margin-top: 120px;
}

.border_bottom {
  border-bottom: 1px solid $edward-color;
  width: 400px;
}
</style>
