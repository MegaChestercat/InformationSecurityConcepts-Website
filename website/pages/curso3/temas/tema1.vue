<template>
    <div>
        <p class="text-center font-weight-bold text-h4 mt-10">III.1 Introducción</p>
        <div>
            <div class="d-flex justify-center">
                <v-img class="my-6" width="500" height="150" src="https://decidesoluciones.es/wp-content/uploads/2022/10/Imagen3.jpg"></v-img>
            </div>
            <p class="mx-10 mt-6 text-justify">Cuando se habla de seguridad infomática, uno de los conceptos más esenciales que existen para lograr prevenir que información privada sea visible para los atacantes mediante ataques como sniffing o el famoso "Man in the Middle Attack" (que es cuando el atacante se logra situar como intermediario de la comunicación entre dos partes de tal forma que es impercetible a simple vista) es importante el hacer uso de técnicas de cifrado, las cuales se pueden dividir en 2 grandes tipos: Simétrico y Asimétrico.</p>
            <p class="mx-10 mt-6 text-justify">En este módulo se hablará acerca del cifrado simétrico, el cual existe desde hace cientos de años y es el que a día de hoy sigue siendo utilizado, en conjunto con la encriptación asimétrica para así lograr transmitir infrmación de forma segura. El cifrado simétrico puede resumirse en los siguientes puntos:</p>
            <v-container class="my-5">
                <v-row>
                    <v-col>
                        <v-card>
                            <v-card-title class="text-center font-weight-bold">
                               También llamado cifrado "convencional" /<br> "llave secreta" / "llave simple" 
                            </v-card-title>
                        </v-card>
                    </v-col>
                    <v-col>
                        <v-card>
                            <v-card-title class="text-center font-weight-bold">
                               Toda Encriptación clásica <br>son de llave secreta
                            </v-card-title>
                        </v-card>
                    </v-col>
                    <v-col>
                        <v-card>
                            <v-card-title class="text-center font-weight-bold">
                               El receptor y emisor <br>tienen una llave en común
                            </v-card-title>
                        </v-card>
                    </v-col>
                </v-row>
            </v-container>
            <p class="mx-10 mt-6 text-justify">Antes de comenzar a hablar de métodos de cifrado es importante definir algunos términos que se repetirán de manera constante:</p>
            <ul class="ml-10 my-5">
                <li>Texto Plano: Mensaje original.</li>
                <li>Text Cifrado: Mensaje que ya se encuentra encriptado por algún algoritmo de cifrado.</li>
                <li>Cifrado: Algoritmo que permite transformar tetxo plano en texto cifrado.</li>
                <li>Encifrado (Encriptado): Proceso de conversión de texto plano a texto cifrado.</li>
                <li>Decifrado (Desencriptado): Proceso de conversión de texto cifrado a texto plano.</li>
                <li>Criptografía: Estudio de los métodos y principios de encriptación.</li>
                <li>Criptanálisis: Estudio de los métodos y principios para descifrar un texto sin conocer la llave.</li>
                <li>Criptología: Campo de estudio tanto de la criptografía como del criptanálisis.</li>
            </ul>
            <div class="d-flex justify-center fill-height">
                <v-btn to="/curso3/temas/tema2" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
            </div>
        </div>
    </div>
</template>