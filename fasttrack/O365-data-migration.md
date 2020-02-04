---
title: Migración de datos
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 2/04/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Los especialistas de FastTrack ofrecen instrucciones sobre los pasos para la migración de datos a Office 365. Esto está disponible para todos los clientes aptos con servicios de Office 365 para Exchange Online, OneDrive para la Empresa y SharePoint Online.
ms.openlocfilehash: 7446a22f1389085220a99c01a6c10c5b7bcde6ae
ms.sourcegitcommit: 7365d80b2e4291e547c2d84b94da02697221abc9
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 02/03/2020
ms.locfileid: "41677060"
---
# <a name="data-migration"></a>Migración de datos

Los especialistas de FastTrack proporcionan orientación sobre los pasos para la migración de datos a Office 365. Le ayudaremos mediante una combinación de herramientas y documentación, además de realizar una serie de tareas de configuración cuando corresponda y sea factible. Está disponible para todos los clientes elegibles con servicios de Office 365 para Exchange Online, OneDrive para la Empresa y SharePoint Online.
  
Los servicios de migración de datos descritos en la tabla siguiente están disponibles para los espacios empresariales de Office 365 con 500 licencias o más\*. Por ejemplo, en sus entornos de origen puede haber datos que quiera migrar a Office 365. El beneficio de Centro FastTrack incluye proporcionar ayuda con la integración del entorno de origen para facilitar la migración del contenido.
  
\* Si ha adquirido o renovado un plan comercial antes del 1 de septiembre de 2017, es necesario que cuente con 150 puestos como mínimo durante todo el período de la suscripción actual para beneficiarse del servicio de migración. Para planes educativos, solo las licencias de pago de profesores y personal son aptas para los servicios de migración. 
  
> [!NOTE]
> Los datos que se migran a través de los servicios de FastTrack se pueden transferir, almacenar y procesar en cualquier lugar donde Microsoft disponga de instalaciones (excepto cuando su compromiso determinado con FastTrack especifique lo contrario). Los servicios de FastTrack no están diseñados ni destinados a su uso con datos sujetos a requisitos legales o normativos especiales. 
  
> [!NOTE]
> Los problemas imprevistos (incluyendo, entre otros, elementos ilegibles o dañados en el entorno de origen) pueden impedir que algunos elementos se migren. 
  
> [!NOTE]
> La asistencia para la migración está disponible en chino tradicional y simplificado (el personal solo habla mandarín), en inglés, en francés, en alemán, en italiano, en japonés, en portugués (de Brasil) y en español. 
  
> [!NOTE]
> Si la integración es necesaria, el entorno de origen debe estar al nivel mínimo para dicha aplicación. 
  
En la siguiente tabla se describe lo que se espera para la migración en el entorno de origen existente.
  

|**Actividad**|**Expectativa del entorno de origen**|
|:-----|:-----|
|**Migración de Exchange Online**  <br/> | Microsoft migra, uno a uno, cualquier combinación de los entornos de origen que se indican a continuación. Podemos migrar el sistema de mensajería que se haya incorporado mediante el Centro de FastTrack o que haya superado las comprobaciones del Centro de FastTrack. Esto incluye:  <br/>  Uno o varios bosques de Active Directory con una o varias organizaciones de Exchange si se realiza una implementación híbrida de Exchange 2010 en adelante en cada organización y los sistemas de correo de Exchange van del 2003 en adelante.  <br/> Un solo entorno a partir de IBM Domino 7.0.3 ( [Apéndice A: Migración de IBM Domino a Exchange Online](O365-from-ibm-domino-to-exchange-online.md)).  <br/>  Un solo entorno de correo electrónico compatible con IMAP.  <br/>  Entornos de G Suite (solo Gmail, Contactos y Calendario)  <br/>  Un solo entorno a partir de Novell GroupWise 7.0.4.  <br/> <br/> **Nota** *La incorporación de Exchange Online debe realizarse antes de la migración.* <br/> <br/> **Nota** *FastTrack solo migra a buzones de Office 365 activos.* <br/> <br/> **Nota** *Para conocer las dependencias de Exchange local, vea [Requisitos previos de implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).* <br/><br/> **Nota** *Estas migraciones se producen consecutivamente al migrar varios entornos de mensajería de origen (por ejemplo, varias organizaciones de Exchange o varios dominios de Domino).*| 
|**Migración de SharePoint Online**  <br/> | Recursos compartidos de archivos (recursos compartidos de archivos del Bloque de mensajes del servidor, o SMB, en dispositivos compatibles a partir SMB 2.0).  <br/>  Box (Starter, Business, Enterprise).  <br/> |
|**Migración de OneDrive para la Empresa**  <br/> | Recursos compartidos de archivos (recursos compartidos de archivos de SMB en dispositivos compatibles a partir de SMB 2.0).  <br/>  Un solo entorno de G Suite (solo Google Drive).  <br/>  Box (Starter, Business, Enterprise). <br/> <br/> **Nota** *FastTrack solo migra a unidades de disco de Office 365 activas.*|
   
