---
title: Productos y capacidades
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias antes de poder comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que haga que el entorno de origen se ajuste a los requisitos mínimos para una incorporación correcta.
ms.openlocfilehash: 56fe941acf3f5739802ac9065c843dbbc2f2525b
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592453"
---
# <a name="products-and-capabilities"></a>Productos y capacidades

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Servicios y escenarios admitidos por FastTrack 

En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias antes de poder comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que haga que el entorno de origen se ajuste a los requisitos mínimos para una incorporación correcta.

FastTrack proporciona instrucciones para ayudarle primero con las funcionalidades principales (comunes para todos los Microsoft Online Services) y luego con la incorporación de cada servicio elegible:

  - [General](#general)
  - [Seguridad y cumplimiento](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [App Assure](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Para obtener información sobre las expectativas de entorno de origen para Office 365 Administración Pública, vea [Expectativas de entorno de origen para Office 365 Administración Pública](/us-gov-appendix-source-environment-expectations). 
 
## <a name="general"></a>General

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
<td><strong>Incorporación principal</strong></td>
<td>  Proporcionamos instrucciones remotas sobre la incorporación principal, que implica el aprovisionamiento de servicios, el inquilino y la integración de identidades. También incluye pasos para proporcionar una base para la incorporación de servicios como Exchange Online, SharePoint Online y Microsoft Teams, incluida una discusión sobre [seguridad,](/office365/enterprise/office-365-network-connectivity-principles)conectividad de red y cumplimiento .  
  La incorporación de uno o más servicios elegibles puede empezar al finalizar la incorporación principal.
</li>
</ul>  

<strong> Integración de identidades </strong>

Proporcionamos instrucciones remotas para:
<ul>
<li>Preparación de identidades locales de Active Directory para la sincronización con Azure Active Directory (Azure AD), incluida la instalación y configuración de Azure AD Conectar (bosque único o múltiple) y licencias (incluidas las licencias basadas en grupos).</li>
<li>Creación de identidades en la nube, incluida la importación masiva y las licencias, incluido el uso de licencias basadas en grupos.</li>
<li>Elegir y habilitar el método de autenticación correcto para el recorrido en la nube, la sincronización hash de contraseña, la autenticación de paso a través o los servicios de federación de Active Directory (AD FS).</li>
<li> Elegir y habilitar una experiencia de autenticación más conveniente para los usuarios con autenticación sin contraseña (Fast Identity Online (FIDO)2 o Microsoft Authenticator App).</li>
<li>Habilitar AD FS para clientes con un único bosque de Active Directory e identidades sincronizadas con la herramienta de Conectar Azure AD. Esto requiere Windows Server 2012 R2 Active Directory Federation Services 2.0 o posterior.</li>
<li>Migrar la autenticación de AD FS a Azure AD mediante la sincronización hash de contraseña o la autenticación de paso a través.</li>
<li>Migración de aplicaciones preinstaladas (como aplicaciones saas) de software como servicio (SaaS) de la galería de Azure AD) de AD FS a Azure AD para el inicio de sesión único (SSO).</li>
<li>Habilitar integraciones de aplicaciones SaaS con SSO desde la galería de Azure AD.</li>
<li>Habilitar el aprovisionamiento automático de usuarios para aplicaciones SaaS integradas previamente, tal como se muestra en la lista de [tutoriales](/azure/active-directory/saas-apps/tutorial-list) de integración de aplicaciones (limitado a aplicaciones SaaS de la galería de Azure AD y aprovisionamiento saliente solamente).  </li>
</td>

<td>  <strong>Habilitación de red </strong>  
  <br>Como parte de las ventajas de FastTrack, le recomendamos que se informe de los procedimientos recomendados para conectarse a los servicios en la nube para garantizar los niveles más altos de rendimiento de Microsoft 365.  
  
<strong>Bosques de Active Directory</strong> Tienen el nivel de bosque funcional establecido en Windows Server 2003 en adelante, con la siguiente configuración de bosque:
<ul>
<li>  Un solo bosque de Active Directory.  </li>
<li>  Un solo bosque de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).  </li>
<li>  Varios bosques de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).  </li>
<li>  Varios bosques de cuentas de Active Directory con uno de los bosques que es un bosque de cuentas de Active Directory centralizado que incluye Exchange o Lync 2010, Lync 2013 o Skype Empresarial.  </li>
<li>  Varios bosques de cuentas de Active Directory, cada uno con su propia organización de Exchange.  </li>
<li>  Tareas necesarias para la configuración e integración del espacio empresarial con Azure Active Directory, si es necesario.   </li>
</ul>
  <strong>Importante</strong>  <ul>
<li>  Para escenarios de Active Directory con varios bosques, si se implementa Lync 2010, Lync 2013 o Skype Empresarial, debe implementarse en el mismo bosque de Active Directory que Exchange.  </li>
<li>  Al implementar varios bosques de Active Directory con varias organizaciones de Exchange en una configuración multi híbrido de Exchange, no se admiten espacios de nombres de nombre principal de usuario compartido (UPN) entre bosques de origen. Los espacios de nombres SMTP principales entre las organizaciones de Exchange también deben estar separados. Para más información, consulte <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implementaciones híbridas con varios bosques de Active Directory</a>.  </li>
<li>  Para todas las configuraciones de varios bosques, la implementación de Servicios de federación de Active Directory (AD FS) está fuera del ámbito. Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.  </li>
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
  Además, si tienes una macro o complemento que funcionaba con versiones anteriores de Office y experimentas problemas de compatibilidad, proporcionamos instrucciones para corregir el problema de compatibilidad sin costo adicional a través del programa App Assure. Consulta la <strong>parte de App Assure</strong> de <a href="#windows-10">Windows 10</a> para obtener más detalles. </li>
