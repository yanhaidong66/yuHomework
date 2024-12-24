<template>
  <div id="headerContainer">
    <div id="leftMainContainer">

    </div >
    <div id="rightMainContainer">
      <ul>
        <li><router-link to="/home">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
        <li><router-link to="/contact">Contact</router-link></li>
        <li><router-link to="/login">Login</router-link></li>
        <li><router-link to="/register">Register</router-link></li>
        <li><router-link to="/logout">Logout</router-link></li>
      </ul>
    </div>
    
  </div>
</template>

<script setup>
</script>

<style>
#headerContainer {
  width: 100vw;
  height: 7vh;
  position:absolute;
  top:0;
  left:0;
  border: 2px solid black;
}
#leftMainContainer {
  width: 10%;
  height: 100%;
  border: 2px solid black;
  display: inline-block;
  position:absolute;
  top:0;
  left:20%;
}
#rightMainContainer {
  width: 40%;
  height: 100%;
  border: 2px solid black;
  display: inline-block;
  position:absolute;
  top:0;
  right:15%;
}
div>ul{
  height: 100%;
  width: 100%;
}
div>ul>li{
  display: inline-flex;
  margin-right: 2%;
  height: 100%;
  width: 12%;
  color: rgb(44, 43, 43);
  font-size: 130%;
  text-decoration: none;
  align-items: center;
  justify-content: center;
  position: relative;
  top: -22%;
  border: 2px solid black;
}
</style>