## <a name="migration-to-exchange-online"></a>Migración a Exchange Online

### <a name="enable-to-migrate"></a>Habilitar la migración
  
Si usa Microsoft para migrar su correo electrónico, le proporcionaremos ayuda para habilitar Exchange Online y el entorno de origen para la migración. Según el origen, podemos llevar a cabo varios pasos de habilitación. Proporcionamos ayuda mediante el uso de una combinación de herramientas y documentación y realizando tareas de configuración donde sea pertinente y viable. Según los parámetros aplicables, migramos los buzones, los trabajos de monitor y proporcionamos informes de estado.
  
Puede que Microsoft requiera el acceso y los permisos adecuados en su sistema de correo con el fin de realizar actividades de migración.
  
### <a name="migration-policy-and-steps"></a>Pasos y directiva de migración
  
> [!NOTE]
> Una franja temporal de migración también se denomina lote de migración.

#### <a name="commercial-and-uk-government"></a>Comercial y organismos gubernamentales del Reino Unido

Las migraciones se realizan con una regularidad programada y normalizada las 24 horas al día y durante siete (7) días laborables a la semana (24x7) en franjas temporales de migración predefinidas. Hay tres lotes de migración por día de migración.

#### <a name="us-governmentdod"></a>Gobierno de Estados Unidos o DOD

Las migraciones se realizan con una regularidad programada y normalizada las 24 horas al día y durante cinco (5) días laborables a la semana (24x5) en franjas temporales de migración predefinidas. Hay tres lotes de migración por día de migración. Hay cinco días de migración en una semana del lunes a las 2:00 de la hora universal coordinada (UTC) al viernes a la medianoche UTC, lo que significa que la última migración programada es el viernes a las 20:00 UTC.
    
 ### <a name="end-state"></a>Estado final
  
El estado final esperado después de un lote de migración incluye lo siguiente:
- Los datos de los buzones de origen elegibles y programados adecuadamente en el entorno de origen se migran a Office 365. 
- Un informe posterior a la migración para el lote de migración proporcionado por Microsoft.
    
El estado final esperado una vez finalizadas todas las migraciones incluye lo siguiente:
- Los datos de los buzones de origen pertinentes se migran a Office 365 tal como se define en la tabla siguiente.
- El tipo de datos que se van a migrar depende del entorno de origen, tal como se describe en la tabla siguiente.
    