</ul></td>
<td><ul>
<li>  El software cliente en línea debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Estado de la red</strong></td>
<td>  Proporcionamos instrucciones remotas para obtener e interpretar datos clave de conectividad de red de su entorno que muestran cómo se alinean los sitios de su organización con los [principios](/office365/enterprise/office-365-network-connectivity-principles)de conectividad de red de Microsoft. Esto resalta la puntuación de red que afecta directamente a la velocidad de migración, la experiencia del usuario, el rendimiento del servicio y la confiabilidad.  
  También le guiaremos a través de los pasos de corrección resaltados por estos datos para ayudarle a mejorar la puntuación de red.  </td>
<td><ul>
<li>  Microsoft 365 Acceso al Centro de administración.  </li>
<li>  Se requieren versiones actualizadas de Microsoft 365 aplicaciones.  </li>
<li>  Servicios de ubicación habilitados según las recomendaciones de rendimiento de red [en el Centro Microsoft 365 administración (versión preliminar).](/Office365/Enterprise/office-365-network-mac-perf-overview)  </li>
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
<th><strong>Detalles de instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></td>
<td>  Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.  

 <br/>

<strong>Infraestructura básica segura</strong>  </ul>
<ul>
<li>  Configurar y habilitar una autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseñas sin servicio (SSPR).  </li>
<li> Implementación de FIDO2 o Microsoft Authenticator app. </li>
<li>  Para clientes que no son de Azure AD Premium, se proporcionan instrucciones para proteger las identidades mediante valores predeterminados de seguridad.  </li>
<li>  Para los clientes premium de Azure AD, se proporcionan instrucciones para proteger sus identidades con acceso condicional.  </li>
<li>  Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.  </li>
<li>  Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.  </li>
<li>  Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.  </li>
<li>  Habilitar una pantalla de inicio de sesión personalizada, incluidos logotipo, texto e imágenes con personalización de marca personalizada.  </li>
<li>  Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.  </li>
<li>  Administrar el acceso de los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.  </li>
<li>  Configuración de la unión híbrida de Azure AD.  </li>
<li>  Configuración de la unión a Azure AD.  </li>
</ul>
  
<strong>Supervisión e informes</strong>  
<ul>
<li>  
  Habilitar la supervisión remota para AD FS, Azure AD Conectar y controladores de dominio con Azure AD Conectar Health.  
  </li>
</ul>
  
<strong>Gobierno</strong>  
<ul>
<li>  
  Administrar la identidad de Azure AD y el ciclo de vida de acceso a escala con la administración de derechos de Azure AD.
  </li>
<li>  
  Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.  
  </li>
<li>  
  Revisión de los Términos de uso de Azure AD.  
  </li>
<li>  
  Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatización y eficiencias </strong>  
<ul>
<li>  
  Habilitar Azure AD SSPR.  
  </li>
<li>  Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos Office 365 con la administración de grupos de autoservicio de Azure AD.  </li>
<li>  Administrar el acceso delegado a aplicaciones empresariales con la administración de grupos delegada de Azure AD.  </li>
<li>  Habilitar grupos dinámicos de Azure AD.  </li>
<li>  Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.  </li>
</ul></td>
<td>Active Directory local y su entorno se han preparado para azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Para obtener más información sobre Azure Information Protection, consulte <strong>Microsoft Information Protection</strong> más adelante en esta tabla.

  </td>
<td>  
  <tr class="odd">
<td><strong>Descubrir & responder</strong></td>
<td>  

<strong>eDiscovery avanzado</strong>
  
Proporcionamos instrucciones remotas para: 
<ul>
<li>  Crear un nuevo caso.   </li>
<li>  Poner a los custodios en espera.  </li>
<li>  Realizar búsquedas. </li>
<li>  Agregar los resultados de búsqueda a un conjunto de revisión. </li>
<li>  Ejecutar análisis en un conjunto de revisión.  </li>
<li>  Revisar y etiquetar documentos.  </li>
<li>  Exportar datos desde el conjunto de revisión. </li>
<li>  Importar datos que no Office 365 datos. </li>
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
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>

