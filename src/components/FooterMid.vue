<script>
    export default {
        name:"FooterMid",
        data(){
            return{

            }
        }
    }
</script>

<template>
    <div class="sfondo">
        <div class="liste">
            <div class="lista">
                <h3>dc comics</h3>
                <ul>
                    <li><a href="">Character</a></li>
                    <li><a href="">Comics</a></li>
                    <li><a href="">Movies</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">Games</a></li>
                    <li><a href="">Videos</a></li>
                    <li><a href="">News</a></li>
                </ul>
                <h3>shop</h3>
                <ul>
                    <li><a href="">Shop DC</a></li>
                    <li><a href="">Shop DC collectibles</a></li>
                </ul>
            </div>
            <div class="lista">
                <h3>dc</h3>
                <ul>
                    <li><a href="">Term Of Use</a></li>
                    <li><a href="">Privacy Policy(New)</a></li>
                    <li><a href="">Ad Choices</a></li>
                    <li><a href="">Advertisement</a></li>
                    <li><a href="">Jobs</a></li>
                    <li><a href="">Subscriptions</a></li>
                    <li><a href="">Talent Workplace</a></li>
                    <li><a href="">CPSC Certificates</a></li>
                    <li><a href="">Rating</a></li>
                    <li><a href="">Shop Help</a></li>
                    <li><a href="">Contact Us</a></li>
                </ul>
            </div>
            <div class="lista">
                <h3>sites</h3>
                <ul>
                    <li><a href="">DC </a></li>
                    <li><a href="">MAD Magazine</a></li>
                    <li><a href="">DC Kids</a></li>
                    <li><a href="">DC Universe</a></li>
                    <li><a href="">DC Power Visa</a></li>
                </ul>
            </div>
        </div>
        <img src="../../public/img/dc-logo-bg.png" alt="">
    </div>
</template>

<style lang="scss" scoped>
    .sfondo{
        background-image: url(../../public/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 450px;
        position: relative;
        .liste{
            width: 100%;
            display: flex;
            .lista{
                color: white;
                padding: 50px;
                
                h3{
                    padding: 10px 0;
                    font-size: 2rem;
                    text-transform: uppercase;
                }
                li{
                    list-style: none;
                    a{
                        text-decoration: none;
                        color: rgb(133, 133, 133);
                    }
                }
            }
           
        }
        img{
            position: absolute;
            top: -20px;
            right: 0;
        }
    }
</style>