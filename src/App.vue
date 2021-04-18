<template>
   <v-app>
     <navbar></navbar>
     <v-main>
       <router-view></router-view>
     </v-main>
     <Footer></Footer>
   </v-app>
</template>

<script>
import Navbar from '@/components/Navbar'
import Footer from '@/components/Footer'
export default {
  name: 'App',
  components: {
    Navbar,
    Footer
  },
  data () {
    return {
      //
    }
  }
}
</script>