<tr class="odd">
<td><strong>Administración de riesgos de Insider</strong></td>

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
<li> Creación y administración de Power Automate flujos.</li>
<li> Conectores de datos (más allá del conector de RECURSOS HUMANOS). </li>
<li> Configuraciones de expresiones regulares personalizadas (RegEx).</li>
<li> Diseño, arquitecto y revisión de documentos de terceros.</li>
<li> Barreras de información.</li>
<li> Administración de acceso con privilegios.</li>
<li> Cumplimiento de las normativas y requisitos regionales y del sector.</li>
<li> Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</li>
</ul></td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender es un conjunto unificado de defensa empresarial anterior y posterior a la infracción que coordina de forma nativa la detección, prevención, investigación y respuesta entre puntos de conexión, identidades, correo electrónico y aplicaciones para proporcionar protección integrada contra ataques sofisticados. Proporcionamos instrucciones remotas para: </p> 
<ul>
<li>  Proporciona información general sobre el centro Microsoft 365 seguridad.  </li>
<li>  Revisión de incidentes entre productos, incluido el centrarse en lo que es fundamental al garantizar el ámbito de ataque completo, los activos afectados y las acciones de corrección automatizadas que se agrupan.  </li>
<li>  Demostración de cómo Microsoft 365 Defender puede organizar la investigación de activos, usuarios, dispositivos y buzones que podrían haber sido comprometidos a través de la recuperación automática. </li>
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
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una amplia visibilidad, control sobre el viaje de datos y análisis sofisticados para identificar y combatir las amenazas cibernéticas en todos los servicios en la nube de Microsoft y de terceros. Proporcionamos instrucciones remotas para:
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
<li> Conectar [aplicaciones características con](/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps) conectores de aplicaciones.</li>
<li> Configurar el control de aplicaciones de acceso condicional en los portales de acceso condicional y Cloud App Security para aplicar controles de sesión en tiempo real.</li>
<li> Implementar los paneles Cloud App Security y Cloud Discovery.</li>
<li> Personalizar las puntuaciones de riesgo de la aplicación en función de las prioridades de la organización.</li>
<li> Crear etiquetas y categorías de aplicaciones.</li>
<li> Sancionar y deshacer la autorización de aplicaciones.</li>
<li> Uso de la actividad y los registros de archivos.</li>
<li> Administrar aplicaciones de OAuth.</li>
<li> Descripción de la correlación de incidentes en el portal Microsoft 365 Defender.</li>
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
<li> Investigación y corrección automatizadas, incluidos los libros Power Automate Microsoft.</li>
<li> Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</li>
<li> Implementar la detección de aplicaciones en la nube como una prueba de concepto.</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender para punto de conexión</strong></td>
<td>  Microsoft Defender para endpoint es una plataforma diseñada para ayudar a las redes empresariales a prevenir, detectar, investigar y responder a amenazas avanzadas.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Implementar las tecnologías para proteger los puntos de conexión.  </li>
<li>  Configuración de perfiles de restricción de dispositivos y protección de puntos de conexión.  </li>
<li>  Evaluar la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios antivirus de Windows Defender u otro software de seguridad de puntos de conexión.  </li>
<li>  Evaluar el estado de su Windows antivirus u otro software de seguridad de extremo.  </li>
<li>  Evaluación de servidores proxy y firewalls que restringen el tráfico de red.  </li>
<li>  Para habilitar el servicio microsoft defender para puntos de conexión, se explica cómo implementar un perfil de agente de Defender for Endpoint mediante un extremo integrado.  </li>
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
<li>  Integración de Microsoft Defender para Office 365 con Microsoft Defender para endpoint.  </li>
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
<li>  Incorporación o configuración de los siguientes agentes de Microsoft Defender para endpoints:
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
<li> Infraestructura de escritorio virtual (VDI) (persistente o no persistente).  </li>
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
<li> Control de dispositivo.</li>
<li>  
  Protección contra vulnerabilidades de seguridad.  
  </li>
<li>  
  Firewall de red.  
  </li>



</ul></li>
<li> Configuración o administración de características de protección de cuentas como: </li>
<ul>

<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>
<li> Configuración o administración de BitLocker.</li>
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
<li>  Implementar el sensor para capturar y analizar el tráfico de red y Windows eventos directamente desde los controladores de dominio, incluidos: </li>
<ul> 
<li>  Descargar el paquete del sensor. </li>
<li>  Configuración del sensor. </li>
<li>  Instalar el sensor en el controlador de dominio de forma silenciosa. </li>
<li>  Implementar el sensor en el entorno de varios bosques. </li>
</ul>
<li>  Integración de Defender for Identity con Microsoft Cloud App Security (Cloud App Security no es necesaria la licencia). </li>
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
<li> Windows Servidor 2019 con KB4487044 (compilación del sistema operativo 17763.316).</li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><strong>Microsoft Defender para Office 365</strong></td>
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
<td><strong>Gobierno de información de Microsoft</strong></td>

<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Crear y publicar directivas y etiquetas de retención (solo se admiten en E5).  
</li>
<li>  Administración de registros (solo se admite en E5).  </li>
<ul><li>  Revisión de la creación del plan de archivos. </li>
<li>  Crear y administrar registros (incluidos los registros basados en eventos).  </li>
<li>  Revisión de la disposición. </ul> </li>
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
<li> Desarrollo de un plan de archivos de administración de registros.</li>
<li> Conectores de datos.</li>
<li> Desarrollo de la arquitectura de la información en SharePoint.</li>
<li> Scripting y codificación personalizados.</li>
<li> Diseño, arquitecto y revisión de documentos de terceros.</li>
<li> Compatibilidad con E3.</li>
<li> Cumplimiento de las normativas y requisitos regionales y del sector.</li>
<li> Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</li>
</ul>

</td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</td>
</tr>
<tr class="odd">
<td><strong>Protección de la información de Microsoft</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Clasificación de datos (compatible con E3 y E5).  </li>
<li>  Tipos de información confidencial (compatibles con E3 y E5).  </li>
<li>  Crear etiquetas de confidencialidad (admitidas en E3 y E5).  </li>
<li>  Aplicar etiquetas de confidencialidad (compatibles con E3 y E5).  </li>
<li>  Clasificadores entrenables (admitidos en E5).  </li>
<li>  Conocer los datos con el explorador de contenido y el explorador de actividades (compatible con E5).  </li>
<li>  Publicar etiquetas con directivas (manual y automática) (admitidas en E5).  </li>
<li>  Crear directivas de prevención de pérdida de datos de extremo (DLP) para Windows 10 dispositivos (compatibles con E5).  </li>
<li>  Crear directivas DLP para Microsoft Teams chats y canales.  </li>
</ul>

<strong> Administrador de cumplimiento</strong>

Proporcionamos instrucciones remotas para:  

<ul> <li>Revisión de tipos de roles.  </li>
<li> Agregar y configurar evaluaciones.</li>
<li> Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</li>
<li> Revisión de controles integrados de asignación y evaluación de controles.</li>
<li> Generar un informe dentro de una evaluación.</li>
</ul>