> [!NOTE]
> Todos los entornos de origen deben estar en el nivel de los últimos Service Pack (SP) y paquetes acumulativos o actualizaciones acumulativas para el producto correspondiente en el entorno de origen al final de la fase de habilitación. Los servicios de migración de datos están sujetos a factores externos y ajenos al control de Microsoft, como pueden ser los cambios en las interfaces de programación de aplicaciones (API) de terceros, que podrían provocar cambios, retrasos o la suspensión de estos servicios. Durante la vigencia de los servicios de FastTrack, los datos que ponga a disposición de Microsoft estarán accesibles y se almacenarán en cualquier lugar en que Microsoft y sus proveedores dispongan de instalaciones. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Entorno de origen**|**Tipo de migración**|**¿Qué se migrará desde el buzón de origen?**|**¿Qué no se migrará?**|
|**Exchange 2003 o superior**|Total| Mensajes de correo electrónico <br/> Reglas de buzón <br/> Delegados <br/> Contactos de buzón de correo <br/> Calendario <br/> Tareas <br/> Correos electrónicos con derechos administrados <br/> Correos electrónicos cifrados| Carpetas públicas <br/> Contactos personales <br/> Usuarios habilitados para correo <br/> Usuarios bloqueados o inactivos <br/> Firmas <br/> Contenedor del buzón <br/>  Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Datos de archivo <br/> Elementos dañados <br/>  Buzones de correo inactivos |
|**Exchange 2003 y Exchange 2007**|Preconfigurada| Mensajes de correo electrónico <br/> Reglas de buzón <br/> Delegados <br/> Contactos de buzón de correo <br/> Calendario <br/> Tareas <br/> Correos electrónicos con derechos administrados <br/> Correos electrónicos cifrados| Carpetas públicas <br/> Contactos personales <br/> Usuarios habilitados para correo <br/> Usuarios bloqueados o inactivos <br/> Firmas <br/> Contenedor del buzón <br/> Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Datos de archivo <br/> Elementos dañados <br/> Buzones de correo inactivos |
|**Exchange 2010, Exchange 2013 y Exchange 2016** <br/><br/> **Nota** *Para conocer las dependencias de Exchange local, vea [Requisitos previos de implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).*           |Migración con implementación híbrida| Mensajes de correo electrónico <br/> Reglas de buzón <br/> Delegados <br/> Contactos de buzón de correo <br/> Calendario <br/> Tareas <br/> Firmas <br/> Archivo personal migrado con el buzón del usuario <br/> Elementos recuperables <br/> Correos electrónicos con derechos administrados <br/> Correos electrónicos cifrados| Carpetas públicas <br/> Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Archivo de registro en diario o cualquier solución de archivo de terceros <br/> Usuarios bloqueados o inactivos <br/> Datos de archivo procedentes de archivos PST (Personal Storage Table) <br/> Elementos dañados <br/> Buzones de correo inactivos |
|**Entorno de G Suite (solo Gmail, Contactos y Calendario)** <br/> <br/> **Nota** *Su entorno de G Suite debe tener la API de Google y el SDK del administrador de Google habilitados para ampliar la funcionalidad.* <br/> <br/> **Nota** *Ubicación de los datos: FastTrack puede transferir, almacenar y procesar datos migrados según la ubicación del espacio empresarial del cliente en Estados Unidos o allí donde Microsoft o sus proveedores de terceros dispongan de instalaciones. FastTrack elimina los datos almacenados en un plazo de 30 días desde la finalización de los servicios aplicables.*           |Total o preconfigurada| Mensajes de correo electrónico <br/> Contactos de correo <br/> Calendario <br/> Etiquetas | Reglas <br/> Delegados <br/> Firmas <br/> Tareas <br/> Cualquier correo electrónico o archivo adjunto superior a 35 MB <br/> Usuarios bloqueados o inactivos <br/> Datos de archivo procedentes de archivos PST o de soluciones de archivo de terceros (por ejemplo, Google Vault) <br/> Mensajes de correo electrónico cifrados o con derechos administrados <br/> Elementos dañados <br/> Google Hangouts <br/> Grupos de Google <br/> Buzones de recursos <br/> Buzones de correo inactivos |
|**A partir de IBM Domino 7.0.3** ([Apéndice A: Migración de IBM Domino a Exchange Online](O365-from-ibm-domino-to-exchange-online.md))|Preconfigurada| Mensajes de correo electrónico: últimos 90 días <br/> Calendario: últimos 90 días y elementos futuros <br/> Contactos de buzón de correo: todos <br/> Tareas: todas <br/> Salas y recursos: siempre y cuando se implementen con la plantilla estándar <br/> Los archivos de correo, incluidos los archivos de correo compartido, deben usar la plantilla estándar de correo | Firmas <br/> Reglas de buzón <br/> Delegados <br/> Elementos cifrados <br/> Vínculos de documentos <br/> Diseño de fondo del usuario <br/> Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Usuarios bloqueados o inactivos <br/> Datos de archivo <br/> Elementos dañados <br/> Coexistencia de Calendario <br/> Buzones de correo inactivos |
|**A partir de Novell GroupWise 7.0.4** <br/><br/> **Nota** *Ubicación de los datos: FastTrack puede transferir, almacenar y procesar datos migrados según la ubicación del espacio empresarial del cliente en Estados Unidos o allí donde Microsoft o sus proveedores de terceros dispongan de instalaciones. FastTrack elimina los datos almacenados en un plazo de 30 días desde la finalización de los servicios aplicables.*           |Preconfigurada| Mensajes de correo electrónico <br/> Calendario <br/> Contactos de buzón de correo <br/> Grupos personales <br/> Tareas (con limitaciones) <br/> Documentos | Rules <br/> Proxies/delegados/conversión de lista de control de acceso (ACL) <br/> Firmas <br/> Categorías de contactos <br/> Correo electrónico cifrado <br/> Carpetas de búsqueda <br/> Cualquier correo electrónico o archivo adjunto superior a 35 MB <br/> Usuarios bloqueados o inactivos <br/> Datos de archivo <br/> Elementos cifrados o con derechos administrados <br/> Elementos dañados <br/> Coexistencia de Calendario <br/> Buzones de correo inactivos |
|**Origen de IMAP4** |Migración con herramientas nativas de IMAP4| Mensajes de correo electrónico | Reglas <br/> Delegados <br/> Listas de distribución <br/> Contactos externos <br/> Usuarios habilitados para correo <br/> Usuarios bloqueados o inactivos <br/> Contactos de buzón de correo <br/> Calendario <br/> Firmas <br/> Tareas <br/> Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Datos de archivo <br/> Correo electrónico cifrado <br/> Elementos dañados <br/> Buzones de correo inactivos |
   
