<template>
  <section class="news__section">
    <div class="container">
      <div class="news__head">
        <h3>Yangilikalar</h3>
        <button class="btn btn-outline-primary">Barcha yangilikalar</button>
      </div>
      <div class="row">
        <div class="col-12 col-lg-6">
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
                  Xalqaro xotin-qizlar kuni uchun
                </figcaption>
                <div class="slider_counter abm">
                  <span class="first__count">1 /</span>
                  <span class="overall__count">3</span>
                </div>
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
                <div class="slider_counter">
                  <span class="first__count">2 /</span>
                  <span class="overall__count">3</span>
                </div>
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
                  federatsiyasida bo‘lib
                </figcaption>
                <div class="slider_counter abm">
                  <span class="first__count">3 /</span>
                  <span class="overall__count">3</span>
                </div>
                <span class="img__id">3</span>
              </div>
            </div>
            <div class="btns__box">
              <button
                class="carousel-control-prev"
                type="button"
                id="cc__btns"
                data-bs-target="#carouselExampleControls"
                data-bs-slide="prev"
              >
                <i class="fas fa-chevron-left"></i>
              </button>
              <button
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
        <div class="col-12 col-lg-6">
          <div class="row">
            <div class="col-12 col-sm-4">
              <img src="./../../public/images/news/n1.jpg" alt="" />
            </div>
            <div class="col-12 col-sm-8 news_col__8">
              <h5>
                Sportni rivojlantirish vaziri O‘zbekiston dzyudo federatsiyasiga
                tashrif buyurdi
              </h5>
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
            </div>
          </div>
          <hr />
          <div class="row">
            <div class="col-12 col-sm-4">
              <img src="./../../public/images/news/n2.jpg" alt="" />
            </div>
            <div class="col-12 col-sm-8 news_col__8">
              <h5>
                Sportni rivojlantirish vaziri O‘zbekiston dzyudo federatsiyasiga
                tashrif buyurdi
              </h5>
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
            </div>
          </div>
          <hr />
          <div class="row">
            <div class="col-12 col-sm-4">
              <img src="./../../public/images/news/n3.jpg" alt="" />
            </div>
            <div class="col-12 col-sm-8 news_col__8">
              <h5>
                Sportni rivojlantirish vaziri O‘zbekiston dzyudo federatsiyasiga
                tashrif buyurdi
              </h5>
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
            </div>
          </div>
          <hr />
          <div class="row">
            <div class="col-12 col-sm-4">
              <img src="./../../public/images/news/n4.jpg" alt="" />
            </div>
            <div class="col-12 col-sm-8 news_col__8">
              <h5>
                Sportni rivojlantirish vaziri O‘zbekiston dzyudo federatsiyasiga
                tashrif buyurdi
              </h5>
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "News",
};
</script>

<style scoped></style>
