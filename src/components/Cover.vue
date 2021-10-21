<template>
  <section
    class="probootstrap-cover overlay"
    :style="{
      'background-image':
        'url(' + require('@/assets/' + imageUrl + '.jpg') + ')',
    }"
  >
    <div class="container">
      <div
        class="
          row
          align-items-center
          justify-content-center
          text-center
          probootstrap-vh-100
        "
      >
        <div class="col-md-8">
          <h1 class="probootstrap-heading">A Good Company</h1>
          <h2 class="h3 probootstrap-subheading mb-5">
            A free template by <a href="#">uicookies.com</a>
          </h2>
          <p>
            <a
              href="https://uicookies.com/"
              target="_blank"
              class="btn btn-primary"
              >Get Started</a
            >
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Cover",
  props: { imageUrl: String },
};
</script>
