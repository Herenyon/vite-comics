<script>
export default {
    name: 'SezioneLinkFooter'
}
</script>

<template>
    <div class="container-liste">
        <div class="container-lista-sx">
            <h3> DC COMICS</h3>
            <ul>
                <li><a href=""> Characters</a></li>
                <li><a href=""> Comics</a></li>
                <li><a href=""> Movies</a></li>
                <li><a href=""> Tv</a></li>
                <li><a href=""> Games</a></li>
                <li><a href=""> Videos</a></li>
                <li><a href=""> News</a></li>
            </ul>
            <h3>SHOP</h3>
            <ul>
                <li><a href=""> Shop DC</a></li>
                <li><a href=""> Shop DC Collectibles</a></li>
            </ul>
        </div>
        <div class="container-lista-cen">
            <h3>DC</h3>
            <ul>
                <li><a href=""> Terms of Use</a></li>
                <li><a href=""> Privacy policy (New)</a></li>
                <li><a href=""> Ad Choices</a></li>
                <li><a href=""> Advertising</a></li>
                <li><a href=""> Jobs</a></li>
                <li><a href=""> Subscriptions</a></li>
                <li><a href=""> Talent Workshop</a></li>
                <li><a href=""> CPSC Certificates</a></li>
                <li><a href=""> Ratings</a></li>
                <li><a href=""> Shop Help</a></li>
                <li><a href=""> Contact Us</a></li>

            </ul>
        </div>
        <div class="container-lista-dx">
            <h3>SITES</h3>
            <ul>
                <li><a href=""> DC</a></li>
                <li><a href=""> MAD Magazine</a></li>
                <li><a href=""> DC Kids</a></li>
                <li><a href=""> DC Universe</a></li>
                <li><a href=""> DC Power Visa</a></li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/variables.scss';


.container-liste {
    display: flex;

    h3 {
        color: white;
        margin-top: 1.875rem;
    }

    a {
        text-decoration: none;
        color: variables.$tertiary-color-text;

        &:hover {
            border-bottom: 1px solid variables.$tertiary-color-text;
        }
    }

    ul {
        list-style: none;

        margin: 1.5625rem 1.875rem 0 0;
        font-size: .90rem;

        li {
            margin-bottom: .3125rem;


        }
    }

}
</style>