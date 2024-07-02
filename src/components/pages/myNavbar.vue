<template>
  <div class="d-flex justify-content-between barre container-fluid d-lg-flex d-none">
    <div class="justify-content-center m-auto fs-6">
      Free shipping on all U.S. orders $50+
    </div>
    <div class="justify-content-end pe-4">
      <img src="../../assets/image/fois.svg" alt="" class="img-fluid" />
    </div>
  </div>
  <div class="container-fluid">
    <nav class="navbar navbar-expand-lg navbar pt-3">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav" style="flex-grow: 1">
        <ul class="navbar-nav fs-6 fw-bold">
          <li class="nav-item">
            <a class="nav-link text-success" href="{{ url_for('home') }}">Home <img src="../../assets/image/flechenav.svg"
                alt="" />
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="{{ url_for('about') }}">TeeSpace <img src="../../assets/image/flechenav.svg"
                alt="" />
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="{{ url_for('contact') }}">Shop <img src="../../assets/image/flechenav.svg" alt="" />
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="{{ url_for('contact') }}">Blog <img src="../../assets/image/flechenav.svg"
                alt="" /></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="{{ url_for('contact') }}">Pages <img src="../../assets/image/flechenav.svg"
                alt="" /></a>
          </li>
        </ul>
      </div>
      <img src="../../assets/image/logo-black.png copy.svg" alt="" class="img-fluid me-5" />
      <div class="justify-content-between gap-3 ms-auto d-none d-lg-flex">
        <img src="../../assets/image/Icon (2).svg" alt="" class="img-fluid" />
        <img src="../../assets/image/Vector.svg" alt="" class="img-fluid" />
        <img src="../../assets/image/div.elementor-element.svg" alt="" class="img-fluid" />
        <img src="../../assets/image/div.elementor-element.png" alt="" class="img-fluid" />
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap");

#app {
  font-family: "Plus jakarta Sans";
}

.barre {
  background: #f4eefa;
}
</style>