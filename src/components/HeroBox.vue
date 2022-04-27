<template>
  <!-- CONTAINER HERO -->
  <div class="hero container-fluid mt-4 d-flex align-items-center">
    <div class="container">
      <!-- Text container Center -->
      <div class="row text-center container-info">
        <h1>Brand New Arrivals</h1>
        <p class="text-uppercase">new collection from new york</p>

        <!-- Buttons -->
        <div class="button py-3">
          <button
            type="button"
            class="
              btn
              text-light text-uppercase
              border border-white
              mx-3
              px-5
              py-3
              fw-bold
            "
          >
            view all
          </button>
          <button
            type="button"
            class="
              btn
              text-light text-uppercase
              border border-white
              px-5
              py-3
              fw-bold
            "
          >
            lookbook
          </button>
        </div>
        <!-- /Buttons -->
      </div>
      <!-- /Text container Center -->
    </div>
  </div>
  <!-- /CONTAINER HERO -->
</template>

<script>
export default {
  name: "HeroBox",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.hero {
  background-image: $bg-hero;
  height: 70vh;
  background-size: cover;
  background-position: center;
  color: $white-color;

  .container-info {
    h1 {
      font-size: 90px;
      font-weight: bold;
      letter-spacing: 2px;
    }
    p {
      font-size: 20px;
      letter-spacing: 2px;
    }

    button {
      border-radius: 22px;
      &:hover {
        background-color: $shocking-color;
      }
    }
  }
}
</style>
