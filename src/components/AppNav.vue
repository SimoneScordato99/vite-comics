<script>
    export default {
        name:"AppNav",
        data(){
            return{
                navbar: [
                    {
                        nome: 'character',
                        soldato: true
                    },
                    {
                        nome: 'comics',
                        soldato: true
                    },
                    {
                        nome: 'movies',
                        soldato: true
                    },
                    {
                        nome: 'tv',
                        soldato: true
                    },
                    {
                        nome: 'games',
                        soldato: true
                    },
                    {
                        nome: 'collectibles',
                        soldato: true
                    },
                    {
                        nome: 'videos',
                        soldato: true
                    },
                    {
                        nome: 'fans',
                        soldato: true
                    },
                    {
                        nome: 'news',
                        soldato: true
                    },
                    {
                        nome: 'shop',
                        soldato: true
                    },
                ]
            }
        }
    }
</script>

<template>
    <nav>
        <img src="/img/dc-logo.png" alt="logo dc">
        <ul>
            <li v-for="(elem, index) in navbar" :key="index" ><a href="#">{{ elem.nome }}</a></li>
        </ul>
    </nav>
</template>

<style lang="scss" scoped>
    nav{
        height: 200px;
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 30px;
            ul{
                display: flex;
                justify-content: space-around;
                height: 100%;
                width: 60%;
                li{
                    display: flex;
                    align-items: center;
                    height: 100%;
                    list-style: none;
                    
                    a{
                        display: flex;
                        align-items: center;
                        text-decoration: none;
                        text-transform: uppercase;
                        font-size: 1.25rem;
                        height: 100%;
                        color: black;
                        flex: 1;
                        &:hover{
                            border-bottom: 6px solid #0C7CEC;
                            color: #0C7CEC;
                        }
                    }
                }
            }
        }
</style>