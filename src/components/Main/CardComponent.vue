<template>
    
    <div class="carta p-relative">
        <div>
            <a href="#"><img :src="dettagliCarta.thumb"></a>
        </div>
        <div class="titolo">{{dettagliCarta.series.toUpperCase()}}</div>
    </div>

</template>

<script>
    export default {
        name: 'CardComponent',
        props: {
            dettagliCarta: Object
        }
    }
</script>

<style lang="scss" scoped>
.carta
{
    width: calc(100% / 6 - 30px);
    
    div:first-child
    {
        width: 100%;
        aspect-ratio: 1/1;
        overflow: hidden;
    }

    img
    {
        width: 100%;
    }


    .titolo
    {
        font-size: 1.2rem;
        padding-top: 20px;
    }

    &:hover img
    {
        opacity: 0.4;
        transform: scale(0.8);
        transition-duration: 500ms;
    }

    &:hover .titolo
    {
        position: relative;
        transform: scale(2) translateY(-30%);
        transition-duration: 500ms;
        background-color: black;
        color: #cfe4f8;
        box-shadow: 0 0 20px #0282f9;
        z-index: 1;
        padding: 0 5px;
        font-size: 0.8rem;
        border-radius: 10px;
    }
}
</style>