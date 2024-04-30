
<template>
  <div class="mainClass">
    <h1 style="text-align: center; margin-bottom: 5%">Honeypots y Herramientas de Sniffing</h1>
    <p>Los honeypots y las herramientas de sniffing son componentes importantes en el arsenal de la ciberseguridad para la detección de intrusos y la recopilación de información sobre amenazas potenciales. Aquí detallaré cada uno y discutiré sus características, eficacia en los IDS y algunas limitaciones:</p>


    <div class="texto textBorder">
        <h2>Honeypots:</h2>
        <p>Los honeypots son sistemas de señuelo diseñados para atraer a los atacantes y desviar su atención lejos de los sistemas y datos reales de una organización. Pueden clasificarse en:</p>
        <ol>
        <li><strong>Honeypots de Bajo Interacción:</strong> Simulan servicios y sistemas vulnerables con poca o ninguna funcionalidad real. Son fáciles de implementar y menos propensos a ser comprometidos, pero ofrecen menos información sobre los ataques.</li>
        <li><strong>Honeypots de Alta Interacción:</strong> Replican sistemas completos con funcionalidades reales, lo que permite una interacción más profunda con los atacantes. Son más complejos de implementar y mantener, pero proporcionan una mayor cantidad de información sobre las tácticas, técnicas y procedimientos de los atacantes.</li>
        </ol>
        <p><strong>Eficiencia en IDS:</strong> Los honeypots son útiles para complementar la detección de intrusos al atraer y capturar actividades maliciosas que podrían pasar desapercibidas en los sistemas reales. Sin embargo, pueden generar falsos positivos si se confunden con tráfico legítimo o si son comprometidos por los atacantes para lanzar ataques desde ellos.</p>
    </div>

    <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2013/07/12/15/18/globe-149610_1280.png" alt="Imagen">
        </div>

    <div class="texto textBorder">
        <h2>Herramientas de Sniffing:</h2>
        <p>Las herramientas de sniffing se utilizan para capturar y analizar el tráfico de red en busca de información sensible o actividades maliciosas. Pueden funcionar en modo pasivo, simplemente observando el tráfico, o en modo activo, inyectando paquetes en la red para obtener respuestas.</p>
        <p><strong>Eficiencia en IDS:</strong> Las herramientas de sniffing son valiosas para monitorear el tráfico de red en busca de anomalías, intentos de intrusión o actividades maliciosas. Sin embargo, pueden generar falsos positivos si interpretan incorrectamente el tráfico normal como malicioso, o falsos negativos si las actividades maliciosas están encriptadas o si el tráfico es muy complejo y difícil de analizar.</p>
    </div>

    <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2021/06/19/12/36/lock-6348498_1280.png" alt="Imagen">
        </div>

    <div class="texto textBorder">
        <h2>Rule-Based:</h2>
        <p>Tanto los honeypots como las herramientas de sniffing pueden funcionar con reglas predefinidas para identificar patrones específicos de tráfico o comportamientos sospechosos. Estas reglas pueden basarse en firmas conocidas, patrones de comportamiento o políticas de seguridad de la organización.</p>
    </div>

    <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2012/04/13/13/14/locker-32360_1280.png" alt="Imagen">
        </div>

    <div class="texto textBorder">
        <h2>Limitaciones y Evitación de IDS:</h2>
        <ol>
        <li><strong>Limitaciones Técnicas:</strong> Los IDS pueden perder tráfico cifrado o no estándar, lo que permite a los atacantes evadir la detección.</li>
        <li><strong>Ofuscación de Ataques:</strong> Los atacantes pueden utilizar técnicas de ofuscación para enmascarar sus actividades y evitar la detección por parte de los IDS.</li>
        <li><strong>Ataques de Inyección:</strong> Los atacantes pueden utilizar técnicas de inyección para modificar o burlar los sistemas de detección de intrusos y evitar ser detectados.</li>
        </ol>
    </div>

    <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2017/10/10/07/04/speed-2836249_1280.png" alt="Imagen">
        </div>


    <div class="texto threat">
        <p>En conclusión, tanto los honeypots como las herramientas de sniffing son herramientas valiosas en la detección de intrusos, pero deben utilizarse con cuidado y junto con otras técnicas de seguridad para mitigar los falsos positivos y negativos, y para hacer frente a las limitaciones y evasiones potenciales de los IDS.</p>
    </div>
    <div class="d-flex justify-center">
        <v-btn to="/curso2/temas/tema5" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
    </div>
  </div>
</template>
