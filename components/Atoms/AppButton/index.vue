<template>
  <button class="app-button">
    <slot />
  </button>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'AppButton',
  props: {
    round: {
      type: Boolean,
      default: false,
    },
    border: {
      type: Boolean,
      default: false,
    },
    disabled: {
      type: Boolean,
      default: false,
    },
  },
  computed: {
    classes() {
      return [
        'app-button',
        {
          'app-button--round': this.round,
          'app-button--border': this.border,
          'app-button--disabled': this.disabled,
        },
      ]
    },
  },
})
</script>

<style lang="scss" scoped>
.app-button {
  background: gray;
}
</style>
