<template>
  <footer>
    <div class="container">
      <div class="row align-items-center py-5 min-vh-50">
        <div class="col-lg-12">
          <div class="wrapper">
            <div class="copyright d-block d-lg-flex justify-content-lg-between align-items-lg-center text-center">
              <router-link class="display-3 d-block text-white fw-bold text-center mb-3 mb-lg-0" to="#">
                L
              </router-link>
              <ul class="text-uppercase d-inline mp-0">
                <li class="d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">about</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">articles</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">sabscribe</router-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>