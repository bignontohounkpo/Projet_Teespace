<template>
  <myNavbar />
  <div class="bg-light py-3 pt-4 pb-4">
    <div class="container text-center">
      <nav style="--bs-breadcrumb-divider: '-'" aria-label="breadcrumb ">
        <ol class="breadcrumb justify-content-center align-items-center">
          <li class="breadcrumb-item fs-6">
            <a href="#" class="text-secondary">Home </a>
          </li>
          <li class="breadcrumb-item active fw-bold" aria-current="page">
            About Us
          </li>
        </ol>
      </nav>
    </div>
  </div>
  <div class="container">
    <div class="row align-items-center justify-content-center py-4">
      <div class="col-lg-6 col-md-6 col-sm-12">
        <div
          class="text-center p1 d-inline p-2 rounded-5 align-content-center d-none"
        >
          Design your own
        </div>
        <p class="fw-bold fs-3">
          Create stunning print for <br />
          your business
        </p>
        <p class="fw-ligth">
          T-shirt Printing for Everyone. Get a headstart with free design <br />
          templates you can customize in a few clicks.
        </p>
        <div class="d-flex gap-2">
          <img
            src="../../assets/image/fvert.png "
            alt=""
            class="img-fluid h-25"
          />
          <p class="fw-bold mt-1 fs-6">
            op quality prints using the latest technology
          </p>
        </div>
        <div class="d-flex gap-2">
          <img
            src="../../assets/image/fvert.png "
            alt=""
            class="img-fluid h-25"
          />
          <p class="fw-bold mt-1 fs-6">
            Mix and match colors, sizes, and designs
          </p>
        </div>
        <div class="d-flex gap-2">
          <img
            src="../../assets/image/fvert.png "
            alt=""
            class="img-fluid h-25"
          />
          <p class="fw-bold mt-1 fs-6">Fast and free standard shipping</p>
        </div>
        <div class="d-flex gap-2">
          <img
            src="../../assets/image/fvert.png "
            alt=""
            class="img-fluid h-25"
          />
          <p class="fw-bold mt-1 fs-6">Customer happiness guarantee</p>
        </div>
        <button class="btn btn-success">Custom T-shirt</button>
      </div>
      <div class="col-lg-6 col-md-6 col-sm-12 text-center pt-3">
        <img
          src="../../assets/image/aboute.svg"
          alt=""
          class="img-fluid w-75"
        />
      </div>
    </div>
  </div>
  <div class="container text-center lh-lg">
    <span class="p1 p-2 rounded-4">Fast and Quality Service</span>
    <p class="fw-bold fs-4">T-shirt printing made easy.</p>
  </div>
  <div class="container">
    <div class="row justify-content-center py-5 align-items-center">
      <div class="col-lg-5 col-md-6 col-sm-12 text-center pt-3">
        <img src="../../assets/image/petit1.svg" alt="" class="img-fluid" />
      </div>
      <div class="col-lg-6 col-md-6 col-sm-10">
        <Acordeon :title="title1" />
        <Acordeon :title="title2" />
        <Acordeon :title="title3" />
        <Acordeon :title="title4" />
      </div>
    </div>
  </div>

  <div class="container text-center lh-lg">
    <span class="p1 p-2 rounded-4">Join us Today</span>
    <p class="fw-bold fs-4">Meet our team!</p>
  </div>
  <div class="container pt-4">
    <div class="row text-center pt-3 pb-3">
      <div class="col-lg-3 col-md-6 col-sm-8 text-center">
        <img
          src="../../assets/image/team-about-1.jpg.svg"
          alt=""
          class="img-fluid rounded-3"
        />
        <div class="ps-3">
          <p class="fw-bold m-1">Arlene McCoy</p>
          <p class="text-secondary">President of Sales</p>
        </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-8 text-center">
        <img
          src="../../assets/image/team-about-3.jpg.svg"
          alt=""
          class="img-fluid rounded-3"
        />
        <div class="ps-3">
          <p class="fw-bold m-1">Marilin</p>
          <p class="text-secondary">Designer</p>
        </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-8 text-center">
        <img
          src="../../assets/image/team-about-2.jpg.svg"
          alt=""
          class="img-fluid rounded-3"
        />
        <div class="ps-3">
          <p class="fw-bold m-1">Mary Lous</p>
          <p class="text-secondary">Copy Writer</p>
        </div>
      </div>
      <div class="col-lg-3 col-md-6 col-sm-8 text-center">
        <img
          src="../../assets/image/team-about-4.jpg.svg"
          alt=""
          class="img-fluid rounded-3"
        />
        <div class="ps-3">
          <p class="fw-bold m-1">Cristina</p>
          <p class="text-secondary">Director</p>
        </div>
      </div>
    </div>
  </div>
  <div class="py-3 text-center">
    <span class="p-2 rounded-3 border d-inline">Join Our Team</span>
  </div>
  <div class="bg-light">
    <div class="container py-5">
      <div class="row justify-content-center pb-3">
        <div class="col-lg-4 d-flex justify-content-between d-lg-flex d-none">
          <img src="../../assets/image/l3.svg" alt="" class="img-fluid w-50" />
          <div class=" ">
            <div>
              <img
                src="../../assets/image/l2.svg"
                alt=""
                class="img-fluid pb-5"
              />
            </div>
            <img
              src="../../assets/image/l1.svg"
              alt=""
              class="img-fluid pt-4"
            />
          </div>
        </div>
        <div class="col-lg-4 text-center">
          <img src="../../assets/image/l3.svg" alt="" class="img-fluid w-50" />
          <p class="fw-bold fs-4">
            Join the 7,000+ <br />
            companies trusting us
          </p>
          <p class="text-secondary">
            You’ve got the ideas, we’ve got the tools
          </p>
          <button class="btn btn-success">Get Started</button>
        </div>
        <div class="col-lg-4 d-flex justify-content-between d-lg-flex d-none">
          <div class=" ">
            <div>
              <img
                src="../../assets/image/l5.svg"
                alt=""
                class="img-fluid pb-5"
              />
            </div>
            <img
              src="../../assets/image/l4.svg"
              alt=""
              class="img-fluid pt-4"
            />
          </div>
          <img src="../../assets/image/l2.svg" alt="" class="img-fluid w-50" />
        </div>
        <div class="col-lg-3 col-md-6 col-sm-6 text-center pt-3">
          <span class="text-success fw-bold fs-2"> $36M </span>
          <p class="text-secondary">printing equipment</p>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-6 text-center">
          <span class="text-success fw-bold fs-2"> 19M+</span>
          <p class="text-secondary">items trusted to delivert</p>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-6 text-center">
          <span class="text-success fw-bold fs-2"> $48M+</span>
          <p class="text-secondary">
            sold by customers <br />
            through TeeSpace
          </p>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-6 text-center">
          <span class="text-success fw-bold fs-2">1056</span>
          <p class="text-secondary">
            person team across North <br />
            America and Europe
          </p>
        </div>
      </div>
    </div>
  </div>
  <div class="container text-center lh-lg py-5">
    <span class="p1 p-2 rounded-4">Testimonials</span>
    <p class="fw-bold fs-2">What People Are Saying</p>
    <Team />
  </div>
  <div class="vert">
    <div class="container py-5 ">
      <div class="row align-items-center ">
        <div class="col-lg-6  text-center ">
          <p class="text-white fw-bold fs-1">
            Enjoy up your vacations <br />
            in the best T-shirts
          </p>
          <p class="text-white">T-shirts that keep you moving.</p>
          <div class="d-flex gap-2 justify-content-center">
            <button class="btn fw-bold" style="background-color: #ffffff">
              Show Now <img src="../../assets/image/vector2.svg" alt="" />
            </button>
            <button class="btn fw-bold py-2" style="background-color: #ffffff">
              Contact Us<img src="../../assets/image/vector2.svg" alt="" />
            </button>
          </div>
        </div>
        <div class="col-lg-5">
          <img src="../../assets/image/banner-111.png.svg" alt="" class="img-fluid">
        </div>
      </div>
    </div>
  </div>

  <barre />
</template>

<script>
import myNavbar from "./myNavbar.vue";
import barre from "./barre.vue";
import Acordeon from "./Acordeon.vue";
import Team from "./Team.vue";
export default {
  name: "About",
  components: {
    myNavbar,
    barre,
    Acordeon,
    Team,
  },
  data() {
    return {
      title1: "How does product customization work?",
      title2: "What products can I customize?",
      title3: "How are your T-shirts printed?",
      title4: "What is the best T-shirt material?",
    };
  },
};
</script>

<style>
.p1 {
  background: #b479d926;

  color: #b479d9;
}
@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap");

#app {
  font-family: "Plus Jakarta Sans";
}
.vert {
  background: #64cb9a;
  background-image: url(../../assets/image/cicle.svg),url(../../assets/image/circle1.svg);
 background-position :left,right;
  background-repeat: no-repeat;
}
</style>
