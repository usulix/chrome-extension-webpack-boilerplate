<template>
  <div class="message">{{ msg }}</div>
</template>

<script>
  export default {
    data () {
      return {
        msg: 'Hello from Vue Options component!'
      }
    }
  }
</script>

<style>
  .message {
    color: green;
  }
</style>
