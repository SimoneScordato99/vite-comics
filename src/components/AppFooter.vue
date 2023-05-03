<script>
import FooterHi from './FooterHi.vue'
import FooterMid from './FooterMid.vue'
import FooterDown from './FooterDown.vue'
    export default {
        name:"AppFooter",
        components:{
            FooterHi,
            FooterMid,
            FooterDown
        }
        
    }
</script>

<template>
    <footer>
        <FooterHi/>
        <FooterMid/>
        <FooterDown/>
    </footer>
</template>

<style lang="scss" scoped>

</style>