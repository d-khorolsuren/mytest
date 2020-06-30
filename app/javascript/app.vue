<template>
  <div id="app">
    <Header/>
    <dashboard/>
  </div>
</template>

<script>

  import Header from './components/header.vue'
  import dashboard from './components/Dashboard.vue'
  
export default {
  name: 'app',
  components: {
    Header,
    dashboard
  },
  data: function () {
  },
}
</script>
