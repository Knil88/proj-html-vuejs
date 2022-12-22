<script >
// Importazione component
import AppHeader from './components/AppHeader.vue';
import AppSection from './components/AppSection.vue';
import AppSection_2 from './components/AppSection_2.vue';
import AppSection_3 from './components/AppSection_3.vue';
import AppSection_4 from './components/AppSection_4.vue';
import AppSection_5 from './components/AppSection_5.vue';
import AppSection_6 from './components/AppSection_6.vue';
import AppSection_7 from './components/AppSection_7.vue';
import AppFooter from './components/AppFooter.vue';

export default{
  components:{
    AppHeader,
  AppSection,
  AppSection_2,
  AppSection_3,
  AppSection_4,
  AppSection_5,
  AppSection_6,
  AppSection_7,
  AppFooter
 
  }
  
}
</script>
  
<template>
  <AppHeader/>
  
  <main>

    <!-- questo div cambia il colore di sfondo che diventerà bianco dopo l'onda -->

   <div class="big-container">
    <AppSection/>
    <AppSection_2/>
    <AppSection_3/>
    <AppSection_4/>
   </div>
     <AppSection_5/>
    <div class="big-container">
      <AppSection_6/>
    </div>
    <AppSection_7/>
   
  </main>
  
  <AppFooter/>
</template>

<style lang="scss" scoped>

  @use"./components/styles/general.scss" as*;
  @use"./components/styles/partial/variables.scss" as*;
 
</style>
