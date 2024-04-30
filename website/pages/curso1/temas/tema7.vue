<template>
  <div class="container">
    <h1>Modelo de Seguridad de Red</h1>
    <div class="model">
      <p>Un modelo de seguridad de red es una estructura conceptual que define cómo se diseñan, implementan y gestionan las medidas de seguridad en una red de computadoras. Estos modelos proporcionan un marco para organizar y entender los diferentes aspectos de la seguridad de red, incluyendo la protección de datos, la gestión de identidad y acceso, y la detección y respuesta a amenazas.</p>
      <h2>Principales Componentes de un Modelo de Seguridad de Red</h2>
      <ol>
        <li><strong>Perímetro de Seguridad:</strong> Define los límites de la red y los puntos de entrada y salida. Las tecnologías como los cortafuegos y los sistemas de prevención de intrusiones se utilizan para proteger el perímetro de la red contra amenazas externas.</li>
        <li><strong>Segmentación de Red:</strong> Divide la red en segmentos más pequeños para limitar la propagación de amenazas y mejorar la seguridad y el rendimiento. Se pueden implementar VLANs (Redes de Área Local Virtuales) y ACLs (Listas de Control de Acceso) para segmentar la red.</li>
        <li><strong>Control de Acceso:</strong> Gestiona quién tiene acceso a qué recursos en la red. Se utilizan técnicas de autenticación y autorización para verificar la identidad de los usuarios y controlar sus privilegios de acceso.</li>
        <li><strong>Monitoreo y Análisis:</strong> Supervisa el tráfico de red en busca de comportamientos anómalos y posibles amenazas. Los registros de seguridad y los sistemas de gestión de eventos e información de seguridad (SIEM) se utilizan para recopilar y analizar datos de seguridad.</li>
        <li><strong>Protección de Datos:</strong> Encripta y protege los datos confidenciales en tránsito y en reposo. Se pueden utilizar tecnologías como SSL/TLS para cifrar la comunicación y soluciones de cifrado de datos para proteger la información almacenada.</li>
        <li><strong>Gestión de Identidad:</strong> Administra las identidades digitales de usuarios y dispositivos en la red. Los sistemas de gestión de identidades y accesos (IAM) se utilizan para gestionar el ciclo de vida de las cuentas de usuario, incluyendo la creación, modificación y eliminación de cuentas.</li>
        <li><strong>Detección y Respuesta a Amenazas:</strong> Detecta y responde a incidentes de seguridad de manera oportuna. Los sistemas de detección de intrusos (IDS) y los sistemas de gestión de incidentes de seguridad (SIM) se utilizan para identificar y mitigar amenazas.</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NetworkSecurityModel',
};
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.model {
  background-color: #f4f4f4;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.model h2 {
  margin-top: 0;
}

.model p {
  margin-bottom: 20px;
}

.model ol {
  padding-left: 20px;
}

.model ol li {
  margin-bottom: 10px;
}
</style>