> [!NOTE]
> Si las listas de distribución (objetos MailEnabledGroup) y los contactos externos (objetos MailEnabledContact) están en el Active Directory local, se pueden sincronizar con Azure AD Connect. Sin embargo, no forman parte de la migración de datos de buzones. Para obtener más información, vea el ejemplo **Integración de identidad** de [Core](O365-onboarding-and-migration.md#core) (Incorporación central). 
  
Durante las migraciones, los especialistas de FastTrack realizan las siguientes operaciones:
- Proporcionar una plantilla estándar para la programación de migraciones de buzones.
- Proporcionar información sobre los permisos necesarios para los especialistas de FastTrack. 
- Recopilar la programación de migración de buzones de correo predeterminados en el formato predeterminado.
- Intentar realizar la migración de un único buzón hasta dos veces en un lote de migración antes de generar un informe sobre dicho buzón como una migración errónea.
- Para los entornos de origen basados en Exchange e IMAP4, se puede migrar contenido hasta el 85 % del límite de almacenamiento del buzón de usuario (por ejemplo, si el límite de almacenamiento del buzón es de 50 GB, Microsoft migra hasta el 85 % de 50 GB). 
- Habilitar la coexistencia de enrutamiento de correo SMTP entre el entorno de mensajería de origen y Office 365 Exchange Online a menos que se esté usando la migración total.
- Proporcionar informes posteriores a la migración.
- Proporcionar asistencia posterior a la migración cuando haya problemas críticos. Los siguientes problemas se consideran críticos:
  - Pérdida de datos durante la migración.
  - El entorno de origen no está disponible durante la migración.
  - Las actividades de migración provocan problemas en el entorno de origen.
    
Durante las migraciones, el usuario realiza las siguientes operaciones:
- Completar la incorporación de Exchange Online o realizar las comprobaciones requeridas con el Centro FastTrack.
- Controlar las comunicaciones con los usuarios finales.  
- Instalar el nivel adecuado de software cliente según las directrices de Office 365. Para más información, vea [Office 365 para empresas](https://go.microsoft.com/fwlink/?linkid=2005429). 
- Validar la coexistencia de enrutamiento de correo SMTP entre el entorno de mensajería de origen y Office 365 Exchange Online si procede.
- Proporcionar una programación en un método definido y una lista de buzones de correo específicos para migrar por cada evento de migración con al menos 3 días de antelación. Para migraciones de Notes, deberá proporcionar la programación con 21 días de antelación.
- Quitar los buzones de correo de la programación hasta 24 horas antes del lote de migración. Esto debe corresponderse con el lote de migración final.
- Programar un promedio de destino de buzones de correo en un período de 24 horas, tal como se muestra en la tabla siguiente.
    
|||
|:-----|:-----|
|**Número de buzones elegibles de migración** <br/> |**Promedio mínimo de buzones de correo en un período de 24 horas** <br/> |
|150-1000  <br/> |25 % del total  <br/> |
|1.001-5.000  <br/> |20 % del total  <br/> |
|5.001-10.000  <br/> |15 % del total  <br/> |
|\>10 000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > Estas cifras se basan en los procedimientos recomendados. Aunque el número de buzones que se migran al día varía en función de las restricciones del entorno, la preparación y la empresa. Microsoft no puede garantizar la velocidad de migración de los buzones de correo. 
  
- Programar un mínimo de 35 buzones en un lote de migración. 
- Corregir los errores previos a la migración (si procede).  
- Proporcionar a los especialistas de FastTrack acceso y permisos al entorno de origen, para que puedan realizar actividades de migración. 
- Adquirir o proporcionar cuentas administrativas con licencia en Office 365 para realizar actividades de migración (según corresponda). 
- Prestar asistencia con los problemas de migración del lado cliente y ejecutar operaciones posteriores a las migraciones cuando sea necesario. 
- Migrar datos del lado cliente si lo desea. Esto incluye, entre otras cosas, las libretas de direcciones locales, los datos en los archivos PST locales, las reglas de Outlook y la configuración local de Outlook.   
- Reducir el tamaño del buzón por debajo del 85 % del límite del buzón de Office 365 de destino (si procede).   
- Controlar las acciones del informe posterior a la migración, incluidos los buzones que no se movieron.  
- Corregir errores posteriores a la migración y volver a programar los buzones de correo (si procede).   
- Prestar asistencia tras la migración para problemas críticos. Los siguientes problemas se consideran críticos:
  - Pérdida de datos durante la migración.
  - El entorno de origen no está disponible durante la migración.
  - Las actividades de migración provocan problemas en el entorno de origen.
    
Debe seguir el proceso de migración estándar y colaborar con Microsoft adecuadamente. Esto incluye proporcionar acceso y permisos a los entornos de origen y de Office 365, proporcionar programaciones de migración, corregir las causas de los errores de migración, etc. También debe colaborar con los usuarios finales para las comunicaciones, la programación de la migración de buzones y la administración de los problemas relativos a la migración.
  
> [!NOTE]
> Las migraciones solo utilizan cuentas que cumplan con los requisitos de seguridad definidos durante la incorporación. Si no utiliza dichas cuentas, es posible que experimente demoras en la migración. 
  
## <a name="migration-to-sharepoint-online"></a>Migración a SharePoint Online

### <a name="enable-to-migrate"></a>Habilitar la migración
  
Si usa Microsoft para migrar datos, le proporcionamos ayuda para habilitar SharePoint Online y el entorno de origen para la migración. Según el origen, podemos llevar a cabo varios pasos de habilitación. Le ayudamos usando una combinación de herramientas y documentación, y realizando tareas de configuración cuando corresponda y sea viable.
  
Necesita proporcionar a Microsoft el acceso y los permisos adecuados para que lleve a cabo algunas actividades.
  
### <a name="migration-policy-and-steps"></a>Pasos y directiva de migración
  
> [!NOTE]
> Una franja temporal de migración también se denomina lote de migración.

#### <a name="commercial-and-uk-government"></a>Comercial y organismos gubernamentales del Reino Unido

Las migraciones se realizan con una regularidad programada y normalizada las 24 horas al día y durante siete (7) días laborables a la semana (24x7) en franjas temporales de migración predefinidas. Hay tres lotes de migración por día de migración.

#### <a name="us-governmentdod"></a>Gobierno de Estados Unidos o DOD

Las migraciones se realizan con una regularidad programada y normalizada las 24 horas al día y durante cinco (5) días laborables a la semana (24x5) en franjas temporales de migración predefinidas. Hay tres lotes de migración por día de migración. Hay cinco días de migración en una semana del lunes a las 2:00 de la hora universal coordinada (UTC) al viernes a la medianoche UTC, lo que significa que la última migración programada es el viernes a las 20:00 UTC.

- Todas las migraciones están sujetas a las cuotas de SharePoint Online indicadas en [SharePoint Online y OneDrive para la Empresa: restricciones y límites del software](https://go.microsoft.com/fwlink/?LinkID=616612).   
- La cantidad general de datos migrados se limitará al 75% de la cuota de almacenamiento general de SharePoint Online a la que tiene derecho (incluido el almacenamiento adicional que haya adquirido por separado).
    
 ### <a name="end-state"></a>Estado final
  
El estado final esperado después de un lote de migración incluye lo siguiente: 
- Los datos de los orígenes elegibles y programados adecuadamente en el entorno de origen se migran a SharePoint Online.   
- Un informe posterior a la migración para el lote de migración proporcionado por Microsoft.
    
El estado final esperado una vez finalizadas todas las migraciones incluye lo siguiente: 
- Los datos de los orígenes pertinentes se migran a Office 365 tal como se define en la tabla siguiente.  
- El tipo de datos que se van a migrar depende del entorno de origen, tal como se describe en la tabla siguiente:
    
|||||
|:-----|:-----|:-----|:-----|
|**Entorno de origen** <br/> |**Tipo de migración** <br/> |**Qué se va a migrar** <br/> |**¿Qué no se migrará?** <br/> |
|**Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de archivos y carpetas de nivel de usuario\*  <br/>  Permisos de archivos y carpetas de nivel de grupo\*  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/><br/> \**Se requiere la configuración de sincronización de directorios. Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows. No se migran permisos administrados directamente en dispositivos de recursos compartidos de archivos. Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.* <br/> | Versiones anteriores e historial de propiedad  <br/>  Conversión de URL insertadas en el contenido  <br/>  Versiones anteriores  <br/>  Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)  <br/>  Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:  <br/>  Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)  <br/>  Configuración de auditoría de NTFS  <br/>  Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)  <br/>  Documentos inaccesibles o dañados  <br/>  Recursos compartidos ocultos  <br/>  Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpetas de nivel de usuario  <br/>  Permisos de carpetas de nivel de grupo  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/>  Contenido de uso compartido propiedad de la cuenta de Box que se migra (si se ha compartido explícitamente con usuarios o grupos)\*  <br/><br/> \**Use informes de Box para identificar cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> | Comentarios, versiones anteriores e historial de propiedad <br/>  Permisos de archivos de nivel de usuario  <br/>  Permisos de archivos de nivel de grupo  <br/>  Descripciones de archivos y carpetas  <br/>  Metadatos avanzados y etiquetas de Box  <br/>  Atributos de bloqueo de archivos  <br/>  Conversión de URL insertadas en el contenido  <br/>  Elementos desechados  <br/>  Documentos inaccesibles o dañados  <br/>  Usuarios bloqueados o inactivos  <br/>  Notas de Box (no funcional debido a que migran sin conversión)  <br/>  Flujos de trabajo, Favoritos, Marcadores y aplicaciones de Box  <br/>  Contenido que no pertenece a la cuenta migrada de Box (carpetas compartidas)  <br/>  Permisos y metadatos básicos de usuarios externos\*  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
   
