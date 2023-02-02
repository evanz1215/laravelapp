<template>
  <div>
    <div>Index</div>
    <div>{{ props.message }}</div>
  </div>
</template>


<script setup>


const props = defineProps({
  message: String,
});
</script>
