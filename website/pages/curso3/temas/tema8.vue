<template>
    <div>
        <p class="text-center font-weight-bold text-h4 mt-10">III.8 La Fuerza de DES y Triple DES</p>
        <p class="mx-10 mt-6 text-justify">A pesar del gran impacto que tuvo el Data Encryption Standard en el mundo de la criptografía y de la tecnología, la realidad es que hoy en día este método de cifrado ya no es considerado como una opción fiable para poder cifrar información, dado que por su naturaleza de tener llaves de 56 bits es que con las computadoras actuales mediante un ataque de fuerza bruta se puede lograr obtener el texto plano en un margen de tiempo relativamente corto. La siguiente lista muestra el tiempo para obtener el texto plano de un texto cifrado mediante DES mediante un ataque de fuerza bruta en diferentes momentos de la historia.</p>
        <ul class="ml-10 my-5">
            <li>1997: Un par de meses mediante el uso de internet.</li>
            <li>1998: Un par de días mediante el uso de hardware dedicado.</li>
            <li>1999: Un alrededor de 22 horas mediante hardware dedicado y con el uso de internet.</li>
        </ul>
        <p class="mx-10 mt-6 text-justify">Es a partir de esta problemática que se plantean como alternativas opciones como el Advanced Encryption Standard, el Doble DES y Triple DES. En este tema se explicará de forma concreta los dos últimos.</p>
        <div class="d-flex justify-center">
            <v-img class="my-6" width="500" height="450" src="https://flylib.com/books/3/190/1/html/2/images/06fig01.jpg"></v-img>
        </div>
        <p class="mx-10 mt-6 text-h5 font-weight-bold text-justify">Doble DES</p>
        <p class="mx-10 mt-6 text-justify">Como se observa en la imagen anterior, el Doble DES (tanto en cifrado como desencriptado) está compuesto por un encriptado doble mediante el algoritmo DES, pero donde cada proceso de encriptado utiliza una llave diferente, ofreciendo así una mayor seguridad, dado que para obtener de manera forzada el código se tendría que obtener ambas llaves, lo cual puede llevar más tiempo ya que en total se tendría una llave de 112 bits.</p>
        <p class="mx-10 mt-6 text-h5 font-weight-bold text-justify">Triple DES</p>
        <p class="mx-10 mt-6 text-justify">El Triple DES consiste de un proceso donde para encriptar texto se aplica dos veces el algoritmo de encriptamiento y una vez el proceso de descifrado, mientras que para desencriptar se aplica dos veces el proceso de descifrado y una vez el de encriptado. Este cifrado puede dividirse en dos grupos principales: </p>
        <ul class="ml-10 my-5">
            <li>Triple DES con dos llaves: Dos llaves son las mismas, mientras que la tercera es distinta. No hay actualmente ataques prácticos.</li>
            <li>Triple DES con dos llaves: Las tres llaves correspondientes a los tres procesos, como lo muestra la imagen anterior, son totalmente distintas entre sí. Tiene uso en tecnologías como PGP o el navegador Firefox para la autenticación de los usuarios.</li>
        </ul>
        <p class="mx-10 mt-6 text-justify">Los siguientes dos videos muestran una explicación sobre los cifrados Doble DES y Triple DES de una forma clara y sencilla:</p>
        <div class="d-flex justify-center mt-5">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/IZFaZDO3-GQ?si=vFCVy6_K7qgJ4BVm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
        <div class="d-flex justify-center mt-5">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/23JangqRhIc?si=h-jtLPPbBSymCXHm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
        <div class="d-flex justify-center">
            <v-btn to="/curso3/dashboard" color="success" size="large" class="my-10">Finalizar Curso</v-btn>
        </div>
    </div>
</template>