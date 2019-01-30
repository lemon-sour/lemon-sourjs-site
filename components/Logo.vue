<template>
  <p align="center">
    <img src="/lemon-sour.small.jpg" :alt="message">
  </p>
</template>

<style>
</style>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class Logo extends Vue {
  message: string = 'lemon-sour.jpg'
}
</script>
