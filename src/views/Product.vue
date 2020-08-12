<template>
  <div class="product">
    <HeaderSutiono />
    <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section text-left">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="breadcrumb-text product-more">
              <router-link to="/">
                <i class="fa fa-home"></i> Home
              </router-link>
              <span>Detail</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Breadcrumb Section Begin -->

    <!-- Product Shop Section Begin -->
    <section class="product-shop spad page-details">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="row">
              <div class="col-lg-6">
                <div class="product-pic-zoom">
                  <img class="product-big-img" :src="gambar_awal" alt />
                </div>
                <div class="product-thumbs">
                  <carousel
                    class="product-thumbs-track ps-slider"
                    :dots="false"
                    :nav="false"
                  >
                    <div class="pt" @click="changeImage(thumbs[0])" :class="thumbs[0] == gambar_awal ? 'active' : '' ">
                      <img src="img/gambar1.jpg" alt />
                    </div>

                    <div class="pt" @click="changeImage(thumbs[1])" :class="thumbs[1] == gambar_awal ? 'active' : '' ">
                      <img src="img/gambar2.jpg" alt />
                    </div>

                    <div class="pt" @click="changeImage(thumbs[2])" :class="thumbs[2] == gambar_awal ? 'active' : '' ">
                      <img src="img/gambar3.jpg" alt />
                    </div>
                  </carousel>
                </div>
              </div>
              <div class="col-lg-6">
                <div class="product-details text-left">
                  <div class="pd-title">
                    <span>blue</span>
                    <h3>Jaket MRDE.CO</h3>
                  </div>
                  <div class="pd-desc">
                    <p>Ini adalah jaket terbaru dari merek kami dan barang sangat nyaman dipakai.</p>
                    <p>Kami merekomendasikan produk ini sangat bagus dan paling diminati di store kami.</p>
                    <h4>Rp.150000,-</h4>
                  </div>
                  <div class="quantity">
                    <router-link to="/cart"><a href="shopping-cart.html" class="primary-btn pd-cart">Beli Sekarang</a></router-link>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Product Shop Section End -->
    <ProdukTersediaSutiono />
    <FooterSutiono />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSutiono from "@/components/HeaderSutiono.vue";
import FooterSutiono from "@/components/FooterSutiono.vue";
import ProdukTersediaSutiono from "@/components/ProdukTersediaSutiono.vue";

import carousel from "vue-owl-carousel";

export default {
  name: "Product",
  components: {
    HeaderSutiono,
    FooterSutiono,
    ProdukTersediaSutiono,
    carousel,
  },
  data() {
      return {
          gambar_awal: "img/gambar1.jpg",
          thumbs: [
              "img/gambar1.jpg",
              "img/gambar2.jpg",
              "img/gambar3.jpg"
          ]
      }
  },
  methods: {
      changeImage(urlImage) {
          this.gambar_awal = urlImage;
      }
  }
};
</script>

<style scoped>
.product-thumbs .pt {
  margin-right: 14px;
}
</style>
