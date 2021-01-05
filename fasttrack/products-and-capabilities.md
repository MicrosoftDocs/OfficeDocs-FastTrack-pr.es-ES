---
title: Productos y capacidades
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Este tema incluye detalles sobre los escenarios de carga de trabajo compatibles con FastTrack y las expectativas del entorno de origen necesarias antes de que podamos comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que incorpore el entorno de origen a los requisitos mínimos para la incorporación correcta.
ms.openlocfilehash: 5e65d160822ed50840ecc65f484433bf0d485913
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750107"
---
# <a name="products-and-capabilities"></a>Productos y capacidades

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Servicios y escenarios compatibles con FastTrack

Este tema incluye detalles sobre los escenarios de carga de trabajo compatibles con FastTrack y las expectativas del entorno de origen necesarias antes de que podamos comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que incorpore el entorno de origen a los requisitos mínimos para la incorporación correcta.

FastTrack proporciona instrucciones para ayudarle primero con las capacidades principales (comunes para todos los servicios en línea de Microsoft) y, a continuación, con la incorporación de cada servicio elegible:

  - [General](#general)
  - [Seguridad y cumplimiento](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [Asesoría de aplicaciones](#app-assure)
  - [El nuevo Microsoft Edge](#the-new-microsoft-edge)

> [!NOTE]
> Para obtener información sobre las expectativas de entorno de origen para Office 365 Administración Pública, vea [Expectativas de entorno de origen para Office 365 Administración Pública](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations). 
 
## <a name="general"></a>General

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de la guía de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Incorporación principal</strong></td>
<td>  Proporcionamos instrucciones remotas sobre la incorporación principal, que implica el aprovisionamiento de servicios, el inquilino y la integración de identidades. También incluye los pasos para ofrecer una base para los servicios de incorporación como Exchange Online, SharePoint Online y Microsoft Teams, incluida una <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">Descripción de la seguridad, la conectividad de red y el cumplimiento normativo</a>.  
  La incorporación de uno o más servicios elegibles puede empezar al finalizar la incorporación principal.
</li>
</ul>  

<strong> Integración de identidades </strong>

Proporcionamos instrucciones remotas para:
<ul>
<li>Preparar las identidades locales de Active Directory para la sincronización a Azure Active Directory (Azure AD), incluida la instalación y la configuración de Azure AD Connect (uno o varios bosques) y las licencias (incluidas las licencias basadas en grupos).</li>
<li>Crear identidades de nube, incluidas la importación en masa y la concesión de licencias, incluido el uso de licencias basadas en grupos.</li>
<li>Elegir y habilitar el método de autenticación correcto para el recorrido de la nube, la sincronización de hash de contraseña, la autenticación de paso a través o los servicios de Federación de Active Directory (AD FS).</li>
<li>Habilitación de AD FS para clientes con un único bosque de Active Directory y identidades sincronizados con la herramienta de Azure AD Connect. Esto requiere Windows Server 2012 R2 Active Directory Federation Services 2,0 o superior.</li>
<li>Migrar la autenticación de AD FS a Azure AD mediante la sincronización de hash de contraseña o la autenticación de paso a través.</li>
<li>Migrar aplicaciones integradas previamente (como las aplicaciones de software de galería de Azure AD (SaaS) de AD FS a Azure AD para el inicio de sesión único (SSO).</li>
<li>Habilitar las integraciones de la aplicación SaaS con SSO desde la galería de Azure AD.</li>
<li>Habilitar el aprovisionamiento automático de usuarios para las aplicaciones SaaS preintegradas, como se muestra en la <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">lista de tutorial de integración de aplicaciones</a> (limitada a las aplicaciones SaaS de galería de Azure ad y al aprovisionamiento saliente únicamente).  </li>
</td>

<td>  <strong>Habilitación de red </strong>  
  <br>Como parte del beneficio de FastTrack, le recomendamos que se asegure de las prácticas recomendadas para conectarse a los servicios en la nube para garantizar los más altos niveles de rendimiento de Microsoft 365.  
  
<strong>Bosques de Active</strong> Directory Tienen el nivel funcional de bosque establecido en Windows Server 2003 o superior, con la siguiente configuración de bosque:
<ul>
<li>  Un solo bosque de Active Directory.  </li>
<li>  Un solo bosque de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).  </li>
<li>  Varios bosques de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).  </li>
<li>  Varios bosques de cuentas de Active Directory con uno de los bosques que es un bosque de cuentas de Active Directory centralizado que incluye Exchange o Lync 2010, Lync 2013 o Skype Empresarial.  </li>
<li>  Varios bosques de cuentas de Active Directory, cada uno con su propia organización de Exchange.  </li>
<li>  Tareas necesarias para la configuración de los inquilinos y la integración con Azure Active Directory, si es necesario.   </li>
</ul>
  <strong>Relevancia</strong>  <ul>
<li>  Para escenarios de varios bosques de Active Directory, si se implementa Lync 2010, Lync 2013 o Skype empresarial, debe implementarse en el mismo bosque de Active Directory que Exchange.  </li>
<li>  Cuando se implementan varios bosques de Active Directory con varias organizaciones de Exchange en una configuración multihíbrida de Exchange, no se admiten los espacios de nombres principales de usuario (UPN) compartidos entre bosques de origen. Los espacios de nombres SMTP principales entre las organizaciones de Exchange también deben estar separados. Para más información, consulte <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implementaciones híbridas con varios bosques de Active Directory</a>.  </li>
<li>  Para todas las configuraciones de varios bosques, la implementación de los servicios de Federación de Active Directory (AD FS) está fuera del ámbito. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Aplicaciones de Microsoft 365</strong></td>
<td>  Proporcionamos una guía de implementación remota para:
<ul>
<li>  Solucionar los problemas de implementación.  </li>
<li>  Asignar licencias de usuario final y basadas en dispositivos mediante el Centro de administración de Microsoft 365 y Windows PowerShell.  </li>
<li>  Instalar Aplicaciones de Microsoft 365 desde el Portal de Office 365 con la opción Hacer clic y ejecutar.  </li>
<li>  Instalar aplicaciones de Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile y PowerPoint Mobile) en los dispositivos iOS o Android.  </li>
<li>  Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.  </li>
<li>  Selección y configuración de una instalación local o en la nube.  </li>
<li>  Creación de la configuración XML de la herramienta de implementación de Office con la herramienta de personalización de Office o XML nativo para configurar el paquete de implementación.  </li>
<li>  Implementar mediante Microsoft Endpoint Configuration Manager, incluida la ayuda con la creación del empaquetado de Microsoft Endpoint Configuration Manager.  
  Además, si tiene una macro o un complemento que funcionaba con versiones anteriores de Office y experimenta problemas de compatibilidad, proporcionamos instrucciones para corregir el problema de compatibilidad sin costo adicional a través del programa de aseguramiento de aplicaciones. Para obtener más información, consulte la parte de <strong>aseguramiento de aplicaciones</strong> de <a href="#windows-10">Windows 10</a> . </li>
</ul></td>
<td><ul>
<li>  El software de cliente en línea debe tener un nivel mínimo, como se define en los <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Estado de la red</strong></td>
<td>  Proporcionamos instrucciones remotas para obtener e interpretar datos clave de conectividad de red desde su entorno que muestre cómo se alinean los sitios de la organización con los <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principios de conectividad de red de</a>Microsoft. Esto destaca su puntuación de red que afecta directamente a la velocidad de migración, la experiencia del usuario, el rendimiento del servicio y la confiabilidad.  
  También le guiaremos a través de los pasos de corrección resaltados por estos datos para ayudarle a mejorar la puntuación de la red.  </td>
<td><ul>
<li>  Acceso al centro de administración de Microsoft 365.  </li>
<li>  Se necesitan versiones actualizadas de las aplicaciones de Microsoft 365.  </li>
<li>  Los servicios de ubicación están habilitados según <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">las recomendaciones de rendimiento de red en el centro de administración de Microsoft 365 (versión preliminar)</a>.  </li>
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
<th><strong>Detalles de la guía de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></td>
<td>  Proporcionamos una orientación remota para proteger sus identidades de nube en los siguientes escenarios.  

 <br/>

<strong>Infraestructura de base segura</strong>  </ul>
<ul>
<li>  Configuración y habilitación de la autenticación segura para sus identidades, incluida la protección con Azure multi-factor Authentication (MFA) (solo nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseña de autoservicio (SSPR).  </li>
<li>  Para clientes que no son de Azure Premium, se proporciona orientación para proteger las identidades mediante los valores predeterminados de seguridad.  </li>
<li>  Para los clientes de Azure AD Premium, se proporciona orientación para proteger las identidades con acceso condicional.  </li>
<li>  Detección y bloqueo del uso de contraseñas débiles con la protección con contraseña de Azure AD.  </li>
<li>  Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.  </li>
<li>  Habilitación de la detección y corrección basada en riesgos con Azure Identity Protection.  </li>
<li>  Habilitación de una pantalla de inicio de sesión personalizada, que incluye logotipos, texto e imágenes con personalización de marca.  </li>
<li>  Comparta de forma segura aplicaciones y servicios con usuarios invitados mediante la B2B de Azure AD.  </li>
<li>  Administración del acceso para los administradores de Office 365 mediante funciones administrativas integradas de control de acceso basado en roles (RBAC) y para reducir el número de cuentas de administrador con privilegios.  </li>
<li>  Configurar una Unión híbrida de Azure AD.  </li>
<li>  Configurando Azure AD join.  </li>
</ul>
  
<strong>Supervisión y generación de informes</strong>  
<ul>
<li>  
  Habilitación de la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Empresarial</strong>  
<ul>
<li>  
  Administrar su ciclo de vida de identidad y acceso de Azure AD a escala con la administración de derechos de Azure AD.
  </li>
<li>  
  Administrar la pertenencia a grupos de Azure AD, el acceso de la aplicación empresarial y las asignaciones de roles con las revisiones de acceso de Azure AD.  
  </li>
<li>  
  Revisión de los términos de uso de Azure AD.  
  </li>
<li>  
  Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatización y eficiencia </strong>  
<ul>
<li>  
  Habilitación de Azure AD SSPR.  
  </li>
<li>  Permitir a los usuarios crear y administrar sus propios grupos de seguridad en la nube u Office 365 con la administración de grupos de autoservicio de Azure AD.  </li>
<li>  Administración del acceso delegado a las aplicaciones empresariales con la administración de grupos delegados de Azure AD.  </li>
<li>  Habilitación de grupos dinámicos de Azure AD.  </li>
<li>  Organizar aplicaciones en el portal de mis aplicaciones mediante colecciones  </li>
</ul></td>
<td>La implementación local de Active Directory y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con Azure AD y las características de Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Activar y configurar el inquilino.  </li>
<li>  Crear y configurar etiquetas y directivas.  </li>
<li>  Aplicar la protección de la información a documentos.  </li>
<li>  Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.  </li>
<li>  Detectar y etiquetar archivos en reposo con el escáner de Azure Information Protection.  </li>
<li>  Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.  </li>
</ul>
También le ofrecemos instrucciones para aplicar la protección con Microsoft Azure Rights Management Services (Azure RMS), el cifrado de mensajes de Office 365 (OME) y la prevención de pérdida de datos (DLP).  </td>
<td>  Las responsabilidades de requisitos previos del cliente incluyen:
<ul>
<li>  Una lista de ubicaciones de recursos compartidos de archivos que se examinarán.  </li>
<li>  Una taxonomía de clasificación aprobada. </li>
<li> Comprensión de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.  </li>
<li>  Una cuenta de servicio creada para su Active Directory local que se haya sincronizado con Azure AD. </li>
<li>  Etiquetas configuradas para clasificación y protección. </li>
<li> Todos los requisitos previos para el analizador de Azure Information Protection están en su ubicación. Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">requisitos previos para instalar e implementar el escáner de etiquetación unificada de Azure Information Protection</a>. </li>
<li>  Asegúrese de que los dispositivos de usuario ejecutan un sistema operativo compatible y tienen instalados los requisitos previos necesarios. Consulte lo siguiente para obtener más información.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetación unificada de Azure Information Protection para los usuarios</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </li>
</ul>
<li> Instalación y configuración del conector y los servidores de Azure RMS, incluido el conector de Active Directory RMS (AD RMS) para la compatibilidad con entornos híbridos.  </li>
<li> Instalación y configuración de traer su propia clave (BYOK), cifrado de doble clave (DKE) (solo cliente de etiquetado unificado) o mantenga su propia clave (HYOK) (solo cliente clásico) en caso de que necesite una de estas opciones para la implementación.  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 defender es un conjunto unificado de defensa de la empresa, antes y después de la violación, que coordina la detección, prevención, investigación y respuesta entre los puntos de conexión, las identidades, el correo electrónico y las aplicaciones de forma nativa para proporcionar protección integrada contra ataques sofisticados. Proporcionamos instrucciones remotas para: </p> 
<ul>
<li>  Proporciona información general sobre el centro de seguridad de Microsoft 365.  </li>
<li>  Revisión de incidencias de productos cruzados, que incluyen centrarse en las tareas críticas al garantizar el ámbito completo de los ataques, los activos afectados y las acciones de corrección automatizadas que se agrupan juntos.  </li>
<li>  Demostrar cómo Microsoft 365 defender puede organizar la investigación de activos, usuarios, dispositivos y buzones de correo que puedan haberse puesto en peligro mediante la Autorrecuperación automática. </li>
<li>  Explicación y proporciona ejemplos de cómo los clientes pueden buscar de forma proactiva los intentos de intrusión y la actividad de infracciones que afectan a su correo electrónico, datos, dispositivos y cuentas en varios conjuntos de datos.   </li>
<li> Mostrar a los clientes cómo pueden revisar y mejorar su postura de seguridad de forma holística mediante la calificación segura de Microsoft.</li>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>
<li> Administración de proyectos de las actividades de corrección de los clientes. </li>
<li> Administración continuada, respuesta a amenazas y corrección. </li>
<li> Guía de implementación o educación sobre:
<ul>
<li> Cómo corregir o interpretar los distintos tipos de alertas y actividades supervisadas. </li>
<li> Cómo investigar un usuario, equipo, ruta de movimiento lateral o entidad. </li>
<li> Caza de amenazas personalizadas.  </li>
</ul>
</li>
<li> Información de seguridad y administración de eventos (SIEM) o integración de la API.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una buena visibilidad, control sobre los recorridos de datos y análisis sofisticados para identificar y combatir las amenazas cibernéticos en todos los servicios en la nube de Microsoft y de terceros. Proporcionamos instrucciones remotas para:
<ul>
<li>  Configuración del portal, que incluye:  </li>
<ul>
<li> Importación de grupos de usuarios.</li>
<li> Administración de la configuración y el acceso de administrador.  </li>
<li> Ámbito de la implementación para seleccionar determinados grupos de usuarios que se van a supervisar o excluir de la supervisión.</li>
<li> Configurar intervalos IP y etiquetas.</li>
<li> Personalización de la experiencia del usuario final con su logotipo y mensajería personalizada.</li>
</ul>
<li> Configuración de detección en la nube para que le proporcione sombreado mediante:</li>
<ul>
<li> Microsoft defender para puntos de conexión.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Conexión de <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">aplicaciones destacadas</a> con conectores de aplicaciones.</li>
<li> Configuración del control de aplicaciones de acceso condicional en los portales de acceso condicional y de aplicación de nube para aplicar controles de sesión en tiempo real.</li>
<li> Implementación de los paneles Cloud App Security y Cloud Discovery.</li>
<li> Personalización de los resultados de riesgos de aplicaciones en función de las prioridades de su organización.</li>
<li> Crear etiquetas y categorías de aplicaciones.</li>
<li> Autorizar y no autorizar aplicaciones.</li>
<li> Uso de los registros de actividad y archivos.</li>
<li> Administración de aplicaciones de OAuth.</li>
<li> Descripción de la correlación de incidentes en el portal de Microsoft 365 defender.</li>
<li> Proporciona asistencia de configuración con los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 principales casos de uso para CASBs</a> (incluida la creación o actualización de hasta seis (6) directivas) excepto: </li>
<ul>
<li> Auditar la configuración de los entornos de Internet como servicio (IaaS) (#18).</li>
<li> Supervisar las actividades de los usuarios para protegerse de las amenazas en los entornos de IaaS (#19).</li>
</ul>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>
<li> Administración de proyectos de las actividades de corrección de los clientes.</li>
<li> Administración continuada, respuesta a amenazas y corrección. </li>
<li> Configuración de la infraestructura, instalación o implementación de las cargas de registro automáticas para los informes continuos mediante el acoplador o un recopilador de registros. Vea los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 primeros casos de uso para CASBs</a> para obtener más información.</li>
<li> Creación de un informe de instantáneas de detección en la nube.</li>
<li> Bloqueo del uso de la aplicación mediante bloques de scripts.</li>
<li> Conexión de aplicaciones personalizadas.</li>
<li> Integración con proveedores de identidades de terceros (ISP) y proveedores de prevención de pérdida de datos (DLP).</li>
<li> Aprendizaje o instrucciones sobre la búsqueda avanzada.</li>
<li> Investigación y corrección automáticas, incluidas las guías de Microsoft Power automatization.</li>
<li> Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</li>
<li> Implementación de la detección de aplicaciones en la nube como prueba de concepto.</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></td>
<td>  La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Implementación de las tecnologías para proteger los extremos.  </li>
<li>  Configuración de Endpoint Protection y los perfiles de restricción de dispositivos.  </li>
<li>  Evaluación de la versión del sistema operativo y la administración de dispositivos (incluidos Intune, el administrador de configuración de Microsoft Endpoint, los objetos de directiva de grupo (GPO) y las configuraciones de terceros), así como el estado de los servicios de AV de Windows Defender u otro software de seguridad de extremos.  </li>
<li>  Evaluar el estado de los servicios de Windows AV o de otro software de seguridad de extremo.  </li>
<li>  Evaluar los servidores proxy y los firewalls restringir el tráfico de red.  </li>
<li>  Habilitar el servicio ATP de Microsoft defender mediante la explicación de cómo implementar un perfil de agente ATP con un punto de conexión incorporado.  </li>
<li>  Guía de implementación, asistencia para la configuración y educación en:
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
<li>  Revisión de simulaciones y tutoriales (como escenarios de prácticas, malware falsificado e investigaciones automatizadas).  </li>
<li>  Información general sobre las características de informes y de análisis de amenazas.  </li>
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
  Canal de Semi-Annual de Windows Server (SAC) versión 1803.  
  </li>
<li>  
  macOS versiones 10,13, 10,14 y 10,15.  
  </li>
</ul>
</li>
</ul>
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse con la versión más reciente del administrador de configuración de System Center 2012 (versiones 1012 R2, 1511 o 1602) o el administrador de configuración de Microsoft Endpoint (versión 2002 o posterior). 

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
  Configuración de un servidor proxy para las comunicaciones sin conexión.  
  </li>
<li>  
  Configuración de paquetes de implementación de Configuration Manager en instancias y versiones de administrador de configuración de nivel inferior.  
  </li>
<li>  
  Servidores de incorporación a Azure Security Center.  
  </li>
<li>  
  Servidores no administrados por Configuration Manager.  
  </li>
</ul></li>
<li>  incorporación y configuración de macOS:
<ul>
<li>  
  Implementación manual basada en la Intune.  
  </li>
<li>  
  Implementación basada en JAMF.
  </li>
<li>  
  Otra implementación basada en producto de administración de dispositivos móviles (MDM).  
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
<li>  Configuración o formación que revisan la API o la información de seguridad y las conexiones de administración de eventos (SIEM).  </li>
<li>  Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).  </li>
<li>  Aprendizaje o instrucciones sobre la búsqueda avanzada.  </li>
<li>  Formación o orientación sobre el uso o la creación de consultas Kusto.</li>
</li>
</ul>
Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft defender para identidad </strong></td>
<td>  Microsoft Defender for Identity es una solución de seguridad basada en la nube que aprovecha las señales locales de Active Directory para identificar, detectar e investigar las amenazas avanzadas, las identidades vulnerables y las acciones internas malintencionadas dirigidas a su organización. Proporcionamos instrucciones remotas para:
<ul>
<li>   Crear la instancia de defender para Identity. </li>
<li>   Conectar defender para identidades a Active Directory. </li>
<li>   Evaluar la preparación del entorno para implementar defender para el sensor de identidad en los controladores de dominio, incluidos:</li>   
<ul> 
<li>  Ejecutar la herramienta de Sizing para planear la capacidad de los recursos. </li>
<li>  Ejecutar la herramienta de auditoría para evaluar la compatibilidad de los controladores de dominio con el sensor. </li>
</ul>
<li>  Implementar el sensor para capturar y analizar el tráfico de red y los eventos de Windows directamente desde los controladores de dominio, entre los que se incluyen: </li>
<ul> 
<li>  Descargar el paquete del sensor. </li>
<li>  Configuración del sensor. </li>
<li>  Instalar el sensor en el controlador de dominio silenciosamente. </li>
<li>  Implementación del sensor en el entorno de varios bosques. </li>
</ul>
<li>  Integración de defender para identidad con Microsoft Cloud App Security (no se requiere licencia de Cloud App Security). </li>
<li>  Proporciona instrucciones de implementación, asistencia para la configuración y educación sobre: </li>
<ul>
<li> Optimización del entorno para reducir el "ruido".  </li>
<li>  Descripción del informe de evaluación de postura de seguridad de identidades. </li>
<li>  Descripción de la puntuación de prioridad de la investigación del usuario y el informe de clasificación de la investigación del usuario. </li>
<li> Información sobre el informe de usuarios inactivos.  </li>
<li> Proporciona opciones de corrección en una cuenta comprometida.  </li>
</ul>
<li>  Facilitar la migración de Advanced Threat Analytics (ATA) a defender para Identity. </li>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>

<li> Administración de proyectos de las actividades de corrección de los clientes. </li>
<li> Administración continuada, respuesta a amenazas y corrección.  </li>
<li> Implementación de defender para el sensor de identidad, que incluye: </li>
<ul>
<li> Planificación manual de la capacidad. </li>
<li> Implementar el sensor en una capacidad independiente. </li>
<li> Implementación del sensor con un adaptador de formación de equipos de tarjeta de interfaz de red (NIC). </li>
<li> Implementación del sensor mediante una herramienta de terceros. </li>
<li> Conexión a defender para el servicio de nube de identidad a través de una conexión de proxy Web. </li>
</ul>
<li> Creación y administración de honeytokens. </li>
<li> Guía de implementación o educación sobre: </li>
<ul>
<li> Corrección o interpretación de varios tipos de alertas y actividades supervisadas.  </li>
<li> Investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad. </li>
<li> Amenaza o caza avanzada. </li>
<li> Respuesta de incidente. </li>
</ul>
<li> Proporciona un tutorial del laboratorio de alertas de seguridad para defender para Identity. </li>
<li> Notificación cuando defender para identidad detecta actividades sospechosas mediante el envío de alertas de seguridad al servidor de syslog a través de un sensor denominado.  </li>
<li> Configurar defender para identidad para realizar consultas mediante el protocolo remoto del administrador de cuentas de seguridad (SAMR) para identificar a los administradores locales en equipos específicos. </li>
<li> Configurar soluciones de VPN para agregar información desde la conexión VPN a la página de Perfil de un usuario.  </li>
<li> Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel). </li>
<li> Implementación de defender para sensores de identidad como prueba de concepto.</li>
</ul></td>
<td><ul>
<li>  Active Directory implementado.  </li>
<li>  Los controladores de dominio que pretende instalar defender para los sensores de identidades tienen conectividad a Internet con el servicio de defender para la nube de identidad.  </li>
<ul>
<li> El firewall y el proxy deben estar abiertos para comunicarse con el defensor para el servicio de nube de identidad (*. atp.azure.com puerto 443 debe estar abierto).</li>
</ul>
<li> Controladores de dominio que se ejecutan en una de las siguientes opciones:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 con KB4487044 (compilación de SO 17763,316).</li>
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
<li> Barreras de la información.</li>
<li> Administración del acceso privilegiado.</li>
<li> Desarrollo de la arquitectura de la información en SharePoint.</li>
<li> Secuencias de comandos y códigos personalizados.</li>
</td>
<td>Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</td>
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
<li>  Crear directivas de DLP de punto de conexión para dispositivos con Windows 10.  </li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>Clave de cliente.</li>
<li>Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</li>
<li>Creación o modificación de diccionarios de palabras clave.</li>
<li>Secuencias de comandos y códigos personalizados.</li>
</ul>
<strong>Nota:</strong> Para obtener más información, vea <strong> Azure Information Protection </strong> en <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.
<ul>

</td>
<td>Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Proporcionamos instrucciones remotas para prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos. Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles. Los pasos pueden incluir:
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que se usarán en Intune aprovechando las identidades locales de Active Directory o de la nube (Azure AD).  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Configurar la autoridad de MDM, en función de las necesidades de administración, entre las que se incluyen:
<ul>
<li>  Establecer Intune como entidad MDM cuando Intune es la única solución MDM.  </li>
</ul></li>
<li>  Proporcionar instrucciones de MDM para:
<ul>
<li>  Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.  </li>
<li>  Configurar servicios y directivas de administración de MDM como:
<ul>
<li>  Implementación de aplicaciones para cada plataforma admitida a través de vínculos Web o vínculos profundos.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tiene una entidad de certificación, una red inalámbrica o una infraestructura de VPN en su organización.  </li>
<li>  Conexión al almacén de datos de Intune.  </li>
<li>  Integrar Intune con:
<ul>
<li>  Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).  </li>
<li>  Soluciones de asociados de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).  </li>
<li>  Una solución de administración de gastos de telecomunicaciones (es necesaria una suscripción a la solución de administración de gastos de telecomunicaciones).  </li>
<li>  ATP de Microsoft defender (se necesitan licencias de Windows E5 o Microsoft 365 E5).  </li>
</ul></li>
<li>  Inscribir dispositivos de cada plataforma compatible en Intune.  </li>
</ul></li>
</ul></li>
<li>  Proporciona instrucciones de protección de aplicaciones en:
<ul>
<li>  Configurar directivas de protección de aplicaciones para cada plataforma compatible.  </li>
<li>  Configuración de directivas de acceso condicional para aplicaciones administradas.  </li>
<li>  Dirigirse a los grupos de usuarios apropiados con las directivas de MAM mencionadas anteriormente.  </li>
<li>  Uso de informes de uso de aplicaciones administradas.  </li>
</ul></li>
<li>  Proporciona instrucciones de migración desde la administración de equipos heredados a Intune MDM.  </li>
</ul>
  <strong>Nota</strong>: la administración de equipos heredados ya no se admite desde el 15 de octubre de 2020 en adelante.  
</li>
</ul>
  
<strong>Conexión a la nube</strong>  

  Le guiamos a través de la preparación para hospedar en la nube entornos de Configuration Manager existentes con Intune. Los pasos detallados dependen del entorno de origen. Los pasos pueden incluir:  
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Proporciona instrucciones sobre cómo configurar la Unión híbrida de Azure AD.  </li>
<li>  Proporciona instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar Cloud Management Gateway.  </li>
<li>  Configurar cargas de trabajo compatibles que quiera cambiar a Intune.  </li>
<li>  Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.  </li>
</ul> 

<strong>Implementar Outlook Mobile para iOS y Android de manera segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook Mobile para iOS y Android de forma segura en su organización para asegurarse de que los usuarios tengan instaladas todas las aplicaciones necesarias.  
  Los pasos para implementar de forma segura Outlook Mobile para iOS y Android con Intune dependen de su entorno de origen. Puede incluir:
<ul>
<li>  Descargar las aplicaciones Outlook para iOS y Android, autenticador de Microsoft y portal de empresa de Intune a través de la App Store de Apple o Google Play Store.  </li>
<li>  Proporciona instrucciones para configurar:
<ul>
<li>  La implementación de las aplicaciones de Outlook para iOS y Android, el autenticador de Microsoft y el portal de empresa de Intune con Intune.  </li>
<li>  Directivas de protección de aplicaciones.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Directivas de configuración de la aplicación.  </li>
</ul></li>
</ul>
  
  <strong>Nota</strong>: FastTrack no es compatible con la protección de Outlook para iOS y Android con las directivas de buzón de correo de dispositivo móvil de Exchange. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.  
  </td>
<td>  Los administradores de TI deben contar con una entidad de certificación, una red inalámbrica y unas infraestructuras VPN existentes en sus entornos de producción al planear la implementación de perfiles de red inalámbrica y VPN con Intune.  
  <strong>Nota</strong>: el beneficio del servicio FastTrack no incluye asistencia para configurar o configurar entidades de certificación, redes inalámbricas, infraestructuras VPN o certificados push de Apple para Intune.  
 
  <strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.

  <strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong> 
 
  <strong>Nota</strong>: proporcionamos asistencia sobre la integración de Intune con Microsoft defender ATP y la creación de directivas de cumplimiento de dispositivos basadas en su evaluación de nivel de riesgo de Windows 10. No proporcionamos asistencia sobre la compra, concesión de licencias o activación. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.  
  
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
<td>Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de la guía de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Para Exchange Online, le guiaremos a través del proceso para preparar la organización para usar el correo electrónico. Los pasos exactos dependen de su entorno de origen y sus planes de migración de correo electrónico.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Configuración de las características de Exchange Online Protection (EOP) para todos los dominios habilitados para correo que se han validado en Office 365.  </li>
<li>  Apuntar los registros de intercambio de correo (MX) a Office 365.  </li>
<li>  Configurar la característica ATP de Office 365 si forma parte de su servicio de suscripción. Para obtener más información, consulte la parte de la <strong>protección contra amenazas avanzada de Office 365</strong> de esta tabla.  </li>
<li>  Configuración de la característica de prevención de pérdida de datos (DLP) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</li>
<li>  Configuración del cifrado de mensajes de Office 365 (OME) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</li>
</ul>
  <strong>Nota:</strong> El servicio de replicación de buzones (MRS) intenta migrar los mensajes de correo electrónico de Information Rights Management (IRM) desde el buzón de correo local al buzón de correo de Exchange Online correspondiente. La capacidad de leer el contenido protegido posterior a la migración dependerá de la asignación de clientes y la copia de las plantillas de Active Directory Rights Management Services (AD RMS) en el servicio Azure Rights Management (Azure RMS).  
<ul>
<li>  Configurar puertos del firewall.  </li>
<li>  Configuración de DNS, incluida la detección automática necesaria, el marco de directivas de remitente (SPF), el correo identificado por DomainKeys (DKIM), la autenticación de mensajes basada en dominio, la notificación y el cumplimiento (DMARC) y los registros MX (según sea necesario).  </li>
<li>  Configuración del flujo de correo electrónico entre su entorno de mensajería de origen y Exchange Online (si procede).  </li>
<li>  Operación de migración de correo desde el entorno de mensajería de origen a Office 365.  </li>
<li>  Configuración de clientes de buzón (Outlook para Windows, Outlook en la web y Outlook para iOS y Android).  </li>
</ul>
  <strong>Migración de datos</strong>  <br>
Para obtener información sobre cómo usar el beneficio de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">migración de datos</a>.   
<td>  El entorno de origen debe tener uno de los siguientes niveles mínimos:
<ul>
<li>  Una o varias organizaciones de Exchange a partir de Exchange Server 2003.  </li>
<li>  Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).  </li>
<li>  Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).  </li>
<li>  Para obtener información sobre las funciones multigeográficas, vea <a href="https://go.microsoft.com/fwlink/?linkid=872776">multi-Geogeográfico Capabilities in Exchange Online</a>.  </li>
</ul>
El software cliente en línea, como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, el cliente de sincronización de OneDrive para la empresa, Power BI Desktop y Skype empresarial deben tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 Office</a>.  </td>
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
<li> Barreras de la información.</li>
<li> Administración del acceso privilegiado.</li>
<li> Desarrollo de la arquitectura de la información en SharePoint.</li>
<li> Secuencias de comandos y códigos personalizados.</li>
</td>
<td>Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</td>
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
<li>  Crear directivas de DLP de punto de conexión para dispositivos con Windows 10.  </li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>Clave de cliente.</li>
<li>Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</li>
<li>Creación o modificación de diccionarios de palabras clave.</li>
<li>Secuencias de comandos y códigos personalizados.</li>
</ul>
<strong>Nota:</strong> Para obtener más información, vea <strong> Azure Information Protection </strong> en <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.
<ul>

