<template>
  <section class="interview__section">
    <div class="container">
      <div class="news__head">
        <h3>MediaFayl</h3>
        <div class="tab">
          <button
            class="tablinks"
            id="londonbtn"
            onclick="openCity(event, 'London')"
          >
            FotoGaleriya
          </button>
          <button
            class="tablinks"
            id="parisbtn"
            onclick="openCity(event, 'Paris')"
          >
            VideoGaleriya
          </button>
        </div>
      </div>

      <!-- Tab content -->
      <div id="London" class="tabcontent">
        <div class="row interview_m__row">
          <div class="col-7 ml-0">
            <a class="interview_col_7_textpart btn">
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
              <h4>
                Olimjon Hikmatov: "Asosiy vazifa - Osiyo o‘yinlariga kuchli
                tarkib bilan borish!"
              </h4>
            </a>
          </div>
          <div class="col-5 mr-0">
            <div class="row">
              <a class="interview_row__one btn">
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4>
                  Shuhrat Salayev: "Keyingi yilgi "Turkish Open" musobaqasida
                  oltin medal olishni maqsad qildim"
                </h4>
              </a>
              <a class="interview_row__two btn">
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4>Komiljon To'xtayev: "Oson emas! Juda qiyin bo'ldi"</h4>
              </a>
            </div>
          </div>
        </div>
      </div>

      <div id="Paris" class="tabcontent">
        <div class="row interview_m__row">
          <div class="col-7 ml-0">
            <a class="interview_col_7_textpart media__video_content__one btn">
              <p><i class="lnr lnr-history"></i> 15 Yanvar 2022</p>
              <h4>
                MOQ rahbarining muvaffaqiyatli urinishi Oʻzbekiston
                chempionatini ochib berdi"
              </h4>
            </a>
          </div>
          <div class="col-5 mr-0">
            <div class="row">
              <a class="interview_row__one media__video_content__two btn">
                <p><i class="lnr lnr-history"></i> 31 Mart 2022</p>
                <h4>"Save Aral" endi Toshkentda!</h4>
              </a>
              <a class="interview_row__two media__video_content__three btn">
                <p><i class="lnr lnr-history"></i> 5 Iyun 2022</p>
                <h4>
                  Yugurish bo'yicha O'zbekistonga kirib kelayotgan Jahon sporti
                  !
                </h4>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "MediaFile",
  mounted() {
    let paris__btn = document.getElementById("parisbtn");
    console.log(paris__btn);
    let paris__content = document.getElementById("Paris");
    paris__btn.className += " active";
    paris__content.className += " d-block";
  },
};
</script>

<style scoped></style>
