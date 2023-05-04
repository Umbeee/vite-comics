<script>
export default {
       name: "lightBlueContainer"
    }

</script>

<template>

    <div class="main">
        <div class="container">

            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>digital comics</p>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>dc merchandise</p>
            </div>

            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>subscription</p>
            </div>

            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>comic shop locator</p>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>dc power visa</p>
            </div>
        </div>
    </div>

    
</template>

<style lang="scss" scoped>

    .main{
        background-color: rgb(2,130,249);
        color: white;

        .container{
            width: 80%;
            margin: 0 auto;
            height: 100%;
            display: flex;
            justify-content: space-between;

            div{
                display: flex;
                align-items: center;
                width: 15%;
                gap: 15px;
                img{
                    height: 40%;
                }
                p{
                    text-transform: uppercase;
                    font-size: 0.8em;
                }
            }
        }
    }


</style>