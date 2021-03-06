---
title: FastTrack Responsabilidades de Office 365 Gobierno de EE. UU.
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: Los especialistas de FastTrack tienen las siguientes responsabilidades durante la incorporación.
ms.openlocfilehash: 57e1ba446304fba42e3c1b815351d3942c6b4e39
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994917"
---
# <a name="fasttrack-responsibilities-for-office-365-us-government"></a>FastTrack Responsabilidades de Office 365 Gobierno de EE. UU.

Los especialistas de FastTrack tienen las siguientes responsabilidades durante la incorporación.  
  
## <a name="general"></a>General

- Proporcionar soporte técnico remoto para que planee satisfactoriamente el desarrollo y la implementación, así como para las actividades de configuración necesarias, tal y como se detalla en las descripciones de las fases.
- Proporcione la documentación y las herramientas de software disponibles, consolas de administración y guiones para proporcionarle ayuda para reducir o eliminar las tareas de configuración y los recursos de planificación correctos.   
    
## <a name="initiate-phase"></a>Fase de inicio

- Trabajar con usted para conocer su propósito, los objetivos de la organización y los planes de uso del servicio. 
- Trabajar con usted mediante los servicios de colaboración de Office 365 (como Microsoft Teams) para empezar la incorporación. 
- Definir qué servicios elegibles desea incorporar. 
    
## <a name="assess-phase"></a>Fase de evaluación

- Mantener una llamada sobre la correcta planificación para ayudar a mejorar para la aceptación por parte de los usuarios.  
- Proporcionar información general administrativa.  
- Proporcionar orientación acerca de: 
  - Necesidades de sistema de nombres de dominio (DNS), red e infraestructura.  
  - Necesidades del cliente (explorador de Internet, sistema operativo de cliente, dispositivo móvil y necesidades de servicios).
  - Identidad y aprovisionamiento de usuarios. 
  - Habilitar los servicios elegibles adquiridos y definidos como parte de la incorporación.
  - Impulsar el valor y la adopción de servicios correctos.   
- Establecer la escala de tiempo para las actividades de corrección.
- Proporcionar una lista de comprobación de corrección.   
- Evaluar la infraestructura existente SharePoint Server 2013 o SharePoint Server 2016 la infraestructura incluido:  
  - Requisitos previos para el Entorno híbrido de SharePoint Online.  
  - Preparación de la infraestructura local para características de Entorno híbrido de SharePoint Online.  
  - Acceso a los extremos requeridos de SharePoint Online. 
  - Audiencias para OneDrive para la Empresa híbrido.    
- Evaluar la infraestructura existente de Lync o Skype Empresarial Online, que incluye:  
  - Estrategia de implementación de un cliente de Skype Empresarial compatible.  
  - Acceso a los puntos de conexión.  
  - Calidad de la conexión.  
  - Estimaciones de ancho de banda.  
  - Requisitos previos para admitir la configuración del servidor de dominio dividido.  
  - Preparación de los usuarios identificados para mover a Skype Empresarial Online.  
- Evaluar la infraestructura de mensajería, incluidos:   
  - Flujo de correo y principios de enrutamiento generales.  
  - Acceso de clientes (incluidos los extremos existentes de acceso de cliente publicados).  
  - Entorno de mensajería de origen para las necesidades de integración. 
- Proporcionar migración de datos si se usa el servicio de migración de datos del centro FastTrack y se cumplen los requisitos de elegibilidad.
    
## <a name="remediate-phase"></a>Fase de corrección

- Mantener llamadas de conferencia con usted según la planificación acordada para revisar el progreso de las actividades de corrección y la correcta planeación.   
- Guiarle en la ejecución de las herramientas de evaluación para identificar y corregir problemas e interpretar los resultados.
    
## <a name="enable-phase"></a>Fase de habilitación

