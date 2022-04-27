<template>
  <div class="container-fluid">
    <div class="container mt-5">
      <!-- Title Center -->
      <div class="text-center">
        <div class="d-flex justify-content-center align-items-center">
          <!-- DIV VUOTO PER BORDI DIVISORI -->
          <div class="border_bottom me-5"></div>

          <!-- Title -->
          <h1>Featured Products</h1>
          <!-- / Title -->

          <!-- DIV VUOTO PER BORDI DIVISORI -->
          <div class="border_bottom ms-5"></div>
        </div>

        <!-- DETAILS -->
        <p class="text-muted">Must have products from our top sellers</p>
        <!-- / DETAILS -->
      </div>
      <!-- Title Center -->

      <!-- BUTTONS -->
      <div class="mt-4">
        <button
          type="button"
          class="btn btn-light border border-1 rounded-0 px-5 py-2 fw-bold"
        >
          Men
        </button>
        <button
          type="button"
          class="btn btn-light border border-1 rounded-0 px-5 py-2 fw-bold"
        >
          Woman
        </button>
        <button
          type="button"
          class="btn btn-light border border-1 rounded-0 px-5 py-2 fw-bold"
        >
          Accessories
        </button>
      </div>
      <!-- /BUTTONS -->
    </div>
  </div>
  <!-- /Title Center -->
</template>

<script>
export default {
  name: "FeaturedProducts",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";
</style>
