<template>
<section id="footerbar">
 <v-footer class="justify-center" color="#374e42

" height="100">
      <div class="title font-weight-light white--text text--lighten-1 text-center">
        &copy; {{ (new Date()).getFullYear() }} — Daniel LOPA —

<div class="iconik">

<v-btn 
class="white--text large"
href="https://github.com/danylo68?tab=repositories"
target="_blank"
icon> 
<v-icon large>mdi-github</v-icon>
</v-btn>

  <v-btn 
  class="font-weight-light white--text "
  href="https://www.linkedin.com/in/daniel-lopa/"
  target="_blank"
  icon>    
<v-icon large>mdi-linkedin</v-icon>        
 </v-btn>
            
 <v-btn
  class="font-weight-light white--text "
  href="mailto:lopa.daniel@gmail.com"
  target="_blank"
  icon>    
<v-icon large>mdi-gmail</v-icon> 
</v-btn>    
         
</div>
      </div>
    </v-footer>
</section>
</template>
