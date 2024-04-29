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
        <v-sheet :elevation="5" width="75vw" height="150" class="ml-15 mt-8 rounded-xl">
            <NuxtLink to="/curso1/temas/tema1" style="text-decoration: none;">
                <div class="d-flex justify-end align-center fill-height">
                <v-icon class="option mr-8" size="x-large">mdi-arrow-right</v-icon>
            </div>
            </NuxtLink>
        </v-sheet>
        <v-sheet :elevation="5" width="75vw" height="150" class="ml-15 my-10 rounded-xl">
            <div class="d-flex justify-end align-center fill-height">
                <v-btn variant="plain"  class="mr-8" icon>
                    <v-icon class="option" size="x-large">mdi-arrow-right</v-icon>
                </v-btn>
            </div>
        </v-sheet>

        <v-sheet :elevation="5" width="75vw" height="150" class="ml-15 my-10 rounded-xl" >
            <div class="d-flex justify-end align-center fill-height">
                <v-btn variant="plain"  class="mr-8" icon>
                    <v-icon class="option" size="x-large">mdi-arrow-right</v-icon>
                </v-btn>
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