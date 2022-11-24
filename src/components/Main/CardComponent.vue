<template>
    
    <div class="carta">
        <div>
            <img :src="dettagliCarta.thumb">
        </div>
        <div>{{dettagliCarta.series.toUpperCase()}}</div>
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


    div:last-child
    {
        font-size: 1.2rem;
        padding-top: 20px;
    }
}
</style>