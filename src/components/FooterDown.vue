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
                <a href=""><img src="../../public/img/footer-facebook.png" alt=""></a>
                <a href=""><img src="../../public/img/footer-twitter.png" alt=""></a>
                <a href=""><img src="../../public/img/footer-youtube.png" alt=""></a>
                <a href=""><img src="../../public/img/footer-pinterest.png" alt=""></a>
                <a href=""><img src="../../public/img/footer-periscope.png" alt=""></a>
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
            &:hover{
                border: 6px solid #4da3f9;
                background-color: #5c5c5c;
                font-size: 3.1rem;
            }
        }
        .social{
            display: flex;
            width: 30%;
            .follow{
                font-size: 3.5rem;
                text-transform: uppercase;
                color: #0C7CEC;
            }
            .icons{
                padding-left: 20px;
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