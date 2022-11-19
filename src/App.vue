<!-- Ｈtml -->
<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <TryIt 
    msg="Here to Change Text" 
    ChangeHtmlTag='<div>
      <div class="1">You can Put any HtmlTag here</div>
     </div>'
    />
</template>

<!-- JS -->
<script>
import TryIt from './components/TryIt.vue'

export default {
  name: 'App',
  components: {
    TryIt
  }
}
</script>

<!-- CSS -->
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  margin-top: 60px;
}
</style>
