<template>
    <div>
        <span>Footer</span>
        <FooterInfo/>
        <FooterAboutus/>
    </div>
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