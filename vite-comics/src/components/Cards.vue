<script>
import CardElement from './CardElement.vue';

export default {
    name: 'Cards',

    components: {
        CardElement
    },

    data() {
        return {
            cards: [
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://picsum.photos/185/185",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    }
};

</script>

<template>
    <section>
        <h2>CURRENT SERIES</h2>
        <div>
            <div class="container-cards-ses">

                <CardElement v-for="card in cards" :img="card.thumb" :title="card.series" />
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.container-cards-ses {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
}
</style>

