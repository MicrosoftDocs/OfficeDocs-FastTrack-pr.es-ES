---
title: Productos y capacidades
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias para poder empezar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que ajuste el entorno de origen a los requisitos mínimos para una incorporación correcta.
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016692"
---
# <a name="products-and-capabilities"></a>Productos y capacidades

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Servicios y escenarios admitidos por FastTrack

En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias para poder empezar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que ajuste el entorno de origen a los requisitos mínimos para una incorporación correcta.

FastTrack proporciona instrucciones para ayudarle primero con las funcionalidades principales (comunes para todos los Microsoft Online Services) y, a continuación, con la incorporación de cada servicio elegible:

  - [General](#general)
  - [Seguridad y cumplimiento](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [App Assure](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Para obtener información sobre las expectativas de entorno de origen para Office 365 Administración Pública, vea [Expectativas de entorno de origen para Office 365 Administración Pública](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations). 
 
## <a name="general"></a>General

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de las instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Incorporación principal</strong></td>
<td>  Proporcionamos instrucciones remotas sobre la incorporación principal, que implica el aprovisionamiento de servicios, el espacio empresarial y la integración de identidades. También incluye pasos para proporcionar una base para la incorporación de servicios como Exchange Online, SharePoint Online y Microsoft Teams, incluida una discusión sobre seguridad, conectividad de red <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">y cumplimiento.</a>  
  La incorporación de uno o más servicios elegibles puede empezar al finalizar la incorporación principal.
</li>
</ul>  

<strong> Integración de identidades </strong>

Proporcionamos instrucciones remotas para:
<ul>
<li>Preparar identidades locales de Active Directory para la sincronización con Azure Active Directory (Azure AD), incluida la instalación y configuración de Azure AD Connect (bosque único o de varios bosques) y licencias (incluidas las licencias basadas en grupos).</li>
<li>Crear identidades en la nube, incluida la importación masiva y las licencias, incluido el uso de licencias basadas en grupos.</li>
<li>Elegir y habilitar el método de autenticación correcto para el recorrido en la nube, la sincronización de hash de contraseña, la autenticación de paso a través o los Servicios de federación de Active Directory (AD FS).</li>
<li>Habilitar AD FS para clientes con un único bosque de Active Directory e identidades sincronizadas con la herramienta Azure AD Connect. Esto requiere Windows Server 2012 R2 Servicios de federación de Active Directory 2.0 o posterior.</li>
<li>Migrar la autenticación de AD FS a Azure AD mediante la sincronización de hash de contraseña o la autenticación de paso a través.</li>
<li>Migración de aplicaciones integradas previamente (como aplicaciones de software como servicio (SaaS) de la galería de Azure AD) desde AD FS a Azure AD para el inicio de sesión único (SSO).</li>
<li>Habilitar las integraciones de aplicaciones SaaS con SSO desde la galería de Azure AD.</li>
<li>Habilitar el aprovisionamiento automático de usuarios para aplicaciones SaaS integradas previamente como se muestra en la lista <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">de tutoriales</a> de integración de aplicaciones (limitado a aplicaciones SaaS de la galería de Azure AD y aprovisionamiento saliente únicamente).  </li>
</td>

<td>  <strong>Habilitación de red </strong>  
  <br>Como parte de las ventajas de FastTrack, le aconsejamos los procedimientos recomendados para conectarse a los servicios en la nube a fin de garantizar los niveles más altos de rendimiento de Microsoft 365.  
  
<strong>Bosques de Active Directory</strong> Tienen el nivel de bosque funcional establecido en Windows Server 2003 en adelante, con la siguiente configuración de bosque:
<ul>
<li>  Un solo bosque de Active Directory.  </li>
<li>  Un solo bosque de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).  </li>
<li>  Varios bosques de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).  </li>
<li>  Varios bosques de cuentas de Active Directory con uno de los bosques que es un bosque de cuentas de Active Directory centralizado que incluye Exchange o Lync 2010, Lync 2013 o Skype Empresarial.  </li>
<li>  Varios bosques de cuentas de Active Directory, cada uno con su propia organización de Exchange.  </li>
<li>  Tareas necesarias para la configuración de inquilinos y la integración con Azure Active Directory, si es necesario.   </li>
</ul>
  <strong>Importante</strong>  <ul>
<li>  Para escenarios de Active Directory con varios bosques, si se implementa Lync 2010, Lync 2013 o Skype Empresarial, debe implementarse en el mismo bosque de Active Directory que Exchange.  </li>
<li>  Al implementar varios bosques de Active Directory con varias organizaciones de Exchange en una configuración multi hybrid de Exchange, no se admiten espacios de nombres de nombre principal de usuario (UPN) compartidos entre bosques de origen. Los espacios de nombres SMTP principales entre las organizaciones de Exchange también deben estar separados. Para más información, consulte <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implementaciones híbridas con varios bosques de Active Directory</a>.  </li>
<li>  Para todas las configuraciones de varios bosques, la implementación de servicios de federación de Active Directory (AD FS) está fuera del ámbito. Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Aplicaciones de Microsoft 365</strong></td>
<td>  Proporcionamos instrucciones de implementación remota para:
<ul>
<li>  Solucionar los problemas de implementación.  </li>
<li>  Asignar licencias de usuario final y basadas en dispositivos mediante el Centro de administración de Microsoft 365 y Windows PowerShell.  </li>
<li>  Instalar Aplicaciones de Microsoft 365 desde el Portal de Office 365 con la opción Hacer clic y ejecutar.  </li>
<li>  Instalar aplicaciones de Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile y PowerPoint Mobile) en los dispositivos iOS o Android.  </li>
<li>  Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.  </li>
<li>  Selección y configuración de una instalación local o en la nube.  </li>
<li>  Creación de la configuración XML de la herramienta de implementación de Office con la herramienta de personalización de Office o XML nativo para configurar el paquete de implementación.  </li>
<li>  Implementar mediante Microsoft Endpoint Configuration Manager, incluida la ayuda con la creación del empaquetado de Microsoft Endpoint Configuration Manager.  
  Además, si tiene una macro o un complemento que ha funcionado con versiones anteriores de Office y experimenta problemas de compatibilidad, proporcionamos instrucciones para corregir el problema de compatibilidad sin coste adicional a través del programa App Assure. Consulta la <strong>parte de App Assure</strong> de Windows <a href="#windows-10">10</a> para obtener más información. </li>
</ul></td>
<td><ul>
<li>  El software cliente en línea debe estar en un nivel mínimo como se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office.</a>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Estado de la red</strong></td>
<td>  Proporcionamos instrucciones remotas para obtener e interpretar datos clave de conectividad de red de su entorno que muestran cómo se alinean los sitios de su organización con los <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principios</a>de conectividad de red de Microsoft. Esto resalta la puntuación de red que afecta directamente a la velocidad de migración, la experiencia del usuario, el rendimiento del servicio y la confiabilidad.  
  También le guiaremos a través de los pasos de corrección resaltados por estos datos para ayudarle a mejorar la puntuación de red.  </td>
<td><ul>
<li>  Acceso al Centro de administración de Microsoft 365.  </li>
<li>  Se requieren versiones actualizadas de las aplicaciones de Microsoft 365.  </li>
<li>  Servicios de ubicación habilitados según las recomendaciones de rendimiento de red en el Centro de administración de <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (versión preliminar).</a>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>Seguridad y cumplimiento

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de las instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></td>
<td>  Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.  

 <br/>

