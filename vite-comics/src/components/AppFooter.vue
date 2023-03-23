<script>
import AppSezioneAzzurraFooter from './AppSezioneAzzurraFooter.vue';
import SezioneLinkFooter from './SezioneLinkFooter.vue';
export default {
    name: 'AppFooter',
    components: {
        AppSezioneAzzurraFooter,
        SezioneLinkFooter
    }
}



</script>

<template>
    <div class="container-footer">
        <div class="container-azzurro">
            <AppSezioneAzzurraFooter />
        </div>

        <div class="container-link">
            <SezioneLinkFooter />
        </div>
        <div>parte contatti</div>
    </div>
</template>

<style lang="scss">
@use '../styles/variables.scss';

.container-footer {

    .container-azzurro {
        background-color: variables.$secondary-color-text;
        padding: 1.125rem 18.75rem;
        display: flex;
        align-content: center;
        justify-content: space-around;
        height: 0 auto;
    }

    .container-link {
        padding: 1.125rem 18.75rem;
        background-image: url(../assets/img/dc-logo-bg.png), url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: 30%, 100%;
        background-position: 80%;
    }
}
</style>
