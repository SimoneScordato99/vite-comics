<script>
    export default {
        name: "MainCard",
        props:['fabio']
    }
</script>

<template>
    <div class="fumetto">
        <img :src="fabio.thumb" alt="">
        <div>
            <h3 class="price">{{ fabio.price }}</h3>
            <h3 class="series">{{ fabio.series }}</h3>
            <h3 class="type">{{ fabio.type }}</h3>
        </div>
    </div>
</template>

<style scoped lang="scss">
    .fumetto{
        color: white;
        padding: 5px;
        width: calc(100%/6 - 20px);
        img{
            width: 100%;
        }
        .series{
            font-size: 2rem;
        }
    }
</style>