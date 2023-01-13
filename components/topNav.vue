<!-- responsive navigation bar-->

<!--<div class="NavBar" id="myTopNav">
    <a href="#Home" class=""active">Home</a>
    <a href="#About Me>About</a>
</div> -->

<!--
<base-nav type ="primary"
        v-model=""showMenu1" ></base-nav>
        
<a slot="brand" class="navbar-brand" href="#">NavBar</a>

<ul class=""nav-item active"
    <li class="nav-item active"
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
    </li>
</ul>
    </base-nav>
    -->

<template>
  <center>
    <!--made class
    want to put nav into a menu bar, how tho?-->
    <div class="topnav">
      <a class="active" href="#home"> Home</a>
      <a class="cont" href="#contact"> Contact</a>
      <a class="ab" href="#about"> About</a>
    </div>
  </center>
  </template>

<style>
/* style of text */
  .active{
    color: maroon;
    font-size: 17px;
  }
  .cont{
    color: maroon;
    font-size: 17px;
  }
  .ab{
    color: maroon;
    font-size: 17px;
  }
/* style of overall header */
  .topnav{
    background-color: lavenderblush;
  }
  /* changing color of words on hover */
  .topnav a:hover{
    color: black;
  }
</style>

<script>
  export default{

  }
</script>