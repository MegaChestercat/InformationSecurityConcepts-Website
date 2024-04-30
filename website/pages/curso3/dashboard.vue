<template>
    <div>
       <div>
            <v-img height="270" width="100vw" src="~~/assets/auth_bg.png" cover>
               <div class="d-flex justify-center align-center fill-height">
                <div class="d-block">
                    <p class="text-white text-center text-h3 font-weight-bold">Cifrado Simétrico</p>
                    <p class="text-white text-center text-subtitle-2 font-weight-bold mt-5">Este módulo presenta conceptos enfocados a la encriptación, los primeros cifrados y la explicación sobre el cifrado de Data Encryption Standard (DES).</p>
                </div>
               </div>
            </v-img>
       </div>
       <p class="text-center text-h3 font-weight-bold mt-10">Contenido</p>
       <div>
            <v-menu>
                <template v-slot:activator="{ props: menu }">
                    <v-sheet :elevation="5" width="75vw" height="150" class="ml-15 my-10 rounded-xl" v-bind="menu">
                        <div class="d-flex align-center fill-height">
                            <p class="ml-8 text-black text-h5 font-weight-bold">Lista de Temas</p>
                            <v-icon class="option ml-4" size="x-large">mdi-chevron-down</v-icon>
                        </div>
                    </v-sheet>
                </template>
                <v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 mt-8 rounded-xl">
                        <NuxtLink to="/curso3/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">III.1 Introducción</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl">
                        <NuxtLink to="/curso3/temas/tema2" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">III.2 Modelo de Cifrado Simétrico</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso3/temas/tema3" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">III.3 Técnicas de Sustitución</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso3/temas/tema4" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">III.4 Técnicas de Transposición</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso3/temas/tema5" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">III.5 Esteganografía</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso3/temas/tema6" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">III.6 Data Encryption Standard (DES)</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso3/temas/tema7" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">III.7 Un Ejemplo del DES</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso3/temas/tema8" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">III.8 La Fuerza del DES y del DES Triple</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                </v-sheet>
            </v-menu>

            <v-sheet :elevation="5" width="75vw" height="150" class="ml-15 my-10 rounded-xl" >
                <div class="d-flex align-center fill-height">
                    <p class="ml-8 text-black text-h5 font-weight-bold">Prueba General</p>
                    <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                </div>
            </v-sheet>

            <v-menu>
        <template v-slot:activator="{ props: menu }">
          <v-sheet :elevation="5" width="75vw" height="150" class="ml-15 my-10 rounded-xl" v-bind="menu">
            <div class="d-flex align-center fill-height">
              <p class="ml-8 text-black text-h5 font-weight-bold">Contenido Adicional</p>
              <v-icon class="option ml-4" size="x-large">mdi-chevron-down</v-icon>
            </div>
          </v-sheet>
        </template>
        <v-sheet>
          <!-- Aquí puedes agregar las opciones del menú para Contenido Adicional -->
          <!-- Por ejemplo: -->
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
  <NuxtLink to="" style="text-decoration: none;">
    <div class="d-flex align-center fill-height">
      <!-- Vista previa del video de YouTube -->
      <iframe width="560" height="315" src="https://www.youtube.com/embed/uzGzSHGip_o?si=J9KCz5p89BDTldPm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

      <!-- Descripción de la opción -->
      <div class="ml-8">
        <p class="text-black text-h5 font-weight-bold">Tema: Symmetric Cipher</p>
        
      </div>
    </div>
  </NuxtLink>
</v-sheet>

          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/WjATtFxR2F0?si=a2f1vof8lzgp7KRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Técnicas de Substitución</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/3gnJtKNbM-A?si=pbQ0ZWdY_i6oe3TK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Esteganografía</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/LPWRerMSQHs?si=-wR59IHrSlPEtOEQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: DES</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          
         
          <!-- Repite este patrón para cada opción del menú de Contenido Adicional -->
        </v-sheet>
      </v-menu>
              
            
       </div>
    </div>
</template>

<style scoped>
.option{
    color: gray;
}

.option:hover{
    color: #1DF02D;
}

iframe{
    margin-left: 3%;
}
</style>