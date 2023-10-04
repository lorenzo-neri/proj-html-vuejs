<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';

export default {

  name: 'App',
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppFooter,
  }

}
</script>

<template>
  <AppHeader />

  <!--######## TEST ########-->
  <main class="text-white">

    <!-- #company################ -->
    <section id="company" class="d-flex justify-content-center pt-5">
      <div class="conatiner p-5 mw_1180">
        <div class="row py-5 px-2">
          <div id="poster" class="col-6 p-4">
            <img src="./assets/img/exprince.jpg" alt="Picture of game">
          </div>
          <!-- /.col-6 -->
          <div class="col-6">
            <span class="es-succes fs_10">12 Year Experience</span>
            <h2 class="fw-bold pt-1 pb-2">We Are The Best Gaming Company</h2>
            <p class="fs_10">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt aliquam sed aspernatur non.
              Nisi corrupti,
              corporis enim omnis odio.
              Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
            <p class="fs_10">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi quis totam quidem veritatis vero.
            </p>

            <!-- sqaure check -->
            <div v-for="i in 4" class="d-flex gap-2 align-items-center py-1">
              <div class="square_check">
                <svg width="1rem" class="svg-inline--fa fa-check m-1" aria-hidden="true" focusable="false"
                  data-prefix="fas" data-icon="check" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                  data-fa-i2svg="">
                  <path fill="currentColor"
                    d="M438.6 105.4C451.1 117.9 451.1 138.1 438.6 150.6L182.6 406.6C170.1 419.1 149.9 419.1 137.4 406.6L9.372 278.6C-3.124 266.1-3.124 245.9 9.372 233.4C21.87 220.9 42.13 220.9 54.63 233.4L159.1 338.7L393.4 105.4C405.9 92.88 426.1 92.88 438.6 105.4H438.6z">
                  </path>
                </svg>
              </div>
              <div class="fs_10 fw-bolder">
                Lorem ipsum dolor sit amet consectetur adipisicing elite.
              </div>
            </div>
            <!-- sqaure check -->

            <div class="col d-flex justify-content-start align-items-center">
              <a class="btn es_button d-flex justify-content-center align-items-center" href="##">
                Discover More
                <svg width="1rem" class="svg-inline--fa fa-right-long ps-1" aria-hidden="true" focusable="false"
                  data-prefix="fas" data-icon="right-long" role="img" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 512 512">
                  <path fill="currentColor"
                    d="M504.3 273.6l-112.1 104c-6.992 6.484-17.18 8.218-25.94 4.406c-8.758-3.812-14.42-12.45-14.42-21.1L351.9 288H32C14.33 288 .0002 273.7 .0002 255.1S14.33 224 32 224h319.9l0-72c0-9.547 5.66-18.19 14.42-22c8.754-3.809 18.95-2.075 25.94 4.41l112.1 104C514.6 247.9 514.6 264.1 504.3 273.6z">
                  </path>
                </svg>
              </a>

              <a style="padding: 2rem; scale: .7;"
                class="btn es_button d-flex align-items-center justify-content-center rounded-circle" href="###">
                <svg width="1rem" class="svg-inline--fa fa-play" aria-hidden="true" focusable="false" data-prefix="fas"
                  data-icon="play" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
                  <path fill="currentColor"
                    d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z">
                  </path>
                </svg>
              </a>
            </div>
            <!-- /buttons -->

          </div>
          <!-- /.col-6 -->
        </div>
        <!-- /.row -->

      </div>
      <!-- /.conatiner -->
    </section>

    <!-- /#company################ -->

    <!-- #arena################# -->

    <section id="arena" class="d-flex justify-content-center">
      <div class="container p-5 mw_1180">
        <div class="row py-5 px-2 align-items-center">

          <div class="col mx-3">
            <span class="es-succes fs_10">Our Extrem Feature</span>
            <h2 class="fw-bold pt-1 pb-2">The Best Gaming Arena On The World!</h2>
            <p class="fs_10">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt aliquam sed aspernatur non.
              Nisi corrupti,
              corporis enim omnis odio.
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Lorem ipsum dolor sit amet, consectetur
              adipisicing elit.</p>
          </div>
          <!-- /.col-6 -->

          <!-- CARD -->
          <div class="col mx-3">
            <div class="row">
              <div class="col-6 p-2">
                <div class="card green_card d-flex flex-column align-items-center text-center">
                  <div class="circle">
                    <img src="./assets/img/feature1.png" alt="">
                  </div>
                  <h6 class="p-0 fw-bolder">Live Streaming</h6>
                  <div class="fs_10">Lorem ipsum dolor sit amet consectetur.</div>
                </div>
              </div>
              <!-- /.col-6 -->
              <div class="col-6 p-2">
                <div class="card dark_card d-flex flex-column align-items-center text-center">
                  <div class="circle">
                    <img src="./assets/img/feature2.png" alt="">
                  </div>
                  <h6 class="p-0 fw-bolder">Gaming News</h6>
                  <div class="fs_10">Lorem ipsum dolor sit amet consectetur.</div>
                </div>
              </div>
              <!-- /.col-6 -->
              <div class="col-6 p-2">
                <div class="card dark_card d-flex flex-column align-items-center text-center">
                  <div class="circle">
                    <img src="./assets/img/feature3.png" alt="">
                  </div>
                  <h6 class="p-0 fw-bolder">Great Tournament</h6>
                  <div class="fs_10">Lorem ipsum dolor sit amet consectetur.</div>
                </div>
              </div>
              <!-- /.col-6 -->
              <div class="col-6 p-2">
                <div class="card green_card d-flex flex-column align-items-center text-center">
                  <div class="circle">
                    <img src="./assets/img/feature4.png" alt="">
                  </div>
                  <h6 class="p-0 fw-bolder">Awward Ceremony</h6>
                  <div class="fs_10">Lorem ipsum dolor sit amet consectetur.</div>
                </div>
              </div>
              <!-- /.col-6 -->
            </div>
          </div>
          <!-- /.col-6 -->
          <!-- /CARD -->

        </div>
        <!-- /.row -->

      </div>
      <!-- /.container -->

    </section>

    <!-- /#arena################# -->












    <div class="container position-relative">
      <div class="row">
        <div class="col d-flex justify-content-center">
          <div id="test" class="d-flex justify-content-center text-white align-items-center">
            form
          </div>
        </div>
        <!-- /.col -->
      </div>
      <!-- /.row -->
    </div>
  </main>
  <!--######## TEST ########-->


  <AppFooter />
</template>

<style lang="scss" scoped></style>
