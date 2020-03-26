<template>
    <!-- Women Banner Section Begin -->
    <section class="women-banner spad">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12 mt-5">
                    <carousel class="product-slider" :items="3"  :dots="false" :nav="false" :autoplay="true">
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/cardi1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Clothing Stradivarius</div>
                                 <router-link to="/Products"><a href="#">
                                    <h5>Drop Shoulder Cardigan Stradivarius</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 350.000
                                    <span>IDR 479.900</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/tshirt1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Clothing Stradivarius</div>
                                 <router-link to="/Products"><a href="#">
                                    <h5>Printed T-shirt Stradivarius</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 100.000
                                    <span>IDR 139.900</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/hoodie1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Clothing Stradivarius</div>
                                 <router-link to="/Products"><a href="#">
                                    <h5>Cropped Sweatshirt Stradivarius</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 370.000
                                    <span>IDR 479.900</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/trainers1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Trainers Bershka</div>
                                 <router-link to="/Products"><a href="#">
                                    <h5>XL Sole Trainers Bershka</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 550.000
                                    <span>IDR 799.900</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/flat1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Mules Berybenka</div>
                                 <router-link to="/Products"><a href="#">
                                    <h5>Cherry Juliette Emblishment Mules Olive</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 189.000
                                    <span>IDR 239.000</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/mules1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Flatshoes Berybenka</div>
                                 <router-link to="/Producst"><a href="#">
                                    <h5>Jennie Juliette Checkered Flats Multi Green</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 150.000
                                    <span>IDR 209.000</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/Handbag1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Handbag Pomelo</div>
                                <router-link to="/Products"><a href="#">
                                    <h5>Rectangle Hand Bag - Blue</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 200.000
                                    <span>IDR 259.000</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/mickey1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Totebag Zara</div>
                                 <router-link to="/Products"><a href="#">
                                    <h5>Mickey Totebag Zara</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 200.000
                                    <span>IDR 299.900</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/Slingbag1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"> <router-link to="/Products">+ Quick View</router-link></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Slingbag Mango</div>
                                 <router-link to="/Products"><a href="#">
                                    <h5>Buckled cross-body bag</h5>
                                </a></router-link>
                                <div class="product-price">
                                    IDR 350.000
                                    <span>IDR 479.000</span>
                                </div>
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
import carousel from 'vue-owl-carousel'

    export default {
        name: 'WomanAllbrands',
        components: {
            carousel
        }
    }
    </script>

    <style scoped>
    .product-item {
        margin-right: 25px;
    }
    .pi-pic img {
        height: 450px;
    }
    </style>