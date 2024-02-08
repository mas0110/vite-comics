<script>
import CompSlider from './CompSlider.vue';

export default{
    name: "Main",
    components:{
        CompSlider,
    }
}
</script>

<template>
<div class="cont"> 
    <button class="btn btn-primary mt-3 currentBtn">current series</button>
</div>
<div>
    <div class="content">
        <CompSlider/>
        <div class="d-flex justify-content-center">
            <button class="btn btn-primary mt-3">Load More</button>
        </div>
    </div>
</div>
<div class="buyComics">
    <ul>
        <li>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="digital">
            <span>DIGITAL COMICS</span>
        </li>
        <li>
            <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
            <span>DC MERCHARDISE</span>
        </li>
        <li>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
            <span>SUBSCRIPTION</span>
        </li>
        <li>
            <img src="../assets/img/buy-comics-shop-locator.png" alt="location">
            <span>COMIC SHOP LOCATOR</span>
        </li>
        <li>
            <img src="../assets/img/buy-dc-power-visa.svg" alt="visa">
            <span>DC POWER VISA</span>
        </li>
    </ul>
</div>

</template>

<style scoped lang="scss">
.cont{
    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 250px;
    position: relative;
}
.currentBtn{
    position: absolute;
    bottom: 0px;
    transform: translateY(50%);
    left: 200px;
}
.content{
    background-color: #1C1C1C;
    color: white;
    padding: 25px;
    div{
        margin: 0 auto;
        width: 80%;
    }
}
.buyComics{
background-color:#0082F9 ;
padding: 20px;
color: white;
display: flex;
justify-content: center;
ul{
    display: flex;
    gap: 15px;
        li{
        display: flex;
        gap: 15px;
        align-items: center;
            img{
            height: 45px;
            }
        }
}
}
</style>
