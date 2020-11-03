---
title: Migración de datos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa). El tipo de asistencia que proporcionamos depende del número de licencias de Office 365.
ms.openlocfilehash: 7b796ea88c884445bd7069c6c7768c8fc3e3d170
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827662"
---
# <a name="data-migration"></a>Migración de datos

FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa).

El tipo de asistencia que proporcionamos depende del número de licencias de Office 365 que tenga:

  - **En el caso de cuentas empresariales de Office 365 con 150-499 licencias** : FastTrack solo proporciona instrucciones para la migración, usted es el responsable de realizar la migración de datos. Lo guiaremos a través de documentación que le ayudará a planear y a usar herramientas gratuitas para realizar una migración de autoservicio.
  - **En el caso de cuentas empresariales de Office 365 con más de 500 licencias** : FastTrack proporciona instrucciones para la migración y servicios de migración de datos. Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y su espacio empresarial de Office 365 y aprovechar nuestros servicios de migración de datos para migrar sus datos. Cree y programe sus eventos de migración. Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.

> [!NOTE]
> Si compró o renovó un plan comercial antes del 1° de septiembre de 2017, solo necesita 150 licencias para calificar para los servicios de migración de datos. En el caso de los planes educativos, solo las licencias pagas del profesorado y el personal pueden optar para los servicios de migración de datos.

### <a name="considerations"></a>Consideraciones

  - Los entornos de origen deben cumplir expectativas específicas para poder migrar datos a Office 365. Para obtener más información sobre las expectativas del entorno de origen de Exchange, SharePoint y OneDrive para la Empresa, consulte [Productos y funciones](products-and-capabilities.md).
  - Requerimos el acceso y los permisos adecuados de acceso a sus entornos de origen y a su cuenta empresarial de Office 365 para proporcionar los servicios de migración de datos.
  - Nuestros servicios de migración de datos no están diseñados ni tienen como objetivo fungir como datos de un sujeto interesado para cumplir con obligaciones jurídicas especiales o requisitos legales. A medida que migramos los datos, se pueden transferir, almacenar y procesar en cualquier lugar en el que mantengamos instalaciones (a menos que se disponga de otro modo en el proyecto de migración de FastTrack).
  - Microsoft no puede garantizar la velocidad de la migración de archivos o correos.
  - Hay problemas imprevistos (como elementos ilegibles o dañados en el entorno de origen) que podrían afectar nuestra capacidad para migrar algunos de los elementos de datos.
  - Los factores externos más allá de nuestro control (como los cambios a las interfaces de programación de aplicaciones (API) de terceros) pueden ocasionar cambios, retrasos o la suspensión de nuestros servicios de migración de datos.

### <a name="migration-service-availability"></a>Disponibilidad del servicio de migración

  - **Para clientes comerciales y gubernamentales del Reino Unido:** Proporcionamos servicios de migración de datos las 24 horas del día, los siete (7) días de la semana (24x7).
  - **Para clientes gubernamentales/DOD de Estados Unidos:** Proporcionamos servicios de migración de datos las 24 horas del día, los cinco (5) días hábiles de la semana (24x5).

## <a name="migration-to-exchange-online"></a>Migración a Exchange Online

Cuando elige usar FastTrack para migrar su correo electrónico a Exchange Online, ofrecemos instrucciones de migración y servicios de migración de datos. Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de Exchange Online, y aprovechar nuestros servicios de migración de datos para migrar sus buzones. Cree y programe sus eventos de migración. Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado. Cuando los eventos de migración se completen, encontrará que los correos provenientes de los buzones de origen que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a Exchange Online.

### <a name="considerations"></a>Consideraciones

  - Antes de la migración, debe completar la incorporación básica de FastTrack para Exchange Online.
      - Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos. Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).
  - FastTrack solo migra a buzones de Office 365 que estén activos.
  - Si tiene previsto migrar desde un entorno local de Exchange, debe cumplir los requisitos específicos. Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).
  - Todos los entornos de origen deben tener el Service Pack (SP) y la actualización acumulativa (RU)/paquete acumulativo de actualizaciones (CU) en el último nivel para el producto correspondiente en el entorno de origen.
  - Las listas de distribución (objetos *MailEnabledGroup* ) y los contactos externos (objetos *MailEnabledContact* ) que existen en su Active Directory local no forman parte de la migración de datos del buzón. Sin embargo, puede sincronizarlos usando Azure Active Directory (Azure AD) Connect. 

