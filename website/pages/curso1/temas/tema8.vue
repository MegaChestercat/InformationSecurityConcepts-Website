<template>
  <div class="container">
    <h1 class="text-center mb-5 font-weight-bold">Métodos Biométricos para la Defensa</h1>
    <div class="methods">
      <p>Los métodos biométricos son técnicas de autenticación que se basan en características físicas o comportamentales únicas de los individuos. Estos métodos se utilizan en la seguridad para verificar la identidad de las personas y proteger los sistemas contra accesos no autorizados. Algunos de los métodos biométricos más comunes incluyen:</p>
      <ul>
        <li><strong>Reconocimiento Facial:</strong> Utiliza características faciales únicas, como la forma de los ojos, la nariz y la boca, para autenticar a los usuarios. Los sistemas de reconocimiento facial pueden utilizar cámaras y algoritmos de aprendizaje automático para comparar la imagen de una persona con una base de datos de imágenes almacenadas.</li>
        <li><strong>Reconocimiento de Iris:</strong> Analiza el patrón único de la iris del ojo para identificar a las personas. Este método es altamente preciso y se utiliza en aplicaciones de alta seguridad, como el control de acceso a edificios y la verificación de identidad en aeropuertos.</li>
        <li><strong>Reconocimiento de Huellas Dactilares:</strong> Mide las características únicas de las huellas dactilares para autenticar a los usuarios. Este método es ampliamente utilizado en dispositivos móviles, como teléfonos inteligentes y tabletas, así como en sistemas de control de acceso físico.</li>
        <li><strong>Reconocimiento de Voz:</strong> Analiza las características únicas de la voz de una persona, como el tono, la frecuencia y el patrón de habla, para verificar su identidad. Los sistemas de reconocimiento de voz se utilizan en aplicaciones de autenticación telefónica y control de voz en dispositivos inteligentes.</li>
        <li><strong>Reconocimiento de Venas:</strong> Examina el patrón de las venas debajo de la piel para autenticar a los usuarios. Este método es menos común que otros métodos biométricos, pero ofrece un alto nivel de precisión y seguridad.</li>
      </ul>
    </div>
    <div class="d-flex justify-center">
      <v-btn to="/curso1/dashboard" color="success" size="large" class="my-10">Finalizar Curso</v-btn>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BiometricDefenseMethods',
};
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.methods {
  background-color: #f4f4f4;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.methods h2 {
  margin-top: 0;
}

.methods p {
  margin-bottom: 20px;
}

.methods ul {
  padding-left: 20px;
}

.methods ul li {
  margin-bottom: 10px;
}
</style>
