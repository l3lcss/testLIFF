<template>
  <div class="home">
    Home.vue
    HelloWorld msg="Welcome to Your Vue.js App"/
  </div>
</template>
<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    // HelloWorld
  },
  beforeCreate () {
    window.alert('beforeCreate in Home.vue')
  }
}
</script>
