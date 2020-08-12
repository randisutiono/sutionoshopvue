<template>
  <!-- Partner Logo Section Begin -->
  <div class="partner-logo">
    <div class="container">
      <carousel
        class="logo-carousel"
        :loop="true"
        :autoplay="true"
        :items="5"
        :dots="false"
        :nav="false"
      >
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/img-1.png" />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/img-2.png" alt />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/img-3.png" alt />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/img-4.png" alt />
          </div>
        </div>
        <div class="logo-item">
          <div class="tablecell-inner">
            <img src="img/logo-carousel/img-5.png" alt />
          </div>
        </div>
      </carousel>
    </div>
  </div>
  <!-- Partner Logo Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "LogoPartnerSutiono",
  components: {
    carousel,
  },
};
</script>