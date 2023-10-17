<template>
  <input 
    class="text-white rounded-lg pa-3"
    type="email"
    placeholder="Seu melhor email"
  >
</template>

<script setup>

</script>

<style lang="scss" scoped>
input {
  background-color: #232326;
  border: none;
  outline: none;
  &:focus {
    border: 2px solid rgb(0, 157, 255);
  }
}
</style>