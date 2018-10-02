---
title: Información general sobre las ventajas del Centro de FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/01/2018
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: ac467db0-3118-41fa-a93d-bb5de1e414d5
description: Con Ventajas del Centro de FastTrack para Office 365, puede trabajar de forma remota con especialistas de FastTrack para dejar el entorno de Office 365 listo para su uso, así como para planear el lanzamiento y el uso en la organización. Para más información sobre la elegibilidad, vea Ventajas del Centro de FastTrack para Office 365.
ms.openlocfilehash: 0ce6c1545af6802e40fbf017bbc09784b4f31a4e
ms.sourcegitcommit: a754d02f1dea1a2147f716a2cbebda7b68141777
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/01/2018
ms.locfileid: "25353687"
---
# <a name="fasttrack-center-benefit-overview"></a>Información general sobre las ventajas del Centro de FastTrack

Con Ventajas del Centro de FastTrack para Office 365, puede trabajar de forma remota con especialistas de FastTrack para dejar el entorno de Office 365 listo para su uso, así como para planear el lanzamiento y el uso en la organización. Para más información sobre la elegibilidad, vea [Ventajas del Centro de FastTrack para Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Tratamos los siguientes temas:
- [Proceso de FastTrack](O365-fasttrack-process.md) 
- [Expectativas del entorno de origen](O365-source-environment-expectations.md)
- [Fases de incorporación y migración](O365-onboarding-and-migration.md)
- [Migración de datos](O365-data-migration.md)
- [Responsabilidades de FastTrack](O365-fasttrack-responsibilities.md)
- [Sus responsabilidades](O365-your-responsibilities.md) 
- [Apéndice A: Migración de IBM Domino a Exchange Online](O365-from-ibm-domino-to-exchange-online.md)
- [Apéndice B: Beneficio adicional del Centro de FastTrack](O365-fasttrack-additional-benefits.md)
- [Apéndice C: Contrato de asociación comercial según las normas HIPAA del Centro de FastTrack](O365-hipaa-business-associate-agreement.md)
- [Apéndice D: Información general de las Ventajas del Centro de FastTrack para Office 365 Administración pública de EE. UU.](US-Gov-appendix-overview.md)
    
El espacio empresarial de Office 365 se crea cuando se completa la incorporación. Los usuarios con licencia pueden acceder a Office 365 mediante una de las siguientes opciones de identidad:
- Identidades de nube con cuentas de Office 365 únicas.
- Identidades sincronizadas con cuentas de Office 365 sincronizadas desde Active Directory local con Azure Active Directory Connect (sincronización de hash de contraseñas y autenticación de paso a través). Están destinadas para clientes con:
  - Un solo entorno de bosque de Active Directory.
  - Una topología compatible de bosques múltiples de Active Directory. Para más información sobre las topologías compatibles, vea [Expectativas del entorno de origen](O365-source-environment-expectations.md).
- Identidades federadas con cuentas de Office 365 que están:
  - Sincronizadas desde Active Directory con la herramienta Azure Active Directory Connect para los clientes con:
      - Una sola configuración de bosque de Active Directory.
      - Un solo bosque de cuentas de Active Directory (también conocido como "bosque de inicio de sesión") y una sola configuración de bosque de recursos de Active Directory.
  - Configuradas con una infraestructura local de Servicios de federación de Active Directory (AD FS) que está:
      - Federado con un rol de AD FS de Windows Server 2012 R2 desde el Active Directory local.
      - Cuando sea necesario, un Windows Server 2012 R2 en adelante el rol Windows Application Proxy (WAP) usado para publicar la infraestructura local AD FS para Internet.
    > [!NOTE]
    > La implementación y configuración de AD FS se realiza usando el [Asistente de configuración de Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) en su entorno local. 
  
- Los usuarios con licencia ahora tienen acceso a los [Servicios y planes elegibles](O365-eligible-services-and-plans.md).
    

 
