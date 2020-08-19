---
title: Productos y capacidades
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Este tema incluye detalles sobre los escenarios de carga de trabajo compatibles con FastTrack y las expectativas del entorno de origen necesarias antes de que podamos comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que incorpore el entorno de origen a los requisitos mínimos para la incorporación correcta.
ms.openlocfilehash: 1b1ffa5812905630723b5d8a23196fbbc18a9c32
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800972"
---
# <a name="products-and-capabilities"></a>Productos y capacidades

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Servicios y escenarios compatibles con FastTrack

Este tema incluye detalles sobre los escenarios de carga de trabajo compatibles con FastTrack y las expectativas del entorno de origen necesarias antes de que podamos comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que incorpore el entorno de origen a los requisitos mínimos para la incorporación correcta.

FastTrack proporciona instrucciones para ayudarle primero con las capacidades principales (comunes para todos los servicios en línea de Microsoft) y, a continuación, con la incorporación de cada servicio elegible:

  - [General](#general)
  - [Office 365](#office-365)
  - [Seguridad de Enterprise Mobility &](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [App Assure](Win-10-app-assure.md)
  - [El nuevo Microsoft Edge](Win-10-microsoft-edge.md)

> [!NOTE]
> Para obtener información sobre las expectativas del entorno de origen para Office 365 US Government, vea [expectativas del entorno de origen para office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).
 
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
<li>  Tareas necesarias para la configuración de los inquilinos y la integración con Azure Active Directory, si es necesario.   </li>
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
<li>  El software de cliente en línea debe tener un nivel mínimo, como se define en los <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.  </li>
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

## <a name="office-365"></a>Office 365

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
Para obtener información sobre cómo usar el beneficio de FastTrack para la migración de datos a Office 365, vea <a href="https://review.docs.microsoft.com/fasttrack/data-migration">migración de datos</a>.   
<td>  El entorno de origen debe tener uno de los siguientes niveles mínimos:
<ul>
<li>  Una o varias organizaciones de Exchange a partir de Exchange Server 2003.  </li>
<li>  Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).  </li>
<li>  Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).  </li>
<li>  Para obtener información sobre las funciones multigeográficas, vea <a href="https://go.microsoft.com/fwlink/?linkid=872776">multi-Geogeográfico Capabilities in Exchange Online</a>.  </li>
</ul>
El software cliente en línea, como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, el cliente de sincronización de OneDrive para la empresa, Power BI Desktop y Skype empresarial deben tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 Office</a>.  </td>
</tr>
<tr class="even">
<td><strong>Gobierno de información de Microsoft</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Gobernanza de la información  </li>
<li>  Etiquetas y directivas de retención  </li>
<li>  Administración de registros  </li>
<li>  Directivas de eliminación  </li>
<li>  Cumplimiento de comunicaciones  </li>
<li>  Administración de riesgos de Insider.  </li>
<li>  eDiscovery avanzado  </li>
</ul></td>
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
<li>  Clasificadores que se capacitan.  </li>
<li>  Conocer los datos con el explorador de contenido y el explorador de actividades.  </li>
<li>  Publicar etiquetas usando directivas (manuales y automáticas).  </li>
<li>  Crear directivas de prevención de pérdida de datos (DLP) para los canales y chats de Microsoft Teams.  </li>
</ul></td>
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
</ul>
<ul>
<li>  Creación de cuentas en línea necesarias para la telefonía admitida y los dispositivos de salas de conferencias que aparecen en el catálogo de dispositivos de Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams</a>.  </li>
</ul>
<ul>
<li>  Habilitar audioconferencia:  </li>
</ul>
<ul>
<li>  Configuración de la organización para los parámetros predeterminados de puente de conferencia.  </li>
<li>  Asignación de un puente de conferencia a usuarios con licencia.  </li>
</ul>
<ul>
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
<li>  Guía de configuración de organización para el diseño de enrutamiento directo de escenarios hospedados por partners o escenarios implementados por clientes para un único sitio.  </li>
</ul></li>
</ul></li>
<li>  Habilitar eventos en directo en Teams  </li>
<li>  Configuración e integración de la organización en Microsoft Stream.  </li>
</ul></td>
<td><ul>
<li>  Identidades habilitadas en Azure AD para Office 365.  </li>
<li>  Usuarios habilitados para SharePoint Online.  </li>
<li>  Los buzones de Exchange están presentes (en línea y local en una configuración híbrida de Exchange).  </li>
<li>  Habilitado para Grupos de Office 365.  </li>
</ul>
  <strong>Nota:</strong>   Si los usuarios no están asignados ni habilitados con licencias de SharePoint Online, no tendrán almacenamiento de OneDrive para la empresa en Office 365. El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin el almacenamiento de OneDrive para la empresa en Office 365. Teams no es compatible con SharePoint local.  <br>
  <strong>Nota:</strong>   El estado ideal es que todos los usuarios tengan sus buzones hospedados en Exchange Online. Los usuarios con buzones de correo hospedados de forma local deben tener sus identidades sincronizadas con el directorio de Office 365 mediante Azure AD Connect. Para estos clientes híbridos de Exchange, si el buzón de correo del usuario es local, el usuario no puede agregar ni configurar conectores.  
  Se pueden descargar los instaladores para los clientes de escritorio de Microsoft Teams para Windows y Mac  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .  </td>
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
<td>El software cliente en línea, como Power BI Desktop, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</td>
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
<td>El software cliente en línea, como Project para Office 365, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</td>
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
<td>El software cliente en línea, como Project para Office 365, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</td>
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
Para obtener información sobre cómo usar el beneficio de FastTrack para la migración de datos a Office 365, vea <a href="https://review.docs.microsoft.com/fasttrack/data-migration">migración de datos</a>.
</ul></td>
<td><br><strong>Para entornos híbridos de SharePoint:</strong>  
<ul>
<li>  La configuración híbrida de SharePoint incluye la configuración de la búsqueda híbrida, los sitios, la taxonomía, los tipos de contenido, OneDrive para la empresa, un iniciador de aplicaciones extendido, sitios de extranet y la creación de sitios sin servicio conectado de forma local a un entorno de SharePoint Online de destino único.  </li>
</ul>
  <strong>Nota:</strong> La creación de sitios sin servicio está en el ámbito de los servidores locales que ejecutan SharePoint 2013.  
<ul>
<li>  Para habilitar el entorno híbrido de SharePoint, debe disponer de uno de los siguientes entornos de SharePoint Server locales: 2013, 2016 o 2019.  </li>
</ul>
  <strong>Nota:</strong> La actualización de entornos de SharePoint local a SharePoint Server no se encuentra en el ámbito. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda. Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">niveles mínimos de actualización pública para las características híbridas de SharePoint</a><em>.</em>  <br>
  <strong>Nota:</strong> Para obtener información sobre las funciones multigeográficas, consulte <a href="https://go.microsoft.com/fwlink/?linkid=831056">multigeográfico Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </td>
</tr>
<tr class="odd">
<td><strong>Skype Empresarial Online</strong></td>
<td>  Proporcionamos instrucciones remotas para:
<ul>
<li>  Configuración de puertos del firewall.  </li>

<li>  Configuración de DNS.  </li>
<li>  Evaluación de la red:
<ul>
<li>  Comprobaciones de puertos y puntos de conexión.  </li>
<li>  Comprobaciones de calidad de la conexión.  </li>
<li>  Estimaciones de ancho de banda.  </li>
</ul></li>
<li>  Creación de cuentas para cualquier dispositivo del sistema de la sala.  </li>
<li>  Implementación de un cliente de Skype Empresarial Online compatible.  </li>
<li>  Establecimiento de una configuración de servidores de dominio dividido entre el entorno de servidor local de Lync 2010, Lync 2013 o Skype Empresarial 2015 y un espacio empresarial de Skype Empresarial Online (si procede), planes de llamada, Difusión de reunión de Skype y sistema telefónico y planes de llamada (en los mercados disponibles).  
  Si procede, FastTrack también le guiará a lo siguiente:  </li>
<li>  Configurar el dispositivo del sistema Room:
<ul>
<li>  Creación de cuentas en línea necesarias para los dispositivos de sala de conferencias admitidos que aparecen en la pestaña sistemas de salas de reuniones en el <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Catálogo de soluciones de Skype empresarial</a>.  </li>
</ul></li>
<li>  Configuración de servidores de dominios divididos y híbridos.  </li>
<li>  Configuración de audioconferencia:
<ul>
<li>  Configuración de la organización para los parámetros predeterminados de puente de conferencia.  </li>
<li>  Asignación de un puente de conferencia a usuarios con licencia.  </li>
</ul></li>
<li>  Configuración de las opciones predeterminadas del sistema telefónico:
<ul>
<li>  Planes de llamada:
<ul>
<li>  Asignación de números a usuarios de licencias.  </li>
<li>  Guía de portabilidad de números locales a través de la interfaz de usuario hasta 99  </li>
<li>  Soporte de solicitud de servicio de portabilidad de número local sobre 999  </li>
</ul></li>
</ul></li>
<li>  Configurar la difusión de reunión de Skype empresarial:
<ul>
<li>  Configuración de la organización para los parámetros predeterminados de federación con el servicio de difusión de reunión.  </li>
</ul></li>
</ul></td>
<td>  <strong>Para Lync Hybrid:</strong>  
<ul>
<li>  Un solo bosque de Active Directory local.  </li>
<li>  Un entorno de Lync 2010 Server con las herramientas de administración de Lync 2013 o las herramientas de administración de Skype Empresarial 2015 y un rol de servidor perimetral de Lync 2010.  </li>
<li>  Un entorno de Lync 2013 Server y un rol de servidor perimetral de Lync 2013.  </li>
</ul>
  <strong>Para Skype empresarial híbrido:</strong>  
<ul>
<li>  Un solo bosque de Active Directory local.  </li>
<li>  Un solo bosque de cuentas de Active Directory o superior y topologías de bosques de recursos (Exchange o Skype Empresarial).  </li>
<li>  Varios bosques de cuentas de Active Directory donde uno de ellos es un bosque de cuentas de Active Directory centralizado con Exchange y/o Skype Empresarial en él.  </li>
<li>  Un entorno de Skype Empresarial Server 2015 que incluya un rol de servidor perimetral de Skype Empresarial.  </li>
</ul>
  <strong>Nota:</strong> Este servicio adicional es para configurar y validar las tareas de dominio dividido (híbrido) y no incluye la introducción de componentes locales (por ejemplo, herramientas de administración de Lync 2013 o de Lync 2013/Skype empresarial online, o Lync 2010, Lync 2013 o servidores perimetrales de Skype empresarial).  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Proporcionamos instrucciones remotas para habilitar el servicio Yammer Enterprise.  
</ul></td>
<td>El software de cliente en línea debe tener un nivel mínimo, como se define en los <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Seguridad de Enterprise Mobility &

<table>
<thead>
</tr>
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
  Administrar y controlar el acceso a las cuentas de administrador con privilegios con Azure AD privileged Identity Management.  
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
<td><strong>Azure Information Protection (P2 o EMS E5)</strong></td>
<td>  Proporcionamos instrucciones sobre cómo:
<ul>
<li>  Activar y configurar el inquilino.  </li>
<li>  Crear y configurar etiquetas y directivas.  </li>
<li>  Aplicar la protección de la información a documentos.  </li>
<li>  Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.  </li>
<li>  Usar archivos en reposo con el escáner de Azure Information Protection.  </li>
<li>  Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.  </li>
</ul>
También le ofrecemos instrucciones para aplicar la protección con Microsoft Azure Rights Management Services (Azure RMS), el cifrado de mensajes de Office 365 (OME) y la prevención de pérdida de datos (DLP).  </td>
<td>  Ya debe:
<ul>
<li>  Usar Azure AD.  </li>
<li>  Use Windows o iOS (otros sistemas operativos están fuera del ámbito).  
  </ul>
<strong>Nota</strong>: los equipos y dispositivos móviles deben ejecutarse en un <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">sistema operativo</a> compatible con Azure Information Protection.  
<li>  Tener las ubicaciones principales del recurso compartido de archivos.  </li>
<strong>Nota</strong>: la compatibilidad híbrida requiere el conector de AD RMS. 
<li>  Tener una taxonomía de clasificación aprobada.  </li>
<li>  Comprenda las restricciones regulatorias para la administración de claves protegida.  </li>
</ul>
  
<strong>Escáner de Azure Information Protection</strong>  
  
Ya debe:  
<ul>
<li>  Usar Windows Server 2012 R2 o Windows Server 2016.  </li>
<li>  Tener una conexión a Internet.  </li>
<li>  Tener Microsoft SQL Server 2012 en adelante en una instancia local o remota.  </li>
<li>  Tener una cuenta de servicio creada para su Active Directory local y sincronizada con Azure AD.  </li>
<li>  Ha descargado AzInfoProtection.exe.  </li>
<li>  Tienen etiquetas configuradas para la clasificación/protección automática.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Proporcionamos instrucciones sobre cómo prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos. Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles. Los pasos pueden incluir:
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
<li>  Implementación de los perfiles de correo electrónico, redes inalámbricas y VPN) si tiene una entidad de certificación, una red inalámbrica o una infraestructura de VPN en su organización.  </li>
<li>  La configuración de Microsoft Intune Exchange Connector (si es necesario).  </li>
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
<li>  Explicar las ventajas de conectar Configuration Manager a la nube con Intune.  </li>
<li>  Conceder licencias a los usuarios finales.  </li>
<li>  Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.  </li>
<li>  Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.  </li>
<li>  Habilitar la conexión a la nube en la consola de Configuration Manager.  </li>
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

