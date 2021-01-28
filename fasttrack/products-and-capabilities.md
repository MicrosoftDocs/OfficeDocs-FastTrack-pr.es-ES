---
title: Productos y capacidades
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias para poder empezar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que ajuste el entorno de origen a los requisitos mínimos para una incorporación correcta.
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016692"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="4de3c-104">Productos y capacidades</span><span class="sxs-lookup"><span data-stu-id="4de3c-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="4de3c-105">Servicios y escenarios admitidos por FastTrack</span><span class="sxs-lookup"><span data-stu-id="4de3c-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="4de3c-106">En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias para poder empezar.</span><span class="sxs-lookup"><span data-stu-id="4de3c-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="4de3c-107">En función de la configuración actual, trabajamos con usted para crear un plan de corrección que ajuste el entorno de origen a los requisitos mínimos para una incorporación correcta.</span><span class="sxs-lookup"><span data-stu-id="4de3c-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="4de3c-108">FastTrack proporciona instrucciones para ayudarle primero con las funcionalidades principales (comunes para todos los Microsoft Online Services) y, a continuación, con la incorporación de cada servicio elegible:</span><span class="sxs-lookup"><span data-stu-id="4de3c-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="4de3c-109">General</span><span class="sxs-lookup"><span data-stu-id="4de3c-109">General</span></span>](#general)
  - [<span data-ttu-id="4de3c-110">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="4de3c-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="4de3c-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="4de3c-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="4de3c-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="4de3c-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="4de3c-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="4de3c-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="4de3c-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="4de3c-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="4de3c-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="4de3c-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="4de3c-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="4de3c-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="4de3c-117">Para obtener información sobre las expectativas de entorno de origen para Office 365 Administración Pública, vea [Expectativas de entorno de origen para Office 365 Administración Pública](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="4de3c-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="4de3c-118">General</span><span class="sxs-lookup"><span data-stu-id="4de3c-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4de3c-119"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4de3c-120"><strong>Detalles de las instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4de3c-121"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4de3c-122"><strong>Incorporación principal</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-123">Proporcionamos instrucciones remotas sobre la incorporación principal, que implica el aprovisionamiento de servicios, el espacio empresarial y la integración de identidades.</span><span class="sxs-lookup"><span data-stu-id="4de3c-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="4de3c-124">También incluye pasos para proporcionar una base para la incorporación de servicios como Exchange Online, SharePoint Online y Microsoft Teams, incluida una discusión sobre seguridad, conectividad de red <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">y cumplimiento.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="4de3c-125">La incorporación de uno o más servicios elegibles puede empezar al finalizar la incorporación principal.</span><span class="sxs-lookup"><span data-stu-id="4de3c-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="4de3c-126"></li>
</ul>  

<strong> Integración de identidades </strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="4de3c-127">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="4de3c-128">Preparar identidades locales de Active Directory para la sincronización con Azure Active Directory (Azure AD), incluida la instalación y configuración de Azure AD Connect (bosque único o de varios bosques) y licencias (incluidas las licencias basadas en grupos).</span><span class="sxs-lookup"><span data-stu-id="4de3c-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="4de3c-129">Crear identidades en la nube, incluida la importación masiva y las licencias, incluido el uso de licencias basadas en grupos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="4de3c-130">Elegir y habilitar el método de autenticación correcto para el recorrido en la nube, la sincronización de hash de contraseña, la autenticación de paso a través o los Servicios de federación de Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="4de3c-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="4de3c-131">Habilitar AD FS para clientes con un único bosque de Active Directory e identidades sincronizadas con la herramienta Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="4de3c-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="4de3c-132">Esto requiere Windows Server 2012 R2 Servicios de federación de Active Directory 2.0 o posterior.</span><span class="sxs-lookup"><span data-stu-id="4de3c-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="4de3c-133">Migrar la autenticación de AD FS a Azure AD mediante la sincronización de hash de contraseña o la autenticación de paso a través.</span><span class="sxs-lookup"><span data-stu-id="4de3c-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="4de3c-134">Migración de aplicaciones integradas previamente (como aplicaciones de software como servicio (SaaS) de la galería de Azure AD) desde AD FS a Azure AD para el inicio de sesión único (SSO).</span><span class="sxs-lookup"><span data-stu-id="4de3c-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="4de3c-135">Habilitar las integraciones de aplicaciones SaaS con SSO desde la galería de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="4de3c-136">Habilitar el aprovisionamiento automático de usuarios para aplicaciones SaaS integradas previamente como se muestra en la lista <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">de tutoriales</a> de integración de aplicaciones (limitado a aplicaciones SaaS de la galería de Azure AD y aprovisionamiento saliente únicamente).</span><span class="sxs-lookup"><span data-stu-id="4de3c-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="4de3c-137"><strong>Habilitación de red </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="4de3c-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="4de3c-138">Como parte de las ventajas de FastTrack, le aconsejamos los procedimientos recomendados para conectarse a los servicios en la nube a fin de garantizar los niveles más altos de rendimiento de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="4de3c-139"><strong>Bosques de Active Directory</strong> Tienen el nivel de bosque funcional establecido en Windows Server 2003 en adelante, con la siguiente configuración de bosque:</span><span class="sxs-lookup"><span data-stu-id="4de3c-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-140">Un solo bosque de Active Directory.</span><span class="sxs-lookup"><span data-stu-id="4de3c-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-141">Un solo bosque de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="4de3c-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-142">Varios bosques de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="4de3c-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-143">Varios bosques de cuentas de Active Directory con uno de los bosques que es un bosque de cuentas de Active Directory centralizado que incluye Exchange o Lync 2010, Lync 2013 o Skype Empresarial.</span><span class="sxs-lookup"><span data-stu-id="4de3c-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-144">Varios bosques de cuentas de Active Directory, cada uno con su propia organización de Exchange.</span><span class="sxs-lookup"><span data-stu-id="4de3c-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-145">Tareas necesarias para la configuración de inquilinos y la integración con Azure Active Directory, si es necesario.</span><span class="sxs-lookup"><span data-stu-id="4de3c-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="4de3c-146">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="4de3c-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="4de3c-147">Para escenarios de Active Directory con varios bosques, si se implementa Lync 2010, Lync 2013 o Skype Empresarial, debe implementarse en el mismo bosque de Active Directory que Exchange.</span><span class="sxs-lookup"><span data-stu-id="4de3c-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-148">Al implementar varios bosques de Active Directory con varias organizaciones de Exchange en una configuración multi hybrid de Exchange, no se admiten espacios de nombres de nombre principal de usuario (UPN) compartidos entre bosques de origen.</span><span class="sxs-lookup"><span data-stu-id="4de3c-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="4de3c-149">Los espacios de nombres SMTP principales entre las organizaciones de Exchange también deben estar separados.</span><span class="sxs-lookup"><span data-stu-id="4de3c-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="4de3c-150">Para más información, consulte <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implementaciones híbridas con varios bosques de Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="4de3c-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-151">Para todas las configuraciones de varios bosques, la implementación de servicios de federación de Active Directory (AD FS) está fuera del ámbito.</span><span class="sxs-lookup"><span data-stu-id="4de3c-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="4de3c-152">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-153"><strong>Aplicaciones de Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-154">Proporcionamos instrucciones de implementación remota para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-155">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-156">Asignar licencias de usuario final y basadas en dispositivos mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="4de3c-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-157">Instalar Aplicaciones de Microsoft 365 desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="4de3c-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-158">Instalar aplicaciones de Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile y PowerPoint Mobile) en los dispositivos iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="4de3c-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-159">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-160">Selección y configuración de una instalación local o en la nube.</span><span class="sxs-lookup"><span data-stu-id="4de3c-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-161">Creación de la configuración XML de la herramienta de implementación de Office con la herramienta de personalización de Office o XML nativo para configurar el paquete de implementación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-162">Implementar mediante Microsoft Endpoint Configuration Manager, incluida la ayuda con la creación del empaquetado de Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="4de3c-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="4de3c-163">Además, si tiene una macro o un complemento que ha funcionado con versiones anteriores de Office y experimenta problemas de compatibilidad, proporcionamos instrucciones para corregir el problema de compatibilidad sin coste adicional a través del programa App Assure.</span><span class="sxs-lookup"><span data-stu-id="4de3c-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="4de3c-164">Consulta la <strong>parte de App Assure</strong> de Windows <a href="#windows-10">10</a> para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="4de3c-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="4de3c-165">El software cliente en línea debe estar en un nivel mínimo como se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-166"><strong>Estado de la red</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-167">Proporcionamos instrucciones remotas para obtener e interpretar datos clave de conectividad de red de su entorno que muestran cómo se alinean los sitios de su organización con los <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principios</a>de conectividad de red de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="4de3c-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="4de3c-168">Esto resalta la puntuación de red que afecta directamente a la velocidad de migración, la experiencia del usuario, el rendimiento del servicio y la confiabilidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="4de3c-169">También le guiaremos a través de los pasos de corrección resaltados por estos datos para ayudarle a mejorar la puntuación de red.</span><span class="sxs-lookup"><span data-stu-id="4de3c-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="4de3c-170">Acceso al Centro de administración de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-171">Se requieren versiones actualizadas de las aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-172">Servicios de ubicación habilitados según las recomendaciones de rendimiento de red en el Centro de administración de <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (versión preliminar).</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="4de3c-173">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="4de3c-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4de3c-174"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4de3c-175"><strong>Detalles de las instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4de3c-176"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="4de3c-177"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-178">Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="4de3c-179">

<strong>Infraestructura de base segura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="4de3c-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="4de3c-180">Configurar y habilitar la autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el autoservicio de restablecimiento de contraseña (SSPR).</span><span class="sxs-lookup"><span data-stu-id="4de3c-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-181">Para los clientes que no son de Azure AD Premium, se proporcionan instrucciones para proteger las identidades con valores predeterminados de seguridad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-182">Para los clientes de Azure AD Premium, se proporcionan instrucciones para proteger las identidades con acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="4de3c-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-183">Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-184">Proteger el acceso remoto a las aplicaciones web locales con el Proxy de aplicación de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-185">Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-186">Habilitar una pantalla de inicio de sesión personalizada, incluido el logotipo, el texto y las imágenes con la personalización de marca.</span><span class="sxs-lookup"><span data-stu-id="4de3c-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-187">Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="4de3c-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-188">Administrar el acceso de los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-189">Configurar la unión híbrida a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-190">Configurar la unión a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="4de3c-191">
  
<strong>Supervisión e informes</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-192">Habilitar la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="4de3c-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="4de3c-193">
  
<strong>Gobierno</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-194">Administrar el ciclo de vida de acceso e identidad de Azure AD a escala con la administración de derechos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="4de3c-195">Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-196">Revisar los Términos de uso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-197">Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="4de3c-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="4de3c-198">
  
<strong>Automatización y eficiencia </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-199">Habilitar SSPR de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="4de3c-200">Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos de Office 365 con la administración de grupos de autoservicio de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-201">Administrar el acceso delegado a las aplicaciones empresariales con la administración de grupos delegada de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-202">Habilitar grupos dinámicos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-203">Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4de3c-204">Active Directory local y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="4de3c-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="4de3c-206">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-207">Activar y configurar el espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="4de3c-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-208">Crear y configurar etiquetas y directivas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-209">Aplicar la protección de la información a documentos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-210">Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-211">Descubrir y etiquetar archivos en reposo con el escáner de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-212">Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4de3c-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="4de3c-213">También proporcionamos instrucciones si desea aplicar protección con Microsoft Azure Rights Management Services (Azure RMS), cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="4de3c-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="4de3c-214">Las responsabilidades de requisitos previos del cliente incluyen:</span><span class="sxs-lookup"><span data-stu-id="4de3c-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-215">Una lista de ubicaciones de recurso compartido de archivos que se examinarán.</span><span class="sxs-lookup"><span data-stu-id="4de3c-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-216">Taxonomía de clasificación aprobada.</span><span class="sxs-lookup"><span data-stu-id="4de3c-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="4de3c-217">Descripción de cualquier restricción normativa o requisitos relacionados con la administración de claves.</span><span class="sxs-lookup"><span data-stu-id="4de3c-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-218">Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="4de3c-219">Etiquetas configuradas para clasificación y protección.</span><span class="sxs-lookup"><span data-stu-id="4de3c-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="4de3c-220">Todos los requisitos previos para el escáner de Azure Information Protection están en su lugar.</span><span class="sxs-lookup"><span data-stu-id="4de3c-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="4de3c-221">Para obtener más información, vea <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Requisitos previos para</a>instalar e implementar el escáner de etiquetado unificado de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="4de3c-222">Asegúrese de que los dispositivos de usuario ejecutan un sistema operativo compatible y tienen instalados los requisitos previos necesarios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="4de3c-223">Vea lo siguiente para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="4de3c-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="4de3c-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetado unificado de Azure Information Protection para los usuarios</a>   </span><span class="sxs-lookup"><span data-stu-id="4de3c-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="4de3c-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="4de3c-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="4de3c-226">Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para la compatibilidad híbrida.</span><span class="sxs-lookup"><span data-stu-id="4de3c-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="4de3c-227">El programa de instalación y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado únicamente) o Hold Your Own Key (HYOK) (solo cliente clásico) debe requerir una de estas opciones para la implementación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="4de3c-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="4de3c-229">Microsoft 365 Defender es un conjunto unificado de defensa empresarial anterior y posterior a la infracción que coordina de forma nativa la detección, prevención, investigación y respuesta entre puntos de conexión, identidades, correo electrónico y aplicaciones para proporcionar protección integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="4de3c-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="4de3c-230">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="4de3c-231">Proporcionar información general sobre el Centro de seguridad de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-232">Revisar incidentes entre productos, incluyendo centrarse en lo que es fundamental al garantizar el ámbito de ataque completo, los activos afectados y las acciones de corrección automatizadas que se agrupan.</span><span class="sxs-lookup"><span data-stu-id="4de3c-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-233">Demostrar cómo Microsoft 365 Defender puede organizar la investigación de activos, usuarios, dispositivos y buzones que podrían haber sido comprometidos a través de la recuperación automática.</span><span class="sxs-lookup"><span data-stu-id="4de3c-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="4de3c-234">Explicar y proporcionar ejemplos de cómo los clientes pueden buscar de forma proactiva intentos de intrusiones y actividad de infracción que afecten al correo electrónico, los datos, los dispositivos y las cuentas en varios conjuntos de datos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="4de3c-235">Mostrar a los clientes cómo pueden revisar y mejorar su posición de seguridad de forma holística con puntuación de seguridad de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="4de3c-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="4de3c-236"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="4de3c-237">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="4de3c-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="4de3c-238">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="4de3c-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="4de3c-239">Guía de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="4de3c-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="4de3c-240">Cómo corregir o interpretar los distintos tipos de alertas y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="4de3c-241">Cómo investigar un usuario, equipo, ruta de movimiento lateral o entidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="4de3c-242">Búsqueda de amenazas personalizada.</span><span class="sxs-lookup"><span data-stu-id="4de3c-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="4de3c-243">Información de seguridad y administración de eventos (SIEM) o integración de API.</span><span class="sxs-lookup"><span data-stu-id="4de3c-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-245">Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una amplia visibilidad, control sobre los viajes de datos y análisis sofisticados para identificar y combatir las ciberamenazas en todos los servicios en la nube de Microsoft y de terceros.</span><span class="sxs-lookup"><span data-stu-id="4de3c-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="4de3c-246">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-247">Configurar el portal, incluidos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="4de3c-248">Importar grupos de usuarios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="4de3c-249">Administrar la configuración y el acceso de administrador.</span><span class="sxs-lookup"><span data-stu-id="4de3c-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="4de3c-250">Ámbito de la implementación para seleccionar determinados grupos de usuarios que se supervisarán o excluirán de la supervisión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="4de3c-251">Establecer intervalos IP y etiquetas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="4de3c-252">Personalización de la experiencia del usuario final con el logotipo y la mensajería personalizada.</span><span class="sxs-lookup"><span data-stu-id="4de3c-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="4de3c-253">Configurar la detección de nube para proporcionar una instantánea de IT mediante:</span><span class="sxs-lookup"><span data-stu-id="4de3c-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="4de3c-254">Microsoft Defender para puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="4de3c-255">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="4de3c-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="4de3c-256">iboss.</span><span class="sxs-lookup"><span data-stu-id="4de3c-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="4de3c-257">Conexión <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">de aplicaciones destacados</a> mediante conectores de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="4de3c-258">Configurar el control de aplicaciones de acceso condicional en los portales de Acceso condicional y Seguridad de aplicaciones en la nube para aplicar controles de sesión en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="4de3c-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="4de3c-259">Implementación de los paneles Cloud App Security y Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="4de3c-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="4de3c-260">Personalización de puntuaciones de riesgo de aplicaciones en función de las prioridades de su organización.</span><span class="sxs-lookup"><span data-stu-id="4de3c-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="4de3c-261">Crear etiquetas y categorías de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="4de3c-262">Sancionar y no autorizar aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="4de3c-263">Uso de los registros de actividad y archivo.</span><span class="sxs-lookup"><span data-stu-id="4de3c-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="4de3c-264">Administrar aplicaciones de OAuth.</span><span class="sxs-lookup"><span data-stu-id="4de3c-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="4de3c-265">Descripción de la correlación de incidentes en el portal de Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="4de3c-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="4de3c-266">Proporcionar asistencia de configuración con los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 casos</a> de uso principales para LAS CASB (incluida la creación o actualización de hasta seis (6) directivas), excepto:</span><span class="sxs-lookup"><span data-stu-id="4de3c-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="4de3c-267">Auditar la configuración de los entornos de Internet como servicio (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="4de3c-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="4de3c-268">Supervisar las actividades de los usuarios para protegerse contra amenazas en los entornos de IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="4de3c-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="4de3c-269"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="4de3c-270">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="4de3c-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="4de3c-271">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="4de3c-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="4de3c-272">Configurar la infraestructura, la instalación o la implementación de cargas automáticas de registros para informes continuos mediante Docker o un recopilador de registros.</span><span class="sxs-lookup"><span data-stu-id="4de3c-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="4de3c-273">Para obtener más información, vea los 20 primeros casos de uso <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">de las CASB.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="4de3c-274">Creación de un informe de instantáneas de detección de nube.</span><span class="sxs-lookup"><span data-stu-id="4de3c-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="4de3c-275">Bloquear el uso de la aplicación mediante scripts de bloqueo.</span><span class="sxs-lookup"><span data-stu-id="4de3c-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="4de3c-276">Conectar aplicaciones personalizadas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="4de3c-277">Integración con proveedores de identidades de terceros (ISP) y proveedores de prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="4de3c-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="4de3c-278">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="4de3c-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="4de3c-279">Investigación y corrección automatizadas, incluidas las guías de juegos de Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="4de3c-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="4de3c-280">Administración de eventos e información de seguridad (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="4de3c-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="4de3c-281">Implementar la detección de aplicaciones en la nube como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="4de3c-282"><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-283">La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="4de3c-284">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-285">Implementar las tecnologías para proteger los puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-286">Configurar perfiles de restricción de dispositivos y protección de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-287">Evaluar la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios av de Windows Defender u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-288">Evaluar el estado de los servicios antivirus de Windows u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-289">Evaluar servidores proxy y firewalls que restringen el tráfico de red.</span><span class="sxs-lookup"><span data-stu-id="4de3c-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-290">Habilitar el servicio ATP de Microsoft Defender explicando cómo implementar un perfil de agente de ATP con un punto de conexión incorporado.</span><span class="sxs-lookup"><span data-stu-id="4de3c-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-291">Instrucciones de implementación, asistencia de configuración y formación sobre:</span><span class="sxs-lookup"><span data-stu-id="4de3c-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-292">Administración de amenazas y vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="4de3c-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-293">Reducción de la superficie de ataque.</span><span class="sxs-lookup"><span data-stu-id="4de3c-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-294">Protección de nueva generación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-295">Detección y respuesta de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-296">Investigación y corrección automatizadas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-297">Puntuación de seguridad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-298">Revisar simulaciones y tutoriales (como escenarios de prácticas, malware falso e investigaciones automatizadas).</span><span class="sxs-lookup"><span data-stu-id="4de3c-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-299">Información general sobre las características de informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-300">Integrar Protección contra amenazas avanzadas de Office 365 con Protección contra amenazas avanzada de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="4de3c-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-301">Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="4de3c-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-302">Los siguientes sistemas operativos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-303">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-304">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="4de3c-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-305">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="4de3c-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-306">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="4de3c-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-307">Windows Server Semi-Annual Channel (SAC) versión 1803.</span><span class="sxs-lookup"><span data-stu-id="4de3c-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-308">macOS versiones 10.13, 10.14 y 10.15.</span><span class="sxs-lookup"><span data-stu-id="4de3c-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="4de3c-309">
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la última versión de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior).</span><span class="sxs-lookup"><span data-stu-id="4de3c-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="4de3c-310"></li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="4de3c-311">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="4de3c-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-312">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-313">Administración continua y respuesta ante amenazas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-314">Incorporación o configuración para los siguientes agentes de Protección contra amenazas avanzada de Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="4de3c-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-315">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="4de3c-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-316">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="4de3c-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-317">Linux.</span><span class="sxs-lookup"><span data-stu-id="4de3c-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-318">Dispositivos móviles (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="4de3c-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-319">Incorporación y configuración del servidor:</span><span class="sxs-lookup"><span data-stu-id="4de3c-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-320">Configurar un servidor proxy para las comunicaciones sin conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-321">Configurar paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.</span><span class="sxs-lookup"><span data-stu-id="4de3c-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-322">Incorporación de servidores al Centro de seguridad de Azure.</span><span class="sxs-lookup"><span data-stu-id="4de3c-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-323">Servidores no administrados por Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="4de3c-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-324">Configuración y incorporación de macOS:</span><span class="sxs-lookup"><span data-stu-id="4de3c-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-325">Implementación manual basada en Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-326">Implementación basada en JAMF.</span><span class="sxs-lookup"><span data-stu-id="4de3c-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="4de3c-327">Otra implementación basada en productos de administración de dispositivos móviles (MDM).</span><span class="sxs-lookup"><span data-stu-id="4de3c-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-328">Implementación manual.</span><span class="sxs-lookup"><span data-stu-id="4de3c-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-329">Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:</span><span class="sxs-lookup"><span data-stu-id="4de3c-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-330">Aislamiento basado en hardware.</span><span class="sxs-lookup"><span data-stu-id="4de3c-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-331">Control de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-332">Protección contra vulnerabilidades de seguridad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-333">Firewall de red.</span><span class="sxs-lookup"><span data-stu-id="4de3c-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-334">Inscripción o configuración de Expertos en amenazas de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="4de3c-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-335">Configuración o aprendizaje que revisa la API o las conexiones de administración de eventos e información de seguridad (SIEM).</span><span class="sxs-lookup"><span data-stu-id="4de3c-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-336">Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="4de3c-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-337">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="4de3c-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-338">Formación u orientación sobre el uso o la creación de consultas de Kusto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="4de3c-339">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="4de3c-340"><strong>Microsoft Defender para identidad </strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="4de3c-341">Microsoft Defender for Identity es una solución de seguridad basada en la nube que aprovecha las señales locales de Active Directory para identificar, detectar e investigar las amenazas avanzadas, las identidades vulnerables y las acciones internas malintencionadas dirigidas a su organización.</span><span class="sxs-lookup"><span data-stu-id="4de3c-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="4de3c-342">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="4de3c-343">Crear la instancia de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="4de3c-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="4de3c-344">Conectar Defender for Identity a Active Directory.</span><span class="sxs-lookup"><span data-stu-id="4de3c-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="4de3c-345">Evaluar la preparación del entorno para implementar el sensor Defender for Identity en los controladores de dominio, incluidos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="4de3c-346">Ejecución de la herramienta de tamaño para la planeación de la capacidad de los recursos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="4de3c-347">Ejecutar la herramienta de auditoría para evaluar la compatibilidad de los controladores de dominio con el sensor.</span><span class="sxs-lookup"><span data-stu-id="4de3c-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="4de3c-348">Implementar el sensor para capturar y analizar el tráfico de red y los eventos de Windows directamente desde los controladores de dominio, incluidos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="4de3c-349">Descargar el paquete del sensor.</span><span class="sxs-lookup"><span data-stu-id="4de3c-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="4de3c-350">Configurar el sensor.</span><span class="sxs-lookup"><span data-stu-id="4de3c-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="4de3c-351">Instalar el sensor en el controlador de dominio de forma silenciosa.</span><span class="sxs-lookup"><span data-stu-id="4de3c-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="4de3c-352">Implementar el sensor en el entorno de varios bosques.</span><span class="sxs-lookup"><span data-stu-id="4de3c-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="4de3c-353">Integración de Defender for Identity con Microsoft Cloud App Security (no se requiere licencia de Cloud App Security).</span><span class="sxs-lookup"><span data-stu-id="4de3c-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="4de3c-354">Proporcionar instrucciones de implementación, asistencia de configuración y formación sobre:</span><span class="sxs-lookup"><span data-stu-id="4de3c-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="4de3c-355">Ajuste del entorno para reducir el "ruido".</span><span class="sxs-lookup"><span data-stu-id="4de3c-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="4de3c-356">Descripción del informe de evaluación de la posición de seguridad de identidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="4de3c-357">Descripción de la puntuación de prioridad de investigación de usuario y el informe de clasificación de la investigación de usuarios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="4de3c-358">Descripción del informe de usuario inactivo.</span><span class="sxs-lookup"><span data-stu-id="4de3c-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="4de3c-359">Proporcionar opciones de corrección en una cuenta comprometida.</span><span class="sxs-lookup"><span data-stu-id="4de3c-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="4de3c-360">Facilitar la migración de Advanced Threat Analytics (ATA) a Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="4de3c-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="4de3c-361"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="4de3c-362">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="4de3c-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="4de3c-363">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="4de3c-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="4de3c-364">Implementar el sensor Defender for Identity, incluidos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="4de3c-365">Planeación manual de la capacidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="4de3c-366">Implementar el sensor en una capacidad independiente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="4de3c-367">Implementar el sensor mediante un adaptador de formación de equipos de tarjeta de interfaz de red (NIC).</span><span class="sxs-lookup"><span data-stu-id="4de3c-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="4de3c-368">Implementar el sensor a través de una herramienta de terceros.</span><span class="sxs-lookup"><span data-stu-id="4de3c-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="4de3c-369">Conectarse al servicio en la nube de Defender for Identity a través de una conexión de proxy web.</span><span class="sxs-lookup"><span data-stu-id="4de3c-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="4de3c-370">Creación y administración detokens detokens.</span><span class="sxs-lookup"><span data-stu-id="4de3c-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="4de3c-371">Guía de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="4de3c-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="4de3c-372">Corregir o interpretar varios tipos de alertas y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="4de3c-373">Investigar un usuario, equipo, ruta de movimiento lateral o entidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="4de3c-374">Amenaza o búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="4de3c-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="4de3c-375">Respuesta a incidentes.</span><span class="sxs-lookup"><span data-stu-id="4de3c-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="4de3c-376">Proporcionar un tutorial de laboratorio de alertas de seguridad para Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="4de3c-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="4de3c-377">Proporcionar una notificación cuando Defender para identidad detecta actividades sospechosas mediante el envío de alertas de seguridad a tu servidor de Vmm a través de un sensor designado.</span><span class="sxs-lookup"><span data-stu-id="4de3c-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="4de3c-378">Configurar Defender para Identity para realizar consultas mediante el protocolo de administrador de cuentas de seguridad remoto (SAMR) para identificar a los administradores locales en equipos específicos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="4de3c-379">Configurar soluciones VPN para agregar información de la conexión VPN a la página de perfil de un usuario.</span><span class="sxs-lookup"><span data-stu-id="4de3c-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="4de3c-380">Administración de eventos e información de seguridad (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="4de3c-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="4de3c-381">Implementar sensores de Defender for Identity como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="4de3c-382">Active Directory implementado.</span><span class="sxs-lookup"><span data-stu-id="4de3c-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-383">Los controladores de dominio en los que quieres instalar los sensores de Defender for Identity tienen conectividad a Internet con el servicio en la nube de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="4de3c-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="4de3c-384">El firewall y el proxy deben estar abiertos para comunicarse con el servicio en la nube de Defender for Identity (\*.atp.azure.com puerto 443 debe estar abierto).</span><span class="sxs-lookup"><span data-stu-id="4de3c-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="4de3c-385">Controladores de dominio que se ejecutan en una de las siguientes opciones:</span><span class="sxs-lookup"><span data-stu-id="4de3c-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="4de3c-386">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="4de3c-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="4de3c-387">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="4de3c-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="4de3c-388">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="4de3c-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="4de3c-389">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="4de3c-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="4de3c-390">Windows Server 2019 con KB4487044 (compilación del sistema operativo 17763.316).</span><span class="sxs-lookup"><span data-stu-id="4de3c-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="4de3c-391"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-392">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-393">Etiquetas y directivas de retención</span><span class="sxs-lookup"><span data-stu-id="4de3c-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-394">Administración de registros</span><span class="sxs-lookup"><span data-stu-id="4de3c-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-395">Directivas de eliminación</span><span class="sxs-lookup"><span data-stu-id="4de3c-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-396">Cumplimiento de comunicaciones</span><span class="sxs-lookup"><span data-stu-id="4de3c-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-397">Administración de riesgos internos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-398">eDiscovery avanzado</span><span class="sxs-lookup"><span data-stu-id="4de3c-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="4de3c-399">

  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="4de3c-400">Desarrollo de un plan de archivos de administración de registros.</span><span class="sxs-lookup"><span data-stu-id="4de3c-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="4de3c-401">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="4de3c-402">Barreras de información.</span><span class="sxs-lookup"><span data-stu-id="4de3c-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="4de3c-403">Administración de acceso con privilegios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="4de3c-404">Desarrollo de la arquitectura de la información en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="4de3c-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="4de3c-405">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="4de3c-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="4de3c-406">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="4de3c-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-407"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-408">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-409">Clasificación de los datos</span><span class="sxs-lookup"><span data-stu-id="4de3c-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-410">Tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="4de3c-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-411">Crear etiquetas de confidencialidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-412">Aplicar etiquetas de confidencialidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-413">Etiquetado unificado</span><span class="sxs-lookup"><span data-stu-id="4de3c-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-414">Clasificadores que se pueden entrenar.</span><span class="sxs-lookup"><span data-stu-id="4de3c-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-415">Conocer sus datos con el explorador de contenido y el explorador de actividades.</span><span class="sxs-lookup"><span data-stu-id="4de3c-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-416">Publicar etiquetas mediante las directivas (manual y automático).</span><span class="sxs-lookup"><span data-stu-id="4de3c-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-417">Crear directivas de protección de pérdida de datos (DLP) de los chats y canales de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="4de3c-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-418">Crear directivas DLP de punto de conexión para dispositivos Con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="4de3c-419">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="4de3c-420">Clave de cliente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-420">Customer key.</span></span></li>
<li><span data-ttu-id="4de3c-421">Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="4de3c-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="4de3c-422">Creación o modificación de diccionarios de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="4de3c-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="4de3c-423">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="4de3c-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="4de3c-424">
<strong>Nota:</strong> Para obtener más información, <strong>vea Azure Information Protection</strong> en Enterprise Mobility + <a href="#enterprise-mobility--security">Security.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="4de3c-425">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="4de3c-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-427">Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como el proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="4de3c-428">Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles.</span><span class="sxs-lookup"><span data-stu-id="4de3c-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="4de3c-429">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="4de3c-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-430">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="4de3c-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-431">Configurar identidades para que Intune las utilice mediante el uso de active directory local o identidades de nube (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="4de3c-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-432">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-433">Configurar la autoridad MDM, en función de tus necesidades de administración, incluidos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-434">Establecer Intune como entidad MDM cuando Intune es la única solución MDM.</span><span class="sxs-lookup"><span data-stu-id="4de3c-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-435">Proporcionar instrucciones de MDM para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-436">Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.</span><span class="sxs-lookup"><span data-stu-id="4de3c-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-437">Configurar servicios y directivas de administración de MDM como:</span><span class="sxs-lookup"><span data-stu-id="4de3c-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-438">Implementación de aplicaciones para cada plataforma compatible a través de vínculos web o vínculos profundos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-439">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="4de3c-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-440">Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tienes una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en tu organización.</span><span class="sxs-lookup"><span data-stu-id="4de3c-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-441">Conectarse al almacén de datos de Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-442">Integrar Intune con:</span><span class="sxs-lookup"><span data-stu-id="4de3c-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-443">Visor de equipo para asistencia remota (se requiere una suscripción al Visor de equipo).</span><span class="sxs-lookup"><span data-stu-id="4de3c-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-444">Soluciones de asociados de Mobile Threat Defense (MTD) (se requiere una suscripción mtd).</span><span class="sxs-lookup"><span data-stu-id="4de3c-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-445">Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción de solución de administración de gastos de telecomunicaciones).</span><span class="sxs-lookup"><span data-stu-id="4de3c-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="4de3c-446">Inscribir dispositivos de cada plataforma compatible en Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-446">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="4de3c-447">Proporcionar instrucciones de protección de aplicaciones sobre:</span><span class="sxs-lookup"><span data-stu-id="4de3c-447">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-448">Configurar directivas de protección de aplicaciones para cada plataforma compatible.</span><span class="sxs-lookup"><span data-stu-id="4de3c-448">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-449">Configuración de directivas de acceso condicional para aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-449">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-450">Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-450">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-451">Uso de informes de uso de aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-451">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-452">Proporcionar instrucciones de migración de la administración de equipos heredados a MDM de Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-452">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="4de3c-453">
 
</li>
</ul>
  
<strong>Conexión a la nube</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-453">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="4de3c-454">Le guiaremos a través de prepararse para adjuntar entornos de Configuration Manager existentes a la nube con Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-454">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="4de3c-455">Los pasos detallados dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="4de3c-455">The exact steps depend on your source environment.</span></span> <span data-ttu-id="4de3c-456">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="4de3c-456">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="4de3c-457">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="4de3c-457">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-458">Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="4de3c-458">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-459">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-459">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-460">Proporcionar instrucciones para configurar la unión híbrida a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-460">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-461">Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.</span><span class="sxs-lookup"><span data-stu-id="4de3c-461">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-462">Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.</span><span class="sxs-lookup"><span data-stu-id="4de3c-462">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-463">Configurar cargas de trabajo compatibles que quiera cambiar a Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-463">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-464">Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-464">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="4de3c-465"><strong>Implementar Outlook Mobile para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook Mobile para iOS y Android de forma segura en su organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.</span><span class="sxs-lookup"><span data-stu-id="4de3c-465"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="4de3c-466">Los pasos para implementar Outlook mobile para iOS y Android con Intune de forma segura dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="4de3c-466">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="4de3c-467">Puede incluir:</span><span class="sxs-lookup"><span data-stu-id="4de3c-467">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-468">Descargar las aplicaciones outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal a través de La App Store de Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="4de3c-468">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-469">Proporcionar instrucciones sobre la configuración:</span><span class="sxs-lookup"><span data-stu-id="4de3c-469">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-470">La implementación de aplicaciones de Outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal con Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-470">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-471">Directivas de protección de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-471">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-472">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="4de3c-472">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-473">Directivas de configuración de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-473">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="4de3c-474">Los administradores de TI deben tener infraestructuras existentes de entidad de certificación, red inalámbrica e VPN que ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-474">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="4de3c-475"><strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar las autoridades de certificados, las redes inalámbricas, las infraestructuras VPN o los certificados de inserción de MDM de Apple para Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-475"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="4de3c-476"><strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube.</span><span class="sxs-lookup"><span data-stu-id="4de3c-476"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="4de3c-477">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="4de3c-478"><strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-478"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="4de3c-479"><strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con ATP de Microsoft Defender y crear directivas de cumplimiento de dispositivos en función de su evaluación del nivel de riesgo de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-479"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="4de3c-480">No proporcionamos asistencia sobre la compra, la concesión de licencias o la activación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-480">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="4de3c-481">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="4de3c-482"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-482"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="4de3c-483">Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="4de3c-483">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="4de3c-484"><strong>Protección contra amenazas avanzada de Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-484"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-485">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-485">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-486">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="4de3c-486">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-487">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="4de3c-487">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-488">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="4de3c-488">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-489">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-489">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4de3c-490">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="4de3c-490">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="4de3c-491">Office 365</span><span class="sxs-lookup"><span data-stu-id="4de3c-491">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4de3c-492"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-492"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4de3c-493"><strong>Detalles de las instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-493"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4de3c-494"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-494"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4de3c-495"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-495"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-496">Para Exchange Online, le guiaremos a través del proceso para preparar a su organización para usar el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="4de3c-496">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="4de3c-497">Los pasos exactos dependen del entorno de origen y de los planes de migración de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="4de3c-497">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="4de3c-498">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-498">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-499">Configuración de las características de Exchange Online Protection (EOP) para todos los dominios habilitados para correo que se han validado en Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-499">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-500">Apuntar los registros de intercambio de correo (MX) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-500">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-501">Configurar la característica atp de Office 365 si forma parte de su servicio de suscripción.</span><span class="sxs-lookup"><span data-stu-id="4de3c-501">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="4de3c-502">Para obtener más información, vea la parte protección contra amenazas avanzada de <strong>Office 365</strong> de esta tabla.</span><span class="sxs-lookup"><span data-stu-id="4de3c-502">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-p126">Configuración de la característica de prevención de pérdida de datos (DLP) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="4de3c-p127">Configuración del cifrado de mensajes de Office 365 (OME) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="4de3c-507">
  <strong>Nota:</strong> El servicio de replicación de buzones (MRS) intenta migrar correos electrónicos de Information Rights Managed (IRM) desde su buzón local al buzón de Exchange Online correspondiente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-507">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="4de3c-508">La capacidad de leer el contenido protegido posterior a la migración dependerá de la asignación de clientes y la copia de las plantillas de Active Directory Rights Management Services (AD RMS) en el servicio Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="4de3c-508">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="4de3c-509">Configurar puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="4de3c-509">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-510">Configurar DNS, incluidos la detección automática, el marco de directivas de remitente (SPF), el correo identificado de DomainKeys (DKIM), la autenticación de mensajes basada en dominio, la creación de informes y la conformidad (DMARC) y los registros MX (según sea necesario).</span><span class="sxs-lookup"><span data-stu-id="4de3c-510">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-511">Configuración del flujo de correo electrónico entre su entorno de mensajería de origen y Exchange Online (si procede).</span><span class="sxs-lookup"><span data-stu-id="4de3c-511">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-512">Operación de migración de correo desde el entorno de mensajería de origen a Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-512">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-513">Configuración de clientes de buzón (Outlook para Windows, Outlook en la web y Outlook para iOS y Android).</span><span class="sxs-lookup"><span data-stu-id="4de3c-513">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="4de3c-514">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="4de3c-514">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="4de3c-515">Para obtener información sobre cómo usar las ventajas de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">Migración de datos.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-515">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="4de3c-516">El entorno de origen debe tener uno de los siguientes niveles mínimos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-516">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-517">Una o varias organizaciones de Exchange a partir de Exchange Server 2003.</span><span class="sxs-lookup"><span data-stu-id="4de3c-517">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-518">Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).</span><span class="sxs-lookup"><span data-stu-id="4de3c-518">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-519">Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="4de3c-519">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-520">Para obtener información sobre las capacidades multige geográficas, consulte <a href="https://go.microsoft.com/fwlink/?linkid=872776">Capacidades multigeómicas en Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-520">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="4de3c-521">El software cliente en línea como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, el cliente de sincronización de OneDrive para la Empresa, Power BI Desktop y Skype Empresarial deben estar en un nivel mínimo como se define en los requisitos del sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-521">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-522"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-522"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-523">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-523">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-524">Etiquetas y directivas de retención</span><span class="sxs-lookup"><span data-stu-id="4de3c-524">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-525">Administración de registros</span><span class="sxs-lookup"><span data-stu-id="4de3c-525">Records management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-526">Directivas de eliminación</span><span class="sxs-lookup"><span data-stu-id="4de3c-526">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-527">Cumplimiento de comunicaciones</span><span class="sxs-lookup"><span data-stu-id="4de3c-527">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-528">Administración de riesgos internos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-528">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-529">eDiscovery avanzado</span><span class="sxs-lookup"><span data-stu-id="4de3c-529">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="4de3c-530">

  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-530">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="4de3c-531">Desarrollo de un plan de archivos de administración de registros.</span><span class="sxs-lookup"><span data-stu-id="4de3c-531">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="4de3c-532">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-532">Data connectors.</span></span></li>
<li> <span data-ttu-id="4de3c-533">Barreras de información.</span><span class="sxs-lookup"><span data-stu-id="4de3c-533">Information barriers.</span></span></li>
<li> <span data-ttu-id="4de3c-534">Administración de acceso con privilegios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-534">Privileged access management.</span></span></li>
<li> <span data-ttu-id="4de3c-535">Desarrollo de la arquitectura de la información en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="4de3c-535">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="4de3c-536">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="4de3c-536">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="4de3c-537">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="4de3c-537">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-538"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-538"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-539">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-539">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-540">Clasificación de los datos</span><span class="sxs-lookup"><span data-stu-id="4de3c-540">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-541">Tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="4de3c-541">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-542">Crear etiquetas de confidencialidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-542">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-543">Aplicar etiquetas de confidencialidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-543">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-544">Etiquetado unificado</span><span class="sxs-lookup"><span data-stu-id="4de3c-544">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-545">Clasificadores que se pueden entrenar.</span><span class="sxs-lookup"><span data-stu-id="4de3c-545">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-546">Conocer sus datos con el explorador de contenido y el explorador de actividades.</span><span class="sxs-lookup"><span data-stu-id="4de3c-546">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-547">Publicar etiquetas mediante las directivas (manual y automático).</span><span class="sxs-lookup"><span data-stu-id="4de3c-547">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-548">Crear directivas de protección de pérdida de datos (DLP) de los chats y canales de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="4de3c-548">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-549">Crear directivas DLP de punto de conexión para dispositivos Con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-549">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="4de3c-550">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-550">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="4de3c-551">Clave de cliente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-551">Customer key.</span></span></li>
<li><span data-ttu-id="4de3c-552">Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="4de3c-552">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="4de3c-553">Creación o modificación de diccionarios de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="4de3c-553">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="4de3c-554">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="4de3c-554">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="4de3c-555">
<strong>Nota:</strong> Para obtener más información, <strong>vea Azure Information Protection</strong> en Enterprise Mobility + <a href="#enterprise-mobility--security">Security.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-555">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="4de3c-556">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="4de3c-556">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-557"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-557"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-558">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-558">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-559">Confirmar los requisitos mínimos en Exchange Online, SharePoint Online, Grupos de Office 365 y Azure AD para admitir Teams.</span><span class="sxs-lookup"><span data-stu-id="4de3c-559">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-560">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="4de3c-560">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-561">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="4de3c-561">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-562">Confirmar que se ha habilitado Teams en su espacio empresarial de Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-562">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-563">Habilitar o deshabilitar licencias de usuario.</span><span class="sxs-lookup"><span data-stu-id="4de3c-563">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-564">Evaluación de red para Teams:</span><span class="sxs-lookup"><span data-stu-id="4de3c-564">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-565">Comprobaciones de puertos y puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-565">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-566">Comprobaciones de calidad de la conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-566">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-567">Estimaciones de ancho de banda.</span><span class="sxs-lookup"><span data-stu-id="4de3c-567">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="4de3c-568">Configuración de la directiva de aplicación de Teams (aplicación web de Teams, aplicación de escritorio de Teams y teams para aplicaciones de iOS y Android).</span><span class="sxs-lookup"><span data-stu-id="4de3c-568">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="4de3c-569">Si procede, también proporcionamos instrucciones para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-569">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-570">Dispositivos de sala de Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="4de3c-570">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="4de3c-571">Creación de cuentas en línea necesarias para los dispositivos de telefonía y salas de conferencias compatibles que aparecen en el <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos de Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="4de3c-571">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-572">Asistencia remota con la configuración del lado del servicio de dispositivos de salas de Microsoft Teams certificados.</span><span class="sxs-lookup"><span data-stu-id="4de3c-572">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-573">Habilitar audioconferencia:</span><span class="sxs-lookup"><span data-stu-id="4de3c-573">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="4de3c-574">Parámetros predeterminados de la configuración de la organización para puente de conferencia.</span><span class="sxs-lookup"><span data-stu-id="4de3c-574">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-575">Asignación de un puente de conferencia a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="4de3c-575">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="4de3c-576">Sistema telefónico:</span><span class="sxs-lookup"><span data-stu-id="4de3c-576">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-577">Configuración de la organización para los parámetros predeterminados de voz en la nube.</span><span class="sxs-lookup"><span data-stu-id="4de3c-577">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-578">Guía de planes de llamadas (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponibles):</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-578">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-579">Asignación de números a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="4de3c-579">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-580">Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.</span><span class="sxs-lookup"><span data-stu-id="4de3c-580">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-581">Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.</span><span class="sxs-lookup"><span data-stu-id="4de3c-581">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-582">Guía de enrutamiento directo:</span><span class="sxs-lookup"><span data-stu-id="4de3c-582">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-583">Guía de configuración de la organización para el diseño de enrutamiento directo de escenarios hospedados por asociados o escenarios implementados por el cliente para un máximo de 10 sitios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-583">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="4de3c-584">Revisión de configuración del controlador de borde de sesión (SBC).</span><span class="sxs-lookup"><span data-stu-id="4de3c-584">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="4de3c-585">Asistencia remota con la configuración del plan de marcado.</span><span class="sxs-lookup"><span data-stu-id="4de3c-585">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="4de3c-586">Configuración de ruta de voz.</span><span class="sxs-lookup"><span data-stu-id="4de3c-586">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="4de3c-587">Desvío de medios y optimización de medios locales.</span><span class="sxs-lookup"><span data-stu-id="4de3c-587">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="4de3c-588">Habilitar eventos en directo en Teams</span><span class="sxs-lookup"><span data-stu-id="4de3c-588">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-589">Configuración e integración de la organización en Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="4de3c-589">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-590">Guía para la transición de Skype Empresarial a Teams.</span><span class="sxs-lookup"><span data-stu-id="4de3c-590">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="4de3c-591">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-591">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-592">Usuarios habilitados para SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="4de3c-592">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-593">Los buzones de Exchange están presentes (en línea y local en una configuración híbrida de Exchange).</span><span class="sxs-lookup"><span data-stu-id="4de3c-593">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-594">Habilitado para Grupos de Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-594">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="4de3c-595">
  <strong>Nota:</strong> Si los usuarios no están asignados ni habilitados con licencias de SharePoint Online, no tendrán almacenamiento de OneDrive para la Empresa en Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-595">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="4de3c-596">El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin el almacenamiento de OneDrive para la Empresa en Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-596">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="4de3c-597">Teams no admite SharePoint local.</span><span class="sxs-lookup"><span data-stu-id="4de3c-597">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="4de3c-598">
  <strong>Nota:</strong> El estado ideal es que todos los usuarios tengan sus buzones de correo en Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4de3c-598">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="4de3c-599">Los usuarios con buzones de correo locales deben tener sus identidades sincronizadas con el directorio de Office 365 a través de Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="4de3c-599">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="4de3c-600">Para estos clientes híbridos de Exchange, si el buzón del usuario es local, el usuario no puede agregar ni configurar conectores.</span><span class="sxs-lookup"><span data-stu-id="4de3c-600">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="4de3c-601">Los instaladores para los clientes de escritorio de Mac y Windows en Microsoft Teams se pueden descargar de <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="4de3c-601">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-602"><strong>Protección contra amenazas avanzada de Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-602"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-603">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-603">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-604">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="4de3c-604">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-605">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="4de3c-605">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-606">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="4de3c-606">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-607">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-607">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4de3c-608">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="4de3c-608">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-609"><strong>Outlook para iOS y Android</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-609"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-610">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-610">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-611">Descargar Outlook para iOS y Android desde la App Store de Apple y Google Play.</span><span class="sxs-lookup"><span data-stu-id="4de3c-611">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-612">Configurar cuentas y acceder al buzón de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4de3c-612">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-613">Protección de Outlook mobile (vea <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Protección de Outlook para iOS y Android en Exchange Online</a> para obtener más información).</span><span class="sxs-lookup"><span data-stu-id="4de3c-613">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="4de3c-614">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-614">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-615">Exchange Online configurado y licencias asignadas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-615">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-616"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-616"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-617">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-617">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-618">Asignación de licencias de Power BI.</span><span class="sxs-lookup"><span data-stu-id="4de3c-618">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-619">Implementación de la aplicación Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="4de3c-619">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4de3c-620">El software cliente en línea, como Power BI Desktop, debe estar en un nivel mínimo como se define en los requisitos del sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 y Office.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-620">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-621"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-621"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-622">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-622">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-623">Comprobación de la funcionalidad básica de SharePoint que se basa en Project Online.</span><span class="sxs-lookup"><span data-stu-id="4de3c-623">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-624">Adición del servicio de Project Online al espacio empresarial (incluida la adición de las suscripciones a los usuarios).</span><span class="sxs-lookup"><span data-stu-id="4de3c-624">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-625">Configuración del grupo de recursos de empresa (ERP).</span><span class="sxs-lookup"><span data-stu-id="4de3c-625">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-626">Creación del primer proyecto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-626">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4de3c-627">El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 y Office.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-627">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-628"><strong>Project Online Professional y Premium</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-628"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-629">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-629">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-630">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-630">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-631">Asignar licencias de usuario final mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="4de3c-631">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-632">Instalar Cliente de escritorio de Project Online desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="4de3c-632">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-633">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-633">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-634">Configurar un servidor de distribución in situ único para Cliente de escritorio de Project Online, incluida la ayuda para crear un archivo configuration.xml para usarlo con la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-634">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-635">Conectar Cliente de escritorio de Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="4de3c-635">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4de3c-636">El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 y Office.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-636">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-637"><strong>SharePoint Online y OneDrive para la Empresa</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-637"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-638">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-638">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-639">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="4de3c-639">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-640">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="4de3c-640">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-641">Aprovisionamiento de usuarios y licencias.</span><span class="sxs-lookup"><span data-stu-id="4de3c-641">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="4de3c-642">Habilitar la creación de sitios para el administrador de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="4de3c-642">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="4de3c-643">Planificar las colecciones de sitios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-643">Planning site collections.</span></span></li>
<li><span data-ttu-id="4de3c-644">Proteger el contenido y administrar los permisos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-644">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="4de3c-645">Configurar las características de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="4de3c-645">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="4de3c-646">Configuración de las características de Entorno híbrido de SharePoint, como la búsqueda híbrida, los sitios híbridos, la taxonomía híbrida, los tipos de contenido, la creación híbrida de sitios sin intervención del administrador (solo SharePoint Server 2013), el iniciador de aplicaciones extendido, OneDrive para la Empresa híbrido y los sitios de extranet.</span><span class="sxs-lookup"><span data-stu-id="4de3c-646">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-647">El enfoque de migración.</span><span class="sxs-lookup"><span data-stu-id="4de3c-647">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="4de3c-648">Se proporcionan instrucciones adicionales para OneDrive para la Empresa en función de su versión de SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="4de3c-648">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-649">Identificar las opciones de integración y revisar el ancho de banda y la infraestructura de red local y en línea.</span><span class="sxs-lookup"><span data-stu-id="4de3c-649">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-650">Instalar SharePoint Online 2013 SP1 (si corresponde), planear e implementar requisitos de sincronización e identidad, e identificar el cliente de sincronización de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="4de3c-650">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-651">Planeación e implementación de una única implementación para todos los usuarios (o una implementación por fases).</span><span class="sxs-lookup"><span data-stu-id="4de3c-651">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-652">Asignar licencias, redirigir Mis sitios y bibliotecas de documentos personales a Office 365 (aplicable a SharePoint Online 2013), configurar audiencias para controlar el acceso a OneDrive (aplicable a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="4de3c-652">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="4de3c-653">Redirigir o mover carpetas conocidas a OneDrive.</span><span class="sxs-lookup"><span data-stu-id="4de3c-653">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="4de3c-654">Implementación de la sincronización de cliente de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="4de3c-654">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="4de3c-655">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="4de3c-655">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="4de3c-656">Para obtener información sobre cómo usar las ventajas de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">Migración de datos.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-656">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="4de3c-657"><strong>Para entornos híbridos de SharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-657"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="4de3c-658">La configuración híbrida de SharePoint incluye la configuración de búsqueda híbrida, sitios, taxonomía, tipos de contenido, OneDrive para la Empresa, un iniciador de aplicaciones extendido, sitios de extranet y creación de sitios sin administrador conectados desde local a un entorno de SharePoint Online de destino único.</span><span class="sxs-lookup"><span data-stu-id="4de3c-658">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="4de3c-659">
  <strong>Nota:</strong> La creación de sitios sin administrador no está en el ámbito de los servidores locales que ejecutan SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="4de3c-659">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="4de3c-660">Para habilitar SharePoint híbrido, debe tener uno de los siguientes entornos locales de SharePoint Server: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="4de3c-660">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="4de3c-661">
  <strong>Nota:</strong> La actualización de entornos de SharePoint locales a SharePoint Server no está en el ámbito.</span><span class="sxs-lookup"><span data-stu-id="4de3c-661">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="4de3c-662">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="4de3c-662">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="4de3c-663">Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">Niveles mínimos de actualización pública para características híbridas de SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="4de3c-663">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="4de3c-664">
  <strong>Nota:</strong> Para obtener información sobre las capacidades multige geográficas, vea Capacidades multigeómicas en <a href="https://go.microsoft.com/fwlink/?linkid=831056">OneDrive y SharePoint Online en Office 365.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="4de3c-664">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-665"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-665"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="4de3c-666">Proporcionamos instrucciones remotas para habilitar el servicio Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="4de3c-666">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="4de3c-667">El software cliente en línea debe estar en un nivel mínimo como se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-667">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="4de3c-668">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="4de3c-668">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4de3c-669"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-669"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4de3c-670"><strong>Detalles de las instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-670"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4de3c-671"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-671"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="4de3c-672"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-672"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-673">Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-673">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="4de3c-674">

<strong>Infraestructura de base segura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="4de3c-674">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="4de3c-675">Configurar y habilitar la autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el autoservicio de restablecimiento de contraseña (SSPR).</span><span class="sxs-lookup"><span data-stu-id="4de3c-675">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-676">Para los clientes que no son de Azure AD Premium, se proporcionan instrucciones para proteger las identidades con valores predeterminados de seguridad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-676">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-677">Para los clientes de Azure AD Premium, se proporcionan instrucciones para proteger las identidades con acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="4de3c-677">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-678">Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-678">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-679">Proteger el acceso remoto a las aplicaciones web locales con el Proxy de aplicación de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-679">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-680">Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-680">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-681">Habilitar una pantalla de inicio de sesión personalizada, incluido el logotipo, el texto y las imágenes con la personalización de marca.</span><span class="sxs-lookup"><span data-stu-id="4de3c-681">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-682">Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="4de3c-682">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-683">Administrar el acceso de los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-683">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-684">Configurar la unión híbrida a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-684">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-685">Configurar la unión a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-685">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="4de3c-686">
  
<strong>Supervisión e informes</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-686">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-687">Habilitar la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="4de3c-687">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="4de3c-688">
  
<strong>Gobierno</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-688">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-689">Administrar el ciclo de vida de acceso e identidad de Azure AD a escala con la administración de derechos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-689">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="4de3c-690">Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-690">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-691">Revisar los Términos de uso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-691">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-692">Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="4de3c-692">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="4de3c-693">
  
<strong>Automatización y eficiencia </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-693">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-694">Habilitar SSPR de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-694">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="4de3c-695">Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos de Office 365 con la administración de grupos de autoservicio de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-695">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-696">Administrar el acceso delegado a las aplicaciones empresariales con la administración de grupos delegada de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-696">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-697">Habilitar grupos dinámicos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-697">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-698">Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-698">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="4de3c-699">Active Directory local y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="4de3c-699">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="4de3c-700"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-700"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="4de3c-701">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-701">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-702">Activar y configurar el espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="4de3c-702">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-703">Crear y configurar etiquetas y directivas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-703">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-704">Aplicar la protección de la información a documentos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-704">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-705">Clasificar y etiquetar automáticamente la información de las aplicaciones de Office (como Word, PowerPoint, Excel y Outlook), que se ejecutan en Windows y usan el cliente de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-705">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-706">Descubrir y etiquetar archivos en reposo con el escáner de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-706">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-707">Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4de3c-707">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="4de3c-708">También proporcionamos instrucciones si desea aplicar protección con Microsoft Azure Rights Management Services (Azure RMS), cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="4de3c-708">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="4de3c-709">Las responsabilidades de requisitos previos del cliente incluyen:</span><span class="sxs-lookup"><span data-stu-id="4de3c-709">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-710">Una lista de ubicaciones de recurso compartido de archivos que se examinarán.</span><span class="sxs-lookup"><span data-stu-id="4de3c-710">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-711">Taxonomía de clasificación aprobada.</span><span class="sxs-lookup"><span data-stu-id="4de3c-711">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="4de3c-712">Descripción de cualquier restricción normativa o requisitos relacionados con la administración de claves.</span><span class="sxs-lookup"><span data-stu-id="4de3c-712">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-713">Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-713">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="4de3c-714">Etiquetas configuradas para clasificación y protección.</span><span class="sxs-lookup"><span data-stu-id="4de3c-714">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="4de3c-715">Todos los requisitos previos para el escáner de Azure Information Protection están en su lugar.</span><span class="sxs-lookup"><span data-stu-id="4de3c-715">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="4de3c-716">Para obtener más información, vea <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Requisitos previos para</a>instalar e implementar el escáner de etiquetado unificado de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="4de3c-716">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="4de3c-717">Asegúrese de que los dispositivos de usuario ejecutan un sistema operativo compatible y tienen instalados los requisitos previos necesarios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-717">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="4de3c-718">Vea lo siguiente para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="4de3c-718">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="4de3c-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: Instalar el cliente de etiquetado unificado de Azure Information Protection para los usuarios</a>   </span><span class="sxs-lookup"><span data-stu-id="4de3c-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="4de3c-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="4de3c-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="4de3c-721">Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para la compatibilidad híbrida.</span><span class="sxs-lookup"><span data-stu-id="4de3c-721">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="4de3c-722">El programa de instalación y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado únicamente) o Hold Your Own Key (HYOK) (solo cliente clásico) debe requerir una de estas opciones para la implementación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-722">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="4de3c-723"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-723"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-724">Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como el proveedor de administración de dispositivos móviles (MDM) y administración de aplicaciones móviles (MAM) basado en la nube para sus aplicaciones y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-724">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="4de3c-725">Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles.</span><span class="sxs-lookup"><span data-stu-id="4de3c-725">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="4de3c-726">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="4de3c-726">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-727">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="4de3c-727">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-728">Configurar las identidades que va a usar Intune aprovechando active directory local o identidades de nube (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="4de3c-728">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-729">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-729">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-730">Configurar la autoridad MDM, en función de tus necesidades de administración, incluidos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-730">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-731">Establecer Intune como entidad MDM cuando Intune es la única solución MDM.</span><span class="sxs-lookup"><span data-stu-id="4de3c-731">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-732">Proporcionar instrucciones de MDM para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-732">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-733">Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.</span><span class="sxs-lookup"><span data-stu-id="4de3c-733">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-734">Configurar servicios y directivas de administración de MDM como:</span><span class="sxs-lookup"><span data-stu-id="4de3c-734">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-735">Implementación de aplicaciones para cada plataforma compatible a través de vínculos web o vínculos profundos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-735">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-736">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="4de3c-736">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-737">Implementación de correo electrónico, redes inalámbricas y perfiles de VPN si tienes una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en tu organización.</span><span class="sxs-lookup"><span data-stu-id="4de3c-737">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-738">Conectarse al almacén de datos de Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-738">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-739">Integrar Intune con:</span><span class="sxs-lookup"><span data-stu-id="4de3c-739">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-740">Visor de equipo para asistencia remota (se requiere una suscripción al Visor de equipo).</span><span class="sxs-lookup"><span data-stu-id="4de3c-740">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-741">Soluciones de asociados de Mobile Threat Defense (MTD) (se requiere una suscripción mtd).</span><span class="sxs-lookup"><span data-stu-id="4de3c-741">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-742">Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción de solución de administración de gastos de telecomunicaciones).</span><span class="sxs-lookup"><span data-stu-id="4de3c-742">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-743">Inscribir dispositivos de cada plataforma compatible en Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-743">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="4de3c-744">Proporcionar instrucciones de protección de aplicaciones sobre:</span><span class="sxs-lookup"><span data-stu-id="4de3c-744">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-745">Configurar directivas de protección de aplicaciones para cada plataforma compatible.</span><span class="sxs-lookup"><span data-stu-id="4de3c-745">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-746">Configuración de directivas de acceso condicional para aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-746">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-747">Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-747">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-748">Uso de informes de uso de aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-748">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-749">Proporcionar instrucciones de migración de la administración de equipos heredados a MDM de Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-749">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="4de3c-750">
  
</li>
</ul>
  
<strong>Conexión a la nube</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-750">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="4de3c-751">Le guiaremos a través de prepararse para adjuntar entornos de Configuration Manager existentes a la nube con Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-751">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="4de3c-752">Los pasos detallados dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="4de3c-752">The exact steps depend on your source environment.</span></span> <span data-ttu-id="4de3c-753">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="4de3c-753">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="4de3c-754">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="4de3c-754">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-755">Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="4de3c-755">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-756">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="4de3c-756">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-757">Proporcionar instrucciones para configurar la unión híbrida a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="4de3c-757">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-758">Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.</span><span class="sxs-lookup"><span data-stu-id="4de3c-758">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-759">Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.</span><span class="sxs-lookup"><span data-stu-id="4de3c-759">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-760">Configurar cargas de trabajo compatibles que quiera cambiar a Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-760">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-761">Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-761">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="4de3c-762"><strong>Implementar Outlook Mobile para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook Mobile para iOS y Android de forma segura en su organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.</span><span class="sxs-lookup"><span data-stu-id="4de3c-762"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="4de3c-763">Los pasos para implementar Outlook mobile para iOS y Android con Intune de forma segura dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="4de3c-763">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="4de3c-764">Puede incluir:</span><span class="sxs-lookup"><span data-stu-id="4de3c-764">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-765">Descargar las aplicaciones outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal a través de La App Store de Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="4de3c-765">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-766">Proporcionar instrucciones sobre la configuración:</span><span class="sxs-lookup"><span data-stu-id="4de3c-766">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-767">La implementación de aplicaciones de Outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal con Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-767">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-768">Directivas de protección de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-768">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-769">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="4de3c-769">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-770">Directivas de configuración de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-770">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="4de3c-771">Los administradores de TI deben tener infraestructuras existentes de entidad de certificación, redes inalámbricas e VPN que ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-771">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="4de3c-772"><strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar las autoridades de certificados, las redes inalámbricas, las infraestructuras VPN o los certificados de inserción de MDM de Apple para Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-772"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="4de3c-773"><strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube.</span><span class="sxs-lookup"><span data-stu-id="4de3c-773"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="4de3c-774">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-774">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="4de3c-775"><strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-775"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="4de3c-776"><strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con ATP de Microsoft Defender y crear directivas de cumplimiento de dispositivos en función de su evaluación del nivel de riesgo de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-776"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="4de3c-777">No proporcionamos asistencia sobre la compra, la concesión de licencias o la activación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-777">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="4de3c-778">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="4de3c-779"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-779"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="4de3c-780">Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="4de3c-780">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="4de3c-781">Windows 10</span><span class="sxs-lookup"><span data-stu-id="4de3c-781">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4de3c-782"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-782"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4de3c-783"><strong>Detalles de las instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-783"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4de3c-784"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-784"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4de3c-785"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-785"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-786">Proporcionamos instrucciones para actualizar de Windows 7 Professional y Windows 8.1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="4de3c-786">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="4de3c-787">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-787">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-788">Comprender la intención de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-788">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-789">Evaluar el entorno de origen y los requisitos (asegúrate de que Microsoft Endpoint Configuration Manager se actualiza al nivel requerido para admitir la implementación de Windows 10).</span><span class="sxs-lookup"><span data-stu-id="4de3c-789">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-790">Implementar Windows 10 Enterprise y Aplicaciones de Microsoft 365 con Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-790">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-791">Te recomendamos opciones para evaluar las aplicaciones de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-791">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-792">Habilitación del uso de Análisis de escritorio y orientación mediante la creación de un plan de implementación de Análisis de escritorio.</span><span class="sxs-lookup"><span data-stu-id="4de3c-792">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-793">Evaluación de compatibilidad de aplicaciones de Microsoft 365 aprovechando el panel de preparación de Office 365 en Configuration Manager o con readiness toolkit independiente para Office, además de asistencia para implementar aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-793">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-794">Crear una lista de comprobación de corrección sobre lo que necesita hacer para que el entorno de origen se asemeja a los requisitos mínimos para una implementación correcta.</span><span class="sxs-lookup"><span data-stu-id="4de3c-794">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-795">Proporcionar instrucciones de actualización para los dispositivos existentes a Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesarios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-795">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-796">Proporcionar instrucciones de actualización para admitir el movimiento de implementación existente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-796">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="4de3c-797">FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-797">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="4de3c-798">Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="4de3c-798">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-799">Implementar Aplicaciones de Microsoft 365 con Configuration Manager como parte de la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-799">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="4de3c-800">Proporcionar instrucciones para ayudar a su organización a mantenerse al día con Windows 10 Enterprise y aplicaciones de Microsoft 365 con su entorno de Configuration Manager existente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-800">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="4de3c-801">
  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-801">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="4de3c-802">Actualizar Configuration Manager a la rama actual.</span><span class="sxs-lookup"><span data-stu-id="4de3c-802">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-803">Crear imágenes personalizadas para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-803">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-804">Crear y admitir scripts de implementación para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-804">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-805">Convertir un sistema Windows 10 del BIOS a la Interfaz de firmware extensible unificado (UEFI).</span><span class="sxs-lookup"><span data-stu-id="4de3c-805">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-806">Habilitar las características de seguridad de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-806">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-807">Configurar los Servicios de implementación de Windows (WDS) para el arranque del Entorno de ejecución previo al inicio (PXE).</span><span class="sxs-lookup"><span data-stu-id="4de3c-807">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-808">Usar Microsoft Deployment Toolkit (MDT) para capturar e implementar imágenes de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-808">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-809">Usar la Herramienta de migración de estado de usuario (USMT).</span><span class="sxs-lookup"><span data-stu-id="4de3c-809">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="4de3c-810">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-810">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="4de3c-811">Para actualizar su PC, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-811">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-812">Sistema operativo de origen: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="4de3c-812">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-813">Dispositivos: factor de forma de escritorio, bloc de notas o tableta.</span><span class="sxs-lookup"><span data-stu-id="4de3c-813">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-814">Sistema operativo de destino: Ventana 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="4de3c-814">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="4de3c-815">Para actualizar la infraestructura, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-815">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-816">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="4de3c-816">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-817">La versión de Configuration Manager debe ser compatible con la versión de destino de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-817">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="4de3c-818">Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Soporte para Windows 10 en Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="4de3c-818">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="4de3c-819"><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-819"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-820">La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-820">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="4de3c-821">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-821">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-822">Implementar las tecnologías para proteger los puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-822">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-823">Configurar perfiles de restricción de dispositivos y protección de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-823">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-824">Evaluar la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios av de Windows Defender u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-824">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-825">Evaluar el estado de los servicios antivirus de Windows u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-825">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-826">Evaluar servidores proxy y firewalls que restringen el tráfico de red.</span><span class="sxs-lookup"><span data-stu-id="4de3c-826">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-827">Habilitar el servicio ATP de Microsoft Defender explicando cómo implementar un perfil de agente de ATP con un punto de conexión incorporado.</span><span class="sxs-lookup"><span data-stu-id="4de3c-827">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-828">Instrucciones de implementación, asistencia de configuración y formación sobre:</span><span class="sxs-lookup"><span data-stu-id="4de3c-828">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-829">Administración de amenazas y vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="4de3c-829">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-830">Reducción de la superficie de ataque.</span><span class="sxs-lookup"><span data-stu-id="4de3c-830">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-831">Protección de nueva generación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-831">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-832">Detección y respuesta de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-832">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-833">Investigación y corrección automatizadas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-833">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="4de3c-834">ATP de Microsoft Defender (se requieren licencias de Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="4de3c-834">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="4de3c-835">Puntuación de seguridad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-835">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-836">Revisar simulaciones y tutoriales (como escenarios de prácticas, malware falso e investigaciones automatizadas).</span><span class="sxs-lookup"><span data-stu-id="4de3c-836">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-837">Información general sobre las características de informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-837">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-838">Integrar Protección contra amenazas avanzadas de Office 365 con Protección contra amenazas avanzada de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="4de3c-838">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-839">Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="4de3c-839">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-840">Los siguientes sistemas operativos:</span><span class="sxs-lookup"><span data-stu-id="4de3c-840">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-841">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="4de3c-841">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-842">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="4de3c-842">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-843">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="4de3c-843">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-844">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="4de3c-844">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-845">Windows Server Semi-Annual Channel (SAC) versión 1803.</span><span class="sxs-lookup"><span data-stu-id="4de3c-845">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-846">macOS versiones 10.13, 10.14 y 10.15.</span><span class="sxs-lookup"><span data-stu-id="4de3c-846">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="4de3c-847">
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la última versión de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior).</span><span class="sxs-lookup"><span data-stu-id="4de3c-847">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="4de3c-848"></li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-848"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="4de3c-849">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="4de3c-849">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-850">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-850">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-851">Administración continua y respuesta ante amenazas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-851">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-852">Incorporación o configuración para los siguientes agentes de Protección contra amenazas avanzada de Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="4de3c-852">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-853">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="4de3c-853">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-854">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="4de3c-854">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-855">Linux.</span><span class="sxs-lookup"><span data-stu-id="4de3c-855">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-856">Dispositivos móviles (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="4de3c-856">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-857">Configuración y incorporación de servidores:</span><span class="sxs-lookup"><span data-stu-id="4de3c-857">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-858">Configurar un servidor proxy para las comunicaciones sin conexión.</span><span class="sxs-lookup"><span data-stu-id="4de3c-858">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-859">Configurar paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.</span><span class="sxs-lookup"><span data-stu-id="4de3c-859">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-860">Incorporación de servidores al Centro de seguridad de Azure.</span><span class="sxs-lookup"><span data-stu-id="4de3c-860">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-861">Servidores no administrados por Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="4de3c-861">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-862">Configuración y incorporación de macOS:</span><span class="sxs-lookup"><span data-stu-id="4de3c-862">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-863">Implementación manual basada en Intune.</span><span class="sxs-lookup"><span data-stu-id="4de3c-863">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-864">Implementación basada en JAMF.</span><span class="sxs-lookup"><span data-stu-id="4de3c-864">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="4de3c-865">Otra implementación basada en productos de administración de dispositivos móviles (MDM).</span><span class="sxs-lookup"><span data-stu-id="4de3c-865">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-866">Implementación manual.</span><span class="sxs-lookup"><span data-stu-id="4de3c-866">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-867">Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:</span><span class="sxs-lookup"><span data-stu-id="4de3c-867">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-868">Aislamiento basado en hardware.</span><span class="sxs-lookup"><span data-stu-id="4de3c-868">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-869">Control de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-869">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-870">Protección contra vulnerabilidades de seguridad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-870">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-871">Firewall de red.</span><span class="sxs-lookup"><span data-stu-id="4de3c-871">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="4de3c-872">Inscripción o configuración de Expertos en amenazas de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="4de3c-872">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-873">Configuración o aprendizaje que revisa la API o las conexiones de administración de eventos e información de seguridad (SIEM).</span><span class="sxs-lookup"><span data-stu-id="4de3c-873">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-874">Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="4de3c-874">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-875">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="4de3c-875">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-876">Formación u orientación sobre el uso o la creación de consultas kusto.</span><span class="sxs-lookup"><span data-stu-id="4de3c-876">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="4de3c-877">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="4de3c-878">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="4de3c-878">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4de3c-879"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-879"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4de3c-880"><strong>Detalles de las instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-880"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4de3c-881"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-881"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="4de3c-882"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-882"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="4de3c-883">Proporcionamos instrucciones de implementación para la incorporación a Windows Virtual Desktop (un servicio de virtualización de aplicaciones y escritorio).</span><span class="sxs-lookup"><span data-stu-id="4de3c-883">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="4de3c-884">Windows Virtual Desktop aprovecha las ventajas de la experiencia de varias sesiones de Windows 10 y está optimizado para Aplicaciones de Microsoft 365 para empresas con seguridad y administración integradas para Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-884">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="4de3c-885">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="4de3c-885">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="4de3c-886">Implementar el entorno de Windows Virtual Desktop con varias sesiones de Windows 10 Enterprise y Aplicaciones de Microsoft 365 para empresas mediante lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="4de3c-886">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="4de3c-887">Imagen de Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="4de3c-887">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="4de3c-888">Imagen compartida.</span><span class="sxs-lookup"><span data-stu-id="4de3c-888">Shared image.</span></span></li>
<li><span data-ttu-id="4de3c-889">Kit de herramientas de implementación de Office (ODT).</span><span class="sxs-lookup"><span data-stu-id="4de3c-889">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="4de3c-890">Configuración de FSLogix:</span><span class="sxs-lookup"><span data-stu-id="4de3c-890">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="4de3c-891">Implementación del agente FSLogix con el contenedor de perfiles.</span><span class="sxs-lookup"><span data-stu-id="4de3c-891">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="4de3c-892">Implementación del agente FSLogix con el contenedor de Office.</span><span class="sxs-lookup"><span data-stu-id="4de3c-892">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="4de3c-893">Configurar la carpeta FSLogix con exclusiones de contenido.</span><span class="sxs-lookup"><span data-stu-id="4de3c-893">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="4de3c-894">Implementación de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="4de3c-894">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="4de3c-895">Implementar Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="4de3c-895">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="4de3c-896">Conectarse con clientes de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="4de3c-896">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="4de3c-897">

<strong>Lo siguiente está fuera del ámbito</strong>
</span><span class="sxs-lookup"><span data-stu-id="4de3c-897">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="4de3c-898">Administración de proyectos de la implementación de Windows Virtual Desktop del cliente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-898">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="4de3c-899">Implementación y virtualización de aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="4de3c-899">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="4de3c-900">Imágenes personalizadas.</span><span class="sxs-lookup"><span data-stu-id="4de3c-900">Custom images.</span></span></li>
<li><span data-ttu-id="4de3c-901">Migraciones y escenarios relacionados con VMware y Citrix.</span><span class="sxs-lookup"><span data-stu-id="4de3c-901">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="4de3c-902">Escenarios de Linux.</span><span class="sxs-lookup"><span data-stu-id="4de3c-902">Linux scenarios.</span></span></li>
<li><span data-ttu-id="4de3c-903">Conversión o migraciones de perfiles de usuario.</span><span class="sxs-lookup"><span data-stu-id="4de3c-903">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="4de3c-904">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-904">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="4de3c-905">Ya debería tener lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="4de3c-905">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="4de3c-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licencias de Windows Virtual Desktop.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="4de3c-907">Redes de Azure:</span><span class="sxs-lookup"><span data-stu-id="4de3c-907">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="4de3c-908">Creación y subred de red virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="4de3c-908">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="4de3c-909">Firewall y grupos de seguridad de red.</span><span class="sxs-lookup"><span data-stu-id="4de3c-909">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="4de3c-910">VPN y ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="4de3c-910">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="4de3c-911">Enrutamiento a Azure desde local.</span><span class="sxs-lookup"><span data-stu-id="4de3c-911">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="4de3c-912">Reglas de firewall para permitir la conectividad a Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="4de3c-912">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="4de3c-913">Para obtener más información, vea <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Clientes de Escritorio remoto compatibles.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-913">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="4de3c-914">Configuración general de Azure AD:</span><span class="sxs-lookup"><span data-stu-id="4de3c-914">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="4de3c-915">Estrategia de <i>identidad (solo puede usar una de las tres opciones siguientes):</i>
</span><span class="sxs-lookup"><span data-stu-id="4de3c-915">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="4de3c-916">Active Directory con Azure AD Connect en Azure.</span><span class="sxs-lookup"><span data-stu-id="4de3c-916">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="4de3c-917">Active Directory con Azure AD Connect local a través de VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="4de3c-917">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="4de3c-918">Servicios de dominio de Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="4de3c-918">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="4de3c-919">App Assure</span><span class="sxs-lookup"><span data-stu-id="4de3c-919">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4de3c-920"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-920"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4de3c-921"><strong>Detalles de las instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-921"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4de3c-922"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-922"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="4de3c-923"><strong>Asesoría de aplicaciones</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-923"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="4de3c-924">App Assure es un servicio diseñado para solucionar problemas relacionados con la compatibilidad de aplicaciones de Windows 10 y Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-924">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="4de3c-925">Cuando solicite el servicio App Assure, trabajaremos con usted para solucionar los problemas válidos de la aplicación sin costo adicional para usted con una suscripción válida.</span><span class="sxs-lookup"><span data-stu-id="4de3c-925">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="4de3c-926">También proporcionamos instrucciones a los clientes que se enfrentan a problemas de compatibilidad al implementar Windows Virtual Desktop y Microsoft Edge, y realizar todos los esfuerzos razonables para resolver problemas de compatibilidad.</span><span class="sxs-lookup"><span data-stu-id="4de3c-926">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="4de3c-927">Proporcionamos asistencia de corrección para las aplicaciones implementadas en los siguientes productos de Microsoft:</span><span class="sxs-lookup"><span data-stu-id="4de3c-927">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="4de3c-928"><strong>Windows 10 </strong> (incluidos los dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="4de3c-928"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="4de3c-929"><strong>Aplicaciones de Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="4de3c-929"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="4de3c-930"><strong>Microsoft Edge:</strong> Para obtener instrucciones de implementación, consulte <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Información general de los canales de Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-930"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-931"><strong>Windows Virtual Desktop</strong> - Para obtener más información, consulte <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">¿Qué es Windows Virtual Desktop?</a> y Preguntas más frecuentes sobre las sesiones múltiples <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">de Windows 10 Enterprise.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-931"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="4de3c-932">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-932">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="4de3c-p145">Inventario y pruebas de aplicaciones para determinar lo que funciona y lo que no en Windows 10 y en las Aplicaciones de Microsoft 365. Para obtener más información sobre este proceso, visite el <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de implementación de escritorios</a>. Si está interesado en una evaluación detallada de la preparación para la actualización, complete el formulario <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitud de cliente para la evaluación del escritorio moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="4de3c-p145">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="4de3c-936">Buscar instrucciones de compatibilidad y soporte técnico de Windows 10 en aplicaciones ISV de terceros.</span><span class="sxs-lookup"><span data-stu-id="4de3c-936">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="4de3c-937">Para más información, vea <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análisis de escritorio</a>.</span><span class="sxs-lookup"><span data-stu-id="4de3c-937">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="4de3c-938">Servicios de solo empaquetado de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="4de3c-938">App packaging-only services.</span></span> <span data-ttu-id="4de3c-939">Sin embargo, el equipo de App Assure crea paquetes de aplicaciones que hemos corregido para Windows 10 para asegurarse de que se pueden implementar en el entorno del cliente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-939">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="4de3c-940">

<strong>Las responsabilidades del cliente incluyen</strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-940">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="4de3c-941">Creación de un inventario de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-941">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="4de3c-942">Validación de esas aplicaciones en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-942">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="4de3c-943">
<strong>Nota:</strong>  Microsoft no puede realizar cambios en el código fuente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-943">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="4de3c-944">Sin embargo, el equipo de App Assure puede proporcionar instrucciones a los desarrolladores de aplicaciones si el código fuente está disponible para sus aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-944">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="4de3c-945">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="4de3c-945">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="4de3c-946"><strong>Aplicaciones de Windows 10 y Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="4de3c-946"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-947">Las aplicaciones que funcionaban en Windows 7, Windows 8.1, Office 2010 y Office 2013 también funcionan en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="4de3c-947">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="4de3c-948">
<strong>Windows 10 en ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="4de3c-948">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="4de3c-949">Las aplicaciones que funcionaban en Windows 7, Office 2010 o versiones posteriores también funcionan en Windows 10 y aplicaciones de Microsoft 365 en dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="4de3c-949">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="4de3c-950">
  <strong>Nota:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="4de3c-950">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="4de3c-951">La emulación x64 (64 bits) está disponible en versión preliminar para los clientes que participan en <a href="https://insider.windows.com/">el Programa Windows Insider.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-951">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="4de3c-952">Para los clientes que no son de Windows Insider en Windows 10 versión 2004 (o posterior), ARM64 Photoshop es compatible con el paquete de compatibilidad de OpenCL y <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-952">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="4de3c-953">Los clientes del Programa Windows Insider pueden descargar una versión de Insider del paquete de compatibilidad de OpenCL y OpenGL para usarla con aplicaciones adicionales.</span><span class="sxs-lookup"><span data-stu-id="4de3c-953">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="4de3c-954">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="4de3c-954">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-955">Si las aplicaciones web o los sitios funcionan en Internet Explorer 11, las versiones compatibles de Google Chrome o cualquier versión de Microsoft Edge, también funcionarán con Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="4de3c-955">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-956">Como la web evoluciona constantemente, asegúrese de revisar esta lista publicada de cambios conocidos que afectan a la compatibilidad de sitios <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">para Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="4de3c-956">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="4de3c-957">
  <strong>Windows Virtual Desktop </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-957">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="4de3c-958">Las aplicaciones virtualizadas que se ejecutan en el host de sesión de Escritorio remoto (RDSH) de Windows Server también se ejecutan en Windows 10 Enterprise multisesión como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="4de3c-958">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-959">Las aplicaciones que se ejecutan en cualquier entorno de infraestructura de escritorio virtual (VDI) de Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="4de3c-959">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-960">Las aplicaciones que se ejecutan en dispositivos cliente con Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="4de3c-960">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="4de3c-961">
  <strong>Nota:</strong> Las exclusiones y limitaciones de compatibilidad de varias sesiones de Windows 10 Enterprise incluyen:</span><span class="sxs-lookup"><span data-stu-id="4de3c-961">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="4de3c-962">Redirección limitada del hardware.</span><span class="sxs-lookup"><span data-stu-id="4de3c-962">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-963">Las aplicaciones que hacen un uso intensivo de A/V pueden tener una capacidad reducida.</span><span class="sxs-lookup"><span data-stu-id="4de3c-963">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="4de3c-964">Las aplicaciones de 16 bits no son compatibles con Windows Virtual Desktop de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="4de3c-964">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="4de3c-965">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="4de3c-965">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="4de3c-966"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-966"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="4de3c-967"><strong>Detalles de las instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-967"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="4de3c-968"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="4de3c-968"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="4de3c-969"><strong>Microsoft Edge</strong> (para clientes de Windows 10 Enterprise)</span><span class="sxs-lookup"><span data-stu-id="4de3c-969"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="4de3c-970">Proporcionamos orientación de implementación remota y asistencia de compatibilidad para: implementar Microsoft Edge en Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="4de3c-970">We provide remote deployment guidance and compatibility assistance for: Deploying Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-971">Configuración de Microsoft Edge (con directivas de grupo o configuración de aplicaciones y directivas de aplicaciones de Intune).</span><span class="sxs-lookup"><span data-stu-id="4de3c-971">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="4de3c-972">Realizar un inventario de la lista de sitios que pueden requerir su uso en el modo Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="4de3c-972">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="4de3c-973">Habilitar el modo de Internet Explorer con la lista de sitios de empresa existente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-973">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="4de3c-974">Además, si tiene una aplicación web o un sitio que funciona con Internet Explorer o Google Chrome y experimenta problemas de compatibilidad, le proporcionamos instrucciones para resolver el problema sin costo adicional.</span><span class="sxs-lookup"><span data-stu-id="4de3c-974">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="4de3c-975">Consulte <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="4de3c-975">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="4de3c-976">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="4de3c-976">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="4de3c-977">Administración de proyectos de la implementación de Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="4de3c-977">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="4de3c-978">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="4de3c-978">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