</td>
<td>Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Confirmar que los requisitos mínimos de Exchange Online, SharePoint Online, los grupos de Office 365 y Azure AD son compatibles con Teams.  </li>
<li>  Configuración de puertos del firewall.  </li>
<li>  Configuración de DNS.  </li>
<li>  Confirmar que se ha habilitado Teams en su espacio empresarial de Office 365.  </li>
<li>  Habilitar o deshabilitar licencias de usuario.  </li>
<li>  Evaluación de la red para Teams:
<ul>
<li>  Comprobaciones de puertos y puntos de conexión.  </li>
<li>  Comprobaciones de calidad de la conexión.  </li>
<li>  Estimaciones de ancho de banda.  </li>
</ul>
<ul>
<li>  Configuración de la Directiva de aplicación de Microsoft Teams (Teams Web App, Teams App de escritorio y Teams para iOS y aplicación Android).  </li>
</ul>
Si procede, también se proporcionan instrucciones para:
<ul>
<li>  Dispositivos de Microsoft Teams Room:  </li>
<ul>
<li>  Creación de cuentas en línea necesarias para los dispositivos de telefonía y salas de conferencias compatibles que aparecen en el <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos de Teams</a>.  </li>
<li>  Asistencia remota con la configuración del servicio de dispositivos certificados de salas de Microsoft Teams.  </li>
<li>  Habilitar audioconferencia:  </li>
<li>  Parámetros predeterminados de la configuración de la organización para puente de conferencia.  </li>
<li>  Asignación de un puente de conferencia a usuarios con licencia.  </li>
</ul>
<li>  Sistema telefónico:
<ul>
<li>  Configuración de la organización para los parámetros predeterminados de voz en la nube.  </li>
<li>  Guía de planes de llamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponibles</a>):
<ul>
<li>  Asignación de números a usuarios con licencia.  </li>
<li>  Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.  </li>
<li>  Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.  </li>
</ul></li>
<li>  Guía de enrutamiento directo:
<ul>
<li>  Guía de configuración de la organización para el diseño de enrutamiento directo de escenarios hospedados por asociados o escenarios implementados por el cliente para un máximo de 10 sitios.  </li>
<li> Revisión de la configuración del controlador de borde de sesión (SBC). </li>

