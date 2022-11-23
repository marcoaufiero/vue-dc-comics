<template>
    <div class="sect-padding">
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="">
            <ul class="nav-menu d-flex">
                <li><a href="">CHARACTERS</a></li>
                <li><a href="">COMICS</a></li>
                <li><a href="">MOVIES</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">GAMES</a></li>
                <li><a href="">COLLECTIBLES</a></li>
                <li><a href="">VIDEOS</a></li>
                <li><a href="">FANS</a></li>
                <li><a href="">NEWS</a></li>
                <li><a href="">SHOP</a></li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HeaderComp'
    }
</script>

<style lang="scss" scoped>

    .sect-padding{
        padding: 20px 0;
    }

    .container{
        width: 70%;
        margin-inline: auto; 
        display: flex;
        justify-content: space-between;
        align-items: center;

        ul{
        display: flex;

            li{
                list-style: none;
                margin: 0 15px;
                font-size: 0.8rem;
                font-weight: 600;
                
                
                a{
                    text-decoration: none;
                    color: black;
                }
            }
        }
    }

    

</style>