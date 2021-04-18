<template>
  <div id="home">
    <home-header></home-header>
    <about-me></about-me>
<!--    <v-container>-->
<!--      <joshua-timeline></joshua-timeline>-->
<!--    </v-container>-->
    <joshua-projects></joshua-projects>
    <contact></contact>
  </div>
</template>

<script>
import AboutMe from '@/components/AboutMe'
import HomeHeader from '@/components/HomeHeader'
// import JoshuaTimeline from '@/components/JoshuaTimeline'
import JoshuaProjects from '@/components/JoshuaProjects'
import Contact from '@/components/Contact'
export default {
  components: {
    JoshuaProjects,
    HomeHeader,
    AboutMe,
    Contact
  }
}
</script>

<style scoped>
/*.container {*/
/*  border: 1px solid green;*/
/*}*/
/*.row {*/
/*  border: 1px solid red;*/
/*}*/
/*.col {*/
/*  border: 1px solid blue;*/
/*}*/
</style>
