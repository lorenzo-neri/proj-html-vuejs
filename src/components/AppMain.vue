<script>
import PlayButtonCircle from './PlayButtonCircle.vue';

export default {

    name: 'AppMain',
    data() {
        return {

        }
    },
    components: {
        PlayButtonCircle,
    }

}
</script>

<template>
    <main class="text-white">

        <!-- #company################ -->
        <section id="company" class="d-flex justify-content-center pt-5">
            <div class="conatiner py-5 mw_1180">
                <div class="row py-5 px-2">
                    <div id="poster" class="col-6 p-4">
                        <img src="../assets/img/exprince.jpg" alt="Picture of game">
                    </div>
                    <!-- /.col-6 -->
                    <div class="col-6 pt-3">
                        <span class="es-succes fs_10">12 Year Experience</span>
                        <h2 class="fw-bold pt-1 pb-2">We Are The Best Gaming Company</h2>
                        <p class="fs_10">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt aliquam sed
                            aspernatur non.
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
                                    data-prefix="fas" data-icon="check" role="img" xmlns="http://www.w3.org/2000/svg"
                                    viewBox="0 0 448 512" data-fa-i2svg="">
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
                                <svg width="1rem" class="svg-inline--fa fa-right-long ps-1" aria-hidden="true"
                                    focusable="false" data-prefix="fas" data-icon="right-long" role="img"
                                    xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                                    <path fill="currentColor"
                                        d="M504.3 273.6l-112.1 104c-6.992 6.484-17.18 8.218-25.94 4.406c-8.758-3.812-14.42-12.45-14.42-21.1L351.9 288H32C14.33 288 .0002 273.7 .0002 255.1S14.33 224 32 224h319.9l0-72c0-9.547 5.66-18.19 14.42-22c8.754-3.809 18.95-2.075 25.94 4.41l112.1 104C514.6 247.9 514.6 264.1 504.3 273.6z">
                                    </path>
                                </svg>
                            </a>

                            <PlayButtonCircle />
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
            <div class="black_bg">


                <div class="container py-5 mw_1180">
                    <div class="row py-5 px-2 align-items-center">

                        <div class="col mx-3">
                            <span class="es-succes fs_10">Our Extrem Feature</span>
                            <h2 class="fw-bold pt-1 pb-2">The Best Gaming Arena On The World!</h2>
                            <p class="fs_10">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt aliquam sed
                                aspernatur non.
                                Nisi corrupti,
                                corporis enim omnis odio.
                                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Lorem ipsum dolor sit amet,
                                consectetur
                                adipisicing elit.</p>
                        </div>
                        <!-- /.col-6 -->

                        <!-- CARD -->
                        <div class="col mx-3">
                            <div class="row">
                                <div class="col-6 p-2">
                                    <div class="card green_card d-flex flex-column align-items-center text-center">
                                        <div class="circle">
                                            <img src="../assets/img/feature1.png" alt="">
                                        </div>
                                        <h6 class="p-0 fw-bolder">Live Streaming</h6>
                                        <div class="fs_10">Lorem ipsum dolor sit amet consectetur.</div>
                                    </div>
                                </div>
                                <!-- /.col-6 -->
                                <div class="col-6 p-2">
                                    <div class="card dark_card d-flex flex-column align-items-center text-center">
                                        <div class="circle">
                                            <img src="../assets/img/feature2.png" alt="">
                                        </div>
                                        <h6 class="p-0 fw-bolder">Gaming News</h6>
                                        <div class="fs_10">Lorem ipsum dolor sit amet consectetur.</div>
                                    </div>
                                </div>
                                <!-- /.col-6 -->
                                <div class="col-6 p-2">
                                    <div class="card dark_card d-flex flex-column align-items-center text-center">
                                        <div class="circle">
                                            <img src="../assets/img/feature3.png" alt="">
                                        </div>
                                        <h6 class="p-0 fw-bolder">Great Tournament</h6>
                                        <div class="fs_10">Lorem ipsum dolor sit amet consectetur.</div>
                                    </div>
                                </div>
                                <!-- /.col-6 -->
                                <div class="col-6 p-2">
                                    <div class="card green_card d-flex flex-column align-items-center text-center">
                                        <div class="circle">
                                            <img src="../assets/img/feature4.png" alt="">
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
            </div>
        </section>

        <!-- /#arena################# -->

        <!-- #live################# -->

        <section id="live" class="d-flex justify content-center">
            <div class="black_bg">
                <div class="container py-5 mw_1180">
                    <div class="row py-5">
                        <div class="col">
                            <div class="video position-relative">
                                <img src="../assets/img/v-1.png" alt="video">
                                <div id="play_video">
                                    <PlayButtonCircle />
                                    <div style="width: 110%;" class="fs_8">Call of Deauty</div>
                                </div>
                            </div>
                        </div>
                        <!-- /.col -->
                        <div class="col">
                            <span class="es-succes fs_10">Live Streaming</span>

                            <div class="d-flex justify-content-between">
                                <div class="col-9">
                                    <h2 class="fw-bold pt-1 pb-2">Checkout Our Live Streaming</h2>
                                </div>
                                <!-- ARROW -->
                                <div class="col-2 d-flex align-items-end pb-2 justify-content-between">
                                    <div class="circle_icon_light">
                                        <svg width="1rem" class="svg-inline--fa fa-arrow-left-long" aria-hidden="true"
                                            focusable="false" data-prefix="fas" data-icon="arrow-left-long" role="img"
                                            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                            <path fill="currentColor"
                                                d="M9.375 233.4l128-128c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25L109.3 224H480c17.69 0 32 14.31 32 32s-14.31 32-32 32H109.3l73.38 73.38c12.5 12.5 12.5 32.75 0 45.25c-12.49 12.49-32.74 12.51-45.25 0l-128-128C-3.125 266.1-3.125 245.9 9.375 233.4z">
                                            </path>
                                        </svg>
                                    </div>
                                    <div class="circle_icon_light">
                                        <svg width="1rem" class="svg-inline--fa fa-arrow-right-long" aria-hidden="true"
                                            focusable="false" data-prefix="fas" data-icon="arrow-right-long" role="img"
                                            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                            <path fill="currentColor"
                                                d="M502.6 278.6l-128 128c-12.51 12.51-32.76 12.49-45.25 0c-12.5-12.5-12.5-32.75 0-45.25L402.8 288H32C14.31 288 0 273.7 0 255.1S14.31 224 32 224h370.8l-73.38-73.38c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0l128 128C515.1 245.9 515.1 266.1 502.6 278.6z">
                                            </path>
                                        </svg>
                                    </div>
                                </div>
                                <!-- /ARROW -->
                            </div>

                            <div class="d-flex gap-2">
                                <div class="col-6">
                                    <img src="../assets/img/v-small1.png" alt="">
                                    <div class="fw-bolder pt-2">Call of Deauty</div>
                                    <p class="fs_10">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </div>
                                <!-- /.col-6 -->
                                <div class="col-6">
                                    <img src="../assets/img/v-small2.png" alt="">
                                    <div class="fw-bolder pt-2">Doom III</div>
                                    <p class="fs_10">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </div>
                                <!-- /.col-6 -->
                            </div>
                        </div>
                        <!-- /.col -->
                    </div>
                    <!-- /.row -->
                </div>
                <!-- /.container -->
            </div>
        </section>
        <!-- /#live -->

        <!-- /#live################# -->

        <!-- #match################# -->

        <section id="match" class="d-flex justify content-center">
            <div class="container py-5 mw_1180">
                <div class="row py-5 text-center">


                    <div class="card_match col-12 d-flex align-items-center justify-content-between gap-4">
                        <div class="col-6 d-flex py-3 align-items-center justify-content-around">
                            <div class="col-4 p-1">
                                <div class="text-start card">
                                    <img class="p-4" src="../assets/img/t3.png" alt="">
                                    <div class="card-body p-2 py-3 text-white">
                                        <div class="es-succes fs_10 py-1">
                                            Italy
                                        </div>
                                        <h5>
                                            Ninja Gaming
                                        </h5>
                                    </div>
                                </div>
                                <!-- /.card -->
                            </div>
                            <!-- /.col-5 -->
                            <div class="col-3 p-1">
                                <div class="card p-2 py-5">
                                    <h4 class="m-0 es-primary fw-bolder">VS</h4>
                                </div>
                            </div>
                            <!-- /.col-2 -->
                            <div class="col-4 p-1">
                                <div class="text-start card">
                                    <img class="p-4" src="../assets/img/t4.png" alt="">
                                    <div class="card-body p-2 py-3 text-white">
                                        <div class="es-succes fs_10 py-1">
                                            India
                                        </div>
                                        <h5>
                                            Witch Gaming
                                        </h5>
                                    </div>
                                </div>
                                <!-- /.card -->
                            </div>
                            <!-- /.col-5 -->
                        </div>
                        <!-- /.col-6 -->

                        <div class="col-6 d-flex py-3 align-items-center justify-content-start">
                            <div class="col-7 text-start">
                                <h3 class="text-bold">
                                    PUBG Battleground
                                </h3>
                                <p class="fs_10">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex similique, nam
                                    temporibus illum officiis repellat quidem magnam iusto architecto possimus.
                                </p>
                            </div>
                            <!-- /.col-7 -->
                            <div class="col-4">
                                <div class="card special p-3 py-4">
                                    <div class="fs-3">
                                        10:45
                                    </div>
                                    <div class="fs_10">
                                        1st November, 2022
                                    </div>
                                    <div class="icon_card d-flex justify-content-center gap-2 pt-2">
                                        <div class="circle_icon_success">
                                            <svg class="svg-inline--fa fa-youtube p-2" aria-hidden="true" focusable="false"
                                                data-prefix="fab" data-icon="youtube" role="img"
                                                xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
                                                <path fill="currentColor"
                                                    d="M549.7 124.1c-6.281-23.65-24.79-42.28-48.28-48.6C458.8 64 288 64 288 64S117.2 64 74.63 75.49c-23.5 6.322-42 24.95-48.28 48.6-11.41 42.87-11.41 132.3-11.41 132.3s0 89.44 11.41 132.3c6.281 23.65 24.79 41.5 48.28 47.82C117.2 448 288 448 288 448s170.8 0 213.4-11.49c23.5-6.321 42-24.17 48.28-47.82 11.41-42.87 11.41-132.3 11.41-132.3s0-89.44-11.41-132.3zm-317.5 213.5V175.2l142.7 81.21-142.7 81.2z">
                                                </path>
                                            </svg>
                                        </div>
                                        <div class="circle_icon_success">
                                            <svg class="p-2 svg-inline--fa fa-message" aria-hidden="true" focusable="false"
                                                data-prefix="fas" data-icon="message" role="img"
                                                xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                                <path fill="currentColor"
                                                    d="M511.1 63.1v287.1c0 35.25-28.75 63.1-64 63.1h-144l-124.9 93.68c-7.875 5.75-19.12 .0497-19.12-9.7v-83.98h-96c-35.25 0-64-28.75-64-63.1V63.1c0-35.25 28.75-63.1 64-63.1h384C483.2 0 511.1 28.75 511.1 63.1z">
                                                </path>
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <!-- /.col-5 -->
                        </div>
                        <!-- /.col-6 -->
                    </div>
                    <!-- /.card_match -->
                    <div class="card_match col-12 d-flex align-items-center justify-content-between gap-4">
                        <div class="col-6 d-flex py-3 align-items-center justify-content-around">
                            <div class="col-4 p-1">
                                <div class="text-start card">
                                    <img class="p-4" src="../assets/img/t1.png" alt="">
                                    <div class="card-body p-2 py-3 text-white">
                                        <div class="es-succes fs_10 py-1">
                                            Italy
                                        </div>
                                        <h5>
                                            King Gaming
                                        </h5>
                                    </div>
                                </div>
                                <!-- /.card -->
                            </div>
                            <!-- /.col-5 -->
                            <div class="col-3 p-1">
                                <div class="card p-2 py-5">
                                    <h4 class="m-0 es-primary fw-bolder">VS</h4>
                                </div>
                            </div>
                            <!-- /.col-2 -->
                            <div class="col-4 p-1">
                                <div class="text-start card">
                                    <img class="p-4" src="../assets/img/t2.png" alt="">
                                    <div class="card-body p-2 py-3 text-white">
                                        <div class="es-succes fs_10 py-1">
                                            India
                                        </div>
                                        <h5>
                                            Witch Astro
                                        </h5>
                                    </div>
                                </div>
                                <!-- /.card -->
                            </div>
                            <!-- /.col-5 -->
                        </div>
                        <!-- /.col-6 -->

                        <div class="col-6 d-flex py-3 align-items-center justify-content-start">
                            <div class="col-7 text-start">
                                <h3 class="text-bold">
                                    Assasin's Creed
                                </h3>
                                <p class="fs_10">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex similique, nam
                                    temporibus illum officiis repellat quidem magnam iusto architecto possimus.
                                </p>
                            </div>
                            <!-- /.col-7 -->
                            <div class="col-4">
                                <div class="card special p-3 py-4">
                                    <div class="fs-3">
                                        09:45
                                    </div>
                                    <div class="fs_10">
                                        1st November, 2022
                                    </div>
                                    <div class="icon_card d-flex justify-content-center gap-2 pt-2">
                                        <div class="circle_icon_success">
                                            <svg class="svg-inline--fa fa-youtube p-2" aria-hidden="true" focusable="false"
                                                data-prefix="fab" data-icon="youtube" role="img"
                                                xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
                                                <path fill="currentColor"
                                                    d="M549.7 124.1c-6.281-23.65-24.79-42.28-48.28-48.6C458.8 64 288 64 288 64S117.2 64 74.63 75.49c-23.5 6.322-42 24.95-48.28 48.6-11.41 42.87-11.41 132.3-11.41 132.3s0 89.44 11.41 132.3c6.281 23.65 24.79 41.5 48.28 47.82C117.2 448 288 448 288 448s170.8 0 213.4-11.49c23.5-6.321 42-24.17 48.28-47.82 11.41-42.87 11.41-132.3 11.41-132.3s0-89.44-11.41-132.3zm-317.5 213.5V175.2l142.7 81.21-142.7 81.2z">
                                                </path>
                                            </svg>
                                        </div>
                                        <div class="circle_icon_success">
                                            <svg class="p-2 svg-inline--fa fa-message" aria-hidden="true" focusable="false"
                                                data-prefix="fas" data-icon="message" role="img"
                                                xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                                <path fill="currentColor"
                                                    d="M511.1 63.1v287.1c0 35.25-28.75 63.1-64 63.1h-144l-124.9 93.68c-7.875 5.75-19.12 .0497-19.12-9.7v-83.98h-96c-35.25 0-64-28.75-64-63.1V63.1c0-35.25 28.75-63.1 64-63.1h384C483.2 0 511.1 28.75 511.1 63.1z">
                                                </path>
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <!-- /.col-5 -->
                        </div>
                        <!-- /.col-6 -->
                    </div>
                    <!-- /.card_match -->
                    <div class="card_match col-12 d-flex align-items-center justify-content-between gap-4">
                        <div class="col-6 d-flex py-3 align-items-center justify-content-around">
                            <div class="col-4 p-1">
                                <div class="text-start card">
                                    <img class="p-4" src="../assets/img/t5.png" alt="">
                                    <div class="card-body p-2 py-3 text-white">
                                        <div class="es-succes fs_10 py-1">
                                            Italy
                                        </div>
                                        <h5>
                                            Dgn Gaming
                                        </h5>
                                    </div>
                                </div>
                                <!-- /.card -->
                            </div>
                            <!-- /.col-5 -->
                            <div class="col-3 p-1">
                                <div class="card p-2 py-5">
                                    <h4 class="m-0 es-primary fw-bolder">VS</h4>
                                </div>
                            </div>
                            <!-- /.col-2 -->
                            <div class="col-4 p-1">
                                <div class="text-start card">
                                    <img class="p-4" src="../assets/img/t6.png" alt="">
                                    <div class="card-body p-2 py-3 text-white">
                                        <div class="es-succes fs_10 py-1">
                                            India
                                        </div>
                                        <h5>
                                            Joker Gaming
                                        </h5>
                                    </div>
                                </div>
                                <!-- /.card -->
                            </div>
                            <!-- /.col-5 -->
                        </div>
                        <!-- /.col-6 -->

                        <div class="col-6 d-flex py-3 align-items-center justify-content-start">
                            <div class="col-7 text-start">
                                <h3 class="text-bold">
                                    Mortal Combat X
                                </h3>
                                <p class="fs_10">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex similique, nam
                                    temporibus illum officiis repellat quidem magnam iusto architecto possimus.
                                </p>
                            </div>
                            <!-- /.col-7 -->
                            <div class="col-4">
                                <div class="card special p-3 py-4">
                                    <div class="fs-3">
                                        08:45
                                    </div>
                                    <div class="fs_10">
                                        1st November, 2022
                                    </div>
                                    <div class="icon_card d-flex justify-content-center gap-2 pt-2">
                                        <div class="circle_icon_success">
                                            <svg class="svg-inline--fa fa-youtube p-2" aria-hidden="true" focusable="false"
                                                data-prefix="fab" data-icon="youtube" role="img"
                                                xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
                                                <path fill="currentColor"
                                                    d="M549.7 124.1c-6.281-23.65-24.79-42.28-48.28-48.6C458.8 64 288 64 288 64S117.2 64 74.63 75.49c-23.5 6.322-42 24.95-48.28 48.6-11.41 42.87-11.41 132.3-11.41 132.3s0 89.44 11.41 132.3c6.281 23.65 24.79 41.5 48.28 47.82C117.2 448 288 448 288 448s170.8 0 213.4-11.49c23.5-6.321 42-24.17 48.28-47.82 11.41-42.87 11.41-132.3 11.41-132.3s0-89.44-11.41-132.3zm-317.5 213.5V175.2l142.7 81.21-142.7 81.2z">
                                                </path>
                                            </svg>
                                        </div>
                                        <div class="circle_icon_success">
                                            <svg class="p-2 svg-inline--fa fa-message" aria-hidden="true" focusable="false"
                                                data-prefix="fas" data-icon="message" role="img"
                                                xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                                <path fill="currentColor"
                                                    d="M511.1 63.1v287.1c0 35.25-28.75 63.1-64 63.1h-144l-124.9 93.68c-7.875 5.75-19.12 .0497-19.12-9.7v-83.98h-96c-35.25 0-64-28.75-64-63.1V63.1c0-35.25 28.75-63.1 64-63.1h384C483.2 0 511.1 28.75 511.1 63.1z">
                                                </path>
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <!-- /.col-5 -->
                        </div>
                        <!-- /.col-6 -->
                    </div>
                    <!-- /.card_match -->
                    <div class="card_match col-12 d-flex align-items-center justify-content-between gap-4">
                        <div class="col-6 d-flex py-3 align-items-center justify-content-around">
                            <div class="col-4 p-1">
                                <div class="text-start card">
                                    <img class="p-4" src="../assets/img/t7.png" alt="">
                                    <div class="card-body p-2 py-3 text-white">
                                        <div class="es-succes fs_10 py-1">
                                            Italy
                                        </div>
                                        <h5>
                                            Shark Gaming
                                        </h5>
                                    </div>
                                </div>
                                <!-- /.card -->
                            </div>
                            <!-- /.col-5 -->
                            <div class="col-3 p-1">
                                <div class="card p-2 py-5">
                                    <h4 class="m-0 es-primary fw-bolder">VS</h4>
                                </div>
                            </div>
                            <!-- /.col-2 -->
                            <div class="col-4 p-1">
                                <div class="text-start card">
                                    <img class="p-4" src="../assets/img/t8.png" alt="">
                                    <div class="card-body p-2 py-3 text-white">
                                        <div class="es-succes fs_10 py-1">
                                            India
                                        </div>
                                        <h5>
                                            Krull Gaming
                                        </h5>
                                    </div>
                                </div>
                                <!-- /.card -->
                            </div>
                            <!-- /.col-5 -->
                        </div>
                        <!-- /.col-6 -->

                        <div class="col-6 d-flex py-3 align-items-center justify-content-start">
                            <div class="col-7 text-start">
                                <h3 class="text-bold">
                                    Call Of Deauty
                                </h3>
                                <p class="fs_10">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex similique, nam
                                    temporibus illum officiis repellat quidem magnam iusto architecto possimus.
                                </p>
                            </div>
                            <!-- /.col-7 -->
                            <div class="col-4">
                                <div class="card special p-3 py-4">
                                    <div class="fs-3">
                                        04:45
                                    </div>
                                    <div class="fs_10">
                                        1st November, 2022
                                    </div>
                                    <div class="icon_card d-flex justify-content-center gap-2 pt-2">
                                        <div class="circle_icon_success">
                                            <svg class="svg-inline--fa fa-youtube p-2" aria-hidden="true" focusable="false"
                                                data-prefix="fab" data-icon="youtube" role="img"
                                                xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg="">
                                                <path fill="currentColor"
                                                    d="M549.7 124.1c-6.281-23.65-24.79-42.28-48.28-48.6C458.8 64 288 64 288 64S117.2 64 74.63 75.49c-23.5 6.322-42 24.95-48.28 48.6-11.41 42.87-11.41 132.3-11.41 132.3s0 89.44 11.41 132.3c6.281 23.65 24.79 41.5 48.28 47.82C117.2 448 288 448 288 448s170.8 0 213.4-11.49c23.5-6.321 42-24.17 48.28-47.82 11.41-42.87 11.41-132.3 11.41-132.3s0-89.44-11.41-132.3zm-317.5 213.5V175.2l142.7 81.21-142.7 81.2z">
                                                </path>
                                            </svg>
                                        </div>
                                        <div class="circle_icon_success">
                                            <svg class="p-2 svg-inline--fa fa-message" aria-hidden="true" focusable="false"
                                                data-prefix="fas" data-icon="message" role="img"
                                                xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg="">
                                                <path fill="currentColor"
                                                    d="M511.1 63.1v287.1c0 35.25-28.75 63.1-64 63.1h-144l-124.9 93.68c-7.875 5.75-19.12 .0497-19.12-9.7v-83.98h-96c-35.25 0-64-28.75-64-63.1V63.1c0-35.25 28.75-63.1 64-63.1h384C483.2 0 511.1 28.75 511.1 63.1z">
                                                </path>
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <!-- /.col-5 -->
                        </div>
                        <!-- /.col-6 -->
                    </div>
                    <!-- /.card_match -->


                </div>
                <!-- /.row -->
            </div>
            <!-- /.container -->
        </section>
        <!-- /#match -->

        <!-- /#match################# -->










        <!--######## TEST ########-->
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
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/AppMain.scss' as *;
</style>