<li> Asistencia remota con la configuración del plan de marcado. </li>

<li> Configuración de la ruta de voz.</li>

<li> Omisión de medios y optimización de medios locales. </li>

</ul></li>
</ul></li>
<li>  Habilitar eventos en directo en Teams  </li>
<li>  Configuración e integración de la organización en Microsoft Stream.  </li>
<li>  Guía para la transición de Skype empresarial a teams.  </li>
</ul></td>
<td><ul>
<li>  Identidades habilitadas en Azure AD para Office 365.  </li>
<li>  Usuarios habilitados para SharePoint Online.  </li>
<li>  Los buzones de Exchange están presentes (en línea y local en una configuración híbrida de Exchange).  </li>
<li>  Habilitado para Grupos de Office 365.  </li>
</ul>
  <strong>Nota:</strong> Si los usuarios no están asignados ni habilitados con licencias de SharePoint Online, no tendrán almacenamiento de OneDrive para la empresa en Office 365. El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin el almacenamiento de OneDrive para la empresa en Office 365. Teams no es compatible con SharePoint local.  <br>
  <strong>Nota:</strong> El estado ideal es que todos los usuarios tengan sus buzones hospedados en Exchange Online. Los usuarios con buzones de correo hospedados de forma local deben tener sus identidades sincronizadas con el directorio de Office 365 mediante Azure AD Connect. Para estos clientes híbridos de Exchange, si el buzón de correo del usuario es local, el usuario no puede agregar ni configurar conectores.  
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
<td>Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</td>
</tr>
<tr class="even">
<td><strong>Outlook para iOS y Android</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Descargar Outlook para iOS y Android desde la App Store de Apple y Google Play.  </li>
<li>  Configurar cuentas y acceder al buzón de Exchange Online.  </li>
<li>  Securing Outlook Mobile (consulte <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">protección de Outlook para iOS y Android en Exchange Online</a> para obtener más información).  </li>
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
<td>El software cliente en línea, como Power BI Desktop, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</td>
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
<td>El software cliente en línea, como Project para Office 365, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</td>
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
<td>El software cliente en línea, como Project para Office 365, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</td>
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
Se proporcionan instrucciones adicionales para OneDrive para la empresa en función de la versión de SharePoint, como:
<ul>
<li>  Identificación de las opciones de integración y revisión del ancho de banda y la infraestructura de red local y en línea.  </li>
<li>  Instalación de SharePoint Online 2013 SP1 (si procede), planeamiento e implementación de los requisitos de sincronización e identidad e identificación del cliente de sincronización de OneDrive para la empresa.  </li>
<li>  Planeación e implementación de un solo lanzamiento para todos los usuarios (o un lanzamiento por fases).  </li>
<li>  Asignar licencias, redirigir mis sitios y bibliotecas de documentos personales a Office 365 (aplicable a SharePoint Online 2013), configurar audiencias para controlar el acceso a OneDrive (aplicable a SharePoint Online 2013).  </li>
<li>Redirigir o mover carpetas conocidas a OneDrive.</li>
<li>  Implementación de la sincronización de clientes de OneDrive para la empresa.  </li>
</ul>
  <strong>Migración de datos</strong>  <br>
Para obtener información sobre cómo usar el beneficio de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">migración de datos</a>.
</ul></td>
<td><br><strong>Para entornos híbridos de SharePoint:</strong>  
<ul>
<li>  La configuración híbrida de SharePoint incluye la configuración de la búsqueda híbrida, los sitios, la taxonomía, los tipos de contenido, OneDrive para la empresa, un iniciador de aplicaciones extendido, sitios de extranet y la creación de sitios sin servicio conectado de forma local a un entorno de SharePoint Online de destino único.  </li>
</ul>
  <strong>Nota:</strong> La creación de sitios sin servicio está en el ámbito de los servidores locales que ejecutan SharePoint 2013.  
<ul>
<li>  Para habilitar el entorno híbrido de SharePoint, debe disponer de uno de los siguientes entornos de SharePoint Server locales: 2013, 2016 o 2019.  </li>
</ul>
  <strong>Nota:</strong> La actualización de entornos de SharePoint local a SharePoint Server no se encuentra en el ámbito. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda. Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">niveles mínimos de actualización pública para las características híbridas de SharePoint</a><em>.</em>  <br>
  <strong>Nota:</strong> Para obtener información sobre las funciones multigeográficas, consulte <a href="https://go.microsoft.com/fwlink/?linkid=831056">multigeográfico Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Proporcionamos instrucciones remotas para habilitar el servicio Yammer Enterprise.  
</ul></td>
<td>El software de cliente en línea debe tener un nivel mínimo, como se define en los <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de la guía de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></td>
<td>  Proporcionamos una orientación remota para proteger sus identidades de nube en los siguientes escenarios.  

 <br/>

<strong>Infraestructura de base segura</strong>  </ul>
<ul>
<li>  Configuración y habilitación de la autenticación segura para sus identidades, incluida la protección con Azure multi-factor Authentication (MFA) (solo nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseña de autoservicio (SSPR).  </li>
<li>  Para clientes que no son de Azure Premium, se proporciona orientación para proteger las identidades mediante los valores predeterminados de seguridad.  </li>
<li>  Para los clientes de Azure AD Premium, se proporciona orientación para proteger las identidades con acceso condicional.  </li>
<li>  Detección y bloqueo del uso de contraseñas débiles con la protección con contraseña de Azure AD.  </li>
<li>  Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.  </li>
<li>  Habilitación de la detección y corrección basada en riesgos con Azure Identity Protection.  </li>
<li>  Habilitación de una pantalla de inicio de sesión personalizada, que incluye logotipos, texto e imágenes con personalización de marca.  </li>
<li>  Comparta de forma segura aplicaciones y servicios con usuarios invitados mediante la B2B de Azure AD.  </li>
<li>  Administración del acceso para los administradores de Office 365 mediante funciones administrativas integradas de control de acceso basado en roles (RBAC) y para reducir el número de cuentas de administrador con privilegios.  </li>
<li>  Configurar una Unión híbrida de Azure AD.  </li>
<li>  Configurando Azure AD join.  </li>
</ul>
  
<strong>Supervisión y generación de informes</strong>  
<ul>
<li>  
  Habilitación de la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Empresarial</strong>  
<ul>
<li>  
  Administrar su ciclo de vida de identidad y acceso de Azure AD a escala con la administración de derechos de Azure AD.
  </li>
<li>  
  Administrar la pertenencia a grupos de Azure AD, el acceso de la aplicación empresarial y las asignaciones de roles con las revisiones de acceso de Azure AD.  
  </li>
<li>  
  Revisión de los términos de uso de Azure AD.  
  </li>
<li>  
  Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatización y eficiencia </strong>  
<ul>
<li>  
  Habilitación de Azure AD SSPR.  
  </li>
<li>  Permitir a los usuarios crear y administrar sus propios grupos de seguridad en la nube u Office 365 con la administración de grupos de autoservicio de Azure AD.  </li>
<li>  Administración del acceso delegado a las aplicaciones empresariales con la administración de grupos delegados de Azure AD.  </li>
<li>  Habilitación de grupos dinámicos de Azure AD.  </li>
<li>  Organizar aplicaciones en el portal de mis aplicaciones mediante colecciones  </li>
</ul></td>
<td>La implementación local de Active Directory y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con Azure AD y las características de Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Activar y configurar el inquilino.  </li>
<li>  Crear y configurar etiquetas y directivas.  </li>
<li>  Aplicar la protección de la información a documentos.  </li>
<li>  Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.  </li>
<li>  Detectar y etiquetar archivos en reposo con el escáner de Azure Information Protection.  </li>
<li>  Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.  </li>
</ul>
También le ofrecemos instrucciones para aplicar la protección con Microsoft Azure Rights Management Services (Azure RMS), el cifrado de mensajes de Office 365 (OME) y la prevención de pérdida de datos (DLP).  </td>
<td>  Las responsabilidades de requisitos previos del cliente incluyen:
<ul>
<li>  Una lista de ubicaciones de recursos compartidos de archivos que se examinarán.  </li>
<li>  Una taxonomía de clasificación aprobada. </li>
<li> Comprensión de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.  </li>
<li>  Una cuenta de servicio creada para su Active Directory local que se haya sincronizado con Azure AD. </li>
<li>  Etiquetas configuradas para clasificación y protección. </li>
<li> Todos los requisitos previos para el analizador de Azure Information Protection están en su ubicación. Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">requisitos previos para instalar e implementar el escáner de etiquetación unificada de Azure Information Protection</a>. </li>
<li>  Asegúrese de que los dispositivos de usuario ejecutan un sistema operativo compatible y tienen instalados los requisitos previos necesarios. Consulte lo siguiente para obtener más información.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetación unificada de Azure Information Protection para los usuarios</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </li>
</ul>
<li> Instalación y configuración del conector y los servidores de Azure RMS, incluido el conector de Active Directory RMS (AD RMS) para la compatibilidad con entornos híbridos.  </li>
<li> Instalación y configuración de traer su propia clave (BYOK), cifrado de doble clave (DKE) (solo cliente de etiquetado unificado) o mantenga su propia clave (HYOK) (solo cliente clásico) en caso de que necesite una de estas opciones para la implementación.  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Proporcionamos instrucciones remotas para prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos. Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles. Los pasos pueden incluir:
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que se usarán en Intune aprovechando las identidades locales de Active Directory o de la nube (Azure AD).  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Configurar la autoridad de MDM, en función de las necesidades de administración, entre las que se incluyen:
<ul>
<li>  Establecer Intune como entidad MDM cuando Intune es la única solución MDM.  </li>
</ul></li>
<li>  Proporcionar instrucciones de MDM para:
<ul>
<li>  Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.  </li>
<li>  Configurar servicios y directivas de administración de MDM como:
<ul>
<li>  Implementación de aplicaciones para cada plataforma admitida a través de vínculos Web o vínculos profundos.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tiene una entidad de certificación, una red inalámbrica o una infraestructura de VPN en su organización.  </li>
<li>  Conexión al almacén de datos de Intune.  </li>
<li>  Integrar Intune con:
<ul>
<li>  Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).  </li>
<li>  Soluciones de asociados de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).  </li>
<li>  Una solución de administración de gastos de telecomunicaciones (es necesaria una suscripción a la solución de administración de gastos de telecomunicaciones).  </li>
<li>  ATP de Microsoft defender (se necesitan licencias de Windows E5 o Microsoft 365 E5).  </li>
</ul></li>
<li>  Inscribir dispositivos de cada plataforma compatible en Intune.  </li>
</ul></li>
</ul></li>
<li>  Proporciona instrucciones de protección de aplicaciones en:
<ul>
<li>  Configurar directivas de protección de aplicaciones para cada plataforma compatible.  </li>
<li>  Configuración de directivas de acceso condicional para aplicaciones administradas.  </li>
<li>  Dirigirse a los grupos de usuarios apropiados con las directivas de MAM mencionadas anteriormente.  </li>
<li>  Uso de informes de uso de aplicaciones administradas.  </li>
</ul></li>
<li>  Proporciona instrucciones de migración desde la administración de equipos heredados a Intune MDM.  </li>
</ul>
  <strong>Nota</strong>: la administración de equipos heredados ya no se admite desde el 15 de octubre de 2020 en adelante.  