<strong> Azure Information Protection</strong>

Proporcionamos instrucciones remotas para:  
<ul>
<li>  Activar y configurar el espacio empresarial.  </li>
<li>  Creación y configuración de etiquetas y directivas (compatibles con P1 y P2).  </li>
<li>  Aplicar protección de información a documentos (admitidos en P1 y P2).  </li>
<li>  Clasificar y etiquetar automáticamente la información en aplicaciones de Office (como Word, PowerPoint, Excel y Outlook) que se ejecutan en Windows y usan el cliente de Azure Information Protection (compatible con P2).  </li>
<li>  Detección y etiquetado de archivos en reposo con el escáner de Azure Information Protection (compatible con P1 y P2).  </li>
<li>  Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.  </li>
</ul>

  También proporcionamos instrucciones si desea aplicar protección mediante Microsoft Azure Rights Management Services (Azure RMS), Cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>Clave de cliente.</li>
<li>Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</li>
<li>Creación o modificación de diccionarios de palabras clave.</li>
<li>Scripting y codificación personalizados.</li>
<li> Azure Purview.</li>
<li> Diseño, arquitecto y revisión de documentos de terceros.</li>
<li> Cumplimiento de las normativas y requisitos regionales y del sector.</li>
<li> Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</li>
</ul>

<ul>

</td>
<td>Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema a excepción de Azure Information Protection.

<strong>Azure Information Protection</strong>

Las responsabilidades de requisitos previos del cliente incluyen:  
<ul>
<li>  Una lista de ubicaciones de recurso compartido de archivos que se examinarán.  </li>
<li>  Taxonomía de clasificación aprobada. </li>
<li> Descripción de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.  </li>
<li>  Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD. </li>
<li>  Etiquetas configuradas para clasificación y protección. </li>
<li> Todos los requisitos previos del escáner de Azure Information Protection están en su lugar. Para obtener más información, vea [Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner](/azure/information-protection/deploy-aip-scanner-prereqs). </li>
<li>  Asegúrese de que los dispositivos de usuario ejecuten un sistema operativo compatible y tengan instalados los requisitos previos necesarios. Vea lo siguiente para obtener más información.</li>
<ul>
<li> [Guía de administración: instalar el cliente de etiquetado unificado de Azure Information Protection para usuarios](/azure/information-protection/rms-client/clientv2-admin-guide-install)   </li>
<li>  [¿Qué es la aplicación de Azure Information Protection para iOS o Android?](/azure/information-protection/rms-client/mobile-app-faq)  </li>
</ul>
<li> Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para compatibilidad híbrida.  </li>
<li> Configuración y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado solamente) o Hold Your Own Key (HYOK) (solo cliente clásico) si necesita una de estas opciones para la implementación.  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) basado en la nube y administración de aplicaciones móviles (MAM) para sus aplicaciones y dispositivos. Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles. Los pasos pueden incluir:
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que Intune usará aprovechando las identidades locales de Active Directory o de la nube (Azure AD).  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Configuración de la entidad mdma, según tus necesidades de administración, incluidos:
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
<li>  Implementación de correo electrónico, redes inalámbricas y perfiles vpn si tiene una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en su organización.  </li>
<li>  Conexión al almacén de datos de Intune.  </li>
<li>  Integrar Intune con:
<ul>
<li>  Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).  </li>
<li>  Soluciones de partners de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).  </li>
<li>  Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción a una solución de administración de gastos de telecomunicaciones).  </li>

</ul></li>
<li>  Inscribir dispositivos de cada plataforma compatible en Intune.  </li>
</ul></li>
</ul></li>
<li>  Proporcionar instrucciones de protección de aplicaciones sobre:
<ul>
<li>  Configurar directivas de protección de aplicaciones para cada plataforma compatible.  </li>
<li>  Configurar directivas de acceso condicional para aplicaciones administradas.  </li>
<li>  Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.  </li>
<li>  Uso de informes de uso de aplicaciones administradas.  </li>
</ul></li>
<li>  Proporcionar instrucciones de migración desde la administración de equipos heredados a MDM de Intune.  </li>
</ul>
 
</li>
</ul>
  
<strong>Conexión a la nube</strong>  

  Le guiaremos para prepararse para adjuntar entornos de Configuration Manager existentes con Intune. Los pasos detallados dependen del entorno de origen. Los pasos pueden incluir:  
<ul>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Proporcionar instrucciones para configurar la unión híbrida de Azure AD.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.  </li>
<li>  Configurar cargas de trabajo compatibles que quiera cambiar a Intune.  </li>
<li>  Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.  </li>
</ul> 

<strong>Implementar Outlook móvil para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarte a implementar Outlook móvil para iOS y Android de forma segura en tu organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.  
  Los pasos para implementar de forma segura Outlook móvil para iOS y Android con Intune dependen del entorno de origen. Puede incluir:
<ul>
<li>  Descargar el Outlook para iOS y Android, Microsoft Authenticator y Portal de empresa de Intune aplicaciones a través de la Tienda de aplicaciones de Apple o Google Play Store.  </li>
<li>  Proporcionar instrucciones sobre cómo configurar:
<ul>
<li>  El Outlook para iOS y Android, Microsoft Authenticator y Portal de empresa de Intune de aplicaciones con Intune.  </li>
<li>  Directivas de protección de aplicaciones.  </li>
<li>  Directivas de acceso condicional.  </li>
<li>  Directivas de configuración de aplicaciones.  </li>
</ul></li>
</ul>  
  </td>
