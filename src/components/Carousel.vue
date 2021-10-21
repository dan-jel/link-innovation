<template>
  <section class="probootstrap-section">
    <div class="container">
      <div class="row mb-5">
        <div class="col-md-12">
          <carousel id="carousel" :loop="true" :nav="false" :margin="10">
            <img src="@/assets/person_1.jpg" />
            <img src="@/assets/person_2.jpg" />
            <img src="@/assets/person_3.jpg" />
            <img src="@/assets/person_1.jpg" />
            <img src="@/assets/person_2.jpg" />
            <img src="@/assets/person_3.jpg" />
          </carousel>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "Carousel",
  components: { carousel },
};
</script>
