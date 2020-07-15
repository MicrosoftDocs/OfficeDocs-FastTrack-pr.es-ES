---
title: Migración de datos
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack Specialists provide guidance on steps for data migration to Office 365. This is available for all eligible customers with Office 365 services for Exchange Online, OneDrive for Business, and SharePoint Online.
ms.openlocfilehash: 7780af3d5edcdbdf21acba1d421bf379967305fa
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011314"
---
# <a name="data-migration"></a>Migración de datos

Es posible que tenga datos en sus entornos de origen que quiera migrar a Office 365.

**Para los espacios empresariales de Office 365 con un número de 150 a 499 licencias:** proporcionamos orientación mediante el uso de una combinación de herramientas y documentación para que su migración se lleve a cabo sin problemas y de manera eficiente. 

**Para los espacios empresariales de Office 365 con 500 o más licencias\*:** los servicios de migración de datos están disponibles para Exchange Online, SharePoint Online y OneDrive para la Empresa. Su ventaja de FastTrack incluye proporcionarle orientación sobre la integración del entorno de origen y la migración de datos.
  
\*If you purchased or renewed a commercial plan prior to 9/1/2017, 150 seats is the minimum seat requirement throughout your current subscription period in order to receive the migration benefit. For education plans, only paid faculty and staff licenses are eligible for migration services. 
  
> [!NOTE]
> Data migrated through the FastTrack services may be transferred to, stored, and processed anywhere that Microsoft maintains facilities (except as otherwise provided for your particular FastTrack engagement). The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements. 
  
> [!NOTE]
> Los problemas imprevistos (incluyendo, entre otros, elementos ilegibles o dañados en el entorno de origen) pueden impedir que algunos elementos se migren. 
  
> [!NOTE]
> La asistencia para la migración está disponible en chino tradicional y simplificado (el personal solo habla mandarín), en inglés, en francés, en alemán, en italiano, en japonés, en portugués (de Brasil) y en español. 
  
> [!NOTE]
> Si la integración es necesaria, el entorno de origen debe estar al nivel mínimo para dicha aplicación. 
  
> [!NOTE]
> A partir de marzo de 2020, Microsoft hará disponibles licencias de prueba de seis meses de [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license) y [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license) para dar soporte al trabajo y el aprendizaje remotos durante el brote de COVID-19. Como excepción, FastTrack está haciendo que los servicios de migración de datos estén disponibles para los espacios empresariales con 500 o más licencias de estas versiones de prueba y para [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1) para estudiantes desde marzo de 2020 a agosto de 2020. Microsoft se reserva el derecho a cancelar, cambiar o suspender esta oferta en cualquier momento sin previo aviso.

En la siguiente tabla se describe lo que se espera para la migración en el entorno de origen existente.
  

|**Actividad**|**Expectativa del entorno de origen**|
|:-----|:-----|
|**Migración de Exchange Online**  <br/> | Microsoft migrates any combination of the source environments listed below, each one at a time. We can migrate the onboarded messaging system using the FastTrack Center or if it's passed the FastTrack Center checks. This includes:  <br/>  Uno o varios bosques de Active Directory con una o varias organizaciones de Exchange si se realiza una implementación híbrida de Exchange 2010 en adelante en cada organización y los sistemas de correo de Exchange van del 2003 en adelante.  <br/>  Un solo entorno de correo electrónico compatible con IMAP.  <br/>  Entornos de G Suite (solo Gmail, Contactos y Calendario) <br/> <br/> **Nota** *La incorporación de Exchange Online debe realizarse antes de la migración.* <br/> <br/> **Nota** *FastTrack solo migra a buzones de Office 365 activos.* <br/> <br/> **Nota** *Para conocer las dependencias de Exchange local, vea [Requisitos previos de implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).* <br/><br/> **Nota** *Estas migraciones se producen consecutivamente al migrar varios entornos de mensajería de origen (por ejemplo, varias organizaciones de Exchange o varios dominios de Domino).*| 
|**Migración de SharePoint Online**  <br/> | Recursos compartidos de archivos (recursos compartidos de archivos del Bloque de mensajes del servidor, o SMB, en dispositivos compatibles a partir SMB 2.0). <br/> Un solo entorno de G Suite (solo Google Drive)<br/>  Box (Starter, Business, Enterprise).  <br/> Dropbox para Equipos (estándar y avanzado).<br/> |
|**Migración de OneDrive para la Empresa**  <br/> | Recursos compartidos de archivos (recursos compartidos de archivos de SMB en dispositivos compatibles a partir de SMB 2.0).  <br/>  Un solo entorno de G Suite (solo Google Drive)  <br/>  Box (Starter, Business, Enterprise). <br/> Dropbox para Equipos (estándar y avanzado).<br/><br/> **Nota** *FastTrack solo migra a unidades de disco de Office 365 activas.*|
   
