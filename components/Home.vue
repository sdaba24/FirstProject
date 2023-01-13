<template>
    <div id="home">
        <topNav/>
        <Header/>
        <MainImages/>
      
        <center>
    <div class="text">
        <p>Hi! I'm a current student at Barnard College currently pursuing degrees in 
            Medical Anthropology and Computer Science. </p>
    </div>
            <p class="homepageheading"> Some of my socials: </p>
            <a href="https://www.instagram.com/soretii.iii/"> link to insta! </a>

    <div>
        <p class="link"> If you want to check out my resume...</p>
    </div>
        </center>
    <div id="ResumeSect">
        <Resume/>
    </div>
    </div>

</template>


<style>
    body{
        background-color: ivory;
    }
    .homepagetext{
        font-size: 25px;
        color: black;
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