<strong>Infraestructura de base segura</strong>  </ul>
<ul>
<li>  Configurar y habilitar la autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el autoservicio de restablecimiento de contraseña (SSPR).  </li>
<li>  Para los clientes que no son de Azure AD Premium, se proporcionan instrucciones para proteger las identidades con valores predeterminados de seguridad.  </li>
<li>  Para los clientes de Azure AD Premium, se proporcionan instrucciones para proteger las identidades con acceso condicional.  </li>
<li>  Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.  </li>
<li>  Proteger el acceso remoto a las aplicaciones web locales con el Proxy de aplicación de Azure AD.  </li>
<li>  Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.  </li>
<li>  Habilitar una pantalla de inicio de sesión personalizada, incluido el logotipo, el texto y las imágenes con la personalización de marca.  </li>
<li>  Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.  </li>
<li>  Administrar el acceso de los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.  </li>
<li>  Configurar la unión híbrida a Azure AD.  </li>
<li>  Configurar la unión a Azure AD.  </li>
</ul>
  
<strong>Supervisión e informes</strong>  
<ul>
<li>  
  Habilitar la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Gobierno</strong>  
<ul>
<li>  
  Administrar el ciclo de vida de acceso e identidad de Azure AD a escala con la administración de derechos de Azure AD.
  </li>
<li>  
  Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.  
  </li>
<li>  
  Revisar los Términos de uso de Azure AD.  
  </li>
<li>  
  Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatización y eficiencia </strong>  
<ul>
<li>  
  Habilitar SSPR de Azure AD.  
  </li>
<li>  Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos de Office 365 con la administración de grupos de autoservicio de Azure AD.  </li>
<li>  Administrar el acceso delegado a las aplicaciones empresariales con la administración de grupos delegada de Azure AD.  </li>
<li>  Habilitar grupos dinámicos de Azure AD.  </li>
<li>  Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.  </li>
</ul></td>
<td>Active Directory local y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Activar y configurar el espacio empresarial.  </li>
<li>  Crear y configurar etiquetas y directivas.  </li>
<li>  Aplicar la protección de la información a documentos.  </li>
<li>  Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.  </li>
<li>  Descubrir y etiquetar archivos en reposo con el escáner de Azure Information Protection.  </li>
<li>  Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.  </li>
</ul>
También proporcionamos instrucciones si desea aplicar protección con Microsoft Azure Rights Management Services (Azure RMS), cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).  </td>
<td>  Las responsabilidades de requisitos previos del cliente incluyen:
<ul>
<li>  Una lista de ubicaciones de recurso compartido de archivos que se examinarán.  </li>
<li>  Taxonomía de clasificación aprobada. </li>
<li> Descripción de cualquier restricción normativa o requisitos relacionados con la administración de claves.  </li>
<li>  Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD. </li>
<li>  Etiquetas configuradas para clasificación y protección. </li>
<li> Todos los requisitos previos para el escáner de Azure Information Protection están en su lugar. Para obtener más información, vea <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Requisitos previos para</a>instalar e implementar el escáner de etiquetado unificado de Azure Information Protection. </li>
<li>  Asegúrese de que los dispositivos de usuario ejecutan un sistema operativo compatible y tienen instalados los requisitos previos necesarios. Vea lo siguiente para obtener más información.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetado unificado de Azure Information Protection para los usuarios</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </li>
</ul>
<li> Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para la compatibilidad híbrida.  </li>
<li> El programa de instalación y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado únicamente) o Hold Your Own Key (HYOK) (solo cliente clásico) debe requerir una de estas opciones para la implementación.  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender es un conjunto unificado de defensa empresarial anterior y posterior a la infracción que coordina de forma nativa la detección, prevención, investigación y respuesta entre puntos de conexión, identidades, correo electrónico y aplicaciones para proporcionar protección integrada contra ataques sofisticados. Proporcionamos instrucciones remotas para: </p> 
<ul>
<li>  Proporcionar información general sobre el Centro de seguridad de Microsoft 365.  </li>
<li>  Revisar incidentes entre productos, incluyendo centrarse en lo que es fundamental al garantizar el ámbito de ataque completo, los activos afectados y las acciones de corrección automatizadas que se agrupan.  </li>
<li>  Demostrar cómo Microsoft 365 Defender puede organizar la investigación de activos, usuarios, dispositivos y buzones que podrían haber sido comprometidos a través de la recuperación automática. </li>
<li>  Explicar y proporcionar ejemplos de cómo los clientes pueden buscar de forma proactiva intentos de intrusiones y actividad de infracción que afecten al correo electrónico, los datos, los dispositivos y las cuentas en varios conjuntos de datos.   </li>
<li> Mostrar a los clientes cómo pueden revisar y mejorar su posición de seguridad de forma holística con puntuación de seguridad de Microsoft.</li>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>
<li> Administración de proyectos de las actividades de corrección de los clientes. </li>
<li> Administración continua, respuesta a amenazas y corrección. </li>
<li> Guía de implementación o educación sobre:
<ul>
<li> Cómo corregir o interpretar los distintos tipos de alertas y actividades supervisadas. </li>
<li> Cómo investigar un usuario, equipo, ruta de movimiento lateral o entidad. </li>
<li> Búsqueda de amenazas personalizada.  </li>
</ul>
</li>
<li> Información de seguridad y administración de eventos (SIEM) o integración de API.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una amplia visibilidad, control sobre los viajes de datos y análisis sofisticados para identificar y combatir las ciberamenazas en todos los servicios en la nube de Microsoft y de terceros. Proporcionamos instrucciones remotas para:
<ul>
<li>  Configurar el portal, incluidos:  </li>
<ul>
<li> Importar grupos de usuarios.</li>
<li> Administrar la configuración y el acceso de administrador.  </li>
<li> Ámbito de la implementación para seleccionar determinados grupos de usuarios que se supervisarán o excluirán de la supervisión.</li>
<li> Establecer intervalos IP y etiquetas.</li>
<li> Personalización de la experiencia del usuario final con el logotipo y la mensajería personalizada.</li>
</ul>
<li> Configurar la detección de nube para proporcionar una instantánea de IT mediante:</li>
<ul>
<li> Microsoft Defender para puntos de conexión.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Conexión <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">de aplicaciones destacados</a> mediante conectores de aplicaciones.</li>
<li> Configurar el control de aplicaciones de acceso condicional en los portales de Acceso condicional y Seguridad de aplicaciones en la nube para aplicar controles de sesión en tiempo real.</li>
<li> Implementación de los paneles Cloud App Security y Cloud Discovery.</li>
<li> Personalización de puntuaciones de riesgo de aplicaciones en función de las prioridades de su organización.</li>
<li> Crear etiquetas y categorías de la aplicación.</li>
<li> Sancionar y no autorizar aplicaciones.</li>
<li> Uso de los registros de actividad y archivo.</li>
<li> Administrar aplicaciones de OAuth.</li>
<li> Descripción de la correlación de incidentes en el portal de Microsoft 365 Defender.</li>
<li> Proporcionar asistencia de configuración con los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 casos</a> de uso principales para LAS CASB (incluida la creación o actualización de hasta seis (6) directivas), excepto: </li>
<ul>
<li> Auditar la configuración de los entornos de Internet como servicio (IaaS) (#18).</li>
<li> Supervisar las actividades de los usuarios para protegerse contra amenazas en los entornos de IaaS (#19).</li>
</ul>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>
<li> Administración de proyectos de las actividades de corrección de los clientes.</li>
<li> Administración continua, respuesta a amenazas y corrección. </li>
<li> Configurar la infraestructura, la instalación o la implementación de cargas automáticas de registros para informes continuos mediante Docker o un recopilador de registros. Para obtener más información, vea los 20 primeros casos de uso <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">de las CASB.</a></li>
<li> Creación de un informe de instantáneas de detección de nube.</li>
<li> Bloquear el uso de la aplicación mediante scripts de bloqueo.</li>
<li> Conectar aplicaciones personalizadas.</li>
<li> Integración con proveedores de identidades de terceros (ISP) y proveedores de prevención de pérdida de datos (DLP).</li>
<li> Aprendizaje o instrucciones sobre la búsqueda avanzada.</li>
<li> Investigación y corrección automatizadas, incluidas las guías de juegos de Microsoft Power Automate.</li>
<li> Administración de eventos e información de seguridad (SIEM) o integración de API (incluido Azure Sentinel).</li>
<li> Implementar la detección de aplicaciones en la nube como una prueba de concepto.</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></td>
<td>  La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Implementar las tecnologías para proteger los puntos de conexión.  </li>
<li>  Configurar perfiles de restricción de dispositivos y protección de puntos de conexión.  </li>
<li>  Evaluar la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios av de Windows Defender u otro software de seguridad de puntos de conexión.  </li>
<li>  Evaluar el estado de los servicios antivirus de Windows u otro software de seguridad de puntos de conexión.  </li>
<li>  Evaluar servidores proxy y firewalls que restringen el tráfico de red.  </li>
<li>  Habilitar el servicio ATP de Microsoft Defender explicando cómo implementar un perfil de agente de ATP con un punto de conexión incorporado.  </li>
<li>  Instrucciones de implementación, asistencia de configuración y formación sobre:
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
<li>  Revisar simulaciones y tutoriales (como escenarios de prácticas, malware falso e investigaciones automatizadas).  </li>
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
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la última versión de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior). 

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
<li>  Incorporación y configuración del servidor:
<ul>
<li>  
  Configurar un servidor proxy para las comunicaciones sin conexión.  
  </li>
<li>  
  Configurar paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.  
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
<li>  Configuración o aprendizaje que revisa la API o las conexiones de administración de eventos e información de seguridad (SIEM).  </li>
<li>  Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).  </li>
<li>  Aprendizaje o instrucciones sobre la búsqueda avanzada.  </li>
<li>  Formación u orientación sobre el uso o la creación de consultas de Kusto.</li>
</li>
</ul>
Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender para identidad </strong></td>
<td>  Microsoft Defender for Identity es una solución de seguridad basada en la nube que aprovecha las señales locales de Active Directory para identificar, detectar e investigar las amenazas avanzadas, las identidades vulnerables y las acciones internas malintencionadas dirigidas a su organización. Proporcionamos instrucciones remotas para:
<ul>
<li>   Crear la instancia de Defender for Identity. </li>
<li>   Conectar Defender for Identity a Active Directory. </li>
<li>   Evaluar la preparación del entorno para implementar el sensor Defender for Identity en los controladores de dominio, incluidos:</li>   
<ul> 
<li>  Ejecución de la herramienta de tamaño para la planeación de la capacidad de los recursos. </li>
<li>  Ejecutar la herramienta de auditoría para evaluar la compatibilidad de los controladores de dominio con el sensor. </li>
</ul>
<li>  Implementar el sensor para capturar y analizar el tráfico de red y los eventos de Windows directamente desde los controladores de dominio, incluidos: </li>
<ul> 
<li>  Descargar el paquete del sensor. </li>
<li>  Configurar el sensor. </li>
<li>  Instalar el sensor en el controlador de dominio de forma silenciosa. </li>
<li>  Implementar el sensor en el entorno de varios bosques. </li>
</ul>
<li>  Integración de Defender for Identity con Microsoft Cloud App Security (no se requiere licencia de Cloud App Security). </li>
<li>  Proporcionar instrucciones de implementación, asistencia de configuración y formación sobre: </li>
<ul>
<li> Ajuste del entorno para reducir el "ruido".  </li>
<li>  Descripción del informe de evaluación de la posición de seguridad de identidad. </li>
<li>  Descripción de la puntuación de prioridad de investigación de usuario y el informe de clasificación de la investigación de usuarios. </li>
<li> Descripción del informe de usuario inactivo.  </li>
<li> Proporcionar opciones de corrección en una cuenta comprometida.  </li>
</ul>
<li>  Facilitar la migración de Advanced Threat Analytics (ATA) a Defender for Identity. </li>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>

