<template>
  <div class="container">
    <h1 class="text-center mb-5 font-weight-bold">Amenazas contra la Seguridad</h1>
    <div class="threats">
      <div class="passive-threats">
        <h2>Amenazas Pasivas</h2>
        <p>Las amenazas pasivas son aquellas que intentan obtener información sin afectar directamente los sistemas o los datos.</p>
        <ul>
          <li>Intercepción de datos: El atacante monitoriza o intercepta la comunicación para obtener información confidencial.</li>
          <li>Reconocimiento: El atacante recopila información sobre la red y sus sistemas para identificar vulnerabilidades.</li>
          <li>Escucha: El atacante obtiene información sensible al escuchar conversaciones o comunicaciones no cifradas.</li>
          <li>Análisis de tráfico: El atacante analiza el tráfico de red para identificar patrones de comportamiento o información sensible.</li>
        </ul>
      </div>
      <div class="active-threats">
        <h2>Amenazas Activas</h2>
        <p>Las amenazas activas son aquellas que intentan afectar directamente los sistemas o los datos para causar daño o interrupción.</p>
        <ul>
          <li>Ataques de denegación de servicio (DoS): El atacante intenta sobrecargar un sistema o red para hacerlo inaccesible para los usuarios legítimos.</li>
          <li>Malware: El atacante utiliza software malicioso, como virus, gusanos o troyanos, para infectar sistemas y robar información o causar daño.</li>
          <li>Ataques de inyección: El atacante introduce código malicioso o comandos en aplicaciones web u otros sistemas para comprometer su seguridad.</li>
          <li>Phishing: El atacante utiliza correos electrónicos o mensajes falsos para engañar a los usuarios y obtener información confidencial, como contraseñas o datos financieros.</li>
        </ul>
      </div>
    </div>
    <div class="d-flex justify-center">
      <v-btn to="/curso1/temas/tema6" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SecurityThreats',
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

.passive-threats,
.active-threats {
  background-color: #f4f4f4;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.passive-threats h2,
.active-threats h2 {
  margin-top: 0;
}

.passive-threats p,
.active-threats p {
  margin-bottom: 10px;
}

.passive-threats ul,
.active-threats ul {
  padding-left: 20px;
}

.passive-threats ul li,
.active-threats ul li {
  margin-bottom: 5px;
}
</style>
