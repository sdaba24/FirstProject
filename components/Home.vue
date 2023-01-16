<template>
    <div id="home">
        <Header/>
        <MainImages/>
      
        <center>
    <!--<div class="aboutMe">
        <p>Hi! I'm a current student at Barnard College currently pursuing degrees in 
            Medical Anthropology and Computer Science. 
    </div>
            <p class="homepageheading"> Some of my socials: </p>-->

    <div>
        <div class="mediaButtons">
            <mediaButtons/>
        </div>
        
    </div>
        </center>
    <div>
        <Resume/>
    </div>
    </div>
</template>


<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:wght@100&family=Noto+Serif&family=Poppins:wght@200;400&family=Raleway:wght@300&family=Roboto+Condensed&family=Rowdies:wght@300&display=swap');
    body{
        background-color: whitesmoke;
    }
    .aboutMe{
        font-family:'Noto Serif', serif; 
    }
    .homepagetext{
        font-size: 20px;
        color: darkblue;
    }
/* text next to image */
    .image{
        display: flex;
        align-items: left;
        justify-content: left;
    }
</style>

<script>
    //a prop is..

import HomeImages from './MainImages.vue';

    //an attribute is...
export default {
    name: "Home",
    components: { HomeImages }
}
</script>