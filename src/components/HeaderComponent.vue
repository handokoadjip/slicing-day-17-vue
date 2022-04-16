<template>
  <header class="min-vh-200 bg-image-1">
    <nav class="navbar navbar-expand-lg fixed-top navbar-dark px-4">
      <div class="container-fluid px-0">
        <router-link class="display-3 navbar-brand me-5 fw-bold" to="#">
          L
        </router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase d-flex ms-auto align-items-center">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" aria-current="page" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" to="#">articles</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link line py-2 px-4" to="#">sabscribe</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section>
      <div class="container p-5 min-vh-100 position-relative">
        <div class="row">
          <div class="col-lg-12">
            <div class="wrapper d-flex justify-content-start">
              <div class="position-absolute bottom-0 start-0 p-5 p-xl-8">
                <h1 class="display-1 fw-bolder ls-5px m-0">
                  Lava
                </h1>
                <p class="fs-3 text-blue fw-medium text-uppercase ls-5px text-border-bottom">black sand beach</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container p-5 min-vh-100 d-flex justify-content-center align-items-center">
        <div class="row">
          <div class="col-lg-12">
            <div class="wrapper">
              <div class="d-flex flex-column justify-content-center align-items-center text-center">
                <h2 class="display-4 mp-0 fw-medium">
                  Slow Travelling
                </h2>
                <small class="fs-4 text-uppercase ls-5px text-fade-1 text-border-bottom-center gray gap mb-5 d-block">a
                  travel blog</small>
                <p class="text-fade-1 w-50 leading-loose">
                  We look to provide the most authentuc content from athletes, adventuren, explores travellers around
                  the world. Our long them mission is to educate inspire and enuble all peoples to experence & protect
                  wildeness
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

