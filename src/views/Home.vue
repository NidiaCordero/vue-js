<template>
  <div class="home">
  <!---navbar-->
  <Nav/>
  <Header/>
    
    
  </div>
      
</template>

<script>
// @ is an alias to /src

import Nav from '@/components/nav.vue'
import Header from '@/components/header.vue'

export default {
  name: 'home',
  components: {
    Nav,
    Header,
  }
}
</script>