<li> Administración de proyectos de las actividades de corrección de los clientes. </li>
<li> Administración continua, respuesta a amenazas y corrección.  </li>
<li> Implementar el sensor Defender for Identity, incluidos: </li>
<ul>
<li> Planeación manual de la capacidad. </li>
<li> Implementar el sensor en una capacidad independiente. </li>
<li> Implementar el sensor mediante un adaptador de formación de equipos de tarjeta de interfaz de red (NIC). </li>
<li> Implementar el sensor a través de una herramienta de terceros. </li>
<li> Conectarse al servicio en la nube de Defender for Identity a través de una conexión de proxy web. </li>
</ul>
<li> Creación y administración detokens detokens. </li>
<li> Guía de implementación o educación sobre: </li>
<ul>
<li> Corregir o interpretar varios tipos de alertas y actividades supervisadas.  </li>
<li> Investigar un usuario, equipo, ruta de movimiento lateral o entidad. </li>
<li> Amenaza o búsqueda avanzada. </li>
<li> Respuesta a incidentes. </li>
</ul>
<li> Proporcionar un tutorial de laboratorio de alertas de seguridad para Defender for Identity. </li>
<li> Proporcionar una notificación cuando Defender para identidad detecta actividades sospechosas mediante el envío de alertas de seguridad a tu servidor de Vmm a través de un sensor designado.  </li>
<li> Configurar Defender para Identity para realizar consultas mediante el protocolo de administrador de cuentas de seguridad remoto (SAMR) para identificar a los administradores locales en equipos específicos. </li>
<li> Configurar soluciones VPN para agregar información de la conexión VPN a la página de perfil de un usuario.  </li>
<li> Administración de eventos e información de seguridad (SIEM) o integración de API (incluido Azure Sentinel). </li>
<li> Implementar sensores de Defender for Identity como una prueba de concepto.</li>
</ul></td>
<td><ul>
<li>  Active Directory implementado.  </li>
<li>  Los controladores de dominio en los que quieres instalar los sensores de Defender for Identity tienen conectividad a Internet con el servicio en la nube de Defender for Identity.  </li>
<ul>
<li> El firewall y el proxy deben estar abiertos para comunicarse con el servicio en la nube de Defender for Identity (*.atp.azure.com puerto 443 debe estar abierto).</li>
</ul>
<li> Controladores de dominio que se ejecutan en una de las siguientes opciones:</li>
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
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
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
<li>  Crear directivas DLP de punto de conexión para dispositivos Con Windows 10.  </li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>Clave de cliente.</li>
<li>Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</li>
<li>Creación o modificación de diccionarios de palabras clave.</li>
<li>Scripting y codificación personalizados.</li>
</ul>
<strong>Nota:</strong> Para obtener más información, <strong>vea Azure Information Protection</strong> en Enterprise Mobility + <a href="#enterprise-mobility--security">Security.</a>
<ul>

