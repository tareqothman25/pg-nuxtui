<script setup lang="ts">
definePageMeta({
  title: 'Exclusive Subscription Discounts',
  description: 'Join Ocevera’s membership plans and enjoy exclusive discounts on luxury fragrances.',
  navOrder: '5',
  type: 'secondary',
  icon: 'i-mdi-cash-percent',
})
</script>

<template>
  <section class="py-16 bg-gray-50 dark:bg-gray-900">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <!-- Heading -->
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold tracking-tight text-gray-900 dark:text-white">
          Ocevera Membership Plans
        </h2>
        <p class="mt-4 text-lg text-gray-600 dark:text-gray-300">
          Save more on every order — choose your plan and enjoy exclusive discounts all year long.
        </p>
      </div>

      <!-- Pricing Cards Grid -->
      <div class="grid gap-8 sm:grid-cols-2 lg:grid-cols-3">
        <!-- Bronze Plan -->
        <div
          class="bg-white dark:bg-gray-800 shadow-lg rounded-2xl p-8 flex flex-col border border-gray-200 dark:border-gray-700">
          <h3 class="text-xl font-semibold text-gray-900 dark:text-white">Bronze</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Great for occasional perfume lovers.</p>

          <!-- Price -->
          <div class="mt-6">
            <span class="text-4xl font-bold text-gray-900 dark:text-white">49.99 JOD</span>
            <span class="text-lg font-medium text-gray-500 ml-1">/year</span>
          </div>

          <!-- Discount -->
          <div class="mt-2">
            <span class="text-primary-600 font-semibold text-lg">10% OFF</span> on all orders
          </div>

          <ul class="mt-6 space-y-3 text-gray-600 dark:text-gray-300 flex-1">
            <li>Minimum order: 40 JOD</li>
            <li>Valid for 12 months</li>
            <li>Free standard shipping in Jordan</li>
          </ul>
          <UButton color="primary" size="lg" class="mt-8 w-full">Join Bronze</UButton>
        </div>

        <!-- Silver Plan -->
        <div class="bg-white dark:bg-gray-800 shadow-lg rounded-2xl p-8 flex flex-col border-2 border-primary-500">
          <h3 class="text-xl font-semibold text-primary-600">Silver</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Ideal for regular fragrance enthusiasts.</p>

          <!-- Price -->
          <div class="mt-6">
            <span class="text-4xl font-bold text-gray-900 dark:text-white">74.99 JOD</span>
            <span class="text-lg font-medium text-gray-500 ml-1">/year</span>
          </div>

          <!-- Discount -->
          <div class="mt-2">
            <span class="text-primary-600 font-semibold text-lg">20% OFF</span> on all orders
          </div>

          <ul class="mt-6 space-y-3 text-gray-600 dark:text-gray-300 flex-1">
            <li>Minimum order: 30 JOD</li>
            <li>Valid for 12 months</li>
            <li>Free express shipping in Jordan</li>
          </ul>
          <UButton color="primary" size="lg" class="mt-8 w-full">Join Silver</UButton>
        </div>

        <!-- Gold Plan -->
        <div
          class="bg-white dark:bg-gray-800 shadow-lg rounded-2xl p-8 flex flex-col border border-gray-200 dark:border-gray-700">
          <h3 class="text-xl font-semibold text-gray-900 dark:text-white">Gold</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Perfect for our most loyal luxury clients.</p>

          <!-- Price -->
          <div class="mt-6">
            <span class="text-4xl font-bold text-gray-900 dark:text-white">99.99 JOD</span>
            <span class="text-lg font-medium text-gray-500 ml-1">/year</span>
          </div>

          <!-- Discount -->
          <div class="mt-2">
            <span class="text-primary-600 font-semibold text-lg">30% OFF</span> on all orders
          </div>

          <ul class="mt-6 space-y-3 text-gray-600 dark:text-gray-300 flex-1">
            <li>No minimum order</li>
            <li>Valid for 12 months</li>
            <li>Free worldwide shipping</li>
            <li>Exclusive early access to new releases</li>
          </ul>
          <UButton color="primary" size="lg" class="mt-8 w-full">Join Gold</UButton>
        </div>
      </div>
    </div>
  </section>
</template>
