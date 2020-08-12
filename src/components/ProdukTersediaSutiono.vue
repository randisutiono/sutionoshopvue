<template>
  <!-- Related Products Section End -->
  <div class="related-products spad">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="section-title">
            <h2>Produk Tersedia Lainnya</h2>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/products/produk1.jpg" alt />
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
              <div class="catagory-name">Jaket Hame</div>
              <a href="#">
                <h5>Semiparka Wolv</h5>
              </a>
              <div class="product-price">
                Rp.350000,-
                <span>Rp.250000,-</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/products/produk2.jpg" alt />
              <ul>
                <li class="w-icon active">
                  <a href="#">
                    <i class="icon_bag_alt"></i>
                  </a>
                </li>
                <li class="quick-view">
                  <a href="#">+ Lihat Detail</a>
                </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">Jaket Levis</div>
              <a href="#">
                <h5>Rompi Jeans Bioblitz</h5>
              </a>
              <div class="product-price">Rp.300000,-</div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/products/produk3.jpg" alt />
              <ul>
                <li class="w-icon active">
                  <a href="#">
                    <i class="icon_bag_alt"></i>
                  </a>
                </li>
                <li class="quick-view">
                  <a href="#">+ Lihat Detail</a>
                </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">Jaket Anti Air</div>
              <a href="#">
                <h5>SwakOrs Jaket</h5>
              </a>
              <div class="product-price">Rp.200000,-</div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/products/produk4.jpg" alt />
              <ul>
                <li class="w-icon active">
                  <a href="#">
                    <i class="icon_bag_alt"></i>
                  </a>
                </li>
                <li class="quick-view">
                  <a href="#">+ Lihat Detail</a>
                </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">Jaket Keren</div>
              <a href="#">
                <h5>Jaket Volkert</h5>
              </a>
              <div class="product-price">Rp.400000,-</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Related Products Section End -->
</template>

<script>
export default {
  name: "ProdukTersediaSutiono",
};
</script>
