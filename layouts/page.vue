<template>
  <div class="relative antialiased font-sans text-gd-neutral-dark overflow-x-hidden">
    <TheNav buttonType="default" class="fixed top-0 w-full bg-white"/>
    <Nuxt />
    <TheFooter class="mt-24"/>
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
