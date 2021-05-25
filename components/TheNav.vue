<template>
  <nav class="w-full px-8 relative z-50">
      <TheLogo/>
      <ul class="mx-12 w-full font-bold text-lg text-pw-gray-200 flex items-center">
          <li class="mr-8"><NuxtLink to="/services" class="transition duration-200 text-pw-gray-200 hover:text-brand">Service & Applications</NuxtLink></li>
          <li class="mr-8"><NuxtLink to="/" class="transition duration-200 text-pw-gray-200 hover:text-brand">Capabilities</NuxtLink></li>
          <li class="mr-8"><NuxtLink to="/" class="transition duration-200 text-pw-gray-200 hover:text-brand">About Us</NuxtLink></li>
          <li class="mr-8"><NuxtLink to="/" class="transition duration-200 text-pw-gray-200 hover:text-brand">Contact Us</NuxtLink></li>
      </ul>
      <!-- <button class="flex-shrink-0 px-8 py-4 bg-pw-gray-50 rounded-lg font-bold">Talk to us today</button> -->
      <Btn link="/" :type="buttonType">Talk to us today</Btn>
  </nav>
</template>

<script>
export default {
    props: {
        buttonType: String
    }
}
</script>

<style>
nav {
    height: 120px;
    @apply flex items-center justify-between;
}
</style>