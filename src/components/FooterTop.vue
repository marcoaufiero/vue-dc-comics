<template>
    <div class="sect-settings">
        <div class="container">
            <div class="d-flex">
                <div class="footer-menu">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="footer-menu">
                    <h3>DC</h3>
                    <ul>
                        <li><a href="">Terms Of Use</a></li>
                        <li><a href="">Privacy Policy (new)</a></li>
                        <li><a href="">Ad Choice</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">Talent Workshops</a></li>
                        <li><a href="">CPSC Certificates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                </div>
                <div class="footer-menu">
                    <h3>SITES</h3>
                    <ul>
                        <li><a href="">DC</a></li>
                        <li><a href="">MAD Magazine</a></li>
                        <li><a href="">DC Kids</a></li>
                        <li><a href="">DC Universe</a></li>
                        <li><a href="">Dc Power Visa</a></li>
                    </ul>
                </div>
            </div>
            
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterTop'
    }
</script>

<style lang="scss" scoped>
    .sect-settings{
        padding: 50px 0;
        background: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        background-repeat: no-repeat;
    }

    .d-flex{
        display: flex;
    }

    .container{
        width: 70%;
        margin-inline: auto; 
        display: flex;
        justify-content: space-between;

        img{
            width: 300px;
        }
    }

    .footer-menu{
        margin: 0 20px;

        h3{
            color: white;
            margin-bottom: 10px;
        }

        ul{
            margin-bottom: 20px;

            li{
            list-style: none;
            line-height: 20px;
            
                a{
                    text-decoration: none;
                    font-size: 0.8rem;
                    color: grey;
                }
            }
        }
        
    }

</style>