<template>
  <div>
    <navbar></navbar>
    <nuxt/>
  </div>
</template>

<script>
  import Navbar from '../components/Navbar'

  export default {
    components: {
      Navbar
    }
  }
</script>

<style>
  html, body {
    font-family: 'Lato', sans-serif;
    height:100%;
  }
  
  body {
  display:flex;
  justify-content: center;
  align-items:center;
  text-align:center;
  }
</style>