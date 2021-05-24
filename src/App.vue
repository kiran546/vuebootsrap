<template>
  <div  id="app" class="mt-1">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <AboutMe/>
    <Navbar/>
    <Jumbotron/>
    <Cards/>
    <!-- <List/> -->
    <Form/>
  </div>
</template>

<script>

import Navbar from './components/Navbar'
import Jumbotron from './components/Jumbotron'
import Cards from './components/Cards'
// import List from './components/List'
import Form from './components/Form'


export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
    Cards,
    // List,
    Form   
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
