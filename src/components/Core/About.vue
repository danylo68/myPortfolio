

<template>
<section id="about-me">
                        <div class="py-8"></div>

                        <v-container class="text-center">
                            <h2 class="display-2 font-weight-bold mb-3">A propos de moi</h2>

                            <v-responsive class="mx-auto mb-8" width="56">
                                <v-divider class="mb-1"></v-divider>

                                <v-divider></v-divider>
                            </v-responsive>

                            <v-responsive class="mx-auto title font-weight-light mb-8" max-width="720">
                                Après avoir acquis plusieurs expériences dans différent domaine,
                                Je me suis réorienté vers le métier de Développeur Web, j'ai passé une
                                année à développer des projets avec le HTML, le CSS et le JAVASCRIPT 
                                sur des technologies NODE.JS, MySQL et VUE.JS. Autonomie, persévérance,
                                curiosité et motivation m'ont permis d'y arrivé. 

                            </v-responsive>

                            <v-avatar class="elevation-20 mb-12" size="128">
                                <v-img  :src="require('@/assets/photo_cv.jpg')"></v-img>
                            </v-avatar>

                            <div></div>                       
                        </v-container>

                        <div class="py-0"></div>
                    </section>
</template>


<style lang="scss" scoped>
#about-me
 {
  font-family: "aileronblack";
}
</style>
