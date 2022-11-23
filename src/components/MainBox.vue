<template>
    <div class="sect-settings">
        <div class="container">
            <h2>Content goes here</h2>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'MainBox'
    }
</script>

<style lang="scss" scoped>
    .sect-settings{
        padding: 60px 0;
        background-color: black;
    }

    .container{
        width: 70%;
        margin-inline: auto; 
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    h2{
        color: white;
    }

</style>