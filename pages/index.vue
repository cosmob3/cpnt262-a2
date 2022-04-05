<template>
  <TheHero />
  <ShortBio />
  <div class="flex justify-evenly py-10">
    <!-- Card 1 -->
    <AppCard :title="'Family Photos'">
      <template #card-image>
        <img
          src="https://images.pexels.com/photos/11341064/pexels-photo-11341064.jpeg?auto=compress&cs=tinysrgb&dpr=2"
          alt="Image of Plane"
        />
      </template>
    </AppCard>
    <!-- Card 2 -->
    <AppCard :title="'Weddings'">
      <template #card-image>
        <img
          src="https://images.pexels.com/photos/11341064/pexels-photo-11341064.jpeg?auto=compress&cs=tinysrgb&dpr=2"
          alt="Image of Plane"
        />
      </template>
    </AppCard>
    <!-- Card 3 -->
    <AppCard :title="'Other Special Events'">
      <template #card-image>
        <img
          src="https://images.pexels.com/photos/11341064/pexels-photo-11341064.jpeg?auto=compress&cs=tinysrgb&dpr=2"
          alt="Image of Plane"
        />
      </template>
    </AppCard>
  </div>
</template>
