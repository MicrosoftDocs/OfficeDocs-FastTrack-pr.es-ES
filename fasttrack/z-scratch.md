---
title: Seguridad y cumplimiento
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: O365-seccomp
localization_priority: None
ms.collection: FastTrack
description: Detalles de instrucciones de FastTrack para los servicios de Microsoft.
ms.openlocfilehash: 000a81c51729deba8d3f5c4d88a0baa918dcd048
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996249"
---
# <a name="security-and-compliance"></a>Seguridad y cumplimiento

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender es un conjunto unificado de defensa empresarial anterior y posterior a la infracción que coordina de forma nativa la detección, prevención, investigación y respuesta entre puntos de conexión, identidades, correo electrónico y aplicaciones para proporcionar protección integrada contra ataques sofisticados. Proporcionamos instrucciones remotas para: </p> 
<ul>
<li>  Proporcionar información general sobre el Centro de seguridad de Microsoft 365.  </li>
<li>  Revisión de incidentes entre productos, incluido el centrarse en lo que es fundamental al garantizar el ámbito de ataque completo, los activos afectados y las acciones de corrección automatizadas que se agrupan.  </li>
<li>  Demostración de cómo Microsoft 365 Defender puede orquestar la investigación de activos, usuarios, dispositivos y buzones de correo que podrían haber sido comprometidos a través de la recuperación automática. </li>
<li>  Explicar y proporcionar ejemplos de cómo los clientes pueden buscar proactivamente intentos de intrusión y actividad de infracción que afecten al correo electrónico, los datos, los dispositivos y las cuentas en varios conjuntos de datos.   </li>
<li> Mostrar a los clientes cómo pueden revisar y mejorar su posición de seguridad de forma holística con Microsoft Secure Score.</li>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>
<li> Administración de proyectos de las actividades de corrección de los clientes. </li>
<li> Administración continua, respuesta a amenazas y corrección. </li>
<li> Instrucciones de implementación o educación sobre:
<ul>
<li> Cómo corregir o interpretar los distintos tipos de alerta y actividades supervisadas. </li>
<li> Cómo investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad. </li>
<li> Búsqueda de amenazas personalizada.  </li>
</ul>
</li>
<li> Información de seguridad y administración de eventos (SIEM) o integración de API.</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una amplia visibilidad, control sobre el desplazamiento de datos y análisis sofisticados para identificar y combatir las amenazas cibernéticas en todos los servicios en la nube de Microsoft y de terceros. Proporcionamos instrucciones remotas para:
<ul>
<li>  Configurar el portal, incluidos:  </li>
<ul>
<li> Importar grupos de usuarios.</li>
<li> Administrar el acceso de administrador y la configuración.  </li>
<li> Ámbito de la implementación para seleccionar determinados grupos de usuarios para supervisar o excluir de la supervisión.</li>
<li> Establecer intervalos y etiquetas IP.</li>
<li> Personalizar la experiencia del usuario final con el logotipo y la mensajería personalizada.</li>
</ul>
<li> Configuración de la detección en la nube para proporcionar UNA instantánea con:</li>
<ul>
<li> Microsoft Defender para puntos de conexión.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Conectar <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">aplicaciones características con</a> conectores de aplicaciones.</li>
<li> Configurar el control de aplicaciones de acceso condicional en los portales de Acceso condicional y Seguridad de aplicaciones en la nube para aplicar controles de sesión en tiempo real.</li>
<li> Implementación de los paneles Cloud App Security y Cloud Discovery.</li>
<li> Personalizar las puntuaciones de riesgo de la aplicación en función de las prioridades de la organización.</li>
<li> Crear etiquetas y categorías de aplicaciones.</li>
<li> Sancionar y deshacer la autorización de aplicaciones.</li>
<li> Uso de la actividad y los registros de archivos.</li>
<li> Administrar aplicaciones de OAuth.</li>
<li> Descripción de la correlación de incidentes en el portal de Microsoft 365 Defender.</li>
<li> Proporcionar asistencia de configuración con los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 casos</a> de uso principales para CASB (incluida la creación o actualización de hasta seis (6) directivas), excepto: </li>
<ul>
<li> Auditar la configuración de internet como entornos de servicio (IaaS) (#18).</li>
<li> Supervisar las actividades de los usuarios para protegerse contra amenazas en los entornos de IaaS (#19).</li>
</ul>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>
<li> Administración de proyectos de las actividades de corrección de los clientes.</li>
<li> Administración continua, respuesta a amenazas y corrección. </li>
<li> Configurar la infraestructura, la instalación o la implementación de cargas automáticas de registros para informes continuos con Docker o un recopilador de registros. Vea <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> para obtener más detalles.</li>
<li> Creación de un informe de instantáneas de detección de nube.</li>
<li> Bloquear el uso de la aplicación mediante scripts de bloqueo.</li>
<li> Conexión de aplicaciones personalizadas.</li>
<li> Integración con proveedores de identidades de terceros (ISP) y proveedores de prevención de pérdida de datos (DLP).</li>
<li> Aprendizaje o instrucciones sobre la búsqueda avanzada.</li>
<li> Investigación y corrección automatizadas, incluidos los libros de juegos de Microsoft Power Automate.</li>
<li> Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</li>
<li> Implementación de Cloud App Security como una prueba de concepto.</li>
</ul></td>
</tr>



<tr class="odd">
<td><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></td>
<td>  La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Implementar las tecnologías para proteger los puntos de conexión.  </li>
<li>  Configuración de perfiles de restricción de dispositivos y protección de puntos de conexión.  </li>
<li>  Evaluación de la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios antivirus de Windows Defender u otro software de seguridad de puntos de conexión.  </li>
<li>  Evaluar el estado de los servicios antivirus de Windows u otro software de seguridad de puntos de conexión.  </li>
<li>  Evaluación de servidores proxy y firewalls que restringen el tráfico de red.  </li>
<li>  Para habilitar el servicio ATP de Microsoft Defender, explique cómo implementar un perfil de agente de ATP con un punto de conexión integrado.  </li>
<li>  Instrucciones de implementación, asistencia de configuración y educación sobre:
<ul>
<li>  
  Administración de amenazas y vulnerabilidades.  
  </li>
<li>  
  Reducción de la superficie de ataque.  
  </li>
<li>  
  Protección de nueva generación.  
  </li>
<li>  
  Detección y respuesta de puntos de conexión.  
  </li>
<li>  
  Investigación y corrección automatizadas.  
  </li>
<li>  
  Puntuación de seguridad.  
  </li>
</ul></li>
<li>  Revisión de simulaciones y tutoriales (como escenarios de práctica, malware falso e investigaciones automatizadas).  </li>
<li>  Información general sobre las características de informes y análisis de amenazas.  </li>
<li>  Integrar Protección contra amenazas avanzadas de Office 365 con Protección contra amenazas avanzada de Microsoft Defender.  </li>
<li>  Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.  </li>
<li>  Los siguientes sistemas operativos:
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Server 2019.  
  </li>
<li>  
  Windows Server 2019 Core Edition.  
  </li>
<li>  
  Windows Server Semi-Annual Channel (SAC) versión 1803.  
  </li>
<li>  
  macOS versiones 10.13, 10.14 y 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la versión más reciente de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior). 

</li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>  Administración de proyectos de las actividades de corrección de los clientes.  </li>
<li>  Soporte técnico en las instalaciones.  </li>
<li>  Administración continua y respuesta ante amenazas.  </li>
<li>  Incorporación o configuración para los siguientes agentes de Protección contra amenazas avanzada de Microsoft Defender:
<ul>
<li>  
  Windows Server 2008.  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Linux.  
  </li>
<li>  
  Dispositivos móviles (Android e iOS).  
  </li>
</ul></li>
<li>  Configuración y incorporación de servidores:
<ul>
<li>  
  Configurar un servidor proxy para comunicaciones sin conexión.  
  </li>
<li>  
  Configuración de paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.  
  </li>
<li>  
  Incorporación de servidores al Centro de seguridad de Azure.  
  </li>
<li>  
  Servidores no administrados por Configuration Manager.  
  </li>
</ul></li>
<li>  Configuración y incorporación de macOS:
<ul>
<li>  
  Implementación manual basada en Intune.  
  </li>
<li>  
  Implementación basada en JAMF.
  </li>
<li>  
  Otra implementación basada en productos de administración de dispositivos móviles (MDM).  
  </li>
<li>  
  Implementación manual.  
  </li>
</ul></li>
<li>  Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:
<ul>
<li>  
  Aislamiento basado en hardware.  
  </li>
<li>  
  Control de aplicaciones.  
  </li>
<li>  
  Protección contra vulnerabilidades de seguridad.  
  </li>
<li>  
  Firewall de red.  
  </li>
</ul></li>
<li>  Inscripción o configuración de Expertos en amenazas de Microsoft.  </li>
<li>  Configuración o aprendizaje que revisa las conexiones DE API o de información de seguridad y administración de eventos (SIEM).  </li>
<li>  Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).  </li>
<li>  Aprendizaje o instrucciones sobre la búsqueda avanzada.  </li>
<li>  Formación u instrucciones sobre el uso o creación de consultas de Kusto.</li>
</li>
</ul>
Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender para la identidad </strong></td>
<td>  Microsoft Defender for Identity es una solución de seguridad basada en la nube que aprovecha las señales locales de Active Directory para identificar, detectar e investigar las amenazas avanzadas, las identidades vulnerables y las acciones internas malintencionadas dirigidas a su organización. Proporcionamos instrucciones remotas para:
<ul>
<li>   Crear la instancia de Defender for Identity. </li>
<li>   Conectar Defender for Identity a Active Directory. </li>
<li>   Evaluar la preparación del entorno para implementar el sensor Defender for Identity en los controladores de dominio, incluidos:</li>   
<ul> 
<li>  Ejecución de la herramienta de tamaño para la planeación de capacidad de recursos. </li>
<li>  Ejecutar la herramienta de auditoría para evaluar la compatibilidad de los controladores de dominio con el sensor. </li>
</ul>
<li>  Implementar el sensor para capturar y analizar el tráfico de red y los eventos de Windows directamente desde los controladores de dominio, incluidos: </li>
<ul> 
<li>  Descargar el paquete del sensor. </li>
<li>  Configuración del sensor. </li>
<li>  Instalar el sensor en el controlador de dominio de forma silenciosa. </li>
<li>  Implementar el sensor en el entorno de varios bosques. </li>
</ul>
<li>  Integración de Defender para la identidad con Microsoft Cloud App Security (no se requieren licencias de Cloud App Security). </li>
<li>  Proporcionar instrucciones de implementación, asistencia de configuración y educación sobre: </li>
<ul>
<li> Ajustar el entorno para reducir el "ruido".  </li>
<li>  Descripción del informe de evaluación de la postura de seguridad de identidad. </li>
<li>  Descripción de la puntuación de prioridad de investigación del usuario y el informe de clasificación de la investigación del usuario. </li>
<li> Descripción del informe de usuario inactivo.  </li>
<li> Proporcionar opciones de corrección en una cuenta comprometida.  </li>
</ul>
<li>  Facilitar la migración de Análisis avanzado de amenazas (ATA) a Defender for Identity. </li>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>

