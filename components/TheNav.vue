<template>
  <nav class="w-full max-w-1440 mx-auto px-4 md:pl-8 md:pr-8 2xl:pr-4 relative z-50">
      <TheLogo/>
      <div class="w-12 h-12 bg-white text-brand rounded-lg lg:hidden flex items-center justify-center cursor-pointer">
          <svg width="21" height="18" viewBox="0 0 21 18" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M20.7188 2.34375C20.8594 2.34375 21 2.25 21 2.0625V0.9375C21 0.796875 20.8594 0.65625 20.7188 0.65625H0.28125C0.09375 0.65625 0 0.796875 0 0.9375V2.0625C0 2.25 0.09375 2.34375 0.28125 2.34375H20.7188ZM20.7188 9.84375C20.8594 9.84375 21 9.75 21 9.5625V8.4375C21 8.29688 20.8594 8.15625 20.7188 8.15625H0.28125C0.09375 8.15625 0 8.29688 0 8.4375V9.5625C0 9.75 0.09375 9.84375 0.28125 9.84375H20.7188ZM20.7188 17.3438C20.8594 17.3438 21 17.25 21 17.0625V15.9375C21 15.7969 20.8594 15.6562 20.7188 15.6562H0.28125C0.09375 15.6562 0 15.7969 0 15.9375V17.0625C0 17.25 0.09375 17.3438 0.28125 17.3438H20.7188Z" fill="currentColor"/>
            </svg>
      </div>
      <ul class="hidden mx-12 w-full font-bold lg:text-sm xl:text-lg text-pw-gray-200 lg:flex items-center">
          <li class="mr-8"><NuxtLink to="/services" class="transition duration-200 text-pw-gray-200 hover:text-brand">Service & Applications</NuxtLink></li>
          <li class="mr-8"><NuxtLink to="/" class="transition duration-200 text-pw-gray-200 hover:text-brand">Capabilities</NuxtLink></li>
          <li class="mr-8"><NuxtLink to="/" class="transition duration-200 text-pw-gray-200 hover:text-brand">About Us</NuxtLink></li>
          <li class="mr-8"><NuxtLink to="/" class="transition duration-200 text-pw-gray-200 hover:text-brand">Contact Us</NuxtLink></li>
      </ul>
      <!-- <button class="flex-shrink-0 px-8 py-4 bg-pw-gray-50 rounded-lg font-bold">Talk to us today</button> -->
      <Btn link="/" type="default" class="hidden lg:block">Talk to us today</Btn>
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