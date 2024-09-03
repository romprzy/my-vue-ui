<template>
  <button class="my-button">
    <slot>Submit</slot>
  </button>
</template>

<script>
export default {
  name: 'MyButton'
}
</script>

<style scoped>
.my-button {
  background-color: #001C30;
  color: #fff;
  border: none;
  border-radius: 5px;
  padding: 0.5rem 1rem;
  cursor: pointer;
}

button:is(:hover, :focus, :active) {
  background-color: #176B87;
}
</style>
