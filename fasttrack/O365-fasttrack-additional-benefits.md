---
title: Apéndice A - Beneficio adicional del Centro de FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: Customers who purchase at least 20,000 licenses for an Exchange Online tenant are eligible for FastTrack Center additional services. See Eligible Services and Plans for more details.
ms.openlocfilehash: 619ba9bf27116a94a40e74b38a4f4bbdd4d6c99d
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/01/2020
ms.locfileid: "45010990"
---
# <a name="appendix-a---fasttrack-center-additional-benefit"></a>Apéndice A - Beneficio adicional del Centro de FastTrack

Customers who purchase at least 20,000 licenses for an Exchange Online tenant are eligible for FastTrack Center additional services. See [Eligible Services and Plans](M365-eligible-services-and-plans.md) for more details. 
  
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
  
## <a name="microsoft-365-apps"></a>Aplicaciones de Microsoft 365

Para Aplicaciones de Microsoft 365, proporcionamos instrucciones para las siguientes opciones: 
- Evaluación y planeación centradas en la preparación del entorno para la implementación inicial y la administración de actualizaciones de acuerdo con los procedimientos recomendados de Microsoft. 
- Desarrollo de configuraciones de implementación y de actualización mediante la Herramienta de implementación de Office 365 y la Herramienta de personalización de Office. 
- Empaquetado de implementación con Microsoft Endpoint Configuration Manager  
- Habilitar el uso del Kit de herramientas de preparación para Office para identificar posibles problemas de compatibilidad con las macros de Microsoft Visual Basics for Applications (VBA) y los complementos instalados que se usan junto con Office.
    
## <a name="fasttrack-responsibilities"></a>Responsabilidades de FastTrack

FastTrack Specialists have the following responsibilities during onboarding. These may be in addition to or replace the activities defined in [FastTrack Responsibilities](O365-fasttrack-responsibilities.md).
  
## <a name="general"></a>General

- Proporcionar soporte técnico remoto para que planee satisfactoriamente el desarrollo, la implementación y las actividades de configuración necesarias, tal y como se detalla en [Fases de incorporación y migración](#onboarding-and-migration-phases).
    
## <a name="assess-phase"></a>Fase de evaluación

- Mantener una llamada sobre la correcta planificación para ayudar para una aceptación por parte de los usuarios correcta. 
- Evaluar su entorno para admitir la configuración de AD FS con redundancia geográfica.  
- Ejecutar una evaluación para identificar sus requisitos para el acceso de cliente de AD FS.
    
## <a name="enable-phase"></a>Fase de habilitación

### <a name="geo-redundant-ad-fs-guidance"></a>Guía AD FS con redundancia geográfica

- Provide standard reference architecture design for a geo-redundant AD FS topology spanning two (2) data centers. The standard architecture provides for:
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
- Provide guidance and assistance with configuring the AD FS client access policy for identified client access scenarios within the boundaries of supported scenarios. For more information, see [Limiting Access to Office 365 Services Based on the Location of the Client](https://go.microsoft.com/fwlink/?LinkID=525689). 
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
> UM can be configured with supported UM IP gateways and session border controllers (SBCs). For more information, see [Telephone system integration with UM](https://go.microsoft.com/fwlink/?LinkID=809293). 
  
### <a name="public-folder-coexistence-guidance"></a>Guía de la coexistencia de carpetas públicas

- Proporcionar instrucciones sobre la coexistencia única de árbol de carpetas públicas, que incluyen:  
  - Preparación de carpetas públicas en Exchange 2007, Exchange 2010 y Exchange 2013. 
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
    
## <a name="microsoft-365-apps"></a>Aplicaciones de Microsoft 365

- Proporcionar instrucciones y asistencia para:  
  - Evaluación y planeación de acuerdo con los procedimientos recomendados de Microsoft para la implementación inicial y la administración de actualizaciones.
  - Habilitar el uso del Kit de herramientas de preparación para Office para identificar posibles problemas de compatibilidad con las macros de Microsoft VBA y los complementos instalados que se usan junto con Office.
  
## <a name="your-responsibilities"></a>Sus responsabilidades

You have the following responsibilities during onboarding. These are in addition to the responsibilities defined in the [Your Responsibilities](O365-your-responsibilities.md) section. 
  
- Asignar y administrar recursos de acuerdo al plan del proyecto.  
- Tomar las medidas oportunas para mitigar los riesgos y resolver los problemas provocados por el cliente, los administradores de proyectos asociados y el Administrador de FastTrack.   
- Revisar los informes de estado y actuar en consecuencia.   
- Asignar un líder o patrocinador operativo con autoridad para tomar decisiones para dirigir el comité directivo.  
- Asignar un patrocinador ejecutivo para trabajar con el patrocinador ejecutivo de Microsoft.  
- Establecer una reunión mensual del comité directivo.
