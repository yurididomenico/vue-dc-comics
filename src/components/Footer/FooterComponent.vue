<template>
    <footer>
        <FooterInfo/>
        <FooterAboutus/>
    </footer>
</template>

<script>
    import FooterInfo from './FooterInfo.vue';
    import FooterAboutus from './FooterAboutus.vue';
    
    export default {
        name: 'FooterComponent',
        components: {
            FooterInfo,
            FooterAboutus
        }
    }
</script>

<style lang="scss" scoped>

</style>