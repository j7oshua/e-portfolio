<template>
   <v-app>
     <navbar></navbar>
     <v-main class="black white--text">
       <v-container fluid>
         <router-view></router-view>
       </v-container>
     </v-main>
     <v-footer></v-footer>
   </v-app>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  name: 'App',
  components: { Navbar },
  data () {
    return {
      //
    }
  }
}
</script>
