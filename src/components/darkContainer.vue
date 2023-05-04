<script>
export default {
       name: "darkContainer"
    }

</script>

<template>

    <div class="main">
        <div class="container">

            <span>
                in questo container realizzerò tutte le cards
            </span>
           

        </div>
    </div>


</template> 

<style lang="scss" scoped>

    .main{

        background-color: black;

        height: 150px;

        color: white;

        .container{

            width: 80%;
            margin: 0 auto;

            display: flex;
            align-items: center;
            
            height: 100%;
        }

    }


</style>