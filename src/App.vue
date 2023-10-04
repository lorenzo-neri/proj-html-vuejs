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
  <main class="bg-danger">
    <div class="container p-5 position-relative">
      <div class="row p-5">
        <div class="col p-5 text-center">
          MAIN
        </div>
        <!-- /.col -->
      </div>
      <!-- /.row -->

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
    <!-- /.container -->

  </main>
  <!--######## TEST ########-->


  <AppFooter />
</template>

<style lang="scss" scoped></style>
