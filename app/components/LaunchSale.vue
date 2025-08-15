<template>
  <section>
    <UCard>
      <div
        class="bg-clip-text bg-gradient-to-r from-purple-400 launch-sale-grid font-extrabold text-transparent to-primary-600">
        <!-- Title -->
        <div class="flex lg:flex lg:items-center" style="grid-area: sale">
          <span class="-tracking-wide font-semibold text-3xl uppercase lg:text-center">
            Ocevera Launch Offer
          </span>
        </div>

        <!-- Discount -->
        <div class="justify-center lg:flex lg:items-center" style="grid-area: discount">
          <span class="-tracking-wide font-bold text-6xl uppercase whitespace-nowrap lg:text-6xl">
            10% Off
          </span>
        </div>

        <!-- Tagline -->
        <div style="grid-area: categories" class="flex items-center">
          <span class="-tracking-wide font-extrabold text-right uppercase w-full text-center">
            Luxury Scents • Limited Editions
          </span>
        </div>
      </div>
    </UCard>
  </section>
</template>

<style scoped>
.launch-sale-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  grid-template-areas:
    'discount categories'
    'sale categories';
  gap: 20px;
  grid-area: sale;
}

@media (min-width: 1024px) {
  .launch-sale-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr;
    grid-template-areas: 'sale discount categories';
    gap: 20px;
  }
}
</style>
