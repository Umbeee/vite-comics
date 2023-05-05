<script>

import comicsCards from './comicsCards.vue';

export default {
       name: "darkContainer",
       components: {
        comicsCards
       }
    }

</script>

<template>

    <div class="main">

        <div id="jumbo">
            <span>current series</span>
        </div>

        <div class="container">

            <comicsCards/>
           

        </div>
    </div>


</template> 

<style lang="scss" scoped>

    .main{

        background-color: rgb(28,28,28);
        color: white;

        .container{
            width: 80%;
            margin: 0 auto;
        }


        #jumbo{
            background-image: url('../assets/img/jumbotron.jpg');
            background-repeat: no-repeat;
            background-size: cover;
            height: 300px;
            width: 100%;
            position: relative;

            span{
                position: absolute;
                padding: 15px;
                color: white;
                background-color: rgb(2,130,249);
                text-transform: uppercase;
                font-weight: bold;
                bottom: -25px;
                left: 100px;
            }
        }
    }


</style>