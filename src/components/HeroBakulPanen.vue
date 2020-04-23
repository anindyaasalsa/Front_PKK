<template>
     <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">
            <div class="single-hero-items set-bg" style="background-image: url('/img/1slider.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span style="color: #EEEE21">Butuh Produk Pertanian ?</span>
                            <h1>Bakul Panen</h1>
                            <p style="color: #EEEE21">
                                Produk segar hasil pertanian dengan kualitas unggul untuk menjadi primadona andalan
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
             <div class="single-hero-items set-bg" style="background-image: url('/img/2slider.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span style="color: #76BC42">Butuh Produk Pertanian ?</span>
                            <h1>Bakul Panen</h1>
                            <p style="color: #EEEE21">
                                Produk segar hasil pertanian dengan kualitas unggul untuk menjadi primadona andalan
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
             <div class="single-hero-items set-bg" style="background-image: url('/img/3slider.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span style="color: #76BC42">Butuh Produk Pertanian ?</span>
                            <h1>Bakul Panen</h1>
                            <p style="color: #EEEE21">
                                Produk segar hasil pertanian dengan kualitas unggul untuk menjadi primadona andalan
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
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
    name: "HeroBakulPanen",
    components: {
        carousel
    }  
}
</script>