</td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como el proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos. Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles. Los pasos pueden incluir:
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar identidades para que Intune las utilice mediante el uso de active directory local o identidades de nube (Azure AD).  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Configurar la autoridad MDM, en función de tus necesidades de administración, incluidos:
<ul>
<li>  Establecer Intune como entidad MDM cuando Intune es la única solución MDM.  </li>
</ul></li>
<li>  Proporcionar instrucciones de MDM para:
<ul>
<li>  Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.  </li>
<li>  Configurar servicios y directivas de administración de MDM como:
<ul>
<li>  Implementación de aplicaciones para cada plataforma compatible a través de vínculos web o vínculos profundos.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tienes una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en tu organización.  </li>
<li>  Conectarse al almacén de datos de Intune.  </li>
<li>  Integrar Intune con:
<ul>
<li>  Visor de equipo para asistencia remota (se requiere una suscripción al Visor de equipo).  </li>
<li>  Soluciones de asociados de Mobile Threat Defense (MTD) (se requiere una suscripción mtd).  </li>
<li>  Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción de solución de administración de gastos de telecomunicaciones).  </li>

</ul></li>
<li>  Inscribir dispositivos de cada plataforma compatible en Intune.  </li>
</ul></li>
</ul></li>
<li>  Proporcionar instrucciones de protección de aplicaciones sobre:
<ul>
<li>  Configurar directivas de protección de aplicaciones para cada plataforma compatible.  </li>
<li>  Configuración de directivas de acceso condicional para aplicaciones administradas.  </li>
<li>  Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.  </li>
<li>  Uso de informes de uso de aplicaciones administradas.  </li>
</ul></li>
<li>  Proporcionar instrucciones de migración de la administración de equipos heredados a MDM de Intune.  </li>
</ul>
 
</li>
</ul>
  
<strong>Conexión a la nube</strong>  

  Le guiaremos a través de prepararse para adjuntar entornos de Configuration Manager existentes a la nube con Intune. Los pasos detallados dependen del entorno de origen. Los pasos pueden incluir:  
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Proporcionar instrucciones para configurar la unión híbrida a Azure AD.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.  </li>
<li>  Configurar cargas de trabajo compatibles que quiera cambiar a Intune.  </li>
<li>  Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.  </li>
</ul> 

<strong>Implementar Outlook Mobile para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook Mobile para iOS y Android de forma segura en su organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.  
  Los pasos para implementar Outlook mobile para iOS y Android con Intune de forma segura dependen del entorno de origen. Puede incluir:
<ul>
<li>  Descargar las aplicaciones outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal a través de La App Store de Apple o Google Play Store.  </li>
<li>  Proporcionar instrucciones sobre la configuración:
<ul>
<li>  La implementación de aplicaciones de Outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal con Intune.  </li>
<li>  Directivas de protección de aplicaciones.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Directivas de configuración de aplicaciones.  </li>
</ul></li>
</ul>  
  </td>
<td>  Los administradores de TI deben tener infraestructuras existentes de entidad de certificación, red inalámbrica e VPN que ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.  
  <strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar las autoridades de certificados, las redes inalámbricas, las infraestructuras VPN o los certificados de inserción de MDM de Apple para Intune.  
 
  <strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube. Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.

  <strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong> 
 
  <strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con ATP de Microsoft Defender y crear directivas de cumplimiento de dispositivos en función de su evaluación del nivel de riesgo de Windows 10. No proporcionamos asistencia sobre la compra, la concesión de licencias o la activación. Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.  
  
<strong>Windows Autopilot</strong> 
 
  Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.  
  
</td>
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
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de las instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Para Exchange Online, le guiaremos a través del proceso para preparar a su organización para usar el correo electrónico. Los pasos exactos dependen del entorno de origen y de los planes de migración de correo electrónico.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Configuración de las características de Exchange Online Protection (EOP) para todos los dominios habilitados para correo que se han validado en Office 365.  </li>
<li>  Apuntar los registros de intercambio de correo (MX) a Office 365.  </li>
<li>  Configurar la característica atp de Office 365 si forma parte de su servicio de suscripción. Para obtener más información, vea la parte protección contra amenazas avanzada de <strong>Office 365</strong> de esta tabla.  </li>
<li>  Configuración de la característica de prevención de pérdida de datos (DLP) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</li>
<li>  Configuración del cifrado de mensajes de Office 365 (OME) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</li>
</ul>
  <strong>Nota:</strong> El servicio de replicación de buzones (MRS) intenta migrar correos electrónicos de Information Rights Managed (IRM) desde su buzón local al buzón de Exchange Online correspondiente. La capacidad de leer el contenido protegido posterior a la migración dependerá de la asignación de clientes y la copia de las plantillas de Active Directory Rights Management Services (AD RMS) en el servicio Azure Rights Management (Azure RMS).  
<ul>
<li>  Configurar puertos del firewall.  </li>
<li>  Configurar DNS, incluidos la detección automática, el marco de directivas de remitente (SPF), el correo identificado de DomainKeys (DKIM), la autenticación de mensajes basada en dominio, la creación de informes y la conformidad (DMARC) y los registros MX (según sea necesario).  </li>
<li>  Configuración del flujo de correo electrónico entre su entorno de mensajería de origen y Exchange Online (si procede).  </li>
<li>  Operación de migración de correo desde el entorno de mensajería de origen a Office 365.  </li>
<li>  Configuración de clientes de buzón (Outlook para Windows, Outlook en la web y Outlook para iOS y Android).  </li>
</ul>
  <strong>Migración de datos</strong>  <br>
Para obtener información sobre cómo usar las ventajas de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">Migración de datos.</a>   
<td>  El entorno de origen debe tener uno de los siguientes niveles mínimos:
<ul>
<li>  Una o varias organizaciones de Exchange a partir de Exchange Server 2003.  </li>
<li>  Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).  </li>
<li>  Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).  </li>
<li>  Para obtener información sobre las capacidades multige geográficas, consulte <a href="https://go.microsoft.com/fwlink/?linkid=872776">Capacidades multigeómicas en Exchange Online.</a>  </li>
</ul>
El software cliente en línea como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, el cliente de sincronización de OneDrive para la Empresa, Power BI Desktop y Skype Empresarial deben estar en un nivel mínimo como se define en los requisitos del sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a>  </td>
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
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
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
<li>  Crear directivas DLP de punto de conexión para dispositivos Con Windows 10.  </li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>Clave de cliente.</li>
<li>Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</li>
<li>Creación o modificación de diccionarios de palabras clave.</li>
<li>Scripting y codificación personalizados.</li>
</ul>
<strong>Nota:</strong> Para obtener más información, <strong>vea Azure Information Protection</strong> en Enterprise Mobility + <a href="#enterprise-mobility--security">Security.</a>
<ul>

