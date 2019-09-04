---
title: Apéndice B Beneficio adicional del Centro de FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 09/04/2019
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: Los clientes que compren al menos 20 000 licencias para un espacio empresarial de Exchange Online son elegibles para los servicios adicionales del Centro de FastTrack. Para más información, vea Servicios y planes elegibles.
ms.openlocfilehash: 325e37b5f860cca73d2d491db06966801f53bdc7
ms.sourcegitcommit: df949b40ade215de00f74771ffadf0d3be0de797
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/03/2019
ms.locfileid: "36712134"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>Apéndice B: Ventaja adicional del Centro de FastTrack

Los clientes que compren al menos 20 000 licencias para un espacio empresarial de Exchange Online son elegibles para los servicios adicionales del Centro de FastTrack. Para más información, vea [Servicios y planes elegibles](M365-eligible-services-and-plans.md). 
  
## <a name="onboarding-and-migration-phases"></a>Fases de incorporación y migración

## <a name="core"></a>Incorporación principal

Los complementos de los servicios de incorporación principal incluyen instrucciones de configuración para los Servicios de federación de Active Directory con redundancia geográfica y para las directivas de acceso de clientes AD FS del servicio. 
  
## <a name="exchange-online"></a>Exchange Online

Para Exchange Online, proporcionamos instrucciones de configuración para las siguientes opciones:
- Configuración de la mensajería unificada (UM) con Exchange Online.
- Configuración de la coexistencia entre Exchange Online y carpetas públicas locales heredadas.
- Integración de aplicaciones habilitadas para correo. 
- Agrupación y planeación de la migración de buzones.
    
## <a name="skype-for-business-online"></a>Skype Empresarial Online

Para Skype Empresarial Online, proporcionamos instrucciones para la migración de usuarios de Lync y Skype Empresarial local a Skype Empresarial Online.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Para Office 365 ProPlus, proporcionamos instrucciones para las siguientes opciones: 
- Evaluación y planeación centradas en la preparación del entorno para la implementación inicial y la administración de actualizaciones de acuerdo con los procedimientos recomendados de Microsoft. 
- Desarrollar configuraciones de implementación y de actualización mediante la Herramienta de implementación de Office 365. 
- Empaquetado de implementación mediante el Administrador de configuración de System Center.  
- Implementar y configurar la telemetría de Office para ayudarle a evaluar el uso de documentos y soluciones cruciales para la empresa de Office para la compatibilidad de aplicaciones.
    
## <a name="fasttrack-responsibilities"></a>Responsabilidades de FastTrack

Los especialistas de FastTrack tienen las siguientes responsabilidades durante la incorporación. Estas pueden agregarse a las actividades que se definen en [Responsabilidades de FastTrack](O365-fasttrack-responsibilities.md) o reemplazarlas.
  
## <a name="general"></a>General

