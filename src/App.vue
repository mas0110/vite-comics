<script>
import CompHeader from './components/CompHeader.vue';
import CompMain from './components/CompMain.vue';
import CompFooter from './components/CompFooter.vue';


export default{
  components: {
    CompHeader,
    CompMain,
    CompFooter,
  }
}

</script>

<template>
    <div class="mainContainer">
        <CompHeader/>
        <CompMain/>
        <CompFooter/>
    </div>
</template>

<style>
li{
    list-style: none;
}
.mainContainer{
    height: 100vh;
}
</style>