<td>  Los administradores de TI necesitan que las infraestructuras de vpn, red inalámbrica y entidad de certificación ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.  
  <strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar autoridades de certificados, redes inalámbricas, infraestructuras VPN o certificados de inserción mdm de Apple para Intune.  
 
  <strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube. Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.

  <strong>Intune integrado con Microsoft Defender para endpoint</strong> 
 
  <strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con Microsoft Defender para Endpoint y crear directivas de cumplimiento de dispositivos en función de su Windows 10 nivel de riesgo. No proporcionamos asistencia en compras, licencias o activación. Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.  
  
<strong>Windows Autopilot</strong> 
 
  Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a>Office 365

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
<td><strong>Exchange Online</strong></td>
<td>  Por Exchange Online, le guiaremos a través del proceso para que su organización esté lista para usar el correo electrónico. Los pasos exactos dependen del entorno de origen y de los planes de migración de correo electrónico.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Configuración de las características de Exchange Online Protection (EOP) para todos los dominios habilitados para correo que se han validado en Office 365.  </li>
<li>  Apuntar los registros de intercambio de correo (MX) a Office 365.  </li>
<li>  Configurar la característica de Microsoft Defender para Office 365 si forma parte del servicio de suscripción. Para obtener más información, consulte <strong>microsoft defender para obtener Office 365</strong> parte de esta tabla.  </li>
<li>  Configuración de la característica de prevención de pérdida de datos (DLP) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</li>
<li>  Configuración del cifrado de mensajes de Office 365 (OME) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</li>
</ul>
  <strong>Nota:</strong> El servicio de replicación de buzones de correo (MRS) intenta migrar correos electrónicos de Information Rights Managed (IRM) desde su buzón local al buzón de correo Exchange Online buzón de correo. La capacidad de leer el contenido protegido posterior a la migración dependerá de la asignación de clientes y la copia de las plantillas de Active Directory Rights Management Services (AD RMS) en el servicio Azure Rights Management (Azure RMS).  
<ul>
<li>  Configurar puertos del firewall.  </li>
<li>  Configuración de DNS, incluida la detección automática, el marco de directivas de remitente (SPF), el correo identificado de domainkeys (DKIM), la autenticación de mensajes basada en dominio, la creación de informes y la conformidad (DMARC) y los registros MX (según sea necesario).  </li>
<li>  Configuración del flujo de correo electrónico entre su entorno de mensajería de origen y Exchange Online (si procede).  </li>
<li>  Operación de migración de correo desde el entorno de mensajería de origen a Office 365.  </li>
<li>  Configuración de clientes de buzón (Outlook para Windows, Outlook en la web y Outlook para iOS y Android).  </li>
</ul>
  <strong>Migración de datos</strong>  <br>
Para obtener información sobre cómo usar la ventaja de FastTrack para la migración de datos a Office 365, vea [Data Migration](data-migration.md).   
<td>  El entorno de origen debe tener uno de los siguientes niveles mínimos:
<ul>
<li>  Una o varias organizaciones de Exchange a partir de Exchange Server 2003.  </li>
<li>  Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).  </li>
<li>  Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).  </li>
<li>  Para obtener información sobre las capacidades multige geográficas, vea <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.  </li>
</ul>
El software cliente en línea como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, cliente de sincronización de OneDrive para la Empresa, Power BI Desktop y Skype Empresarial deben estar en un nivel mínimo según se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos</a>del sistema para Microsoft 365 Office .  </td>
</tr>

