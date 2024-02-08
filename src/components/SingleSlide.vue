<script>
export default{
    name:"slide",
    props:{
        propsTitolo: "stringa",
        propsImg: "stringa",
    }
}
</script>

<template>
    <div class="posterCol">
        <img :src="propsImg" alt="">
        <div>{{ propsTitolo }}</div>        
    </div>
</template>

<style scoped lang="scss">
.posterCol{
    flex-basis: calc(100% / 6);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    div{
        text-align: center;
    }
}



</style>
