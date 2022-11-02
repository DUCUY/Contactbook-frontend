<template>
  <!-- <h1>Hello, vue.js!</h1> -->
  <div id="app">
    <AppHeader />
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>

<script>
//import dt1 from "../services/contact.service.js"
import AppHeader from "@/components/AppHeader.vue";
export default {
  // mounted(){
  // dt1.getAll();
  //  }
  components: {
    AppHeader,
  },
};
</script>
<style>
.page {
  max-width: 400px;
  margin: auto;
}
</style>
