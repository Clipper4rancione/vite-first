<script>

import AppTitle from './components/AppTitle.vue';


export default {
  name: 'App',
  components:{
    AppTitle
  }  
}
</script>

<template>
  <div class="container">
    <AppTitle/>
  </div>
</template>


<style>
  .container{
    border: 1px solid #b1b1b1;
    padding: 40px;
  }
</style>