<script>
export default {
    name: 'SezioneSocialFooter'
}

</script>

<template>
    <div class="container-bottone">
        <button>SIGN UP NOW!</button>
    </div>
    <div class="container-img">
        <div>FOLLOW US</div>
        <a href=""> <img src="../assets/img/footer-facebook.png" alt="logo-fb"></a>
        <a href=""> <img src="../assets/img/footer-twitter.png" alt="logo-twitter"></a>
        <a href=""> <img src="../assets/img/footer-youtube.png" alt="logo-yt"></a>
        <a href=""> <img src="../assets/img/footer-pinterest.png" alt="logo-pin"></a>
        <a href=""> <img src="../assets/img/footer-periscope.png" alt="logo-periscope"></a>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/variables.scss';


.container-bottone {

    button {
        color: white;
        padding: .9375rem;
        border: 2px solid variables.$secondary-color-text;
        background-color: variables.$backgound-color-footer;
        font-weight: bold;
        padding: .9375rem;
        font-size: .875rem;
    }
}

.container-img {

    display: flex;
    align-items: center;

    div {
        font-weight: bold;
        color: variables.$secondary-color-text;
        display: inline-block;
        margin-right: 1.875rem;

    }

    img {
        margin: 0 .625rem;
    }


}
</style>