<template>
    <NuxtLink :to="link" class="transition duration-200 flex items-center px-8 py-4 flex-shrink-0 rounded-lg font-bold" :class="type">
        <slot></slot>
        <svg v-if="arrow" class="ml-4" width="16" height="10" viewBox="0 0 16 10" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M11.0586 0.390625L10.7773 0.636719C10.6367 0.8125 10.6367 1.05859 10.7773 1.23438L13.7305 4.15234H0.546875C0.300781 4.15234 0.125 4.36328 0.125 4.57422V4.92578C0.125 5.17188 0.300781 5.34766 0.546875 5.34766H13.7305L10.7773 8.30078C10.6367 8.47656 10.6367 8.72266 10.7773 8.89844L11.0586 9.14453C11.1992 9.32031 11.4805 9.32031 11.6562 9.14453L15.7344 5.06641C15.9102 4.89062 15.9102 4.64453 15.7344 4.46875L11.6562 0.390625C11.4805 0.214844 11.1992 0.214844 11.0586 0.390625Z" fill="currentColor"/>
        </svg>
    </NuxtLink>
</template>

<script>
export default {
    props: {
        'link': String,
        'type': String,
        'arrow': Boolean
    }
}
</script>

<style>
.default {
    @apply bg-brand text-white hover:bg-brand-dark;
}
.white {
    @apply bg-white text-brand hover:bg-gray-200;
}
.white-outline {
    @apply bg-transparent border border-white text-white hover:bg-brand-dark;
}
</style>