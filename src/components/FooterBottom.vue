<template>
    <div class="sect-settings">
        <div class="container">
            <div>
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="footer-socials">
                <h2>FOLLOW US</h2>
                <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
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

            &:hover{
                cursor: pointer;
                background-color: #0282F9;
                transition: 0.3s;
            }
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