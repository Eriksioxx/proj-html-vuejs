<template>
  <div class="container-fluid">
    <div class="margin-bottom container mt-5">
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
      <!-- / Title Center -->

      <!-- BUTTONS -->
      <div class="mt-4 justify-content-center d-flex">
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

      <!-- OUTFITS CONTAINER -->
      <div class="row mt-5 pb-5">
        <!-- Outfit 1 hover-->
        <div class="col-3">
          <!-- Container Outfit -->
          <div class="container-outfit">
            <!-- Show -->
            <div class="show col-3">
              <img
                src="../assets/img/black_elegant_leather_jacket-400x520.jpg"
                alt="black_elegant_leather_jacket"
                class="mb-2"
              />

              <div>
                <span class="fw-bold">Black Leather Jacket</span>
                <br />
                <span class="text-muted">Men, Jacket, Jeans</span>
                <br />
                <span class="text-decoration-line-through text-primary me-2"
                  >$235</span
                >
                <span class="text-primary">$200</span>
              </div>
            </div>
            <!-- /Show -->

            <!-- Hidden -->
            <div
              class="hidden d-flex align-items-center justify-content-center"
            >
              <div
                class="
                  container-icon
                  d-flex
                  align-items-center
                  justify-content-center
                "
              >
                <font-awesome-icon
                  icon="fa-solid fa-check-double"
                  class="display-6 icon-font"
                />
              </div>
            </div>
            <!-- /Hidden -->
          </div>
          <!-- /Container Outfit -->
        </div>
        <!-- / Outfit 1 hover-->

        <!-- Outfit 2 -->
        <div class="col-3">
          <div class="container-outfit">
            <div class="show col-3">
              <img
                src="../assets/img/black_leather_suit-400x520.jpg"
                alt="black_leather_suit"
                class="mb-2"
              />

              <div>
                <span class="fw-bold">Black Leather Suit</span>
                <br />
                <span class="text-muted">Men, Jacket</span>
                <br />
                <span class="text-primary">$176</span>
              </div>
            </div>
            <!-- Hidden -->
            <div
              class="hidden d-flex align-items-center justify-content-center"
            >
              <div
                class="
                  container-icon
                  d-flex
                  align-items-center
                  justify-content-center
                "
              >
                <font-awesome-icon
                  icon="fa-solid fa-check-double"
                  class="display-6 icon-font"
                />
              </div>
            </div>
            <!-- /Hidden -->
          </div>
        </div>

        <!-- / Outfit 2 -->

        <!-- Outfit 3 -->
        <div class="col-3">
          <div class="container-outfit">
            <div class="show col-3">
              <img
                src="../assets/img/blue_jacket_and_white_stripe_tee-400x520.jpg"
                alt="blue_jacket_and_white_stripe_tee"
                class="mb-2"
              />

              <div>
                <span class="fw-bold">Blue Jacket & Stripe Tee</span>
                <br />
                <span class="text-muted">Men, Jacktes, Suits</span>
                <br />
                <span class="text-primary">$580</span>
              </div>
            </div>
            <!-- Hidden -->
            <div
              class="hidden d-flex align-items-center justify-content-center"
            >
              <div
                class="
                  container-icon
                  d-flex
                  align-items-center
                  justify-content-center
                "
              >
                <font-awesome-icon
                  icon="fa-solid fa-check-double"
                  class="display-6 icon-font"
                />
              </div>
            </div>
            <!-- /Hidden -->
          </div>
        </div>
        <!-- / Outfit 3 -->

        <!-- Outfit 4 -->
        <div class="col-3">
          <div class="container-outfit">
            <div class="show col-3">
              <img
                src="../assets/img/modern_black_leather_suit-400x520.jpg"
                alt="modern_black_leather_suit"
                class="mb-2"
              />

              <div>
                <span class="fw-bold">Modern Black Leather Suit</span>
                <br />
                <span class="text-muted">Men, Jacktes</span>
                <br />
                <span class="text-primary">$96</span>
              </div>
            </div>
            <!-- Hidden -->
            <div
              class="hidden d-flex align-items-center justify-content-center"
            >
              <div
                class="
                  container-icon
                  d-flex
                  align-items-center
                  justify-content-center
                "
              >
                <font-awesome-icon
                  icon="fa-solid fa-check-double"
                  class="display-6 icon-font"
                />
              </div>
            </div>
            <!-- /Hidden -->
          </div>
        </div>
        <!-- / Outfit 4 -->
      </div>
      <!-- / OUTFITS CONTAINER -->
    </div>
  </div>
</template>

<script>
export default {
  name: "FeaturedProducts",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.margin-bottom {
  margin-bottom: 200px;
}

.border_bottom {
  border-bottom: 1px solid $edward-color;
  width: 400px;
}

button {
  background-color: #f6f6f6;

  &:hover {
    background-color: $edward-color;
  }
}

// Hidden
.hidden {
  width: 100%;
  height: 430px;
  display: none;
  background: rgb(103, 122, 215);
  background: linear-gradient(
    169deg,
    rgba(103, 122, 215, 1) 0%,
    rgba(225, 70, 252, 0.3536765047816002) 100%
  );

  .container-icon {
    width: 50px;
    height: 50px;
    background-color: $shark-color;
    border-radius: 50%;
    .icon-font {
      color: $white-color;
    }
  }
}
.show {
  position: absolute;
  z-index: 0;
  > img {
    width: 70%;
  }
}

// HOVER
.container-outfit {
  &:hover {
    .show > img {
      -webkit-transition: opacity 0.4s ease-in-out;
      -moz-transition: opacity 0.4s ease-in-out;
      -ms-transition: opacity 0.4s ease-in-out;
      -o-transition: opacity 0.4s ease-in-out;
      transition: opacity 0.4s ease-in-out;
      opacity: 0.5;
    }

    .hidden {
      display: block;
      transition-property: display;
      transition-duration: 0.4s;
      -webkit-transition-property: display; /*Safari e Chrome */
      -webkit-transition-duration: 0.4s;
    }
  }
}
</style>
