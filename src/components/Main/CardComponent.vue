<template>
    <div class="areaCarte">
        <div class="carta">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
            <div>Titolo Carta</div>
        </div>
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
.areaCarte
{
    padding: 10px 0;
    .carta
    {
        >*
        {
            padding: 10px 20px;
        }

        div
        {
            font-size: 1.2rem;
        }
    }
}
</style>