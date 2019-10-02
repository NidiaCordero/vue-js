<template>
  <div class="home">
  <!---navbar-->
  <Nav/>
  <Header/>
  <Content/>
  <Footer/>
    
    
  </div>
      
</template>

<script>
// @ is an alias to /src

import Nav from '@/components/nav.vue'
import Header from '@/components/header.vue'
import Content from '@/components/content.vue'
import Footer from '@/components/footer.vue'

export default {
  name: 'home',
  components: {
    Nav,
    Header,
    Content,
    Footer,
  }
}
</script>
