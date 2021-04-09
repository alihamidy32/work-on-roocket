<template>
  <div>
    <upper-header />
    <nav-bar />
    <the-part />
    <the-article />
  </div>
</template>

<script>
import NavBar from './components/layout/NavBar.vue';
import TheArticle from './components/layout/TheArticle.vue';
import ThePart from './components/layout/ThePart.vue';
import UpperHeader from './components/layout/UpperHeader.vue';

export default {
  components: { UpperHeader,  NavBar, TheArticle, ThePart},

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