</li>
</ul>
  
<strong>Conexión a la nube</strong>  

  Le guiamos a través de la preparación para hospedar en la nube entornos de Configuration Manager existentes con Intune. Los pasos detallados dependen del entorno de origen. Los pasos pueden incluir:  
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Proporciona instrucciones sobre cómo configurar la Unión híbrida de Azure AD.  </li>
<li>  Proporciona instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar Cloud Management Gateway.  </li>
<li>  Configurar cargas de trabajo compatibles que quiera cambiar a Intune.  </li>
<li>  Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.  </li>
</ul> 

<strong>Implementar Outlook Mobile para iOS y Android de manera segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook Mobile para iOS y Android de forma segura en su organización para asegurarse de que los usuarios tengan instaladas todas las aplicaciones necesarias.  
  Los pasos para implementar de forma segura Outlook Mobile para iOS y Android con Intune dependen de su entorno de origen. Puede incluir:
<ul>
<li>  Descargar las aplicaciones Outlook para iOS y Android, autenticador de Microsoft y portal de empresa de Intune a través de la App Store de Apple o Google Play Store.  </li>
<li>  Proporciona instrucciones para configurar:
<ul>
<li>  La implementación de las aplicaciones de Outlook para iOS y Android, el autenticador de Microsoft y el portal de empresa de Intune con Intune.  </li>
<li>  Directivas de protección de aplicaciones.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Directivas de configuración de la aplicación.  </li>
</ul></li>
</ul>
  
  <strong>Nota</strong>: FastTrack no es compatible con la protección de Outlook para iOS y Android con las directivas de buzón de correo de dispositivo móvil de Exchange. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.  
  </td>
