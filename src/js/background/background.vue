<template>
  <div class="message">{{ msg }}</div>
</template>

<script>
  export default {
    data () {
      return {
        msg: 'Hello from Vue Background component!'
      }
    }
  }
</script>

<style>
  .message {
    color: orange;
  }
</style>
