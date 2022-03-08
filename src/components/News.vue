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
              <div class="carousel-item active news__slide">
                <img src="./../../public/images/news/n1.jpg" alt="" />
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4>
                  Aziz ayollar, muhtaram opa-singillar, bayramingiz muborak
                  bo‘lsin!
                </h4>
                <figcaption>
                  O‘zbekiston Milliy Olimpiya qo‘mitasi Sizlarni 8 mart –
                  Xalqaro xotin-qizlar kuni
                </figcaption>
              </div>

              <div class="carousel-item news__slide">
                <img src="./../../public/images/news/n3.jpg" alt="" />
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4>
                  Suvga sakrash. Hamyurtlarimiz Yevrosiyo kubogida sovrindor
                  bo‘lishdi
                </h4>
                <figcaption>
                  Suvga sakrash bo‘yicha O‘zbekiston terma jamoasi a’zolari
                  birinchi bor tashkil
                </figcaption>
              </div>
              <div class="carousel-item news__slide">
                <img src="./../../public/images/news/n2.jpg" alt="" />
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4>
                  Sportni rivojlantirish vaziri O‘zbekiston dzyudo
                  federatsiyasiga tashrif buyurdi
                </h4>
                <figcaption>
                  Sportni rivojlantirish vaziri Adham Ikramov O‘zbekiston dzyudo
                  federatsiyasida bo‘lib, u
                </figcaption>
              </div>
            </div>
            <div class="btns__box">
              <button
                class="carousel-control-prev btn btn-outline-primary"
                type="button"
                data-bs-target="#carouselExampleControls"
                data-bs-slide="prev"
              >
                <span
                  class="carousel-control-prev-icon"
                  aria-hidden="true"
                ></span>
              </button>
              <div class="slider_counter">
                <span class="first__count">2 /</span>
                <span class="overall__count">3</span>
              </div>
              <button
                class="carousel-control-next btn btn-outline-primary"
                type="button"
                data-bs-target="#carouselExampleControls"
                data-bs-slide="next"
              >
                <span
                  class="carousel-control-next-icon"
                  aria-hidden="true"
                ></span>
              </button>
            </div>
          </div>

          <div class="news__slider"></div>
        </div>
        <div class="col-6"></div>
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
