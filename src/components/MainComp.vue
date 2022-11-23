<template>
    <div>
        <MainBox/>
        <BlueSection/>
    </div>
</template>

<script>
    import MainBox from './MainBox.vue'
    import BlueSection from './BlueSection.vue'

    export default {
        name: 'MainComp',
        components: {
            MainBox,
            BlueSection
        }
    }
</script>

<style lang="scss" scoped>
    

</style>