<template>
  <div>
    <Cover imageUrl="img_3" />
    <CardsCarousel />
    <Banner />
  </div>
</template>

<script>
import Cover from "@/components/Cover.vue";
import Banner from "@/components/Banner.vue";
import CardsCarousel from "@/components/CardsCarousel.vue";

export default {
  name: "About",
  components: { Cover, Banner, CardsCarousel },
};
</script>
