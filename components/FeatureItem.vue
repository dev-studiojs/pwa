<template>
  <div class="w-1/2 md:w-full lg:w-1/2 p-4">
    <img class="mb-6 feature-icon" :src="require(`~/assets/images/${icon}`)" :alt="title">
    <h3 class="text-2xl font-semibold">{{title}}</h3>
    <p class="my-3">{{description}}</p>
  </div>
</template>

<script>
export default {
    props: {
        icon: String,
        title: String,
        description: String
    }
}
</script>

<style>
.feature-icon {
  width: 100px;
}
</style>