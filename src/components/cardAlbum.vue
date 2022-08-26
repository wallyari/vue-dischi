<template>
<div class="music-card">
        <img src="https://upload.wikimedia.org/wikipedia/en/c/c6/How_Doth_the_Little_Crocodile_%281998%29.jpg" alt="">
        <h3 class="text-center text-white-50">title</h3>
        <h6 class="text-center text-white-50">artist <br> anno </h6> 
</div> 
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";
.music-card{
    background-color: $colorHeader;
    border: 1px solid rgb(0, 255, 81);
        img{
        width: 100%;
        }
    }
</style>