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
    <!-- #company -->
    <section id="company" class="d-flex justify-content-center p-5">
      <div class="conatiner p-5 mw_1180">
        <div class="row p-5">
          <div id="poster" class="col-6 p-4">
            <img src="./assets/img/exprince.jpg" alt="Picture of game">
          </div>
          <!-- /.col-6 -->
          <div class="col-6">
            <span class="es-succes">12 Year Experience</span>
            <h2>We Are The Best Gaming Company</h2>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt aliquam sed aspernatur non. Nisi corrupti,
              corporis enim omnis odio.</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi quis totam quidem veritatis vero.
            </p>
            <div class="d-flex gap-2">
              <div class="square_check">
                <svg width="1rem" class="svg-inline--fa fa-check m-1" aria-hidden="true" focusable="false"
                  data-prefix="fas" data-icon="check" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                  data-fa-i2svg="">
                  <path fill="currentColor"
                    d="M438.6 105.4C451.1 117.9 451.1 138.1 438.6 150.6L182.6 406.6C170.1 419.1 149.9 419.1 137.4 406.6L9.372 278.6C-3.124 266.1-3.124 245.9 9.372 233.4C21.87 220.9 42.13 220.9 54.63 233.4L159.1 338.7L393.4 105.4C405.9 92.88 426.1 92.88 438.6 105.4H438.6z">
                  </path>
                </svg>
              </div>
              <div>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit, aut!
              </div>
            </div>
          </div>
          <!-- /.col-6 -->
        </div>
        <!-- /.row -->

      </div>
      <!-- /.conatiner -->
    </section>
    <!-- /#company -->










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