Durante las migraciones, los especialistas de FastTrack realizan las siguientes operaciones: 
- Ofrecer un tutorial sobre la migración que abarca el proceso y el enfoque referentes al escenario de la migración seleccionada.
- Proporcionar los requisitos previos de las herramientas de evaluación y migración que correspondan al escenario.   
- Proporcionar los requisitos previos para el acceso del equipo de migración al entorno de origen y destino a efectos de evaluación y migración. 
- Ofrecer herramientas de evaluación para realizar evaluaciones del entorno de origen y destino o proporcionar instrucciones sobre cómo usar las funciones de plataforma de origen nativas para crear informes de evaluación.   
- Ayudar a implementar y ejecutar las herramientas de evaluación y migración (si es el caso).   
- Configurar la infraestructura de migración en preparación para la migración de contenido (si es aplicable).    
- Realizar una migración de prueba limitada para validar la infraestructura de migración y los requisitos previos necesarios.   
- Aprovisionar sitios de destino de SharePoint Online listos para su uso como parte de la migración.    
- Realizar una migración piloto antes de la migración de velocidad.   
- Proporcionar instrucciones sobre la programación de la migración para el escenario seleccionado. 
- Llevar a cabo ondas de migración de velocidad de contenido de acuerdo con la programación de migración que proporcione el cliente y que los recursos FastTrack hayan validado.   
- Proporcionar resultados de migración después de cada ventana de migración.   
- Participar en la clasificación de los problemas de migración de velocidad y proporcionar instrucciones sobre las posibles opciones de corrección.   
- Proporcionar un informe de migración final para cada ventana de migración de velocidad.   
- Proporcionar asistencia después de la migración durante las pruebas de aceptación de usuario a lo largo de cinco días tras la finalización de la migración.
    
