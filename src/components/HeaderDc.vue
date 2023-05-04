<script>
    export default {
       name: "HeaderDc"
    }
</script>

<template>
    <div class="header">
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="">
            <ul>
                <li><a href="#">characters</a></li>
                <li><a href="#">comics</a></li>
                <li><a href="#">movies</a></li>
                <li><a href="#">tv</a></li>
                <li><a href="#">games</a></li>
                <li><a href="#">collectibles</a></li>
                <li><a href="#">videos</a></li>
                <li><a href="#">fans</a></li>
                <li><a href="#">news</a></li>
                <li><a href="#">shop</a></li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>

    .header{
        background-color: white;
        height: 150px;

        

        .container{
            width: 80%;
            margin: 0 auto;
            display: flex;
            align-items: center;
            justify-content: space-between;

           

            ul{
                display: flex;
                gap: 10px;
                line-height: 147px;
                li{
                    list-style-type: none;

                    a{
                        text-decoration: none;
                        color: black;
                        text-transform: uppercase;
                        font-size: 0.8em;
                    }
                }
                li:hover{
                    border-bottom: 4px solid rgb(12,124,236);

                    a{
                        color: rgb(12,124,236);
                    }
                }
            }


        }


    }


</style>