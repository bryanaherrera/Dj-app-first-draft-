<template>
  <div class="header">
    <h3>{{ msg }}</h3>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h3{
    color: #ffff;
  }
</style>