</td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Confirmar los requisitos mínimos en Exchange Online, SharePoint Online, Grupos de Office 365 y Azure AD para admitir Teams.  </li>
<li>  Configuración de puertos del firewall.  </li>
<li>  Configuración de DNS.  </li>
<li>  Confirmar que se ha habilitado Teams en su espacio empresarial de Office 365.  </li>
<li>  Habilitar o deshabilitar licencias de usuario.  </li>
<li>  Evaluación de red para Teams:
<ul>
<li>  Comprobaciones de puertos y puntos de conexión.  </li>
<li>  Comprobaciones de calidad de la conexión.  </li>
<li>  Estimaciones de ancho de banda.  </li>
</ul>
<ul>
<li>  Configuración de la directiva de aplicación de Teams (aplicación web de Teams, aplicación de escritorio de Teams y teams para aplicaciones de iOS y Android).  </li>
</ul>
Si procede, también proporcionamos instrucciones para:
<ul>
<li>  Dispositivos de sala de Microsoft Teams:  </li>
<ul>
<li>  Creación de cuentas en línea necesarias para los dispositivos de telefonía y salas de conferencias compatibles que aparecen en el <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos de Teams</a>.  </li>
<li>  Asistencia remota con la configuración del lado del servicio de dispositivos de salas de Microsoft Teams certificados.  </li>
<li>  Habilitar audioconferencia:  </li>
<li>  Parámetros predeterminados de la configuración de la organización para puente de conferencia.  </li>
<li>  Asignación de un puente de conferencia a usuarios con licencia.  </li>
</ul>
<li>  Sistema telefónico:
<ul>
<li>  Configuración de la organización para los parámetros predeterminados de voz en la nube.  </li>
<li>  Guía de planes de llamadas (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponibles):</a>
<ul>
<li>  Asignación de números a usuarios con licencia.  </li>
<li>  Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.  </li>
<li>  Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.  </li>
</ul></li>
<li>  Guía de enrutamiento directo:
<ul>
<li>  Guía de configuración de la organización para el diseño de enrutamiento directo de escenarios hospedados por asociados o escenarios implementados por el cliente para un máximo de 10 sitios.  </li>
<li> Revisión de configuración del controlador de borde de sesión (SBC). </li>

<li> Asistencia remota con la configuración del plan de marcado. </li>

<li> Configuración de ruta de voz.</li>

<li> Desvío de medios y optimización de medios locales. </li>

</ul></li>
</ul></li>
<li>  Habilitar eventos en directo en Teams  </li>
<li>  Configuración e integración de la organización en Microsoft Stream.  </li>
<li>  Guía para la transición de Skype Empresarial a Teams.  </li>
</ul></td>
<td><ul>
<li>  Identidades habilitadas en Azure AD para Office 365.  </li>
<li>  Usuarios habilitados para SharePoint Online.  </li>
<li>  Los buzones de Exchange están presentes (en línea y local en una configuración híbrida de Exchange).  </li>
<li>  Habilitado para Grupos de Office 365.  </li>
</ul>
  <strong>Nota:</strong> Si los usuarios no están asignados ni habilitados con licencias de SharePoint Online, no tendrán almacenamiento de OneDrive para la Empresa en Office 365. El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin el almacenamiento de OneDrive para la Empresa en Office 365. Teams no admite SharePoint local.  <br>
  <strong>Nota:</strong> El estado ideal es que todos los usuarios tengan sus buzones de correo en Exchange Online. Los usuarios con buzones de correo locales deben tener sus identidades sincronizadas con el directorio de Office 365 a través de Azure AD Connect. Para estos clientes híbridos de Exchange, si el buzón del usuario es local, el usuario no puede agregar ni configurar conectores.  
  Los instaladores para los clientes de escritorio de Mac y Windows en Microsoft Teams se pueden descargar de <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.  </td>
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
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>
<tr class="even">
<td><strong>Outlook para iOS y Android</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Descargar Outlook para iOS y Android desde la App Store de Apple y Google Play.  </li>
<li>  Configurar cuentas y acceder al buzón de Exchange Online.  </li>
<li>  Protección de Outlook mobile (vea <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Protección de Outlook para iOS y Android en Exchange Online</a> para obtener más información).  </li>
</ul></td>
<td><ul>
<li>  Identidades habilitadas en Azure AD para Office 365.  </li>
<li>  Exchange Online configurado y licencias asignadas.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Asignación de licencias de Power BI.  </li>
<li>  Implementación de la aplicación Power BI Desktop.  </li>
</ul></td>
<td>El software cliente en línea, como Power BI Desktop, debe estar en un nivel mínimo como se define en los requisitos del sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 y Office.</a></td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Comprobación de la funcionalidad básica de SharePoint que se basa en Project Online.  </li>
<li>  Adición del servicio de Project Online al espacio empresarial (incluida la adición de las suscripciones a los usuarios).  </li>
<li>  Configuración del grupo de recursos de empresa (ERP).  </li>
<li>  Creación del primer proyecto.  </li>
</ul></td>
<td>El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 y Office.</a></td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional y Premium</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Solucionar los problemas de implementación.  </li>
<li>  Asignar licencias de usuario final mediante el Centro de administración de Microsoft 365 y Windows PowerShell.  </li>
<li>  Instalar Cliente de escritorio de Project Online desde el Portal de Office 365 con la opción Hacer clic y ejecutar.  </li>
<li>  Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.  </li>
<li>  Configurar un servidor de distribución in situ único para Cliente de escritorio de Project Online, incluida la ayuda para crear un archivo configuration.xml para usarlo con la Herramienta de implementación de Office 365.  </li>
<li>  Conectar Cliente de escritorio de Project Online a Project Online Professional o Project Online Premium.  </li>
</ul></td>
<td>El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 y Office.</a></td>
</tr>
<tr class="even">
<td><strong>SharePoint Online y OneDrive para la Empresa</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Configuración de DNS.  </li>
<li>  Configuración de puertos del firewall.  </li>
<li>  Aprovisionamiento de usuarios y licencias.  </li>
<li>Habilitar la creación de sitios para el administrador de SharePoint Online.</li>
<li>Planificar las colecciones de sitios.</li>
<li>Proteger el contenido y administrar los permisos.</li>
<li>Configurar las características de SharePoint Online.</li>
<li>  Configuración de las características de Entorno híbrido de SharePoint, como la búsqueda híbrida, los sitios híbridos, la taxonomía híbrida, los tipos de contenido, la creación híbrida de sitios sin intervención del administrador (solo SharePoint Server 2013), el iniciador de aplicaciones extendido, OneDrive para la Empresa híbrido y los sitios de extranet.  </li>
<li>  El enfoque de migración.  </li>
</ul>
Se proporcionan instrucciones adicionales para OneDrive para la Empresa en función de su versión de SharePoint, como:
<ul>
<li>  Identificar las opciones de integración y revisar el ancho de banda y la infraestructura de red local y en línea.  </li>
<li>  Instalar SharePoint Online 2013 SP1 (si corresponde), planear e implementar requisitos de sincronización e identidad, e identificar el cliente de sincronización de OneDrive para la Empresa.  </li>
<li>  Planeación e implementación de una única implementación para todos los usuarios (o una implementación por fases).  </li>
<li>  Asignar licencias, redirigir Mis sitios y bibliotecas de documentos personales a Office 365 (aplicable a SharePoint Online 2013), configurar audiencias para controlar el acceso a OneDrive (aplicable a SharePoint Online 2013).  </li>
<li>Redirigir o mover carpetas conocidas a OneDrive.</li>
<li>  Implementación de la sincronización de cliente de OneDrive para la Empresa.  </li>
</ul>
  <strong>Migración de datos</strong>  <br>
