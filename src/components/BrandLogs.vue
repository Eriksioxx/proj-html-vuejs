<template>
  <div class="container-logo container-fluid">
    <div class="container margin-top">
      <h6 class="text-center pt-5 mb-5" style="letter-spacing: 3px">
        BRAND LOGOS
      </h6>
      <div class="row">
        <carousel
          class="col-12"
          :per-page="5"
          :mouse-drag="true"
          :autoplay="true"
          :autoplayTimeout="2000"
          :loop="true"
        >
          <!-- LOGO 1 -->
          <slide>
            <div class="col">
              <div class="logo-1">
                <img src="../assets/img/b_logotype_6.png" alt="" />
              </div>
            </div>
          </slide>
          <!-- / LOGO 1 -->

          <!-- LOGO 2 -->
          <slide>
            <div class="col">
              <div class="logo-1">
                <img src="../assets/img/b_logotype_7.png" alt="" />
              </div>
            </div>
          </slide>
          <!-- / LOGO 2 -->

          <!-- LOGO 3 -->
          <slide>
            <div class="col">
              <div class="logo-1">
                <img src="../assets/img/b_logotype_1.png" alt="" />
              </div>
            </div>
          </slide>
          <!-- / LOGO 3 -->

          <!-- LOGO 4 -->
          <slide>
            <div class="col">
              <div class="logo-1">
                <img src="../assets/img/b_logotype_2.png" alt="" />
              </div>
            </div>
          </slide>
          <!-- / LOGO 4 -->

          <!-- LOGO 5 -->
          <slide>
            <div class="col">
              <div class="logo-1">
                <img src="../assets/img/b_logotype_3.png" alt="" />
              </div>
            </div>
          </slide>
          <!-- / LOGO 5 -->

          <!-- LOGO 6 -->
          <slide>
            <div class="col">
              <div class="logo-1">
                <img src="../assets/img/b_logotype_4.png" alt="" />
              </div>
            </div>
          </slide>
          <!-- / LOGO 6 -->

          <!-- LOGO 7 -->
          <slide>
            <div class="col">
              <div class="logo-1">
                <img src="../assets/img/b_logotype_5.png" alt="" />
              </div>
            </div>
          </slide>
          <!-- / LOGO 7 -->
        </carousel>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BrandLogs",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.margin-top {
  margin-top: 100px;
}

.container-logo {
  height: 300px;
  background-color: #f6f6f6;
}
</style>
