<template>
  <div class="app">
    <base-component />
  </div>
</template>
<script>
import BaseComponent from './components/BaseComponent.vue'
export default {
  components: {
    BaseComponent
  }
}
</script>
<style scoped>
.app {
 height: 100%;
 width: 100%;
 margin: 0;
 padding: 0;
}
</style>