## <a name="source-environments"></a>Entornos de origen

Nuestro servicio de migración de datos migra los datos desde los siguientes entornos de origen:

  - Uno o varios bosques de Active Directory con una o varias organizaciones de Exchange (cada sistema de correo de Exchange debe ser Exchange 2010 o superior).
  - Un solo entorno de correo electrónico compatible con IMAP.
  - Entorno de G Suite (solo Gmail, Contactos y Calendario).

En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:

<table>
<thead>
<tr class="header">
<th><strong>Entorno de origen</strong></th>
<th><strong>Tipo de migración</strong></th>
<th><strong>Qué se migra</strong></th>
<th><strong>Qué no se migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong><br />
<br />
<strong>Nota:</strong> Para las dependencias de Exchange local, consulte <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">requisitos previos de la implementación híbrida</span></a>.</td>
<td>Migración con implementación híbrida</td>
<td><ul>
<li>Mensajes de correo electrónico</li>
<li>Reglas de buzón</li>
<li>Delegados</li>
<li>Contactos de buzón de correo </li>
<li> Calendario </li>
<li> Tareas </li>
<li> Correos electrónicos con derechos administrados </li>
<li> Correos electrónicos cifrados </li>
<li> Firmas </li>
<li> Archivo personal migrado con el buzón del usuario </li>
<li> Elementos recuperables </li>
</ul></td>
<td><ul>
<li> Carpetas públicas </li>
<li> Cualquier correo electrónico que supere el límite de tamaño de mensaje </li>
<li> Archivo de registro en diario o cualquier solución de archivo de terceros </li>
<li> Usuarios bloqueados o inactivos </li>
<li> Datos de archivo procedentes de archivos PST (Personal Storage Table) </li>
<li> Elementos dañados </li>
<li> Buzones de correo inactivos </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Entorno de G Suite (solo Gmail, Contactos y Calendario)</strong><br />
<br />
<strong>Nota:</strong> El entorno de G Suite debe cumplir los requisitos previos descritos en <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a g Suite Migration</a>.</td>
<td>Total o preconfigurada</td>
<td><ul>
<li> Mensajes de correo electrónico </li>
<li> Contactos del buzón (se migra un máximo de 3 direcciones de correo electrónico por contacto) </li>
<li> Calendar </li>
<li> Etiquetas </li>
</ul></td>
<td><ul>
<li> Reglas </li>
<li> Delegados </li>
<li> Firmas </li>
<li> Tareas </li>
<li> Cualquier correo electrónico o dato adjunto que supere el límite de tamaño de mensaje </li>
<li> Usuarios bloqueados o inactivos </li>
<li> Datos de archivo procedentes de archivos PST o de soluciones de archivo de terceros (por ejemplo, Google Vault) </li>
<li> Mensajes de correo electrónico cifrados o con derechos administrados </li>
<li> Elementos dañados </li>
<li> Google Hangouts** </li>
<li> Grupos de Google </li>
<li> Buzones de recursos </li>
<li> Buzones de correo inactivos </li>
<li> Configuración de ausencia por vacaciones y respuesta automática </li>
<li> Calendarios compartidos, datos adjuntos en la nube, vínculos a Google Hangout y colores del evento </li>
</ul>
**Se migran las conversaciones de Hangouts guardadas como etiqueta. </td>
</tr>
<tr class="odd">
<td><strong>Origen de IMAP4 (como Domino, GroupWise o Zimbra)</strong></td>
<td>Migración con herramientas nativas de IMAP4</td>
<td><li>Mensajes de correo electrónico </li></td>
<td><ul>
<li> Reglas </li>
<li> Delegados </li>
<li> Listas de distribución </li>
<li> Contactos externos </li>
<li> Usuarios habilitados para correo </li>
<li> Usuarios bloqueados o inactivos </li>
<li> Contactos de buzón de correo </li>
<li> Calendario </li>
<li> Firmas </li>
<li> Tareas </li>
<li> Cualquier correo electrónico que supere el límite de tamaño de mensaje </li>
<li> Datos de archivo </li>
<li> Correo electrónico cifrado </li>
<li> Elementos dañados </li>
<li> Buzones de correo inactivos </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilidades de FastTrack

Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración. Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.

