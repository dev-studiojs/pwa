<template>
  <div id="clients" class="pt-36 pb-12 text-center">
     <h4 class="text-3xl text-semibold mb-6">Trusted by remarkable companies</h4>
     <!-- <div class="max-w-6xl mx-auto mb-24"> -->
            <div class="max-w-6xl mx-auto">
                <!-- <div class="col-start-1 lg:col-start-1 col-span-full relative"> -->
                    <client-only>
                        <vue-tiny-slider v-bind="clientSliderOptions" id="clients" class="flex">
                            <div class="p-2">
                                <NuxtLink to="/" class="group drag-none">
                                    <img :src="require(`~/assets/images/client-logo-1.svg`)" alt="service" class="select-none drag-none">
                                </NuxtLink>
                            </div>
                            <div class="p-2">
                                <NuxtLink to="/" class="group drag-none">
                                    <img :src="require(`~/assets/images/client-logo-2.svg`)" alt="service" class="select-none drag-none">
                                </NuxtLink>
                            </div>
                            <div class="p-2">
                                <NuxtLink to="/" class="group drag-none">
                                    <img :src="require(`~/assets/images/client-logo-3.svg`)" alt="service" class="select-none drag-none">
                                </NuxtLink>
                            </div>
                            <div class="p-2">
                                <NuxtLink to="/" class="group drag-none">
                                    <img :src="require(`~/assets/images/client-logo-4.svg`)" alt="service" class="select-none drag-none">
                                </NuxtLink>
                            </div>
                           
                           
                            
                        </vue-tiny-slider>
                        <div class="max-w-lg px-8 lg:px-0 mt-20 relative">
                            <ul id="clients-controls" class="customize-controls flex items-center justify-between">
                                <li class="text-brand cursor-pointer">
                                    <svg width="57" height="26" viewBox="0 0 57 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path d="M11.934 1.72954L2.71581 11.5625C2.59069 11.6959 2.48661 11.8433 2.40356 12H56.9998V14H2.40356C2.48661 14.1566 2.59069 14.304 2.71581 14.4375L11.934 24.2704L10.5661 25.7295L1.34794 15.8966C-0.151788 14.2968 -0.151788 11.7031 1.34794 10.1034L10.5661 0.270447L11.934 1.72954Z" fill="currentColor"/>
                                    </svg>
                                </li>

                                <li class="text-brand cursor-pointer">
                                <svg width="57" height="26" viewBox="0 0 57 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path d="M45.0648 1.72954L54.283 11.5625C54.4081 11.6959 54.5122 11.8433 54.5953 12H-0.000976562V14H54.5953C54.5122 14.1566 54.4081 14.304 54.283 14.4375L45.0648 24.2704L46.4327 25.7295L55.6509 15.8966C57.1506 14.2968 57.1506 11.7031 55.6509 10.1034L46.4327 0.270447L45.0648 1.72954Z" fill="currentColor"/>
                                    </svg>
                                </li>
                            </ul>
                            
                        </div>
                    </client-only>
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