Durante las migraciones, el usuario realiza las siguientes operaciones: 
- Proporcionar recursos de proyecto recomendados para actividades de evaluación y migración. Entre ellos se incluyen: 
  - Administración de proyectos. 
  - Prueba de aceptación del usuario (UAT).  
  - Administradores responsables de las plataformas de contenido de origen y de destino.  
- Proporcionar los requisitos previos de la infraestructura para las actividades de evaluación y migración (si es necesario).  
- Proporcionar a los especialistas de FastTrack acceso y permisos al entorno de origen y destino, para que puedan realizar actividades de migración (si es necesario).
    > [!NOTE]
    > Las migraciones solo utilizan cuentas que cumplan con los requisitos de seguridad definidos durante la incorporación. Si no utiliza dichas cuentas, es posible que experimente demoras en la migración. 
- Proporcionar los requisitos previos y realizar actividades necesarias para admitir la evaluación y la migración.   
- Instalar las herramientas de evaluación que proporciona FastTrack y completar las actividades de recopilación de datos de evaluación (si es aplicable).   
- Instalar localmente el software de migración que proporciona FastTrack (si es el caso).   
- Completar las actividades de corrección indicadas en el informe de corrección de FastTrack (si corresponde).  
- Proporcionar una programación de migración mediante las plantillas y las instrucciones de FastTrack.   
- Realizar un control de calidad de migración y pruebas de aceptación de usuario.   
- Realizar correcciones posteriores a la migración (si corresponde).
- Planear e implementar la administración de cambios y las comunicaciones del usuario final (si es el caso).   
- Administrar y configurar los cambios en el sistema de origen y los dispositivos necesarios para la correcta finalización de las actividades de evaluación y migración.
- Proporcionar una programación en un método definido y una lista de datos de usuario específicos para migrar en cada evento de migración con al menos 3 días de antelación.
- Quitar los datos de usuarios de la programación hasta 24 horas antes del lote de migración. Esto debe corresponderse con el lote de migración final.
> [!NOTE]
> Microsoft no garantiza la velocidad de la migración de archivos.
    
## <a name="migration-to-onedrive-for-business"></a>Migración a OneDrive para la Empresa

 ### <a name="enable-to-migrate"></a>Habilitar la migración
  
