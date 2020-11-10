<template>
  <div id="app">
    <Navbar/>
    <HelloWorld/>
  </div>
</template>
<script>
import Navbar from './components/Navbar'
import HelloWorld from './components/HelloWorld'

export default {
  name: 'navbar',
  components: {
    Navbar,
    HelloWorld
  }
}
</script>
