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

                    <span class="es-succes fs_10">Trending Battle</span>
                    <h2 class="fw-bold pt-2 pb-4 fs-1">Upcoming Match</h2>

                    <div class="d-flex fs_9 justify-content-center gap-4 pb-2">
                        <div class="es-succes">All</div>
                        <div>Pubg</div>
                        <div>COD</div>
                        <div>AC</div>
                        <div>MCX</div>
                    </div>

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
                                <p class="fs_10 d-block">
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

        <!-- #choose################# -->

        <section id="choose">
            <div class="black_bg">
                <div class="container py-5 mw_1180">
                    <div class="row py-5 justify-content-between">
                        <div class="col-6">
                            <span class="es-succes fs_10">Upcoming Match</span>
                            <h2 class="fw-bold pt-1 pb-2">Choose Who Is The Best In World!</h2>
                        </div>
                        <!-- ARROW -->
                        <div class="col-6 d-flex align-items-end gap-3 pb-2 justify-content-end">
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

                        <div class="col-3">
                            <div class="card position-relative">
                                <img src="../assets/img/protfolio1.png" class="card-img-top">
                                <div class="ticket fs_8">
                                    New
                                </div>
                                <div class="card-body px-2 d-flex text-white">
                                    <div class="col-9">
                                        <div class="fw-bolder">
                                            Assasin's Creed
                                        </div>
                                        <div class="fs_10">
                                            Lorem, ipsum dolor.
                                        </div>
                                    </div>
                                    <a class="p-3 btn es_button d-flex align-items-center justify-content-center rounded-circle"
                                        href="###">
                                        <svg width=".7rem" class="svg-inline--fa fa-play" aria-hidden="true"
                                            focusable="false" data-prefix="fas" data-icon="play" role="img"
                                            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
                                            <path fill="currentColor"
                                                d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z">
                                            </path>
                                        </svg>
                                    </a>

                                </div>
                            </div>
                            <!-- /.card -->
                        </div>
                        <!-- /.col-3 -->
                        <div class="col-3">
                            <div class="card position-relative">
                                <img src="../assets/img/protfolio2.png" class="card-img-top">
                                <div class="ticket fs_8">
                                    New
                                </div>
                                <div class="card-body px-2 d-flex text-white">
                                    <div class="col-9">
                                        <div class="fw-bolder">
                                            Call of Duty
                                        </div>
                                        <div class="fs_10">
                                            Lorem, ipsum dolor.
                                        </div>
                                    </div>
                                    <a class="p-3 btn es_button d-flex align-items-center justify-content-center rounded-circle"
                                        href="###">
                                        <svg width=".7rem" class="svg-inline--fa fa-play" aria-hidden="true"
                                            focusable="false" data-prefix="fas" data-icon="play" role="img"
                                            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
                                            <path fill="currentColor"
                                                d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z">
                                            </path>
                                        </svg>
                                    </a>

                                </div>
                            </div>
                            <!-- /.card -->
                        </div>
                        <!-- /.col-3 -->
                        <div class="col-3">
                            <div class="card position-relative">
                                <img src="../assets/img/protfolio3.png" class="card-img-top">
                                <div class="ticket fs_8">
                                    New
                                </div>
                                <div class="card-body px-2 d-flex text-white">
                                    <div class="col-9">
                                        <div class="fw-bolder">
                                            Tomb Raider
                                        </div>
                                        <div class="fs_10">
                                            Lorem, ipsum dolor.
                                        </div>
                                    </div>
                                    <a class="p-3 btn es_button d-flex align-items-center justify-content-center rounded-circle"
                                        href="###">
                                        <svg width=".7rem" class="svg-inline--fa fa-play" aria-hidden="true"
                                            focusable="false" data-prefix="fas" data-icon="play" role="img"
                                            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
                                            <path fill="currentColor"
                                                d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z">
                                            </path>
                                        </svg>
                                    </a>

                                </div>
                            </div>
                            <!-- /.card -->
                        </div>
                        <!-- /.col-3 -->
                        <div class="col-3">
                            <div class="card position-relative">
                                <img src="../assets/img/protfolio4.png" class="card-img-top">
                                <div class="ticket fs_8">
                                    New
                                </div>
                                <div class="card-body px-2 d-flex text-white">
                                    <div class="col-9">
                                        <div class="fw-bolder">
                                            Mortal Kombat X
                                        </div>
                                        <div class="fs_10">
                                            Lorem, ipsum dolor.
                                        </div>
                                    </div>
                                    <a class="p-3 btn es_button d-flex align-items-center justify-content-center rounded-circle"
                                        href="###">
                                        <svg width=".7rem" class="svg-inline--fa fa-play" aria-hidden="true"
                                            focusable="false" data-prefix="fas" data-icon="play" role="img"
                                            xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
                                            <path fill="currentColor"
                                                d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z">
                                            </path>
                                        </svg>
                                    </a>

                                </div>
                            </div>
                            <!-- /.card -->
                        </div>
                        <!-- /.col-3 -->

                    </div>
                    <!-- /.row -->
                </div>
            </div>
        </section>
        <!-- /#choose -->

        <!-- /#choose################# -->


        <!-- /#experts_team################# -->

        <section id="experts_team">
            <div class="container py-5 mw_1180">
                <div class="row py-5 justify-content-between">
                    <div class="col-6">
                        <span class="es-succes fs_10">Team Members</span>
                        <h2 class="fw-bold pt-1 pb-2">Our Experts Team Members</h2>
                    </div>
                    <!-- ARROW -->
                    <div class="col-6 d-flex align-items-end gap-3 pb-2 justify-content-end">
                        <div class="circle_icon_light">
                            <svg width="1rem" class="svg-inline--fa fa-arrow-left-long" aria-hidden="true" focusable="false"
                                data-prefix="fas" data-icon="arrow-left-long" role="img" xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 512 512" data-fa-i2svg="">
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

                    <div class="col-3">
                        <div class="card ">
                            <img src="../assets/img/team1.png" class="card-img-top">
                            <div class="icon_social gap-2 d-flex justify-content-around">
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-facebook circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="facebook"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M504 256C504 119 393 8 256 8S8 119 8 256c0 123.8 90.69 226.4 209.3 245V327.7h-63V256h63v-54.64c0-62.15 37-96.48 93.67-96.48 27.14 0 55.52 4.84 55.52 4.84v61h-31.28c-30.8 0-40.41 19.12-40.41 38.73V256h68.78l-11 71.69h-57.78V501C413.3 482.4 504 379.8 504 256z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-twitter circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitter"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M459.4 151.7c.325 4.548 .325 9.097 .325 13.65 0 138.7-105.6 298.6-298.6 298.6-59.45 0-114.7-17.22-161.1-47.11 8.447 .974 16.57 1.299 25.34 1.299 49.06 0 94.21-16.57 130.3-44.83-46.13-.975-84.79-31.19-98.11-72.77 6.498 .974 12.99 1.624 19.82 1.624 9.421 0 18.84-1.3 27.61-3.573-48.08-9.747-84.14-51.98-84.14-102.1v-1.299c13.97 7.797 30.21 12.67 47.43 13.32-28.26-18.84-46.78-51.01-46.78-87.39 0-19.49 5.197-37.36 14.29-52.95 51.65 63.67 129.3 105.3 216.4 109.8-1.624-7.797-2.599-15.92-2.599-24.04 0-57.83 46.78-104.9 104.9-104.9 30.21 0 57.5 12.67 76.67 33.14 23.72-4.548 46.46-13.32 66.6-25.34-7.798 24.37-24.37 44.83-46.13 57.83 21.12-2.273 41.58-8.122 60.43-16.24-14.29 20.79-32.16 39.31-52.63 54.25z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-linkedin circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="linkedin"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-instagram circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="instagram"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z">
                                        </path>
                                    </svg>
                                </a>
                            </div>
                            <div class="card-body px-2 text-center text-white">
                                <div class="fw-bolder">
                                    Cristiano Messi
                                </div>
                                <div class="fs_10">
                                    CEO/Founder
                                </div>


                            </div>
                        </div>
                        <!-- /.card -->
                    </div>
                    <!-- /.col-3 -->
                    <div class="col-3">
                        <div class="card ">
                            <img src="../assets/img/team2.png" class="card-img-top">
                            <div class="icon_social gap-2 d-flex justify-content-around">
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-facebook circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="facebook"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M504 256C504 119 393 8 256 8S8 119 8 256c0 123.8 90.69 226.4 209.3 245V327.7h-63V256h63v-54.64c0-62.15 37-96.48 93.67-96.48 27.14 0 55.52 4.84 55.52 4.84v61h-31.28c-30.8 0-40.41 19.12-40.41 38.73V256h68.78l-11 71.69h-57.78V501C413.3 482.4 504 379.8 504 256z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-twitter circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitter"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M459.4 151.7c.325 4.548 .325 9.097 .325 13.65 0 138.7-105.6 298.6-298.6 298.6-59.45 0-114.7-17.22-161.1-47.11 8.447 .974 16.57 1.299 25.34 1.299 49.06 0 94.21-16.57 130.3-44.83-46.13-.975-84.79-31.19-98.11-72.77 6.498 .974 12.99 1.624 19.82 1.624 9.421 0 18.84-1.3 27.61-3.573-48.08-9.747-84.14-51.98-84.14-102.1v-1.299c13.97 7.797 30.21 12.67 47.43 13.32-28.26-18.84-46.78-51.01-46.78-87.39 0-19.49 5.197-37.36 14.29-52.95 51.65 63.67 129.3 105.3 216.4 109.8-1.624-7.797-2.599-15.92-2.599-24.04 0-57.83 46.78-104.9 104.9-104.9 30.21 0 57.5 12.67 76.67 33.14 23.72-4.548 46.46-13.32 66.6-25.34-7.798 24.37-24.37 44.83-46.13 57.83 21.12-2.273 41.58-8.122 60.43-16.24-14.29 20.79-32.16 39.31-52.63 54.25z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-linkedin circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="linkedin"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-instagram circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="instagram"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z">
                                        </path>
                                    </svg>
                                </a>
                            </div>
                            <div class="card-body px-2 text-center text-white">
                                <div class="fw-bolder">
                                    Sergio Naymer
                                </div>
                                <div class="fs_10">
                                    Programmer
                                </div>


                            </div>
                        </div>
                        <!-- /.card -->
                    </div>
                    <!-- /.col-3 -->
                    <div class="col-3">
                        <div class="card ">
                            <img src="../assets/img/team3.png" class="card-img-top">
                            <div class="icon_social gap-2 d-flex justify-content-around">
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-facebook circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="facebook"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M504 256C504 119 393 8 256 8S8 119 8 256c0 123.8 90.69 226.4 209.3 245V327.7h-63V256h63v-54.64c0-62.15 37-96.48 93.67-96.48 27.14 0 55.52 4.84 55.52 4.84v61h-31.28c-30.8 0-40.41 19.12-40.41 38.73V256h68.78l-11 71.69h-57.78V501C413.3 482.4 504 379.8 504 256z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-twitter circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitter"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M459.4 151.7c.325 4.548 .325 9.097 .325 13.65 0 138.7-105.6 298.6-298.6 298.6-59.45 0-114.7-17.22-161.1-47.11 8.447 .974 16.57 1.299 25.34 1.299 49.06 0 94.21-16.57 130.3-44.83-46.13-.975-84.79-31.19-98.11-72.77 6.498 .974 12.99 1.624 19.82 1.624 9.421 0 18.84-1.3 27.61-3.573-48.08-9.747-84.14-51.98-84.14-102.1v-1.299c13.97 7.797 30.21 12.67 47.43 13.32-28.26-18.84-46.78-51.01-46.78-87.39 0-19.49 5.197-37.36 14.29-52.95 51.65 63.67 129.3 105.3 216.4 109.8-1.624-7.797-2.599-15.92-2.599-24.04 0-57.83 46.78-104.9 104.9-104.9 30.21 0 57.5 12.67 76.67 33.14 23.72-4.548 46.46-13.32 66.6-25.34-7.798 24.37-24.37 44.83-46.13 57.83 21.12-2.273 41.58-8.122 60.43-16.24-14.29 20.79-32.16 39.31-52.63 54.25z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-linkedin circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="linkedin"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-instagram circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="instagram"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z">
                                        </path>
                                    </svg>
                                </a>
                            </div>
                            <div class="card-body px-2 text-center text-white">
                                <div class="fw-bolder">
                                    Antonella Roccuzzo
                                </div>
                                <div class="fs_10">
                                    Project Manager
                                </div>


                            </div>
                        </div>
                        <!-- /.card -->
                    </div>
                    <!-- /.col-3 -->
                    <div class="col-3">
                        <div class="card">
                            <img src="../assets/img/team4.png" class="card-img-top">
                            <div class="icon_social gap-2 d-flex justify-content-around">
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-facebook circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="facebook"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M504 256C504 119 393 8 256 8S8 119 8 256c0 123.8 90.69 226.4 209.3 245V327.7h-63V256h63v-54.64c0-62.15 37-96.48 93.67-96.48 27.14 0 55.52 4.84 55.52 4.84v61h-31.28c-30.8 0-40.41 19.12-40.41 38.73V256h68.78l-11 71.69h-57.78V501C413.3 482.4 504 379.8 504 256z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-twitter circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitter"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M459.4 151.7c.325 4.548 .325 9.097 .325 13.65 0 138.7-105.6 298.6-298.6 298.6-59.45 0-114.7-17.22-161.1-47.11 8.447 .974 16.57 1.299 25.34 1.299 49.06 0 94.21-16.57 130.3-44.83-46.13-.975-84.79-31.19-98.11-72.77 6.498 .974 12.99 1.624 19.82 1.624 9.421 0 18.84-1.3 27.61-3.573-48.08-9.747-84.14-51.98-84.14-102.1v-1.299c13.97 7.797 30.21 12.67 47.43 13.32-28.26-18.84-46.78-51.01-46.78-87.39 0-19.49 5.197-37.36 14.29-52.95 51.65 63.67 129.3 105.3 216.4 109.8-1.624-7.797-2.599-15.92-2.599-24.04 0-57.83 46.78-104.9 104.9-104.9 30.21 0 57.5 12.67 76.67 33.14 23.72-4.548 46.46-13.32 66.6-25.34-7.798 24.37-24.37 44.83-46.13 57.83 21.12-2.273 41.58-8.122 60.43-16.24-14.29 20.79-32.16 39.31-52.63 54.25z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-linkedin circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="linkedin"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z">
                                        </path>
                                    </svg>
                                </a>
                                <a href="##">
                                    <svg width="1rem" class="svg-inline--fa fa-instagram circle_icon_dark p-2"
                                        aria-hidden="true" focusable="false" data-prefix="fab" data-icon="instagram"
                                        role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                                        data-fa-i2svg="">
                                        <path fill="currentColor"
                                            d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z">
                                        </path>
                                    </svg>
                                </a>
                            </div>
                            <div class="card-body px-2 text-center text-white">

                                <div class="fw-bolder">
                                    Lionel Ramos
                                </div>
                                <div class="fs_10">
                                    Game Designer
                                </div>



                            </div>
                        </div>
                        <!-- /.card -->
                    </div>
                    <!-- /.col-3 -->

                </div>
                <!-- /.row -->
            </div>
        </section>
        <!-- /#experts_team -->

        <!-- /#experts_team################# -->



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
