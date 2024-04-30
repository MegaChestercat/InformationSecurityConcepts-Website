<template>
    <div class="mainClass">
      <h1 style="text-align: center; margin-bottom: 5%">Firewalls</h1>
      <p>Los firewalls son una parte fundamental de la seguridad de red que actúan como una barrera entre una red interna privada y redes externas no confiables, como Internet. Su función principal es controlar y filtrar el tráfico de red según un conjunto de reglas predefinidas, con el objetivo de prevenir accesos no autorizados, ataques y la propagación de malware. Aquí te proporcionaré una visión detallada de los firewalls, incluyendo tipos, beneficios, limitaciones y subtemas derivados:</p>
  
      <div class="texto textBorder">
        <h2>Tipos de Firewalls:</h2>
        <ol>
            <li><strong>Firewalls de Packet Filtering (Filtrado de Paquetes):</strong> Examinan cada paquete de datos que entra o sale de la red y deciden si permitir o bloquear según las reglas de filtrado definidas.</li>
            <li><strong>Firewalls de Estado (Stateful Firewalls):</strong> Realizan un seguimiento del estado de las conexiones de red y permiten o bloquean el tráfico en función del estado de la sesión.</li>
            <li><strong>Firewalls de Aplicación (Application Firewalls):</strong> Inspeccionan el tráfico a nivel de aplicación, lo que les permite detectar y bloquear ataques específicos a aplicaciones.</li>
            <li><strong>Firewalls de Próximos Generación (Next-Generation Firewalls - NGFW):</strong> Integran características avanzadas como inspección profunda de paquetes, prevención de intrusiones y filtrado de contenido web en una sola solución.</li>
        </ol>
      </div>

      <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2013/07/13/12/33/wall-159844_1280.png" alt="Imagen">
        </div>
  
      <div class="texto textBorder">
        <h2>Beneficios de los Firewalls:</h2>
        <ol>
            <li><strong>Seguridad de Red:</strong> Protegen las redes contra accesos no autorizados, ataques maliciosos y la propagación de malware.</li>
            <li><strong>Control de Tráfico:</strong> Permiten a los administradores de red establecer políticas de seguridad para controlar el tráfico entrante y saliente.</li>
            <li><strong>Monitorización y Registro:</strong> Registran y auditan el tráfico de red, lo que permite a los administradores identificar y responder a actividades sospechosas o anomalías.</li>
            <li><strong>Cumplimiento Normativo:</strong> Ayudan a cumplir con los requisitos de seguridad y privacidad establecidos por regulaciones como GDPR, HIPAA y PCI-DSS.</li>
        </ol>
      </div>

      <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2012/04/11/10/19/firewall-27297_1280.png" alt="Imagen">
        </div>

      <div class="texto textBorder">
        <h2>Limitaciones de los Firewalls:</h2>
        <ol>
            <li><strong>Filtrado Limitado:</strong> Pueden no detectar ciertos tipos de ataques avanzados, como ataques de día cero o ataques basados en ingeniería social.</li>
            <li><strong>Costo y Complejidad:</strong> Las soluciones de firewall más avanzadas pueden ser costosas de implementar y mantener, especialmente para organizaciones más pequeñas.</li>
            <li><strong>Rendimiento:</strong> El filtrado exhaustivo del tráfico puede afectar el rendimiento de la red, especialmente en firewalls con capacidades avanzadas de inspección de paquetes.</li>
            <li><strong>Configuración Incorrecta:</strong> Una configuración incorrecta del firewall puede conducir a falsos positivos, falsos negativos o vulnerabilidades de seguridad.</li>
        </ol>
      </div>
  
      <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2022/12/04/20/49/laptop-7635374_1280.png" alt="Imagen">
        </div>

      <div class="texto textBorder">
        <h2>Subtemas Derivados de los Firewalls:</h2>
        <ol>
            <li><strong>Prevención de Intrusiones (Intrusion Prevention Systems - IPS):</strong> Extensiones de los firewalls que detectan y bloquean ataques en tiempo real.</li>
            <li><strong>Filtrado de Contenido Web:</strong> Funciones que permiten bloquear o permitir el acceso a sitios web basados en categorías o reglas predefinidas.</li>
            <li><strong>VPN y Acceso Remoto Seguro:</strong> Funcionalidades que permiten establecer conexiones seguras a la red interna desde ubicaciones externas a través de VPN.</li>
            <li><strong>Firewalls Personales:</strong> Aplicaciones de software instaladas en dispositivos individuales para controlar el tráfico de red y proteger contra amenazas locales.</li>
        </ol>
      </div>
  
      <div class="imagenCentro">
            <img src="https://cdn.pixabay.com/photo/2012/04/02/16/37/server-24903_1280.png" alt="Imagen">
        </div>

      <div class="texto threat">
        <p>En resumen, los firewalls son una parte crucial de la estrategia de seguridad de cualquier organización, pero es importante entender sus tipos, beneficios, limitaciones y subtemas relacionados para implementarlos de manera efectiva y mitigar los riesgos de seguridad.</p>
      </div>
      <div class="d-flex justify-center">
        <v-btn to="/curso2/temas/tema7" color="success" size="large" class="my-10">Ir al siguiente tema</v-btn>
      </div>
    </div>
  </template>
  