<script>
import AppTitle from '../components/AppTitle.vue'  

export default {
    name: "AppHero",
    components: {
        AppTitle
    }
}
</script>

<template>
    <figure id="jumbo-img">
        <AppTitle/>
    </figure>
</template>

<style scoped>
#jumbo-img {
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url("../assets/img/jumbotron.webp");
    background-size: cover;
    background-position: center;
}

@media (min-width: 1024px) {}
</style>