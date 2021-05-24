<template>
<div class="">
    <div class="w-full grid grid-cols-12">
        <div class="col-start-1 lg:col-start-1 col-span-full relative">
            <client-only>
                <vue-tiny-slider v-bind="tinySliderOptions" id="center" class="flex">
                    <div class="w-1/2 slider-item p-2">
                        <NuxtLink to="/" class="group slider-box drag-none">
                            <h3 class="relative z-10 font-bold text-3xl text-white">Minesite Equipment Washing</h3>
                            <img :src="require(`~/assets/images/1.png`)" alt="service" class="select-none drag-none absolute bottom-0 absolute-center-x z-0 w-full h-full object-cover object-center">
                            <div class="w-full h-full bg-black bg-opacity-25 absolute inset-0 z-0"></div>
                        </NuxtLink>
                    </div>
                    <div class="w-1/2 slider-item p-2">
                        <NuxtLink to="/" class="slider-box drag-none">
                            <h3 class="relative z-10 font-bold text-3xl text-white">Aircraft & Transportation</h3>
                            <img :src="require(`~/assets/images/2.png`)" alt="service" class="select-none drag-none absolute bottom-0 absolute-center-x z-0 w-full h-full object-cover object-center">
                            <div class="w-full h-full bg-black bg-opacity-25 absolute inset-0 z-0"></div>
                        </NuxtLink>
                    </div>
                    <div class="w-1/2 slider-item p-2">
                        <NuxtLink to="/" class="slider-box drag-none">
                            <h3 class="relative z-10 font-bold text-3xl text-white">Hydroscaling</h3>
                            <img :src="require(`~/assets/images/3.png`)" alt="service" class="select-none drag-none absolute bottom-0 absolute-center-x z-0 w-full h-full object-cover object-center">
                            <div class="w-full h-full bg-black bg-opacity-25 absolute inset-0 z-0"></div>
                        </NuxtLink>
                    </div>
                    <div class="w-1/2 slider-item p-2">
                        <NuxtLink to="/" class="slider-box drag-none">
                            <h3 class="relative z-10 font-bold text-3xl text-white">General High Pressure Waching</h3>
                            <img :src="require(`~/assets/images/4.png`)" alt="service" class="select-none drag-none absolute bottom-0 absolute-center-x z-0 w-full h-full object-cover object-center">
                            <div class="w-full h-full bg-black bg-opacity-25 absolute inset-0 z-0"></div>
                        </NuxtLink>
                    </div>
                    <div class="w-1/2 slider-item p-2">
                        <NuxtLink to="/" class="slider-box drag-none">
                            <h3 class="relative z-10 font-bold text-3xl text-white">Aircraft & Transportation</h3>
                            <img :src="require(`~/assets/images/5.png`)" alt="service" class="select-none drag-none absolute bottom-0 absolute-center-x z-0 w-full h-full object-cover object-center">
                            <div class="w-full h-full bg-black bg-opacity-25 absolute inset-0 z-0"></div>
                        </NuxtLink>
                    </div>
                    <div class="w-1/2 slider-item p-2">
                        <NuxtLink to="/" class="slider-box drag-none">
                            <h3 class="relative z-10 font-bold text-3xl text-white">Hydroscaling</h3>
                            <img :src="require(`~/assets/images/1.png`)" alt="service" class="select-none drag-none absolute bottom-0 absolute-center-x z-0 w-full h-full object-cover object-center">
                            <div class="w-full h-full bg-black bg-opacity-25 absolute inset-0 z-0"></div>
                        </NuxtLink>
                    </div>
                    <div class="w-1/2 slider-item p-2">
                        <NuxtLink to="/" class="slider-box drag-none">
                            <h3 class="relative z-10 font-bold text-3xl text-white">General High Pressure Waching</h3>
                            <img :src="require(`~/assets/images/2.png`)" alt="service" class="select-none drag-none absolute bottom-0 absolute-center-x z-0 w-full h-full object-cover object-center">
                            <div class="w-full h-full bg-black bg-opacity-25 absolute inset-0 z-0"></div>
                        </NuxtLink>
                    </div>
              
                    <div class="w-1/2 slider-item p-2">
                        <NuxtLink to="/" class="slider-box bg-white drag-none">
                            <!-- <h3 class="relative z-10 font-bold text-3xl text-white">Executive Search</h3>
                            <img :src="require(`~/assets/images/sector3.jpeg`)" alt="service" class="select-none drag-none absolute bottom-0 absolute-center-x z-0 w-full h-full object-cover object-center">
                            <div class="w-full h-full bg-black bg-opacity-25 absolute inset-0 z-0"></div> -->
                        </NuxtLink>
                    </div>
                    
                </vue-tiny-slider>
                <div class="max-w-6xl mx-auto px-8 lg:px-0">
                    <ul id="customize-controls" class="customize-controls max-w-sm flex items-center justify-between">
                        <li class="text-brand">
                            <svg width="57" height="26" viewBox="0 0 57 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M11.934 1.72954L2.71581 11.5625C2.59069 11.6959 2.48661 11.8433 2.40356 12H56.9998V14H2.40356C2.48661 14.1566 2.59069 14.304 2.71581 14.4375L11.934 24.2704L10.5661 25.7295L1.34794 15.8966C-0.151788 14.2968 -0.151788 11.7031 1.34794 10.1034L10.5661 0.270447L11.934 1.72954Z" fill="currentColor"/>
                            </svg>
                        </li>

                        <li class="text-brand">
                          <svg width="57" height="26" viewBox="0 0 57 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M45.0648 1.72954L54.283 11.5625C54.4081 11.6959 54.5122 11.8433 54.5953 12H-0.000976562V14H54.5953C54.5122 14.1566 54.4081 14.304 54.283 14.4375L45.0648 24.2704L46.4327 25.7295L55.6509 15.8966C57.1506 14.2968 57.1506 11.7031 55.6509 10.1034L46.4327 0.270447L45.0648 1.72954Z" fill="currentColor"/>
                            </svg>
                        </li>
                    </ul>
                    <ul id="custom-nav" class="flex items-center">
                        <li><svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path opacity="0.25" d="M0.72841 7.75736C-0.242152 6.7868 -0.242152 5.2132 0.72841 4.24264L4.24313 0.727922C5.21369 -0.242641 6.78728 -0.242641 7.75785 0.727922L11.2726 4.24264C12.2431 5.2132 12.2431 6.7868 11.2726 7.75736L7.75785 11.2721C6.78728 12.2426 5.21369 12.2426 4.24313 11.2721L0.72841 7.75736Z" fill="#8E95AC"/>
                        </svg>
                        </li>
                        <li><svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path opacity="0.25" d="M0.72841 7.75736C-0.242152 6.7868 -0.242152 5.2132 0.72841 4.24264L4.24313 0.727922C5.21369 -0.242641 6.78728 -0.242641 7.75785 0.727922L11.2726 4.24264C12.2431 5.2132 12.2431 6.7868 11.2726 7.75736L7.75785 11.2721C6.78728 12.2426 5.21369 12.2426 4.24313 11.2721L0.72841 7.75736Z" fill="#8E95AC"/>
                        </svg>
                        </li>
                        <li><svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path opacity="0.25" d="M0.72841 7.75736C-0.242152 6.7868 -0.242152 5.2132 0.72841 4.24264L4.24313 0.727922C5.21369 -0.242641 6.78728 -0.242641 7.75785 0.727922L11.2726 4.24264C12.2431 5.2132 12.2431 6.7868 11.2726 7.75736L7.75785 11.2721C6.78728 12.2426 5.21369 12.2426 4.24313 11.2721L0.72841 7.75736Z" fill="#8E95AC"/>
                        </svg>
                        </li>
                        <li><svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path opacity="0.25" d="M0.72841 7.75736C-0.242152 6.7868 -0.242152 5.2132 0.72841 4.24264L4.24313 0.727922C5.21369 -0.242641 6.78728 -0.242641 7.75785 0.727922L11.2726 4.24264C12.2431 5.2132 12.2431 6.7868 11.2726 7.75736L7.75785 11.2721C6.78728 12.2426 5.21369 12.2426 4.24313 11.2721L0.72841 7.75736Z" fill="#8E95AC"/>
                        </svg>
                        </li>
                        <li><svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path opacity="0.25" d="M0.72841 7.75736C-0.242152 6.7868 -0.242152 5.2132 0.72841 4.24264L4.24313 0.727922C5.21369 -0.242641 6.78728 -0.242641 7.75785 0.727922L11.2726 4.24264C12.2431 5.2132 12.2431 6.7868 11.2726 7.75736L7.75785 11.2721C6.78728 12.2426 5.21369 12.2426 4.24313 11.2721L0.72841 7.75736Z" fill="#8E95AC"/>
                        </svg>
                        </li>
                        <li><svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path opacity="0.25" d="M0.72841 7.75736C-0.242152 6.7868 -0.242152 5.2132 0.72841 4.24264L4.24313 0.727922C5.21369 -0.242641 6.78728 -0.242641 7.75785 0.727922L11.2726 4.24264C12.2431 5.2132 12.2431 6.7868 11.2726 7.75736L7.75785 11.2721C6.78728 12.2426 5.21369 12.2426 4.24313 11.2721L0.72841 7.75736Z" fill="#8E95AC"/>
                        </svg>
                        </li>
                        <li><svg width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path opacity="0.25" d="M0.72841 7.75736C-0.242152 6.7868 -0.242152 5.2132 0.72841 4.24264L4.24313 0.727922C5.21369 -0.242641 6.78728 -0.242641 7.75785 0.727922L11.2726 4.24264C12.2431 5.2132 12.2431 6.7868 11.2726 7.75736L7.75785 11.2721C6.78728 12.2426 5.21369 12.2426 4.24313 11.2721L0.72841 7.75736Z" fill="#8E95AC"/>
                        </svg>
                        </li>
                    </ul>
                </div>
            </client-only>
        </div>
    </div>
