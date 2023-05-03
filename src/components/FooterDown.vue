<script>
    export default {
        name:"FooterDown",
        data(){
            return{

            }
        }
    }
</script>

<template>
    <div class="container">
        <button class="btn">sign-up now!</button>
        <div class="social">
            <div class="follow">follow us</div>
            <div class="icons">
                <img src="../../public/img/footer-facebook.png" alt="">
                <img src="../../public/img/footer-twitter.png" alt="">
                <img src="../../public/img/footer-youtube.png" alt="">
                <img src="../../public/img/footer-pinterest.png" alt="">
                <img src="../../public/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .container{
        background-color: #303030;
        min-height: 150px;
        position: relative;
        z-index: 2;
        padding: 30px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .btn{
            height: 50%;
            border: 6px solid #0C7CEC;
            padding: 20px;
            background-color: #303030;
            font-size: 3rem;
            text-transform: uppercase;
            color: white;
        }
        .social{
            display: flex;
            width: 40%;
            .follow{
                font-size: 3.5rem;
                text-transform: uppercase;
                color: #0C7CEC;
            }
            .icons{
                display: flex;
                justify-content: space-between;
                align-items: center;
                img{
                    padding: 10px;
                }
            }
        }
    }
</style>