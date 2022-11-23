<template>
    <header class="margin-y-">
        <div class="contenitore65 flex-mode f-justify-between f-align-center">
            <img class="width-80" src="../../assets/img/dc-logo.png" alt="Logo_DC">
            <ul class="flex-mode">
                <li>CHARACTERS</li>
                <li class="active">COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </div>
    </header>
</template>

<script>
    export default {
        name: 'HeaderComponent'
    }
</script>

<style lang="scss" scoped>
    // ----- PRESET --------------------------------------------------------------- //
    .margin-y-
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

    ul
    {
        list-style-type: none;
    }

    ul > li
    {
        font-size: 0.8rem;
        font-weight: bold;
        padding: 0 15px;
    }

    .contenitore65
    {
        width: 65vw;
        margin: 0 auto;
    }

    .width-80
    {
        width: 80px;
    }

    .active
    {
        color: #0282f9;
        border-bottom: 3px solid #0282f9;
    }

    // ----- FLEX --------------------------------------------------------------- //

    .flex-mode
    {
        display: flex;
    }

    .f-align-center
    {
        align-items: center;
    }

    .f-justify-between
    {
        justify-content: space-between
    }


</style>