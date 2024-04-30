<template>
    <div>
       <div>
            <v-img height="270" width="100vw" src="~~/assets/auth_bg.png" cover>
               <div class="d-flex justify-center align-center fill-height">
                <div class="d-block">
                    <p class="text-white text-center text-h3 font-weight-bold">Introducción a la Seguridad Informática</p>
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
                        <NuxtLink to="/curso1/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">I.1 Motivación: Amenazas hacia la Ciberseguridad</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl">
                        <NuxtLink to="/curso1/temas/tema2" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">I.2 La Web: Superficie, Profunda y Oscura</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema3" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">I.3 Tendencias de la Seguridad</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema4" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">I.4 La Arquitectura de Seguridad OSI</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema5" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">I.5 Amenazas contra la Seguridad: Pasivas y Activas</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema6" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">I.6 Mecanismos y Servicios de Seguridad</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema7" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">I.7 Un Modelo de la Seguridad de Red</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema8" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">I.8 Métodos para la Defensa: Biométricos</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                </v-sheet>
            </v-menu>

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
      <iframe width="560" height="315" src="https://www.youtube.com/embed/LupJ9Z9xlC8?si=iBkry3z8gFSAv_gE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

      <!-- Descripción de la opción -->
      <div class="ml-8">
        <p class="text-black text-h5 font-weight-bold">Tema: Amenazas de Ciberseguridad</p>
        
      </div>
    </div>
  </NuxtLink>
</v-sheet>

          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/mzXNU5vLNDc?si=l0yGqCgKlPJjgUvu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Web: Superficie, Deep y Dark</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/ZpCV3oa-1E8?si=UrPol42mgnYwNZ8R" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Tendencias en la Seguridad</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/O8SeYEFnBmQ?si=HFE5NyC__3FTMyIv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Modelo OSI</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/EHjmxujXIaQ?si=ac7q_nrbCP6zKxaY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Mecanismos de Seguridad</p>
                
              </div>
             
            </NuxtLink>
          </v-sheet>
          <v-sheet :elevation="5" width="75vw" height="350" class="mx-15 mt-8 rounded-xl">
            <NuxtLink to="/curso2/contenido-adicional/opcion1" style="text-decoration: none;">
              <div class="d-flex align-center fill-height">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/s1qnXTfeXMI?si=zeynpxhwqpV4j9rW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <p class="ml-8 text-black text-h5 font-weight-bold">Tema: Biométricos</p>
                
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