<td>  Los administradores de TI deben contar con una entidad de certificación, una red inalámbrica y unas infraestructuras VPN existentes en sus entornos de producción al planear la implementación de perfiles de red inalámbrica y VPN con Intune.  
  <strong>Nota</strong>: el beneficio del servicio FastTrack no incluye asistencia para configurar o configurar entidades de certificación, redes inalámbricas, infraestructuras VPN o certificados push de Apple para Intune.  
 
  <strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.

  <strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong> 
 
  <strong>Nota</strong>: proporcionamos asistencia sobre la integración de Intune con Microsoft defender ATP y la creación de directivas de cumplimiento de dispositivos basadas en su evaluación de nivel de riesgo de Windows 10. No proporcionamos asistencia sobre la compra, concesión de licencias o activación. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.  
  
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
<th><strong>Detalles de la guía de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Proporcionamos instrucciones para la actualización de Windows 7 Professional y Windows 8,1 Professional a Windows 10 Enterprise.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Comprender su intención de Windows 10.  </li>
<li>  Evaluar el entorno de origen y los requisitos (Asegúrese de que el administrador de configuración de Microsoft Endpoint se actualiza al nivel requerido para admitir la implementación de Windows 10).  </li>
<li>  Implementación de aplicaciones de Windows 10 Enterprise y Microsoft 365 con Microsoft Endpoint Configuration Manager o Microsoft 365.  </li>
<li>  Recomendar opciones para evaluar las aplicaciones de Windows 10.  </li>
<li>  Habilitación del uso de análisis de escritorio y orientación mediante la creación de un plan de implementación de análisis de escritorio.  </li>
<li>  Evaluación de la compatibilidad de las aplicaciones de Microsoft 365 aprovechando el panel de preparación de Office 365 en Configuration Manager o con el kit de herramientas de preparación independiente para Office más asistencia para la implementación de aplicaciones de Microsoft 365.  </li>
<li>  Crear una lista de comprobación de corrección sobre lo que debe hacer para llevar el entorno de origen a los requisitos mínimos para una implementación correcta.  </li>
<li>  Proporciona instrucciones de actualización para los dispositivos existentes a Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesario.  </li>
<li>  Proporcionar instrucciones de actualización para apoyar el movimiento de implementación existente. FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10. Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.  </li>
<li>  Implementación de aplicaciones de Microsoft 365 con Configuration Manager como parte de la implementación de Windows 10.   </li>
<li>  Proporcionan instrucciones para ayudar a su organización a mantenerse al día con las aplicaciones de Windows 10 Enterprise y Microsoft 365 usando su entorno de Configuration Manager existente o Microsoft 365.  </li>
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
Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.  </td>
<td>  Para actualizar su PC, debe cumplir con estos requisitos:
<ul>
<li>  SO de origen: Windows 7 Enterprise o Professional, Windows 8,1 Enterprise o Professional.  </li>
<li>  Dispositivos: formato de escritorio, portátil o tableta.  </li>
<li>  SO de destino: window 10 Enterprise.  </li>
</ul>
Para actualizar la infraestructura, debe cumplir con estos requisitos:
<ul>
<li>  Administrador de configuración de Microsoft Endpoint.  </li>
<li>  La versión de destino de Windows 10 debe admitir la versión del administrador de configuración. Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Soporte para Windows 10 en Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></td>
<td>  La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Implementación de las tecnologías para proteger los extremos.  </li>
<li>  Configuración de Endpoint Protection y los perfiles de restricción de dispositivos.  </li>
<li>  Evaluación de la versión del sistema operativo y la administración de dispositivos (incluidos Intune, el administrador de configuración de Microsoft Endpoint, los objetos de directiva de grupo (GPO) y las configuraciones de terceros), así como el estado de los servicios de AV de Windows Defender u otro software de seguridad de extremos.  </li>
<li>  Evaluar el estado de los servicios de Windows AV o de otro software de seguridad de extremo.  </li>
<li>  Evaluar los servidores proxy y los firewalls restringir el tráfico de red.  </li>
<li>  Habilitar el servicio ATP de Microsoft defender mediante la explicación de cómo implementar un perfil de agente ATP con un punto de conexión incorporado.  </li>
<li>  Guía de implementación, asistencia para la configuración y educación en:
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
<li>  Revisión de simulaciones y tutoriales (como escenarios de prácticas, malware falsificado e investigaciones automatizadas).  </li>
<li>  Información general sobre las características de informes y de análisis de amenazas.  </li>
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
  Canal de Semi-Annual de Windows Server (SAC) versión 1803.  
  </li>
