<template>
    <div class="bg-azzurro">
        <div class="contenitore65 padding-y-40">
            <ul class="flex-mode f-justify-around f-align-center">
                <li><span>[]</span><span>Testo</span></li>
                <li><span>[]</span><span>Testo</span></li>
                <li><span>[]</span><span>Testo</span></li>
                <li><span>[]</span><span>Testo</span></li>
                <li><span>[]</span><span>Testo</span></li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default
    {
        name: 'MainShopComponent'
    }
</script>

<style lang="scss" scoped>

    // ----- GENERALE --------------------------------------------------------------- //
    .bg-azzurro
    {
        background-color: #0282f9;
    }

    ul li span
    {
        padding: 0 5px;
    }
    
</style>