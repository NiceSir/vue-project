<template>
  <div id="app">
    <header></header>
    <main><Parent/></main>
    <footer></footer>
  </div>
</template>

<script>
import Parent from 'components/Parent'
export default {
  name: 'App',
  components: {
    Parent
  }
}
</script>

<style lang="scss"  type="text/css" scoped>
$width:300px;
#app{
  .contain{

  }
}
</style>
