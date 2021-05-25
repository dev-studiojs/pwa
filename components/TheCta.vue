<template>
    <div id="cta" class="text-white">
        <div class="max-w-6xl mx-auto bg-brand rounded-2xl relative overflow-hidden">
            <svg class="absolute left-0 top-24" width="25" height="62" viewBox="0 0 25 62" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M0 61.1725V0.827461C0.168719 0.980628 0.334604 1.13865 0.497474 1.30152L20.2965 21.1005C25.7638 26.5678 25.7638 35.4322 20.2965 40.8995L0.497474 60.6985C0.334604 60.8614 0.168719 61.0194 0 61.1725Z" fill="#CECECE"/>
            </svg>

            <img class="absolute -right-1/4 top-0 z-0" :src="require(`~/assets/images/cta-diamond.svg`)">

            <div class="flex items-center p-28">
                <div class="w-2/3">
                    <h3 class="text-4xl">We're here to help</h3>
                    <p class="max-w-lg mt-4">Got questions? Need advice? Tap into our experience and get specialist advice from our friendly team.</p>
                </div>
                <div class="w-1/3 text-right relative z-10">
                    <Btn link="/" type="white" class="inline-flex">Learn more</Btn>
                </div>
            </div>
        </div>
    </div>  
</template>