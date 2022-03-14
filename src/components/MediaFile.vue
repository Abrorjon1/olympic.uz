<template>
  <section class="interview__section">
    <div class="container">
      <div class="news__head">
        <h3>MediaFayl</h3>
        <div class="tab">
          <button
            :class="{ active: show == false }"
            @click="show = false"
            class="tablinks"
            id="londonbtn"
          >
            FotoGaleriya
          </button>
          <button
            :class="{ active: show == true }"
            @click="show = true"
            class="tablinks"
            id="parisbtn"
          >
            VideoGaleriya
          </button>
        </div>
      </div>

      <!-- Tab content -->

      <div v-if="show == false" id="London" class="tabcontent">
        <div class="row interview_m__row">
          <div class="col-12 col-lg-7 ml-0">
            <a class="interview_col_7_textpart btn">
              <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
              <h4 class="text-truncate">
                Olimjon Hikmatov: "Asosiy vazifa - Osiyo o‘yinlariga kuchli
                tarkib bilan borish!"
              </h4>
            </a>
          </div>
          <div class="col-12 col-lg-5 mr-0">
            <div class="row">
              <a class="interview_row__one col-12 col-sm-6 col-lg-12 btn">
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4 class="text-truncate">
                  Shuhrat Salayev: "Keyingi yilgi "Turkish Open" musobaqasida
                  oltin medal olishni maqsad qildim"
                </h4>
              </a>
              <a class="interview_row__two col-12 col-sm-6 col-lg-12 btn">
                <p><i class="lnr lnr-history"></i> 2 Mart 2022</p>
                <h4 class="text-truncate">
                  Komiljon To'xtayev: "Oson emas! Juda qiyin bo'ldi"
                </h4>
              </a>
            </div>
          </div>
        </div>
      </div>
      <div v-else id="Paris" class="tabcontent">
        <div class="row interview_m__row">
          <div class="col-12 col-lg-7 ml-0">
            <a class="interview_col_7_textpart media__video_content__one btn">
              <p><i class="lnr lnr-history"></i> 15 Yanvar 2022</p>
              <h4 class="text-truncate">
                MOQ rahbarining muvaffaqiyatli urinishi Oʻzbekiston
                chempionatini ochib berdi"
              </h4>
            </a>
          </div>
          <div class="col-12 col-lg-5 mr-0">
            <div class="row">
              <a
                class="interview_row__one media__video_content__two col-12 col-sm-6 col-lg-12 btn"
              >
                <p><i class="lnr lnr-history"></i> 31 Mart 2022</p>
                <h4 class="text-truncate">"Save Aral" endi Toshkentda!</h4>
              </a>
              <a
                class="interview_row__two media__video_content__three col-12 col-sm-6 col-lg-12 btn"
              >
                <p><i class="lnr lnr-history"></i> 5 Iyun 2022</p>
                <h4 class="text-truncate">
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
  data() {
    return {
      show: true,
    };
  },
  // mounted() {
  //   let paris__btn = document.getElementById("parisbtn");
  //   console.log(paris__btn);
  //   let paris__content = document.getElementById("Paris");
  //   paris__btn.className += " active";
  //   paris__content.className += " d-block";
  // },
};
</script>

<style scoped></style>
