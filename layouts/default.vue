<template>
  <div class="relative antialiased font-sans text-gd-neutral-dark overflow-x-hidden">
    <TheNav buttonType="white"/>
    <Nuxt />
    <TheFooter/>
  </div>
</template>

<script>
import aosMixin from '~/mixins/aos'
  export default {
    mixins: [aosMixin]
  }

</script>

<style>

</style>
