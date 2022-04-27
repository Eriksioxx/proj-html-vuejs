<template>
  <div class="container-fluid">
    <div class="container margin-top">
      <div class="text-center">
        <div class="d-flex justify-content-center align-items-center">
          <!-- Border bottom SX -->
          <div class="border_bottom me-5"></div>

          <!-- Title -->
          <h1 class="fw-bold">Best Seller</h1>

          <!-- Border bottom DX -->
          <div class="border_bottom ms-5"></div>
        </div>

        <!-- Details -->
        <p class="text-muted">Must have products from our top sellers</p>
      </div>

      <!-- OUTFITS CONTAINER -->
      <div class="row row-cols-5 mt-5">
        <!-- Outfit 1 -->
        <div class="col">
          <div class="container-outfit">
            <img
              src="../assets/img/spring_printed_dress-400x520.jpg"
              alt="spring_printed_dress"
              class="img-fluid"
            />
          </div>
        </div>
        <!-- Outfit 1 -->
        <!-- Outfit 2 -->
        <div class="col">
          <div class="container-outfit">
            <img
              src="../assets/img/modern_love_tee-400x520.jpg"
              alt="modern_love_tee"
              class="img-fluid"
            />
          </div>
        </div>
        <!-- Outfit 2 -->
        <!-- Outfit 3 -->
        <div class="col">
          <div class="container-outfit">
            <img
              src="../assets/img/black_leather_jacket-400x520.jpg"
              alt="black_leather_jacket"
              class="img-fluid"
            />
          </div>
        </div>
        <!-- Outfit 3 -->
        <!-- Outfit 4 -->
        <div class="col">
          <div class="container-outfit">
            <img
              src="../assets/img/black_elegant_leather_jacket-400x520.jpg"
              alt="black_elegant_leather_jacket"
              class="img-fluid"
            />
          </div>
        </div>
        <!-- Outfit 4 -->
        <!-- Outfit 5 -->
        <div class="col">
          <div class="container-outfit">
            <img
              src="../assets/img/hipster_black_top-400x520.jpg"
              alt="hipster_black_top"
              class="img-fluid"
            />
          </div>
        </div>
        <!-- Outfit 5 -->
      </div>
      <!-- / OUTFITS CONTAINER -->
    </div>
  </div>
</template>

<script>
export default {
  name: "CollectionBox",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.margin-top {
  margin-top: 150px;
}

.border_bottom {
  border-bottom: 1px solid $edward-color;
  width: 400px;
}
</style>
