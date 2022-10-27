<!-- import "ContactService" from './services/contact.service'; -->
<script>
import AppHeader from "@/components/AppHeader.vue";

export default {
  // mounted() {
  //   ContactService.getAll();
  // },
  components: {
    AppHeader,
  },
}
</script>

<template>
  <div id="app">
    <AppHeader />
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>
<style>
.page {
  max-width: 400px;
  margin: auto;
}
</style>
