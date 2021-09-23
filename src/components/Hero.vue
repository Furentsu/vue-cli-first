<template>
    <div class="container">
        <Title class="title-position"/>
        <img src="../assets/turkey.jpg" alt="Hot air baloons in Cappadocia">
    </div>
</template>

<script>
import Title from './Title.vue'

export default {
    name: 'Hero',
    components: {
        Title,
    }
}
</script>

<style scoped lang="scss">

.container {
    width: 100vw;
    height: 100vh;
    position: relative;
    overflow: hidden;
}
.title-position {
    position: absolute;
    bottom: 100px;
    left: 100px;

}

.container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

</style>