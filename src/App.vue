<template>
  <header>
    <div id="app">
      <Header />
      <Latest />
      <Posts />
    </div>
  </header>
</template>

<script lang="ts">
import  Header  from './components/header.vue'
import  Latest  from './components/Latest.vue'
import  Posts  from './components/Posts.vue'

export default {
    name: 'app',
    components: {
    Header,
    Latest,
    Posts
}
}
</script>

<style lang="scss">
body{
  background-color: #F3F3F3;
  font-family: "Rockwell", serif;
}

h3{
  color: #171717;
  font-size: 28px;
  font-weight: 700;
}
</style>
