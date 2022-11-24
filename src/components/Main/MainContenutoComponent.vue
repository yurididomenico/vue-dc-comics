<template>
    <main>
        <div class="jumbotron-image">
            <img src="../../assets/img/jumbotron.jpg" alt="Immagine Jumbotron">
        </div>
        <div class="contenitore65 padding-y-30 p-relative">
            <a href="#" id="botone-serieCorrente" class="btn bg-dc-blue font-size-14 font-weight-bold p-absolute">CURRENT SERIES</a>
            <CardComponent/>
        </div>
    </main>
</template>

<script>
    import CardComponent from './CardComponent.vue'

    export default
    {
        name: 'MainContenutoComponent',
        components: {
            CardComponent
        }
    }
</script>

<style lang="scss" scoped>
    main
    {
        background-color: #1c1c1c;
    }

    .jumbotron-image
    {
        height: 45vh;
        overflow: hidden;
    }

    #botone-serieCorrente
    {
        top: 0;
        left: 0;
        transform: translateY(-50%);
    }
    
</style>