<template>
    <div class="mainClass">
      <h1 style="text-align: center; margin-bottom: 5%">Hacking y Hackers</h1>
      <p>El hacking es un término amplio que se refiere al acto de encontrar debilidades en sistemas informáticos o redes para acceder, manipular o robar información de manera no autorizada. Los hackers son individuos con habilidades avanzadas en informática que utilizan su conocimiento para explorar y explotar vulnerabilidades en sistemas informáticos. Aquí te detallo más sobre el hacking y los diferentes tipos de hackers:</p>
  
     
        <div class="texto textBorder">
            <h2>Tipos de Hackers:</h2>
            <ol>
                <li><strong>Hackers Éticos (White Hat):</strong> Son hackers que utilizan sus habilidades para identificar y corregir vulnerabilidades en sistemas informáticos. Trabajan en el ámbito de la seguridad informática y suelen ser contratados por empresas para realizar pruebas de penetración y fortalecer la seguridad de sus sistemas.</li>
                <li><strong>Hackers Maliciosos (Black Hat):</strong> Estos hackers tienen intenciones maliciosas y utilizan sus habilidades para robar información, causar daño o realizar actividades ilegales en línea, como el robo de datos personales o financieros, el sabotaje de sistemas, entre otros.</li>
                <li><strong>Hackers Grises (Gray Hat):</strong> Son hackers que no actúan estrictamente por motivos éticos o maliciosos. A menudo descubren vulnerabilidades y las divulgan públicamente, aunque también pueden aprovechar esas vulnerabilidades para su propio beneficio antes de informar sobre ellas.</li>
                <li><strong>Hackers Sombríos (Script Kiddies):</strong> No poseen un conocimiento profundo de la informática, pero utilizan herramientas y scripts preexistentes para realizar ataques básicos. Suelen ser aficionados que buscan causar daño sin entender completamente las implicaciones de sus acciones.</li>
            </ol>
        </div>
        
        <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2021/04/18/06/10/man-6187392_1280.png" alt="Imagen">
        </div>
      

      
      
        <div class="texto textBorder">
            <h2>Técnicas de Hacking:</h2>
            <ol>
                <li><strong>Phishing:</strong> Envío de correos electrónicos fraudulentos que parecen legítimos para engañar a las personas y obtener información confidencial como contraseñas o datos bancarios.</li>
                <li><strong>Ingeniería Social:</strong> Manipulación psicológica para engañar a las personas y obtener información confidencial o acceso a sistemas. Puede implicar el uso de pretextos, suplantación de identidad, entre otros.</li>
                <li><strong>Ataques de Fuerza Bruta:</strong> Consiste en probar todas las combinaciones posibles de contraseñas para obtener acceso no autorizado a un sistema.</li>
                <li><strong>Exploits y Vulnerabilidades:</strong> Uso de fallas de seguridad conocidas en software o sistemas para obtener acceso no autorizado.</li>
                <li><strong>Ataques de Denegación de Servicio (DDoS):</strong> Sobrecarga de un servidor o red con solicitudes falsas para que no pueda atender las solicitudes legítimas, lo que resulta en la caída del servicio.</li>
            </ol>
            
        </div>

        <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2023/12/13/13/21/cybersecurity-8446898_1280.png" alt="Imagen">
        </div>
      
  
      <div class="texto textBorder">
        <h2>Habilidades para la Ciberseguridad:</h2>
        <ol>
            <li><strong>Conocimientos en Redes:</strong> Comprender cómo funcionan las redes informáticas y cómo los datos se comunican entre sí es fundamental para identificar posibles puntos de vulnerabilidad.</li>
            <li><strong>Programación:</strong> Tener habilidades en lenguajes de programación como Python, C++ o Java permite entender el funcionamiento interno de los sistemas y desarrollar herramientas para defenderse contra ataques.</li>
            <li><strong>Conocimientos en Sistemas Operativos:</strong> Entender cómo funcionan los sistemas operativos como Windows, Linux o macOS es esencial para identificar vulnerabilidades y aplicar medidas de seguridad.</li>
            <li><strong>Criptografía:</strong> Comprender los principios de la criptografía es fundamental para proteger la información confidencial y asegurar la comunicación en línea.</li>
            <li><strong>Ética y Legalidad:</strong> Es importante tener una comprensión clara de lo que es ético y legal en el ámbito del hacking. Los hackers éticos deben operar dentro de los límites legales y éticos para garantizar que su trabajo contribuya positivamente a la seguridad informática.</li>
        </ol>
      </div>
      <div class="d-flex justify-center">
            <v-btn to="/curso2/temas/tema2" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
        </div>
    </div>
  </template>
  
  <style>

.mainClass{
    padding: 5%;
    text-align: justify;
}


h2{
    margin-bottom: 2%;
}

.threat {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    
  }

.textBorder{
    border: solid #7a7a7a 2px;
    border-radius: 15px;
    padding: 3%;
}

.texto{
    margin: 4% 0 4% 0;
}

.texto li{
    margin-bottom: 1%;
}


img{
    width: 50%; 
}

.imagenCentro{
    display: flex;
    justify-content: center;
}


  </style>