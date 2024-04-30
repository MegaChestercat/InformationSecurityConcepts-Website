<template>
    <div>
        <p class="text-center font-weight-bold text-h4 mt-10">III.3 Técnicas de Sustitución</p>
        <p class="mx-10 mt-6 text-justify">Dentro de los métodos de encriptación simétrica, éstos pueden clasificarse a partir de las operaciones utilizadas para encriptar, siendo una de estas la sustitución, la cual consiste en reemplazar una letra del texto plano por otra.</p>
        <p class="mx-10 mt-6 text-justify">En esta sección se presentarán algunos ejemplos de encriptación mediante técnicas de sustitución mediante videos, para así mostrar de una forma más práctica y sencilla su funcionamiento.</p>
        <v-container class="my-5">
            <v-row>
                <v-col>
                    <v-card>
                        <v-card-title class="text-center font-weight-bold">
                        Caesar Cipher
                        </v-card-title>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/JtbKh_12ctg?si=Wuk1wPBNfNN03Dk3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
                <v-col>
                    <v-card>
                        <v-card-title class="text-center font-weight-bold">
                        Monoalphabetic Cipher 
                        </v-card-title>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/J-utjSeUq_c?si=kTX6PnKy2kin27tw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
            </v-row>
            <v-row>
                <v-col>
                    <v-card>
                        <v-card-title class="text-center font-weight-bold">
                        Playfair Cipher
                        </v-card-title>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/quKhvu2tPy8?si=qu3lbC6lvkegm5pv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
                <v-col>
                    <v-card>
                        <v-card-title class="text-center font-weight-bold">
                        Polyalphabetic Cipher (Vigenere)
                        </v-card-title>
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/SkJcmCaHqS0?si=rqzmbvfxLDNTZQz3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>
        <p class="mx-10 mt-6 text-justify">Los métodos de cifrado mostrados demuestran que con el pasar del tiempo los algoritmos que implementaban la sustitución fueron evolucionando de tal manera que fueron volviéndose más sofisticados para así lograr evitar los tipos de criptanálisis. Sin embargo, en conjunto con este tipo de algoritmos con esta operación, también surgieron otros los cuales implementan otro tipo de operación que también permite encriptar pero sin la necesidad de reemplazar letras de texto plano, los cuales se verán en el siguiente tema.</p>
        <div class="d-flex justify-center">
            <v-btn to="/curso3/temas/tema4" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
        </div>
    </div>
</template>