Si usa Microsoft para migrar datos, le proporcionaremos instrucciones para habilitar OneDrive para la Empresa y el entorno de origen para la migración. Según el origen, podemos llevar a cabo varios pasos de habilitación. Le ayudaremos con algunas actividades usando una combinación de herramientas, documentación y orientación, y realizando tareas de configuración cuando corresponda y sea viable.
  
Podría tener que proporcionar acceso adecuado y permisos a Microsoft para realizar ciertas actividades. Si no le proporciona acceso o permisos, usted mismo deberá realizar ciertas tareas definidas con instrucciones de Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Pasos y directiva de migración
  
> [!NOTE]
> Una franja temporal de migración también se denomina lote de migración.

#### <a name="commercial-and-uk-government"></a>Comercial y organismos gubernamentales del Reino Unido

Las migraciones se realizan con una regularidad programada y normalizada las 24 horas al día y durante siete (7) días laborables a la semana (24x7) en franjas temporales de migración predefinidas. Hay tres lotes de migración por día de migración.

#### <a name="us-governmentdod"></a>Gobierno de Estados Unidos o DOD

Las migraciones se realizan con una regularidad programada y normalizada las 24 horas al día y durante cinco (5) días laborables a la semana (24x5) en franjas temporales de migración predefinidas. Hay tres lotes de migración por día de migración. Hay cinco días de migración en una semana del lunes a las 2:00 de la hora universal coordinada (UTC) al viernes a la medianoche UTC, lo que significa que la última migración programada es el viernes a las 20:00 UTC.
    
- Todas las migraciones requieren el acceso y los permisos adecuados en el entorno de origen.   
- Todas las migraciones están sujetas a las cuotas de OneDrive para la Empresa indicadas en [SharePoint Online y OneDrive para la Empresa: restricciones y límites del software](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 ### <a name="end-state"></a>Estado final
  
El estado final esperado después de un lote de migración incluye lo siguiente:  
- Los datos de orígenes adecuadamente programados y pertinentes del entorno de origen se migran a OneDrive para la Empresa.  
- Un informe posterior a la migración para el lote de migración proporcionado por Microsoft.
    
El estado final esperado una vez finalizadas todas las migraciones incluye lo siguiente:
- Los datos de orígenes pertinentes se migran a Office 365 tal como se define en la tabla siguiente.  
- El tipo de datos que se van a migrar depende del entorno de origen, tal como se describe en la tabla siguiente.
    
|||||
|:-----|:-----|:-----|:-----|
|**Entorno de origen**|**Tipo de migración**|**Qué se va a migrar**|**¿Qué no se migrará?**|
|**Un solo entorno de G Suite (solo Google Drive)**  <br/> |Una o varias fases  <br/> | Google Docs, hojas de cálculo y diapositivas (archivos que se convierten en el formato Office equivalente)  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpetas de nivel de usuario  <br/>  Permisos de carpetas de nivel de grupo  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/>  Contenido de uso compartido propiedad de una cuenta de Google Drive que ha migrado (si se ha compartido explícitamente con usuarios o grupos)  <br/> | Comentarios, versiones anteriores e historial de propiedad  <br/>  Descripciones de archivos y carpetas, colores de las carpetas  <br/>  Conversión de URL insertadas en el contenido  <br/>  Permisos de archivos de nivel de usuario  <br/>  Permisos de archivos de nivel de grupo  <br/> Elementos desechados  <br/>  Documentos inaccesibles o dañados  <br/>  Usuarios bloqueados o inactivos  <br/>  Contenido externo compartido con su organización  <br/>  Google Fotos, Formularios de Google, Google Maps y otras aplicaciones conectadas<br/>  Dibujos de Google  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de archivos y carpetas de nivel de usuario\*  <br/>  Permisos de archivos y carpetas de nivel de grupo\*  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/> <br/>\**Se requiere la configuración de sincronización de directorios. Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows. No se migran permisos administrados directamente en dispositivos de recursos compartidos de archivos. Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.* <br/> | Versiones anteriores e historial de propiedad  <br/>  Conversión de URL insertadas en el contenido  <br/>  Versiones anteriores  <br/>  Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)  <br/>  Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:  <br/>  Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)  <br/>  Configuración de auditoría de NTFS  <br/>  Metadatos de archivo adicionales proporcionados por FCI  <br/>  Documentos inaccesibles o dañados  <br/>  Recursos compartidos ocultos  <br/>  Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpetas de nivel de usuario  <br/>  Permisos de carpetas de nivel de grupo  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/>  Contenido de uso compartido propiedad de la cuenta de Box que se migra (si se ha compartido explícitamente con usuarios o grupos)\*  <br/><br/> \**Use informes de Box para identificar cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> | Comentarios, versiones anteriores e historial de propiedad  <br/>  Descripciones de archivos y carpetas  <br/>  Permisos de archivos de nivel de usuario  <br/>  Permisos de archivos de nivel de grupo  <br/>  Metadatos avanzados y etiquetas de Box  <br/>  Atributos de bloqueo de archivos  <br/>  Conversión de URL insertadas en el contenido  <br/>  Elementos desechados  <br/>  Documentos inaccesibles o dañados  <br/>  Usuarios bloqueados o inactivos  <br/>  Notas de Box (no funcional debido a que migran sin conversión)  <br/>  Flujos de trabajo, Favoritos, Marcadores y aplicaciones de Box  <br/>  Contenido que no pertenece a la cuenta migrada de Box (carpetas compartidas)  <br/>  Permisos y metadatos básicos de usuarios externos\*  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
   
