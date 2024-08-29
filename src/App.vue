<template>
  <router-view />
</template>


<script>
 import AOS from "aos";
 export default {
  mounted(){
    AOS.init();
  }
 }

</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Nerko+One&display=swap');


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Nerko One", cursive;
  scroll-behavior: smooth
}
</style>
