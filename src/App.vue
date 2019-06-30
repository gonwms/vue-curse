<template>
  <div id="app">
    <!-- app -->

  
    <AppHeader msg="un Header"></AppHeader>
    <Article></Article>
    <AppFooter></AppFooter>
    



    <!-- end app -->
  </div>
</template>

<script>
  import AppHeader from './components/Header.vue'
  import Article from './components/Article.vue'
  import AppFooter from './components/Footer.vue'
  
  export default {
    name: 'app',
    components: {
      AppHeader, Article, AppFooter,
    }
  }
</script>

<style>

  html, body {
    padding: 0;
    margin: 0;
    font-family: sans-serif;
  }

  #app{
    display:grid;
    height: 100vh;
    grid-template-rows: 1fr 4fr 1fr;
    /* align-items: center; */
    /* justify-content: center */
  }
  .container{
    width: 100%;
    height: 100%;
    display: grid;
    justify-items: center;
    padding: 20px;
    box-sizing:border-box
  }
</style>
