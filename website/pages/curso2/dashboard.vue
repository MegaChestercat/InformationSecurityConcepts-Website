<template>
    <div>
       <div>
            <v-img height="270" width="100vw" src="~~/assets/auth_bg.png" cover>
               <div class="d-flex justify-center align-center fill-height">
                <div class="d-block">
                    <p class="text-white text-center text-h3 font-weight-bold">Hacking y Sistemas de Detección de Intrusiones</p>
                    <p class="text-white text-center text-subtitle-2 font-weight-bold mt-5">Este módulo presenta información con respecto a temas introductorios de seguridad informática para sentar las bases para temas subsecuentes.</p>
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
                        <NuxtLink to="/curso2/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.1 Hacking y Hackers</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl">
                        <NuxtLink to="/curso2/temas/tema2" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.2 Detección de Intrusos</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso2/temas/tema3" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.3 Acercamiento a la Detección de Intrusos</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso2/temas/tema4" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.4 Honeypots y Herramientas de Sniffing</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso2/temas/tema5" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.5 Ejemplo de Sistema: Snort</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso2/temas/tema6" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.6 Firewalls</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso2/temas/tema7" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.7 DDoS y Software Malicioso</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso2/temas/tema8" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.8 Resumen</p>
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

           
                    <!-- <v-sheet :elevation="5" width="75vw" height="150" class="ml-15 my-10 rounded-xl" >
                        <div class="d-flex align-center fill-height">
                            <p class="ml-8 text-black text-h5 font-weight-bold">Contenido Adicional</p>
                            <v-icon class="option ml-4" size="x-large">mdi-chevron-down</v-icon>
                        </div>
                    </v-sheet> -->

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
      <iframe width="560" height="315" src="https://www.youtube.com/embed/3f8YAEfSlEY?si=CdIixdOUMJgJzROL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

      <!-- Descripción de la opción -->
      <div class="ml-8">
        <p class="text-black text-h5 font-weight-bold">Tema: Hacking y Hackers</p>
        
      </div>
    </div>
  </NuxtLink>
</v-sheet>

          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/nuPYFRlBM58?si=XmT9o_z7YX5UIUSR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Detección de Intrusos</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/qouJ7sxu0Dc?si=dDiXNttiG2Ynnct8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Honeypots y Herramientas de Sniffing</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/MwqdKevOas0?si=kxsku5x8oxB9y5Et" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Snort</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/mcTCrTneeco?si=w7IzGx6wmXSi7GsT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Firewalls</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/_sVObRVfoms?si=qvrdZMGWKWrC7Ili" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: DDoS</p>
                
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