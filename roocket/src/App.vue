<template>
  <div>
    <the-navigation />
    <nav-bar />
    <the-part />
    <the-ui />
  </div>
</template>

<script>
import NavBar from './components/layout/NavBar.vue';
import TheNavigation from './components/layout/TheNavigation.vue';
import ThePart from './components/layout/ThePart.vue';
import TheUi from './components/UI/TheUi.vue';

export default {
  components: {  NavBar,  ThePart, TheUi, TheNavigation},

}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0 ;
}
html{
  direction: rtl;
  background-color: rgba(241, 234, 234, 0.26);
  font-weight: 590;
  font-family: 'Vazir' ;
}
</style>