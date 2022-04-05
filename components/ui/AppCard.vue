<template>
  <div
    class="flex flex-wrap flex-col text-center sm:p-28 md:p-2 bg-black rounded-2xl sm:my-6 md:m-auto sm:w-full md:w-1/4"
  >
    <section class="gap-1 p-2 sm:flex sm:flex-col sm:items-center">
      <slot name="card-image"></slot>
      <div>
        <h2 class="text-2xl font-extrabold text-stone-100 py-6">
          {{ props.title }}
        </h2>
        <CardButton :btn-text="'Book Now!'"></CardButton>
      </div>
    </section>
  </div>
</template>

<script setup>
const props = defineProps({
  title: {
    type: String,
    default: "Card Title",
  },
  img: {
    type: String,
    default: "Image Url",
  },
  altText: {
    type: String,
    default: "Image altText",
  },
});
</script>