</div>
</template>

<script>
export default {
    data() {
        return {
            tinySliderOptions: {
                "controlsContainer": "#customize-controls",
                "navContainer": "#custom-nav",
                "mouseDrag": true,
                "items": 1,
                "center": false,
                "loop": false,
                "gutter": 0,
                "edgePadding": 80,
                "fixedWidth": 300,
                "controls": true,
                "navPosition": "bottom",
                "controlsPosition": "bottom",
                "responsive": {
                    "640": {
                        "edgePadding": 100,
                        "items": 3
                    },
                    "1024": {
                        "edgePadding": 230,
                        "items": 3
                    }
                },
            }
        }
    },
}
</script>

<style>
/* #center {
    transform: translate3d(7.14286%, 0px, 0px)!important;
} */

.slider-box {
    @apply relative p-8 rounded-3xl transform transition duration-200 flex items-end justify-start w-full h-full overflow-hidden hover:-translate-y-2 hover:shadow-xl;
}
.slider-item {
    height: 428px;
}
.button-control {
    @apply cursor-pointer w-10 h-10 rounded-md flex items-center justify-center;
}

 #center-iw {
        margin: 0 calc(100vw / 15)!important;
    }
    .customize-controls {
        margin-left: calc(100vw / 15);
    }


@media screen and (min-width: 768px) and (max-width: 1023px) {
   #center-iw {
        margin: 0 calc(100vw / 15)!important;
    }
    .customize-controls {
        margin-left: calc(100vw / 15);
    }
}

@media screen and (min-width: 1024px) {
     #center-iw {
        margin: 0 calc(100vw / 15)!important;
    }
    .customize-controls {
        margin-left: calc(100vw / 15);
    }
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