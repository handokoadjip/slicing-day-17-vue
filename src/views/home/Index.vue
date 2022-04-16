<template>
  <ArticleComponent />
  <SubscribeComponent />
</template>

<script>
import ArticleComponent from "@/components/ArticleComponent.vue";
import SubscribeComponent from "@/components/SubscribeComponent.vue";

export default {
  name: "HomePage",
  components: {
    ArticleComponent,
    SubscribeComponent,
  },
  mounted() {
    document.title = "Vovk Kseniia | Lava"
  }
}
</script>
