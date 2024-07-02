<template>
  <myNavbar />
  <div class="bg-light py-5">
    <div class="container text-center">
      <p class="fw-bold mb-0 fs-3">FAQs</p>
      <nav style="--bs-breadcrumb-divider: '-'" aria-label="breadcrumb ">
        <ol class="breadcrumb justify-content-center align-items-center">
          <li class="breadcrumb-item fs-6">
            <a href="#" class="text-secondary">Home </a>
          </li>
          <li class="breadcrumb-item active fw-bold" aria-current="page">
            FAQs
          </li>
        </ol>
      </nav>
    </div>
  </div>
  <div class="container text-center py-3">
    <p class="fw-bold mb-0 fs-3">Frequently asked questions</p>
    <p class="text-secondary">Let us show you how your product come to life.</p>
  </div>
  <div class="container py-4">
    <div class="row justify-content-center">
      <div class="col-lg-8">
        <acordeon :title="title1"></acordeon>
        <acordeon :title="title2"></acordeon>
        <acordeon :title="title3"></acordeon>
        <acordeon :title="title4"></acordeon>
      </div>
    </div>
  </div>
  <div class="bg-light py-5">
    <div class="container">
      <div class="row justify-content-center align-items-center">
        <div class="col-lg-5">
          <p><span class="p1 p-2 rounded-5"> Support </span></p>
          <p class="fw-bold fs-3">Frequently asked<br />questions</p>
          <p class="text-secondary">
            You’ve got the idea, we’ve got the tools—design your <br />
            custom clothing with our free design assets:
          </p>
          <p class="fw-bold">
            <img src="../../assets/image/h2.svg" alt="" class="img-fluid" /> Any
            questions <br />
            hello@teespace.com
          </p>
        </div>
        <div class="col-lg-7">
          <acordeon :title="title1"></acordeon>
        <acordeon :title="title2"></acordeon>
        <acordeon :title="title3"></acordeon>
        <acordeon :title="title4"></acordeon>
        <acordeon :title="title5"></acordeon>
        </div>
      </div>
    </div>
  </div>
  <div class="container py-4 text-center">
    <div class="text-center">
      <div class="fs-6 gap-3">
        <img src="../../assets/image/point.svg" alt="" class="img-fluid" />
        <span class="justify-content-center"> SUPPORT 24/7 </span>
      </div>
      <p class="fw-bold fs-4">Frequently asked questions</p>
    </div>
    <div class="row justify-content-center py-4">
      <div class="col-lg-6 justify-content-between fs-6">
        <Button :myText="text1"></Button>
        <Button :myText="text2"></Button>
        <Button :myText="text3"></Button>
        <Button :myText="text4"></Button>
      </div>
      <div class="col-lg-6 justify-content-between fs-6">
        <Button :myText="text5"></Button>
        <Button :myText="text3"></Button>
        <Button :myText="text6"></Button>
        <Button :myText="text1"></Button>
      </div>
    </div>
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
  <Barres />
</template>

<script>
import Acordeon from "./Acordeon.vue";
import Barres from "./Barres.vue";
import myNavbar from "./myNavbar.vue";
import Button from "./Button.vue";
export default {
  name: "App",
  components: {
    Button,
    myNavbar,
    Barres,
    Acordeon,
  },
  data() {
    return {
      text1: "How did my package ship?",
      text2: "What products can I customize?",
      text3: "How long will my package take to arrive?",
      text4: "What are business days?",
      text5: "What is the best T-shirt material?",
      text6: "How are your T-shirts printed?",
      title1: "How does product customization work?",
      title2: "What products can I customize?",
      title3: "How are your T-shirts printed?",
      title4: "What is the best T-shirt material?",
      title5: "Can I order a personalized gift?"
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap");

#app {
  font-family: "Plus jakarta Sans";
}
.vert {
  background: #64cb9a;
  background-image: url(../../assets/image/cicle.svg),url(../../assets/image/circle1.svg);
 background-position :left,right;
  background-repeat: no-repeat;
}
.p1 {
  background: #cfc1d8;
  color: #b479d9;
}
</style>