- Proporcionar soporte técnico remoto para que planee satisfactoriamente el desarrollo, la implementación y las actividades de configuración necesarias, tal y como se detalla en [Fases de incorporación y migración](#onboarding-and-migration-phases).
    
## <a name="assess-phase"></a>Fase de evaluación

- Mantener una llamada sobre la correcta planificación para ayudar para una aceptación por parte de los usuarios correcta. 
- Evaluar su entorno para admitir la configuración de AD FS con redundancia geográfica.  
- Ejecutar una evaluación para identificar sus requisitos para el acceso de cliente de AD FS.
    
## <a name="enable-phase"></a>Fase de habilitación

### <a name="geo-redundant-ad-fs-guidance"></a>Guía AD FS con redundancia geográfica

- Proporcionar un diseño de arquitectura de referencia estándar para una topología de AD FS con redundancia geográfica que se expande en dos (2) centros de datos. La arquitectura estándar se proporciona para:
  - Autenticación federada para los servicios en el ámbito de las ventajas del Centro de FastTrack Center Benefit. 
  - Resistencia del sitio único.  
  - Conmutación por error y alta disponibilidad.  
  - Instrucciones de cambio de tamaño. 
- Proporcionar instrucciones sobre el uso de la base de datos interna de Windows y SQL Server como la instancia de base de datos para la granja de servidores de AD FS.   
- Validar el establecimiento de la autenticación federada para cada bosque del ámbito.  
- Confirmar la funcionalidad de autenticación federada para hasta 10 usuarios.
    
> [!NOTE]
> Las implementaciones de AD FS se encuentran en el ámbito de los clientes elegibles de beneficios adicionales con varias configuraciones de bosque de Active Directory. 
  
### <a name="ad-fs-client-access-policy-guidance"></a>Guía de la directiva de acceso de cliente de AD FS

- Revisar las directivas y la configuración requerida para proteger los recursos de Office 365.  
- Proporcionar instrucciones y ayuda con la configuración de la directiva de acceso de clientes AD FS para los escenarios de acceso de clientes identificados dentro de los límites de los escenarios admitidos. Para obtener más información, vea [Limiting Access to Office 365 Services Based on the Location of the Client (Limitar el acceso a los servicios de Office 365 basados en la ubicación del cliente)](https://go.microsoft.com/fwlink/?LinkID=525689). 
- Validar la funcionalidad de autenticación federada con directivas de acceso de cliente modificadas para los escenarios de acceso identificados con una configuración de hasta 10 usuarios.
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Guía de mensajería unificada de Exchange

- Proporcionar instrucciones en la configuración requerida de Exchange Online para habilitar hasta 10: 
  - Planes de marcado de mensajería unificada.   
  - Directivas de buzón de mensajería unificada. 
  - Operadores automáticos.  
- Proporcionar instrucciones para la configuración de entorno local Lync o Skype Empresarial para habilitar la mensajería unificada y destinarse específicamente a:  
  - Directivas hospedadas en Exchange Online.  
  - Directivas de correo de voz hospedadas en Exchange Online. 
  - Contactos de operadores automáticos de mensajería unificada y correos de voz de Outlook para redirigir a los usuarios a Exchange Online. 
  - Asistir a la creación de los registros de Ubicación del servicio (SRV) según lo requiera la federación.
> [!NOTE]
> La mensajería unificada puede configurarse con puertas de enlace IP y controladores de borde de sesión (SBC) de mensajería unificada compatibles. Para más información, vea [Integración del sistema telefónico con mensajería unificada](https://go.microsoft.com/fwlink/?LinkID=809293). 
  
### <a name="public-folder-coexistence-guidance"></a>Guía de la coexistencia de carpetas públicas

- Proporcionar instrucciones sobre la coexistencia única de árbol de carpetas públicas, que incluyen:  
  - Preparación de carpetas públicas en Exchange 2007, Exchange 2010 y Exchange 2013. 
  - Los cmdlets de Windows PowerShell necesitaban sincronizar la jerarquía de carpetas públicas de Exchange 2007, Exchange 2010 y Exchange 2013 con Exchange Online.  
  - La configuración de Exchange Online para redirigir el acceso de las carpetas públicas a las carpetas públicas locales.  
  - Configuración de acceso a las carpetas públicas de Exchange Online a un entorno local único de Exchange 2007, Exchange 2010 o Exchange 2013.  
  - Asistencia en la validación de acceso al entorno de la carpeta pública para hasta 10 usuarios en Exchange Online.
    
### <a name="mail-enabled-application-integration-guidance"></a>Instrucciones de integración de aplicación habilitada para correo

- Proporcionar plantillas de instrucciones para:  
  - Aplicaciones de correo masivo.  
  - Aplicaciones que enrutan correos electrónicos a través de Exchange.  
  - Aplicaciones que usan buzones de Exchange.  
  - Aplicaciones que necesitan que componentes de terceros o personalizados se instalen en los servidores de Exchange.
    
### <a name="mailbox-migration-planning-and-grouping"></a>Agrupación y planeación de la migración de buzones

- Proporcionar instrucciones para la creación de un plan de migración, que incluyen:  
  - Agrupación de usuarios y recursos en lotes.
  - Coordinar la implementación de los paquetes de software necesarios con los lotes de migración.   
  - Instrucciones para crear un plan de comunicación para los usuarios finales. 
  - Coordinación del tamaño de los lotes de migración, las tasas de errores y la ayuda de soporte técnico esperada. 
- Proporcionar instrucciones para la agrupación de buzones de recursos y usuarios en lotes por tipo, función empresarial y acceso delegado basado en la información relevante proporcionada por el cliente.
    
## <a name="skype-for-business-online"></a>Skype Empresarial Online

- Proporcionar instrucciones sobre la migración de usuarios en lotes en una implementación híbrida de Skype Empresarial (retener las listas de contactos de usuarios).
    
## <a name="office-365-proplus"></a>Office 365 ProPlus

- Proporcionar instrucciones y asistencia para:  
  - Evaluación y planeación de acuerdo con los procedimientos recomendados de Microsoft para la implementación inicial y la administración de actualizaciones.
  - Implementación y configuración de la telemetría de Office. 
  - Habilitación del registro de telemetría para clientes de Office 2013 y posterior mediante la directiva de grupo. 
  - Implementación de agentes de telemetría de Office para clientes anteriores de Office (Office 2003, Office 2007 y Office 2010). 
  - Implementación del procesador de telemetría. 
    > [!NOTE]
    > Esto requiere una ubicación de recurso compartido de archivos para almacenar los datos de telemetría y un servidor con SQL Server 2005 y posterior al cual poder enviar los datos procesados. 
  
## <a name="your-responsibilities"></a>Sus responsabilidades

El usuario tiene las siguientes responsabilidades durante la incorporación. Estas se agregan a las responsabilidades que se definen en la sección [Sus responsabilidades](O365-your-responsibilities.md). 
  
- Asignar y administrar recursos de acuerdo al plan del proyecto.  
- Tomar las medidas oportunas para mitigar los riesgos y resolver los problemas provocados por el cliente, los administradores de proyectos asociados y el Administrador de FastTrack.   
- Revisar los informes de estado y actuar en consecuencia.   
- Asignar un líder o patrocinador operativo con autoridad para tomar decisiones para dirigir el comité directivo.  
- Asignar un patrocinador ejecutivo para trabajar con el patrocinador ejecutivo de Microsoft.  
- Establecer una reunión mensual del comité directivo.
    

  