## <a name="migration-to-exchange-online"></a>Migración a Exchange Online
''
### <a name="enable-to-migrate"></a>Habilitar la migración
  
Si usa Microsoft para migrar su correo electrónico, le proporcionaremos ayuda para habilitar Exchange Online y el entorno de origen para la migración. Según el origen, podemos llevar a cabo varios pasos de habilitación. Proporcionamos ayuda mediante el uso de una combinación de herramientas y documentación y realizando tareas de configuración donde sea pertinente y viable. Según los parámetros aplicables, migramos los buzones, los trabajos de monitor y proporcionamos informes de estado.
'' Puede que Microsoft requiera el acceso y los permisos adecuados en su sistema de correo con el fin de realizar actividades de migración.
  
### <a name="migration-policy-and-steps"></a>Pasos y directiva de migración
  
> [!NOTE]
> Una franja temporal de migración también se denomina lote de migración.

#### <a name="commercial-and-uk-government"></a>Comercial y organismos gubernamentales del Reino Unido

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>Gobierno de Estados Unidos o DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
 ### <a name="end-state"></a>Estado final
  
El estado final esperado después de un lote de migración incluye lo siguiente:
- Los datos de los buzones de origen elegibles y programados adecuadamente en el entorno de origen se migran a Office 365. 
- Un informe posterior a la migración para el lote de migración proporcionado por Microsoft.
    
El estado final esperado una vez finalizadas todas las migraciones incluye lo siguiente:
- Los datos de los buzones de origen pertinentes se migran a Office 365 tal como se define en la tabla siguiente.
- El tipo de datos que se van a migrar depende del entorno de origen, tal como se describe en la tabla siguiente.
    
