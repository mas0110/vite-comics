<script>
export default{
    name: "ciao"
}
</script>

<template>
    <div>
        <figure>
           <img src="../assets/img/dc-logo-bg.png" alt="">
        </figure>
        <div>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTION</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </div>
    </div>
</template>

<style scoped>
div{
   display: flex;
   justify-content: space-around;
   vertical-align: baseline;
   align-items: center;
   padding-block: 10px;
}
div figure{
    margin: 0;
}
div figure img{
   height: 80px;

}
div div ul{
    display: flex;
    gap: 20px;
    align-items: center;
    margin-top: 10px;
    color:#573F51 ;
}
div div ul li:hover{
    color: blue;
    border-bottom: 1px solid blue;
    padding-bottom: 50px;
}
</style>