Proporcionar orientación acerca de: 
- Evaluar el progreso del éxito de la planeación y averiguar si necesita más ayuda.    
- Activar el espacio empresarial de Office 365.
- Configurar los protocolos TCP/IP y puertos del firewall.   
- Configurar el DNS para los servicios pertinentes.   
- Validar la conectividad con Office 365.   
- Conectar Active Directory local con Azure Active Directory:   
  - Instalar un servidor de sincronización de directorios entre los Servicios de dominio de Active Directory (AD DS) y Office 365 (en caso necesario).   
  - Configurar la sincronización de contraseña (hash de contraseña) a Office 365 (Azure Active Directory) con la herramienta Azure Active Directory Connect, si es necesario.  
  - Para los entornos de uno y varios bosques:
      - Configuración de Azure Active Directory autenticación de paso a través, si es necesario (no disponible en GCC planes De alta o doD).
      - Configuración de Azure Active Directory single Sign-On sin Sign-On (SSO), si es necesario (no disponible en GCC planes High o DoD).
    > [!NOTE]
    > La autenticación de paso a través de Azure Active Directory para entornos de varios bosques se admite si hay confianzas entre sus bosques de Active Directory y si el enrutamiento de sufijo de nombre se ha configurado correctamente. Con el objetivo de poder proporcionar una disponibilidad alta para las solicitudes de inicio de sesión, pueden instalarse agentes adicionales en varios servidores locales. Para obtener más información, vea [Autenticación de paso a través de Azure Active Directory: inicio rápido](https://go.microsoft.com/fwlink/?linkid=860094) y [Inicio de sesión único de conexión directa de Azure Active Directory: Guía de inicio rápido](https://go.microsoft.com/fwlink/?linkid=860095).[!NOTE]
    > Para más información sobre los límites de la autenticación de paso a través, vea [Autenticación de paso a través de Azure Active Directory: Limitaciones actuales](https://go.microsoft.com/fwlink/?linkid=860356).[!NOTE]
    > Para obtener más información sobre los problemas del inicio de sesión único de conexión directa, vea [Solución de problemas de inicio de sesión único de conexión directa de Azure Active Directory](https://go.microsoft.com/fwlink/?linkid=841926). 
- Para un único bosque cuando las identidades federadas son el destino: 
  - Instalar y configurar AD FS para la autenticación de dominios local con Office 365 en una configuración de sitio único y tolerante a errores, si es necesario.  
  - Instalar y configurar WAP para publicar la infraestructura de AD FS en Internet, cuando sea necesario. 
    > [!NOTE]
    > En todas las configuraciones de varios bosques, las implementaciones de AD FS quedan fuera del ámbito. 
- Probar la funcionalidad de SSO si se ha implementado.   
- Impulsar el valor y la adopción de servicios correctos.
    
## <a name="compliance"></a>Cumplimiento

Proporcionar orientación acerca de:
- Asistencia remota con **Microsoft Information Governance** (vea Security and [Compliance](products-and-capabilities.md#security-and-compliance)).
- Asistencia remota con **Microsoft Information Protection** (vea [Seguridad y cumplimiento](products-and-capabilities.md#security-and-compliance)).
- Asistencia remota con **Azure Information Protection** (vea Seguridad y [cumplimiento).](products-and-capabilities.md#security-and-compliance)

## <a name="exchange-online"></a>Exchange Online

Proporcionar orientación acerca de: 
- Crear o actualizar los registros DNS.    
- Habilitar el enrutamiento de correo electrónico entre el sistema de mensajería de origen y los entornos de Office 365.    
- Configurar las características de Protección de Exchange Online (incluidas las características de Protección contra amenazas avanzada de Exchange Online si están disponibles en su suscripción) y comprobar que los registros MX se refieren a Office 365 para todos los dominios habilitados para correo que se han validado.   
- Configurar una instalación híbrida entre una sola organización de Exchange local y Office 365 *o* entre varias organizaciones de Exchange local y Office 365. 
- Configurar la mensajería unificada (UM) con Exchange Online (la mensajería unificada no está disponible en GCC de DoD). 
    
Para obtener más información sobre las responsabilidades relativas a la migración de datos, vea [Migración de datos](data-migration.md).
  
## <a name="sharepoint-online"></a>SharePoint Online

Proporcionar orientación acerca de:
- Configurar el aprovisionamiento de usuarios, incluidas las licencias.   
- Habilitar la creación de sitios para el administrador de SharePoint Online.   
- Planificar las colecciones de sitios.   
- Proteger el contenido y administrar los permisos.   
- Habilitar sitios personales y características sociales.   
- Configurar las características de SharePoint Online.    
- Proporcionar migración de datos si se usa el servicio de migración de datos del centro FastTrack y se cumplen los requisitos de elegibilidad.  
- Evaluar la configuración de infraestructura de granja de SharePoint local necesaria para Entorno híbrido de SharePoint Online.    
- Utilizar herramientas y automatización para: 
  - Configurar aplicaciones de servicio de búsqueda en la nube local.    
  - Configurar la confianza entre SharePoint local y los entornos de la nube.   
- Configurar sitios de SharePoint local para usar características de Entorno híbrido de SharePoint Online.
    
## <a name="onedrive-for-business"></a>OneDrive para la Empresa

Proporcionar orientación acerca de: 
- Identificar la versión de SharePoint local y las opciones de integración.    
- Identificar las opciones de sincronización y de identidad.   
- Seleccionar una opción de lanzamiento:   
  - Lanzamiento en el momento.  
  - Lanzamiento preconfigurado (secuencial y en fases).   
- Preparar el entorno local para la implementación de OneDrive para la Empresa:  
  - Identificar el cliente de sincronización de OneDrive para la Empresa correcto. 
  - Configurar el DNS, los puertos de red y el firewall.   
- Asignar licencias de usuario final.   
- Configurar las audiencias de SharePoint Online para controlar y regir quién obtiene OneDrive para la Empresa.    
- Implementar el cliente de sincronización de OneDrive para la Empresa en equipos de escritorio.   
- Cómo configurar el redireccionamiento de OneDrive para la Empresa en el Entorno híbrido de SharePoint Online (solo SharePoint 2013 y SharePoint 2016).  
- Realizar la migración de datos si se usa el servicio de migración de datos del Centro de FastTrack y se cumplen los requisitos de elegibilidad.
    
## <a name="skype-for-business-online"></a>Skype Empresarial Online

Proporcionar orientación acerca de:
- Aprovisionar identidades de Skype Empresarial para Office 365.   
- Habilitar conferencias en línea, mensajería instantánea (MI) y características de presencia de Office 365.  
- Creación de cuentas para asociar a los dispositivos de sistema de salas de reuniones compatibles (hasta 10 cuentas).    
- Configurar un entorno de servidores de dominio dividido para admitir escenarios híbridos de Lync o Skype Empresarial Online (si corresponde).   
- Habilitar audioconferencia:   
  - Parámetros predeterminados de la configuración de la organización para puente de conferencia.   
  - Asignación de puente de conferencia a usuarios con licencia. 
- Habilitar Sistema telefónico (no disponible en GCC planes De alto o DoD):  
  - Habilitar la incorporación de sistema telefónico y planes de llamada (en los mercados disponibles). 
  - Asignación de números a usuarios con licencia.  
  - Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.  
  - Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.  
- Habilitar Skype Empresarial difusión de reunión (no disponible en GCC planes De alto o doD):  
  - Incorporación de instrucciones para la habilitación de la Difusión de reunión de Skype Empresarial.  
  - Configuración de la organización para los parámetros predeterminados de federación con el servicio de difusión de reunión.
    
## <a name="microsoft-teams"></a>Microsoft Teams

Proporcionar orientación acerca de:
- Confirmación de requisitos mínimos.   
- Configuración de puertos del firewall.  
- Configuración de DNS.  
- Confirmando que se ha habilitado Microsoft Teams en su espacio empresarial de Office 365.   
- Habilitar o deshabilitar licencias de usuario.  
- Distribución de clientes de Microsoft Teams.    
- Características para profesionales de TI y administradores. 
- Características de productos principales.  
- Plantillas de éxito de clientes.
    
## <a name="power-bi"></a>Power BI

Proporcionar orientación acerca de:
- Revisar los planes de suscripción de Power BI.    
- Agregar el servicio de Power BI.    
- Descargar la aplicación Power BI Desktop.
    
## <a name="project-online"></a>Project Online

Proporcionar orientación acerca de:  
- Revisar los planes de suscripción.  
- Comprobar la funcionalidad básica de SharePoint.    
- Agregar el servicio de Project Online.  
- Agregar usuarios a Project Online, incluida la sincronización de ERP.  
- Comprobar la funcionalidad básica de Project Online mediante la creación de un proyecto.
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

Proporcionar instrucciones sobre cómo convertir la red única de Yammer Basic en una red única de Yammer Enterprise.

> [!NOTE]
> Yammer Enterprise no es un componente de Office 365 gobierno de estados unidos, pero se puede adquirir sin costo como una oferta independiente para cada usuario con licencia para Office 365 en GCC. Actualmente, esta oferta está limitada a los clientes que compren Office 365 GCC contratos Enterprise contratos y Enterprise de suscripción. Yammer no está disponible en los planes GCC High o DoD.
  
## <a name="microsoft-365-apps"></a>Aplicaciones de Microsoft 365

Proporcionar instrucciones acerca de:
- Solucionar los problemas de implementación.   
- Asignar licencias de usuario final mediante el [Centro de administración de Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704) y Windows PowerShell.  
- Instalar Aplicaciones de Microsoft 365 desde el Portal de Office 365 con la opción Hacer clic y ejecutar.   
- Instalar aplicaciones de Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile y PowerPoint Mobile) en sus dispositivos de iOS, Android, o Windows Mobile.   
- Configurar las opciones de actualización mediante la Herramienta de implementación de Office 2016 o las plantillas de directiva de grupo.   
- Configurar un único servidor de distribución en el sitio para Aplicaciones Microsoft 365, incluida la asistencia con la creación de un archivo configuration.xml para su uso con la herramienta de Office 365 implementación.   
- Implementar mediante Microsoft Endpoint Configuration Manager, incluida la ayuda con la creación del empaquetado de Microsoft Endpoint Configuration Manager.
