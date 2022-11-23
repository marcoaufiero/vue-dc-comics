<template>
    <div class="sect-settings">
        <div class="container">
            <div>
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="footer-socials">
                <h2>FOLLOW US</h2>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterBottom'
    }
</script>

<style lang="scss" scoped>
    .sect-settings{
        padding: 30px 0;
        background-color: #303030;
    }

    .container{
        width: 70%;
        margin-inline: auto; 
        display: flex;
        justify-content: space-between;
        align-items: center;

        button{
            padding: 10px;
            background-color: #303030;
            border: 2px solid #0282F9;
            color: white;
            font-size: 1.1rem;
        }

        .footer-socials{
            display: flex;
            align-items: center;
            
            *{
                margin: 0 10px;
            }

            h2{
                font-size: 1.2rem;
                color: #0282F9;
            }

        }
    }
</style>