---
title: Responsabilidades de FastTrack
description: Responsabilidades de FastTrack cuando los clientes usan las ventajas del Centro de FastTrack para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 2/04/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0f5ed94a81a1846c8652cf78f96b6253ab774b5d
ms.sourcegitcommit: 7365d80b2e4291e547c2d84b94da02697221abc9
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 02/03/2020
ms.locfileid: "41676616"
---
# <a name="fasttrack-responsibilities"></a>Responsabilidades de FastTrack

FastTrack tiene las siguientes responsabilidades durante la incorporación:

## <a name="general"></a>General

-   Proporcionar soporte técnico remoto para las actividades de configuración necesarias, tal y como se muestra en las descripciones detalladas de las fases.

-   Proporcionar la documentación disponible, las herramientas de software y las consolas de administración para ayudarle a reducir o eliminar las tareas de configuración.

## <a name="initiate-phase"></a>Fase de inicio

-   Trabajar con usted para comenzar la incorporación.

-   Definir qué servicios elegibles desea incorporar.

## <a name="assess-phase"></a>Fase de evaluación

-   Proporcionar información general administrativa.

-   Proporcionar orientación acerca de:

    -   Necesidades de DNS, red e infraestructura.

    -   Necesidades del cliente (explorador de Internet, sistema operativo de cliente y necesidades de servicios).

    -   Identidad y aprovisionamiento de usuarios.

    -   Habilitar los servicios pertinentes que se han adquirido y definido como parte de la incorporación.

-   Establecer la escala de tiempo para las actividades de corrección.

-   Proporcionar una lista de comprobación de correcciones para Intune y Azure AD Premium.

## <a name="remediate-phase"></a>Fase de corrección

-   Realizar llamadas de conferencia con usted de acuerdo con la programación acordada para revisar el progreso de las actividades de corrección (por ejemplo, instrucciones sobre los requisitos previos de instalación antes de la incorporación a un servicio en la nube de Microsoft).

## <a name="enable-phase"></a>Fase de habilitación
Proporcionar orientación acerca de:

-   La activación de la suscripción o del espacio empresarial de Microsoft Online Services.

-   Configurar los protocolos TCP/IP y puertos del firewall.

-   Configurar el DNS para los servicios pertinentes.

-   La validación de la conectividad a Microsoft Online Services.

-   En un entorno de un solo bosque:

    -   Instalación de un servidor de sincronización de directorios entre Active Directory Domain Services (AD DS) y los Microsoft Online Services pertinentes (solo instrucciones si es necesario).

    -   Configuración de la autenticación administrada (sincronización de hash de contraseña o autenticación de paso a través) con la herramienta Azure Active Directory Connect. (solo instrucciones si es necesario).

        > [!NOTE]
        > El desarrollo y la implementación de extensiones de reglas personalizadas están fuera del ámbito.

-   Para un solo bosque cuando las identidades federadas son el destino: instalación y configuración de los Servicios de federación de Active Directory (AD FS) para la autenticación de dominios local con Intune en una configuración de sitio único y tolerante a errores, si es necesario.

    > [!NOTE]
    > En todas las configuraciones de varios bosques, las implementaciones de AD FS están fuera del ámbito.

-   Pruebas de funcionalidad de inicio de sesión único (SSO), si se ha implementado.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Fase de habilitación: Microsoft Azure Active Directory Premium

Proporcionar instrucciones acerca de:

- La activación del espacio empresarial de Azure AD Premium.

- La configuración de puertos del firewall.

- La configuración del DNS para los servicios pertinentes.

- La validación de la conectividad a los servicios de Azure AD Premium.

- En un entorno de un solo bosque:

  -   Instalación de una sincronización de directorios entre Active Directory Domain Services (AD DS) y Azure AD Connect, si es necesario.

  -   Configuración de un método de autenticación (sincronización hash de contraseña o autenticación de paso a través) con la herramienta Azure AD Connect.

- Para un entorno de varios bosques:

  -   Instalación de la sincronización de Azure AD Connect, configurado para escenarios con varios bosques.
