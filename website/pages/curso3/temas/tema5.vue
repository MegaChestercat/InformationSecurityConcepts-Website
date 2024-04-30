<template>
    <div>
        <p class="text-center font-weight-bold text-h4 mt-10">III.5 Esteganografía</p>
        <div class="d-flex justify-center">
            <v-img class="my-6" width="500" height="350" src="https://esgeeks.com/wp-content/uploads/2019/04/Mejores-Herramientas-para-Esteganograf%C3%ADa.jpg"></v-img>
        </div>
        <p class="mx-10 mt-6 text-justify">La estenografía más que considerarlo como un método de cifrado, puede ser visto como una forma de ocultar un mensaje de tal forma que pase inadvertida por la mayoría de las persoans, incluyendo atacantes.</p>
        <p class="mx-10 mt-6 text-justify">La idea consiste en ocultar información dentro de los pixeles de una imagen de tal forma que el esquema de colores utilizado es alterado en los bits menos significativos de su escala (como RGB), para así gaurdar el mensaje en formato binario.</p>
        <p class="mx-10 mt-6 text-justify">Cabe señalar que la estenografía puede ser utilizada en conjunto con el cifrado, ofreciendo así una solución que no solamente está oculta a la vista, sino que a su vez necesita ser descifrada para lograr obtener el mensaje real.</p>
        <div class="d-flex justify-center">
            <v-img class="my-6" width="500" height="350" src="https://programacionpython80889555.wordpress.com/wp-content/uploads/2021/02/stg6.png?w=599"></v-img>
        </div>
        <p class="mx-10 mt-6 text-justify">Como se logra observar en la imagen anterior, un ejemplo del uso de la estenografía es reemplazar los bits menos significativos del código rgb de un pixel del cuadro "La Gioconda" de tal manera que al ser rangos de color similares al original, pasa inadvertido para el público que existe un mensaje oculto en la obra.</p>
        <p class="mx-10 mt-6 text-justify">El siguiente video explicará más a detalle sobre la estenografía y ofrecerá un ejemplo práctico mediante el uso de la computadora.</p>
        <div class="d-flex justify-center mt-5">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/SzU8ohRk5sg?si=ZpRK5PYn5jrg8oyA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
        <div class="d-flex justify-center">
            <v-btn to="/curso3/temas/tema6" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
        </div>
    </div>
</template>