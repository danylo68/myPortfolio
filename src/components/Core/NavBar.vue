<template>
  <v-app-bar class="topbar" app height="100" elevation="14" 
>
      <v-avatar
        class="mr-3"
        color="grey lighten-4"
        size="70"
      >
      <v-list-item-avatar>
         <v-img :src="require('@/assets/photo_cv.jpg')"></v-img>
        </v-list-item-avatar>
      </v-avatar>

      <v-toolbar-title class="font-weight-black headline">
       Daniel LOPA
      </v-toolbar-title>
      
      <v-spacer></v-spacer>
       
  
     <v-btn text @click="$vuetify.goTo('#about-me')" >
     <span>A propos</span> 
    </v-btn>

   
     <v-btn text @click="$vuetify.goTo('#carousel')" >
    <span>Projet</span>  
    </v-btn> 
    
    <v-btn text @click="$vuetify.goTo('#footerbar')" >
     <span>Contact</span>
    </v-btn>
    
    </v-app-bar>

</template>

