<template>
    <div>
       <div>
            <v-img height="270" width="100vw" src="~~/assets/auth_bg.png" cover>
               <div class="d-flex justify-center align-center fill-height">
                <div class="d-block">
                    <p class="text-white text-center text-h3 font-weight-bold">Fundamentos I</p>
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
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.1 Hacking y Hackers</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl">
                        <NuxtLink to="/curso1/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.2 Detección de Intrusión</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.3 Métodos de Detección de Intrusión</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.4 Honeypots y Herramientas de Sniffing</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.5 Ejemplo de Sistema: Snort</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.6 Firewalls</p>
                                <v-icon class="option ml-4" size="x-large">mdi-arrow-right</v-icon>
                            </div>
                        </NuxtLink>
                    </v-sheet>
                    <v-sheet :elevation="5" width="75vw" height="150" class="mx-15 my-10 rounded-xl" >
                        <NuxtLink to="/curso1/temas/tema1" style="text-decoration: none;">
                            <div class="d-flex align-center fill-height">
                                <p class="ml-8 text-black text-h5 font-weight-bold">II.7 DDoS y Software Malicioso</p>
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

            <v-sheet :elevation="5" width="75vw" height="150" class="ml-15 my-10 rounded-xl" >
                <div class="d-flex align-center fill-height">
                    <p class="ml-8 text-black text-h5 font-weight-bold">Contenido Adicional</p>
                    <v-icon class="option ml-4" size="x-large">mdi-chevron-down</v-icon>
                </div>
            </v-sheet>
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
</style>