<template>
  <div class="pb-48 px-8">
       <div id="hero" class="hero w-full bg-brand text-white rounded-2xl">
      <div class="max-w-6xl mx-auto px-8 xl:px-0 h-full flex items-start">
        <div class="absolute video-wrapper">
            <!-- <div class="w-full h-full relative"> -->
                <video loop autoplay muted playsinline>
                    <source src="~/assets/videos/DJI_0054.webm" type="video/webm">
                    <source src="~/assets/videos/DJI_0054.mp4" type="video/mp4"
                </video>
            <div class="w-24 h-24 bg-white bg-opacity-50 rounded-full flex items-center justify-center absolute absolute-center-y left-1/5 z-50">
                <div class="w-16 h-16 flex items-center justify-center bg-white bg-opacity-80 rounded-full">
                    <svg class="w-6 -mr-1" viewBox="0 0 29 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M4.858 33.3333C4.00952 33.3336 3.17474 33.1193 2.43133 32.7103C1.69918 32.3254 1.08589 31.7481 0.657471 31.0405C0.229053 30.3329 0.00173883 29.5218 0 28.6947V5.30533C0.00173883 4.47815 0.229053 3.66712 0.657471 2.95953C1.08589 2.25194 1.69918 1.6746 2.43133 1.28966C3.22252 0.85255 4.117 0.637003 5.02045 0.66575C5.9239 0.694496 6.80286 0.966469 7.56467 1.453L25.858 13.1477C26.5152 13.5525 27.0578 14.1189 27.4341 14.7928C27.8105 15.4667 28.0081 16.2258 28.0081 16.9977C28.0081 17.7696 27.8105 18.5286 27.4341 19.2025C27.0578 19.8764 26.5152 20.4428 25.858 20.8477L7.56467 32.5423C6.75723 33.0607 5.8175 33.3353 4.858 33.3333V33.3333ZM4.858 5.33333C4.77373 5.33175 4.69144 5.35891 4.62467 5.41033L4.66667 28.6877C4.66667 28.6527 4.739 28.669 4.82533 28.6713C4.90226 28.6737 4.97829 28.6543 5.04467 28.6153L23.3333 16.9207L23.3637 16.8973L5.04233 5.38466C4.9885 5.35091 4.9262 5.33311 4.86267 5.33333H4.858Z" fill="#1E2B5A"/>
                    </svg>
                </div>
            </div>
        <svg class="clipping-paths">
        <defs>
            <clipPath clipPathUnits="objectBoundingBox" transform="scale(0.0005208333333333333, 0.000925925925925926)" id="clip-00">
                <path d="M28.3327 474.013L474.013 28.3327C510.457 -8.11087 569.543 -8.11093 605.987 28.3327L1051.67 474.013C1088.11 510.457 1088.11 569.543 1051.67 605.987L605.987 1051.67C569.543 1088.11 510.457 1088.11 474.013 1051.67L28.3327 605.987C-8.11087 569.543 -8.11093 510.457 28.3327 474.013Z"/>
            </clipPath>
        </defs>
        </svg>
            <!-- </div> -->
        </div>
        <div class="w-1/2 left h-full flex flex-col justify-center">
          <h1 class="font-bold text-5xl">Innovative <br class="hidden lg:block"> Equipment Washing</h1>
          <p class="max-w-sm mt-6">All-in-one mobile solution for the mining and infrastructure industries.</p>
          <div class="w-full flex items-center my-12">
             <Btn link="/" type="white" arrow class="mr-6">Our Services</Btn>
            <Btn link="/" type="white-outline" arrow>Our Capabilities</Btn>
          </div>
          <svg width="26" height="57" viewBox="0 0 26 57" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M25 45.7497L15.167 54.9679C13.9702 56.0899 12.0298 56.0899 10.8329 54.9679L0.999999 45.7497" stroke="#C4C4C4" stroke-width="2"/>
            <path d="M13 56L13 0" stroke="#C4C4C4" stroke-width="2"/>
        </svg>

        </div>
        <div class="w-1/2 right relative"></div>
      </div>
   </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.video-wrapper {
transform: scale(1.8);
  top: 32px;
  right: -50vw; 
  @apply z-40;
}
video {
  clip-path: url(#clip-00);
}
/* .video-container video {
  display: block;
  width: 100%;
} */

.clipping-paths {
  width: 0;
  height: 0;
  position: absolute;
}
</style>