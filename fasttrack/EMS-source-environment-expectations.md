---
title: Expectativas del entorno de origen
description: Requisitos del entorno de origen para usar el beneficio del centro FastTrack para EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a512e97f48df7fc3040478f4e35fe0c357ef7ce3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513155"
---
# <a name="source-environment-expectations"></a>Expectativas del entorno de origen

Cuando se usan las [ventajas del centro de FastTrack para Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) para obtener Microsoft Azure Active Directory Premium, Microsoft Intune y Azure Information Protection Ready for use, el entorno debe cumplir con las expectativas. se describe en las secciones siguientes.

Es posible que ya tenga Active Directory local en su organización y quiera integrarse con Enterprise Mobility + Security (EMS) o con cualquiera de sus servicios individuales que use la administración de identidades enriquecida desde una única consola. Las ventajas del centro de FastTrack para Enterprise Mobility + Security (EMS) incluyen ayudarle a integrar Azure Active Directory con su entorno local de Active Directory existente.

En la siguiente tabla se muestran las expectativas del entorno de origen existente para la incorporación.

|Actividad|Expectativa del entorno de origen|
|------------|----------------------------------|
|Central de incorporación|Bosques de Active Directory con el nivel funcional de bosque establecido en Windows Server 2008 o posterior, con la siguiente configuración del bosque:<br /><br />-Un solo bosque de Active Directory<br />-Varios bosques de Active Directory </br></br>**Nota**: para todas las configuraciones de varios bosques, la implementación de los servicios de Federación de Active Directory (AD FS) está fuera del ámbito del beneficio del centro FastTrack.|
|Incorporación de Azure AD Premium|La implementación local de Active Directory y su entorno se han preparado para Azure AD Premium, que incluye la corrección de problemas identificados que impiden la integración con Azure AD y las características de Azure AD Premium.|
|Incorporación de Intune| Los administradores de TI deben tener infraestructuras de entidades de certificación, WiFi y VPN ya existentes en sus entornos de producción al planear la implementación de perfiles de Wi-Fi y VPN con Intune.<br /><br /> **Nota**: el beneficio del servicio no incluye asistencia para configurar o configurar entidades de certificación, redes Wi-Fi, infraestructuras VPN o certificados push de Apple para  |
|Coadministración|Con la coadministración, los administradores de TI son responsables de preparar el entorno local, que puede incluir correcciones de problemas que le impiden administrar simultáneamente dispositivos con Windows 10 con Configuration Manager e Intune.<br /><br />**Nota**: el beneficio del servicio de FastTrack no incluye la asistencia para configurar o actualizar el cliente de Configuration Manager o el servidor de configuración del administrador de configuración a los requisitos mínimos necesarios para admitir la coadministración con dispositivos Windows 10. |
|Intune integrado con la protección contra amenazas avanzada de Windows Defender (ATP de Windows Defender)|La suscripción ATP de Windows Defender se ha activado y configurado en función de los requisitos de seguridad de la compañía.<br /><br />**Nota**: el beneficio del servicio FastTrack proporciona asistencia sobre la integración de Intune con Windows Defender ATP y la creación de directivas de cumplimiento de dispositivos basadas en su evaluación del nivel de riesgo de Windows 10. La ventaja del servicio FastTrack no proporciona asistencia sobre la compra, concesión de licencias, activación o el uso de ATP de Windows Defender y su consola del centro de seguridad. |
|Windows Autopilot|Los administradores de TI son responsables de registrar sus dispositivos en su organización, ya sea para que el proveedor de hardware cargue sus identificadores de hardware en su nombre o al cargarlos en el servicio de Windows AutoPilot. |
|Implementación de Outlook para iOS y Android de manera segura con Intune|<br /><br />-Identidades de usuario habilitadas en Azure AD para Office 365.<br />-Exchange online o Exchange híbrido configurado con licencias de usuario asignadas.<br />|
|Azure Information Protection (P2 o EMS E5)|<br /><br />Los clientes ya deben: <br /> -Usar Azure AD.<br />-Use Windows o iOS (otros sistemas operativos están fuera del ámbito).<br /> -Use clientes de Office más recientes que Office 2010 SP2 que no confíen en Office online como cliente principal. <br /> -Tener sus ubicaciones principales de recursos compartidos de archivos.  <br /> -Se ha actualizado desde Active Directory Rights Management Services (AD RMS). <br /> -Tener una taxonomía de clasificación aprobada. <br /> -Comprenda las restricciones regulatorias para su administración de claves protegida. <br />|
|Escáner de Azure Information Protection|<br /><br /> Los clientes ya deben: <br /> -Use Windows Server 2012 R2 o Windows Server 2016.<br /> -Tener una conexión a Internet. <br /> -Tener Microsoft SQL Server 2012 en adelante en una instancia local o remota.  <br /> -Tener una cuenta de servicio creada para su Active Directory local y sincronizada con Azure AD.  <br /> -Haber descargado AzInfoProtection. exe. <br /> -Tener etiquetas configuradas para la clasificación/protección automática.<br />|

> [!NOTE]
> **¿Desea obtener más información?** 
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Pasos siguientes

[Ventajas del centro de FastTrack para las fases de incorporación de EMS](EMS-onboarding-phases.md)
