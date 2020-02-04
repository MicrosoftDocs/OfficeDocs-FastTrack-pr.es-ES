---
title: Expectativas del entorno de origen
description: Requisitos del entorno de origen para usar las ventajas del Centro de FastTrack para EMS
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
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: caceb5d7fd5a689dbd4e5e1d7c94096b36752315
ms.sourcegitcommit: 7365d80b2e4291e547c2d84b94da02697221abc9
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 02/03/2020
ms.locfileid: "41676796"
---
# <a name="source-environment-expectations"></a>Expectativas del entorno de origen

Al usar las [Ventajas del Centro de FastTrack para Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) para obtener Microsoft Azure Active Directory Premium, Microsoft Intune y Azure Information Protection listos para usarse, su entorno necesita cumplir las expectativas descritas en las secciones siguientes.

Es posible que ya disponga de Active Directory local en su organización y quiera que se integre con Enterprise Mobility + Security (EMS) o con cualquiera de sus servicios individuales que usen la administración de identidades enriquecida desde una única consola. Las ventajas del Centro de FastTrack para Enterprise Mobility + Security (EMS) incluyen ayudarle a integrar Azure Active Directory con el entorno local de Active Directory existente.

En la siguiente tabla se muestran las expectativas del entorno de origen existente para la incorporación.

|Actividad|Expectativa del entorno de origen|
|------------|----------------------------------|
|Incorporación principal|Bosques de Active Directory con el nivel funcional de bosque establecido como Windows Server 2008 o superior, con la configuración del bosque siguiente:<br /><br />- Un solo bosque de Active Directory<br />- Varios bosques de Active Directory </br></br>**Nota**: para todas las opciones de configuración de varios bosques, la implementación de los Servicios de federación de Active Directory (AD FS) está fuera del ámbito de las ventajas del Centro de FastTrack.|
|Incorporación de Azure AD Premium|Active Directory local y su entorno se han preparado para Azure AD Premium que incluye la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.|
|Incorporación de Intune| Los administradores de TI deben disponer de infraestructuras de VPN, WiFi o una entidad de certificación que ya funcionan en sus entornos de producción al planear la implementación de perfiles WiFi y VPN con Intune.<br /><br /> **Nota**: la ventaja del servicio no incluye la asistencia para configurar entidades de certificación, WiFi, infraestructuras de VPN o certificados de inserción MDM de Apple para  |
|Administración conjunta|Con la administración conjunta, los administradores de TI son responsables de la preparación del entorno local, lo que podría incluir la corrección de problemas que impiden la administración simultánea de dispositivos con Windows 10 mediante Configuration Manager e Intune.<br /><br />**Nota**: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager o el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la administración conjunta en dispositivos con Windows 10. |
|Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)|**Nota**: las ventajas del servicio de FastTrack ofrecen asistencia para la integración de Intune con la ATP de Microsoft Defender y la creación de directivas de cumplimiento de dispositivos en función de la evaluación de nivel de riesgo de Windows 10. Las ventajas del servicio no ofrecen asistencia para la compra, la concesión de licencias o la activación. |
|Windows Autopilot|Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot. |
|Implementar Outlook para iOS y Android de forma segura con Intune|<br /><br />- Identidades de usuario habilitadas en Azure AD para Office 365.<br />- Exchange Online o Exchange híbrido configurado con las licencias de usuario asignadas.<br />|
|Azure Information Protection (P2 o EMS E5)|<br /><br />Los clientes ya deben: <br /> - Usar Azure AD.<br />- Usar Windows o iOS (otros SO están fuera del ámbito).<br /> - Usar clientes de Office más recientes que Office 2010 SP2 que no se basan en Office como cliente principal. <br /> - Tener las principales ubicaciones de uso compartido de archivos.  <br /> - Haber actualizado Active Directory Rights Management Services (AD RMS). <br /> - Tener una taxonomía de clasificación aprobada. <br /> - Comprender las restricciones reglamentarias para la administración de claves protegida. <br />|
|Escáner de Azure Information Protection|<br /><br /> Los clientes ya deben: <br /> - Usar Windows Server 2012 R2 o Windows Server 2016.<br /> - Tener conexión a Internet. <br /> - Tener Microsoft SQL Server 2012 en adelante en una instancia local o remota.  <br /> - Tener una cuenta de servicio creada para su Active Directory local y sincronizada con Azure AD.  <br /> - Haber descargado AzInfoProtection.exe. <br /> - Tener etiquetas configuradas para la clasificación y protección automática.<br />|

> [!NOTE]
> **¿Quiere obtener más información?**
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Pasos siguientes

[Fases de incorporación de las ventajas del Centro de FastTrack para EMS](EMS-onboarding-phases.md)
