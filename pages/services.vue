<template>
 <div class="space-init">
    <!-- <TheHero/> -->
    <div class="w-full image-header relative overflow-hidden">
      <img class="absolute bottom-0 left-0 w-full" :src="require(`~/assets/images/service.png`)">
      <div class="absolute inset-0 w-full h-full bg-black bg-opacity-25"></div>
      <h4 class="absolute mt-32 ml-24 font-bold text-2xl text-white">Our Services</h4>
    </div>
    <div class="w-full px-24">
      <div class="w-full bg-white rounded-xl -mt-28 px-16 py-16 relative z-10 flex items-start">
        <div class="w-1/2">
                <div class="font-bold text-6xl text-brand">
                  <h2 class="text-outline">Simplifying mine site maintenance</h2>
              </div>
              <p class="text-2xl font-semibold my-8">Tap into our expert heavy duty cleaning services and specialist advice. We're here to make your job easier.</p>
              <p class="text-pw-medium">Utilizing the components and systems from washing and de-icing systems that have already proven themselves over the years, PLANTWASH provides customers with reliable and efficient washing capability.</p>
        </div>

        <div class="w-1/2 px-24">
          <div class="w-full px-8 py-14 bg-gradient-to-b from-beige to-transparent rounded-2xl">
            <div class="flex items-start">
              <p class="text-8xl font-semibold leading-snug -mt-6 mr-6">"</p>
              <div>
                <p class="text-2xl font-semibold leading-snug">My promise to you is we’ll always take the time to understand what you need, and only recommend the solution we’d choose in your shoes.</p>
                <div class="mt-6">
                  <p>Josh</p>
                  <p class="font-bold">Managing Director, ABC Corp.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- <TheIntro/> -->
   <div class="w-full py-24 bg-gradient-to-b from-beige to-transparent ">
      <TheSlider/>
   </div>
    <TheCta/>
 </div>
</template>

<script>
  export default {
    layout: 'page'
    
  }
</script>

<style>
.space-init {
  margin-top: 120px;
}
.image-header {
  height: 363px;
}
</style>