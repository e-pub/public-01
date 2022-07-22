<template>
  <headerTop msg="Welcome to Your Vue.js App"/>
</template>

<script>
import headerTop from './components/headerTop.vue'

export default {
  name: 'App',
  components: {
    headerTop
  }
}
</script>


<style>
* {margin:0; padding:0;}
ul {display:inline-block;}
li {float:left; list-style:none;}
.right {float:right !important;}
.bg {background:red;}
.bgb {background:blue;}
</style>