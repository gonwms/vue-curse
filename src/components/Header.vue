<template>
  <div class="container">
    <h4>{{ msg }}</h4>
  
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
  props: {
    msg: String
  }
}
</script>


<style scoped>
  .container{
    background: black;
    color:white;
  }
</style>
