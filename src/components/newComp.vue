<template>
  <div>
    <button @click="customClickHandler">Click me</button>
  </div>
</template>

<script>
export default {
  methods: {
    customClickHandler() {
      // Your custom logic for button click goes here
      console.log('Button clicked! This is a custom method.');
    }
  }
}
</script>

<style scoped>
/* Add your component-specific styles here */
</style>