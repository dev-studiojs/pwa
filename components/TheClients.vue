<template>
  <div id="clients" class="pt-36 pb-12 text-center px-8">
     <h4 class="text-xl md:text-3xl text-semibold mb-6">Trusted by remarkable companies</h4>
     <!-- <div class="max-w-6xl mx-auto mb-24"> -->
            <div class="max-w-4xl mx-auto mb-24">
                <!-- <div class="col-start-1 lg:col-start-1 col-span-full relative"> -->
                        <div class="w-full grid grid-cols-6">
                            <div class="col-span-2 flex items-center justify-center">
                                <NuxtLink to="/" class="group drag-none">
                                    <img :src="require(`~/assets/images/anglo_gold_ashanti.png`)" alt="service" class="w-32 md:w-40 select-none drag-none">
                                </NuxtLink>
                            </div>
                            <div class="col-span-2 flex items-center justify-center">
                                <NuxtLink to="/" class="group drag-none">
                                    <img :src="require(`~/assets/images/igo.png`)" alt="service" class="w-16 md:w-24 select-none drag-none">
                                </NuxtLink>
                            </div>
                            <div class="col-span-2 flex items-center justify-center">
                                <NuxtLink to="/" class="group drag-none">
                                    <img :src="require(`~/assets/images/goldfields.png`)" alt="service" class="w-32 md:w-40 select-none drag-none">
                                </NuxtLink>
                            </div>
                           
                           
                            
                        </div>
                        

                <!-- </div> -->
            </div>
        <!-- </div> -->
    </div>  
</template>

<script>
export default {
    data() {
        return {
            clientSliderOptions: {
                "container": "#clients",
                "controlsContainer": "#clients-controls",
                "mouseDrag": true,
                "items": 4,
                "center": false,
                "loop": true,
                "gutter": 32,
                // "edgePadding": 80,
                // "fixedWidth": 300,
                "controls": true,
                // "navPosition": "bottom",
                "controlsPosition": "bottom",
                // "responsive": {
                //     "640": {
                //         "edgePadding": 100,
                //         "items": 3
                //     },
                //     "1024": {
                //         "edgePadding": 230,
                //         "items": 3
                //     }
                // },
            }
        }
    },
}
</script>

<style>


.button-control {
    @apply cursor-pointer w-10 h-10 rounded-md flex items-center justify-center;
}


.tns-outer {
    overflow-x: hidden;
}
.tns-controls {
    z-index: 100;
}
.tns-nav {
    z-index: 10;
    width: 50%;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
}
.tns-nav button {
    background-color: #474A4D;
}
.tns-nav-active {
    @apply text-brand
}
button.tns-nav-active {
    background-color: #E0E2E3!important;
}
.tns-controls button,
.tns-nav button:focus {
    outline: none;
}
.tns-controls > button[data-controls="next"] {
    position: absolute;
    right: 32px;
}
.tns-liveregion {
    display: none;
}
</style>