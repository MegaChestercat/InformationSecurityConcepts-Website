<template>
  <div class="container">
    <h1 class="text-center mb-5 font-weight-bold">Arquitectura de Seguridad OSI</h1>
    <div class="osi">
      <div class="layer">
        <h2>Capa 1: Física</h2>
        <p>La capa física se encarga de la transmisión de bits sin procesar a través de un medio de comunicación físico, como cables o señales de radio.</p>
        <p>Los principales riesgos de seguridad en esta capa incluyen la interceptación de señales, el sabotaje físico de cables y dispositivos, y el acceso no autorizado a equipos de red.</p>
      </div>
      <div class="layer">
        <h2>Capa 2: Enlace de Datos</h2>
        <p>La capa de enlace de datos se encarga de la transmisión de datos entre dispositivos en la misma red local.</p>
        <p>Los riesgos de seguridad en esta capa incluyen los ataques de spoofing de direcciones MAC, los ataques de denegación de servicio (DoS) y los ataques de ingeniería social dirigidos a obtener acceso a la red.</p>
      </div>
      <div class="layer">
        <h2>Capa 3: Red</h2>
        <p>La capa de red se encarga de enrutar los datos entre redes diferentes y de controlar el flujo de datos a través de la red.</p>
        <p>Los principales riesgos de seguridad en esta capa incluyen los ataques de envenenamiento de tablas de enrutamiento, los ataques de redireccionamiento de tráfico y los ataques de denegación de servicio distribuido (DDoS).</p>
      </div>
      <div class="layer">
        <h2>Capa 4: Transporte</h2>
        <p>La capa de transporte se encarga de garantizar la entrega de datos de manera confiable y ordenada entre sistemas finales.</p>
        <p>Los riesgos de seguridad en esta capa incluyen los ataques de inyección de datos, los ataques de secuestro de sesiones y los ataques de denegación de servicio.</p>
      </div>
      <div class="layer">
        <h2>Capa 5: Sesión</h2>
        <p>La capa de sesión se encarga de establecer, mantener y finalizar las conexiones de comunicación entre sistemas finales.</p>
        <p>Los riesgos de seguridad en esta capa incluyen los ataques de secuestro de sesión, los ataques de ingeniería social dirigidos a obtener credenciales de inicio de sesión y los ataques de negación de servicio.</p>
      </div>
      <div class="layer">
        <h2>Capa 6: Presentación</h2>
        <p>La capa de presentación se encarga de traducir los datos en un formato que pueda ser entendido por las aplicaciones.</p>
        <p>Los principales riesgos de seguridad en esta capa incluyen los ataques de inyección de código, los ataques de manipulación de datos y los ataques de suplantación de identidad.</p>
      </div>
      <div class="layer">
        <h2>Capa 7: Aplicación</h2>
        <p>La capa de aplicación se encarga de proporcionar servicios de red a las aplicaciones de usuario.</p>
        <p>Los riesgos de seguridad en esta capa incluyen los ataques de phishing, los ataques de malware y los ataques de ingeniería social dirigidos a los usuarios finales.</p>
      </div>
    </div>
    <div class="d-flex justify-center">
      <v-btn to="/curso1/temas/tema5" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
    </div>
  </div>
</template>

<script>
export default {
  name: 'OSISecurityArchitecture',
};
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.osi {
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
