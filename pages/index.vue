<template>
  <h1>
    Hello {{message}}!
  </h1>
</template>

<script lang="ts">
import Vue from 'vue'

export default {
  data() {
    return {message: "World"}
  }
}
</script>
