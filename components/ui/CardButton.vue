<template>
  <div
    class="bg-yellow-300 hover:bg-yellow-500 rounded-lg text-center my-10 sm:mx-0 md:mx-10 sm:p-1 md:p-4"
  >
    <NuxtLink class="text-xl" to="/contact">{{ btnText }}</NuxtLink>
  </div>
</template>

<script>
export default {
  props: ["btnText"],
};
</script>
