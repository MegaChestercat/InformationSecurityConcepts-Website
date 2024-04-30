<template>
    <div>
        <p class="text-center font-weight-bold text-h4 mt-10">III.2 Modelo de Cifrado Simétrico</p>
        <div class="d-flex justify-center">
            <v-img class="my-6" width="500" height="250" src="https://issy81seguridadinformatica.wordpress.com/wp-content/uploads/2015/02/simetria.png"></v-img>
        </div>
        <p class="mx-10 mt-6 text-justify">Como se logra apreciar en el anterior diagrama, el cifrado simétrico se compone de 5 elementos esenciales: </p>
        <ul class="ml-10 my-5">
            <li>Texto Plano</li>
            <li>Algoritmo de Encriptación</li>
            <li>Llave Secreta</li>
            <li>Texto Cifrado</li>
            <li>Algoritmo de Desencriptación</li>
        </ul>
        <p class="mx-10 mt-6 text-justify">Es importante resaltar que para que un cifrado simétrico sea considerado como seguro se deben cumplir 2 criterios:</p>
        <ul class="ml-10 my-5">
            <li>Un fuerte Algoritmo de encriptación.</li>
            <li>Secrecía de la llave privada (Solo conocida entre emisor y receptor).</li>
        </ul> 
        <p class="mx-10 mt-6 text-justify">De forma matemática los algoritmos de encriptado y descifrado pueden ser vistos como:</p>
        <ul class="ml-10 my-5">
            <li>Texto Cifrado = Llave de Encriptación(Texto Plano)</li>
            <li>Texto Cifrado = Llave de Encriptación(Texto Plano)</li>
        </ul> 
        <p class="mx-10 mt-6 text-h5 font-weight-bold text-justify">Criptografía</p>
        <p class="mx-10 mt-6 text-justify">Los distintos métodos para cfrar texto pueden clasificarse en tres distintos puntos:</p>
        <ul class="mx-10 my-5">
            <li>Operaciones de encriptación utilizadas: Sustitución/Transposición/Producto</li>
            <li>Cantidad de llaves utilizadas: Simétrico (llave única) o Asimétrico (2 llaves)</li>
            <li>Forma en la que el texto plano es procesado: Bloque o Cadena.</li>
        </ul> 
        <p class="mx-10 mt-6 text-h5 font-weight-bold text-justify">Criptanálisis</p>
        <p class="mx-10 mt-6 text-justify">El criptanálisis es el estudio de métodos o formas para poder obtener el texto plano que se encuentra cifrado, sin tener la llave, y para ello existen 2 formas principales:</p>
        <ul class="mx-10 my-5">
            <li>Ataque Criptanalítico: Deducir el texto plano a partir de características o patrones del texto cifrado.</li>
            <li>Ataque de Fuerza Bruta: Obtener todo el texto plano a partir de hacer uso de muchas llaves en un fragmento del texto cifrado.</li>
        </ul> 
        <p class="mx-10 mt-6 text-h5 font-weight-bold text-justify">Ataques Criptanalíticos</p>
        <p class="mx-10 mt-6 text-justify">Este tipo de ataques pueden clasificarse en los siguientes tipos:</p>
        <ul class="mx-10 my-5">
            <li>Ciphertext-only attack (COA): El atacante solo tiene acceso a uno o más cifrados mensajes pero no sabe nada acerca de los datos de texto sin formato. Sólo conoce algoritmos y texto cifrado.</li>
            <li>Known plaintext attack (KPA): El analista puede tener acceso a algunos o todos los texto plano del texto cifrado; El objetivo del analista en este caso es descubrir la clave utilizada para cifrar/descifrar el mensaje.</li>
            <li>Chosen plaintext attack (CPA): El analista conoce el algoritmo de cifrado. El analista puede cifrar el texto plano elegido con el algoritmo dirigido para derivar información sobre la clave.</li>
            <li>Differential cryptanalysis attack: Es un tipo de ataque de texto plano elegido que analiza pares de textos claros en lugar de textos claros individuales, por lo que el analista puede determinar cómo funciona el algoritmo objetivo. Funciona cuando encuentra diferentes tipos de datos.</li>
        </ul>
        <p class="mx-10 mt-6 text-h5 font-weight-bold text-justify">Ataque de Fuerza Bruta (BFA)</p>
        <p class="mx-10 mt-6 text-justify">Como fue mencionado previamente, este ataque consiste en realizar varios intentos para descifrar el texto plano a partir de usar diferentes llaves en cada ejemplo, hasta conseguir algo con coherencia. Sin embargo, esto trae consigo desventajas, dado que el tiempo del ataque dependerá del tamaño de la llave, además de que se asume de que se conoce/reconoce el texto plano. La siguiente tabla muestra el tiempo proporcional de un ataque de fuerza bruta a partir de diferentes algoritmos de cifrado, con diferentes tamaños de llave.</p>
        <div class="d-flex justify-center">
            <v-img class="my-6" width="500" height="250" src="~~/assets/cursos/comparison.png"></v-img>
        </div>
        <p class="mx-10 mt-6 text-justify">El siguiente video muestra un ejemplo práctico sencillo que explica cómo funciona un ataque de fuerza bruta:</p>
        <div class="d-flex justify-center mt-5">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/OiUk1WIQH3g?si=fe5wFQTRAN3NumDe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
        <div class="d-flex justify-center">
            <v-btn to="/curso3/temas/tema3" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
        </div>
    </div>
</template>