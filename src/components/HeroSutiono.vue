<template>
  <!-- Hero Section Begin -->
  <section class="hero-section">
    <carousel class="hero-items" :items="1" :nav="false">
      <div class="single-hero-items set-bg" style="background-image: url('img/hero-1.jpg')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>Selamat datang di Store kami</span>
              <h1>Diskon 50%</h1>
              <p>Belanja produk terlaris dan terlengkap dari store kami, nikmati juga promo gratis ongkos kirim ke semua indonesia. </p>
              <a href="#" class="primary-btn">Mulai Belanja</a>
            </div>
          </div>
        </div>
      </div>
      <div class="single-hero-items set-bg" style="background-image: url('img/hero-2.jpg')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>Selamat datang di Store kami</span>
              <h1>Diskon 50%</h1>
              <p>Belanja produk terlaris dan terlengkap dari store kami, nikmati juga promo gratis ongkos kirim ke semua indonesia.</p>
               <a href="#" class="primary-btn">Mulai Belanja</a>
            </div>
          </div>
        </div>
      </div>
      <div class="single-hero-items set-bg" style="background-image: url('img/hero-3.jpg')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>Selamat datang di Store kami</span>
              <h1>Diskon 50%</h1>
              <p>Belanja produk terlaris dan terlengkap dari store kami, nikmati juga promo gratis ongkos kirim ke semua indonesia.</p>
                <a href="#" class="primary-btn">Mulai Belanja</a>
            </div>
          </div>
        </div>
      </div>
    </carousel>
  </section>
  <!-- Hero Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "HeroSutiono",
  components: {
    carousel,
  },
};
</script>
