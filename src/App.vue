<script setup>
import Badge from "./components/atoms/Badge.vue";
import Button from "./components/atoms/Button.vue";
import ProjectCard from "./components/ProjectCard.vue";
</script>

<template>
  <main>
    <h1>Case UI System</h1>
    <ProjectCard title="Button 按鈕元件">
      <Button />
    </ProjectCard>
    <ProjectCard title="Badge 標籤元件">
      <Badge />
    </ProjectCard>
  </main>
</template>
