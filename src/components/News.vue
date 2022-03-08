<template>
  <section class="news__section">
    <div class="container">
      <div class="news__head">
        <h3>Yangilikalar</h3>
        <button class="btn btn-outline-primary">Barcha yangilikalar</button>
      </div>
      <div class="row">
        <div class="col-6">
          <div class="news__slider">
            <div class="news__slide">
              <img src="./../../public/images/news/n1.jpg" alt="" />
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
              <h4>
                Aziz ayollar, muhtaram opa-singillar, bayramingiz muborak
                bo‘lsin!
              </h4>
              <figcaption>
                O‘zbekiston Milliy Olimpiya qo‘mitasi Sizlarni 8 mart – Xalqaro
                xotin-qizlar kuni
              </figcaption>
              <div class="slider_counter">
                <span class="first__count">1/ </span>
                <span class="overall__count">3</span>
              </div>
            </div>
          </div>
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
