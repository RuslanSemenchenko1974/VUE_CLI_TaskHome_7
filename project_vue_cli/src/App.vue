<template> 
  
<headerSight/>
<mainFirstPage/>
<footerSight/>
<hr>
<headerSight/>
<mainTwoPage/>
<footerSight/>
<hr>
<headerSight/>
<mainThirdPage/>
<footerSight/>
<hr> 
<headerSight/>
<MainForthPage/>
<footerSight/>
<hr>
<headerSight/>
<MainFifthPage/>
<footerSight/>

</template>

<script>
import headerSight from './components/headerSight.vue';
import mainTwoPage from './components/mainTwoPage.vue';
import mainFirstPage from './components/mainFirstPage.vue';
import mainThirdPage from './components/mainThirdPage.vue';
import footerSight from './components/footerSight.vue';
import MainForthPage from './components/mainForthPage.vue';
import MainFifthPage from './components/mainFifthPage.vue';
export default {  
  components: {
    headerSight,
    footerSight,
    mainTwoPage,
    mainFirstPage,
    mainThirdPage,
    MainForthPage,
    MainFifthPage
}
}
</script>

<style lang="scss">

</style>