Nuestros especialistas de FastTrack también realizan las siguientes actividades específicas para las migraciones de Exchange:

  -  Ofrece instrucciones para ayudarle a habilitar la coexistencia de enrutamiento de correo SMTP entre los entornos de origen y Exchange Online, si procede.

## <a name="your-responsibilities"></a>Sus responsabilidades

Usted realizará actividades estándares durante el proyecto de migración. Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.

También realizará las siguientes actividades específicas para las migraciones de Exchange:

  - Completar la incorporación básica de FastTrack para Exchange Online. Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos. Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).
  -  Instalar el nivel adecuado del software del cliente según las instrucciones de Office 365. Para obtener más información, consulte [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).
  -  Cumplir los requerimientos específicos si tiene previsto migrar desde un entorno local de Exchange. Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).
  -  Asegurarse de que cada entorno de origen tenga la versión más reciente del Service Pack (SP) y de la actualización cumulativa (RU)/paquete acumulativo de actualizaciones (CU), si procede.
  -  Configurar y validar la coexistencia del enrutamiento de correo SMTP entre sus entornos de origen y Exchange Online, si procede.
  -  Asegurarse de que el tamaño de su buzón de origen no supere la cuota del buzón de destino. Dependiendo de la plataforma de origen, es posible que deba limitar los datos de origen a 85% de la cuota del buzón de destino.
  -  Puede migrar los datos del lado del cliente, si lo desea. Esto incluye, entre otras cosas, las libretas de direcciones locales, los datos de los archivos PST locales, las reglas de Outlook y la configuración local de Outlook.
  -  Ayudar a los usuarios finales con la corrección de los problemas de migración del lado del cliente.

## <a name="migration-to-sharepoint-online"></a>Migración a SharePoint Online

Cuando elige usar FastTrack para migrar sus archivos a SharePoint Online, ofrecemos instrucciones de migración y servicios de migración de datos. Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de SharePoint Online, y aprovechar nuestros servicios de migración de datos para migrar sus archivos. Cree y programe sus eventos de migración. Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado. Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a SharePoint Online.

## <a name="considerations"></a>Consideraciones

  - Todas las migraciones están sujetas a las cuotas de SharePoint Online. Consulte los [<span class="underline">Límites de software de SharePoint Online y de OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más detalles.
  - Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).

