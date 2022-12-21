<script >
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default{

  components:
  AppHeader,
  AppMain,
  AppFooter
}
</script>
  
<template>
 <header>
  <AppHeader/>
 </header>
  <main>
    <AppMain/>
  </main>
 <footer>
  <AppFooter/>
 </footer>
</template>

<style lang="scss" scoped>
  @use"./components/styles/general.scss" as*;
  @use"./components/styles/partial/variables.scss" as*;
</style>
