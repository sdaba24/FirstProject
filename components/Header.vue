<template>
  <!--  <center>
    <div class="header">
        <img src="progNotPerf.ico" alt="Header of Pink Flowers"
                width="700"
                height="200"> 
    </div>
</center>-->
<div class="header">
    <nameLogo/>
<div class="topNav">
        <topNav/>
    </div>

<div class="headerWords">
    <center>
            <h1 class="homepageheading">Hey Hey! </h1>
    </center>
</div>  
</div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:wght@100&family=Noto+Serif&family=Poppins:wght@200;400&family=Raleway:wght@300&family=Roboto+Condensed&family=Rowdies:wght@300&display=swap');

    .pageHead{
        display: flex;
        flex-direction: column;
        gap: 1px;
    }
    .homepageheading{
        font-size: 37px;
    }
    .headerWords{
        font-family: 'Noto Serif', serif;
    }
    .topNav{
        display: flex;
        flex-direction: row;
        align-items: flex-end;
    }
</style>
