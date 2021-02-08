<template>
  <footer class="app-footer">footer</footer>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'AppFooter',
})
</script>

<style lang="scss" scoped>
.app-footer {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 10vh;
  padding: 40px;
  background-color: #475050;
  color: #fff;
}
</style>