> [!NOTE]
> All source environments need to be on the latest service packs (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment at the end of the Enable phase. Data migration services are subject to external factors beyond Microsoft's control, like changes to third-party application programming interfaces (APIs), which could result in changes to, delays in, or suspension of these services. For the duration of the FastTrack services, data you make available to Microsoft is accessible from and stored anywhere that Microsoft and its suppliers maintain facilities. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Entorno de origen**|**Tipo de migración**|**¿Qué se migrará desde el buzón de origen?**|**¿Qué no se migrará?**|
|**Exchange 2003 o superior**|Total| Mensajes de correo electrónico <br/> Reglas de buzón <br/> Delegados <br/> Contactos de buzón de correo <br/> Calendario <br/> Tareas <br/> Correos electrónicos con derechos administrados <br/> Correos electrónicos cifrados| Carpetas públicas <br/> Contactos personales <br/> Usuarios habilitados para correo <br/> Usuarios bloqueados o inactivos <br/> Firmas <br/> Contenedor del buzón <br/>  Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Datos de archivo <br/> Elementos dañados <br/>  Buzones de correo inactivos |
|**Exchange 2003 y Exchange 2007**|Preconfigurada| Mensajes de correo electrónico <br/> Reglas de buzón <br/> Delegados <br/> Contactos de buzón de correo <br/> Calendario <br/> Tareas <br/> Correos electrónicos con derechos administrados <br/> Correos electrónicos cifrados| Carpetas públicas <br/> Contactos personales <br/> Usuarios habilitados para correo <br/> Usuarios bloqueados o inactivos <br/> Firmas <br/> Contenedor del buzón <br/> Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Datos de archivo <br/> Elementos dañados <br/> Buzones de correo inactivos |
|**Exchange 2010, Exchange 2013, Exchange 2016 y Exchange 2019** <br/><br/> **Nota** *Para conocer las dependencias de Exchange local, vea [Requisitos previos de implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).*           |Migración con implementación híbrida| Mensajes de correo electrónico <br/> Reglas de buzón <br/> Delegados <br/> Contactos de buzón de correo <br/> Calendario <br/> Tareas <br/> Firmas <br/> Archivo personal migrado con el buzón del usuario <br/> Elementos recuperables <br/> Correos electrónicos con derechos administrados <br/> Correos electrónicos cifrados| Carpetas públicas <br/> Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Archivo de registro en diario o cualquier solución de archivo de terceros <br/> Usuarios bloqueados o inactivos <br/> Datos de archivo procedentes de archivos PST (Personal Storage Table) <br/> Elementos dañados <br/> Buzones de correo inactivos |
|**Entorno de G Suite (solo Gmail, Contactos y Calendario)** <br/> <br/> **Nota** *Su entorno de G Suite debe tener la API de Google y el SDK del administrador de Google habilitados para ampliar la funcionalidad.* <br/>          |Total o preconfigurada| Mensajes de correo electrónico <br/> Contactos de buzón de correo\*  <br/> Calendario <br/> Etiquetas <br/> \*Se migra un máximo de tres direcciones de correo electrónico por contacto| Rules <br/> Delegados <br/> Firmas <br/> Tareas <br/> Cualquier correo electrónico o dato adjunto que supere el límite de tamaño de mensaje <br/> Usuarios bloqueados o inactivos <br/> Datos de archivo procedentes de archivos PST o de soluciones de archivo de terceros (por ejemplo, Google Vault) <br/> Mensajes de correo electrónico cifrados o con derechos administrados <br/> Elementos dañados <br/> Google Hangouts\*\* <br/> Grupos de Google <br/> Buzones de recursos <br/> Buzones de correo inactivos <br/> Configuración de ausencia por vacaciones y respuesta automática <br/> Calendarios compartidos, datos adjuntos en la nube, vínculos a Google Hangout y colores del evento <br/>\*\*Se migran las conversaciones de Hangouts guardadas como etiqueta |
|**Origen de IMAP4 (como Domino, GroupWise y Zimbra)** |Migración con herramientas nativas de IMAP4| Mensajes de correo electrónico | Reglas <br/> Delegados <br/> Listas de distribución <br/> Contactos externos <br/> Usuarios habilitados para correo <br/> Usuarios bloqueados o inactivos <br/> Contactos de buzón de correo <br/> Calendario <br/> Firmas <br/> Tareas <br/> Cualquier correo electrónico que supere el límite de tamaño de mensaje <br/> Datos de archivo <br/> Correo electrónico cifrado <br/> Elementos dañados <br/> Buzones de correo inactivos |
   
> [!NOTE]
> If distribution lists (MailEnabledGroup objects) and external contacts (MailEnabledContact objects) are in the on-premises Active Directory, they can be synchronized using Azure AD Connect. However, they aren't a part of mailbox data migration. For more information, see the **Identity integration** example in [Core](O365-onboarding-and-migration.md#core). 
  
Durante las migraciones, los especialistas de FastTrack realizan las siguientes operaciones:
- Proporcionar una plantilla estándar para la programación de migraciones de buzones.
- Proporcionar información sobre los permisos necesarios para los especialistas de FastTrack. 
- Recopilar la programación de migración de buzones de correo predeterminados en el formato predeterminado.
- Intentar realizar la migración de un único buzón hasta dos veces en un lote de migración antes de generar un informe sobre dicho buzón como una migración errónea.
- Para los entornos de origen basados en Exchange e IMAP4, se puede migrar contenido hasta el 85 % del límite de almacenamiento del buzón de usuario (por ejemplo, si el límite de almacenamiento del buzón es de 50 GB, Microsoft migra hasta el 85 % de 50 GB). 
- Habilitar la coexistencia de enrutamiento de correo SMTP entre el entorno de mensajería de origen y Office 365 Exchange Online a menos que se esté usando la migración total.
- Proporcionar informes posteriores a la migración.
- Provide post-migration assistance for critical issues. The following issues are considered critical:
  - Pérdida de datos durante la migración.
  - El entorno de origen no está disponible durante la migración.
  - Las actividades de migración provocan problemas en el entorno de origen.
    
Durante las migraciones, el usuario realiza las siguientes operaciones:
- Completar la incorporación de Exchange Online o realizar las comprobaciones requeridas con el Centro FastTrack.
- Controlar las comunicaciones con los usuarios finales.  
- Instalar el nivel adecuado del software de cliente según las instrucciones de Office 365. Para obtener más información, consulte [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg). 
- Validar la coexistencia de enrutamiento de correo SMTP entre el entorno de mensajería de origen y Office 365 Exchange Online si procede.
- Proporcionar una programación en un método definido y una lista de buzones de correo específicos para migrar por cada evento de migración.
- Quitar los buzones de correo de la programación hasta 24 horas antes del lote de migración. 
- Programar un promedio de destino de buzones de correo en un período de 24 horas, tal como se muestra en la tabla siguiente.
    
|||
|:-----|:-----|
|**Número de buzones elegibles de migración** <br/> |**Promedio mínimo de buzones de correo en un período de 24 horas** <br/> |
|150-1000  <br/> |25 % del total  <br/> |
|1.001-5.000  <br/> |20 % del total  <br/> |
|5.001-10.000  <br/> |15 % del total  <br/> |
|\>10 000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > These numbers are based on best practice. However, the number of mailboxes that migrate per day will vary based on environment, readiness, and business constraints. Microsoft can't guarantee the speed of mailbox migration. 
  
- Programar un mínimo de 35 buzones en un lote de migración. 
- Corregir los errores previos a la migración (si procede).  
- Proporcionar a los especialistas de FastTrack acceso y permisos al entorno de origen, para que puedan realizar actividades de migración. 
- Adquirir o proporcionar cuentas administrativas con licencia en Office 365 para realizar actividades de migración (según corresponda). 
- Prestar asistencia con los problemas de migración del lado cliente y ejecutar operaciones posteriores a las migraciones cuando sea necesario. 
- Migrate client-side data if desired. This includes, but is not limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.   
- Reducir el tamaño del buzón por debajo del 85 % del límite del buzón de Office 365 de destino (si procede).   
- Controlar las acciones del informe posterior a la migración, incluidos los buzones que no se movieron.  
- Corregir errores posteriores a la migración y volver a programar los buzones de correo (si procede).   
- Engage in post-migration assistance for critical issues. The following issues are considered critical:
  - Pérdida de datos durante la migración.
  - El entorno de origen no está disponible durante la migración.
  - Las actividades de migración provocan problemas en el entorno de origen.
    
You need to follow the standard migration process and engage with Microsoft appropriately. This includes providing access and permissions to source and Office 365 environments, providing migration schedules, correcting any causes for migration errors, and so on. You also need to engage with end users for communications, mailbox migration schedule, and handling end user migration-related issues.
  
> [!NOTE]
> Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
  
## <a name="migration-to-sharepoint-online"></a>Migración a SharePoint Online

### <a name="enable-to-migrate"></a>Habilitar la migración
  
If you use Microsoft to migrate your data, we provide guidance to enable both SharePoint Online and the source environment for migration. Depending on the source, we may perform various Enable steps. We provide guidance for you by using a combination of tools and documentation and by performing configuration tasks where applicable and feasible.
  
Necesita proporcionar a Microsoft el acceso y los permisos adecuados para que lleve a cabo algunas actividades.
  
### <a name="migration-policy-and-steps"></a>Pasos y directiva de migración
  
> [!NOTE]
> Una franja temporal de migración también se denomina lote de migración.

#### <a name="commercial-and-uk-government"></a>Comercial y organismos gubernamentales del Reino Unido

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>Gobierno de Estados Unidos o DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.

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
|**Un solo entorno de G Suite (solo Google Drive)**  <br/> |Una o varias fases  <br/> | <br/>  Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office), incluidos los de más de 10 MB <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpeta de nivel de usuario  <br/>  Permisos de carpeta de nivel de grupo <br/>  Archivos de menos de 15 GB  <br/> Metadatos básicos de documentos y carpetas: <br/> Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/> Unidades compartidas (carpetas y archivos) <br/>  Contenido de uso compartido propiedad de la cuenta de Google Drive que se migra (si se ha compartido explícitamente con usuarios o grupos)\*  <br/><br/> \**Use el administrador de Google Drive para identificar las cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> | Comentarios, versiones anteriores e historial de propiedad <br/>  Descripciones de archivos y carpetas, colores de las carpetas  <br/>  Permisos de archivo de nivel de usuario  <br/>  Permisos de archivo de nivel de grupo  <br/>  Metadatos avanzados  <br/>  Atributos de bloqueo de archivos  <br/>  Conversión de URL insertadas en el contenido  <br/>  Elementos desechados  <br/>  Documentos inaccesibles o dañados  <br/>  Usuarios bloqueados o inactivos  <br/>  Google Fotos, Formularios de Google, Google Maps y otras aplicaciones conectadas  <br/>  Dibujos de Google  <br/>  Contenido de uso compartido que es externo a su organización  <br/> Contenido que no es propiedad de la cuenta de Google Drive que se migra <br/>Permisos y metadatos básicos de usuarios externos  <br/> Permisos de miembro de Unidad compartida\* <br/> Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Use el administrador de Google Drive para identificar las cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/>|
|**Box (Starter, Business, Enterprise)**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpetas de nivel de usuario  <br/>  Permisos de carpetas de nivel de grupo  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/>  Contenido de uso compartido propiedad de la cuenta de Box que se migra (si se ha compartido explícitamente con usuarios o grupos)\*  <br/><br/> \**Use informes de Box para identificar cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> | Comentarios, versiones anteriores e historial de propiedad <br/>  Permisos de archivos de nivel de usuario  <br/>  Permisos de archivos de nivel de grupo  <br/>  Descripciones de archivos y carpetas  <br/>  Metadatos avanzados y etiquetas de Box  <br/>  Atributos de bloqueo de archivos  <br/>  Conversión de URL insertadas en el contenido  <br/>  Elementos desechados  <br/>  Documentos inaccesibles o dañados  <br/>  Usuarios bloqueados o inactivos  <br/>  Notas de Box (no funcional debido a que migran sin conversión)  <br/>  Flujos de trabajo, Favoritos, Marcadores y aplicaciones de Box  <br/>  Contenido que no pertenece a la cuenta migrada de Box (carpetas compartidas)  <br/>  Permisos y metadatos básicos de usuarios externos\*  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/>\**Use el administrador de Google Drive para identificar la membresía de unidad compartida. Indique a los usuarios finales cómo configurar la membresía en el destino antes de la migración.* |
|**Dropbox para Equipos (estándar y avanzado)**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpeta de nivel de usuario  <br/>  Permisos de carpeta de nivel de grupo  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/> Contenido y carpetas de equipo de uso compartido <br/>  Contenido de uso compartido propiedad de la cuenta de Dropbox que se migra (si se ha compartido explícitamente con usuarios o grupos)\*  <br/> <br/> \**Use informes de Dropbox para identificar cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> | Comentarios, versiones anteriores e historial de propiedad <br/>  Descripciones de archivos y carpetas <br/>  Permisos de archivo de nivel de usuario  <br/>  Permisos de archivo de nivel de grupo    <br/> Metadatos avanzados  <br/>  Atributos de bloqueo de archivos  <br/>  Conversión de URL insertadas en el contenido  <br/>  Elementos desechados  <br/>  Documentos inaccesibles o dañados  <br/>  Carpetas de Dropbox desmontadas <br/>  Usuarios eliminados o desconectados <br/>  Dropbox Paper, Showcases y Spaces  <br/> Aplicaciones y favoritos de Dropbox (Pins/Estrellas) <br/> Contenido que no es propiedad de la cuenta de Dropbox migrada  <br/>  Permisos y metadatos básicos de usuarios externos\*  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Use informes de Dropbox para identificar cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> |
   
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
- Provide project resources recommended for assessment and migration activities. These include: 
  - Administración de proyectos. 
  - Prueba de aceptación del usuario (UAT).  
  - Administradores responsables de las plataformas de contenido de origen y de destino.  
