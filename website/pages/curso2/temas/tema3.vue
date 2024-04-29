<template>
    <div class="mainClass">
      <h1 style="text-align: center;">Acercamiento a la Detección de Intrusos</h1>
      <p>Un enfoque efectivo para la detección de intrusos implica la combinación de diversas técnicas y herramientas para identificar actividades maliciosas o anómalas en sistemas informáticos y redes. Aquí detallaré los diferentes aspectos clave de este enfoque:</p>
  
      <h2>Tipos de Anomalías:</h2>
      <ol>
        <li><strong>Anomalías de Tráfico de Red:</strong> Incluyen cambios significativos en el volumen de tráfico, patrones de comunicación inusuales, o actividades como escaneo de puertos y barrido de redes que pueden indicar un intento de intrusión.</li>
        <li><strong>Anomalías de Comportamiento del Usuario:</strong> Implican actividades inusuales por parte de usuarios, como acceso a recursos no autorizados, cambios repentinos en los patrones de acceso, o intentos de iniciar sesión con credenciales incorrectas en repetidas ocasiones.</li>
        <li><strong>Anomalías de Sistema:</strong> Detectan cambios en el comportamiento o el estado del sistema, como modificaciones en archivos de sistema, cambios en los privilegios de usuario, o actividades inusuales de procesos o servicios.</li>
      </ol>
  
      <h2>Signatures (Firmas):</h2>
      <p>Las firmas son patrones específicos asociados con actividades maliciosas conocidas. Los IDS utilizan bases de datos de firmas para comparar con el tráfico de red o los eventos del sistema en busca de coincidencias. Si se encuentra una coincidencia, se genera una alerta para indicar una posible intrusión.</p>
  
      <h2>Modelos:</h2>
      <ol>
        <li><strong>Basados en Reglas:</strong> Utilizan reglas predefinidas para identificar actividades maliciosas. Estas reglas pueden estar basadas en firmas conocidas, patrones de comportamiento o políticas de seguridad de la organización.</li>
        <li><strong>Basados en Anomalías:</strong> Comparan el comportamiento actual del sistema o de la red con un perfil normal previamente establecido. Las desviaciones significativas del perfil normal pueden indicar una intrusión.</li>
      </ol>
  
      <h2>Lo que los IDS pueden detectar:</h2>
      <ol>
        <li><strong>Intentos de Acceso no Autorizado:</strong> Incluyendo escaneos de puertos, intentos de autenticación fallidos y explotación de vulnerabilidades conocidas.</li>
        <li><strong>Tráfico Malicioso:</strong> Como ataques de denegación de servicio (DDoS), tráfico de malware, o comunicaciones de comando y control de botnets.</li>
        <li><strong>Exfiltración de Datos:</strong> Detección de transferencias de datos no autorizadas desde la red interna hacia fuentes externas, lo que puede indicar un robo de información.</li>
      </ol>
  
      <h2>Sensores:</h2>
      <p>Los sensores son los componentes que recopilan datos para el análisis del IDS. Pueden ser hardware o software, y se despliegan en diferentes puntos de la red o en sistemas individuales para monitorear y recolectar información sobre el tráfico de red, eventos del sistema o actividades de usuario.</p>
  
      <p>En resumen, un enfoque integral para la detección de intrusos combina el uso de firmas, modelos de comportamiento y análisis de anomalías para identificar y responder a actividades maliciosas en sistemas informáticos y redes. Esto implica una combinación de tecnologías, procesos y políticas para proteger eficazmente los activos digitales de una organización contra las amenazas cibernéticas.</p>
    </div>
  </template>