## <a name="source-environment-details"></a>Detalles del entorno de origen

Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:

  - Recursos compartidos de archivos (recursos compartidos de archivos de Bloqueo de mensajes del servidor (SMB) en dispositivos compatibles a partir de SMB 2.0 en adelante).
  - Un solo entorno de G Suite (solo Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox para Equipos (estándar y avanzado).

En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:

<table>
<thead>
<tr class="header">
<th><strong>Entorno de origen</strong></th>
<th><strong>Tipo de migración</strong></th>
<th><strong>Qué se migra</strong></th>
 <th><strong>Qué no se migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></td>
<td>Una o varias fases</td>
<td><ul>
<li> Documentos </li>
<li> Estructura de archivos y carpetas </li>
<li> Permisos de archivos y carpetas del nivel del usuario* </li>
<li> Permisos de archivos y carpetas del nivel del grupo* </li>
<li> Archivos de menos de 15 GB </li>
<li> Metadatos básicos de documentos y carpetas:
<ul>
<li> Fecha de creación </li>
<li> Fecha de modificación </li>
<li> Creada por </li>
<li> Última modificación </li>
</ul></li>
</ul>
* Se requiere la configuración de sincronización de directorios. Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows. No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos. Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</td>
<td><ul>
<li> Versiones anteriores e historial de propiedad </li>
<li> Conversión de URL insertadas en el contenido </li>
<li> Versiones anteriores </li>
<li> Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto) </li>
<li> Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows: </li>
<li> Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal) </li>
<li> Configuración de auditoría de NTFS </li>
<li> Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI) </li>
<li> Documentos inaccesibles o dañados </li>
<li> Recursos compartidos ocultos </li>
<li> Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido) </li>
<li> Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Un solo entorno de G Suite (solo Google Drive)</strong></td>
<td>Una o varias fases</td>
<td><ul>
<li> Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office), incluidos los de más de 10 MB </li>
<li> Estructura de archivos y carpetas </li>
<li> Permisos de carpeta de nivel de usuario </li>
<li> Permisos de carpeta de nivel de grupo </li>
<li> Archivos de menos de 15 GB </li>
<li> Metadatos básicos de documentos y carpetas:
<ul>
<li> Fecha de creación </li>
<li> Fecha de modificación </li>
<li> Creada por </li>
<li> Última modificación </li>
</ul></li>
<li> Unidades compartidas (carpetas y archivos) </li>
<li> Contenido compartido propiedad de la cuenta de Google Drive que se migra </li>
</ul></td>
<td><ul>
<li> Comentarios, versiones anteriores e historial de propiedad </li>
<li> Descripciones de archivos y carpetas, colores de las carpetas </li>
<li> Permisos de archivo de nivel de usuario </li>
<li> Permisos de archivo de nivel de grupo </li>
<li> Metadatos avanzados </li>
<li> Atributos de bloqueo de archivos </li>
<li> Conversión de URL insertadas en el contenido </li>
<li> Elementos desechados </li>
<li> Documentos inaccesibles o dañados </li>
<li> Usuarios bloqueados o inactivos </li>
<li> Google Fotos, Formularios de Google, Google Maps y otras aplicaciones conectadas </li>
<li> Dibujos de Google </li>
<li> Contenido de uso compartido que es externo a su organización </li>
<li> Contenido que no es propiedad de la cuenta de Google Drive que se migra </li>
<li> Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos. Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración). </li>
<li> Permisos de suscripción a una unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas. Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración). </li>
<li> Archivos marcados como restringidos o no copiables </li>
<li> Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Una o varias fases</td>
<td><ul>
<li> Documentos </li>
<li> Estructura de archivos y carpetas </li>
<li> Permisos de carpeta de nivel de usuario </li>
<li> Permisos de carpeta de nivel de grupo </li>
<li> Archivos de menos de 15 GB </li>
<li> Metadatos básicos de documentos y carpetas:
<ul>
<li> Fecha de creación </li>
<li> Fecha de modificación </li>
<li> Creada por </li>
<li> Última modificación </li>
</ul></li>
<li> Contenido compartido que es propiedad de la cuenta de Box que se va a migrar </li>
</ul></td>
<td><ul>
<li> Comentarios, versiones anteriores e historial de propiedad </li>
<li> Descripciones de archivos y carpetas </li>
<li> Permisos de archivo de nivel de usuario </li>
<li> Permisos de archivo de nivel de grupo </li>
<li> Metadatos avanzados y etiquetas de Box </li>
<li> Atributos de bloqueo de archivos </li>
<li> Conversión de URL insertadas en el contenido </li>
<li> Elementos desechados </li>
<li> Documentos inaccesibles o dañados </li>
<li> Usuarios bloqueados o inactivos </li>
<li> Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo </li>
<li> Contenido que no es propiedad de la cuenta de Box migrada </li>
<li> Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos. Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración). </li>
<li> Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox para Equipos (estándar y avanzado)</strong></td>
<td>Una o varias fases</td>
<td><ul>
<li> Documentos </li>
<li> Estructura de archivos y carpetas </li>
<li> Permisos de carpeta de nivel de usuario </li>
<li> Permisos de carpeta de nivel de grupo </li>
<li> Archivos de menos de 15 GB </li>
<li> Metadatos básicos de documentos y carpetas:
<ul>
<li> Fecha de creación </li>
<li> Fecha de modificación </li>
<li> Creada por </li>
<li> Última modificación </li>
</ul></li>
<li> Contenido y carpetas de equipo de uso compartido </li>
<li> Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar </li>
</ul></td>
<td><ul>
<li> Comentarios, versiones anteriores e historial de propiedad </li>
<li> Descripciones de archivos y carpetas </li>
<li> Permisos de archivo de nivel de usuario </li>
<li> Permisos de archivo de nivel de grupo </li>
<li> Metadatos avanzados </li>
<li> Atributos de bloqueo de archivos </li>
<li> Conversión de URL insertadas en el contenido </li>
<li> Elementos desechados </li>
<li> Documentos inaccesibles o dañados </li>
<li> Carpetas de Dropbox desmontadas </li>
<li> Usuarios eliminados o desconectados </li>
<li> Dropbox Paper, Showcases y Spaces </li>
<li> Aplicaciones y favoritos de Dropbox (Pins/Estrellas) </li>
<li> Contenido que no es propiedad de la cuenta de Dropbox migrada </li>
<li> Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos. Informe a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración) </li>
<li> Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilidades de FastTrack

Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración. Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.