- Proporcionar los requisitos previos de la infraestructura para las actividades de evaluación y migración (si es necesario).  
- Proporcionar a los especialistas de FastTrack acceso y permisos al entorno de origen y destino, para que puedan realizar actividades de migración (si es necesario).
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
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
- Quitar los datos de usuario de la programación hasta 24 horas antes del lote de migración. Esto debe corresponderse con el lote de migración final.
> [!NOTE]
> Microsoft no garantiza la velocidad de la migración de archivos.
    
## <a name="migration-to-onedrive-for-business"></a>Migración a OneDrive para la Empresa

 ### <a name="enable-to-migrate"></a>Habilitar la migración
  
If you use Microsoft to migrate your data, we provide guidance to enable both OneDrive for Business and the source environment for migration. Depending on the source, we may perform various Enable steps. We help you with some activities by using a combination of tools, documentation, and guidance, and by performing configuration tasks where applicable and feasible.
  
You may need to provide appropriate access and permissions to Microsoft to perform some activities. If you don't provide access and/or permissions, you need to perform certain defined tasks yourself with guidance from Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Pasos y directiva de migración
  
> [!NOTE]
> Una franja temporal de migración también se denomina lote de migración.

#### <a name="commercial-and-uk-government"></a>Comercial y organismos gubernamentales del Reino Unido

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>Gobierno de Estados Unidos o DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
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
|**Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de archivos y carpetas de nivel de usuario\*  <br/>  Permisos de archivos y carpetas de nivel de grupo\*  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/> <br/>\**Se requiere la configuración de sincronización de directorios. Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows. No se migran permisos administrados directamente en dispositivos de recursos compartidos de archivos. Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.* <br/> | Versiones anteriores e historial de propiedad  <br/>  Conversión de URL insertadas en el contenido  <br/>  Versiones anteriores  <br/>  Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)  <br/>  Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:  <br/>  Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)  <br/>  Configuración de auditoría de NTFS  <br/>  Metadatos de archivo adicionales proporcionados por FCI  <br/>  Documentos inaccesibles o dañados  <br/>  Recursos compartidos ocultos  <br/>  Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Un solo entorno de G Suite (solo Google Drive)**  <br/> |Una o varias fases  <br/> | Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office, incluidos los de más de 10 MB)  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpeta de nivel de usuario  <br/>  Permisos de carpeta de nivel de grupo  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/> Unidades compartidas (carpetas y archivos) <br/> Contenido de uso compartido propiedad de la cuenta de Google Drive que se migra (si se ha compartido explícitamente con usuarios o grupos)\* <br/> <br/>\**Use el administrador de Google Drive para identificar las cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> | Comentarios, versiones anteriores e historial de propiedad  <br/>  Descripciones de archivos y carpetas, colores de las carpetas  <br/>   Permisos de archivo de nivel de usuario  <br/>  Permisos de archivo de nivel de grupo  <br/> Metadatos avanzados <br/>  Atributos de bloqueo de archivos <br/> Conversión de URL insertadas en el contenido  <br/> Elementos desechados <br/> Documentos inaccesibles o dañados <br/> Usuarios bloqueados o inactivos <br/> Google Fotos <br/> Formularios de Google, Maps y otras aplicaciones conectadas <br/> Dibujos de Google <br/> Contenido de uso compartido que es externo a su organización <br/> Contenido que no es propiedad de la cuenta de Google Drive que se migra <br/> Permisos y metadatos básicos de usuarios externos<br/> Permisos de miembro de unidad compartida\*<br/> Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/><br/> \**Use el administrador de Google Drive para identificar la membresía de unidad compartida. Indique a los usuarios finales cómo configurar la membresía en el destino antes de la migración.* <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpetas de nivel de usuario  <br/>  Permisos de carpetas de nivel de grupo  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/>  Contenido de uso compartido propiedad de la cuenta de Box que se migra (si se ha compartido explícitamente con usuarios o grupos)\*  <br/><br/> \**Use informes de Box para identificar cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> | Comentarios, versiones anteriores e historial de propiedad  <br/>  Descripciones de archivos y carpetas  <br/>  Permisos de archivos de nivel de usuario  <br/>  Permisos de archivos de nivel de grupo  <br/>  Metadatos avanzados y etiquetas de Box  <br/>  Atributos de bloqueo de archivos  <br/>  Conversión de URL insertadas en el contenido  <br/>  Elementos desechados  <br/>  Documentos inaccesibles o dañados  <br/>  Usuarios bloqueados o inactivos  <br/>  Notas de Box (no funcional debido a que migran sin conversión)  <br/>  Flujos de trabajo, Favoritos, Marcadores y aplicaciones de Box  <br/>  Contenido que no pertenece a la cuenta migrada de Box (carpetas compartidas)  <br/>  Permisos y metadatos básicos de usuarios externos\*  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Dropbox para Equipos (estándar y avanzado)**  <br/> |Una o varias fases  <br/> | Documentos  <br/>  Estructura de archivos y carpetas  <br/>  Permisos de carpeta de nivel de usuario  <br/>  Permisos de carpeta de nivel de grupo  <br/>  Archivos de menos de 15 GB  <br/>  Metadatos básicos de documentos y carpetas:  <br/>  Fecha de creación  <br/>  Fecha de modificación  <br/>  Creada por  <br/>  Última modificación  <br/> Contenido y carpetas de equipo de uso compartido <br/> Contenido de uso compartido propiedad de la cuenta de Dropbox que se migra (si se ha compartido explícitamente con usuarios o grupos)\*  <br/> <br/> \**Use informes de Dropbox para identificar cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> | Comentarios, versiones anteriores e historial de propiedad <br/>  Descripciones de archivos y carpetas <br/>  Permisos de archivo de nivel de usuario  <br/>  Permisos de archivo de nivel de grupo    <br/> Metadatos avanzados  <br/>  Atributos de bloqueo de archivos  <br/>  Conversión de URL insertadas en el contenido  <br/>  Elementos desechados  <br/>  Documentos inaccesibles o dañados  <br/>  Carpetas de Dropbox desmontadas <br/>  Usuarios eliminados o desconectados <br/>  Dropbox Paper, Showcases y Spaces  <br/> Aplicaciones y favoritos de Dropbox (Pins/Estrellas) <br/> Contenido que no es propiedad de la cuenta de Dropbox migrada  <br/>  Permisos y metadatos básicos de usuarios externos\*  <br/>  Archivos o carpetas que superen las [restricciones y limitaciones actuales de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Use informes de Dropbox para identificar cuentas externas. Indique a los usuarios finales cómo volver a compartir su contenido después de la migración.* <br/> |
   
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
- Provide project resources recommended for assessment and migration activities. These include:
  - Administración de proyectos.
  - UAT.
  - Administradores responsables de las plataformas de contenido de origen y de destino.
- Proporcionar los requisitos previos de la infraestructura para las actividades de evaluación y migración (si es necesario).   
- Proporcionar a los especialistas de FastTrack acceso y permisos al entorno de origen y destino, para que puedan realizar actividades de migración (si es necesario).  
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- Instalar las herramientas de evaluación que ofrece FastTrack y completar las actividades de recopilación de datos de evaluación (si procede).
- Instalar localmente el software de migración que proporciona FastTrack (si es el caso).  
- Completar las actividades de corrección indicadas en el informe de corrección de FastTrack (si corresponde).   
- Proporcionar una programación de migración mediante las plantillas y las instrucciones de FastTrack. 
- Proporcionar una programación en un método definido y una lista de datos de usuario específicos para migrar en cada evento de migración.
- Drop user data from the schedule until 24 hours in advance of the migration batch. This should correspond to the final migration batch.
- Realizar un control de calidad de migración y pruebas de aceptación de usuario.   
- Realizar correcciones posteriores a la migración (si corresponde).  
- Planear e implementar la administración de cambios y las comunicaciones del usuario final (si es el caso).  
- Administrar y configurar los cambios en el sistema de origen y los dispositivos necesarios para la correcta finalización de las actividades de evaluación y migración.
    
> [!NOTE]
> Microsoft no garantiza la velocidad de la migración de archivos. 


