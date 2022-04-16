<template>
  <section>
    <div class="container-fluid bg-gray p-5 min-vh-80 d-flex justify-content-center align-items-center">
      <div class="row w-100">
        <div class="col-lg-12">
          <div class="wrapper">
            <div class="d-flex flex-column justify-content-center align-items-center text-center">
              <h2 class="display-4 mp-0 fw-medium">Sabscribe</h2>
              <small class="fs-4 text-uppercase ls-5px text-fade-1 mb-4 d-block">
                a sign-up to our newsletters
              </small>
              <form class="w-75" action="" method="post">
                <div class="mb-5">
                  <input class="form-control p-4 px-5" type="text" placeholder="Your email" />
                </div>
                <button class="btn btn-sabmit text-uppercase py-2 px-5 ls-5px">
                  sabmit
                </button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SubscribeComponent",
}
</script>