<td><strong>Microsoft Defender para Office 365</strong></td>
<td>  Para obtener más información, vea <strong>Microsoft Defender for Office 365</strong> en Security and [Compliance](products-and-capabilities.md#security-and-compliance).  
</td>
<td></td>
</tr>


<tr class="even">
<td><strong>Gobierno de información de Microsoft</strong></td>
<td>  Para obtener más información, vea <strong> Microsoft Information Governance</strong> in Security and [Compliance](products-and-capabilities.md#security-and-compliance). 

</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Protección de la información de Microsoft</strong></td>
<td>  
Para obtener más información, vea <strong>Microsoft Information Protection </strong> in Security and [Compliance](products-and-capabilities.md#security-and-compliance).

</td>
<td>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Confirmar los requisitos mínimos en Exchange Online, SharePoint Online, Office 365 Grupos y Azure AD para admitir Teams.  </li>
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
<li>  Configuración de Teams de aplicaciones (Teams web, Teams de escritorio y Teams para iOS y android app).  </li>
</ul>
Si procede, también proporcionamos instrucciones para:
<ul>
<li>  Microsoft Teams Dispositivos de sala:  </li>
<ul>
<li>  Creación de cuentas en línea necesarias para los dispositivos de telefonía y salas de conferencias compatibles que aparecen en el <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos de Teams</a>.  </li>
<li>  Asistencia remota con la configuración del lado de servicio de dispositivos Salas de Microsoft Teams certificados.  </li>
<li>  Habilitar audioconferencia:  </li>
<li>  Parámetros predeterminados de la configuración de la organización para puente de conferencia.  </li>
<li>  Asignación de un puente de conferencia a usuarios con licencia.  </li>
</ul>
<li>  Sistema telefónico:
<ul>
<li>  Configuración de la organización para los parámetros predeterminados de voz en la nube.  </li>
<li>  Instrucciones de planes de llamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponibles</a>):
<ul>
<li>  Asignación de números a usuarios con licencia.  </li>
<li>  Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.  </li>
<li>  Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.  </li>
</ul></li>
<li>  Guía de enrutamiento directo:
<ul>
<li>  Guía de configuración de la organización para el diseño de enrutamiento directo de escenarios hospedados por asociados o escenarios implementados por el cliente para hasta 10 sitios.  </li>
<li> Revisión de configuración del controlador de borde de sesión (SBC). </li>

<li> Asistencia remota con la configuración del plan de marcado. </li>

<li> Configuración de ruta de voz.</li>

<li> Desvío de medios y optimización de medios locales. </li>

</ul></li>
</ul></li>
<li>  Habilitar eventos en directo en Teams  </li>
<li>  Configuración e integración de la organización en Microsoft Stream.  </li>
<li>  Instrucciones para Skype Empresarial para Teams transición.  </li>
</ul></td>
<td><ul>
<li>  Identidades habilitadas en Azure AD para Office 365.  </li>
<li>  Usuarios habilitados para SharePoint Online.  </li>
<li>  Exchange buzones de correo están presentes (en línea y local en una Exchange de configuración híbrida).  </li>
<li>  Habilitado para Grupos de Office 365.  </li>
</ul>
  <strong>Nota:</strong> Si los usuarios no están asignados y habilitados con SharePoint online, no tendrán OneDrive para la Empresa almacenamiento en Office 365. El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin OneDrive para la Empresa almacenamiento en Office 365. Teams no admite SharePoint local.  <br>
  <strong>Nota:</strong> El estado ideal es que todos los usuarios tengan sus buzones en Exchange Online. Los usuarios con buzones de correo locales deben tener sus identidades sincronizadas con el directorio Office 365 a través de Azure AD Conectar. Para estos Exchange híbridos, si el buzón del usuario es local, el usuario no puede agregar ni configurar conectores.  
  Los instaladores para los clientes de escritorio de Mac y Windows en Microsoft Teams se pueden descargar de <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.  </td>
</tr>

<tr class="even">
<td><strong>Outlook para iOS y Android</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Descargar Outlook para iOS y Android desde la App Store de Apple y Google Play.  </li>
<li>  Configurar cuentas y acceder al buzón de Exchange Online.  </li>
<li>  Proteger Outlook móvil (consulte [Securing Outlook for iOS and Android in Exchange Online](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android) para obtener más información).  </li>
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
<td>El software cliente en línea como Power BI Desktop debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</td>
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
<td>El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</td>
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
<td>El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</td>
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
<li>  Su enfoque de migración.  </li>
</ul>
Se proporcionan instrucciones adicionales para OneDrive para la Empresa según la versión SharePoint, como:
<ul>
<li>  Identificar las opciones de integración y revisar el ancho de banda y la infraestructura de red local y en línea.  </li>
<li>  Instalar SharePoint Online 2013 SP1 (si corresponde), planear e implementar requisitos de sincronización e identidad, e identificar el OneDrive para la Empresa de sincronización.  </li>
<li>  Planeación e implementación de un solo lanzamiento para todos los usuarios (o un lanzamiento por fases).  </li>
<li>  Asignar licencias, redirigir Mis sitios y bibliotecas de documentos personales a Office 365 (aplicable a SharePoint Online 2013), configurar audiencias para controlar el acceso a OneDrive (aplicable a SharePoint Online 2013).  </li>
<li>Redirigir o mover carpetas conocidas a OneDrive.</li>
<li>  Implementar la sincronización OneDrive para la Empresa cliente.  </li>
</ul>
  <strong>Migración de datos</strong>  <br>
Para obtener información sobre cómo usar la ventaja de FastTrack para la migración de datos a Office 365, vea [Data Migration](data-migration.md).
</ul></td>
<td><br><strong>Para SharePoint híbrido:</strong>  
<ul>
<li>  SharePoint configuración híbrida incluye la configuración de búsqueda híbrida, sitios, taxonomía, tipos de contenido, OneDrive para la Empresa, un iniciador de aplicaciones extendido, sitios de extranet y creación de sitios de autoservicio conectados desde local a un único entorno de SharePoint Online de destino.  </li>
</ul>
  <strong>Nota:</strong> La creación de sitios sin servicio no está en el ámbito con servidores locales que se ejecutan SharePoint 2013.  
<ul>
<li>  Para habilitar SharePoint híbrido, debe tener uno de los siguientes entornos de servidor SharePoint locales: 2013, 2016 o 2019.  </li>
</ul>
  <strong>Nota:</strong> La actualización de entornos SharePoint locales a SharePoint server no está en el ámbito. Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda. Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  <br>
  <strong>Nota:</strong> Para obtener información sobre las capacidades multigeo, vea <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td>
Proporcionamos instrucciones remotas para habilitar el Yammer Enterprise servicio.  
</td>
<td>El software cliente en línea debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security 

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></td>
<td>  Para obtener más información, <strong>vea Azure Active Directory (Azure AD) y Azure AD Premium</strong> seguridad y [cumplimiento](products-and-capabilities.md#security-and-compliance).</td>
<td></td>
</tr>
<tr class="odd">#seguridad y cumplimiento
<td><strong>Azure Information Protection </strong></td>
<td>  Para obtener más información sobre Azure Information Protection, vea <strong>Microsoft Information Protection</strong> in Security and [Compliance](products-and-capabilities.md#security-and-compliance).  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Para obtener más información, <strong>vea Microsoft Intune</strong> en Seguridad [y cumplimiento](products-and-capabilities.md#security-and-compliance).
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

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
<td><strong>Windows 10</strong></td>
<td>  Proporcionamos instrucciones para actualizar de Windows 7 Professional y Windows 8.1 Professional a Windows 10 Enterprise.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Comprender su Windows 10 intenciones.  </li>
<li>  Evaluar el entorno de origen y los requisitos (asegúrese de que Microsoft Endpoint Configuration Manager se actualice al nivel requerido para admitir la Windows 10 implementación).  </li>
<li>  Implementar Windows 10 Enterprise y Aplicaciones Microsoft 365 mediante Microsoft Endpoint Configuration Manager o Microsoft 365.  </li>
<li>  Te recomendamos opciones para que evalúes tus Windows 10 aplicaciones.  </li>
<li>  Habilitar el uso de Análisis de escritorio y la guía mediante la creación de un plan de implementación de Desktop Analytics.  </li>
<li>  Aplicaciones Microsoft 365 de compatibilidad aprovechando el panel de preparación de Office 365 en Configuration Manager o con el Toolkit de preparación independiente para Office además de la asistencia para implementar Aplicaciones Microsoft 365.  </li>
<li>  Crear una lista de comprobación de corrección sobre lo que necesita hacer para que el entorno de origen se asemeja a los requisitos mínimos para una implementación correcta.  </li>
<li>  Proporcionar instrucciones de actualización para que los dispositivos existentes Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesarios.  </li>
<li>  Proporcionar instrucciones de actualización para admitir el movimiento de implementación existente. FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10. Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.  </li>
<li>  Implementar Aplicaciones Microsoft 365 con Configuration Manager como parte de la Windows 10 implementación.   </li>
<li>  Proporcionar instrucciones para ayudar a su organización a mantenerse al día con Windows 10 Enterprise y Aplicaciones Microsoft 365 el entorno de Configuration Manager existente o Microsoft 365.  </li>
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
Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.  </td>
<td>  Para actualizar su PC, debe cumplir con estos requisitos:
<ul>
<li>  Sistema operativo de origen: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.  </li>
<li>  Dispositivos: factor de forma de escritorio, bloc de notas o tableta.  </li>
<li>  Sistema operativo de destino: ventana 10 Enterprise.  </li>
</ul>
Para actualizar la infraestructura, debe cumplir con estos requisitos:
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  La versión de Configuration Manager debe ser compatible con la Windows 10 de destino. Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en [Soporte para Windows 10 en Configuration Manager](/sccm/core/plan-design/configs/support-for-windows-10).  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender para punto de conexión</strong></td>
<td>  Para obtener más información, vea <strong> Microsoft Defender for Endpoint</strong> in Security and [Compliance](products-and-capabilities.md#security-and-compliance).</td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

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
<td><strong>Windows Virtual Desktop</strong></td>
<td><p>Proporcionamos instrucciones de implementación para la incorporación Windows Virtual Desktop (un servicio de virtualización de aplicaciones y escritorio). Windows Virtual Desktop aprovecha la Windows 10 de varias sesiones y está optimizado para Aplicaciones Microsoft 365 para Enterprise con seguridad y administración integradas para Microsoft 365.</p>
<p>Proporcionamos instrucciones remotas para:</p>
<ul>
<li>Implementar el entorno Windows Escritorio virtual con Windows 10 Enterprise multi-sesión y Aplicaciones Microsoft 365 para Enterprise mediante lo siguiente:
<ul>
<li>Imagen de Azure Marketplace.</li>
<li>Imagen compartida.</li>
<li>Office Implementación Toolkit (ODT).</li>
</ul></li>
<li>Configuración de FSLogix:
<ul>
<li>Implementación del agente FSLogix con el contenedor de perfiles.</li>
<li>Implementación del agente FSLogix con Office contenedor.</li>
<li>Configurar la carpeta FSLogix con exclusiones de contenido.</li>
</ul></li>
<li>Implementación de Microsoft Edge.</li>
<li>Implementación de Microsoft Teams.</li>
<li>Conectarse con Windows cliente de Escritorio virtual.</li>
</ul>

<strong>Lo siguiente está fuera del ámbito</strong>
<ul>
<li>Project administración de la implementación de Escritorio virtual Windows cliente.</li>
<li>Implementación y virtualización de aplicaciones de terceros.</li>
<li>Imágenes personalizadas.</li>
<li>Migraciones y escenarios en los que participan VMware y Citrix.</li>
<li>Escenarios de Linux.</li>
<li>Conversión o migraciones de perfiles de usuario.</li>
</ul>
Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</td>
<td>Ya debería tener lo siguiente:
<ul>
<li>[Windows de licencias de Escritorio virtual](/azure/virtual-desktop/overview#requirements).</li>
<li>Redes de Azure:
<ul>
<li>Creación y subred de red virtual (VNET).</li>
<li>Firewall y grupos de seguridad de red.</li>
<li>VPN y ExpressRoute.</li>
<li>Enrutamiento a Azure desde local.</li>
<li>Reglas de firewall para permitir la conectividad Windows Escritorio virtual.
</ul>
Para obtener más información, vea [Supported Remote Desktop clients](/azure/virtual-desktop/overview#supported-remote-desktop-clients).
</ul>
<ul><li>Configuración general de Azure AD:
<ul>
<li>Estrategia de <i>identidad (solo puede usar una de las tres opciones siguientes):</i>
<ul>
<li>Active Directory con Azure AD Conectar azure.</li>
<li>Active Directory con Azure AD Conectar local a través de VPN o ExpressRoute.</li>
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
<th><strong>Detalles de instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Asesoría de aplicaciones</strong></td>
<td>  App Assure es un servicio diseñado para solucionar problemas con Windows 10 y Aplicaciones Microsoft 365 de aplicaciones. Cuando solicitas el servicio App Assure, trabajamos contigo para solucionar problemas válidos de la aplicación sin ningún costo adicional para ti con una suscripción elegible. También proporcionamos instrucciones a los clientes que se enfrentan a problemas de compatibilidad al implementar Windows Escritorio virtual y Microsoft Edge y hacemos todos los esfuerzos razonables para resolver problemas de compatibilidad. Proporcionamos asistencia de corrección para las aplicaciones implementadas en los siguientes productos de Microsoft:
<ul>
<li>  <strong>Windows 10</strong> (incluidos los dispositivos ARM64)</li>
<li> <strong>Aplicaciones Microsoft 365</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> Para obtener instrucciones de implementación, vea [Overview of the Microsoft Edge channels](/DeployEdge/microsoft-edge-channels).  </li>
<li>  <strong>Windows Virtual Desktop</strong> - Para obtener más información, vea [What is Windows Virtual Desktop?](/azure/virtual-desktop/overview) y Windows 10 Enterprise preguntas más frecuentes de varias [sesiones.](/azure/virtual-desktop/windows-10-multisession-faq)  </li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
<ul>
<li>  Inventario y pruebas de aplicaciones para determinar lo que funciona y lo que no en Windows 10 y en las Aplicaciones de Microsoft 365. Para obtener más información sobre este proceso, visite el <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de implementación de escritorios</a>. Si está interesado en una evaluación detallada de la preparación para la actualización, complete el formulario <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitud de cliente para la evaluación del escritorio moderno</a>.</li>
<li>  Buscar instrucciones de compatibilidad y soporte técnico de Windows 10 en aplicaciones ISV de terceros. Para más información, vea [Análisis de escritorio](/sccm/desktop-analytics/overview).</li>
<li>Servicios de solo empaquetado de la aplicación. Sin embargo, el equipo de App Assure crea paquetes de aplicaciones que hemos corregido para Windows 10 para asegurarse de que se pueden implementar en el entorno del cliente.</li>
</ul>

<strong>Entre las responsabilidades del cliente se incluyen</strong>  
<ul>
<li>  Creación de un inventario de aplicaciones.</li>
<li>  Validación de esas aplicaciones en Windows 10 y en las Aplicaciones de Microsoft 365.</li>
</ul>
<strong>Nota:</strong>  Microsoft no puede realizar cambios en el código fuente. Sin embargo, el equipo de App Assure puede proporcionar instrucciones a los desarrolladores de aplicaciones si el código fuente está disponible para sus aplicaciones. 


  Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.  </td>

</td>
<td><strong>Windows 10 y Aplicaciones Microsoft 365</strong>
<ul>
<li>  
  Las aplicaciones que funcionaban en Windows 7, Windows 8.1, Office 2010 y Office 2013 también funcionan en Windows 10 y en las Aplicaciones de Microsoft 365.  
  </li>
</ul>
<strong>Windows 10 en ARM</strong>
<ul>
<li>  
Las aplicaciones que funcionaban Windows 7, Office 2010 o versiones posteriores también funcionan en Windows 10 y Aplicaciones Microsoft 365 dispositivos ARM64. 
  </li>
</ul>
  <strong>Nota:</strong> 
<ul>
<li> La emulación x64 (64 bits) está disponible en versión preliminar para los clientes que participan en el <a href="https://insider.windows.com/">Windows Insider Program</a>.  </li>
<li>  
 Para clientes no Windows Insider en Windows 10 versión 2004 (o posterior), ARM64 Photoshop es compatible con OpenCL y <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack</a>. 
  </li>
<li>  
  Los clientes del programa Windows Insider pueden descargar una versión insider del Paquete de compatibilidad de OpenCL y OpenGL para usarla con aplicaciones adicionales.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Si las aplicaciones web o los sitios funcionan en Internet Explorer 11, las versiones compatibles de Google Chrome o cualquier versión de Microsoft Edge, también funcionarán con Microsoft Edge.  
  </li>
<li>  
  A medida que la web está en constante evolución, asegúrese de revisar esta lista publicada de cambios conocidos que afectan a la compatibilidad de sitios para [Microsoft Edge](/microsoft-edge/web-platform/site-impacting-changes).  
  </li>
</ul>
  <strong>Windows Escritorio virtual</strong>  
<ul>
<li>  
  Las aplicaciones virtualizadas que se ejecutan en el host de sesión de Escritorio remoto (RDSH) de Windows Server también se ejecutan en Windows 10 Enterprise multisesión como parte de Windows Virtual Desktop.  
  </li>
<li>  
  Las aplicaciones que se ejecutan en cualquier entorno de infraestructura de escritorio virtual (VDI) Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.  
  </li>
<li>  
  Las aplicaciones que se ejecutan en dispositivos cliente con Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.  
  </li>
</ul>
  <strong>Nota: Windows 10 Enterprise</strong> exclusiones y limitaciones de compatibilidad de varias sesiones incluyen:
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
<th><strong>Detalles de instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
Proporcionamos ayuda para la compatibilidad y la implementación remota y la adopción para: <ul> <li>Implementación de Microsoft Edge en Windows 10 con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).  </li>
<li>  Configuración de Microsoft Edge (mediante directivas de grupo o configuración de aplicaciones de Intune y directivas de aplicaciones).  </li>
<li>  Inventario de la lista de sitios que pueden requerir su uso en modo Internet Explorer.  </li>
<li>  Habilitar el modo de Internet Explorer con la lista Enterprise sitio existente. (Para obtener más información, vea [Engaging FastTrack](process-and-expectations.md#engaging-fasttrack)). Además, si tienes una aplicación web o un sitio que funciona con Internet Explorer o Google Chrome y tienes problemas de compatibilidad, te ofrecemos instrucciones para resolver el problema sin costo adicional. Para solicitar compatibilidad con App Assure, inicie sesión en el <a href="https://fasttrack.microsoft.com/portal#/signin">portal de FastTrack</a> para iniciar una interacción.  </li>
<li> Instrucciones de planeación para la adopción y configuración perimetrales para marcadores de Microsoft Search.</li>
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
