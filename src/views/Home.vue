<template>
  <div>
    <Cover imageUrl="bg_1" />
    <Carousel />
    <Boxes />
    <Slogan />
  </div>
</template>

<script>
import Cover from "@/components/Cover.vue";
import Carousel from "@/components/Carousel.vue";
import Boxes from "@/components/Boxes.vue";
import Slogan from "@/components/Slogan.vue";

export default {
  name: "Home",
  components: { Cover, Boxes, Carousel, Slogan },
};
</script>
