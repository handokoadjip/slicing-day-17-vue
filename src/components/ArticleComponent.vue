<template>
  <section>
    <div class="container p-5 min-vh-100">
      <div class="py-5">
        <div class="row">
          <div class="col-lg-12">
            <div class="wrapper">
              <div class="d-flex flex-column justify-content-center align-items-center text-center">
                <h2 class="display-4 mp-0 fw-medium">Slow Travelling</h2>
                <small class="fs-4 text-uppercase ls-5px text-fade-1 text-border-bottom-center gray mb-5 d-block">
                  a travel blog
                </small>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4" v-for="(list, index) in lists" :key="index" :id="list.title">
            <div class="wrapper mb-5 mb-lg-0">
              <div class="card bg-transparent border-0">
                <div class="card-body mp-0 shadow-1">
                  <figure class="position-relative">
                    <img class="img-fluid w-100 img-articles" :src="list.image" :alt="`article-${index}`" />
                    <figcaption
                      class="w-100 pb-5 text-uppercase text-center position-absolute bottom-0 start-50 translate-middle-x">
                      <h3 class="mp-0">{{list.title}}</h3>
                      <p class="fs-5 mp-0 text-fade-1 text-border-bottom-center gray ls-5px">
                        {{list.subtitle}}
                      </p>
                    </figcaption>
                  </figure>
                </div>
                <Link class="stretched-link" :to="list.href">
                </Link>
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ArticleComponent",
  data() {
    return {
      lists: [
        {
          image: require("@/assets/source/image/article-1.jpg"),
          title: "TUNZA",
          subtitle: "RUGGED PORT",
          href: "#",
        },
        {
          image: require("@/assets/source/image/article-2.jpg"),
          title: "TIMOR",
          subtitle: "UNTOUCHED BEACH",
          href: "#",
        },
        {
          image: require("@/assets/source/image/article-3.jpg"),
          title: "LOMBOK",
          subtitle: "ENDLES LAVA",
          href: "#",
        },
      ]
    }
  }
}
</script>