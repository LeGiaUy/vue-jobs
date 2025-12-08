<script setup>
import { RouterLink } from 'vue-router';
import { ArrowLeftCircleIcon } from '@heroicons/vue/24/outline';
</script>

<template>
    <section>
      <div class="container m-auto py-6 px-6">
        <RouterLink
          to="/jobs"
          class="text-green-500 hover:text-green-600 flex items-center"
        >
          <ArrowLeftCircleIcon class="size-6"></ArrowLeftCircleIcon> Back to Job Listings
        </RouterLink>
      </div>
    </section>
</template>