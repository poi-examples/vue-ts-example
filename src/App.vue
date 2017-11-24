<template>
  <div id="app">Hello {{ msg }}</div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data() {
    return {
      msg: 'World'
    }
  }
})
</script>

