---
title: Responsabilidades de FastTrack
description: Responsabilidades de FastTrack cuando los clientes usan el beneficio del centro FastTrack para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 9b766eea35cb1c22906bf68733c1b19471858fb9
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513839"
---
# <a name="fasttrack-responsibilities"></a>Responsabilidades de FastTrack

FastTrack tiene las siguientes responsabilidades durante la incorporación.

## <a name="general"></a>General

-   Proporcionar asistencia de soporte remoto para las actividades de configuración necesarias, tal y como se indica en las descripciones detalladas de las fases.

-   Proporcionar documentación disponible, herramientas de software y consolas de administración para ayudarle a reducir o eliminar las tareas de configuración.

## <a name="initiate-phase"></a>Fase de inicio

-   Trabajar con usted para comenzar la incorporación.

-   Definir qué servicios elegibles desea incorporar.

## <a name="assess-phase"></a>Fase de evaluación

-   Proporcionar información general administrativa.

-   Proporcionar orientación acerca de:

    -   Necesidades de DNS, red e infraestructura.

    -   Necesidades de cliente (explorador de Internet, sistema operativo de cliente y necesidades de servicios).

    -   Identidad y aprovisionamiento de usuarios.

    -   Habilitación de los servicios elegibles que se han comprado y definido como parte de la incorporación.

-   Establecer la escala de tiempo para las actividades de corrección.

-   Proporcionar una lista de comprobación de corrección para Intune y Azure AD Premium.

## <a name="remediate-phase"></a>Fase de corrección

-   Mantenga las llamadas de conferencia con usted de acuerdo con la programación acordada para revisar el progreso de las actividades de corrección, por ejemplo, le guiará por los requisitos previos de instalación antes de incorporar un servicio en la nube de Microsoft.

## <a name="enable-phase"></a>Fase de habilitación
Proporcionar orientación acerca de:

-   Activar el espacio empresarial o la suscripción de Microsoft online Service.

-   Configurar los protocolos TCP/IP y puertos del firewall.

-   Configurar el DNS para los servicios pertinentes.

-   Validando la conectividad a Microsoft Online Services.

-   Para un entorno de un solo bosque:

    -   Instalar un servidor de sincronización de directorios entre los servicios de dominio de Active Directory (AD DS) y los servicios de Microsoft online elegibles (solo la guía si es necesario).

    -   Configuración de la autenticación administrada (autenticación de hash de contraseña o de paso a través) con la herramienta Azure Active Directory Connect. (solo guía si es necesario).

        > [!NOTE]
        > El desarrollo y la implementación de las extensiones de reglas personalizadas están fuera del ámbito.

-   Para un único bosque cuando el destino es identidades federadas: instalar y configurar los servicios de Federación de Active Directory (AD FS) para la autenticación de dominios local con Intune en una configuración de sitio único y tolerante a errores, si es necesario.

    > [!NOTE]
    > Para todas las configuraciones de varios bosques, las implementaciones de AD FS están fuera del ámbito.

-   Probar la funcionalidad de inicio de sesión único (SSO), si se ha implementado.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Fase de habilitación: Microsoft Azure Active Directory Premium

Proporcionar instrucciones sobre:

- Activar el espacio empresarial de Azure AD Premium.

- Configuración de puertos del firewall.

- Configurar el DNS para los servicios pertinentes.

- Validando la conectividad con los servicios de Azure AD Premium.

- Para un entorno de un solo bosque:

  -   Instalar una sincronización de directorios entre los servicios de dominio de Active Directory (AD DS) y Azure AD Connect, si es necesario.

  -   Configuración de un método de autenticación (sincronización de hash de contraseña o autenticación de paso a través) con la herramienta de Azure AD Connect.

- Para un entorno de varios bosques:

  -   Instalar la sincronización de Azure AD Connect, configurada para escenarios de varios bosques.
