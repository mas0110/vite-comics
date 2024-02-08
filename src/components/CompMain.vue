<script>
export default{
    name: "Main"
}
</script>

<template>
<div class="content">
    <h3>** Content goes here **</h3>
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
.content{
    background-color: #1C1C1C;
    color: white;
    padding: 25px;
}
.buyComics{
background-color:#0082F9 ;
padding: 20px;
color: white;
position: relative;
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
