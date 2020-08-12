<template>
  <!-- Women Banner Section Begin -->
  <section class="women-banner spad">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-12 mt-5">
          <carousel class="product-slider" :items="3" :nav="false" :dots="false" :autoplay="true">
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/gambar1.jpg" />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Lihat Detail</router-link>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Harga</div>
                <a href="#">
                  <h5>Jaket MRDE.CO</h5>
                </a>
                <div class="product-price">
                  Rp.180000,-
                  <span>Rp.150000,-</span>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/gambar2.1.jpg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="#"> Lihat Detail</a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Harga</div>
                <a href="#">
                  <h5>Jaket REBEL IDCLOTH</h5>
                </a>
                <div class="product-price">
                  Rp.250000,-
                  <span>Rp.200000,-</span>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/gambar3.1.jpg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="product.html">+ Lihat Detail</a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Harga</div>
                <a href="#">
                  <h5>Sweater KAMUFLASE</h5>
                </a>
                <div class="product-price">Rp.250000,-</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/gambar4.1.jpg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="product.html">+ Lihat Detail</a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Harga</div>
                <a href="#">
                  <h5>Sweater SUPERDAY</h5>
                </a>
                <div class="product-price">Rp.100000,-</div>
              </div>
            </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
  <!-- Women Banner Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "BannerSutiono",
  components: {
    carousel,
  },
};
</script>

<style scoped>
.product-item {
  margin-right: 25px;
}
.pi-pic img {
  height: 450px;
}
</style>
