<template>
  <div class="container-fluid container-review margin-top">
    <div class="container pt-5">
      <!-- ROW -->
      <div class="row d-flex justify-content-center text-center mt-5">
        <carousel
          :per-page="1"
          :navigate-to="someLocalProperty"
          :mouse-drag="true"
          :autoplay="true"
          :autoplayTimeout="2000"
          :loop="true"
          :navigationEnabled="true"
          :NavigationNextLabel="corda"
          :NavigationPrevLabel="free"
        >
          <!-- Testimonial 1-->
          <slide>
            <div>
              <img src="../assets/img/man_testimonial.png" alt="testimonial" />
              <p class="fst-italic mt-4">
                Integer eget hendrerit nisl. Maecenas in turpis imperdiet turpis
                rutrum convallis non eu nisi. Integer interdum gravida lacus
                efficitur tempus. Praesent elit odio, scelerisque id justo eget,
                luctus pretium ipsum. Proin justo est, convallis nec eleifend
                consectetur, blandit id dui. Fusce at diam vel turpis sagittis
                lobortis.
              </p>
              <p><span class="fw-bold">Dario Pineda</span>, Theme Fusion</p>
            </div>
          </slide>
          <!-- /Testimonial 1-->
          <!-- Testimonial 2 -->
          <slide>
            <div>
              <img
                src="../assets/img/woman_testimonial.png"
                alt="testimonial"
              />
              <p class="fst-italic mt-4">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Possimus laboriosam veritatis nemo illum amet nesciunt odio unde
                delectus dignissimos. Nobis praesentium nam obcaecati placeat
                dolore odit optio odio laudantium recusandae.
              </p>
              <p><span class="fw-bold">Gina Patata</span>, Theme Fusion</p>
            </div>
          </slide>
          <!-- /Testimonial 2-->
        </carousel>
      </div>
      <!-- /ROW -->
    </div>
  </div>
</template>

<script>
export default {
  name: "CostumersReview",
  props: {},
};
</script>

<style scoped lang="scss">
@import "@/style/variables.scss";

.margin-top {
  margin-top: 120px;
}

.container-review {
  height: 500px;
  background-image: $testimonial-img;
  background-size: 120%;
  background-position: center;
  color: $white-color;
  img {
    width: 8rem;
  }
}
</style>
