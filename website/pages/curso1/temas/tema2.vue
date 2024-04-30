<template>
    <div class="container">
      <h1>Capas de la Web</h1>
      <div class="layers">
        <div class="layer">
          <h2>Web Superficial</h2>
          <p>La web superficial, también conocida como web visible o indexada, es la parte de internet que está indexada por los motores de búsqueda y es accesible para el público en general. Contiene sitios web que son fácilmente accesibles a través de motores de búsqueda convencionales como Google, Bing y Yahoo.</p>
          <p>Los sitios de la web superficial suelen tener una estructura simple y son fáciles de encontrar utilizando palabras clave en los motores de búsqueda.</p>
          <p>Este nivel de la web es comúnmente utilizado para publicar contenido público, como blogs, sitios de noticias, páginas web corporativas y mucho más.</p>
        </div>
        <div class="layer">
          <h2>Web Profunda</h2>
          <p>La web profunda, también llamada web invisible o web no indexada, es la parte de internet que no es indexada por los motores de búsqueda convencionales. Esta capa de la web incluye contenido que está protegido por contraseñas, bases de datos privadas, archivos en la nube y otras formas de información que no son accesibles públicamente.</p>
          <p>El contenido de la web profunda no es fácilmente accesible a través de los motores de búsqueda tradicionales y generalmente requiere credenciales de inicio de sesión o acceso específico para verlo.</p>
          <p>Esta capa de la web es utilizada por organizaciones, instituciones académicas, empresas y otros usuarios que necesitan proteger su información y restringir el acceso a determinados usuarios.</p>
        </div>
        <div class="layer">
          <h2>Web Oscura</h2>
          <p>La web oscura, a veces conocida como darknet, es una parte de internet que está oculta y no es accesible a través de navegadores web convencionales. Se accede a través de redes privadas y requiere software específico, como el navegador Tor, para acceder a ella.</p>
          <p>La web oscura es conocida por ser un lugar donde se llevan a cabo actividades ilegales y clandestinas, como la venta de drogas, armas, información robada y otros bienes y servicios ilegales.</p>
          <p>Si bien la web oscura tiene una reputación negativa debido a sus actividades ilícitas, también puede ser utilizada por periodistas, activistas y usuarios preocupados por la privacidad para comunicarse y compartir información de manera segura y anónima.</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'WebLayers',
  };
  </script>
  
  <style scoped>
  .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  
  .layers {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
  }
  
  .layer {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  
  .layer h2 {
    margin-top: 0;
  }
  
  .layer p {
    margin-bottom: 10px;
  }
  </style>
  