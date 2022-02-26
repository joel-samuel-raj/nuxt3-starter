<template>
  <div style="color: red">{{ msg }}</div>
</template>

<script lang="ts" setup>
defineProps<{ msg: string }>();
</script>
