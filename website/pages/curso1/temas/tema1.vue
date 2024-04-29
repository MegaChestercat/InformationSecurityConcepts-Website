<template>
    <div class="container">
      <h1>Amenazas a la Ciberseguridad</h1>
      <div class="threats">
        <div class="threat">
          <h2>Malware</h2>
          <p>El malware es software malicioso diseñado para infiltrarse o dañar una computadora o sistema de información.</p>
        </div>
        <div class="threat">
          <h2>Phishing</h2>
          <p>El phishing es un intento de adquirir información confidencial, como contraseñas y detalles de tarjetas de crédito, haciéndose pasar por una entidad confiable en una comunicación electrónica.</p>
        </div>
        <div class="threat">
          <h2>Ataques de Denegación de Servicio (DDoS)</h2>
          <p>Los ataques de denegación de servicio buscan inundar un sistema, servidor o red con tráfico inútil o malintencionado para interrumpir o paralizar los servicios.</p>
        </div>
        <div class="threat">
          <h2>Ataques de Ransomware</h2>
          <p>El ransomware es un tipo de malware que cifra los datos de un usuario y exige un rescate para desbloquearlos. Los ataques de ransomware pueden causar pérdidas financieras significativas y afectar gravemente la operatividad de una organización.</p>
        </div>
        <div class="threat">
          <h2>Ataques de Ingeniería Social</h2>
          <p>Los ataques de ingeniería social implican el engaño de individuos para obtener información confidencial o acceso no autorizado a sistemas. Esto puede incluir la manipulación psicológica, el uso de pretextos falsos o la creación de mensajes engañosos.</p>
        </div>
        <div class="threat">
          <h2>Ataques de Intermediarios (Man-in-the-Middle)</h2>
          <p>En un ataque de intermediario, un atacante intercepta y altera la comunicación entre dos partes sin su conocimiento. Esto puede permitir al atacante robar datos sensibles o modificar la información transmitida.</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CyberSecurityThreats',
  };
  </script>
  
  <style scoped>
  .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  
  .threats {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
  }
  
  .threat {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  
  .threat h2 {
    margin-top: 0;
  }
  
  .threat p {
    margin-bottom: 0;
  }
  </style>
  