- Para los entornos de uno y varios bosques:
  - Configurar la autenticación de paso a través de Azure Active Directory, si es necesario.
  - Configurar el inicio de sesión único de conexión directa (SSO) de Azure Active Directory, si es necesario.
    > [!NOTE]
    > La autenticación de paso a través de Azure Active Directory para entornos de varios bosques se admite si hay confianzas entre sus bosques de Active Directory y si el enrutamiento de sufijo de nombre se ha configurado correctamente. Con el objetivo de poder proporcionar una disponibilidad alta para las solicitudes de inicio de sesión, pueden instalarse agentes adicionales en varios servidores locales.

  - Para obtener más información, vea [Autenticación de paso a través de Azure Active Directory: inicio rápido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) y [Inicio de sesión único de conexión directa de Azure Active Directory: Guía de inicio rápido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Para más información sobre los límites de la autenticación de paso a través, vea [Autenticación de paso a través de Azure Active Directory: Limitaciones actuales](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Para obtener más información sobre los problemas del inicio de sesión único de conexión directa, vea [Solución de problemas de inicio de sesión único de conexión directa de Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > La sincronización de hash de contraseña y la escritura diferida de la contraseña son compatibles con varios bosques. Pero no se admiten otros escenarios de escritura diferida.

  - Configuración de sincronización entre bosques de Active Directory local y el directorio de Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > El desarrollo y la implementación de extensiones de reglas personalizadas están fuera del ámbito.

- Para un solo bosque cuando las identidades federadas son el destino:

  -   Instalación y configuración de AD FS para la autenticación de dominios local con Azure AD Premium en una configuración de sitio único y tolerante a errores, si es necesario.

  > [!NOTE]
  > En todas las configuraciones de varios bosques, las implementaciones de AD FS están fuera del ámbito.

- Pruebas de funcionalidad de SSO, si se ha implementado.

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Fase de habilitación: Azure AD Premium con Azure AD Connect y AD FS

Proporcionar instrucciones sobre cómo configurar:

- El aprovisionamiento de usuarios (incluidas las licencias).

- La sincronización de directorios de Azure AD Connect (con sincronización de hash de contraseña y escritura diferida de contraseña).

  - El autoservicio de restablecimiento de contraseña (SSPR) de Azure Active Directory.

  - Azure Multi-Factor Authentication.

  - Hasta tres (3) o más integraciones de aplicaciones de Software como servicio (SaaS) con el inicio de sesión único (SSO) desde [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - El aprovisionamiento automático de usuarios para aplicaciones SaaS previamente integradas que se muestran en la [lista de tutoriales de integración de aplicaciones](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list) limitada solo al aprovisionamiento saliente.

  - Pantalla de inicio de sesión personalizada, incluido el logotipo, el texto y las imágenes.

  - Grupos dinámicos y de autoservicio (grupos).

  - Azure Active Directory Application Proxy.

  - Azure Active Directory Connect Health.

  - Acceso condicional de Azure Active Directory.

  - Términos de uso de Azure Active Directory.

  - Azure Active Directory Identity Protection.

  - Azure Active Directory Privileged Identity Management.

  - Revisiones de acceso de Azure Active Directory.

### <a name="enable-phase---intune"></a>Fase de habilitación: Intune

> [!IMPORTANT]
> FastTrack no es compatible con la administración de equipos clásica de Windows 10 con Intune. FastTrack solo es compatible con la administración de Windows 10 a través de la administración de dispositivos móviles (MDM) de Intune.

Proporcionar instrucciones sobre :

-   Configurar las identidades que se van a usar en Intune, al usar su Active Directory local o las identidades de la nube (Azure Active Directory).

-   Conceder licencias a los usuarios finales.

-   Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.

-   Configurar la entidad de la administración de dispositivos móviles (MDM), en función de las necesidades de administración, entre las que se incluyen:

    -   Establecer Intune como entidad MDM.

    -   Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.

    -   Navegar por el portal de administración de Intune para localizar información sobre usuarios y dispositivos.

    -   Configurar los roles de Intune (operador de soporte técnico, administradores, etc.)

    -   Configurar servicios y directivas de administración de MDM como:

        -   La implementación de aplicaciones para cada plataforma compatible mediante vínculos web, MSI y/o vínculos profundos.

        -   La implementación de Office ProPlus en dispositivos con Windows 10.

        -   Programas de compras por volumen para la implementación de aplicaciones, incluidos VPP de Apple, la tienda Windows para empresas y Play for Work Store de Google.

        -   La implementación del correo electrónico, las redes inalámbricas y los perfiles de VPN si tiene una infraestructura de VPN, Wi-Fi o una entidad de certificación existente en la organización.

        -   La configuración de Microsoft Intune Exchange Connector (si es necesario).

        -   Perfiles de configuración de dispositivo para plataformas de dispositivo compatibles.

    -   Configurar directivas de acceso condicional.

    -   Configurar e implementar directivas de protección de aplicaciones de Intune para cada plataforma compatible.

    -   Preparar aplicaciones de línea de negocio (LOB) para las directivas de protección de aplicaciones de Intune, con instrucciones sobre las opciones disponibles.

    -   Inscribir dispositivos de cada plataforma compatible a Intune o Configuration Manager con el servicio de Microsoft Intune.

    -   Conectarse al almacenamiento de datos de Intune.

    -   Integrar Intune con:
        -   Team Viewer para asistencia remota (se requiere una suscripción a Team Viewer).

        -   Soluciones de partner de Mobile Threat Defense (se requiere una suscripción a la solución de partner de Mobile Threat Defense).

        -   Soluciones de administración de gastos de telecomunicaciones (se requiere una suscripción a la solución de administración de gastos de telecomunicaciones).

        -   Protección contra amenazas avanzada de Windows Defender (se requieren licencias de Windows E5 o de Microsoft 365 E5).

    -   Configurar las actualizaciones de software para las plataformas compatibles aplicables.

    -   Recursos para planear la adopción de usuarios.

- Configurar Windows Autopilot:

    - Configurar Microsoft Intune para Windows Autopilot.

    - Configurar grupos dinámicos de Azure AD.

    - Agregar la personalización de marca de la empresa a Azure AD.

    - Crear y asignar dispositivos a perfiles de Windows Autopilot (por ejemplo, un perfil de Windows Autopilot que limite la creación de cuentas de administrador local).

    - Personalizar la configuración rápida (OOBE) para cumplir los requisitos de la organización.

    - Configurar la inscripción automática de MDM en Azure AD e Intune.

    > [!NOTE]
    > Configurar Windows Autopilot fuera de Intune está fuera del ámbito de las ventajas de FastTrack.

### <a name="enable-phase---co-management"></a>Fase de habilitación: administración conjunta

Proporcionar instrucciones sobre cómo:

-   Conceder licencias a los usuarios finales.

-   Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos (si Intune no está instalado).

-   Configurar Azure Active Directory para la inscripción automática de MDM.

-   Configurar la unión híbrida de Azure Active Directory.

-   Configurar Cloud Management Gateway.

-   Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.

-   Preparar Intune (si Intune no está instalado):

    -   Configurar la entidad de la administración de dispositivos móviles (MDM), en función de las necesidades de administración, entre las que se incluyen:

    -   Establecer Intune como entidad MDM.

    -   Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.

    -   Navegar por el portal de administración de Intune para localizar información sobre usuarios y dispositivos.

    -   Configurar los roles de Intune (operador de soporte técnico, administradores, etc.)

    -   Configurar e implementar directivas de protección de aplicaciones de Intune para cada plataforma compatible.

    -   Inscribir dispositivos Windows 10 en su Intune.

- Habilitar la administración conjunta en la consola de Configuration Manager.

- Cambiar las cargas de trabajo a Intune.

- Supervisar la actividad de administración conjunta de su entorno.

### <a name="enable-phase--azure-information-protection"></a>Fase de habilitación: Azure Information Protection

Proporcionar instrucciones sobre cómo: 

- Activar y configurar el espacio empresarial de cliente.

- Crear y configurar etiquetas y directivas.

- Aplicar la protección de la información a documentos. 

- Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.

- Usar archivos en reposo con el escáner de Azure Information Protection.

- Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.

También se proporcionan instrucciones para los clientes que quieran aplicar la protección con Microsoft Azure Rights Management Services (Azure RMS), el cifrado de mensajes de Office 365 (OME) y la prevención de pérdida de datos (DLP).

> [!NOTE]
> **¿Quiere obtener más información?** vea [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).  

## <a name="next-steps"></a>Pasos siguientes

[Ventajas de FastTrack para EMS: sus responsabilidades](EMS-your-responsibilities.md)