Para obtener información sobre cómo usar las ventajas de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">Migración de datos.</a>
</ul></td>
<td><br><strong>Para entornos híbridos de SharePoint:</strong>  
<ul>
<li>  La configuración híbrida de SharePoint incluye la configuración de búsqueda híbrida, sitios, taxonomía, tipos de contenido, OneDrive para la Empresa, un iniciador de aplicaciones extendido, sitios de extranet y creación de sitios sin administrador conectados desde local a un entorno de SharePoint Online de destino único.  </li>
</ul>
  <strong>Nota:</strong> La creación de sitios sin administrador no está en el ámbito de los servidores locales que ejecutan SharePoint 2013.  
<ul>
<li>  Para habilitar SharePoint híbrido, debe tener uno de los siguientes entornos locales de SharePoint Server: 2013, 2016 o 2019.  </li>
</ul>
  <strong>Nota:</strong> La actualización de entornos de SharePoint locales a SharePoint Server no está en el ámbito. Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda. Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">Niveles mínimos de actualización pública para características híbridas de SharePoint.</a><em></em>  <br>
  <strong>Nota:</strong> Para obtener información sobre las capacidades multige geográficas, vea Capacidades multigeómicas en <a href="https://go.microsoft.com/fwlink/?linkid=831056">OneDrive y SharePoint Online en Office 365.</a><em></em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Proporcionamos instrucciones remotas para habilitar el servicio Yammer Enterprise.  
</ul></td>
<td>El software cliente en línea debe estar en un nivel mínimo como se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office.</a></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de las instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></td>
<td>  Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.  

 <br/>

<strong>Infraestructura de base segura</strong>  </ul>
<ul>
<li>  Configurar y habilitar la autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el autoservicio de restablecimiento de contraseña (SSPR).  </li>
<li>  Para los clientes que no son de Azure AD Premium, se proporcionan instrucciones para proteger las identidades con valores predeterminados de seguridad.  </li>
<li>  Para los clientes de Azure AD Premium, se proporcionan instrucciones para proteger las identidades con acceso condicional.  </li>
<li>  Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.  </li>
<li>  Proteger el acceso remoto a las aplicaciones web locales con el Proxy de aplicación de Azure AD.  </li>
<li>  Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.  </li>
<li>  Habilitar una pantalla de inicio de sesión personalizada, incluido el logotipo, el texto y las imágenes con la personalización de marca.  </li>
<li>  Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.  </li>
<li>  Administrar el acceso de los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.  </li>
<li>  Configurar la unión híbrida a Azure AD.  </li>
<li>  Configurar la unión a Azure AD.  </li>
</ul>
  
<strong>Supervisión e informes</strong>  
<ul>
<li>  
  Habilitar la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Gobierno</strong>  
<ul>
<li>  
  Administrar el ciclo de vida de acceso e identidad de Azure AD a escala con la administración de derechos de Azure AD.
  </li>
<li>  
  Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.  
  </li>
<li>  
  Revisar los Términos de uso de Azure AD.  
  </li>
<li>  
  Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatización y eficiencia </strong>  
<ul>
<li>  
  Habilitar SSPR de Azure AD.  
  </li>
<li>  Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos de Office 365 con la administración de grupos de autoservicio de Azure AD.  </li>
<li>  Administrar el acceso delegado a las aplicaciones empresariales con la administración de grupos delegada de Azure AD.  </li>
<li>  Habilitar grupos dinámicos de Azure AD.  </li>
<li>  Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.  </li>
</ul></td>
<td>Active Directory local y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Activar y configurar el espacio empresarial.  </li>
<li>  Crear y configurar etiquetas y directivas.  </li>
<li>  Aplicar la protección de la información a documentos.  </li>
<li>  Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.  </li>
<li>  Descubrir y etiquetar archivos en reposo con el escáner de Azure Information Protection.  </li>
<li>  Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.  </li>
</ul>
También proporcionamos instrucciones si desea aplicar protección con Microsoft Azure Rights Management Services (Azure RMS), cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).  </td>
<td>  Las responsabilidades de requisitos previos del cliente incluyen:
<ul>
<li>  Una lista de ubicaciones de recurso compartido de archivos que se examinarán.  </li>
<li>  Taxonomía de clasificación aprobada. </li>
<li> Descripción de cualquier restricción normativa o requisitos relacionados con la administración de claves.  </li>
<li>  Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD. </li>
<li>  Etiquetas configuradas para clasificación y protección. </li>
<li> Todos los requisitos previos para el escáner de Azure Information Protection están en su lugar. Para obtener más información, vea <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Requisitos previos para</a>instalar e implementar el escáner de etiquetado unificado de Azure Information Protection. </li>
<li>  Asegúrese de que los dispositivos de usuario ejecutan un sistema operativo compatible y tienen instalados los requisitos previos necesarios. Vea lo siguiente para obtener más información.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: Instalar el cliente de etiquetado unificado de Azure Information Protection para los usuarios</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </li>
</ul>
<li> Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para la compatibilidad híbrida.  </li>
<li> El programa de instalación y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado únicamente) o Hold Your Own Key (HYOK) (solo cliente clásico) debe requerir una de estas opciones para la implementación.  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como el proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos. Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles. Los pasos pueden incluir:
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que va a usar Intune aprovechando active directory local o identidades de nube (Azure AD).  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Configurar la autoridad MDM, en función de tus necesidades de administración, incluidos:
<ul>
<li>  Establecer Intune como entidad MDM cuando Intune es la única solución MDM.  </li>
</ul></li>
<li>  Proporcionar instrucciones de MDM para:
<ul>
<li>  Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.  </li>
<li>  Configurar servicios y directivas de administración de MDM como:
<ul>
<li>  Implementación de aplicaciones para cada plataforma compatible a través de vínculos web o vínculos profundos.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tienes una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en tu organización.  </li>
<li>  Conectarse al almacén de datos de Intune.  </li>
<li>  Integrar Intune con:
<ul>
<li>  Visor de equipo para asistencia remota (se requiere una suscripción al Visor de equipo).  </li>
<li>  Soluciones de asociados de Mobile Threat Defense (MTD) (se requiere una suscripción mtd).  </li>
<li>  Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción de solución de administración de gastos de telecomunicaciones).  </li>
</ul></li>
<li>  Inscribir dispositivos de cada plataforma compatible en Intune.  </li>
</ul></li>
</ul></li>
<li>  Proporcionar instrucciones de protección de aplicaciones sobre:
<ul>
<li>  Configurar directivas de protección de aplicaciones para cada plataforma compatible.  </li>
<li>  Configuración de directivas de acceso condicional para aplicaciones administradas.  </li>
<li>  Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.  </li>
<li>  Uso de informes de uso de aplicaciones administradas.  </li>
</ul></li>
<li>  Proporcionar instrucciones de migración de la administración de equipos heredados a MDM de Intune.  </li>
</ul>
  
</li>
</ul>
  
<strong>Conexión a la nube</strong>  

  Le guiaremos a través de prepararse para adjuntar entornos de Configuration Manager existentes a la nube con Intune. Los pasos detallados dependen del entorno de origen. Los pasos pueden incluir:  
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Proporcionar instrucciones para configurar la unión híbrida a Azure AD.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.  </li>
<li>  Configurar cargas de trabajo compatibles que quiera cambiar a Intune.  </li>
<li>  Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.  </li>
</ul> 

<strong>Implementar Outlook Mobile para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook Mobile para iOS y Android de forma segura en su organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.  
  Los pasos para implementar Outlook mobile para iOS y Android con Intune de forma segura dependen del entorno de origen. Puede incluir:
