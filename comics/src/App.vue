<template>
  <div id="app">
    <Header />
    <Content />
    <Info />
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Content from '@/components/Content.vue'
import Info from '@/components/Info.vue'

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Info
  }
}
</script>

<style lang="scss">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
</style>