## <a name="your-responsibilities"></a>Sus responsabilidades

Usted realizará actividades estándares durante el proyecto de migración. Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.

Usted también realizará las siguientes actividades, específicas para las migraciones de SharePoint Online:

  - Aprovisionamiento de todos los sitios del grupo de SharePoint que se incluirán en los eventos de migración.

## <a name="migration-to-onedrive-for-business"></a>Migración a OneDrive para la Empresa

Cuando elige usar FastTrack para migrar sus archivos a OneDrive para la Empresa, proporcionamos instrucciones de migración y servicios de migración de datos. Le proporcionamos instrucciones para ayudarle a planear su migración, configurar sus entornos de origen y de OneDrive para la Empresa, y aprovechar nuestros servicios de migración de datos para migrar sus archivos. Cree y programe sus eventos de migración. Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado. Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a OneDrive para la Empresa.

## <a name="considerations"></a>Consideraciones

  - Todas las migraciones están sujetas a las cuotas de OneDrive para la Empresa. Consulte los [<span class="underline">Límites de software de SharePoint Online y OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más información.
  - Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).
  - FastTrack realiza la migración solo para las unidades activas de OneDrive para la Empresa.

## <a name="source-environment-details"></a>Detalles del entorno de origen

Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:

  - Recursos compartidos de archivos (recursos compartidos de archivos de SMB en dispositivos compatibles a partir de SMB 2.0).
  - Un solo entorno de G Suite (solo Google Drive)
  - Box (Starter, Business, Enterprise).
  - Dropbox para Equipos (estándar y avanzado).

En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:

<table>
<thead>
<tr class="header">
 <th><strong>Entorno de origen</strong></th>
 <th><strong>Tipo de migración</strong></th>
 <th><strong>Qué se migra</strong></th>
 <th><strong>Qué no se migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></td>
