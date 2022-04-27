<template>
  <div class="container-fluid mt-5">
    <div class="row text-center text-light">
      <!-- Winter Collection -->
      <div class="winter-collection col-4">
        <div class="details">
          <h2 class="fw-bold display-6">Winter Collection</h2>
          <p class="text-uppercase">stilysh and warm</p>
          <button
            type="button"
            class="btn text-light rounded-pill border border-white px-4 py-2"
          >
            VIEW MORE
          </button>
        </div>
      </div>
      <!-- /Winter Collection -->
      <!-- Spring Collection -->
      <div class="spring-collection col-4">
        <div class="details">
          <h2 class="fw-bold display-6">Spring Collection</h2>
          <p class="text-uppercase">bright and colorful</p>
          <button
            type="button"
            class="
              btn
              text-light
              rounded-pill
              border border-white
              px-4
              py-2
              mb-4
            "
          >
            VIEW MORE
          </button>
        </div>
      </div>
      <!-- /Spring Collection -->
      <!-- Autumn Collection -->
      <div class="autumn-collection col-4">
        <div class="details">
          <h2 class="fw-bold display-6">Autumn Collection</h2>
          <p class="text-uppercase">rich and comfortable</p>
          <button
            type="button"
            class="btn text-light rounded-pill border border-white px-4 py-2"
          >
            VIEW MORE
          </button>
        </div>
      </div>
      <!-- /Autumn Collection -->
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

.winter-collection {
  background-image: $winter-collection;
  background-size: cover;
  background-position: center top;
}

.spring-collection {
  background-image: $spring-collection;
  background-size: cover;
  background-position: center top;
}

.autumn-collection {
  background-image: $autumn-collection;
  background-size: cover;
  background-position: center top;
}

.details {
  margin-top: 400px;
}

button {
  font-size: 13px;
  &:hover {
    background-color: $shocking-color;
  }
}
</style>
