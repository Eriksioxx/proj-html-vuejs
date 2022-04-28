<template>
  <div class="container-fluid container-shipping">
    <div class="container margin-top d-flex justify-content-center">
      <div class="row mt-3">
        <div class="text-center mb-4">
          <div class="d-flex justify-content-center align-items-center">
            <!-- DIV VUOTO PER BORDI DIVISORI -->
            <div class="border_bottom me-5"></div>
            <!-- / DIV VUOTO PER BORDI DIVISORI -->

            <h1 class="fw-bold">From Our Blog</h1>

            <!-- DIV VUOTO PER BORDI DIVISORI -->
            <div class="border_bottom ms-5"></div>
            <!-- / DIV VUOTO PER BORDI DIVISORI -->
          </div>

          <p class="text-muted">The latest Classic Shop news</p>
        </div>
        <!-- BOX 1 -->
        <div class="col-4">
          <div class="box mx-auto">
            <div>
              <img
                src="../assets/img/post_img_12-320x202.jpg"
                alt="post_img_12"
                class="mb-3 w-100"
              />
            </div>
            <h6 class="fw-bold mb-1" style="font-size: 17px">
              Aenean lobortis sapien enim viverra
            </h6>
            <p style="font-size: 12px" class="text-muted">
              September 9th, 2015 | 0 comments
            </p>
            <p class="text-muted" style="font-size: 13px">
              Etiam finibus suscipit odio, quis cursus dui pharetra vitae. Donec
              hendrerit tincidunt congue.
            </p>
          </div>
        </div>
        <!-- / BOX 1 -->
        <!-- BOX 2 -->
        <div class="col-4">
          <div class="box mx-auto">
            <div>
              <img
                src="../assets/img/post_img_11-320x202.jpg"
                alt="post_img_11"
                class="mb-3 w-100"
              />
            </div>
            <h6 class="fw-bold mb-1" style="font-size: 17px">
              Aenean lobortis sapien enim viverra
            </h6>
            <p style="font-size: 12px" class="text-muted">
              September 9th, 2015 | 0 comments
            </p>
            <p class="text-muted" style="font-size: 13px">
              Etiam finibus suscipit odio, quis cursus dui pharetra vitae. Donec
              hendrerit tincidunt congue.
            </p>
          </div>
        </div>
        <!-- / BOX 2 -->
        <!-- BOX 3 -->
        <div class="col-4">
          <div class="box mx-auto">
            <div>
              <img
                src="../assets/img/post_img_10-320x202.jpg"
                alt="post_img_10"
                class="mb-3 w-100"
              />
            </div>
            <h6 class="fw-bold mb-1" style="font-size: 17px">
              Aenean lobortis sapien enim viverra
            </h6>
            <p style="font-size: 12px" class="text-muted">
              September 9th, 2015 | 0 comments
            </p>
            <p class="text-muted" style="font-size: 13px">
              Etiam finibus suscipit odio, quis cursus dui pharetra vitae. Donec
              hendrerit tincidunt congue.
            </p>
          </div>
        </div>
        <!-- / BOX 3 -->
      </div>
    </div>
    <hr class="mx-5 mt-5" />
  </div>
</template>

<script>
export default {
  name: "OurBlog",
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
  width: 435px;
}

.box {
  width: 350px;
}
</style>
