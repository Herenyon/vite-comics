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
    <div>
        <div><img :src="img"></div>
        <h3>{{ title }}</h3>
    </div>
</template>

<style lang="scss" scoped></style>