<template>
  <div class="=products">
   <HeaderAllbrands/>
   <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section text-left">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="breadcrumb-text product-more">
                        <router-link to="/"><i class="fa fa-home"></i> Home</router-link>
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
                                <img class="product-big-img" :src="gambar_default" alt="" />
                            </div>
                            <div class="product-thumbs">
                                <carousel :dots="false" :nav="false" class="product-thumbs-track ps-slider">
                                    <div class="pt" @click="changeImage(thumbs[0])" :class="thumbs[0] == gambar_default ? 'active' : ''">
                                        <img src="img/products/tshirt1.jpg" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[1])" :class="thumbs[1] == gambar_default ? 'active' : ''">
                                        <img src="img/products/tshirt2.jpg" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[2])" :class="thumbs[2] == gambar_default ? 'active' : ''">
                                        <img src="img/products/tshirt4.jpg" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[3])" :class="thumbs[3] == gambar_default ? 'active' : ''">
                                        <img src="img/products/tshirt3.jpg" alt="" />
                                    </div>

                                </carousel>
                            </div>
                        </div>
                        <div class="col-lg-6">
                            <div class="product-details text-left">
                                <div class="pd-title">
                                    <span>Clothing</span>
                                    <h3>Printed T-shirt Stradivarius</h3>
                                </div>
                                <div class="pd-desc">
                                    <p>
                                        Material: Cotton Combed 30S
                                    </p>
                                    <p>
                                        Color: Stone, Ecru, White
                                    </p>
                                    <p>
                                        Size: XS-S-M-L-XL
                                    </p>
                                    <p>
                                        Chart:
                                    </p>
                                    <p>
                                        XS = 82 Chest, 62 Waist, 90 Hip
                                    </p>
                                    <p>
                                        S = 86 Chest, 66 Waist, 94 Hip
                                    </p>
                                    <p>
                                        M = 90 Chest, 70 Waist, 98 Hip
                                    </p>
                                    <p>
                                        L = 96 Chest, 76 Waist, 104 Hip
                                    </p>
                                    <p>
                                       XL = 100 Chest, 80 Waist, 108 Hip
                                    </p>
                                    <br>
                                    <h4>IDR 100.000
                                        <span>IDR 139.900</span></h4>
                                </div>
                                <div class="quantity">
                                    <router-link to="/cart" class="primary-btn pd-cart">Add To Cart</router-link>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Product Shop Section End -->

    <RelatedProduct/>
   <Footer/>
  </div>
</template>


<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderAllbrands from '@/components/HeaderAllbrands.vue'
import Footer from '@/components/Footer.vue'
import RelatedProduct from '@/components/RelatedProduct.vue'
import carousel from 'vue-owl-carousel'



export default {
  name: 'Products',
  components: {
    HeaderAllbrands,
    RelatedProduct,
    Footer,
    carousel
  },
  data() {
      return {
          gambar_default: "img/tshirt1.jpg",
          thumbs: [
              "img/tshirt1.jpg",
              "img/tshirt2.jpg",
              "img/tshirt4.jpg",
              "img/tshirt3.jpg"
          ]
      }
  },
  methods: {
      changeImage(urlImage){
          this.gambar_default = urlImage;
      }
  }
};
</script>

<style scoped>
    .product-pic-zoom {
        margin-bottom: 10px;
        position: relative;
        z-index: 1;
    }

    .product-pic-zoom img {
        min-width: 70%;
        height: 450px;
    }

    .product-pic-zoom .zoom-icon {
        position: absolute;
        right: 20px;
        top: 20px;
    }

    .product-pic-zoom .zoom-icon i {
        color: #4c4c4c;
        font-size: 14px;
        width: 40px;
        height: 40px;
        border: 1px solid #d7d7d7;
        text-align: center;
        border-radius: 50%;
        line-height: 37px;
    }
    .product-thumbs .pt {
        margin-right: 14px;
    }
    .product-details .pd-title h3{
        margin-bottom: 30px;
    }
</style>
