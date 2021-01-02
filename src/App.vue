<template>
  <div>
    <NavBar />
    <Header />
  </div>
</template>

<script>
import NavBar from './components/NavBar';
import Header from './components/Header';

export default {
  name: 'App',
  components: {
    NavBar,
    Header,
  }
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

*, button, input {
    font-family: Roboto, sans-serif;
  }
</style>
