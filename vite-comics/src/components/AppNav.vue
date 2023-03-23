<script>

export default {
    name: 'AppNav'
}
</script>
<template>
    <nav>
        <ul>
            <li><a href=""> CHARACTERS</a></li>
            <li><a href=""> COMICS</a></li>
            <li><a href=""> MOVIES</a></li>
            <li><a href=""> TV</a></li>
            <li><a href=""> GAMES</a></li>
            <li><a href=""> COLLECTIBLES</a></li>
            <li><a href=""> VIDEOS</a></li>
            <li><a href=""> FANS</a></li>
            <li><a href=""> NEWS</a></li>
            <li><a href=""> SHOP</a></li>
        </ul>
    </nav>
</template>
<style lang="scss" scoped>
@use '../styles/variables.scss';

ul {
    list-style: none;
    display: flex;


    li {
        padding: 10px;


        a {
            color: variables.$primary-color-text;
            text-decoration: none;
            font-size: 0.95rem;
            font-weight: bold;
            padding-bottom: 15px;



        }

        &:hover {
            border-bottom: 5px solid variables.$secondary-color-text;

            a {
                color: variables.$secondary-color-text;
            }
        }



    }


}
</style>