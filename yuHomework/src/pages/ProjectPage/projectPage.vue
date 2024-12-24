<template>
  <header-container id="headerContainer">
    <Header />
  </header-container>
  <main-container id="mainContainer">
    <div id="projectContainer">
      <div id="projectItem1"></div>
      <div id="projectItem2"></div>
      <div id="projectItem3"></div>
      <div id="projectItem4"></div>
      <div id="projectItem5"></div>
      <div id="projectItem6"></div>
    </div>
  </main-container>
  <footer-container id="footerContainer">
    <Footer />
  </footer-container>
</template>

<script setup>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
</script>

<style>
#mainContainer {
  width: 100%;
  height: 90vh;
  background-color: pink;
}
#footerContainer {
  bottom: 0;
  left: 0;
  width: 100%;
  height: 10vh;
}
#headerContainer {
  width: 100vw;
  height: 7vh;
}
#projectContainer {
  padding: 20px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  grid-template-rows: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
  background-color: antiquewhite;
}
#projectContainer > div {
  background-color: #15a581;
  border-radius: 10px;
  width: 100%;
  height: 100%;
}
#projectItem1 {
  grid-row-start: 2;
  grid-row-end: 3;
  grid-column-start: 2;
  grid-column-end: last-line;
}
#projectItem2 {
  grid-row-start: 3;
  grid-row-end: 4;
  grid-column-start: 2;
  grid-column-end: last-line;
}
#projectItem3 {
  grid-row-start: 4;
  grid-row-end: 5;
  grid-column-start: 2;
  grid-column-end: last-line;
}
#projectItem4 {
  grid-row-start: 5;
  grid-row-end: 6;
  grid-column-start: 2;
  grid-column-end: last-line;
}
#projectItem5 {
  grid-row-start: 6;
  grid-row-end: 7;
  grid-column-start: 2;
  grid-column-end: last-line;
}
#projectItem6 {
  grid-row-start: 7;
  grid-row-end: 8;
  grid-column-start: 2;
  grid-column-end: last-line;
}
</style>