<template>
    <header class="margin-y-30">
        <a href="#" alt="Logo" class="contenitore65 flex-mode f-justify-between f-align-center">
            <img class="width-80" src="../../assets/img/dc-logo.png" alt="Logo_DC">
            <ul class="flex-mode">
                <li><a href="#">CHARACTERS</a></li>
                <li class="active"><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </a>
    </header>
</template>

<script>
    export default {
        name: 'HeaderComponent'
    }
</script>

<style lang="scss" scoped>
    // ----- PRESET --------------------------------------------------------------- //
    .margin-y-30
    {
        margin: 30px 0;
    }

    // ----- GENERALE --------------------------------------------------------------- //
    header
    {
        background-color: white;
        color: black;
        padding: 15px 0;
    }

    ul > li
    {
        font-size: 0.8rem;
        font-weight: bold;
        padding: 0 15px;
    }

    .width-80
    {
        width: 80px;
    }

    .active
    {
        color: #0282f9;
        // border-bottom: 3px solid #0282f9;
    }

    


</style>