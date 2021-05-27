<template>
  <div class="pb-40 px-4 lg:px-8">
       <div id="hero" class="w-full max-w-1440 mx-auto bg-brand text-white rounded-2xl px-6 py-6 sm:px-10 sm:py-16 lg:p-16">
      <div class="w-full h-full flex flex-col md:flex-row items-start">

      <div class="w-full md:w-1/2 lg:w-2/3 video-section order-1 md:order-2 relative">

        <div class="video-wrapper">
                <video src="~/assets/videos/DJI_0054.mp4" loop autoplay muted playsinline>
                    <source src="~/assets/videos/DJI_0054.mp4" type="video/mp4">
                    <source src="~/assets/videos/DJI_0054.webm" type="video/webm">
                </video>

        <svg class="clipping-paths">
        <defs>
            <clipPath clipPathUnits="objectBoundingBox" transform="scale(0.0005208333333333333, 0.000925925925925926)" id="clip-00">
                <path d="M28.3327 474.013L474.013 28.3327C510.457 -8.11087 569.543 -8.11093 605.987 28.3327L1051.67 474.013C1088.11 510.457 1088.11 569.543 1051.67 605.987L605.987 1051.67C569.543 1088.11 510.457 1088.11 474.013 1051.67L28.3327 605.987C-8.11087 569.543 -8.11093 510.457 28.3327 474.013Z"/>
            </clipPath>
        </defs>
        </svg>
        </div>
      </div>

        <div class="w-full md:w-1/2 lg:w-1/3 left h-full flex flex-col justify-center order-2 md:order-1 py-8 md:py-0">
          <h1 class="font-bold text-6xl max-w-md md:max-w-none">Innovative<br>Equipment<br>Washing</h1>
          <p class="max-w-sm mt-6">All-in-one mobile solution for the mining and infrastructure industries.</p>
          <div class="w-full flex items-center my-12">
            <Btn link="/" type="white" arrow class="mr-3 md:mr-6">Our Services</Btn>
            <Btn link="/" type="white-outline" arrow>Our Capabilities</Btn>
          </div>
          <svg width="26" height="57" viewBox="0 0 26 57" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M25 45.7497L15.167 54.9679C13.9702 56.0899 12.0298 56.0899 10.8329 54.9679L0.999999 45.7497" stroke="#C4C4C4" stroke-width="2"/>
            <path d="M13 56L13 0" stroke="#C4C4C4" stroke-width="2"/>
        </svg>

        </div>
      </div>
   </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.video-section  {
  min-height: 400px;
}

.video-wrapper {
  @apply absolute;
  top: -50%;
  left: 5%;
  right: auto;
  bottom: auto;
  width: 1200px;
}

video {
  margin-left: -15%;
}

@screen sm {
  .video-section  {
  min-height: 300px;
}
  .video-wrapper {
    top: -85%;
    left: 20%;
    right: auto;
    bottom: auto;
  }
}

@screen md {
  .video-wrapper {
    top: -110%;
    left: 0;
    right: auto;
    bottom: auto;
    width: 1700px;
    height: auto;
  }
}

@screen lg {
  .video-wrapper {
    top: -100%;
    left: 20%;
    right: auto;
    bottom: auto;
    width: 1800px;
    height: auto;
  }
}

@screen xl {
  .video-wrapper {
    top: -120%;
    left: 15%;
    right: auto;
    bottom: auto;
    width: 2100px;
    height: auto;
  }
}

@screen 2xl {
  .video-wrapper {
    top: -90%;
    left: 1%;
    right: auto;
    bottom: auto;
    width: 1800px;
    height: auto;
  }
}

.video-wrapper {
  /* width: 1920px; */
  clip-path: url(#clip-00);
  -webkit-clip-path: url(#clip-00);
}

.clipping-paths {
  width: 0;
  height: 0;
  position: absolute;
}
</style>