<template>
  <div>
    <NavBar />
    <Header />
    <SectionOne />
  </div>
</template>

<script>
import NavBar from './components/NavBar';
import Header from './components/Header';
import SectionOne from './components/SectionOne';

export default {
  name: 'App',
  components: {
    NavBar,
    Header,
    SectionOne,
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
