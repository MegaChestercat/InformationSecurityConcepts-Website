<template>
  <div class="container">
    <h1 class="text-center mb-5 font-weight-bold">Mecanismos y Servicios de Seguridad</h1>
    <div class="mechanisms">
      <div class="authentication">
        <h2>Autenticación</h2>
        <p>La autenticación es el proceso de verificar la identidad de un usuario o dispositivo.</p>
        <ul>
          <li>Contraseñas: El usuario proporciona una contraseña secreta para demostrar su identidad.</li>
          <li>Biometría: Se utilizan características físicas o comportamentales únicas, como huellas dactilares o reconocimiento facial, para la autenticación.</li>
          <li>Token de seguridad: Se utiliza un dispositivo físico o una aplicación móvil para generar un código único que se utiliza para la autenticación.</li>
        </ul>
      </div>
      <div class="encryption">
        <h2>Encriptación</h2>
        <p>La encriptación es el proceso de convertir datos en un formato ilegible que solo puede ser entendido por personas autorizadas.</p>
        <ul>
          <li>Encriptación simétrica: Se utiliza una única clave para cifrar y descifrar los datos.</li>
          <li>Encriptación asimétrica: Se utilizan dos claves diferentes, una pública y una privada, para cifrar y descifrar los datos.</li>
          <li>Protocolos de seguridad: Se utilizan protocolos como SSL/TLS para garantizar la seguridad de la comunicación en línea.</li>
        </ul>
      </div>
      <div class="firewalls">
        <h2>Cortafuegos (Firewalls)</h2>
        <p>Los cortafuegos son dispositivos o software que controlan el tráfico de red y protegen una red privada de accesos no autorizados.</p>
        <ul>
          <li>Cortafuegos de red: Filtran el tráfico en función de reglas predefinidas para permitir o bloquear el acceso.</li>
          <li>Cortafuegos de aplicación: Inspeccionan el tráfico a nivel de aplicación para detectar y bloquear amenazas específicas.</li>
          <li>Cortafuegos de próxima generación: Utilizan técnicas avanzadas, como la inspección profunda de paquetes y el análisis de comportamiento, para identificar y mitigar amenazas.</li>
        </ul>
      </div>
      <div class="ids-ips">
        <h2>Sistemas de Detección y Prevención de Intrusiones (IDS/IPS)</h2>
        <p>Los IDS monitorean el tráfico de red en busca de actividades sospechosas, mientras que los IPS intervienen activamente para bloquear o prevenir intrusiones.</p>
        <ul>
          <li>IDS basados en red: Analizan el tráfico de red en busca de patrones de comportamiento y firmas de amenazas conocidas.</li>
          <li>IDS basados en host: Monitorizan la actividad en un sistema específico, como un servidor, en busca de actividades anómalas.</li>
          <li>IPS basados en red: Interceptan y bloquean el tráfico malicioso en tiempo real para proteger la red.</li>
        </ul>
      </div>
    </div>
    <div class="d-flex justify-center">
      <v-btn to="/curso1/temas/tema7" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SecurityMechanisms',
};
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.mechanisms {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}

.authentication,
.encryption,
.firewalls,
.ids-ips {
  background-color: #f4f4f4;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.authentication h2,
.encryption h2,
.firewalls h2,
.ids-ips h2 {
  margin-top: 0;
}

.authentication p,
.encryption p,
.firewalls p,
.ids-ips p {
  margin-bottom: 10px;
}

.authentication ul,
.encryption ul,
.firewalls ul,
.ids-ips ul {
  padding-left: 20px;
}

.authentication ul li,
.encryption ul li,
.firewalls ul li,
.ids-ips ul li {
  margin-bottom: 5px;
}
</style>
