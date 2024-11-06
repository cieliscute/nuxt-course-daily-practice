<template>
  <img :src="imageSrc" :alt="altText">
</template>
<script setup>
defineProps({
  imageSrc: String,
  altText: String
})
</script>

<style>
img{
  width: 100%;
  height: auto;
  border-radius: 8px 8px 0 0;
}
</style>