<strong>Conectar a la nube Configuration Manager con Microsoft Intune</strong>  

 Con la conexión a la nube, los administradores de TI son responsables de preparar el entorno local. Esto puede incluir la corrección de problemas que le impiden asociar en la nube sus entornos de Configuration Manager con Intune.  
  <strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.

  <strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong> 
 
  <strong>Nota</strong>: proporcionamos asistencia sobre la integración de Intune con Microsoft defender ATP y la creación de directivas de cumplimiento de dispositivos basadas en su evaluación de nivel de riesgo de Windows 10. No proporcionamos asistencia sobre la compra, concesión de licencias o activación. Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.  
  
<strong>Windows Autopilot</strong> 
 
  Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.  
  
<strong>Implementación de Outlook para iOS y Android de manera segura con Intune </strong>  
<ul>
<li>  Identidades de usuario habilitadas en Azure AD para Office 365.  </li>
<li>  Exchange online o Exchange híbrido configurado con licencias de usuario asignadas.  </li>
</ul></td>
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
<td>  Le proporcionamos instrucciones para ayudarle a actualizar de Windows 7 Professional y Windows 8,1 Professional a Windows 10 Enterprise.  
  Proporcionamos instrucciones remotas para:
<ul>
<li>  Comprender su intención de Windows 10.  </li>
<li>  Evaluar el entorno de origen y los requisitos (Asegúrese de que el administrador de configuración de Microsoft Endpoint se actualiza al nivel requerido para admitir la implementación de Windows 10).  </li>
<li>  Implementación de aplicaciones de Windows 10 Enterprise y Microsoft 365 con Microsoft Endpoint Configuration Manager o Microsoft 365.  </li>
<li>  Recomendar opciones para evaluar las aplicaciones de Windows 10.  </li>
<li>  Habilitación del uso de análisis de escritorio y orientación mediante la creación de un plan de implementación de análisis de escritorio.  </li>
<li>  Evaluación de la compatibilidad de las aplicaciones de Microsoft 365 aprovechando el panel de preparación de Office 365 en Configuration Manager o con el kit de herramientas de preparación independiente para Office más asistencia para la implementación de aplicaciones de Microsoft 365.  </li>
<li>  Evaluar las estrategias de administración modernas, incluido el administrador de configuración con conexión a la nube con Microsoft Intune o la implementación de Intune como la única solución de administración de nube.  </li>
<li>  Crear una lista de comprobación de corrección sobre lo que debe hacer para llevar el entorno de origen a los requisitos mínimos para una implementación correcta.  </li>
<li>  Proporciona instrucciones de actualización para los dispositivos existentes a Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesario.  </li>
<li>  Proporcionar instrucciones de actualización para apoyar el movimiento de implementación existente. FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10. Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.  </li>
<li>  Implementación de aplicaciones de Microsoft 365 con Configuration Manager como parte de la implementación de Windows 10.   </li>
<li>  Proporcionan instrucciones para ayudar a su organización a mantenerse al día con las aplicaciones de Windows 10 Enterprise y Microsoft 365 usando su entorno de Configuration Manager existente o Microsoft 365.  </li>
<li>  Proporciona instrucciones para habilitar la administración moderna mediante el administrador de configuración con conexión a la nube para Intune o mediante la implementación de Intune Standalone (donde sea necesario).  </li>
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
<li>  La versión de destino de Windows 10 debe admitir la versión del administrador de configuración. Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">soporte para Windows 10 en el administrador de configuración</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Protección contra amenazas avanzada de Microsoft defender (ATP)</strong></td>
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
  Canal semianual de Windows Server (SAC) versión 1803.  
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
