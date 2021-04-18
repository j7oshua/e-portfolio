<template>
 <nav>
   <v-app-bar app dark class="black">
     <v-app-bar-title class="text-uppercase">
       Joshua Grimard
     </v-app-bar-title>
     <v-btn icon plain href="https://www.instagram.com/j7oshua/" target="_blank">
       <v-icon>mdi-instagram</v-icon>
     </v-btn>
     <v-btn icon plain href="https://github.com/j7oshua/" target="_blank">
       <v-icon>mdi-github</v-icon>
     </v-btn>
     <v-btn icon plain href="www.linkedin.com/in/joshuagrimard" target="_blank">
       <v-icon>mdi-linkedin</v-icon>
     </v-btn>
     <v-spacer></v-spacer>
     <v-toolbar-items class="hidden-xs-only">
       <router-link :to="'#home'" class="text-decoration-none ma-4 white--text">Home</router-link>
       <router-link :to="'#about'" class="text-decoration-none ma-4 white--text">About</router-link>
       <router-link :to="'#projects'" class="text-decoration-none ma-4 white--text">Projects</router-link>
       <router-link :to="'#contact'" class="text-decoration-none ma-4 white--text">Contact</router-link>
     </v-toolbar-items>
   </v-app-bar>
 </nav>
</template>

<script>
export default {
  data: () => ({
    drawer: false
  })
}

</script>
