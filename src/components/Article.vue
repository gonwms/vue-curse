<template>
  <div class="container">
    <ul>
      <li v-for="name in names">{{name}}</li>
    </ul>
  </div>
</template>

<script>


export default {
  name: 'AppBody',
  data: function(){
    return {
      names: ["Gon", "Perci", "Mili" ]
    }
  },
  props: {
    msg: String
  }
}
</script>

<style lang="css" >

</style>