<ul>
<li>  Descargar las aplicaciones outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal a través de La App Store de Apple o Google Play Store.  </li>
<li>  Proporcionar instrucciones sobre la configuración:
<ul>
<li>  La implementación de aplicaciones de Outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal con Intune.  </li>
<li>  Directivas de protección de aplicaciones.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Directivas de configuración de aplicaciones.  </li>
</ul></li>
</ul>  
  </td>
<td>  Los administradores de TI deben tener infraestructuras existentes de entidad de certificación, redes inalámbricas e VPN que ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.  
  <strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar las autoridades de certificados, las redes inalámbricas, las infraestructuras VPN o los certificados de inserción de MDM de Apple para Intune.  
 
  <strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube. Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.

  <strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong> 
 
  <strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con ATP de Microsoft Defender y crear directivas de cumplimiento de dispositivos en función de su evaluación del nivel de riesgo de Windows 10. No proporcionamos asistencia sobre la compra, la concesión de licencias o la activación. Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.  
  
<strong>Windows Autopilot</strong> 
 
  Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de las instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Proporcionamos instrucciones para actualizar de Windows 7 Professional y Windows 8.1 Professional a Windows 10 Enterprise.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Comprender la intención de Windows 10.  </li>
<li>  Evaluar el entorno de origen y los requisitos (asegúrate de que Microsoft Endpoint Configuration Manager se actualiza al nivel requerido para admitir la implementación de Windows 10).  </li>
<li>  Implementar Windows 10 Enterprise y Aplicaciones de Microsoft 365 con Microsoft Endpoint Configuration Manager o Microsoft 365.  </li>
<li>  Te recomendamos opciones para evaluar las aplicaciones de Windows 10.  </li>
<li>  Habilitación del uso de Análisis de escritorio y orientación mediante la creación de un plan de implementación de Análisis de escritorio.  </li>
<li>  Evaluación de compatibilidad de aplicaciones de Microsoft 365 aprovechando el panel de preparación de Office 365 en Configuration Manager o con readiness toolkit independiente para Office, además de asistencia para implementar aplicaciones de Microsoft 365.  </li>
<li>  Crear una lista de comprobación de corrección sobre lo que necesita hacer para que el entorno de origen se asemeja a los requisitos mínimos para una implementación correcta.  </li>
<li>  Proporcionar instrucciones de actualización para los dispositivos existentes a Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesarios.  </li>
<li>  Proporcionar instrucciones de actualización para admitir el movimiento de implementación existente. FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10. Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.  </li>
<li>  Implementar Aplicaciones de Microsoft 365 con Configuration Manager como parte de la implementación de Windows 10.   </li>
<li>  Proporcionar instrucciones para ayudar a su organización a mantenerse al día con Windows 10 Enterprise y aplicaciones de Microsoft 365 con su entorno de Configuration Manager existente o Microsoft 365.  </li>
</ul>
  <strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>  Actualizar Configuration Manager a la rama actual.  </li>
<li>  Crear imágenes personalizadas para la implementación de Windows 10.  </li>
<li>  Crear y admitir scripts de implementación para la implementación de Windows 10.  </li>
<li>  Convertir un sistema Windows 10 del BIOS a la Interfaz de firmware extensible unificado (UEFI).  </li>
<li>  Habilitar las características de seguridad de Windows 10.  </li>
<li>  Configurar los Servicios de implementación de Windows (WDS) para el arranque del Entorno de ejecución previo al inicio (PXE).  </li>
<li>  Usar Microsoft Deployment Toolkit (MDT) para capturar e implementar imágenes de Windows 10.  </li>
<li>  Usar la Herramienta de migración de estado de usuario (USMT).  </li>
</ul>
Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.  </td>
<td>  Para actualizar su PC, debe cumplir con estos requisitos:
<ul>
<li>  Sistema operativo de origen: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.  </li>
<li>  Dispositivos: factor de forma de escritorio, bloc de notas o tableta.  </li>
<li>  Sistema operativo de destino: Ventana 10 Enterprise.  </li>
</ul>
Para actualizar la infraestructura, debe cumplir con estos requisitos:
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  La versión de Configuration Manager debe ser compatible con la versión de destino de Windows 10. Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Soporte para Windows 10 en Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></td>
<td>  La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Implementar las tecnologías para proteger los puntos de conexión.  </li>
<li>  Configurar perfiles de restricción de dispositivos y protección de puntos de conexión.  </li>
<li>  Evaluar la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios av de Windows Defender u otro software de seguridad de puntos de conexión.  </li>
<li>  Evaluar el estado de los servicios antivirus de Windows u otro software de seguridad de puntos de conexión.  </li>
<li>  Evaluar servidores proxy y firewalls que restringen el tráfico de red.  </li>
<li>  Habilitar el servicio ATP de Microsoft Defender explicando cómo implementar un perfil de agente de ATP con un punto de conexión incorporado.  </li>
<li>  Instrucciones de implementación, asistencia de configuración y formación sobre:
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
<li> ATP de Microsoft Defender (se requieren licencias de Windows E5 o Microsoft 365 E5).  </li>
<li>  
  Puntuación de seguridad.  
  </li>
</ul></li>
<li>  Revisar simulaciones y tutoriales (como escenarios de prácticas, malware falso e investigaciones automatizadas).  </li>
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
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la última versión de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior). 

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
  Configurar un servidor proxy para las comunicaciones sin conexión.  
  </li>
<li>  
  Configurar paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.  
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
<li>  Configuración o aprendizaje que revisa la API o las conexiones de administración de eventos e información de seguridad (SIEM).  </li>
<li>  Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).  </li>
<li>  Aprendizaje o instrucciones sobre la búsqueda avanzada.  </li>
<li>  Formación u orientación sobre el uso o la creación de consultas kusto.</li>
</li>
</ul>
Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de las instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows Virtual Desktop</strong></td>
<td><p>Proporcionamos instrucciones de implementación para la incorporación a Windows Virtual Desktop (un servicio de virtualización de aplicaciones y escritorio). Windows Virtual Desktop aprovecha las ventajas de la experiencia de varias sesiones de Windows 10 y está optimizado para Aplicaciones de Microsoft 365 para empresas con seguridad y administración integradas para Microsoft 365.</p>
<p>Proporcionamos instrucciones remotas para:</p>
<ul>
<li>Implementar el entorno de Windows Virtual Desktop con varias sesiones de Windows 10 Enterprise y Aplicaciones de Microsoft 365 para empresas mediante lo siguiente:
<ul>
<li>Imagen de Azure Marketplace.</li>
<li>Imagen compartida.</li>
<li>Kit de herramientas de implementación de Office (ODT).</li>
</ul></li>
<li>Configuración de FSLogix:
<ul>
<li>Implementación del agente FSLogix con el contenedor de perfiles.</li>
<li>Implementación del agente FSLogix con el contenedor de Office.</li>
<li>Configurar la carpeta FSLogix con exclusiones de contenido.</li>
</ul></li>
<li>Implementación de Microsoft Edge.</li>
<li>Implementar Microsoft Teams.</li>
<li>Conectarse con clientes de Windows Virtual Desktop.</li>
</ul>

