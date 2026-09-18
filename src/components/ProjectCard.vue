<script setup>
defineProps({
  title: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="project-card">
    <div class="project-card__header">
      <h2 class="project-card__title">
        {{ title }}
      </h2>
    </div>
    <div class="project-card__main">
      <slot />
    </div>
  </div>
</template>
