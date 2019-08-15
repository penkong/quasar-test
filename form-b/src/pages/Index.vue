<template>
  <q-page class="flex flex-center">
    <img alt="Quasar logo" src="~assets/quasar-logo-full.svg" />
  </q-page>
</template>



<script>
import Quasar from "quasar";
Vue.use(Quasar);
export default {
  name: "PageIndex",
  created() {
    console.log(Quasar);
  }
};
</script>
