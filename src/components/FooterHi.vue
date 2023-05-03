<script>
    export default {
        name:"FooterHi",
        data(){
            return{
                mario: [
                    {
                        nome:"digital comics",
                        src:"/img/buy-comics-digital-comics.png"
                    },
                    {
                        nome:"dc merchandise",
                        src:"/img/buy-comics-merchandise.png"
                    },
                    {
                        nome:"subscription",
                        src:"/img/buy-comics-subscriptions.png"
                    },
                    {
                        nome:"comic shop locator",
                        src:"/img/buy-comics-shop-locator.png"
                    },
                    {
                        nome:"dc power visa",
                        src:"/img/buy-dc-power-visa.svg"
                    },
                ]
            }
        }
    }
</script>

<template>
    <div>
        <div v-for="(elem, index) in mario" class="lementi" >
            <img :src="elem.src" :alt="elem.nome">
            <span>{{ elem.nome }}</span>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    div{
        background-color: #0C7CEC;
        height: 300px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        position: relative;
        z-index: 2;
        div{
            padding: 20px;
            text-transform: uppercase;
            color: white;
            
            margin: 0 auto;
            img{
                padding: 10px;
                height: 40%;
            }
            svg{
                height: 40%;
            }
            span{
                font-size: 1.5rem;
            }
        }
    }
</style>