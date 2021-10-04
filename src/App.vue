<template>
    <Home />
    <Header />
    <Sidebar />
</template>

<script>
import Home from './components/Home.vue'
import Header from './components/Header.vue'
import Sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Home,
    Header,
    Sidebar
  }
}
</script>

<style>
*{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}
</style>
