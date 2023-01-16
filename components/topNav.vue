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
  <div class="searchbar">
  
    <!--made class
    want to put nav into a menu bar, how tho?-->
    <div class="topnav">
      <div class="home">
        <a class="home" href="./Homee"> Home</a>
      </div>
      <div class="cont">
        <a class="cont" href="./Contact"> Contact</a>
      </div>
      <div class="ab">
        <a class="ab" href="./About"> About</a>
      </div>
    </div>
 
</div>
  </template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:wght@100&family=Noto+Serif&family=Poppins:wght@200;400&family=Raleway:wght@300&family=Roboto+Condensed&family=Rowdies:wght@300&display=swap');
  .searchbar{
    font-family: 'Noto Serif', serif;
    display: flex;
        flex-direction: row;
        align-items: stretch;
        flex-wrap: nowrap;
        justify-content:space-around;
    color: black;
    font-size: 20px;
    
  }

  .home{
    color: black;
    font-size: 20px;
  }
  .cont{
    color: black;
    font-size: 20px;
  }
  .ab{
    color: black;
    font-size: 20px;
  }
/* style of overall header */
  .topnav{
    background-color: whitesmoke;
  }
  /* changing color of words on hover */
  .topnav a:hover{
    color: pink;
  }
</style>

<script>
  export default{

  }
</script>