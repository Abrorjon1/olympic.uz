<template>
  <section class="news__section">
    <div class="container">
      <div class="news__head">
        <h3>Yangilikalar</h3>
        <button class="btn btn-outline-primary">Barcha yangilikalar</button>
      </div>
      <div class="row">
        <div class="col-6">
          <div
            id="carouselExampleControls"
            class="carousel slide carousel-fade"
            data-bs-ride="carousel"
          >
            <div class="carousel-inner">
              <div class="carousel-item active news__slide" data-id="1">
                <img src="./../../public/images/news/n1.jpg" />
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4>
                  Aziz ayollar, muhtaram opa-singillar, bayramingiz muborak
                  bo‘lsin!
                </h4>
                <figcaption>
                  O‘zbekiston Milliy Olimpiya qo‘mitasi Sizlarni 8 mart –
                  Xalqaro xotin-qizlar kuni
                </figcaption>
                <span class="img__id">1</span>
              </div>

              <div class="carousel-item news__slide" data-id="2">
                <img src="./../../public/images/news/n3.jpg" />
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4>
                  Suvga sakrash. Hamyurtlarimiz Yevrosiyo kubogida sovrindor
                  bo‘lishdi
                </h4>
                <figcaption>
                  Suvga sakrash bo‘yicha O‘zbekiston terma jamoasi a’zolari
                  birinchi bor tashkil
                </figcaption>
                <span class="img__id">2</span>
              </div>
              <div class="carousel-item news__slide" data-id="3">
                <img src="./../../public/images/news/n2.jpg" />
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4>
                  Sportni rivojlantirish vaziri O‘zbekiston dzyudo
                  federatsiyasiga tashrif buyurdi
                </h4>
                <figcaption>
                  Sportni rivojlantirish vaziri Adham Ikramov O‘zbekiston dzyudo
                  federatsiyasida bo‘lib, u
                </figcaption>
                <span class="img__id">3</span>
              </div>
            </div>
            <div class="btns__box">
              <button
                @click="btn_func(event)"
                class="carousel-control-prev"
                type="button"
                id="cc__btns"
                data-bs-target="#carouselExampleControls"
                data-bs-slide="prev"
              >
                <i class="fas fa-chevron-left"></i>
              </button>
              <div class="slider_counter">
                <span class="first__count">1 /</span>
                <span class="overall__count">3</span>
              </div>
              <button
                @click="btn_func(event)"
                class="carousel-control-next"
                type="button"
                data-bs-target="#carouselExampleControls"
                data-bs-slide="next"
                id="cc__btns"
              >
                <i class="fas fa-chevron-right"></i>
              </button>
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="row">
            <div class="col-4">
              <img src="./../../public/images/news/n1.jpg" alt="" />
            </div>
            <div class="col-8 news_col__8">
              <h5>
                Sportni rivojlantirish vaziri O‘zbekiston dzyudo federatsiyasiga
                tashrif buyurdi
              </h5>
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
            </div>
          </div>
          <hr />
          <div class="row">
            <div class="col-4">
              <img src="./../../public/images/news/n2.jpg" alt="" />
            </div>
            <div class="col-8 news_col__8">
              <h5>
                Sportni rivojlantirish vaziri O‘zbekiston dzyudo federatsiyasiga
                tashrif buyurdi
              </h5>
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
            </div>
          </div>
          <hr />
          <div class="row">
            <div class="col-4">
              <img src="./../../public/images/news/n3.jpg" alt="" />
            </div>
            <div class="col-8 news_col__8">
              <h5>
                Sportni rivojlantirish vaziri O‘zbekiston dzyudo federatsiyasiga
                tashrif buyurdi
              </h5>
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
            </div>
          </div>
          <hr />
          <div class="row">
            <div class="col-4">
              <img src="./../../public/images/news/n4.jpg" alt="" />
            </div>
            <div class="col-8 news_col__8">
              <h5>
                Sportni rivojlantirish vaziri O‘zbekiston dzyudo federatsiyasiga
                tashrif buyurdi
              </h5>
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
            </div>
          </div>
        </div>
      </div>
      <!-- <swiper ref="mySwiper" :options="swiperOptions">
        <swiper-slide>Slide 1</swiper-slide>
        <swiper-slide>Slide 2</swiper-slide>
        <swiper-slide>Slide 3</swiper-slide>
        <swiper-slide>Slide 4</swiper-slide>
        <swiper-slide>Slide 5</swiper-slide>
        <div class="swiper-pagination" slot="pagination"></div>
      </swiper> -->
    </div>
  </section>
</template>

<script>
// import { Swiper, SwiperSlide, directive } from "vue-awesome-swiper";
// import "swiper/css/swiper.css";

export default {
  name: "News",
  }
</script>

<style scoped></style>
