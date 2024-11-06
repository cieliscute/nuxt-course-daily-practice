<template>
  <p>{{ title }}</p>
</template>
<script setup>
defineProps({
  title: String
})
</script>
<style>
p{
  font-size: 18px;
  font-weight: bold;
  margin: 16px 0 8px;
  text-align: center;
}
</style>