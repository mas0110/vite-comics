<script>
export default{
    name: "Footer"
}
</script>

<template>
<div class="bgContainer">
    <div class="ulContainer">
        <div>
            <ul>
                <h4>DC COMICS</h4>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
                <h4>SHOP</h4>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>            
        </div>
        <div>
            <ul>
                <h4>DC</h4>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact</li>
            </ul>            
        </div>
        <div>
            <ul>
                <h4>SITES</h4>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>
    </div>
    <figure>
        <img src="../assets/img/dc-logo-bg.png" alt="logo">
    </figure>
</div>
<div class="signUp">
    <button class="btn text-light border border-primary">SIGN-UP NOW!</button>
    <div>
        <h5 class="text-primary">FOLLOW US</h5>
        <ul>
            <li><img src="../assets/img/footer-facebook.png" alt=""></li>
            <li><img src="../assets/img/footer-twitter.png" alt=""></li>
            <li><img src="../assets/img/footer-youtube.png" alt=""></li>
            <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
            <li><img src="../assets/img/footer-periscope.png" alt=""></li>
        </ul>
    </div>
</div>
</template>

<style scoped>
.bgContainer{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size:cover ;
   background-repeat: no-repeat;
   display: flex;
   justify-content: space-around;
   align-items: center;
   position: relative;
   width: 100%;

}
.ulContainer{
    display: flex;
    font-size: 15px;
    color: white;
}
.ulContainer ul li{
    opacity: 55%;
}
.signUp{
    background-color: #303030;
    color: white;
    display: flex;
    justify-content: space-around;
    padding: 30px;
    position: absolute;
    width: 100%;

}
.signUp div{
    display: flex;
    align-items: center;
}
.signUp div ul{
    display: flex;
    gap: 10px;
    align-items: center;
}
</style>