Durante las migraciones, los especialistas de FastTrack realizan las siguientes operaciones:  
- Ofrecer un tutorial sobre la migración que abarca el proceso y el enfoque referentes al escenario de la migración seleccionada.   
- Proporcionar los requisitos previos de las herramientas de evaluación y migración que correspondan al escenario.  
- Proporcionar los requisitos previos para el acceso del equipo de migración al entorno de origen y destino a efectos de evaluación y migración.   
- Ofrecer herramientas de evaluación para realizar evaluaciones del entorno de origen y destino o proporcionar instrucciones sobre cómo usar las funciones de plataforma de origen nativas para crear informes de evaluación.    
- Ayudar a implementar y ejecutar las herramientas de evaluación y migración (si es el caso).   
- Configurar la infraestructura de migración en preparación para la migración de contenido (si es aplicable).    
- Realizar una migración de prueba limitada para validar la infraestructura de migración y los requisitos previos necesarios.    
- Aprovisionar sitios de destino de OneDrive para la Empresa listos para su uso como parte de la migración.    
- Realizar una migración piloto antes de la migración de velocidad.
- Proporcionar instrucciones sobre la programación de la migración para el escenario seleccionado.   
- Llevar a cabo ondas de migración de velocidad de contenido de acuerdo con la programación de migración que proporcione el cliente y que los recursos FastTrack hayan validado.   
- Proporcionar resultados de migración después de cada ventana de migración.   
- Participar en la clasificación de los problemas de migración de velocidad y proporcionar instrucciones sobre las posibles opciones de corrección. 
- Proporcionar un informe de migración final para cada ventana de migración de velocidad.   
- Proporcionar asistencia después de la migración durante las pruebas de aceptación de usuario a lo largo de cinco días tras la finalización de la migración.
   
Durante las migraciones, el usuario realiza las siguientes operaciones:
- Proporcionar recursos de proyecto recomendados para actividades de evaluación y migración. Entre ellos se incluyen:
  - Administración de proyectos.
  - UAT.
  - Administradores responsables de las plataformas de contenido de origen y de destino.
- Proporcionar los requisitos previos de la infraestructura para las actividades de evaluación y migración (si es necesario).   
- Proporcionar a los especialistas de FastTrack acceso y permisos al entorno de origen y destino, para que puedan realizar actividades de migración (si es necesario).  
    > [!NOTE]
    > Las migraciones solo utilizan cuentas que cumplan con los requisitos de seguridad definidos durante la incorporación. Si no utiliza dichas cuentas, es posible que experimente demoras en la migración. 
- Instalar las herramientas de evaluación que ofrece FastTrack y completar las actividades de recopilación de datos de evaluación (si procede).
- Instalar localmente el software de migración que proporciona FastTrack (si es el caso).  
- Completar las actividades de corrección indicadas en el informe de corrección de FastTrack (si corresponde).   
- Proporcionar una programación de migración mediante las plantillas y las instrucciones de FastTrack. 
- Proporcionar una programación en un método definido y una lista de datos de usuario específicos para migrar en cada evento de migración con al menos 3 días de antelación.
- Quitar los datos de usuarios de la programación hasta 24 horas antes del lote de migración. Esto debe corresponderse con el lote de migración final.
- Realizar un control de calidad de migración y pruebas de aceptación de usuario.   
- Realizar correcciones posteriores a la migración (si corresponde).  
- Planear e implementar la administración de cambios y las comunicaciones del usuario final (si es el caso).  
- Administrar y configurar los cambios en el sistema de origen y los dispositivos necesarios para la correcta finalización de las actividades de evaluación y migración.
    
> [!NOTE]
> Microsoft no garantiza la velocidad de la migración de archivos.  

