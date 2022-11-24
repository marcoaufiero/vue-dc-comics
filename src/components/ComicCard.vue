<template>
    <div class="card">
        <div class="img-box">
            <img :src="comicDetails.thumb" alt="">
        </div>
        <h5>{{comicDetails.series.toUpperCase()}}</h5>
    </div>
</template>

<script>
    export default {
        name: 'ComicCard',
        props:{
            comicDetails: Object
        }
    }
</script>

<style lang="scss" scoped>
    
    .card{
        
        width: calc(100% / 6);  
        margin-top: 10px;
        padding: 20px;

        &:hover{
            cursor: pointer;
            scale: 1.3;
            transition: 0.3s;
        }
        
        .img-box{

            width: 100%;
            aspect-ratio: 1/1;
            overflow: hidden;

            img{
                
                width: 100%;
            }
        }  
    }

    h5{
        color: white;
        margin-top: 20px;
    }

</style>