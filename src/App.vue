<template>
  <div id="app">
    <HeaderFlix/>
    <MainFlix class="bg-darkgray"/>
  </div>
</template>

<script>
import "bootstrap"
import HeaderFlix from './components/HeaderFlix.vue'
import MainFlix from './components/MainFlix.vue'

export default {
  name: 'App',
  components: {
    HeaderFlix,
    MainFlix
  }
}
</script>



<style lang="scss">
@import "bootstrap/dist/css/bootstrap.min.css";
@import './components/style/index.scss';

</style>
