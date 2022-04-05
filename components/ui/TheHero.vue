<template>
  <section class="grid sm:grid-cols-1 md:grid-cols-3 py-10">
    <div class="col-span-2">
      <div class="flex flex-wrap justify-evenly">
        <img
          class="w-1/3 -rotate-12"
          src="../../assets/images/Flower Lady.jpg"
          alt="Flower Lady"
        />
        <img
          class="w-1/3 rotate-3"
          src="../../assets/images/Man in Black.jpg"
          alt="Man in Black"
        />
      </div>
    </div>
    <div class="flex flex-col justify-center text-center">
      <h2 class="text-5xl m-24">Your No. 1 Stop for Portrait Photography</h2>
      <NuxtLink
        class="flex m-auto rounded-lg bg-teal-700 hover:bg-teal-900 text-white text-2xl justify-center w-48 p-3"
        to="/portfolio"
      >
        See More
      </NuxtLink>
    </div>
  </section>
</template>
