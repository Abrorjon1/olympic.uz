<template>
  <header class="header">
    <div class="container">
      <div class="row header_row">
        <div class="col-4">
          <div class="olympic_logo__box">
            <div class="row">
              <div class="col-3">
                <a href="#" class="header__brand">
                  <img src="./../../public/images/navbar/logo.png" alt="" />
                </a>
              </div>
              <div class="col-9">
                <h3>O‘zbekiston Milliy Olimpiya Qo‘mitasi</h3>
                <ul>
                  <li><a href="#">CITIUS</a></li>
                  <li><a href="#">CALTIUS</a></li>
                  <li><a href="#">FORTIUS</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="col-8">
          <div class="olympic_links__box">
            <div class="olympic_links_above__box">
              <ul>
                <li>
                  <a href="#"
                    ><i class="fas fa-headset"></i> Virtual Qabulxona</a
                  >
                </li>
                <li>
                  <a href="#"><i class="fas fa-headset"></i> E'lonlar</a>
                </li>
                <li>
                  <a href="#"><i class="fas fa-headset"></i> Mediya Galeriya</a>
                </li>
                <li>
                  <a href="#"><i class="fas fa-search"></i> Izlash</a>
                </li>
              </ul>
              <ul>
                <li>
                  <a href="#"><i class="fas fa-globe"></i> Русский</a>
                </li>
                <li>
                  <a href="#">English</a>
                </li>
                <li>
                  <a href="#">Узбекча</a>
                </li>
                <li>
                  <a class="active" href="#">O'zbekcha</a>
                </li>
              </ul>
            </div>
            <hr />
            <div class="olympic_links_bottom__box">
              <ul>
                <li>O'zbekiston MOQ</li>
                <li>Yangiliklar</li>
                <li>Federatsiyalar</li>
                <li>O'yinlar</li>
                <li>Jahon</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped></style>
