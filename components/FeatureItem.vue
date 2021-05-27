<template>
  <div class="w-1/2 p-4">
    <img class="mb-6" :src="require(`~/assets/images/${icon}`)" :alt="title">
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

</style>