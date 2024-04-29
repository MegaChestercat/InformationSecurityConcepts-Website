<template>
    <div class="">
        <p class="text-h5 font-weight-bold text-center mt-16">El curso de "Introducción a la Seguridad Informática" posee el siguiente contenido:</p>
        <v-container class="mt-8">
            <v-row justify="center">
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/seguridad.png" cover></v-img>
                        <p class="text-center font-weight-bold">¿Qué es la Seguridad Informática?</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/ataques.jpg" cover></v-img>
                        <p class="text-center font-weight-bold">Ataques Informáticos</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/prevencion.png" cover></v-img>
                        <p class="text-center font-weight-bold">Estrategias de Prevención</p>
                    </v-sheet>
                </v-col>
            </v-row>
            <v-row justify="center" class="my-5">
                <v-col cols="2">
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/quiz.jpg" cover></v-img>
                        <p class="text-center font-weight-bold">3 Exámenes Rápidos</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/adicional.jpg" cover></v-img>
                        <p class="text-center font-weight-bold">Documentación Adicional</p>
                    </v-sheet>
                </v-col>
                <v-col cols="2"></v-col>
            </v-row>
        </v-container>
        <div class="d-flex justify-center">
            <v-btn width="70vw" color="success" append-icon="mdi-arrow-right" to="/curso1/dashboard">
                Continuar
            </v-btn>
        </div>
    </div>
</template>
<style>

</style>