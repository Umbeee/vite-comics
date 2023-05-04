<script>
export default {
       name: "darkListContaier"
    }

</script>

<template>
    <div class="main">

        <div class="container">
            <div class="list">
                <ul>
                    <li><h3>dc comics</h3></li>
                    <li>characters</li>
                    <li>comics</li>
                    <li>movies</li>
                    <li>tv</li>
                    <li>games</li>
                    <li>videos</li>
                    <li>news</li>
                    <li><h3>shop</h3></li>
                    <li>shop dC</li>
                    <li>shop dC collectibles</li>
                </ul>
                <ul>
                    <li><h3>dc</h3></li>
                    <li>terms of use</li>
                    <li>privacy policy (new)</li>
                    <li>ad choices</li>
                    <li>advertising</li>
                    <li>jobs</li>
                    <li>subscriptions</li>
                    <li>talent workshops</li>
                    <li>CPSC certificates</li>
                    <li>ratings</li>
                    <li>shop help</li>
                    <li>contact us</li>
                </ul>
                <ul>
                    <li><h3>sites</h3></li>
                    <li>dc</li>
                    <li>mad magazine</li>
                    <li>dC kids</li>
                    <li>dC universe</li>
                    <li>dC power visa</li>
                </ul>
            </div>

            <div class="bg-logo">

            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>

    .main{
        background-image: url('../assets/img/footer-bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        height: 400px;
        

        .container{
            height: 100%;
            width: 80%;
            margin: 0 auto;
            display: flex;
            align-items: center;
            justify-content: space-between;

            .list{
                display: flex;
                gap: 25px;
                ul{
                    list-style-type: none;
                    color: rgb(122, 122, 122);
                    li{
                        margin-top: 3px;
                        text-transform: capitalize;
                        h3{
                            font-size: 1.4em;
                            text-transform: uppercase;
                            color: white;
                            margin-bottom: 15px;
                            margin-top: 15px;
                        }

                    }
                }
            }
            .bg-logo{
                
                width: 45%;
                height: 100%;
                background-image: url('../assets/img/dc-logo-bg.png');
                background-size: cover;
                background-position: left;
               
            }
        }
        
    }


</style>
