<template>
  <div class="container-fluid subscribe-container">
    <div class="container container-box d-flex justify-content-center">
      <div class="row">
        <!-- Title -->
        <div class="col-6 d-flex pe-5">
          <div
            class="
              icon
              rounded-circle
              text-center
              me-4
              d-flex
              align-items-center
              justify-content-center
            "
          >
            <font-awesome-icon icon="fa-regular fa-envelope" />
          </div>
          <div
            class="
              text text-light
              d-flex
              align-items-center
              justify-content-center
            "
          >
            <h5 class="fw-bold">Subscribe now and get special offers</h5>
          </div>
        </div>
        <!-- / Title -->

        <!-- input -->
        <div class="col-6 d-flex pt-2 ps-5">
          <div class="input-group input">
            <input
              type="text"
              class="form-control rounded-pill"
              placeholder="Insert your email"
              aria-label="Username"
            />
          </div>

          <!-- button -->
          <button
            type="button"
            class="btn btn-primary text-uppercase rounded-pill px-3 py-0 ms-3"
          >
            send
          </button>
          <!--  / button -->
        </div>
        <!-- / input -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SubscribeBox",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.subscribe-container {
  height: 200px;
  background-color: #303337;
  .icon {
    width: 60px;
    height: 60px;
    background-color: #2b2e32;

    &:hover {
      background-color: $shocking-color;
    }

    .fa-envelope {
      font-size: 25px;
      color: $edward-color;
    }
  }

  .input {
    width: 450px;
    height: 35px;
    font-size: 13px;
  }
}

.container-box {
  padding-top: 70px;
}

button {
  width: 150px;
  font-size: 14px;
  height: 40px;

  &:hover {
    background-color: $shocking-color;
  }
}
</style>


