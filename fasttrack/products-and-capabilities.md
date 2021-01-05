---
title: Productos y capacidades
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Este tema incluye detalles sobre los escenarios de carga de trabajo compatibles con FastTrack y las expectativas del entorno de origen necesarias antes de que podamos comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que incorpore el entorno de origen a los requisitos mínimos para la incorporación correcta.
ms.openlocfilehash: 5e65d160822ed50840ecc65f484433bf0d485913
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750107"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="19a26-104">Productos y capacidades</span><span class="sxs-lookup"><span data-stu-id="19a26-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="19a26-105">Servicios y escenarios compatibles con FastTrack</span><span class="sxs-lookup"><span data-stu-id="19a26-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="19a26-106">Este tema incluye detalles sobre los escenarios de carga de trabajo compatibles con FastTrack y las expectativas del entorno de origen necesarias antes de que podamos comenzar.</span><span class="sxs-lookup"><span data-stu-id="19a26-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="19a26-107">En función de la configuración actual, trabajamos con usted para crear un plan de corrección que incorpore el entorno de origen a los requisitos mínimos para la incorporación correcta.</span><span class="sxs-lookup"><span data-stu-id="19a26-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="19a26-108">FastTrack proporciona instrucciones para ayudarle primero con las capacidades principales (comunes para todos los servicios en línea de Microsoft) y, a continuación, con la incorporación de cada servicio elegible:</span><span class="sxs-lookup"><span data-stu-id="19a26-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="19a26-109">General</span><span class="sxs-lookup"><span data-stu-id="19a26-109">General</span></span>](#general)
  - [<span data-ttu-id="19a26-110">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="19a26-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="19a26-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="19a26-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="19a26-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="19a26-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="19a26-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="19a26-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="19a26-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="19a26-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="19a26-115">Asesoría de aplicaciones</span><span class="sxs-lookup"><span data-stu-id="19a26-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="19a26-116">El nuevo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="19a26-116">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="19a26-117">Para obtener información sobre las expectativas de entorno de origen para Office 365 Administración Pública, vea [Expectativas de entorno de origen para Office 365 Administración Pública](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="19a26-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="19a26-118">General</span><span class="sxs-lookup"><span data-stu-id="19a26-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="19a26-119"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="19a26-120"><strong>Detalles de la guía de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="19a26-121"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="19a26-122"><strong>Incorporación principal</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="19a26-123">Proporcionamos instrucciones remotas sobre la incorporación principal, que implica el aprovisionamiento de servicios, el inquilino y la integración de identidades.</span><span class="sxs-lookup"><span data-stu-id="19a26-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="19a26-124">También incluye los pasos para ofrecer una base para los servicios de incorporación como Exchange Online, SharePoint Online y Microsoft Teams, incluida una <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">Descripción de la seguridad, la conectividad de red y el cumplimiento normativo</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="19a26-125">La incorporación de uno o más servicios elegibles puede empezar al finalizar la incorporación principal.</span><span class="sxs-lookup"><span data-stu-id="19a26-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="19a26-126"></li>
</ul>  

<strong> Integración de identidades </strong></span><span class="sxs-lookup"><span data-stu-id="19a26-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="19a26-127">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="19a26-128">Preparar las identidades locales de Active Directory para la sincronización a Azure Active Directory (Azure AD), incluida la instalación y la configuración de Azure AD Connect (uno o varios bosques) y las licencias (incluidas las licencias basadas en grupos).</span><span class="sxs-lookup"><span data-stu-id="19a26-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="19a26-129">Crear identidades de nube, incluidas la importación en masa y la concesión de licencias, incluido el uso de licencias basadas en grupos.</span><span class="sxs-lookup"><span data-stu-id="19a26-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="19a26-130">Elegir y habilitar el método de autenticación correcto para el recorrido de la nube, la sincronización de hash de contraseña, la autenticación de paso a través o los servicios de Federación de Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="19a26-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="19a26-131">Habilitación de AD FS para clientes con un único bosque de Active Directory y identidades sincronizados con la herramienta de Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="19a26-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="19a26-132">Esto requiere Windows Server 2012 R2 Active Directory Federation Services 2,0 o superior.</span><span class="sxs-lookup"><span data-stu-id="19a26-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="19a26-133">Migrar la autenticación de AD FS a Azure AD mediante la sincronización de hash de contraseña o la autenticación de paso a través.</span><span class="sxs-lookup"><span data-stu-id="19a26-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="19a26-134">Migrar aplicaciones integradas previamente (como las aplicaciones de software de galería de Azure AD (SaaS) de AD FS a Azure AD para el inicio de sesión único (SSO).</span><span class="sxs-lookup"><span data-stu-id="19a26-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="19a26-135">Habilitar las integraciones de la aplicación SaaS con SSO desde la galería de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="19a26-136">Habilitar el aprovisionamiento automático de usuarios para las aplicaciones SaaS preintegradas, como se muestra en la <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">lista de tutorial de integración de aplicaciones</a> (limitada a las aplicaciones SaaS de galería de Azure ad y al aprovisionamiento saliente únicamente).</span><span class="sxs-lookup"><span data-stu-id="19a26-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="19a26-137"><strong>Habilitación de red </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="19a26-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="19a26-138">Como parte del beneficio de FastTrack, le recomendamos que se asegure de las prácticas recomendadas para conectarse a los servicios en la nube para garantizar los más altos niveles de rendimiento de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="19a26-139"><strong>Bosques de Active</strong> Directory Tienen el nivel funcional de bosque establecido en Windows Server 2003 o superior, con la siguiente configuración de bosque:</span><span class="sxs-lookup"><span data-stu-id="19a26-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-140">Un solo bosque de Active Directory.</span><span class="sxs-lookup"><span data-stu-id="19a26-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="19a26-141">Un solo bosque de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="19a26-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-142">Varios bosques de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="19a26-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-143">Varios bosques de cuentas de Active Directory con uno de los bosques que es un bosque de cuentas de Active Directory centralizado que incluye Exchange o Lync 2010, Lync 2013 o Skype Empresarial.</span><span class="sxs-lookup"><span data-stu-id="19a26-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="19a26-144">Varios bosques de cuentas de Active Directory, cada uno con su propia organización de Exchange.</span><span class="sxs-lookup"><span data-stu-id="19a26-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="19a26-145">Tareas necesarias para la configuración de los inquilinos y la integración con Azure Active Directory, si es necesario.</span><span class="sxs-lookup"><span data-stu-id="19a26-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="19a26-146">
  <strong>Relevancia</strong>  </span><span class="sxs-lookup"><span data-stu-id="19a26-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="19a26-147">Para escenarios de varios bosques de Active Directory, si se implementa Lync 2010, Lync 2013 o Skype empresarial, debe implementarse en el mismo bosque de Active Directory que Exchange.</span><span class="sxs-lookup"><span data-stu-id="19a26-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="19a26-148">Cuando se implementan varios bosques de Active Directory con varias organizaciones de Exchange en una configuración multihíbrida de Exchange, no se admiten los espacios de nombres principales de usuario (UPN) compartidos entre bosques de origen.</span><span class="sxs-lookup"><span data-stu-id="19a26-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="19a26-149">Los espacios de nombres SMTP principales entre las organizaciones de Exchange también deben estar separados.</span><span class="sxs-lookup"><span data-stu-id="19a26-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="19a26-150">Para más información, consulte <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implementaciones híbridas con varios bosques de Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="19a26-151">Para todas las configuraciones de varios bosques, la implementación de los servicios de Federación de Active Directory (AD FS) está fuera del ámbito.</span><span class="sxs-lookup"><span data-stu-id="19a26-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="19a26-152">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="19a26-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-153"><strong>Aplicaciones de Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="19a26-154">Proporcionamos una guía de implementación remota para:</span><span class="sxs-lookup"><span data-stu-id="19a26-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-155">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="19a26-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="19a26-156">Asignar licencias de usuario final y basadas en dispositivos mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="19a26-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="19a26-157">Instalar Aplicaciones de Microsoft 365 desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="19a26-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="19a26-158">Instalar aplicaciones de Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile y PowerPoint Mobile) en los dispositivos iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="19a26-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="19a26-159">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="19a26-160">Selección y configuración de una instalación local o en la nube.</span><span class="sxs-lookup"><span data-stu-id="19a26-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="19a26-161">Creación de la configuración XML de la herramienta de implementación de Office con la herramienta de personalización de Office o XML nativo para configurar el paquete de implementación.</span><span class="sxs-lookup"><span data-stu-id="19a26-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="19a26-162">Implementar mediante Microsoft Endpoint Configuration Manager, incluida la ayuda con la creación del empaquetado de Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="19a26-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="19a26-163">Además, si tiene una macro o un complemento que funcionaba con versiones anteriores de Office y experimenta problemas de compatibilidad, proporcionamos instrucciones para corregir el problema de compatibilidad sin costo adicional a través del programa de aseguramiento de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="19a26-164">Para obtener más información, consulte la parte de <strong>aseguramiento de aplicaciones</strong> de <a href="#windows-10">Windows 10</a> .</span><span class="sxs-lookup"><span data-stu-id="19a26-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="19a26-165">El software de cliente en línea debe tener un nivel mínimo, como se define en los <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-166"><strong>Estado de la red</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="19a26-167">Proporcionamos instrucciones remotas para obtener e interpretar datos clave de conectividad de red desde su entorno que muestre cómo se alinean los sitios de la organización con los <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principios de conectividad de red de</a>Microsoft.</span><span class="sxs-lookup"><span data-stu-id="19a26-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="19a26-168">Esto destaca su puntuación de red que afecta directamente a la velocidad de migración, la experiencia del usuario, el rendimiento del servicio y la confiabilidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="19a26-169">También le guiaremos a través de los pasos de corrección resaltados por estos datos para ayudarle a mejorar la puntuación de la red.</span><span class="sxs-lookup"><span data-stu-id="19a26-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="19a26-170">Acceso al centro de administración de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="19a26-171">Se necesitan versiones actualizadas de las aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="19a26-172">Los servicios de ubicación están habilitados según <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">las recomendaciones de rendimiento de red en el centro de administración de Microsoft 365 (versión preliminar)</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="19a26-173">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="19a26-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="19a26-174"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="19a26-175"><strong>Detalles de la guía de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="19a26-176"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="19a26-177"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="19a26-178">Proporcionamos una orientación remota para proteger sus identidades de nube en los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="19a26-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="19a26-179">

<strong>Infraestructura de base segura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="19a26-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="19a26-180">Configuración y habilitación de la autenticación segura para sus identidades, incluida la protección con Azure multi-factor Authentication (MFA) (solo nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseña de autoservicio (SSPR).</span><span class="sxs-lookup"><span data-stu-id="19a26-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="19a26-181">Para clientes que no son de Azure Premium, se proporciona orientación para proteger las identidades mediante los valores predeterminados de seguridad.</span><span class="sxs-lookup"><span data-stu-id="19a26-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="19a26-182">Para los clientes de Azure AD Premium, se proporciona orientación para proteger las identidades con acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="19a26-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="19a26-183">Detección y bloqueo del uso de contraseñas débiles con la protección con contraseña de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="19a26-184">Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="19a26-185">Habilitación de la detección y corrección basada en riesgos con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="19a26-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="19a26-186">Habilitación de una pantalla de inicio de sesión personalizada, que incluye logotipos, texto e imágenes con personalización de marca.</span><span class="sxs-lookup"><span data-stu-id="19a26-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="19a26-187">Comparta de forma segura aplicaciones y servicios con usuarios invitados mediante la B2B de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="19a26-188">Administración del acceso para los administradores de Office 365 mediante funciones administrativas integradas de control de acceso basado en roles (RBAC) y para reducir el número de cuentas de administrador con privilegios.</span><span class="sxs-lookup"><span data-stu-id="19a26-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="19a26-189">Configurar una Unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="19a26-190">Configurando Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="19a26-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="19a26-191">
  
<strong>Supervisión y generación de informes</strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-192">Habilitación de la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="19a26-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="19a26-193">
  
<strong>Empresarial</strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-194">Administrar su ciclo de vida de identidad y acceso de Azure AD a escala con la administración de derechos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="19a26-195">Administrar la pertenencia a grupos de Azure AD, el acceso de la aplicación empresarial y las asignaciones de roles con las revisiones de acceso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-196">Revisión de los términos de uso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-197">Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="19a26-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="19a26-198">
  
<strong>Automatización y eficiencia </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-199">Habilitación de Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="19a26-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="19a26-200">Permitir a los usuarios crear y administrar sus propios grupos de seguridad en la nube u Office 365 con la administración de grupos de autoservicio de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-201">Administración del acceso delegado a las aplicaciones empresariales con la administración de grupos delegados de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-202">Habilitación de grupos dinámicos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="19a26-203">Organizar aplicaciones en el portal de mis aplicaciones mediante colecciones</span><span class="sxs-lookup"><span data-stu-id="19a26-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="19a26-204">La implementación local de Active Directory y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con Azure AD y las características de Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="19a26-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="19a26-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="19a26-206">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-207">Activar y configurar el inquilino.</span><span class="sxs-lookup"><span data-stu-id="19a26-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="19a26-208">Crear y configurar etiquetas y directivas.</span><span class="sxs-lookup"><span data-stu-id="19a26-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-209">Aplicar la protección de la información a documentos.</span><span class="sxs-lookup"><span data-stu-id="19a26-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="19a26-210">Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="19a26-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="19a26-211">Detectar y etiquetar archivos en reposo con el escáner de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="19a26-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="19a26-212">Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="19a26-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="19a26-213">También le ofrecemos instrucciones para aplicar la protección con Microsoft Azure Rights Management Services (Azure RMS), el cifrado de mensajes de Office 365 (OME) y la prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="19a26-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="19a26-214">Las responsabilidades de requisitos previos del cliente incluyen:</span><span class="sxs-lookup"><span data-stu-id="19a26-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-215">Una lista de ubicaciones de recursos compartidos de archivos que se examinarán.</span><span class="sxs-lookup"><span data-stu-id="19a26-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="19a26-216">Una taxonomía de clasificación aprobada.</span><span class="sxs-lookup"><span data-stu-id="19a26-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="19a26-217">Comprensión de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.</span><span class="sxs-lookup"><span data-stu-id="19a26-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-218">Una cuenta de servicio creada para su Active Directory local que se haya sincronizado con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="19a26-219">Etiquetas configuradas para clasificación y protección.</span><span class="sxs-lookup"><span data-stu-id="19a26-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="19a26-220">Todos los requisitos previos para el analizador de Azure Information Protection están en su ubicación.</span><span class="sxs-lookup"><span data-stu-id="19a26-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="19a26-221">Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">requisitos previos para instalar e implementar el escáner de etiquetación unificada de Azure Information Protection</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="19a26-222">Asegúrese de que los dispositivos de usuario ejecutan un sistema operativo compatible y tienen instalados los requisitos previos necesarios.</span><span class="sxs-lookup"><span data-stu-id="19a26-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="19a26-223">Consulte lo siguiente para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="19a26-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="19a26-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetación unificada de Azure Information Protection para los usuarios</a>   </span><span class="sxs-lookup"><span data-stu-id="19a26-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="19a26-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="19a26-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="19a26-226">Instalación y configuración del conector y los servidores de Azure RMS, incluido el conector de Active Directory RMS (AD RMS) para la compatibilidad con entornos híbridos.</span><span class="sxs-lookup"><span data-stu-id="19a26-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="19a26-227">Instalación y configuración de traer su propia clave (BYOK), cifrado de doble clave (DKE) (solo cliente de etiquetado unificado) o mantenga su propia clave (HYOK) (solo cliente clásico) en caso de que necesite una de estas opciones para la implementación.</span><span class="sxs-lookup"><span data-stu-id="19a26-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="19a26-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="19a26-229">Microsoft 365 defender es un conjunto unificado de defensa de la empresa, antes y después de la violación, que coordina la detección, prevención, investigación y respuesta entre los puntos de conexión, las identidades, el correo electrónico y las aplicaciones de forma nativa para proporcionar protección integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="19a26-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="19a26-230">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="19a26-231">Proporciona información general sobre el centro de seguridad de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="19a26-232">Revisión de incidencias de productos cruzados, que incluyen centrarse en las tareas críticas al garantizar el ámbito completo de los ataques, los activos afectados y las acciones de corrección automatizadas que se agrupan juntos.</span><span class="sxs-lookup"><span data-stu-id="19a26-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="19a26-233">Demostrar cómo Microsoft 365 defender puede organizar la investigación de activos, usuarios, dispositivos y buzones de correo que puedan haberse puesto en peligro mediante la Autorrecuperación automática.</span><span class="sxs-lookup"><span data-stu-id="19a26-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="19a26-234">Explicación y proporciona ejemplos de cómo los clientes pueden buscar de forma proactiva los intentos de intrusión y la actividad de infracciones que afectan a su correo electrónico, datos, dispositivos y cuentas en varios conjuntos de datos.</span><span class="sxs-lookup"><span data-stu-id="19a26-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="19a26-235">Mostrar a los clientes cómo pueden revisar y mejorar su postura de seguridad de forma holística mediante la calificación segura de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="19a26-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="19a26-236"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="19a26-237">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="19a26-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="19a26-238">Administración continuada, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="19a26-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="19a26-239">Guía de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="19a26-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="19a26-240">Cómo corregir o interpretar los distintos tipos de alertas y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="19a26-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="19a26-241">Cómo investigar un usuario, equipo, ruta de movimiento lateral o entidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="19a26-242">Caza de amenazas personalizadas.</span><span class="sxs-lookup"><span data-stu-id="19a26-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="19a26-243">Información de seguridad y administración de eventos (SIEM) o integración de la API.</span><span class="sxs-lookup"><span data-stu-id="19a26-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="19a26-245">Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una buena visibilidad, control sobre los recorridos de datos y análisis sofisticados para identificar y combatir las amenazas cibernéticos en todos los servicios en la nube de Microsoft y de terceros.</span><span class="sxs-lookup"><span data-stu-id="19a26-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="19a26-246">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-247">Configuración del portal, que incluye:</span><span class="sxs-lookup"><span data-stu-id="19a26-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="19a26-248">Importación de grupos de usuarios.</span><span class="sxs-lookup"><span data-stu-id="19a26-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="19a26-249">Administración de la configuración y el acceso de administrador.</span><span class="sxs-lookup"><span data-stu-id="19a26-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="19a26-250">Ámbito de la implementación para seleccionar determinados grupos de usuarios que se van a supervisar o excluir de la supervisión.</span><span class="sxs-lookup"><span data-stu-id="19a26-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="19a26-251">Configurar intervalos IP y etiquetas.</span><span class="sxs-lookup"><span data-stu-id="19a26-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="19a26-252">Personalización de la experiencia del usuario final con su logotipo y mensajería personalizada.</span><span class="sxs-lookup"><span data-stu-id="19a26-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="19a26-253">Configuración de detección en la nube para que le proporcione sombreado mediante:</span><span class="sxs-lookup"><span data-stu-id="19a26-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="19a26-254">Microsoft defender para puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="19a26-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="19a26-255">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="19a26-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="19a26-256">iboss.</span><span class="sxs-lookup"><span data-stu-id="19a26-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="19a26-257">Conexión de <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">aplicaciones destacadas</a> con conectores de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="19a26-258">Configuración del control de aplicaciones de acceso condicional en los portales de acceso condicional y de aplicación de nube para aplicar controles de sesión en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="19a26-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="19a26-259">Implementación de los paneles Cloud App Security y Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="19a26-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="19a26-260">Personalización de los resultados de riesgos de aplicaciones en función de las prioridades de su organización.</span><span class="sxs-lookup"><span data-stu-id="19a26-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="19a26-261">Crear etiquetas y categorías de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="19a26-262">Autorizar y no autorizar aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="19a26-263">Uso de los registros de actividad y archivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="19a26-264">Administración de aplicaciones de OAuth.</span><span class="sxs-lookup"><span data-stu-id="19a26-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="19a26-265">Descripción de la correlación de incidentes en el portal de Microsoft 365 defender.</span><span class="sxs-lookup"><span data-stu-id="19a26-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="19a26-266">Proporciona asistencia de configuración con los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 principales casos de uso para CASBs</a> (incluida la creación o actualización de hasta seis (6) directivas) excepto:</span><span class="sxs-lookup"><span data-stu-id="19a26-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="19a26-267">Auditar la configuración de los entornos de Internet como servicio (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="19a26-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="19a26-268">Supervisar las actividades de los usuarios para protegerse de las amenazas en los entornos de IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="19a26-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="19a26-269"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="19a26-270">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="19a26-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="19a26-271">Administración continuada, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="19a26-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="19a26-272">Configuración de la infraestructura, instalación o implementación de las cargas de registro automáticas para los informes continuos mediante el acoplador o un recopilador de registros.</span><span class="sxs-lookup"><span data-stu-id="19a26-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="19a26-273">Vea los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 primeros casos de uso para CASBs</a> para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="19a26-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="19a26-274">Creación de un informe de instantáneas de detección en la nube.</span><span class="sxs-lookup"><span data-stu-id="19a26-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="19a26-275">Bloqueo del uso de la aplicación mediante bloques de scripts.</span><span class="sxs-lookup"><span data-stu-id="19a26-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="19a26-276">Conexión de aplicaciones personalizadas.</span><span class="sxs-lookup"><span data-stu-id="19a26-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="19a26-277">Integración con proveedores de identidades de terceros (ISP) y proveedores de prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="19a26-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="19a26-278">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="19a26-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="19a26-279">Investigación y corrección automáticas, incluidas las guías de Microsoft Power automatization.</span><span class="sxs-lookup"><span data-stu-id="19a26-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="19a26-280">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="19a26-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="19a26-281">Implementación de la detección de aplicaciones en la nube como prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="19a26-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="19a26-282"><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="19a26-283">La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.</span><span class="sxs-lookup"><span data-stu-id="19a26-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="19a26-284">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-285">Implementación de las tecnologías para proteger los extremos.</span><span class="sxs-lookup"><span data-stu-id="19a26-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="19a26-286">Configuración de Endpoint Protection y los perfiles de restricción de dispositivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="19a26-287">Evaluación de la versión del sistema operativo y la administración de dispositivos (incluidos Intune, el administrador de configuración de Microsoft Endpoint, los objetos de directiva de grupo (GPO) y las configuraciones de terceros), así como el estado de los servicios de AV de Windows Defender u otro software de seguridad de extremos.</span><span class="sxs-lookup"><span data-stu-id="19a26-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="19a26-288">Evaluar el estado de los servicios de Windows AV o de otro software de seguridad de extremo.</span><span class="sxs-lookup"><span data-stu-id="19a26-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="19a26-289">Evaluar los servidores proxy y los firewalls restringir el tráfico de red.</span><span class="sxs-lookup"><span data-stu-id="19a26-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="19a26-290">Habilitar el servicio ATP de Microsoft defender mediante la explicación de cómo implementar un perfil de agente ATP con un punto de conexión incorporado.</span><span class="sxs-lookup"><span data-stu-id="19a26-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="19a26-291">Guía de implementación, asistencia para la configuración y educación en:</span><span class="sxs-lookup"><span data-stu-id="19a26-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-292">Administración de amenazas y vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="19a26-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-293">Reducción de la superficie de ataque.</span><span class="sxs-lookup"><span data-stu-id="19a26-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-294">Protección de nueva generación.</span><span class="sxs-lookup"><span data-stu-id="19a26-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-295">Detección y respuesta de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="19a26-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-296">Investigación y corrección automatizadas.</span><span class="sxs-lookup"><span data-stu-id="19a26-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-297">Puntuación de seguridad.</span><span class="sxs-lookup"><span data-stu-id="19a26-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-298">Revisión de simulaciones y tutoriales (como escenarios de prácticas, malware falsificado e investigaciones automatizadas).</span><span class="sxs-lookup"><span data-stu-id="19a26-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="19a26-299">Información general sobre las características de informes y de análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="19a26-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="19a26-300">Integrar Protección contra amenazas avanzadas de Office 365 con Protección contra amenazas avanzada de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="19a26-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="19a26-301">Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="19a26-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="19a26-302">Los siguientes sistemas operativos:</span><span class="sxs-lookup"><span data-stu-id="19a26-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-303">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-304">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="19a26-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-305">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="19a26-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-306">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="19a26-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-307">Canal de Semi-Annual de Windows Server (SAC) versión 1803.</span><span class="sxs-lookup"><span data-stu-id="19a26-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-308">macOS versiones 10,13, 10,14 y 10,15.</span><span class="sxs-lookup"><span data-stu-id="19a26-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="19a26-309">
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse con la versión más reciente del administrador de configuración de System Center 2012 (versiones 1012 R2, 1511 o 1602) o el administrador de configuración de Microsoft Endpoint (versión 2002 o posterior).</span><span class="sxs-lookup"><span data-stu-id="19a26-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="19a26-310"></li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="19a26-311">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="19a26-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="19a26-312">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="19a26-313">Administración continua y respuesta ante amenazas.</span><span class="sxs-lookup"><span data-stu-id="19a26-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="19a26-314">Incorporación o configuración para los siguientes agentes de Protección contra amenazas avanzada de Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="19a26-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-315">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="19a26-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-316">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="19a26-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-317">Linux.</span><span class="sxs-lookup"><span data-stu-id="19a26-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-318">Dispositivos móviles (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="19a26-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-319">Incorporación y configuración del servidor:</span><span class="sxs-lookup"><span data-stu-id="19a26-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-320">Configuración de un servidor proxy para las comunicaciones sin conexión.</span><span class="sxs-lookup"><span data-stu-id="19a26-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-321">Configuración de paquetes de implementación de Configuration Manager en instancias y versiones de administrador de configuración de nivel inferior.</span><span class="sxs-lookup"><span data-stu-id="19a26-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-322">Servidores de incorporación a Azure Security Center.</span><span class="sxs-lookup"><span data-stu-id="19a26-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-323">Servidores no administrados por Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="19a26-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-324">incorporación y configuración de macOS:</span><span class="sxs-lookup"><span data-stu-id="19a26-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-325">Implementación manual basada en la Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-326">Implementación basada en JAMF.</span><span class="sxs-lookup"><span data-stu-id="19a26-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="19a26-327">Otra implementación basada en producto de administración de dispositivos móviles (MDM).</span><span class="sxs-lookup"><span data-stu-id="19a26-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-328">Implementación manual.</span><span class="sxs-lookup"><span data-stu-id="19a26-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-329">Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:</span><span class="sxs-lookup"><span data-stu-id="19a26-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-330">Aislamiento basado en hardware.</span><span class="sxs-lookup"><span data-stu-id="19a26-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-331">Control de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-332">Protección contra vulnerabilidades de seguridad.</span><span class="sxs-lookup"><span data-stu-id="19a26-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-333">Firewall de red.</span><span class="sxs-lookup"><span data-stu-id="19a26-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-334">Inscripción o configuración de Expertos en amenazas de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="19a26-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="19a26-335">Configuración o formación que revisan la API o la información de seguridad y las conexiones de administración de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="19a26-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="19a26-336">Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="19a26-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="19a26-337">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="19a26-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="19a26-338">Formación o orientación sobre el uso o la creación de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="19a26-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="19a26-339">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="19a26-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="19a26-340"><strong>Microsoft defender para identidad </strong></span><span class="sxs-lookup"><span data-stu-id="19a26-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="19a26-341">Microsoft Defender for Identity es una solución de seguridad basada en la nube que aprovecha las señales locales de Active Directory para identificar, detectar e investigar las amenazas avanzadas, las identidades vulnerables y las acciones internas malintencionadas dirigidas a su organización.</span><span class="sxs-lookup"><span data-stu-id="19a26-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="19a26-342">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="19a26-343">Crear la instancia de defender para Identity.</span><span class="sxs-lookup"><span data-stu-id="19a26-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="19a26-344">Conectar defender para identidades a Active Directory.</span><span class="sxs-lookup"><span data-stu-id="19a26-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="19a26-345">Evaluar la preparación del entorno para implementar defender para el sensor de identidad en los controladores de dominio, incluidos:</span><span class="sxs-lookup"><span data-stu-id="19a26-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="19a26-346">Ejecutar la herramienta de Sizing para planear la capacidad de los recursos.</span><span class="sxs-lookup"><span data-stu-id="19a26-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="19a26-347">Ejecutar la herramienta de auditoría para evaluar la compatibilidad de los controladores de dominio con el sensor.</span><span class="sxs-lookup"><span data-stu-id="19a26-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="19a26-348">Implementar el sensor para capturar y analizar el tráfico de red y los eventos de Windows directamente desde los controladores de dominio, entre los que se incluyen:</span><span class="sxs-lookup"><span data-stu-id="19a26-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="19a26-349">Descargar el paquete del sensor.</span><span class="sxs-lookup"><span data-stu-id="19a26-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="19a26-350">Configuración del sensor.</span><span class="sxs-lookup"><span data-stu-id="19a26-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="19a26-351">Instalar el sensor en el controlador de dominio silenciosamente.</span><span class="sxs-lookup"><span data-stu-id="19a26-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="19a26-352">Implementación del sensor en el entorno de varios bosques.</span><span class="sxs-lookup"><span data-stu-id="19a26-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="19a26-353">Integración de defender para identidad con Microsoft Cloud App Security (no se requiere licencia de Cloud App Security).</span><span class="sxs-lookup"><span data-stu-id="19a26-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="19a26-354">Proporciona instrucciones de implementación, asistencia para la configuración y educación sobre:</span><span class="sxs-lookup"><span data-stu-id="19a26-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="19a26-355">Optimización del entorno para reducir el "ruido".</span><span class="sxs-lookup"><span data-stu-id="19a26-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="19a26-356">Descripción del informe de evaluación de postura de seguridad de identidades.</span><span class="sxs-lookup"><span data-stu-id="19a26-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="19a26-357">Descripción de la puntuación de prioridad de la investigación del usuario y el informe de clasificación de la investigación del usuario.</span><span class="sxs-lookup"><span data-stu-id="19a26-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="19a26-358">Información sobre el informe de usuarios inactivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="19a26-359">Proporciona opciones de corrección en una cuenta comprometida.</span><span class="sxs-lookup"><span data-stu-id="19a26-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="19a26-360">Facilitar la migración de Advanced Threat Analytics (ATA) a defender para Identity.</span><span class="sxs-lookup"><span data-stu-id="19a26-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="19a26-361"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="19a26-362">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="19a26-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="19a26-363">Administración continuada, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="19a26-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="19a26-364">Implementación de defender para el sensor de identidad, que incluye:</span><span class="sxs-lookup"><span data-stu-id="19a26-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="19a26-365">Planificación manual de la capacidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="19a26-366">Implementar el sensor en una capacidad independiente.</span><span class="sxs-lookup"><span data-stu-id="19a26-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="19a26-367">Implementación del sensor con un adaptador de formación de equipos de tarjeta de interfaz de red (NIC).</span><span class="sxs-lookup"><span data-stu-id="19a26-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="19a26-368">Implementación del sensor mediante una herramienta de terceros.</span><span class="sxs-lookup"><span data-stu-id="19a26-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="19a26-369">Conexión a defender para el servicio de nube de identidad a través de una conexión de proxy Web.</span><span class="sxs-lookup"><span data-stu-id="19a26-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="19a26-370">Creación y administración de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="19a26-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="19a26-371">Guía de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="19a26-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="19a26-372">Corrección o interpretación de varios tipos de alertas y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="19a26-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="19a26-373">Investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="19a26-374">Amenaza o caza avanzada.</span><span class="sxs-lookup"><span data-stu-id="19a26-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="19a26-375">Respuesta de incidente.</span><span class="sxs-lookup"><span data-stu-id="19a26-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="19a26-376">Proporciona un tutorial del laboratorio de alertas de seguridad para defender para Identity.</span><span class="sxs-lookup"><span data-stu-id="19a26-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="19a26-377">Notificación cuando defender para identidad detecta actividades sospechosas mediante el envío de alertas de seguridad al servidor de syslog a través de un sensor denominado.</span><span class="sxs-lookup"><span data-stu-id="19a26-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="19a26-378">Configurar defender para identidad para realizar consultas mediante el protocolo remoto del administrador de cuentas de seguridad (SAMR) para identificar a los administradores locales en equipos específicos.</span><span class="sxs-lookup"><span data-stu-id="19a26-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="19a26-379">Configurar soluciones de VPN para agregar información desde la conexión VPN a la página de Perfil de un usuario.</span><span class="sxs-lookup"><span data-stu-id="19a26-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="19a26-380">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="19a26-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="19a26-381">Implementación de defender para sensores de identidad como prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="19a26-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="19a26-382">Active Directory implementado.</span><span class="sxs-lookup"><span data-stu-id="19a26-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="19a26-383">Los controladores de dominio que pretende instalar defender para los sensores de identidades tienen conectividad a Internet con el servicio de defender para la nube de identidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="19a26-384">El firewall y el proxy deben estar abiertos para comunicarse con el defensor para el servicio de nube de identidad (\*. atp.azure.com puerto 443 debe estar abierto).</span><span class="sxs-lookup"><span data-stu-id="19a26-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="19a26-385">Controladores de dominio que se ejecutan en una de las siguientes opciones:</span><span class="sxs-lookup"><span data-stu-id="19a26-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="19a26-386">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="19a26-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="19a26-387">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="19a26-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="19a26-388">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="19a26-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="19a26-389">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="19a26-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="19a26-390">Windows Server 2019 con KB4487044 (compilación de SO 17763,316).</span><span class="sxs-lookup"><span data-stu-id="19a26-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="19a26-391"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="19a26-392">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-393">Etiquetas y directivas de retención</span><span class="sxs-lookup"><span data-stu-id="19a26-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-394">Administración de registros</span><span class="sxs-lookup"><span data-stu-id="19a26-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-395">Directivas de eliminación</span><span class="sxs-lookup"><span data-stu-id="19a26-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-396">Cumplimiento de comunicaciones</span><span class="sxs-lookup"><span data-stu-id="19a26-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="19a26-397">Administración de riesgos internos.</span><span class="sxs-lookup"><span data-stu-id="19a26-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-398">eDiscovery avanzado</span><span class="sxs-lookup"><span data-stu-id="19a26-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="19a26-399">

  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="19a26-400">Desarrollo de un plan de archivos de administración de registros.</span><span class="sxs-lookup"><span data-stu-id="19a26-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="19a26-401">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="19a26-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="19a26-402">Barreras de la información.</span><span class="sxs-lookup"><span data-stu-id="19a26-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="19a26-403">Administración del acceso privilegiado.</span><span class="sxs-lookup"><span data-stu-id="19a26-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="19a26-404">Desarrollo de la arquitectura de la información en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="19a26-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="19a26-405">Secuencias de comandos y códigos personalizados.</span><span class="sxs-lookup"><span data-stu-id="19a26-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="19a26-406">Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="19a26-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-407"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="19a26-408">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-409">Clasificación de los datos</span><span class="sxs-lookup"><span data-stu-id="19a26-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="19a26-410">Tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="19a26-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="19a26-411">Crear etiquetas de confidencialidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="19a26-412">Aplicar etiquetas de confidencialidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="19a26-413">Etiquetado unificado</span><span class="sxs-lookup"><span data-stu-id="19a26-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="19a26-414">Clasificadores que se pueden entrenar.</span><span class="sxs-lookup"><span data-stu-id="19a26-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="19a26-415">Conocer sus datos con el explorador de contenido y el explorador de actividades.</span><span class="sxs-lookup"><span data-stu-id="19a26-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="19a26-416">Publicar etiquetas mediante las directivas (manual y automático).</span><span class="sxs-lookup"><span data-stu-id="19a26-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="19a26-417">Crear directivas de protección de pérdida de datos (DLP) de los chats y canales de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="19a26-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="19a26-418">Crear directivas de DLP de punto de conexión para dispositivos con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="19a26-419">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="19a26-420">Clave de cliente.</span><span class="sxs-lookup"><span data-stu-id="19a26-420">Customer key.</span></span></li>
<li><span data-ttu-id="19a26-421">Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="19a26-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="19a26-422">Creación o modificación de diccionarios de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="19a26-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="19a26-423">Secuencias de comandos y códigos personalizados.</span><span class="sxs-lookup"><span data-stu-id="19a26-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="19a26-424">
<strong>Nota:</strong> Para obtener más información, vea <strong> Azure Information Protection </strong> en <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="19a26-425">Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="19a26-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="19a26-427">Proporcionamos instrucciones remotas para prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="19a26-428">Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles.</span><span class="sxs-lookup"><span data-stu-id="19a26-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="19a26-429">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="19a26-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-430">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="19a26-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="19a26-431">Configurar las identidades que se usarán en Intune aprovechando las identidades locales de Active Directory o de la nube (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="19a26-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="19a26-432">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="19a26-433">Configurar la autoridad de MDM, en función de las necesidades de administración, entre las que se incluyen:</span><span class="sxs-lookup"><span data-stu-id="19a26-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-434">Establecer Intune como entidad MDM cuando Intune es la única solución MDM.</span><span class="sxs-lookup"><span data-stu-id="19a26-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-435">Proporcionar instrucciones de MDM para:</span><span class="sxs-lookup"><span data-stu-id="19a26-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-436">Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.</span><span class="sxs-lookup"><span data-stu-id="19a26-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-437">Configurar servicios y directivas de administración de MDM como:</span><span class="sxs-lookup"><span data-stu-id="19a26-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-438">Implementación de aplicaciones para cada plataforma admitida a través de vínculos Web o vínculos profundos.</span><span class="sxs-lookup"><span data-stu-id="19a26-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="19a26-439">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="19a26-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-440">Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tiene una entidad de certificación, una red inalámbrica o una infraestructura de VPN en su organización.</span><span class="sxs-lookup"><span data-stu-id="19a26-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="19a26-441">Conexión al almacén de datos de Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="19a26-442">Integrar Intune con:</span><span class="sxs-lookup"><span data-stu-id="19a26-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-443">Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="19a26-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="19a26-444">Soluciones de asociados de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).</span><span class="sxs-lookup"><span data-stu-id="19a26-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="19a26-445">Una solución de administración de gastos de telecomunicaciones (es necesaria una suscripción a la solución de administración de gastos de telecomunicaciones).</span><span class="sxs-lookup"><span data-stu-id="19a26-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="19a26-446">ATP de Microsoft defender (se necesitan licencias de Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="19a26-446">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-447">Inscribir dispositivos de cada plataforma compatible en Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-447">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="19a26-448">Proporciona instrucciones de protección de aplicaciones en:</span><span class="sxs-lookup"><span data-stu-id="19a26-448">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-449">Configurar directivas de protección de aplicaciones para cada plataforma compatible.</span><span class="sxs-lookup"><span data-stu-id="19a26-449">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="19a26-450">Configuración de directivas de acceso condicional para aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="19a26-450">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="19a26-451">Dirigirse a los grupos de usuarios apropiados con las directivas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="19a26-451">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-452">Uso de informes de uso de aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="19a26-452">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-453">Proporciona instrucciones de migración desde la administración de equipos heredados a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="19a26-453">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="19a26-454">
  <strong>Nota</strong>: la administración de equipos heredados ya no se admite desde el 15 de octubre de 2020 en adelante.</span><span class="sxs-lookup"><span data-stu-id="19a26-454">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="19a26-455"></li>
</ul>
  
<strong>Conexión a la nube</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-455"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="19a26-456">Le guiamos a través de la preparación para hospedar en la nube entornos de Configuration Manager existentes con Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-456">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="19a26-457">Los pasos detallados dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="19a26-457">The exact steps depend on your source environment.</span></span> <span data-ttu-id="19a26-458">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="19a26-458">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="19a26-459">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="19a26-459">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="19a26-460">Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="19a26-460">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="19a26-461">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-461">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="19a26-462">Proporciona instrucciones sobre cómo configurar la Unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-462">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="19a26-463">Proporciona instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.</span><span class="sxs-lookup"><span data-stu-id="19a26-463">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="19a26-464">Proporcionar instrucciones sobre cómo configurar Cloud Management Gateway.</span><span class="sxs-lookup"><span data-stu-id="19a26-464">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="19a26-465">Configurar cargas de trabajo compatibles que quiera cambiar a Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-465">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="19a26-466">Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-466">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="19a26-467"><strong>Implementar Outlook Mobile para iOS y Android de manera segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook Mobile para iOS y Android de forma segura en su organización para asegurarse de que los usuarios tengan instaladas todas las aplicaciones necesarias.</span><span class="sxs-lookup"><span data-stu-id="19a26-467"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="19a26-468">Los pasos para implementar de forma segura Outlook Mobile para iOS y Android con Intune dependen de su entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="19a26-468">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="19a26-469">Puede incluir:</span><span class="sxs-lookup"><span data-stu-id="19a26-469">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-470">Descargar las aplicaciones Outlook para iOS y Android, autenticador de Microsoft y portal de empresa de Intune a través de la App Store de Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="19a26-470">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="19a26-471">Proporciona instrucciones para configurar:</span><span class="sxs-lookup"><span data-stu-id="19a26-471">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-472">La implementación de las aplicaciones de Outlook para iOS y Android, el autenticador de Microsoft y el portal de empresa de Intune con Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-472">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="19a26-473">Directivas de protección de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-473">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-474">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="19a26-474">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-475">Directivas de configuración de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="19a26-475">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="19a26-476"><strong>Nota</strong>: FastTrack no es compatible con la protección de Outlook para iOS y Android con las directivas de buzón de correo de dispositivo móvil de Exchange.</span><span class="sxs-lookup"><span data-stu-id="19a26-476"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="19a26-477">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="19a26-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="19a26-478">Los administradores de TI deben contar con una entidad de certificación, una red inalámbrica y unas infraestructuras VPN existentes en sus entornos de producción al planear la implementación de perfiles de red inalámbrica y VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-478">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="19a26-479"><strong>Nota</strong>: el beneficio del servicio FastTrack no incluye asistencia para configurar o configurar entidades de certificación, redes inalámbricas, infraestructuras VPN o certificados push de Apple para Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-479"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="19a26-480"><strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube.</span><span class="sxs-lookup"><span data-stu-id="19a26-480"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="19a26-481">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="19a26-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="19a26-482"><strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-482"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="19a26-483"><strong>Nota</strong>: proporcionamos asistencia sobre la integración de Intune con Microsoft defender ATP y la creación de directivas de cumplimiento de dispositivos basadas en su evaluación de nivel de riesgo de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-483"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="19a26-484">No proporcionamos asistencia sobre la compra, concesión de licencias o activación.</span><span class="sxs-lookup"><span data-stu-id="19a26-484">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="19a26-485">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="19a26-485">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="19a26-486"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-486"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="19a26-487">Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="19a26-487">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="19a26-488"><strong>Protección contra amenazas avanzada de Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-488"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="19a26-489">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-489">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-490">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="19a26-490">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="19a26-491">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="19a26-491">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="19a26-492">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="19a26-492">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="19a26-493">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="19a26-493">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="19a26-494">Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="19a26-494">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="19a26-495">Office 365</span><span class="sxs-lookup"><span data-stu-id="19a26-495">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="19a26-496"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-496"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="19a26-497"><strong>Detalles de la guía de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-497"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="19a26-498"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-498"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="19a26-499"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-499"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="19a26-500">Para Exchange Online, le guiaremos a través del proceso para preparar la organización para usar el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="19a26-500">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="19a26-501">Los pasos exactos dependen de su entorno de origen y sus planes de migración de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="19a26-501">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="19a26-502">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-502">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-503">Configuración de las características de Exchange Online Protection (EOP) para todos los dominios habilitados para correo que se han validado en Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-503">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="19a26-504">Apuntar los registros de intercambio de correo (MX) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-504">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="19a26-505">Configurar la característica ATP de Office 365 si forma parte de su servicio de suscripción.</span><span class="sxs-lookup"><span data-stu-id="19a26-505">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="19a26-506">Para obtener más información, consulte la parte de la <strong>protección contra amenazas avanzada de Office 365</strong> de esta tabla.</span><span class="sxs-lookup"><span data-stu-id="19a26-506">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="19a26-p128">Configuración de la característica de prevención de pérdida de datos (DLP) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-p128">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="19a26-p129">Configuración del cifrado de mensajes de Office 365 (OME) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-p129">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="19a26-511">
  <strong>Nota:</strong> El servicio de replicación de buzones (MRS) intenta migrar los mensajes de correo electrónico de Information Rights Management (IRM) desde el buzón de correo local al buzón de correo de Exchange Online correspondiente.</span><span class="sxs-lookup"><span data-stu-id="19a26-511">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="19a26-512">La capacidad de leer el contenido protegido posterior a la migración dependerá de la asignación de clientes y la copia de las plantillas de Active Directory Rights Management Services (AD RMS) en el servicio Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="19a26-512">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="19a26-513">Configurar puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="19a26-513">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="19a26-514">Configuración de DNS, incluida la detección automática necesaria, el marco de directivas de remitente (SPF), el correo identificado por DomainKeys (DKIM), la autenticación de mensajes basada en dominio, la notificación y el cumplimiento (DMARC) y los registros MX (según sea necesario).</span><span class="sxs-lookup"><span data-stu-id="19a26-514">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="19a26-515">Configuración del flujo de correo electrónico entre su entorno de mensajería de origen y Exchange Online (si procede).</span><span class="sxs-lookup"><span data-stu-id="19a26-515">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="19a26-516">Operación de migración de correo desde el entorno de mensajería de origen a Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-516">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="19a26-517">Configuración de clientes de buzón (Outlook para Windows, Outlook en la web y Outlook para iOS y Android).</span><span class="sxs-lookup"><span data-stu-id="19a26-517">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="19a26-518">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="19a26-518">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="19a26-519">Para obtener información sobre cómo usar el beneficio de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">migración de datos</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-519">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="19a26-520">El entorno de origen debe tener uno de los siguientes niveles mínimos:</span><span class="sxs-lookup"><span data-stu-id="19a26-520">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-521">Una o varias organizaciones de Exchange a partir de Exchange Server 2003.</span><span class="sxs-lookup"><span data-stu-id="19a26-521">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="19a26-522">Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).</span><span class="sxs-lookup"><span data-stu-id="19a26-522">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="19a26-523">Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="19a26-523">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="19a26-524">Para obtener información sobre las funciones multigeográficas, vea <a href="https://go.microsoft.com/fwlink/?linkid=872776">multi-Geogeográfico Capabilities in Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-524">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="19a26-525">El software cliente en línea, como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, el cliente de sincronización de OneDrive para la empresa, Power BI Desktop y Skype empresarial deben tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-525">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-526"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-526"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="19a26-527">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-527">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-528">Etiquetas y directivas de retención</span><span class="sxs-lookup"><span data-stu-id="19a26-528">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-529">Administración de registros</span><span class="sxs-lookup"><span data-stu-id="19a26-529">Records management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-530">Directivas de eliminación</span><span class="sxs-lookup"><span data-stu-id="19a26-530">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-531">Cumplimiento de comunicaciones</span><span class="sxs-lookup"><span data-stu-id="19a26-531">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="19a26-532">Administración de riesgos internos.</span><span class="sxs-lookup"><span data-stu-id="19a26-532">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-533">eDiscovery avanzado</span><span class="sxs-lookup"><span data-stu-id="19a26-533">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="19a26-534">

  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-534">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="19a26-535">Desarrollo de un plan de archivos de administración de registros.</span><span class="sxs-lookup"><span data-stu-id="19a26-535">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="19a26-536">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="19a26-536">Data connectors.</span></span></li>
<li> <span data-ttu-id="19a26-537">Barreras de la información.</span><span class="sxs-lookup"><span data-stu-id="19a26-537">Information barriers.</span></span></li>
<li> <span data-ttu-id="19a26-538">Administración del acceso privilegiado.</span><span class="sxs-lookup"><span data-stu-id="19a26-538">Privileged access management.</span></span></li>
<li> <span data-ttu-id="19a26-539">Desarrollo de la arquitectura de la información en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="19a26-539">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="19a26-540">Secuencias de comandos y códigos personalizados.</span><span class="sxs-lookup"><span data-stu-id="19a26-540">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="19a26-541">Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="19a26-541">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-542"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-542"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="19a26-543">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-543">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-544">Clasificación de los datos</span><span class="sxs-lookup"><span data-stu-id="19a26-544">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="19a26-545">Tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="19a26-545">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="19a26-546">Crear etiquetas de confidencialidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-546">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="19a26-547">Aplicar etiquetas de confidencialidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-547">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="19a26-548">Etiquetado unificado</span><span class="sxs-lookup"><span data-stu-id="19a26-548">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="19a26-549">Clasificadores que se pueden entrenar.</span><span class="sxs-lookup"><span data-stu-id="19a26-549">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="19a26-550">Conocer sus datos con el explorador de contenido y el explorador de actividades.</span><span class="sxs-lookup"><span data-stu-id="19a26-550">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="19a26-551">Publicar etiquetas mediante las directivas (manual y automático).</span><span class="sxs-lookup"><span data-stu-id="19a26-551">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="19a26-552">Crear directivas de protección de pérdida de datos (DLP) de los chats y canales de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="19a26-552">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="19a26-553">Crear directivas de DLP de punto de conexión para dispositivos con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-553">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="19a26-554">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-554">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="19a26-555">Clave de cliente.</span><span class="sxs-lookup"><span data-stu-id="19a26-555">Customer key.</span></span></li>
<li><span data-ttu-id="19a26-556">Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="19a26-556">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="19a26-557">Creación o modificación de diccionarios de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="19a26-557">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="19a26-558">Secuencias de comandos y códigos personalizados.</span><span class="sxs-lookup"><span data-stu-id="19a26-558">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="19a26-559">
<strong>Nota:</strong> Para obtener más información, vea <strong> Azure Information Protection </strong> en <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-559">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="19a26-560">Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="19a26-560">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-561"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-561"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="19a26-562">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-562">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-563">Confirmar que los requisitos mínimos de Exchange Online, SharePoint Online, los grupos de Office 365 y Azure AD son compatibles con Teams.</span><span class="sxs-lookup"><span data-stu-id="19a26-563">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="19a26-564">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="19a26-564">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="19a26-565">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="19a26-565">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="19a26-566">Confirmar que se ha habilitado Teams en su espacio empresarial de Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-566">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="19a26-567">Habilitar o deshabilitar licencias de usuario.</span><span class="sxs-lookup"><span data-stu-id="19a26-567">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="19a26-568">Evaluación de la red para Teams:</span><span class="sxs-lookup"><span data-stu-id="19a26-568">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-569">Comprobaciones de puertos y puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="19a26-569">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="19a26-570">Comprobaciones de calidad de la conexión.</span><span class="sxs-lookup"><span data-stu-id="19a26-570">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="19a26-571">Estimaciones de ancho de banda.</span><span class="sxs-lookup"><span data-stu-id="19a26-571">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="19a26-572">Configuración de la Directiva de aplicación de Microsoft Teams (Teams Web App, Teams App de escritorio y Teams para iOS y aplicación Android).</span><span class="sxs-lookup"><span data-stu-id="19a26-572">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="19a26-573">Si procede, también se proporcionan instrucciones para:</span><span class="sxs-lookup"><span data-stu-id="19a26-573">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-574">Dispositivos de Microsoft Teams Room:</span><span class="sxs-lookup"><span data-stu-id="19a26-574">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="19a26-575">Creación de cuentas en línea necesarias para los dispositivos de telefonía y salas de conferencias compatibles que aparecen en el <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos de Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-575">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="19a26-576">Asistencia remota con la configuración del servicio de dispositivos certificados de salas de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="19a26-576">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="19a26-577">Habilitar audioconferencia:</span><span class="sxs-lookup"><span data-stu-id="19a26-577">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="19a26-578">Parámetros predeterminados de la configuración de la organización para puente de conferencia.</span><span class="sxs-lookup"><span data-stu-id="19a26-578">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="19a26-579">Asignación de un puente de conferencia a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="19a26-579">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="19a26-580">Sistema telefónico:</span><span class="sxs-lookup"><span data-stu-id="19a26-580">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-581">Configuración de la organización para los parámetros predeterminados de voz en la nube.</span><span class="sxs-lookup"><span data-stu-id="19a26-581">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="19a26-582">Guía de planes de llamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponibles</a>):</span><span class="sxs-lookup"><span data-stu-id="19a26-582">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="19a26-583">Asignación de números a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="19a26-583">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="19a26-584">Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.</span><span class="sxs-lookup"><span data-stu-id="19a26-584">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="19a26-585">Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.</span><span class="sxs-lookup"><span data-stu-id="19a26-585">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-586">Guía de enrutamiento directo:</span><span class="sxs-lookup"><span data-stu-id="19a26-586">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-587">Guía de configuración de la organización para el diseño de enrutamiento directo de escenarios hospedados por asociados o escenarios implementados por el cliente para un máximo de 10 sitios.</span><span class="sxs-lookup"><span data-stu-id="19a26-587">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="19a26-588">Revisión de la configuración del controlador de borde de sesión (SBC).</span><span class="sxs-lookup"><span data-stu-id="19a26-588">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="19a26-589">Asistencia remota con la configuración del plan de marcado.</span><span class="sxs-lookup"><span data-stu-id="19a26-589">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="19a26-590">Configuración de la ruta de voz.</span><span class="sxs-lookup"><span data-stu-id="19a26-590">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="19a26-591">Omisión de medios y optimización de medios locales.</span><span class="sxs-lookup"><span data-stu-id="19a26-591">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="19a26-592">Habilitar eventos en directo en Teams</span><span class="sxs-lookup"><span data-stu-id="19a26-592">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="19a26-593">Configuración e integración de la organización en Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="19a26-593">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="19a26-594">Guía para la transición de Skype empresarial a teams.</span><span class="sxs-lookup"><span data-stu-id="19a26-594">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="19a26-595">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-595">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="19a26-596">Usuarios habilitados para SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="19a26-596">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="19a26-597">Los buzones de Exchange están presentes (en línea y local en una configuración híbrida de Exchange).</span><span class="sxs-lookup"><span data-stu-id="19a26-597">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="19a26-598">Habilitado para Grupos de Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-598">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="19a26-599">
  <strong>Nota:</strong> Si los usuarios no están asignados ni habilitados con licencias de SharePoint Online, no tendrán almacenamiento de OneDrive para la empresa en Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-599">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="19a26-600">El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin el almacenamiento de OneDrive para la empresa en Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-600">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="19a26-601">Teams no es compatible con SharePoint local.</span><span class="sxs-lookup"><span data-stu-id="19a26-601">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="19a26-602">
  <strong>Nota:</strong> El estado ideal es que todos los usuarios tengan sus buzones hospedados en Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="19a26-602">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="19a26-603">Los usuarios con buzones de correo hospedados de forma local deben tener sus identidades sincronizadas con el directorio de Office 365 mediante Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="19a26-603">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="19a26-604">Para estos clientes híbridos de Exchange, si el buzón de correo del usuario es local, el usuario no puede agregar ni configurar conectores.</span><span class="sxs-lookup"><span data-stu-id="19a26-604">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="19a26-605">Los instaladores para los clientes de escritorio de Mac y Windows en Microsoft Teams se pueden descargar de <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-605">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-606"><strong>Protección contra amenazas avanzada de Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-606"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="19a26-607">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-607">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-608">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="19a26-608">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="19a26-609">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="19a26-609">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="19a26-610">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="19a26-610">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="19a26-611">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="19a26-611">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="19a26-612">Aparte de la parte de <strong>incorporación principal</strong> en <a href="#general">General</a>, no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="19a26-612">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-613"><strong>Outlook para iOS y Android</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-613"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="19a26-614">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-614">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-615">Descargar Outlook para iOS y Android desde la App Store de Apple y Google Play.</span><span class="sxs-lookup"><span data-stu-id="19a26-615">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="19a26-616">Configurar cuentas y acceder al buzón de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="19a26-616">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="19a26-617">Securing Outlook Mobile (consulte <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">protección de Outlook para iOS y Android en Exchange Online</a> para obtener más información).</span><span class="sxs-lookup"><span data-stu-id="19a26-617">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="19a26-618">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-618">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="19a26-619">Exchange Online configurado y licencias asignadas.</span><span class="sxs-lookup"><span data-stu-id="19a26-619">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-620"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-620"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="19a26-621">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-621">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-622">Asignación de licencias de Power BI.</span><span class="sxs-lookup"><span data-stu-id="19a26-622">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="19a26-623">Implementación de la aplicación Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="19a26-623">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="19a26-624">El software cliente en línea, como Power BI Desktop, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-624">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-625"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-625"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="19a26-626">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-626">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-627">Comprobación de la funcionalidad básica de SharePoint que se basa en Project Online.</span><span class="sxs-lookup"><span data-stu-id="19a26-627">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="19a26-628">Adición del servicio de Project Online al espacio empresarial (incluida la adición de las suscripciones a los usuarios).</span><span class="sxs-lookup"><span data-stu-id="19a26-628">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="19a26-629">Configuración del grupo de recursos de empresa (ERP).</span><span class="sxs-lookup"><span data-stu-id="19a26-629">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="19a26-630">Creación del primer proyecto.</span><span class="sxs-lookup"><span data-stu-id="19a26-630">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="19a26-631">El software cliente en línea, como Project para Office 365, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-631">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-632"><strong>Project Online Professional y Premium</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-632"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="19a26-633">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-634">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="19a26-634">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="19a26-635">Asignar licencias de usuario final mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="19a26-635">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="19a26-636">Instalar Cliente de escritorio de Project Online desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="19a26-636">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="19a26-637">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-637">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="19a26-638">Configurar un servidor de distribución in situ único para Cliente de escritorio de Project Online, incluida la ayuda para crear un archivo configuration.xml para usarlo con la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-638">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="19a26-639">Conectar Cliente de escritorio de Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="19a26-639">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="19a26-640">El software cliente en línea, como Project para Office 365, debe tener un nivel mínimo, como se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-640">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-641"><strong>SharePoint Online y OneDrive para la Empresa</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-641"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="19a26-642">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-642">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-643">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="19a26-643">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="19a26-644">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="19a26-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="19a26-645">Aprovisionamiento de usuarios y licencias.</span><span class="sxs-lookup"><span data-stu-id="19a26-645">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="19a26-646">Habilitar la creación de sitios para el administrador de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="19a26-646">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="19a26-647">Planificar las colecciones de sitios.</span><span class="sxs-lookup"><span data-stu-id="19a26-647">Planning site collections.</span></span></li>
<li><span data-ttu-id="19a26-648">Proteger el contenido y administrar los permisos.</span><span class="sxs-lookup"><span data-stu-id="19a26-648">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="19a26-649">Configurar las características de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="19a26-649">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="19a26-650">Configuración de las características de Entorno híbrido de SharePoint, como la búsqueda híbrida, los sitios híbridos, la taxonomía híbrida, los tipos de contenido, la creación híbrida de sitios sin intervención del administrador (solo SharePoint Server 2013), el iniciador de aplicaciones extendido, OneDrive para la Empresa híbrido y los sitios de extranet.</span><span class="sxs-lookup"><span data-stu-id="19a26-650">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="19a26-651">El enfoque de migración.</span><span class="sxs-lookup"><span data-stu-id="19a26-651">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="19a26-652">Se proporcionan instrucciones adicionales para OneDrive para la empresa en función de la versión de SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="19a26-652">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-653">Identificación de las opciones de integración y revisión del ancho de banda y la infraestructura de red local y en línea.</span><span class="sxs-lookup"><span data-stu-id="19a26-653">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="19a26-654">Instalación de SharePoint Online 2013 SP1 (si procede), planeamiento e implementación de los requisitos de sincronización e identidad e identificación del cliente de sincronización de OneDrive para la empresa.</span><span class="sxs-lookup"><span data-stu-id="19a26-654">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="19a26-655">Planeación e implementación de un solo lanzamiento para todos los usuarios (o un lanzamiento por fases).</span><span class="sxs-lookup"><span data-stu-id="19a26-655">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="19a26-656">Asignar licencias, redirigir mis sitios y bibliotecas de documentos personales a Office 365 (aplicable a SharePoint Online 2013), configurar audiencias para controlar el acceso a OneDrive (aplicable a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="19a26-656">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="19a26-657">Redirigir o mover carpetas conocidas a OneDrive.</span><span class="sxs-lookup"><span data-stu-id="19a26-657">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="19a26-658">Implementación de la sincronización de clientes de OneDrive para la empresa.</span><span class="sxs-lookup"><span data-stu-id="19a26-658">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="19a26-659">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="19a26-659">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="19a26-660">Para obtener información sobre cómo usar el beneficio de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">migración de datos</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-660">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="19a26-661"><strong>Para entornos híbridos de SharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-661"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="19a26-662">La configuración híbrida de SharePoint incluye la configuración de la búsqueda híbrida, los sitios, la taxonomía, los tipos de contenido, OneDrive para la empresa, un iniciador de aplicaciones extendido, sitios de extranet y la creación de sitios sin servicio conectado de forma local a un entorno de SharePoint Online de destino único.</span><span class="sxs-lookup"><span data-stu-id="19a26-662">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="19a26-663">
  <strong>Nota:</strong> La creación de sitios sin servicio está en el ámbito de los servidores locales que ejecutan SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="19a26-663">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="19a26-664">Para habilitar el entorno híbrido de SharePoint, debe disponer de uno de los siguientes entornos de SharePoint Server locales: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="19a26-664">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="19a26-665">
  <strong>Nota:</strong> La actualización de entornos de SharePoint local a SharePoint Server no se encuentra en el ámbito.</span><span class="sxs-lookup"><span data-stu-id="19a26-665">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="19a26-666">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="19a26-666">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="19a26-667">Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">niveles mínimos de actualización pública para las características híbridas de SharePoint</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="19a26-667">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="19a26-668">
  <strong>Nota:</strong> Para obtener información sobre las funciones multigeográficas, consulte <a href="https://go.microsoft.com/fwlink/?linkid=831056">multigeográfico Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="19a26-668">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-669"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-669"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="19a26-670">Proporcionamos instrucciones remotas para habilitar el servicio Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="19a26-670">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="19a26-671">El software de cliente en línea debe tener un nivel mínimo, como se define en los <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisitos del sistema para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-671">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="19a26-672">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="19a26-672">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="19a26-673"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-673"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="19a26-674"><strong>Detalles de la guía de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-674"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="19a26-675"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-675"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="19a26-676"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-676"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="19a26-677">Proporcionamos una orientación remota para proteger sus identidades de nube en los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="19a26-677">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="19a26-678">

<strong>Infraestructura de base segura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="19a26-678">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="19a26-679">Configuración y habilitación de la autenticación segura para sus identidades, incluida la protección con Azure multi-factor Authentication (MFA) (solo nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseña de autoservicio (SSPR).</span><span class="sxs-lookup"><span data-stu-id="19a26-679">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="19a26-680">Para clientes que no son de Azure Premium, se proporciona orientación para proteger las identidades mediante los valores predeterminados de seguridad.</span><span class="sxs-lookup"><span data-stu-id="19a26-680">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="19a26-681">Para los clientes de Azure AD Premium, se proporciona orientación para proteger las identidades con acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="19a26-681">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="19a26-682">Detección y bloqueo del uso de contraseñas débiles con la protección con contraseña de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-682">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="19a26-683">Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-683">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="19a26-684">Habilitación de la detección y corrección basada en riesgos con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="19a26-684">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="19a26-685">Habilitación de una pantalla de inicio de sesión personalizada, que incluye logotipos, texto e imágenes con personalización de marca.</span><span class="sxs-lookup"><span data-stu-id="19a26-685">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="19a26-686">Comparta de forma segura aplicaciones y servicios con usuarios invitados mediante la B2B de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-686">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="19a26-687">Administración del acceso para los administradores de Office 365 mediante funciones administrativas integradas de control de acceso basado en roles (RBAC) y para reducir el número de cuentas de administrador con privilegios.</span><span class="sxs-lookup"><span data-stu-id="19a26-687">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="19a26-688">Configurar una Unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-688">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="19a26-689">Configurando Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="19a26-689">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="19a26-690">
  
<strong>Supervisión y generación de informes</strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-690">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-691">Habilitación de la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="19a26-691">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="19a26-692">
  
<strong>Empresarial</strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-692">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-693">Administrar su ciclo de vida de identidad y acceso de Azure AD a escala con la administración de derechos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-693">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="19a26-694">Administrar la pertenencia a grupos de Azure AD, el acceso de la aplicación empresarial y las asignaciones de roles con las revisiones de acceso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-694">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-695">Revisión de los términos de uso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-695">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-696">Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="19a26-696">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="19a26-697">
  
<strong>Automatización y eficiencia </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-697">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-698">Habilitación de Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="19a26-698">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="19a26-699">Permitir a los usuarios crear y administrar sus propios grupos de seguridad en la nube u Office 365 con la administración de grupos de autoservicio de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-699">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-700">Administración del acceso delegado a las aplicaciones empresariales con la administración de grupos delegados de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-700">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-701">Habilitación de grupos dinámicos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-701">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="19a26-702">Organizar aplicaciones en el portal de mis aplicaciones mediante colecciones</span><span class="sxs-lookup"><span data-stu-id="19a26-702">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="19a26-703">La implementación local de Active Directory y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con Azure AD y las características de Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="19a26-703">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="19a26-704"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="19a26-704"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="19a26-705">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-705">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-706">Activar y configurar el inquilino.</span><span class="sxs-lookup"><span data-stu-id="19a26-706">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="19a26-707">Crear y configurar etiquetas y directivas.</span><span class="sxs-lookup"><span data-stu-id="19a26-707">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-708">Aplicar la protección de la información a documentos.</span><span class="sxs-lookup"><span data-stu-id="19a26-708">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="19a26-709">Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="19a26-709">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="19a26-710">Detectar y etiquetar archivos en reposo con el escáner de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="19a26-710">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="19a26-711">Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="19a26-711">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="19a26-712">También le ofrecemos instrucciones para aplicar la protección con Microsoft Azure Rights Management Services (Azure RMS), el cifrado de mensajes de Office 365 (OME) y la prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="19a26-712">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="19a26-713">Las responsabilidades de requisitos previos del cliente incluyen:</span><span class="sxs-lookup"><span data-stu-id="19a26-713">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-714">Una lista de ubicaciones de recursos compartidos de archivos que se examinarán.</span><span class="sxs-lookup"><span data-stu-id="19a26-714">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="19a26-715">Una taxonomía de clasificación aprobada.</span><span class="sxs-lookup"><span data-stu-id="19a26-715">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="19a26-716">Comprensión de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.</span><span class="sxs-lookup"><span data-stu-id="19a26-716">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="19a26-717">Una cuenta de servicio creada para su Active Directory local que se haya sincronizado con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-717">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="19a26-718">Etiquetas configuradas para clasificación y protección.</span><span class="sxs-lookup"><span data-stu-id="19a26-718">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="19a26-719">Todos los requisitos previos para el analizador de Azure Information Protection están en su ubicación.</span><span class="sxs-lookup"><span data-stu-id="19a26-719">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="19a26-720">Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">requisitos previos para instalar e implementar el escáner de etiquetación unificada de Azure Information Protection</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-720">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="19a26-721">Asegúrese de que los dispositivos de usuario ejecutan un sistema operativo compatible y tienen instalados los requisitos previos necesarios.</span><span class="sxs-lookup"><span data-stu-id="19a26-721">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="19a26-722">Consulte lo siguiente para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="19a26-722">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="19a26-723"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetación unificada de Azure Information Protection para los usuarios</a>   </span><span class="sxs-lookup"><span data-stu-id="19a26-723"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="19a26-724"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="19a26-724"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="19a26-725">Instalación y configuración del conector y los servidores de Azure RMS, incluido el conector de Active Directory RMS (AD RMS) para la compatibilidad con entornos híbridos.</span><span class="sxs-lookup"><span data-stu-id="19a26-725">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="19a26-726">Instalación y configuración de traer su propia clave (BYOK), cifrado de doble clave (DKE) (solo cliente de etiquetado unificado) o mantenga su propia clave (HYOK) (solo cliente clásico) en caso de que necesite una de estas opciones para la implementación.</span><span class="sxs-lookup"><span data-stu-id="19a26-726">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="19a26-727"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-727"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="19a26-728">Proporcionamos instrucciones remotas para prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-728">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="19a26-729">Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles.</span><span class="sxs-lookup"><span data-stu-id="19a26-729">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="19a26-730">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="19a26-730">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-731">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="19a26-731">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="19a26-732">Configurar las identidades que se usarán en Intune aprovechando las identidades locales de Active Directory o de la nube (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="19a26-732">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="19a26-733">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-733">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="19a26-734">Configurar la autoridad de MDM, en función de las necesidades de administración, entre las que se incluyen:</span><span class="sxs-lookup"><span data-stu-id="19a26-734">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-735">Establecer Intune como entidad MDM cuando Intune es la única solución MDM.</span><span class="sxs-lookup"><span data-stu-id="19a26-735">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-736">Proporcionar instrucciones de MDM para:</span><span class="sxs-lookup"><span data-stu-id="19a26-736">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-737">Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.</span><span class="sxs-lookup"><span data-stu-id="19a26-737">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-738">Configurar servicios y directivas de administración de MDM como:</span><span class="sxs-lookup"><span data-stu-id="19a26-738">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-739">Implementación de aplicaciones para cada plataforma admitida a través de vínculos Web o vínculos profundos.</span><span class="sxs-lookup"><span data-stu-id="19a26-739">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="19a26-740">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="19a26-740">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-741">Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tiene una entidad de certificación, una red inalámbrica o una infraestructura de VPN en su organización.</span><span class="sxs-lookup"><span data-stu-id="19a26-741">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="19a26-742">Conexión al almacén de datos de Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-742">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="19a26-743">Integrar Intune con:</span><span class="sxs-lookup"><span data-stu-id="19a26-743">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-744">Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="19a26-744">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="19a26-745">Soluciones de asociados de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).</span><span class="sxs-lookup"><span data-stu-id="19a26-745">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="19a26-746">Una solución de administración de gastos de telecomunicaciones (es necesaria una suscripción a la solución de administración de gastos de telecomunicaciones).</span><span class="sxs-lookup"><span data-stu-id="19a26-746">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="19a26-747">ATP de Microsoft defender (se necesitan licencias de Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="19a26-747">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-748">Inscribir dispositivos de cada plataforma compatible en Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-748">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="19a26-749">Proporciona instrucciones de protección de aplicaciones en:</span><span class="sxs-lookup"><span data-stu-id="19a26-749">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-750">Configurar directivas de protección de aplicaciones para cada plataforma compatible.</span><span class="sxs-lookup"><span data-stu-id="19a26-750">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="19a26-751">Configuración de directivas de acceso condicional para aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="19a26-751">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="19a26-752">Dirigirse a los grupos de usuarios apropiados con las directivas de MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="19a26-752">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-753">Uso de informes de uso de aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="19a26-753">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-754">Proporciona instrucciones de migración desde la administración de equipos heredados a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="19a26-754">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="19a26-755">
  <strong>Nota</strong>: la administración de equipos heredados ya no se admite desde el 15 de octubre de 2020 en adelante.</span><span class="sxs-lookup"><span data-stu-id="19a26-755">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="19a26-756"></li>
</ul>
  
<strong>Conexión a la nube</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-756"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="19a26-757">Le guiamos a través de la preparación para hospedar en la nube entornos de Configuration Manager existentes con Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-757">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="19a26-758">Los pasos detallados dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="19a26-758">The exact steps depend on your source environment.</span></span> <span data-ttu-id="19a26-759">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="19a26-759">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="19a26-760">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="19a26-760">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="19a26-761">Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="19a26-761">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="19a26-762">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-762">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="19a26-763">Proporciona instrucciones sobre cómo configurar la Unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="19a26-763">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="19a26-764">Proporciona instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.</span><span class="sxs-lookup"><span data-stu-id="19a26-764">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="19a26-765">Proporcionar instrucciones sobre cómo configurar Cloud Management Gateway.</span><span class="sxs-lookup"><span data-stu-id="19a26-765">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="19a26-766">Configurar cargas de trabajo compatibles que quiera cambiar a Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-766">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="19a26-767">Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-767">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="19a26-768"><strong>Implementar Outlook Mobile para iOS y Android de manera segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook Mobile para iOS y Android de forma segura en su organización para asegurarse de que los usuarios tengan instaladas todas las aplicaciones necesarias.</span><span class="sxs-lookup"><span data-stu-id="19a26-768"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="19a26-769">Los pasos para implementar de forma segura Outlook Mobile para iOS y Android con Intune dependen de su entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="19a26-769">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="19a26-770">Puede incluir:</span><span class="sxs-lookup"><span data-stu-id="19a26-770">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-771">Descargar las aplicaciones Outlook para iOS y Android, autenticador de Microsoft y portal de empresa de Intune a través de la App Store de Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="19a26-771">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="19a26-772">Proporciona instrucciones para configurar:</span><span class="sxs-lookup"><span data-stu-id="19a26-772">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-773">La implementación de las aplicaciones de Outlook para iOS y Android, el autenticador de Microsoft y el portal de empresa de Intune con Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-773">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="19a26-774">Directivas de protección de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-774">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-775">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="19a26-775">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="19a26-776">Directivas de configuración de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="19a26-776">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="19a26-777"><strong>Nota</strong>: FastTrack no es compatible con la protección de Outlook para iOS y Android con las directivas de buzón de correo de dispositivo móvil de Exchange.</span><span class="sxs-lookup"><span data-stu-id="19a26-777"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="19a26-778">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="19a26-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="19a26-779">Los administradores de TI deben contar con una entidad de certificación, una red inalámbrica y unas infraestructuras VPN existentes en sus entornos de producción al planear la implementación de perfiles de red inalámbrica y VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-779">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="19a26-780"><strong>Nota</strong>: el beneficio del servicio FastTrack no incluye asistencia para configurar o configurar entidades de certificación, redes inalámbricas, infraestructuras VPN o certificados push de Apple para Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-780"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="19a26-781"><strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube.</span><span class="sxs-lookup"><span data-stu-id="19a26-781"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="19a26-782">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="19a26-782">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="19a26-783"><strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-783"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="19a26-784"><strong>Nota</strong>: proporcionamos asistencia sobre la integración de Intune con Microsoft defender ATP y la creación de directivas de cumplimiento de dispositivos basadas en su evaluación de nivel de riesgo de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-784"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="19a26-785">No proporcionamos asistencia sobre la compra, concesión de licencias o activación.</span><span class="sxs-lookup"><span data-stu-id="19a26-785">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="19a26-786">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="19a26-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="19a26-787"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-787"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="19a26-788">Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="19a26-788">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="19a26-789">Windows 10</span><span class="sxs-lookup"><span data-stu-id="19a26-789">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="19a26-790"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-790"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="19a26-791"><strong>Detalles de la guía de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-791"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="19a26-792"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-792"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="19a26-793"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-793"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="19a26-794">Proporcionamos instrucciones para la actualización de Windows 7 Professional y Windows 8,1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="19a26-794">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="19a26-795">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-795">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-796">Comprender su intención de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-796">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="19a26-797">Evaluar el entorno de origen y los requisitos (Asegúrese de que el administrador de configuración de Microsoft Endpoint se actualiza al nivel requerido para admitir la implementación de Windows 10).</span><span class="sxs-lookup"><span data-stu-id="19a26-797">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="19a26-798">Implementación de aplicaciones de Windows 10 Enterprise y Microsoft 365 con Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-798">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="19a26-799">Recomendar opciones para evaluar las aplicaciones de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-799">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="19a26-800">Habilitación del uso de análisis de escritorio y orientación mediante la creación de un plan de implementación de análisis de escritorio.</span><span class="sxs-lookup"><span data-stu-id="19a26-800">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="19a26-801">Evaluación de la compatibilidad de las aplicaciones de Microsoft 365 aprovechando el panel de preparación de Office 365 en Configuration Manager o con el kit de herramientas de preparación independiente para Office más asistencia para la implementación de aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-801">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="19a26-802">Crear una lista de comprobación de corrección sobre lo que debe hacer para llevar el entorno de origen a los requisitos mínimos para una implementación correcta.</span><span class="sxs-lookup"><span data-stu-id="19a26-802">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="19a26-803">Proporciona instrucciones de actualización para los dispositivos existentes a Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesario.</span><span class="sxs-lookup"><span data-stu-id="19a26-803">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="19a26-804">Proporcionar instrucciones de actualización para apoyar el movimiento de implementación existente.</span><span class="sxs-lookup"><span data-stu-id="19a26-804">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="19a26-805">FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-805">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="19a26-806">Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="19a26-806">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="19a26-807">Implementación de aplicaciones de Microsoft 365 con Configuration Manager como parte de la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-807">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="19a26-808">Proporcionan instrucciones para ayudar a su organización a mantenerse al día con las aplicaciones de Windows 10 Enterprise y Microsoft 365 usando su entorno de Configuration Manager existente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-808">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="19a26-809">
  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-809">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="19a26-810">Actualizar Configuration Manager a la rama actual.</span><span class="sxs-lookup"><span data-stu-id="19a26-810">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="19a26-811">Crear imágenes personalizadas para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-811">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="19a26-812">Crear y admitir scripts de implementación para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-812">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="19a26-813">Convertir un sistema Windows 10 del BIOS a la Interfaz de firmware extensible unificado (UEFI).</span><span class="sxs-lookup"><span data-stu-id="19a26-813">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="19a26-814">Habilitar las características de seguridad de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-814">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="19a26-815">Configurar los Servicios de implementación de Windows (WDS) para el arranque del Entorno de ejecución previo al inicio (PXE).</span><span class="sxs-lookup"><span data-stu-id="19a26-815">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="19a26-816">Usar Microsoft Deployment Toolkit (MDT) para capturar e implementar imágenes de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-816">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="19a26-817">Usar la Herramienta de migración de estado de usuario (USMT).</span><span class="sxs-lookup"><span data-stu-id="19a26-817">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="19a26-818">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="19a26-818">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="19a26-819">Para actualizar su PC, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="19a26-819">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-820">SO de origen: Windows 7 Enterprise o Professional, Windows 8,1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="19a26-820">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="19a26-821">Dispositivos: formato de escritorio, portátil o tableta.</span><span class="sxs-lookup"><span data-stu-id="19a26-821">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="19a26-822">SO de destino: window 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="19a26-822">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="19a26-823">Para actualizar la infraestructura, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="19a26-823">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-824">Administrador de configuración de Microsoft Endpoint.</span><span class="sxs-lookup"><span data-stu-id="19a26-824">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="19a26-825">La versión de destino de Windows 10 debe admitir la versión del administrador de configuración.</span><span class="sxs-lookup"><span data-stu-id="19a26-825">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="19a26-826">Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Soporte para Windows 10 en Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-826">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="19a26-827"><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-827"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="19a26-828">La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.</span><span class="sxs-lookup"><span data-stu-id="19a26-828">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="19a26-829">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-829">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-830">Implementación de las tecnologías para proteger los extremos.</span><span class="sxs-lookup"><span data-stu-id="19a26-830">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="19a26-831">Configuración de Endpoint Protection y los perfiles de restricción de dispositivos.</span><span class="sxs-lookup"><span data-stu-id="19a26-831">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="19a26-832">Evaluación de la versión del sistema operativo y la administración de dispositivos (incluidos Intune, el administrador de configuración de Microsoft Endpoint, los objetos de directiva de grupo (GPO) y las configuraciones de terceros), así como el estado de los servicios de AV de Windows Defender u otro software de seguridad de extremos.</span><span class="sxs-lookup"><span data-stu-id="19a26-832">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="19a26-833">Evaluar el estado de los servicios de Windows AV o de otro software de seguridad de extremo.</span><span class="sxs-lookup"><span data-stu-id="19a26-833">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="19a26-834">Evaluar los servidores proxy y los firewalls restringir el tráfico de red.</span><span class="sxs-lookup"><span data-stu-id="19a26-834">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="19a26-835">Habilitar el servicio ATP de Microsoft defender mediante la explicación de cómo implementar un perfil de agente ATP con un punto de conexión incorporado.</span><span class="sxs-lookup"><span data-stu-id="19a26-835">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="19a26-836">Guía de implementación, asistencia para la configuración y educación en:</span><span class="sxs-lookup"><span data-stu-id="19a26-836">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-837">Administración de amenazas y vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="19a26-837">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-838">Reducción de la superficie de ataque.</span><span class="sxs-lookup"><span data-stu-id="19a26-838">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-839">Protección de nueva generación.</span><span class="sxs-lookup"><span data-stu-id="19a26-839">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-840">Detección y respuesta de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="19a26-840">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-841">Investigación y corrección automatizadas.</span><span class="sxs-lookup"><span data-stu-id="19a26-841">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-842">Puntuación de seguridad.</span><span class="sxs-lookup"><span data-stu-id="19a26-842">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-843">Revisión de simulaciones y tutoriales (como escenarios de prácticas, malware falsificado e investigaciones automatizadas).</span><span class="sxs-lookup"><span data-stu-id="19a26-843">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="19a26-844">Información general sobre las características de informes y de análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="19a26-844">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="19a26-845">Integrar Protección contra amenazas avanzadas de Office 365 con Protección contra amenazas avanzada de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="19a26-845">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="19a26-846">Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="19a26-846">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="19a26-847">Los siguientes sistemas operativos:</span><span class="sxs-lookup"><span data-stu-id="19a26-847">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-848">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="19a26-848">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-849">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="19a26-849">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-850">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="19a26-850">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-851">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="19a26-851">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-852">Canal de Semi-Annual de Windows Server (SAC) versión 1803.</span><span class="sxs-lookup"><span data-stu-id="19a26-852">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-853">macOS versiones 10,13, 10,14 y 10,15.</span><span class="sxs-lookup"><span data-stu-id="19a26-853">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="19a26-854">
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse con la versión más reciente del administrador de configuración de System Center 2012 (versiones 1012 R2, 1511 o 1602) o el administrador de configuración de Microsoft Endpoint (versión 2002 o posterior).</span><span class="sxs-lookup"><span data-stu-id="19a26-854">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="19a26-855"></li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-855"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="19a26-856">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="19a26-856">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="19a26-857">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-857">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="19a26-858">Administración continua y respuesta ante amenazas.</span><span class="sxs-lookup"><span data-stu-id="19a26-858">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="19a26-859">Incorporación o configuración para los siguientes agentes de Protección contra amenazas avanzada de Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="19a26-859">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-860">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="19a26-860">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-861">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="19a26-861">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-862">Linux.</span><span class="sxs-lookup"><span data-stu-id="19a26-862">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-863">Dispositivos móviles (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="19a26-863">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-864">Incorporación y configuración del servidor:</span><span class="sxs-lookup"><span data-stu-id="19a26-864">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-865">Configuración de un servidor proxy para las comunicaciones sin conexión.</span><span class="sxs-lookup"><span data-stu-id="19a26-865">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-866">Configuración de paquetes de implementación de Configuration Manager en instancias y versiones de administrador de configuración de nivel inferior.</span><span class="sxs-lookup"><span data-stu-id="19a26-866">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-867">Servidores de incorporación a Azure Security Center.</span><span class="sxs-lookup"><span data-stu-id="19a26-867">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-868">Servidores no administrados por Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="19a26-868">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-869">incorporación y configuración de macOS:</span><span class="sxs-lookup"><span data-stu-id="19a26-869">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-870">Implementación manual basada en la Intune.</span><span class="sxs-lookup"><span data-stu-id="19a26-870">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-871">Implementación basada en JAMF.</span><span class="sxs-lookup"><span data-stu-id="19a26-871">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="19a26-872">Otra implementación basada en producto de administración de dispositivos móviles (MDM).</span><span class="sxs-lookup"><span data-stu-id="19a26-872">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-873">Implementación manual.</span><span class="sxs-lookup"><span data-stu-id="19a26-873">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-874">Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:</span><span class="sxs-lookup"><span data-stu-id="19a26-874">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-875">Aislamiento basado en hardware.</span><span class="sxs-lookup"><span data-stu-id="19a26-875">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-876">Control de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-876">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-877">Protección contra vulnerabilidades de seguridad.</span><span class="sxs-lookup"><span data-stu-id="19a26-877">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-878">Firewall de red.</span><span class="sxs-lookup"><span data-stu-id="19a26-878">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="19a26-879">Inscripción o configuración de Expertos en amenazas de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="19a26-879">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="19a26-880">Configuración o formación que revisan la API o la información de seguridad y las conexiones de administración de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="19a26-880">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="19a26-881">Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="19a26-881">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="19a26-882">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="19a26-882">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="19a26-883">Formación o orientación sobre el uso o la creación de consultas Kusto.</span><span class="sxs-lookup"><span data-stu-id="19a26-883">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="19a26-884">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="19a26-884">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="19a26-885">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="19a26-885">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="19a26-886"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-886"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="19a26-887"><strong>Detalles de la guía de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-887"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="19a26-888"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-888"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="19a26-889"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-889"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="19a26-890">Proporcionamos una guía de implementación para la incorporación a escritorio virtual de Windows (un servicio de virtualización de aplicaciones y de escritorio).</span><span class="sxs-lookup"><span data-stu-id="19a26-890">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="19a26-891">El escritorio virtual de Windows aprovecha la experiencia de varias sesiones de Windows 10 y está optimizado para Microsoft 365 apps for Enterprise con Integrated Security and Management for Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-891">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="19a26-892">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="19a26-892">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="19a26-893">Implementar el entorno de escritorio virtual de Windows con la sesión múltiple de Windows 10 Enterprise y las aplicaciones de Microsoft 365 para empresas mediante lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="19a26-893">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="19a26-894">Imagen de Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="19a26-894">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="19a26-895">Imagen compartida.</span><span class="sxs-lookup"><span data-stu-id="19a26-895">Shared image.</span></span></li>
<li><span data-ttu-id="19a26-896">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="19a26-896">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="19a26-897">Configuración de FSLogix:</span><span class="sxs-lookup"><span data-stu-id="19a26-897">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="19a26-898">Implementación del agente de FSLogix con el contenedor de perfiles.</span><span class="sxs-lookup"><span data-stu-id="19a26-898">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="19a26-899">Implementación del agente de FSLogix con el contenedor de Office.</span><span class="sxs-lookup"><span data-stu-id="19a26-899">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="19a26-900">Configuración de la carpeta FSLogix con exclusiones de contenido.</span><span class="sxs-lookup"><span data-stu-id="19a26-900">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="19a26-901">Implementación de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="19a26-901">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="19a26-902">Implementación de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="19a26-902">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="19a26-903">Conexión mediante los clientes de escritorio virtuales de Windows.</span><span class="sxs-lookup"><span data-stu-id="19a26-903">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="19a26-904">

<strong>Lo siguiente está fuera del ámbito</strong>
</span><span class="sxs-lookup"><span data-stu-id="19a26-904">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="19a26-905">Administración de proyectos de la implementación de escritorio virtual de Windows del cliente.</span><span class="sxs-lookup"><span data-stu-id="19a26-905">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="19a26-906">Virtualización e implementación de aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="19a26-906">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="19a26-907">Imágenes personalizadas.</span><span class="sxs-lookup"><span data-stu-id="19a26-907">Custom images.</span></span></li>
<li><span data-ttu-id="19a26-908">Migraciones y escenarios que implican VMware y Citrix.</span><span class="sxs-lookup"><span data-stu-id="19a26-908">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="19a26-909">Escenarios de Linux.</span><span class="sxs-lookup"><span data-stu-id="19a26-909">Linux scenarios.</span></span></li>
<li><span data-ttu-id="19a26-910">Conversión o migraciones de perfiles de usuario.</span><span class="sxs-lookup"><span data-stu-id="19a26-910">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="19a26-911">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="19a26-911">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="19a26-912">Ya debe tener lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="19a26-912">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="19a26-913"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licencia de escritorio virtual de Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-913"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="19a26-914">Redes de Azure:</span><span class="sxs-lookup"><span data-stu-id="19a26-914">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="19a26-915">Creación y subredes de la red virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="19a26-915">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="19a26-916">Grupos de seguridad de red y firewall.</span><span class="sxs-lookup"><span data-stu-id="19a26-916">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="19a26-917">VPN y ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="19a26-917">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="19a26-918">Enrutamiento a Azure desde el sistema local.</span><span class="sxs-lookup"><span data-stu-id="19a26-918">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="19a26-919">Reglas de Firewall para permitir la conectividad con el escritorio virtual de Windows.</span><span class="sxs-lookup"><span data-stu-id="19a26-919">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="19a26-920">Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> clientes de escritorio remoto compatibles</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-920">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="19a26-921">Configuración general de Azure AD:</span><span class="sxs-lookup"><span data-stu-id="19a26-921">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="19a26-922">Estrategia <i>de identidad (solo puede usar una de las tres opciones siguientes):</i>
</span><span class="sxs-lookup"><span data-stu-id="19a26-922">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="19a26-923">Active Directory con Azure AD Connect en Azure.</span><span class="sxs-lookup"><span data-stu-id="19a26-923">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="19a26-924">Active Directory con Azure AD Connect local a través de VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="19a26-924">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="19a26-925">Servicios de dominio de Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="19a26-925">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="19a26-926">App Assure</span><span class="sxs-lookup"><span data-stu-id="19a26-926">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="19a26-927"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-927"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="19a26-928"><strong>Detalles de la guía de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-928"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="19a26-929"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-929"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="19a26-930"><strong>Asesoría de aplicaciones</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-930"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="19a26-931">La aplicación garantiza un servicio diseñado para solucionar problemas con Windows 10 y la compatibilidad de aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-931">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="19a26-932">Cuando solicite a la aplicación garantizar el servicio, trabajamos con usted para solucionar problemas de aplicación válidos sin costo adicional para usted con una suscripción elegible.</span><span class="sxs-lookup"><span data-stu-id="19a26-932">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="19a26-933">También ofrecemos orientación a los clientes que se enfrentan a problemas de compatibilidad al implementar el escritorio virtual de Windows y el nuevo Microsoft Edge, y hacer cada uno de los esfuerzos razonables para resolver problemas de compatibilidad.</span><span class="sxs-lookup"><span data-stu-id="19a26-933">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="19a26-934">Proporcionamos asistencia de corrección para las aplicaciones implementadas en los siguientes productos de Microsoft:</span><span class="sxs-lookup"><span data-stu-id="19a26-934">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="19a26-935"><strong>Windows 10 </strong> (incluidos los dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="19a26-935"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="19a26-936"><strong>Aplicaciones de Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="19a26-936"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="19a26-937"><strong>El nuevo Microsoft Edge-</strong> Para obtener instrucciones de implementación, vea <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">información general de los canales de Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-937"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="19a26-938">Escritorio virtual de <strong>Windows</strong> - Para obtener más información, vea <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">¿Qué es el escritorio virtual de Windows?</a> y <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">preguntas más frecuentes sobre la sesión múltiple de Windows 10 Enterprise</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-938"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="19a26-939">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-939">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="19a26-p149">Inventario y pruebas de aplicaciones para determinar lo que funciona y lo que no en Windows 10 y en las Aplicaciones de Microsoft 365. Para obtener más información sobre este proceso, visite el <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de implementación de escritorios</a>. Si está interesado en una evaluación detallada de la preparación para la actualización, complete el formulario <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitud de cliente para la evaluación del escritorio moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-p149">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="19a26-943">Buscar instrucciones de compatibilidad y soporte técnico de Windows 10 en aplicaciones ISV de terceros.</span><span class="sxs-lookup"><span data-stu-id="19a26-943">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="19a26-944">Para más información, vea <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análisis de escritorio</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-944">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="19a26-945">Servicios de solo empaquetado de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="19a26-945">App packaging-only services.</span></span> <span data-ttu-id="19a26-946">Sin embargo, el equipo de App Assure crea paquetes de aplicaciones que hemos corregido para Windows 10 para asegurarse de que se pueden implementar en el entorno del cliente.</span><span class="sxs-lookup"><span data-stu-id="19a26-946">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="19a26-947">

<strong>Las responsabilidades del cliente incluyen</strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-947">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="19a26-948">Creación de un inventario de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-948">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="19a26-949">Validación de esas aplicaciones en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-949">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="19a26-950">
<strong>Nota:</strong>  Microsoft no puede realizar cambios en el código fuente.</span><span class="sxs-lookup"><span data-stu-id="19a26-950">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="19a26-951">Sin embargo, el equipo de App Assure puede proporcionar instrucciones a los desarrolladores de aplicaciones si el código fuente está disponible para sus aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-951">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="19a26-952">Póngase en contacto con un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">socio de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="19a26-952">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="19a26-953"><strong>Aplicaciones de Windows 10 y Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="19a26-953"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-954">Las aplicaciones que funcionaban en Windows 7, Windows 8.1, Office 2010 y Office 2013 también funcionan en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="19a26-954">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="19a26-955">
<strong>Windows 10 en ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="19a26-955">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="19a26-956">Las aplicaciones que funcionaban en Windows 7, Office 2010 o versiones posteriores también funcionan en aplicaciones de Windows 10 y Microsoft 365 en dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="19a26-956">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="19a26-957">
  <strong>Note</strong> 
</span><span class="sxs-lookup"><span data-stu-id="19a26-957">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="19a26-958">la emulación de x64 (64 bits) está disponible en versión preliminar para los clientes que participan en el <a href="https://insider.windows.com/">programa Windows Insider</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-958">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="19a26-959">Para los clientes que no usan Windows Insider en Windows 10 versión 2004 (o posterior), ARM64 de Photoshop es compatible con el <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">paquete de compatibilidad de OpenCL y OpenGL</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-959">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="19a26-960">Los clientes del programa Windows Insider pueden descargar una versión Insider del paquete de compatibilidad de OpenCL y OpenGL para usar con aplicaciones adicionales.</span><span class="sxs-lookup"><span data-stu-id="19a26-960">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="19a26-961">
<strong>El nuevo Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="19a26-961">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-962">Si sus aplicaciones web o sitios funcionan en Internet Explorer 11, en versiones compatibles de Google Chrome o en cualquier versión de Microsoft Edge, también funcionarán con el nuevo Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="19a26-962">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-963">A medida que la web evolucione en todo momento, asegúrese de revisar esta lista publicada de <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">los cambios que afectan a la compatibilidad de sitios conocidos para Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="19a26-963">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="19a26-964">
  <strong>Escritorio virtual de Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-964">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="19a26-965">Las aplicaciones virtualizadas que se ejecutan en el host de sesión de Escritorio remoto (RDSH) de Windows Server también se ejecutan en Windows 10 Enterprise multisesión como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="19a26-965">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-966">Las aplicaciones que se ejecutan en cualquier entorno de infraestructura de escritorio virtual (VDI) de Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte del escritorio virtual de Windows.</span><span class="sxs-lookup"><span data-stu-id="19a26-966">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-967">Las aplicaciones que se ejecutan en dispositivos cliente con Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="19a26-967">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="19a26-968">
  <strong>Nota:</strong> Las exclusiones y limitaciones de compatibilidad de varias sesiones de Windows 10 Enterprise incluyen:</span><span class="sxs-lookup"><span data-stu-id="19a26-968">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="19a26-969">Redirección limitada del hardware.</span><span class="sxs-lookup"><span data-stu-id="19a26-969">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-970">Las aplicaciones que hacen un uso intensivo de A/V pueden tener una capacidad reducida.</span><span class="sxs-lookup"><span data-stu-id="19a26-970">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="19a26-971">Las aplicaciones de 16 bits no son compatibles con Windows Virtual Desktop de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="19a26-971">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="19a26-972">El nuevo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="19a26-972">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="19a26-973"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-973"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="19a26-974"><strong>Detalles de la guía de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-974"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="19a26-975"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="19a26-975"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="19a26-976"><strong>Microsoft Edge</strong> (para clientes de Windows 10 Enterprise)</span><span class="sxs-lookup"><span data-stu-id="19a26-976"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="19a26-977">Proporcionamos una guía de implementación remota y asistencia de compatibilidad para: implementar el nuevo Microsoft Edge en Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="19a26-977">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="19a26-978">Configuración de Microsoft Edge (usando directivas de grupo o directivas de aplicación y configuración de aplicaciones de Intune).</span><span class="sxs-lookup"><span data-stu-id="19a26-978">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="19a26-979">Inventario la lista de sitios que pueden requerir uso en el modo de Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="19a26-979">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="19a26-980">Habilitación del modo de Internet Explorer con la lista de sitios de empresa existente.</span><span class="sxs-lookup"><span data-stu-id="19a26-980">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="19a26-981">Además, si tiene una aplicación web o un sitio que funciona con Internet Explorer o Google Chrome y experimenta problemas de compatibilidad, le proporcionamos instrucciones para resolver el problema sin coste adicional.</span><span class="sxs-lookup"><span data-stu-id="19a26-981">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="19a26-982">Consulte <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">sure</a> de la aplicación para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="19a26-982">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="19a26-983">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="19a26-983">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="19a26-984">Administración de proyectos de la implementación de Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="19a26-984">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="19a26-985">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="19a26-985">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