<li>  
  macOS versiones 10,13, 10,14 y 10,15.  
  </li>
</ul>
</li>
</ul>
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse con la versión más reciente del administrador de configuración de System Center 2012 (versiones 1012 R2, 1511 o 1602) o el administrador de configuración de Microsoft Endpoint (versión 2002 o posterior). 

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
  Configuración de un servidor proxy para las comunicaciones sin conexión.  
  </li>
<li>  
  Configuración de paquetes de implementación de Configuration Manager en instancias y versiones de administrador de configuración de nivel inferior.  
  </li>
<li>  
  Servidores de incorporación a Azure Security Center.  
  </li>
<li>  
  Servidores no administrados por Configuration Manager.  
  </li>
</ul></li>
<li>  incorporación y configuración de macOS:
<ul>
<li>  
  Implementación manual basada en la Intune.  
  </li>
<li>  
  Implementación basada en JAMF.
  </li>
<li>  
  Otra implementación basada en producto de administración de dispositivos móviles (MDM).  
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
<li>  Configuración o formación que revisan la API o la información de seguridad y las conexiones de administración de eventos (SIEM).  </li>
<li>  Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).  </li>
<li>  Aprendizaje o instrucciones sobre la búsqueda avanzada.  </li>
<li>  Formación o orientación sobre el uso o la creación de consultas Kusto.</li>
</li>
</ul>
Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de la guía de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows Virtual Desktop</strong></td>
<td><p>Proporcionamos una guía de implementación para la incorporación a escritorio virtual de Windows (un servicio de virtualización de aplicaciones y de escritorio). El escritorio virtual de Windows aprovecha la experiencia de varias sesiones de Windows 10 y está optimizado para Microsoft 365 apps for Enterprise con Integrated Security and Management for Microsoft 365.</p>
<p>Proporcionamos instrucciones remotas para:</p>
<ul>
<li>Implementar el entorno de escritorio virtual de Windows con la sesión múltiple de Windows 10 Enterprise y las aplicaciones de Microsoft 365 para empresas mediante lo siguiente:
<ul>
<li>Imagen de Azure Marketplace.</li>
<li>Imagen compartida.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Configuración de FSLogix:
<ul>
<li>Implementación del agente de FSLogix con el contenedor de perfiles.</li>
<li>Implementación del agente de FSLogix con el contenedor de Office.</li>
<li>Configuración de la carpeta FSLogix con exclusiones de contenido.</li>
</ul></li>
<li>Implementación de Microsoft Edge.</li>
<li>Implementación de Microsoft Teams.</li>
<li>Conexión mediante los clientes de escritorio virtuales de Windows.</li>
</ul>

