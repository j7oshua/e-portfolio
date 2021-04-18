<template>
  <div id="projects" class="black white--text">
    <v-container class="py-12 my-10">
      <v-row class="ml-16">
        <v-col>
          <h1 class="display-1">Projects</h1>
        </v-col>
      </v-row>
      <v-row>
        <v-col sm="10" offset-sm="1" lg="10" offset-lg="1">
          <v-row>
            <v-col sm="6" md="6">
              <v-card>
                <v-img src="../assets/extremeproject.jpg" height="400px"/>
                <v-card-title>First Website Project</v-card-title>
                <v-card-subtitle>Saskpolytech, Saskatoon</v-card-subtitle>
                <v-card-text>The website I created with a partner for the end of year projects. We had to redesign a website that
                had design flaws and create something that was a bit more UI friendly. We were restricted to use the
                technologies we learnt during first year classes.</v-card-text>
                <v-divider class="mx-4"></v-divider>
                <v-card-title>Technologies</v-card-title>
                <v-card-text><strong>HTML5</strong> | <strong>CSS3</strong> |
                  <strong>Javascript</strong> | <strong>Bootstrap</strong></v-card-text>
              </v-card>
            </v-col>
            <v-col sm="6" md="6">
              <v-card>
                <v-img src="../assets/movienight.jpg" height="400px"/>
                <v-card-title>Movie Night Vue JS Project</v-card-title>
                <v-card-subtitle>Saskpolytech, Saskatoon</v-card-subtitle>
                <v-card-text>2nd year website project created with a partner. We were able to use the frameworks
                learnt in 2nd year which included Vue JS for the frontend. We also created a backend with PHP. We had
                a fully working login system, shopping cart and the ability to like a movie.</v-card-text>
                <v-divider class="mx-4"></v-divider>
                <v-card-title>Technologies</v-card-title>
                <v-card-text><strong>Vue JS</strong> | <strong>Bootstrap Vue</strong> |
                  <strong>PHP</strong></v-card-text>
              </v-card>
            </v-col>
            <v-col sm="6" md="6">
              <v-card>
                <v-img src="../assets/murr.jpg" height="330px"/>
                <v-card-title class="text-no-wrap">Multi-Unit Residential Recycling</v-card-title>
                <v-card-subtitle>Saskpolytech, Saskatoon</v-card-subtitle>
                <v-card-text>Final group project we worked on for the entire 2nd year. We had to create a web
                application that would reward residents that lived at Multi-Unit apartments for their recycling
                efforts. If they recycled properly based on the set guidelines, they would be given points to be
                spent later on rewards. We finished with a fully functional login system with authentication, point system,
                educational informational page, and recycling container pickup system.</v-card-text>
                <v-divider class="mx-4"></v-divider>
                <v-card-title>Technologies</v-card-title>
                <v-card-text><strong>Vue JS</strong> | <strong>Symfony</strong> |
                  <strong>Mocha & Chai</strong> | <strong>Bootstrap Vue</strong></v-card-text>
              </v-card>
            </v-col>
            <v-col sm="6" md="6">
              <v-card>
                <v-img src="../assets/eportfoliov1.jpg" height="400px"/>
                <v-card-title>Personal E-Portfolio V1</v-card-title>
                <v-card-subtitle>Prince Albert, Saskatchewan</v-card-subtitle>
                <v-card-text>Personal E-Portfolio I created for a class project. For the framework I used Vue JS and
                Google Firebase to host the website. I also used a few different libraries to help with the
                creation of the website which included: Vuetify and Vue Router.</v-card-text>
                <v-divider class="mx-4"></v-divider>
                <v-card-title>Technologies</v-card-title>
                <v-card-text><strong>Vue JS</strong> | <strong>Vuetify</strong> |
                  <strong>Vue Router</strong></v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>

</style>
