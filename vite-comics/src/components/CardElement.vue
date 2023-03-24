<script>

export default {
    name: 'CardElement',
    props: {
        img: String,
        title: String
    }
}
</script>

<template>
    <div class="container">
        <a href="">
            <img :src="img">
            <h4>{{ title }}</h4>
        </a>
    </div>
</template>

<style lang="scss" scoped>
.container {
    word-wrap: break-word;
    overflow-wrap: break-word;
    width: min-content;
    margin-top: 1.4375rem;

    h4 {
        text-decoration: none;
        color: white;

    }
}
</style>