<template>
    <main>
        <div class="jumbotron-image">
            <img src="../../assets/img/jumbotron.jpg" alt="Immagine Jumbotron">
        </div>
        <div class="contenitore65 padding-y-30">
            <span class="btn bg-dc-blue">TESTO</span>
            Scrivi Qui

        </div>
    </main>
</template>

<script>
    export default
    {
        name: 'MainContenutoComponent'
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
    
</style>