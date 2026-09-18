<template>
  <section class="project-card">
    <header class="project-card__header">
      <h2 class="project-card__title">
        <slot name="title" />
      </h2>
    </header>

    <div class="project-card__main">
      <slot />
    </div>
  </section>
</template>
