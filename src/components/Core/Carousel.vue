<template>

 <section
        id="carousel"
        class="grey lighten-3 p-3" 
      >
      
  <v-card  elevation="22" max-width="500" class="mx-auto">
    <!-- <v-system-bar lights-out></v-system-bar> -->
    <v-carousel
      :continuous="false"
      :cycle="cycle"
      :show-arrows="false"
      hide-delimiter-background
      delimiter-icon="mdi-minus"
      height="500"
    >
      <v-carousel-item v-for="(slide, i) in slides" 
      :key="i">
       <v-sheet :color="colors[i]" height="100%" tile >

          <v-row class="fill-height" align="center" justify="center">
            <div class="text-h2">{{ slide }}<br> </div>
          </v-row>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>
    <v-list two-line>
      <v-list-item>
        <v-list-item-avatar>
         <v-img :src="require('@/assets/photo_cv.jpg')"></v-img>
        </v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title>Daniel LOPA</v-list-item-title>
          <v-list-item-subtitle>Autheur</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
    </v-list>
  </v-card>

  <div class="py-12"></div>

 </section>
  
</template>


<script>
  export default {
    data () {
   return {
        colors: [
          'green',
          'secondary',
          'yellow darken-4',
          'red lighten-2',
          'orange darken-1',
          'grey'
        ],
        cycle: false,
        slides: [
          'Projet1',
          'Projet2',
          'Projet3',
          'Projet4',
          'Projet5',
          'Projet6'
        ],
      }
    },
  }
</script>
