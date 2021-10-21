<template>
  <section class="probootstrap-section">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <carousel :loop="true" :nav="false" :margin="10">
            <div class="item">
              <div
                class="media d-block text-left probootstrap-media p-md-5 p-4"
              >
                <div class="probootstrap-icon mb-3">
                  <span class="oi oi-monitor display-4"></span>
                </div>
                <div class="media-body">
                  <h5 class="mt-0">Web Development</h5>
                  <p>
                    Far far away, behind the word mountains, far from the
                    countries Vokalia and Consonantia, there live the blind
                    texts.
                  </p>
                </div>
              </div>
            </div>

            <div class="item">
              <div
                class="media d-block text-left probootstrap-media p-md-5 p-4"
              >
                <div class="probootstrap-icon mb-3">
                  <span class="oi oi-location display-4"></span>
                </div>
                <div class="media-body">
                  <h5 class="mt-0">Free Bootstrap 4</h5>
                  <p>
                    Far far away, behind the word mountains, far from the
                    countries Vokalia and Consonantia, there live the blind
                    texts.
                  </p>
                </div>
              </div>
            </div>

            <div class="item">
              <div
                class="media d-block text-left probootstrap-media p-md-5 p-4"
              >
                <div class="probootstrap-icon mb-3">
                  <span class="oi oi-person display-4"></span>
                </div>
                <div class="media-body">
                  <h5 class="mt-0">For People Like You</h5>
                  <p>
                    Far far away, behind the word mountains, far from the
                    countries Vokalia and Consonantia, there live the blind
                    texts.
                  </p>
                </div>
              </div>
            </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "CardsCarousel",
  components: { carousel },
};
</script>