- Para los entornos de uno y varios bosques:
  - Configurar la autenticación de paso a través de Azure Active Directory, si es necesario.
  - Configurar el inicio de sesión único de conexión directa (SSO) de Azure Active Directory, si es necesario.
    > [!NOTE]
    > La autenticación de paso a través de Azure Active Directory para entornos de varios bosques se admite si hay confianzas entre sus bosques de Active Directory y si el enrutamiento de sufijo de nombre se ha configurado correctamente. Con el objetivo de poder proporcionar una disponibilidad alta para las solicitudes de inicio de sesión, pueden instalarse agentes adicionales en varios servidores locales.

  - Para obtener más información, vea [Autenticación de paso a través de Azure Active Directory: inicio rápido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) y [Inicio de sesión único de conexión directa de Azure Active Directory: Guía de inicio rápido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Para obtener más información acerca de los límites de la autenticación de paso a través, vea [Autenticación de paso a través de Azure Active Directory: limitaciones actuales](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Para obtener más información sobre los problemas del inicio de sesión único de conexión directa, vea [Solución de problemas de inicio de sesión único de conexión directa de Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > La sincronización de hash de contraseña y la escritura de contraseña admiten varios bosques. Sin embargo, no se admiten otros escenarios de reescritura.

  - Configurar la sincronización entre los bosques de Active Directory locales y el directorio de Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > El desarrollo y la implementación de las extensiones de reglas personalizadas están fuera del ámbito.

- Para un único bosque cuando el destino es identidades federadas:

  -   Instalación y configuración de AD FS para la autenticación de dominios local con Azure AD Premium en una configuración de sitio único y tolerante a errores (si es necesario).

  > [!NOTE]
  > Para todas las configuraciones de varios bosques, las implementaciones de AD FS están fuera del ámbito.

- Probar la funcionalidad SSO (si se ha implementado).

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>Fase de habilitación: Azure AD Premium--con Azure AD Connect y AD FS

Proporcionar instrucciones sobre la configuración de:

- Aprovisionamiento de usuarios, incluidas las licencias.

- Sincronización de directorios de Azure AD Connect (con la escritura diferida de contraseña y la sincronización de hash de contraseña).

  - Restablecimiento de contraseña de servicio propio de Azure Active Directory (SSPR).

  - Azure multi-factor Authentication.

  - Hasta tres (3) o más integraciones de aplicación de software como servicio (SaaS) con inicio de sesión único (SSO) desde [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Aprovisionamiento automático de usuarios para aplicaciones SaaS preintegradas, como se muestra en la [lista de tutorial de integración de aplicaciones](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list), limitada solo al aprovisionamiento saliente.

  - Pantalla de inicio de sesión personalizada, que incluye logotipos, texto e imágenes.

  - Grupos dinámicos y de autoservicio (grupos).

  - Proxy de aplicación de Azure Active Directory.

  - Estado de Azure Active Directory Connect.

  - Acceso condicional de Azure Active Directory.

  - Condiciones de uso de Azure Active Directory.

  - Protección de identidad de Azure Active Directory.

  - Administración de identidades privilegiada de Azure Active Directory.

  - Revisiones de acceso de Azure Active Directory.

### <a name="enable-phase---intune"></a>Fase de habilitación: Intune

> [!IMPORTANT]
> FastTrack no es compatible con la administración de equipos Windows 10 Classic con Intune. FastTrack solo admite la administración de Windows 10 a través de la administración de dispositivos móviles (MDM) de Intune.

Proporcionar **instrucciones** sobre:

-   Configurar las identidades que se usarán en Intune, ya sea aprovechando su Active Directory local o las identidades de nube (Azure Active Directory).

-   Conceder licencias a los usuarios finales.

-   Adición de usuarios a su suscripción de Intune, definición de roles de administrador de ti y creación de grupos de dispositivos y usuarios.

-   Configuración de la autoridad de la administración de dispositivos móviles (MDM), en función de las necesidades de administración, entre las que se incluyen:

    -   Establecer Intune como su autoridad de MDM.

    -   Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.

    -   Navegación por el portal de administración de Intune para buscar información en usuarios y dispositivos.

    -   Configuración de los roles de Intune (operador de asistencia técnica, administradores, etc.)

    -   Configuración de servicios y directivas de administración de MDM como:

        -   Implementación de aplicaciones para cada plataforma admitida a través de vínculos Web, MSI o vínculos profundos.

        -   Implementar Office ProPlus en dispositivos con Windows 10.

        -   Programas de compras por volumen para la implementación de aplicaciones, incluidos el PCV de Apple, la tienda Windows para empresas y la función reproducir para el almacén de trabajo de Google.

        -   Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tiene una entidad de certificación, una infraestructura de Wi-Fi o VPN en su organización.

        -   Configuración del conector de Exchange de Microsoft Intune (si es aplicable).

        -   Perfiles de configuración de dispositivo para plataformas de dispositivos compatibles.

    -   Configuración de directivas de acceso condicional.

    -   Configuración e implementación de directivas de protección de aplicaciones de Intune para cada plataforma compatible.

    -   Preparar aplicaciones de línea de negocio (LOB) para las directivas de protección de aplicaciones de Intune, con orientación sobre las opciones disponibles.

    -   Inscribir dispositivos de cada plataforma compatible con Intune o Configuration Manager con el servicio de Microsoft Intune.

    -   Conectando con el almacén de datos de Intune.

    -   Integración de Intune con:
        -   Team Viewer para asistencia remota (se requiere la suscripción a Team Viewer).

        -   Mobile Threat Defense Partner Solutions (se requiere la suscripción a una solución de socio para Mobile Threat Defense).

        -   Soluciones de administración de gastos de telecomunicaciones (se requiere una suscripción a la solución de administración de gastos de telecomunicaciones).

        -   Protección contra amenazas avanzada de Windows Defender (se necesitan licencias de Windows E5 o Microsoft 365 E5).

    -   Configuración de actualizaciones de software para plataformas compatibles aplicables.

    -   Recursos para la planeación de adopción de usuarios.

- Configuración de Windows AutoPilot:

    - Configurar y configurar Microsoft Intune para Windows AutoPilot.

    - Configurar grupos dinámicos de Azure AD

    - Agregue la personalización de marca de su empresa a Azure AD.

    - Cree y asigne dispositivos a perfiles de Windows AutoPilot (por ejemplo, un perfil de Windows AutoPilot que restringe la creación de cuentas de administrador local).

    - Personalizar la experiencia rápida (OOBE) para cumplir con los requisitos de la organización.

    - Configurar la inscripción automática de MDM en Azure AD e Intune.

    > [!NOTE]
    > La configuración de Windows AutoPilot fuera de Intune está fuera del ámbito del beneficio de FastTrack.

### <a name="enable-phase---co-management"></a>Fase de habilitación: Co-administración

Proporcionar instrucciones sobre:

-   Conceder licencias a los usuarios finales.

-   Adición de usuarios a su suscripción de Intune, definición de roles de administrador de ti y creación de grupos de usuarios y dispositivos (si no está instalado Intune).

-   Configuración de Azure Active Directory para la inscripción automática de MDM.

-   Configurar una Unión híbrida de Azure Active Directory.

-   Configurar la puerta de enlace de administración de nube.

-   Adición de usuarios a su suscripción de Intune, definición de roles de administrador de ti y creación de grupos de dispositivos y usuarios.

-   Preparar Intune (si Intune no está instalado):

    -   Configuración de la autoridad de la administración de dispositivos móviles (MDM), en función de las necesidades de administración, entre las que se incluyen:

    -   Establecer Intune como su autoridad de MDM.

    -   Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.

    -   Navegación por el portal de administración de Intune para buscar información en usuarios y dispositivos.

    -   Configuración de los roles de Intune (operador de asistencia técnica, administradores, etc.)

    -   Configuración e implementación de directivas de protección de aplicaciones de Intune para cada plataforma compatible.

    -   Inscribir dispositivos Windows 10 en su Intune.

- Habilite la co-administración en la consola de Configuration Manager.

- Cambie las cargas de trabajo a Intune.

- Supervisar la actividad de co-administración en el entorno.

### <a name="enable-phase--azure-information-protection"></a>Fase de habilitación: Azure Information Protection

Proporcionar soporte técnico para: 

- Los clientes pueden clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook) que se ejecutan en Windows y que usan el cliente de Azure Information Protection. 
- Archivos en reposo con el escáner de Azure Information Protection.
- Mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online. 

También se proporciona soporte técnico a los clientes que quieren aplicar la protección con Microsoft Azure Rights Management Services (Azure RMS), el cifrado de mensajes de Office 365 (OME) y la prevención de pérdida de datos (DLP). 

A los clientes se les proporciona orientación sobre cómo: 

- Activar y configurar su inquilino.
- Cree y configure etiquetas y directivas.
- Aplicar protección de la información a los documentos. 

> [!NOTE]
> **¿Desea obtener más información?** consulte [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Pasos siguientes

[Beneficio de FastTrack para EMS-sus responsabilidades](EMS-your-responsibilities.md)