<strong>Lo siguiente está fuera del ámbito</strong>
<ul>
<li>Administración de proyectos de la implementación de escritorio virtual de Windows del cliente.</li>
<li>Virtualización e implementación de aplicaciones de terceros.</li>
<li>Imágenes personalizadas.</li>
<li>Migraciones y escenarios que implican VMware y Citrix.</li>
<li>Escenarios de Linux.</li>
<li>Conversión o migraciones de perfiles de usuario.</li>
</ul>
Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.</td>
<td>Ya debe tener lo siguiente:
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licencia de escritorio virtual de Windows</a>.</li>
<li>Redes de Azure:
<ul>
<li>Creación y subredes de la red virtual (VNET).</li>
<li>Grupos de seguridad de red y firewall.</li>
<li>VPN y ExpressRoute.</li>
<li>Enrutamiento a Azure desde el sistema local.</li>
<li>Reglas de Firewall para permitir la conectividad con el escritorio virtual de Windows.
</ul>
Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> clientes de escritorio remoto compatibles</a>.
</ul>
<ul><li>Configuración general de Azure AD:
<ul>
<li>Estrategia <i>de identidad (solo puede usar una de las tres opciones siguientes):</i>
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
<th><strong>Detalles de la guía de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Asesoría de aplicaciones</strong></td>
<td>  La aplicación garantiza un servicio diseñado para solucionar problemas con Windows 10 y la compatibilidad de aplicaciones de Microsoft 365. Cuando solicite a la aplicación garantizar el servicio, trabajamos con usted para solucionar problemas de aplicación válidos sin costo adicional para usted con una suscripción elegible. También ofrecemos orientación a los clientes que se enfrentan a problemas de compatibilidad al implementar el escritorio virtual de Windows y el nuevo Microsoft Edge, y hacer cada uno de los esfuerzos razonables para resolver problemas de compatibilidad. Proporcionamos asistencia de corrección para las aplicaciones implementadas en los siguientes productos de Microsoft:
<ul>
<li>  <strong>Windows 10 </strong> (incluidos los dispositivos ARM64)</li>
<li> <strong>Aplicaciones de Microsoft 365</strong>  </li>
<li>  <strong>El nuevo Microsoft Edge-</strong> Para obtener instrucciones de implementación, vea <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">información general de los canales de Microsoft Edge</a>.  </li>
<li>  Escritorio virtual de <strong>Windows</strong> - Para obtener más información, vea <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">¿Qué es el escritorio virtual de Windows?</a> y <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">preguntas más frecuentes sobre la sesión múltiple de Windows 10 Enterprise</a>.  </li>
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


  Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.  </td>

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
Las aplicaciones que funcionaban en Windows 7, Office 2010 o versiones posteriores también funcionan en aplicaciones de Windows 10 y Microsoft 365 en dispositivos ARM64. 
  </li>