<li> Administración de proyectos de las actividades de corrección de los clientes. </li>
<li> Administración continua, respuesta a amenazas y corrección.  </li>
<li> Implementación del sensor Defender for Identity, incluidos: </li>
<ul>
<li> Planeación manual de capacidad. </li>
<li> Implementar el sensor en una capacidad independiente. </li>
<li> Implementar el sensor mediante un adaptador de equipo de tarjeta de interfaz de red (NIC). </li>
<li> Implementar el sensor a través de una herramienta de terceros. </li>
<li> Conexión al servicio en la nube de Defender for Identity a través de una conexión de proxy web. </li>
</ul>
<li> Creación y administración de honeytokens. </li>
<li> Instrucciones de implementación o educación sobre: </li>
<ul>
<li> Corrección o interpretación de diversos tipos de alertas y actividades supervisadas.  </li>
<li> Investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad. </li>
<li> Amenaza o búsqueda avanzada. </li>
<li> Respuesta a incidentes. </li>
</ul>
<li> Proporcionar un tutorial de laboratorio de alertas de seguridad para Defender for Identity. </li>
<li> Proporcionar notificaciones cuando Defender for Identity detecta actividades sospechosas enviando alertas de seguridad al servidor de syslog a través de un sensor designado.  </li>
<li> Configuración de Defender for Identity para realizar consultas mediante el protocolo de administrador de cuentas de seguridad remoto (SAMR) para identificar a los administradores locales en máquinas específicas. </li>
<li> Configuración de soluciones VPN para agregar información desde la conexión VPN a la página de perfil de un usuario.  </li>
<li> Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel). </li>
<li> Implementar sensores de Defender for Identity como una prueba de concepto.</li>
</ul></td>
<td><ul>
<li>  Active Directory implementado.  </li>
<li>  Los controladores de dominio en los que quieres instalar los sensores de Defender for Identity tienen conectividad a Internet con el servicio en la nube de Defender for Identity.  </li>
<ul>
<li> El firewall y el proxy deben estar abiertos para comunicarse con el servicio en la nube de Defender for Identity (*.atp.azure.com el puerto 443 debe estar abierto).</li>
</ul>
<li> Controladores de dominio que se ejecutan en uno de los siguientes:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 con KB4487044 (compilación del sistema operativo 17763.316).</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Gobierno de información de Microsoft</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Etiquetas y directivas de retención  </li>
<li>  Administración de registros  </li>
<li>  Directivas de eliminación  </li>
<li>  Cumplimiento de comunicaciones  </li>
<li>  Administración de riesgos internos.  </li>
<li>  eDiscovery avanzado  </li>
</ul>

  <strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li> Desarrollo de un plan de archivos de administración de registros.</li>
