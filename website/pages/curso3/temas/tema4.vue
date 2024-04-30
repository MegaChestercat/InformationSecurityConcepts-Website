<template>
    <div>
        <p class="text-center font-weight-bold text-h4 mt-10">III.4 Técnicas de Transposición</p>
        <p class="mx-10 mt-6 text-justify">La operación de transposición consiste crear un texto cifrado a partir de reordenar el contenido actual del texto plano, por lo que la frequencia de las letras en el texto cifrado es la misma que en la del texto original.</p>
        <p class="mx-10 mt-6 text-justify">En esta sección se presentarán mediante videos algunos ejemplos aplicativos de cifrado mediante la transposición, para que de esa manera sea fácil su comprensión, y aplicación del concepto en futuros temas (como Advanced Encryption Standard).</p>
        <v-container class="my-5">
            <v-row>
                <v-col>
                    <v-card>
                        <v-card-title class="text-center font-weight-bold">
                        Rail Fence Cipher
                        </v-card-title>
                        <v-card-subtitle class="text-center mb-4">
                        Escribir un mensaje en diagonal a través de filas y columnas, y leer en zigzag
                        </v-card-subtitle>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/LEGPQ59bGZo?si=fQcK-4iU-ZviEBcc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
                <v-col>
                    <v-card>
                        <v-card-title class="text-center font-weight-bold">
                        Row Transposition Cipher 
                        </v-card-title>
                        <v-card-subtitle class="text-center mb-4">
                        Escribir mensaje sobre filas y columnas y reordenar de acuerdo a una llave
                        </v-card-subtitle>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/bcyUJK1BvHw?si=kRSXW4ZcXwltP7Yp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>
        <p class="mx-10 mt-6 text-h5 font-weight-bold text-justify">Cifrados de Producto</p>
        <p class="mx-10 mt-6 text-justify">Este tipo de cifrados busca eliminar las desventajas a las que se enfrentan los cifrados que utilizan únicamente sustitución o transposición, dado que son susceptibles a un ataque criptanálítico.</p>
        <p class="mx-10 mt-6 text-justify">La forma en la que funcionan consiste en hacer uso conjunto de las técnicas de sustitución y transposición, para así ofrecer lo que se conoce como "confusión" y "difusión" para así lograr tener un algoritmo de cifrado resistente tanto a ataques criptanalíticos como de fuerza bruta. Es a partir de este tipo de cifrados que se genera la transición de los cifrados clásicos a los modernos.</p>
        <p class="mx-10 mt-6 text-justify">El uso de este tipo de cifrado se verá a partir del tema 6.</p>
        <div class="d-flex justify-center">
            <v-btn to="/curso3/temas/tema5" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
        </div>
    </div>
</template>