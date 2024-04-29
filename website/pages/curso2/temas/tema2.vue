<template>
    <div class="mainClass">
      <h1 style="text-align: center;">Detección de Intrusos</h1>
      <p>La detección de intrusos es un componente fundamental de la ciberseguridad que se centra en identificar y responder a actividades maliciosas o anómalas en sistemas informáticos o redes. Los sistemas de detección de intrusos (IDS) y los sistemas de prevención de intrusos (IPS) son herramientas clave en este campo.</p>
  
      <h2>Sistemas de Detección de Intrusos (IDS):</h2>
      <p>Los IDS monitorean el tráfico de red o los eventos en sistemas informáticos en busca de actividades sospechosas o patrones que puedan indicar una intrusión. Hay dos tipos principales de IDS:</p>
      <ol>
        <li><strong>IDS de Red (NIDS):</strong> Monitorean el tráfico en la red en busca de patrones de comportamiento sospechosos o firmas de ataques conocidos. Funcionan analizando los paquetes de datos que atraviesan la red y comparándolos con una base de datos de firmas de ataques conocidos.</li>
        <li><strong>IDS de Host (HIDS):</strong> Se ejecutan en sistemas individuales y supervisan eventos en el sistema operativo y en las aplicaciones. Pueden detectar actividades anómalas como cambios en archivos de sistema, intentos de acceso no autorizado o comportamientos inusuales de aplicaciones.</li>
      </ol>
  
      <h2>Sistemas de Prevención de Intrusos (IPS):</h2>
      <p>Los IPS van un paso más allá que los IDS al no solo detectar, sino también prevenir actividades maliciosas mediante la aplicación de medidas proactivas. Utilizan las mismas técnicas de detección que los IDS, pero también pueden tomar medidas automáticas para bloquear o mitigar las amenazas detectadas. Hay dos tipos principales de IPS:</p>
      <ol>
        <li><strong>IPS de Red (NIPS):</strong> Se sitúan en puntos estratégicos de la red y pueden bloquear o filtrar el tráfico malicioso en tiempo real. Esto puede incluir la eliminación de paquetes de datos maliciosos o la modificación de reglas de firewall para bloquear el tráfico de origen malicioso.</li>
        <li><strong>IPS de Host (HIPS):</strong> Se ejecutan en sistemas individuales y monitorean y protegen el sistema operativo y las aplicaciones instaladas en él. Pueden tomar medidas como bloquear el acceso a archivos o detener procesos sospechosos.</li>
      </ol>
  
      <h2>Ejemplos de Uso:</h2>
      <ol>
        <li><strong>Detección de Ataques de Denegación de Servicio (DDoS):</strong> Un IDS puede detectar patrones de tráfico inusualmente alto que podrían indicar un ataque DDoS en curso. Un IPS puede entonces bloquear las direcciones IP de origen del tráfico malicioso para mitigar el impacto del ataque.</li>
        <li><strong>Detección de Intrusos en Redes Corporativas:</strong> Un NIDS puede detectar intentos de acceso no autorizado a servidores o intentos de robo de datos sensibles. Un IPS puede entonces bloquear el tráfico malicioso y enviar alertas al equipo de seguridad para una respuesta rápida.</li>
        <li><strong>Protección de Servidores y Estaciones de Trabajo:</strong> Un HIDS instalado en un servidor puede detectar intentos de modificación de archivos de sistema o actividad inusual en las cuentas de usuario. Un HIPS puede entonces bloquear o revertir los cambios maliciosos y prevenir la escalada del ataque.</li>
      </ol>
  
      <p>En resumen, los sistemas de detección y prevención de intrusos son herramientas esenciales en la ciberseguridad moderna, ya que ayudan a proteger sistemas informáticos y redes contra una amplia gama de amenazas y ataques.</p>
    </div>
  </template>
  
