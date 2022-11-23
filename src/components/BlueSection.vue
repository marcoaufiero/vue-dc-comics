<template>
    <div class="sect-settings">
        <div class="container">
            <div class="menu-button">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="menu-button">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHADISE</span>
            </div>
            <div class="menu-button">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="menu-button">
                <img class="" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="menu-button">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC VISA</span>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'BlueSection'
    }
</script>

<style lang="scss" scoped>
    .sect-settings{
        padding: 60px 0;
        background-color: #0282F9;
    }

    .container{
        width: 70%;
        margin-inline: auto; 
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .menu-button{
        display: flex;
        align-items: center;
        
        img{
            width: 60px;
            height: 65px;
            margin: 0 10px;
        }

        span{
            color: white;
        }
    }

</style>