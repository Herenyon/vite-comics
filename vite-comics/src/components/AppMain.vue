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
    <section class="container-list">
        <div class="container-cards">

            <Cards />
        </div>

        <div class="button">
            <button>LOAD MORE</button>
        </div>
    </section>
    <section>


    </section>
</template>

<style lang="scss">
@use '../styles/variables.scss' as *;

.container-comic {


    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 25rem;
    padding: 1.125rem 18.75rem;
    display: flex;
    align-items: center;


}

.container-list {
    color: white;
    background-color: #1c1c1c;
    padding: 1.125rem 18.75rem;


    .container-cards {
        display: flex;
        align-items: center;

        word-wrap: break-word;

    }

    .button {
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: 3.125rem;

        button {
            color: inherit;
            font-weight: bold;
            border: none;
            background-color: $secondary-color-text;
            padding: .5rem 3.75rem;
        }
    }

}
</style>