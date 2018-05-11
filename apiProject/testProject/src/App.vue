<template>
  <div>
    <Header></Header>
    <BodyComponent></BodyComponent>
    <Footer></Footer>
  </div>
</template>

<script>
import headerComponent from './components/Header.vue'
import bodyComponent from './components/Body.vue'
import footerComponent from './components/Footer'

export default {
  name: 'App',
  components : {
    'Header' : headerComponent,
    'BodyComponent' : bodyComponent,
    'Footer' : footerComponent
  }
}
</script>

<style>
  @import './css/index.css'
</style>
