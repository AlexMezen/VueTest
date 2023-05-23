<template>
  <first-header></first-header>
  <title-nav></title-nav>
  <form-resume></form-resume>
  <customize></customize>
  <q-r-wallet></q-r-wallet>
</template>
<script >
  import FirstHeader from './components/FirstHeader.vue';
  import TitleNav from './components/TitleNav.vue';
  import FormResume from './components/FormResume.vue';
  import Customize from './components/Customize.vue';
  import QRWallet from './components/QrWallet.vue';
export default{
components:{
FirstHeader,
TitleNav, 
FormResume,
Customize,
QRWallet,
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

