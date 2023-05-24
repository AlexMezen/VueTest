<template>
  <first-header></first-header>
  <title-nav></title-nav>
  <form-resume></form-resume>
  <customize></customize>
  <q-r-wallet></q-r-wallet>
  <save-trees></save-trees>
  <business-card></business-card>
</template>
<script >
  import FirstHeader from './components/FirstHeader.vue';
  import TitleNav from './components/TitleNav.vue';
  import FormResume from './components/FormResume.vue';
  import Customize from './components/Customize.vue';
  import QRWallet from './components/QrWallet.vue';
  import SaveTrees from './components/SaveTrees.vue';
  import BusinessCard from './components/BusinessCard.vue';
export default{
components:{
FirstHeader,
TitleNav, 
FormResume,
Customize,
QRWallet,
SaveTrees,
BusinessCard,
}
}
</script>
<style>
#App{
  width: 100%;
  height: 100%;
}
body{
  box-sizing: content-box;
  width: 100%;
  margin: 0;
}

</style>

