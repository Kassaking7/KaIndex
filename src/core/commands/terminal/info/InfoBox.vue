<template>
  <div>关于本站：KaIndex </div>
  <div>
    <a href="https://github.com/Kassaking7/KaIndex" target="_blank">
      Open source
    </a>
  </div>
  <div></div>
  <div>
    Author: Kassaking7
  </div>
</template>

<script setup lang="ts">
interface InfoBoxProps {
  seconds: string;
}

const props = withDefaults(defineProps<InfoBoxProps>(), {});
</script>

<style scoped></style>
