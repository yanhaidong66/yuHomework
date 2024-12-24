<template>
<header-container id="headerContainer">
    <Header/>
</header-container>
<main-container id="mainContainer">
    
</main-container>
<footer-container id="footerContainer">
    
</footer-container> 

  
</template>

<script setup>
import Header from "@/components/Header.vue";
</script>

<style>
#headerContainer {
  width: 100vw;
  height: 7vh;
}
#mainContainer {
  position:absolute;
  top: 7vh;
  left: 0;
  width: 100vw;
  height: 89vh;
  border: 2px solid black;
}
#footerContainer {
  position:absolute;
  top:96vh;
  left: 0;
  width: 100vw;
  height: 11vh;  
  border: 2px solid black;
  background-color: red;
}
</style>