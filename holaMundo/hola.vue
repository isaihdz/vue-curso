<template>
  <div>
    <p>Lorem ipsum </p>
    <p>{{ text }} </p>
  </div>
  
</template>

<script>
  export default {
    data(){
      return{
        text: "Hola"
      };
    }
  };
</script>

<style>
  p{
    color: papayawhip;
  }
</style>