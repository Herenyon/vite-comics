<script>
import Cards from './Cards.vue';
// import 
export default {
    name: 'AppMain',
    components: {
        Cards
    },
    props: {
        img: String,
        title: String
    }
}


</script>

<template>
    <section class="container-comic">

    </section>
    <section class="container-cards">
        <Cards />
    </section>
</template>

<style lang="scss">
.container-comic {


    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 25rem;
    padding: 1.125rem 18.75rem;
    display: flex;
    align-items: center;


}

.container-cards {
    color: white;
    background-color: #1c1c1c;
    padding: 1.125rem 18.75rem;
    display: flex;
    align-items: center;
}
</style>