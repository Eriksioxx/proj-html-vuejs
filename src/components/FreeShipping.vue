<template>
  <div class="container-fluid container-shipping margin-top">
    <div class="container d-flex justify-content-center align-items-center">
      <!-- ROW -->
      <div class="row my-5 text-light">
        <!-- PROMO BOX SX -->
        <div class="promo-box col-6 me-5">
          <div class="details">
            <h2 class="fw-bold">70% Off</h2>
            <p>Vivamus tempor leo lacus, feugiat ut magna aliquam erat.</p>
            <button
              type="button"
              class="
                btn
                text-light
                rounded-pill
                border border-white
                mb-4
                px-4 px-2
              "
            >
              VIEW MORE
            </button>
          </div>
        </div>
        <!-- PROMO BOX SX -->

        <!-- FREE SHIPPING DX -->
        <div class="col-6 free-shipping">
          <div class="details">
            <h2 class="fw-bold">Free Shipping</h2>
            <p>Vivamus tempor leo lacus, feugiat ut magna aliquam erat.</p>
            <button
              type="button"
              class="
                btn
                text-light text-uppercase
                rounded-pill
                border border-white
                mb-4
                px-4 px-2
              "
            >
              view more
            </button>
          </div>
        </div>
      </div>
      <!-- / FREE SHIPPING DX -->
    </div>
    <!-- /ROW -->
  </div>
</template>

<script>
export default {
  name: "FreeShipping",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.margin-top {
  margin-top: 120px;
}

.container-shipping {
  background-image: $confetti-bg;
  background-size: contain;

  p {
    font-size: 15px;
    line-height: 25px;
  }

  .promo-box {
    height: 350px;
    width: 30vw;
    background-image: $promo-box-1;
    background-size: cover;
    background-position: bottom;
  }

  .free-shipping {
    height: 350px;
    width: 30vw;
    background-image: $promo-box-2;
    background-size: cover;
    background-position: bottom;
  }
  .details {
    width: 250px;
    margin: 120px 0 10px 30px;
    line-height: 30px;
  }
}

button {
  font-size: 12px;
  &:hover {
    background-color: $shocking-color;
  }
}
</style>
