<template >
<div>
 <nuxt-link to="/about">

<button class="body3 medium">About us</button>
 </nuxt-link></div>
</template>

<script lang="ts">

</script>

<style lang="scss" scoped>
button {
  transition: $transition-default;
  border-radius: 8px;
  border: none;
  outline: none;
  padding: 12px 20px;
  margin-right: 12px;
  cursor: pointer;
  background-color: $background-color;
  appearance: none;

  &:hover,
  &:focus,
  &:active {
    filter: brightness(90%);
  }
}
</style>
