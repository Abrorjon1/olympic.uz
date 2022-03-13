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
        <div class="col-8 align-items-center d-flex">
          <div class="olympic_links__box row">
            <div class="olympic_links_above__box">
              <ul>
                <li>
                  <a href="#"
                    ><i class="fas fa-headset"></i>
                    <span>Virtual Qabulxona</span></a
                  >
                </li>
                <li>
                  <a href="#"
                    ><i class="fas fa-volume-up"></i> <span>E'lonlar</span></a
                  >
                </li>
                <li>
                  <a href="#"
                    ><i class="fas fa-image"></i>
                    <span>Mediya Galeriya</span></a
                  >
                </li>
                <li>
                  <a
                    type="button"
                    href="#"
                    data-toggle="modal"
                    data-target="#exampleModal"
                    ><i class="fas fa-search"></i> <span>Izlash</span></a
                  >
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
                  <a class="active last" href="#">O'zbekcha</a>
                </li>
              </ul>
            </div>
            <hr />
            <div class="olympic_links_bottom__box">
              <a
                class="hamburger__btn"
                data-bs-toggle="offcanvas"
                href="#offcanvasExample"
                role="button"
                aria-controls="offcanvasExample"
              >
                <i class="fas fa-bars"></i>
              </a>
              <div
                class="offcanvas offcanvas-start"
                tabindex="-1"
                id="offcanvasExample"
                aria-labelledby="offcanvasExampleLabel"
              >
                <div class="offcanvas-header">
                  <div class="row">
                    <ul class="canvas-header">
                      <li><a class="canvas__links" href="#">Ру</a></li>
                      <li><a class="canvas__links" href="#">Ўз</a></li>
                      <li><a class="canvas__links" href="#">Eng</a></li>
                    </ul>
                    <a class="xmark__btn" data-bs-dismiss="offcanvas"
                      ><i class="lnr lnr-cross"></i
                    ></a>
                  </div>
                  <a class="offcanvas-title" id="offcanvasExampleLabel">
                    Menyu
                  </a>
                </div>
                <div class="offcanvas-body">
                  <ul>
                    <li>
                      <a href="#"
                        >O'zbekiston MOQ <i class="lnr lnr-chevron-right"></i
                      ></a>
                    </li>
                    <li>
                      <a href="#"
                        >Yangiliklar <i class="lnr lnr-chevron-right"></i
                      ></a>
                    </li>
                    <li>
                      <a href="#"
                        >Federatsiyalar <i class="lnr lnr-chevron-right"></i
                      ></a>
                    </li>
                    <li>
                      <a href="#"
                        >O'yinlar <i class="lnr lnr-chevron-right"></i
                      ></a>
                    </li>
                    <li>
                      <a href="#"
                        >Jahon Arenasi <i class="lnr lnr-chevron-right"></i
                      ></a>
                    </li>
                  </ul>
                </div>
              </div>
              <ul>
                <li class="dropdown">
                  <button class="dropbtn">
                    O'zbekiston MOQ <i class="fas fa-chevron-down"></i>
                  </button>
                  <div class="dropdown-content">
                    <a href="#">Link 1</a>
                    <a href="#">Link 2</a>
                    <a href="#">Link 3</a>
                  </div>
                </li>
                <li class="dropdown">
                  <button class="dropbtn">
                    Yangiliklar <i class="fas fa-chevron-down"></i>
                  </button>
                  <div class="dropdown-content">
                    <a href="#">Link 1</a>
                    <a href="#">Link 2</a>
                    <a href="#">Link 3</a>
                  </div>
                </li>
                <li class="dropdown">
                  <button class="dropbtn">
                    Federatsiyalar <i class="fas fa-chevron-down"></i>
                  </button>
                  <div class="dropdown-content">
                    <a href="#">Link 1</a>
                    <a href="#">Link 2</a>
                    <a href="#">Link 3</a>
                  </div>
                </li>
                <li class="dropdown">
                  <button class="dropbtn">
                    O'yinlar <i class="fas fa-chevron-down"></i>
                  </button>
                  <div class="dropdown-content">
                    <a href="#">Link 1</a>
                    <a href="#">Link 2</a>
                    <a href="#">Link 3</a>
                  </div>
                </li>
                <li class="dropdown">
                  <button class="dropbtn">
                    Jahon <i class="fas fa-chevron-down"></i>
                  </button>
                  <div class="dropdown-content db_content__last">
                    <a href="#">Link 1</a>
                    <a href="#">Link 2</a>
                    <a href="#">Link 3</a>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
  <!-- Modal Search  -->
  <div
    class="modal fade"
    id="exampleModal"
    tabindex="-1"
    role="dialog"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-body">
          <form>
            <input type="text" placeholder="Search..." />
            <button class="btn" type="submit">
              <i class="fas fa-search"></i>
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped></style>
