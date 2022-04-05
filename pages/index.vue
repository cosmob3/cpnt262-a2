<template>
  <TheHero />
  <ShortBio />
  <div class="flex sm:flex-col md:flex-row justify-evenly py-10">
    <!-- Card 1 -->
    <AppCard :title="'Family Photos'">
      <template #card-image>
        <img src="../assets/images/family-photo.jpg" alt="Family Photo" />
      </template>
    </AppCard>

    <!-- Card 2 -->
    <AppCard :title="'Weddings'">
      <template #card-image>
        <img
          src="../assets/images/flowers-n-heels.jpg"
          alt="Flowers and Heels Photo"
        />
      </template>
    </AppCard>

    <!-- Card 3 -->
    <AppCard :title="'Other Special Events'">
      <template #card-image>
        <img src="../assets/images/graduation.jpg" alt="Graduation Photo" />
      </template>
    </AppCard>
  </div>
</template>
