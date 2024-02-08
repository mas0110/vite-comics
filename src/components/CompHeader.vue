<script>
export default{
    name: "header",
    Data(){
        return{
            headerLinks: [
                {
                    name:'CHARACTERS',
                    current:false,
                },
                { 
                    name:'COMICS',
                    current:true,
                },
                {
                    name:'MOVIES',
                    current:false,
                },
                {
                    name:'TV',
                    current:false,
                },
                {
                    name:'GAMES',
                    current:false,
                },
                {
                    name:'COLLECTION',
                    current:false,
                },
                {
                    name:'VIDEOS',
                    current:false,
                },
                {
                    name:'FANS',
                    current:false,
                },
                {
                    name:'NEWS',
                    current:false,
                },
                {
                    name:'SHOP',
                    current:false,
                },
            ]
        }
    }
}
</script>

<template>
    <div>
        <figure>
           <img src="../assets/img/dc-logo.png" alt="">
        </figure>
        <div>
            <ul>
                <li v-for="(element, index) in headerLinks" :key="index">{{ element.name }}</li>
            </ul>
            <!-- <ul> -->
                <!-- <li>CHARACTERS</li> -->
                <!-- <li>COMICS</li> -->
                <!-- <li>MOVIES</li> -->
                <!-- <li>TV</li> -->
                <!-- <li>GAMES</li> -->
                <!-- <li>COLLECTION</li> -->
                <!-- <li>VIDEOS</li> -->
                <!-- <li>FANS</li> -->
                <!-- <li>NEWS</li> -->
                <!-- <li>SHOP</li> -->
            <!-- </ul> -->
        </div>
    </div>
</template>

<style scoped lang="scss">
.active{
    color:blue;
    border-bottom: 3px solid blue;
}
div{
   display: flex;
   justify-content: space-around;
   vertical-align: baseline;
   align-items: center;
   padding-block: 10px;
   background-color: white;
   div figure{
            margin: 0;
       img{
            height: 80px;
        }
    }
    div ul{
        display: flex;
        gap: 20px;
        align-items: center;
        margin-top: 10px;
        color:#573F51 ;
    }
}
</style>
