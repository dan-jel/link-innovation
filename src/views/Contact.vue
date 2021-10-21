<template>
  <div>
    <Cover imageUrl="img_4" />
    <ContactForm />
    <Slogan />
  </div>
</template>

<script>
import Cover from "@/components/Cover.vue";
import ContactForm from "@/components/ContactForm.vue";
import Slogan from "@/components/Slogan.vue";

export default {
  name: "Contact",
  components: { Cover, ContactForm, Slogan },
};
</script>
