<template>
    <main>
        <MainContenutoComponent/>
        <MainShopComponent/>
    </main>
</template>

<script>
    import MainContenutoComponent from './MainContenutoComponent.vue'
    import MainShopComponent from './MainShopComponent.vue'

    export default {
        name: 'MainComponent',
        components: {
            MainContenutoComponent,
            MainShopComponent
        }
    }
</script>

<style lang="scss" scoped>

</style>