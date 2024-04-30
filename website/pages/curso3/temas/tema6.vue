<template>
    <div>
        <p class="text-center font-weight-bold text-h4 mt-10">III.6 Data Encryption Standard (DES)</p>
        <p class="mx-10 mt-6 text-justify">El Data Encryption Standard (abreviado como DES) es un algoritmo de cifrado simétrico (tanto emisor como receptor tienen la misma llave) que tiene origen desde el año 1977 y se caracteriza por lo siguiente:</p>
        <ul class="ml-10 my-5">
            <li>S-Box (Confusión): Hace la relación entre el texto cifrado y la llave tan compleja como sea posible.</li>
            <li>P-Box (Difusión): Hace la relación estadística texto plano - texto cifrado tan compleja como sea posible.</li>
            <li>Encriptación de datos en bloques de de 64-bit.</li>
            <li>Uso de una llave única de 56-bit (que se deriva de una llave única general de 64-bit).</li>
            <li>Reliza el proceso de cifrado por 16 rondas.</li>
            <li>Posee una permutación inicial.</li>
        </ul>
        <p class="mx-10 mt-6 text-justify">Los siguientes videos explicarán de forma más detallada cómo es que funciona este algoritmo, qué elementos deben llevarse a cabo para su funcionamiento, y cuál sería una implementación dentro del lenguaje de programación Python:</p>
        <v-container class="my-5">
            <v-row>
                <v-col>
                    <v-card>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/cVhlCzmb-v0?si=lD4AQs08ZTjAiTQa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
                <v-col>
                    <v-card>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/j53iXhTSi_s?si=K_CJW2Uge2a5ZnAr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
            </v-row>
            <v-row>
                <v-col>
                    <v-card>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/nynAQ593HdU?si=eM3U5HL8Jjw6TejI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
                <v-col>
                    <v-card>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/OePPcJR--F4?si=JAWR7kUjZ_WWhOUu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
            </v-row>
            <v-row>
                <v-col>
                    <v-card>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/S-vLA7d1ORI?si=rFVRG5OCI-rcRDrt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
                <v-col>
                    <v-card>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/SjbI0FAnsRU?si=tTbnuRpvPqLCHr7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>
        <div class="d-flex justify-center">
            <v-btn to="/curso3/temas/tema7" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
        </div>
    </div>
</template>