<script setup>
import Button from "./components/atoms/Button.vue";
import ProjectCard from "./components/ProjectCard.vue";
</script>

<template>
  <main>
    <h1>Case UI System</h1>
    <ProjectCard>
      <template #title> Button </template>
      <Button />
    </ProjectCard>
  </main>
</template>
