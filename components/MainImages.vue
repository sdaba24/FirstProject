<template>

    <div class="picContainer">
     <div class="imageOne">
        <img src="soretiYellow.ico" alt="image of Soreti"
                width="350"
                height="450"> </div>
        <div class="imageTwo">
            <img src="soretiBlue.ico" alt="imaege of Soreti"
                width="400"
                height="540"> </div>
        <div class="imageThree">
            <img src="soretiImageTwo.ico" alt="Image of Soreti"
                    width="300"
                    height="440">
        </div>
        </div>

<!-- one and then two -->
<!-- 
    <div class="picContainer2">
     <div id="imagesOne">
        <img src="soretiYellow.ico" alt="image of Soreti"
                width="300"
                height="400"> </div>
        <div id="imagesTwo">
            <img src="soretiBlue.ico" alt="imaege of Soreti"
                width="300"
                height="400"> 
        
            <img src="soretiImageTwo.ico" alt="Image of Soreti"
                    width="300"
                    height="440">
        
                </div>
    </div>
-->

</template>


<style> 
    .picContainer{
        display: flex;
        flex-direction: row;
        align-items: stretch;
        flex-wrap: nowrap;
        justify-content: space-evenly;
    }

/* one and then two */
/*
    .picContainer2{
        display: flex;
        justify-content: space-around;
    }
    #imagesTwo{
        display: flex;
        flex-direction: column;
    }
    #imagesOne{
        display: flex;
        align-items: center;
    }
*/
</style>