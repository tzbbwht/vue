<!--main component-->
<!--所有的子组件都是在其下面  router也是其子组件-->
<template>
  <div id="app">
    <index></index>
    <layout></layout>
    <!--<slide></slide>-->
  </div>
</template>

<script>
  import layout from './components/layout'
  import slide from './components/slide'
//  import index from './components/index'
export default {
   components: {
    layout,
  slide
//     index
  }
 }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