<td>Una o varias fases</td>
<td><ul>
<li> Documentos </li>
<li> Estructura de archivos y carpetas </li>
<li> Permisos de archivos y carpetas del nivel del usuario* </li>
<li> Permisos de archivos y carpetas del nivel del grupo* </li>
<li> Archivos de menos de 15 GB </li>
<li> Metadatos básicos de documentos y carpetas:
<ul>
<li> Fecha de creación </li>
<li> Fecha de modificación </li>
<li> Creada por </li>
<li> Última modificación </li>
</ul></li>
</ul>
<br>
* Se requiere la configuración de sincronización de directorios. Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows. No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos. Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB. </td>
<td><ul>
<li> Versiones anteriores e historial de propiedad </li>
<li> Conversión de URL insertadas en el contenido </li>
<li> Versiones anteriores </li>
<li> Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto) </li>
<li> Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows: </li>
<li> Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal) </li>
<li> Configuración de auditoría de NTFS </li>
<li> Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI) </li>
<li> Documentos inaccesibles o dañados </li>
<li> Recursos compartidos ocultos </li>
<li> Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido) </li>
<li> Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Un solo entorno de G Suite (solo Google Drive)</strong></td>
<td>Una o varias fases</td>
<td><ul>
<li> Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office, incluidos los de más de 10 MB) </li>
<li> Estructura de archivos y carpetas </li>
<li> Permisos de carpeta de nivel de usuario </li>
<li> Permisos de carpeta de nivel de grupo </li>
<li> Archivos de menos de 15 GB </li>
<li> Metadatos básicos de documentos y carpetas:
<ul>
<li> Fecha de creación </li>
<li> Fecha de modificación </li>
<li> Creada por </li>
<li> Última modificación </li>
</ul></li>
<li> Unidades compartidas (carpetas y archivos) </li>
<li> Contenido compartido propiedad de la cuenta de Google Drive que se migra </li>
</ul></td>
<td><ul>
<li> Comentarios, versiones anteriores e historial de propiedad </li>
<li> Descripciones de archivos y carpetas, colores de las carpetas </li>
<li> Permisos de archivo de nivel de usuario </li>
<li> Permisos de archivo de nivel de grupo </li>
<li> Metadatos avanzados </li>
<li> Atributos de bloqueo de archivos </li>
<li> Conversión de URL insertadas en el contenido </li>
<li> Elementos desechados </li>
<li> Documentos inaccesibles o dañados </li>
<li> Usuarios bloqueados o inactivos </li>
<li> Formularios de Google Photos, Maps y otras aplicaciones conectadas </li>
<li> Dibujos de Google </li>
<li> Contenido de uso compartido que es externo a su organización </li>
<li> Contenido que no es propiedad de la cuenta de Google Drive que se migra </li>
<li> Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos. Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración). </li>
<li> Permisos de suscripción de la unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas. Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración). </li>
<li> Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Una o varias fases</td>
<td><ul>
<li> Documentos </li>
<li> Estructura de archivos y carpetas </li>
<li> Permisos de carpeta de nivel de usuario </li>
<li> Permisos de carpeta de nivel de grupo </li>
<li> Archivos de menos de 15 GB </li>
<li> Metadatos básicos de documentos y carpetas:
<ul>
<li> Fecha de creación </li>
<li> Fecha de modificación </li>
<li> Creada por </li>
<li> Última modificación </li>
</ul></li>
<li> Contenido compartido que es propiedad de la cuenta de Box que se va a migrar </li>
</ul></td>
<td><ul>
<li> Comentarios, versiones anteriores e historial de propiedad </li>
<li> Descripciones de archivos y carpetas </li>
<li> Permisos de archivo de nivel de usuario </li>
<li> Permisos de archivo de nivel de grupo </li>
<li> Metadatos avanzados y etiquetas de Box </li>
<li> Atributos de bloqueo de archivos </li>
<li> Conversión de URL insertadas en el contenido </li>
<li> Elementos desechados </li>
<li> Documentos inaccesibles o dañados </li>
<li> Usuarios bloqueados o inactivos </li>
<li> Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo </li>
<li> Contenido que no es propiedad de la cuenta de Box migrada </li>
<li> Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos. Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración). </li>
<li> Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox para Equipos (estándar y avanzado)</strong></td>
<td>Una o varias fases</td>
<td><ul>
<li> Documentos </li>
<li> Estructura de archivos y carpetas </li>
<li> Permisos de carpeta de nivel de usuario </li>
<li> Permisos de carpeta de nivel de grupo </li>
<li> Archivos de menos de 15 GB </li>
<li> Metadatos básicos de documentos y carpetas:
<ul>
<li> Fecha de creación </li>
<li> Fecha de modificación </li>
<li> Creada por </li>
<li> Última modificación </li>
</ul></li>
<li> Contenido y carpetas de equipo de uso compartido </li>
<li> Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar </li>
</ul></td>
<td><ul>
<li> Comentarios, versiones anteriores e historial de propiedad </li>
<li> Descripciones de archivos y carpetas </li>
<li> Permisos de archivo de nivel de usuario </li>
<li> Permisos de archivo de nivel de grupo </li>
<li> Metadatos avanzados </li>
<li> Atributos de bloqueo de archivos </li>
<li> Conversión de URL insertadas en el contenido </li>
<li> Elementos desechados </li>
<li> Documentos inaccesibles o dañados </li>
<li> Carpetas de Dropbox desmontadas </li>
<li> Usuarios eliminados o desconectados </li>
<li> Dropbox Paper, Showcases y Spaces </li>
<li> Aplicaciones y favoritos de Dropbox (Pins/Estrellas) </li>
<li> Contenido que no es propiedad de la cuenta de Dropbox migrada </li>
<li> Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos. Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración). </li>
<li> Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Responsabilidades de FastTrack

Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración. Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.

## <a name="your-responsibilities"></a>Sus responsabilidades

Usted realizará actividades estándares durante el proyecto de migración. Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.

También realizará las siguientes actividades, específicas para las migraciones de OneDrive para la Empresa:

  - Aprovisionamiento de todos los sitios de OneDrive para la Empresa que se incluirán en los eventos de migración.