<li> Conectores de datos.</li>
<li> Barreras de información.</li>
<li> Administración de acceso con privilegios.</li>
<li> Desarrollo de la arquitectura de la información en SharePoint.</li>
<li> Scripting y codificación personalizados.</li>
</td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="products-and-capabilities.md#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>
<tr class="odd">
<td><strong>Protección de la información de Microsoft</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Clasificación de los datos  </li>
<li>  Tipos de información confidencial.  </li>
<li>  Crear etiquetas de confidencialidad.  </li>
<li>  Aplicar etiquetas de confidencialidad.  </li>
<li>  Etiquetado unificado  </li>
<li>  Clasificadores que se pueden entrenar.  </li>
<li>  Conocer sus datos con el explorador de contenido y el explorador de actividades.  </li>
<li>  Publicar etiquetas mediante las directivas (manual y automático).  </li>
<li>  Crear directivas de protección de pérdida de datos (DLP) de los chats y canales de Microsoft Teams.  </li>
<li>  Crear directivas dlp de extremo para dispositivos Windows 10.  </li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>Clave de cliente.</li>
<li>Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</li>
<li>Creación o modificación de diccionarios de palabras clave.</li>
<li>Scripting y codificación personalizados.</li>
</ul>
<strong>Nota:</strong> Para obtener más información, <strong>vea Azure Information Protection</strong> in Enterprise Mobility + <a href="products-and-capabilities.md#enterprise-mobility--security">Security</a>.
<ul>

