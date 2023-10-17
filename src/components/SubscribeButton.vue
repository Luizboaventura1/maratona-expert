<template>
  <button
    class="font-weight-bold text-white px-4 py-3 rounded-lg"
  >
    <slot />
  </button>
</template>

<script setup>

</script>

<style lang="scss" scoped>
button {
  background-color: rgb(0, 157, 255);
  transition: .3s;
  &:hover {
    box-shadow: 0 0 20px rgba(0, 157, 255, 0.398);
  }
}
</style>