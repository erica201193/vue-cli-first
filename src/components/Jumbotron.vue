<template>
<div id="jumbotron">
<img :src="require('@/assets/immagine-prova.jpg')" alt="" id="jumbo-img">
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
#jumbotron {
    height: 80vh;
}

#jumbo-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    opacity: 0.8;


}
</style>