</td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="products-and-capabilities.md#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>

<tr class="odd">
<td><strong>Protección contra amenazas avanzada de Office 365 (ATP)</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).  </li>
<li>  Configurar la automatización, la investigación y la respuesta.  </li>
<li>  Usar el Simulador de ataques.  </li>
<li>  Elaborar informes y análisis de amenazas.  </li>
</ul></td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="products-and-capabilities.md#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>


<tr class="odd">
<td><strong>Respuesta & de detección</strong></td>
<td>  

<strong>Exhibición de documentos electrónicos avanzada</strong>
  
<ul>
<li>  Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).  </li>
<li>  Configurar la automatización, la investigación y la respuesta.  </li>
<li>  Usar el Simulador de ataques.  </li>
<li>  Elaborar informes y análisis de amenazas.  </li>
</ul>

<strong>Auditoría avanzada</strong> (solo compatible con E5)

Proporcionamos instrucciones remotas para: 
<ul>
<li> Habilitar la auditoría avanzada.</li>
<li> Realizar una interfaz de usuario de registro de auditoría de búsqueda y comandos básicos de PowerShell de auditoría.</li>
</ul>

<strong> Administrador de cumplimiento</strong>

Proporcionamos instrucciones remotas para:  

<ul> <li>Revisión de tipos de roles.  </li>
<li> Agregar y configurar evaluaciones.</li>
<li> Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</li>
<li> Revisión de controles integrados de asignación y evaluación de controles.</li>
<li> Generar un informe dentro de una evaluación.</li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong> 
<ul>
<li> Scripting o codificación personalizados.</li>
<li> API de exhibición de documentos electrónicos. </li>
<li> Conectores de datos. </li>
<li> Límites de cumplimiento y filtros de seguridad.</li>
<li> Investigaciones de datos.</li>
<li> Solicitudes del interesado.</li>
<li> Diseño, arquitecto y revisión de documentos de terceros.</li>
<li> Cumplimiento de las normativas y requisitos regionales y del sector.</li>
<li> Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</li>
</ul>
</td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="products-and-capabilities.md#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>
<tr class="odd">
<td><strong>Administración de amenazas de Insider</strong></td>

