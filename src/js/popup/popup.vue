<template>
  <div class="message">{{ msg }}</div>
</template>

<script>
  export default {
    data () {
      return {
        msg: 'Hello from Vue Pop Up component!'
      }
    }
  }
</script>

<style>
  .message {
    color: blue;
  }
</style>