<strong>Lo siguiente está fuera del ámbito</strong>
<ul>
<li>Administración de proyectos de la implementación de Windows Virtual Desktop del cliente.</li>
<li>Implementación y virtualización de aplicaciones de terceros.</li>
<li>Imágenes personalizadas.</li>
<li>Migraciones y escenarios relacionados con VMware y Citrix.</li>
<li>Escenarios de Linux.</li>
<li>Conversión o migraciones de perfiles de usuario.</li>
</ul>
Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.</td>
<td>Ya debería tener lo siguiente:
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licencias de Windows Virtual Desktop.</a></li>
<li>Redes de Azure:
<ul>
<li>Creación y subred de red virtual (VNET).</li>
<li>Firewall y grupos de seguridad de red.</li>
<li>VPN y ExpressRoute.</li>
<li>Enrutamiento a Azure desde local.</li>
<li>Reglas de firewall para permitir la conectividad a Windows Virtual Desktop.
</ul>
Para obtener más información, vea <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clientes de Escritorio remoto compatibles.</a>
</ul>
<ul><li>Configuración general de Azure AD:
<ul>
<li>Estrategia de <i>identidad (solo puede usar una de las tres opciones siguientes):</i>
<ul>
<li>Active Directory con Azure AD Connect en Azure.</li>
<li>Active Directory con Azure AD Connect local a través de VPN o ExpressRoute.</li>
<li>Servicios de dominio de Active Directory (AD DS).</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>App Assure


<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de las instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Asesoría de aplicaciones</strong></td>
<td>  App Assure es un servicio diseñado para solucionar problemas relacionados con la compatibilidad de aplicaciones de Windows 10 y Aplicaciones de Microsoft 365. Cuando solicite el servicio App Assure, trabajaremos con usted para solucionar los problemas válidos de la aplicación sin costo adicional para usted con una suscripción válida. También proporcionamos instrucciones a los clientes que se enfrentan a problemas de compatibilidad al implementar Windows Virtual Desktop y Microsoft Edge, y realizar todos los esfuerzos razonables para resolver problemas de compatibilidad. Proporcionamos asistencia de corrección para las aplicaciones implementadas en los siguientes productos de Microsoft:
<ul>
<li>  <strong>Windows 10 </strong> (incluidos los dispositivos ARM64)</li>
<li> <strong>Aplicaciones de Microsoft 365</strong>  </li>
<li>  <strong>Microsoft Edge:</strong> Para obtener instrucciones de implementación, consulte <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Información general de los canales de Microsoft Edge.</a>  </li>
<li>  <strong>Windows Virtual Desktop</strong> - Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">¿Qué es Windows Virtual Desktop?</a> y Preguntas más frecuentes sobre las sesiones múltiples <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">de Windows 10 Enterprise.</a>  </li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>  Inventario y pruebas de aplicaciones para determinar lo que funciona y lo que no en Windows 10 y en las Aplicaciones de Microsoft 365. Para obtener más información sobre este proceso, visite el <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de implementación de escritorios</a>. Si está interesado en una evaluación detallada de la preparación para la actualización, complete el formulario <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitud de cliente para la evaluación del escritorio moderno</a>.</li>
<li>  Buscar instrucciones de compatibilidad y soporte técnico de Windows 10 en aplicaciones ISV de terceros. Para más información, vea <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análisis de escritorio</a>.</li>
<li>Servicios de solo empaquetado de la aplicación. Sin embargo, el equipo de App Assure crea paquetes de aplicaciones que hemos corregido para Windows 10 para asegurarse de que se pueden implementar en el entorno del cliente.</li>
</ul>

<strong>Las responsabilidades del cliente incluyen</strong>  
<ul>
<li>  Creación de un inventario de aplicaciones.</li>
<li>  Validación de esas aplicaciones en Windows 10 y en las Aplicaciones de Microsoft 365.</li>
</ul>
<strong>Nota:</strong>  Microsoft no puede realizar cambios en el código fuente. Sin embargo, el equipo de App Assure puede proporcionar instrucciones a los desarrolladores de aplicaciones si el código fuente está disponible para sus aplicaciones. 


  Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.  </td>

</td>
<td><strong>Aplicaciones de Windows 10 y Microsoft 365</strong>
<ul>
<li>  
  Las aplicaciones que funcionaban en Windows 7, Windows 8.1, Office 2010 y Office 2013 también funcionan en Windows 10 y en las Aplicaciones de Microsoft 365.  
  </li>
</ul>
<strong>Windows 10 en ARM</strong>
<ul>
<li>  
Las aplicaciones que funcionaban en Windows 7, Office 2010 o versiones posteriores también funcionan en Windows 10 y aplicaciones de Microsoft 365 en dispositivos ARM64. 
  </li>
</ul>
  <strong>Nota:</strong> 
<ul>
<li> La emulación x64 (64 bits) está disponible en versión preliminar para los clientes que participan en <a href="https://insider.windows.com/">el Programa Windows Insider.</a>  </li>
<li>  
 Para los clientes que no son de Windows Insider en Windows 10 versión 2004 (o posterior), ARM64 Photoshop es compatible con el paquete de compatibilidad de OpenCL y <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL.</a> 
  </li>
<li>  
  Los clientes del Programa Windows Insider pueden descargar una versión de Insider del paquete de compatibilidad de OpenCL y OpenGL para usarla con aplicaciones adicionales.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Si las aplicaciones web o los sitios funcionan en Internet Explorer 11, las versiones compatibles de Google Chrome o cualquier versión de Microsoft Edge, también funcionarán con Microsoft Edge.  
  </li>
<li>  
  Como la web evoluciona constantemente, asegúrese de revisar esta lista publicada de cambios conocidos que afectan a la compatibilidad de sitios <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">para Microsoft Edge.</a>  
  </li>
</ul>
  <strong>Windows Virtual Desktop </strong>  
<ul>
<li>  
  Las aplicaciones virtualizadas que se ejecutan en el host de sesión de Escritorio remoto (RDSH) de Windows Server también se ejecutan en Windows 10 Enterprise multisesión como parte de Windows Virtual Desktop.  
  </li>
<li>  
  Las aplicaciones que se ejecutan en cualquier entorno de infraestructura de escritorio virtual (VDI) de Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.  
  </li>
<li>  
  Las aplicaciones que se ejecutan en dispositivos cliente con Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.  
  </li>
</ul>
  <strong>Nota:</strong> Las exclusiones y limitaciones de compatibilidad de varias sesiones de Windows 10 Enterprise incluyen:
<ul>
<li>  
  Redirección limitada del hardware.  
  </li>
<li>  
  Las aplicaciones que hacen un uso intensivo de A/V pueden tener una capacidad reducida.  
  </li>
<li>  
  Las aplicaciones de 16 bits no son compatibles con Windows Virtual Desktop de 64 bits.  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de las instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> (para clientes de Windows 10 Enterprise)</td>
<td><ul>
<li>  Proporcionamos orientación de implementación remota y asistencia de compatibilidad para: implementar Microsoft Edge en Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).  </li>
<li>  Configuración de Microsoft Edge (con directivas de grupo o configuración de aplicaciones y directivas de aplicaciones de Intune).  </li>
<li>  Realizar un inventario de la lista de sitios que pueden requerir su uso en el modo Internet Explorer.  </li>
<li>  Habilitar el modo de Internet Explorer con la lista de sitios de empresa existente.  
  Además, si tiene una aplicación web o un sitio que funciona con Internet Explorer o Google Chrome y experimenta problemas de compatibilidad, le proporcionamos instrucciones para resolver el problema sin costo adicional. Consulte <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> para obtener más información.  </li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>Administración de proyectos de la implementación de Microsoft Edge del cliente.</li>
<li>  Soporte técnico en las instalaciones.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