<td>  Proporcionamos instrucciones remotas para:
<ul>
<li> Crear directivas y revisar la configuración.</li>
<li> Acceso a informes y alertas.</li>
<li> Creación de casos.</li>
<li> Creación de plantillas de aviso.</li>
<li> Instrucciones para crear el conector de recursos humanos (HR).</li>
</ul>

<strong> Cumplimiento de comunicaciones </strong> 

Proporcionamos instrucciones remotas para: 
<ul>
<li> Crear directivas y revisar la configuración.</li>
<li> Acceso a informes y alertas.</li>
<li> Creación de plantillas de aviso.</li>
</ul>

<strong> Administrador de cumplimiento</strong>

Proporcionamos instrucciones remotas para:  

<ul> <li>Revisión de tipos de roles.  </li>
<li> Agregar y configurar evaluaciones.</li>
<li> Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</li>
<li> Revisión de controles integrados de asignación y evaluación de controles.</li>
<li> Generar un informe dentro de una evaluación.</li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong> 
<ul>
<li> Creación y administración de flujos de Power Automate.</li>
<li> Conectores de datos (más allá del conector de RECURSOS HUMANOS). </li>
<li> Configuraciones de expresiones regulares personalizadas (RegEx).</li>
<li> Diseño, arquitecto y revisión de documentos de terceros.</li>
<li> Barreras de información.</li>
<li> Administración de acceso con privilegios.</li>
<li> Cumplimiento de las normativas y requisitos regionales y del sector.</li>
<li> Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</li>
</ul></td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="products-and-capabilities.md#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>


</tbody>
</table>












</tbody>
</table>


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>Servicio</strong></TD>
<TD width 50%><strong>Detalles de instrucciones de FastTrack</strong></TD>
<TD width 25%><strong>Expectativas del entorno de origen</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>