</ul>
  <strong>Note</strong> 
<ul>
<li> la emulación de x64 (64 bits) está disponible en versión preliminar para los clientes que participan en el <a href="https://insider.windows.com/">programa Windows Insider</a>.  </li>
<li>  
 Para los clientes que no usan Windows Insider en Windows 10 versión 2004 (o posterior), ARM64 de Photoshop es compatible con el <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">paquete de compatibilidad de OpenCL y OpenGL</a>. 
  </li>
<li>  
  Los clientes del programa Windows Insider pueden descargar una versión Insider del paquete de compatibilidad de OpenCL y OpenGL para usar con aplicaciones adicionales.    
  </li>
</ul>
<strong>El nuevo Microsoft Edge</strong>
<ul>
<li>  
  Si sus aplicaciones web o sitios funcionan en Internet Explorer 11, en versiones compatibles de Google Chrome o en cualquier versión de Microsoft Edge, también funcionarán con el nuevo Microsoft Edge.  
  </li>
<li>  
  A medida que la web evolucione en todo momento, asegúrese de revisar esta lista publicada de <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">los cambios que afectan a la compatibilidad de sitios conocidos para Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Escritorio virtual de Windows </strong>  
<ul>
<li>  
  Las aplicaciones virtualizadas que se ejecutan en el host de sesión de Escritorio remoto (RDSH) de Windows Server también se ejecutan en Windows 10 Enterprise multisesión como parte de Windows Virtual Desktop.  
  </li>
<li>  
  Las aplicaciones que se ejecutan en cualquier entorno de infraestructura de escritorio virtual (VDI) de Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte del escritorio virtual de Windows.  
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

## <a name="the-new-microsoft-edge"></a>El nuevo Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de la guía de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> (para clientes de Windows 10 Enterprise)</td>
<td><ul>
<li>  Proporcionamos una guía de implementación remota y asistencia de compatibilidad para: implementar el nuevo Microsoft Edge en Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).  </li>
<li>  Configuración de Microsoft Edge (usando directivas de grupo o directivas de aplicación y configuración de aplicaciones de Intune).  </li>
<li>  Inventario la lista de sitios que pueden requerir uso en el modo de Internet Explorer.  </li>
<li>  Habilitación del modo de Internet Explorer con la lista de sitios de empresa existente.  
  Además, si tiene una aplicación web o un sitio que funciona con Internet Explorer o Google Chrome y experimenta problemas de compatibilidad, le proporcionamos instrucciones para resolver el problema sin coste adicional. Consulte <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">sure</a> de la aplicación para obtener más información.  </li>
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
