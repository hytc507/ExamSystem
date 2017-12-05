<template>
  <div class="hello">
    {{msg}}
  </div>
</template>

<script>
  export default {
    name: 'Test',
    data () {
      return {
        msg: '2333'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    color: #666666;
  }
</style>
