<template>
    <main>
   
            <cardListAlbum/>
   
    </main>
</template>

<script>
import cardListAlbum from '../components/cardListAlbum.vue'
export default {
    components: {
        cardListAlbum,

    }

}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";
main{
    background-color: $colorBody ;
    padding-top: 50px;
 }

</style>