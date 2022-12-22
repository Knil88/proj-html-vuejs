<script >
import AppHeader from './components/AppHeader.vue';
import AppSection from './components/AppSection.vue';
import AppSection_2 from './components/AppSection_2.vue';
import AppSection_3 from './components/AppSection_3.vue';
import AppSection_4 from './components/AppSection_4.vue';
import AppSection_5 from './components/AppSection_5.vue';
import AppFooter from './components/AppFooter.vue';

export default{
  components:{
    AppHeader,
  AppSection,
  AppSection_2,
  AppSection_3,
  AppSection_4,
  AppSection_5,
  AppFooter
 
  }
  
}
</script>
  
<template>
  <AppHeader/>
  
  <main>
    <AppSection/>
    <AppSection_2/>
    <AppSection_3/>
    <AppSection_4/>
    <AppSection_5/>
  </main>
  
  <AppFooter/>
</template>

<style lang="scss" scoped>
  @use"./components/styles/general.scss" as*;
  @use"./components/styles/partial/variables.scss" as*;
</style>
