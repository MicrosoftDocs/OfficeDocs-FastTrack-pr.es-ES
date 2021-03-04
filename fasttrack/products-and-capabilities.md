---
title: Productos y capacidades
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias antes de poder comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que haga que el entorno de origen se ajuste a los requisitos mínimos para una incorporación correcta.
ms.openlocfilehash: 05936adee3f21e6078933a686dfa8dc24c33d1be
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416569"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="6bf37-104">Productos y capacidades</span><span class="sxs-lookup"><span data-stu-id="6bf37-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="6bf37-105">Servicios y escenarios admitidos por FastTrack</span><span class="sxs-lookup"><span data-stu-id="6bf37-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="6bf37-106">En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias antes de poder comenzar.</span><span class="sxs-lookup"><span data-stu-id="6bf37-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="6bf37-107">En función de la configuración actual, trabajamos con usted para crear un plan de corrección que haga que el entorno de origen se ajuste a los requisitos mínimos para una incorporación correcta.</span><span class="sxs-lookup"><span data-stu-id="6bf37-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="6bf37-108">FastTrack proporciona instrucciones para ayudarle primero con las funcionalidades principales (comunes para todos los Microsoft Online Services) y luego con la incorporación de cada servicio elegible:</span><span class="sxs-lookup"><span data-stu-id="6bf37-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="6bf37-109">General</span><span class="sxs-lookup"><span data-stu-id="6bf37-109">General</span></span>](#general)
  - [<span data-ttu-id="6bf37-110">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="6bf37-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="6bf37-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="6bf37-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="6bf37-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="6bf37-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="6bf37-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="6bf37-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="6bf37-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="6bf37-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="6bf37-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="6bf37-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="6bf37-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="6bf37-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="6bf37-117">Para obtener información sobre las expectativas de entorno de origen para Office 365 Administración Pública, vea [Expectativas de entorno de origen para Office 365 Administración Pública](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="6bf37-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="6bf37-118">General</span><span class="sxs-lookup"><span data-stu-id="6bf37-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6bf37-119"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="6bf37-120"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="6bf37-121"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6bf37-122"><strong>Incorporación principal</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-123">Proporcionamos instrucciones remotas sobre la incorporación principal, que implica el aprovisionamiento de servicios, el inquilino y la integración de identidades.</span><span class="sxs-lookup"><span data-stu-id="6bf37-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="6bf37-124">También incluye pasos para proporcionar una base para la incorporación de servicios como Exchange Online, SharePoint Online y Microsoft Teams, incluida una discusión sobre seguridad, conectividad de red <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">y cumplimiento.</a></span><span class="sxs-lookup"><span data-stu-id="6bf37-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="6bf37-125">La incorporación de uno o más servicios elegibles puede empezar al finalizar la incorporación principal.</span><span class="sxs-lookup"><span data-stu-id="6bf37-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="6bf37-126"></li>
</ul>  

<strong> Integración de identidades </strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="6bf37-127">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="6bf37-128">Preparación de identidades locales de Active Directory para la sincronización con Azure Active Directory (Azure AD), incluida la instalación y configuración de Azure AD Connect (bosque único o múltiple) y licencias (incluidas las licencias basadas en grupos).</span><span class="sxs-lookup"><span data-stu-id="6bf37-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="6bf37-129">Creación de identidades en la nube, incluida la importación masiva y las licencias, incluido el uso de licencias basadas en grupos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="6bf37-130">Elegir y habilitar el método de autenticación correcto para el recorrido en la nube, la sincronización hash de contraseña, la autenticación de paso a través o los servicios de federación de Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="6bf37-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="6bf37-131">Habilitar AD FS para clientes con un solo bosque de Active Directory e identidades sincronizadas con la herramienta Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="6bf37-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="6bf37-132">Esto requiere Windows Server 2012 R2 Active Directory Federation Services 2.0 o posterior.</span><span class="sxs-lookup"><span data-stu-id="6bf37-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="6bf37-133">Migrar la autenticación de AD FS a Azure AD mediante la sincronización hash de contraseña o la autenticación de paso a través.</span><span class="sxs-lookup"><span data-stu-id="6bf37-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="6bf37-134">Migración de aplicaciones preinstaladas (como aplicaciones saas) de software como servicio (SaaS) de la galería de Azure AD) de AD FS a Azure AD para el inicio de sesión único (SSO).</span><span class="sxs-lookup"><span data-stu-id="6bf37-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="6bf37-135">Habilitar integraciones de aplicaciones SaaS con SSO desde la galería de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="6bf37-136">Habilitar el aprovisionamiento automático de usuarios para aplicaciones SaaS integradas previamente, tal como se muestra en la lista de <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">tutoriales</a> de integración de aplicaciones (limitado a aplicaciones SaaS de la galería de Azure AD y aprovisionamiento saliente solamente).</span><span class="sxs-lookup"><span data-stu-id="6bf37-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="6bf37-137"><strong>Habilitación de red </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="6bf37-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="6bf37-138">Como parte de la ventaja de FastTrack, le recomendamos que se informe de los procedimientos recomendados para conectarse a los servicios en la nube para garantizar los niveles más altos de rendimiento de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="6bf37-139"><strong>Bosques de Active Directory</strong> Estos tienen el nivel de bosque funcional establecido en Windows Server 2003 en adelante, con la siguiente configuración de bosque:</span><span class="sxs-lookup"><span data-stu-id="6bf37-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-140">Un solo bosque de Active Directory.</span><span class="sxs-lookup"><span data-stu-id="6bf37-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-141">Un solo bosque de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="6bf37-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-142">Varios bosques de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="6bf37-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-143">Varios bosques de cuentas de Active Directory con uno de los bosques que es un bosque de cuentas de Active Directory centralizado que incluye Exchange o Lync 2010, Lync 2013 o Skype Empresarial.</span><span class="sxs-lookup"><span data-stu-id="6bf37-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-144">Varios bosques de cuentas de Active Directory, cada uno con su propia organización de Exchange.</span><span class="sxs-lookup"><span data-stu-id="6bf37-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-145">Tareas necesarias para la configuración e integración de inquilinos con Azure Active Directory, si es necesario.</span><span class="sxs-lookup"><span data-stu-id="6bf37-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="6bf37-146">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="6bf37-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="6bf37-147">Para escenarios de Active Directory de varios bosques, si se implementa Lync 2010, Lync 2013 o Skype Empresarial, debe implementarse en el mismo bosque de Active Directory que Exchange.</span><span class="sxs-lookup"><span data-stu-id="6bf37-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-148">Al implementar varios bosques de Active Directory con varias organizaciones de Exchange en una configuración multi híbrido de Exchange, no se admiten espacios de nombres de nombre principal de usuario compartido (UPN) entre bosques de origen.</span><span class="sxs-lookup"><span data-stu-id="6bf37-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="6bf37-149">Los espacios de nombres SMTP principales entre las organizaciones de Exchange también deben estar separados.</span><span class="sxs-lookup"><span data-stu-id="6bf37-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="6bf37-150">Para más información, consulte <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implementaciones híbridas con varios bosques de Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-151">Para todas las configuraciones de varios bosques, la implementación de Servicios de federación de Active Directory (AD FS) está fuera del ámbito.</span><span class="sxs-lookup"><span data-stu-id="6bf37-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="6bf37-152">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-153"><strong>Aplicaciones de Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-154">Proporcionamos instrucciones de implementación remota para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-155">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-156">Asignar licencias de usuario final y basadas en dispositivos mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="6bf37-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-157">Instalar Aplicaciones de Microsoft 365 desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="6bf37-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-158">Instalar aplicaciones de Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile y PowerPoint Mobile) en los dispositivos iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="6bf37-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-159">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-160">Selección y configuración de una instalación local o en la nube.</span><span class="sxs-lookup"><span data-stu-id="6bf37-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-161">Creación de la configuración XML de la herramienta de implementación de Office con la herramienta de personalización de Office o XML nativo para configurar el paquete de implementación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-162">Implementar mediante Microsoft Endpoint Configuration Manager, incluida la ayuda con la creación del empaquetado de Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="6bf37-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="6bf37-163">Además, si tiene una macro o complemento que ha funcionado con versiones anteriores de Office y experimenta problemas de compatibilidad, le ofrecemos instrucciones para corregir el problema de compatibilidad sin costo adicional a través del programa App Assure.</span><span class="sxs-lookup"><span data-stu-id="6bf37-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="6bf37-164">Consulta la <strong>parte de App Assure</strong> de Windows <a href="#windows-10">10</a> para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="6bf37-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="6bf37-165">El software cliente en línea debe estar en un nivel mínimo tal como se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-166"><strong>Estado de la red</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-167">Proporcionamos instrucciones remotas para obtener e interpretar datos clave de conectividad de red de su entorno que muestran cómo se alinean los sitios de su organización con los <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principios</a>de conectividad de red de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="6bf37-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="6bf37-168">Esto resalta la puntuación de red que afecta directamente a la velocidad de migración, la experiencia del usuario, el rendimiento del servicio y la confiabilidad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="6bf37-169">También le guiaremos a través de los pasos de corrección resaltados por estos datos para ayudarle a mejorar la puntuación de red.</span><span class="sxs-lookup"><span data-stu-id="6bf37-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="6bf37-170">Acceso al Centro de administración de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-171">Se requieren versiones actualizadas de aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-172">Servicios de ubicación habilitados según las recomendaciones de rendimiento de red en el Centro de administración de <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (versión preliminar).</a></span><span class="sxs-lookup"><span data-stu-id="6bf37-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="6bf37-173">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="6bf37-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6bf37-174"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="6bf37-175"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="6bf37-176"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="6bf37-177"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-178">Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="6bf37-179">

<strong>Infraestructura básica segura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="6bf37-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="6bf37-180">Configurar y habilitar una autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseñas sin servicio (SSPR).</span><span class="sxs-lookup"><span data-stu-id="6bf37-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-181">Para los clientes que no son de Azure AD Premium, se proporcionan instrucciones para proteger las identidades mediante valores predeterminados de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-182">Para los clientes premium de Azure AD, se proporcionan instrucciones para proteger sus identidades con acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="6bf37-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-183">Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="6bf37-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-184">Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-185">Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="6bf37-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-186">Habilitar una pantalla de inicio de sesión personalizada, incluidos logotipo, texto e imágenes con personalización de marca personalizada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-187">Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="6bf37-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-188">Administrar el acceso para los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-189">Configuración de la unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-190">Configuración de la unión a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="6bf37-191">
  
<strong>Supervisión e informes</strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-192">Habilitar la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="6bf37-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="6bf37-193">
  
<strong>Gobierno</strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-194">Administrar la identidad de Azure AD y el ciclo de vida de acceso a escala con la administración de derechos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="6bf37-195">Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-196">Revisión de los Términos de uso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-197">Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="6bf37-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="6bf37-198">
  
<strong>Automatización y eficiencias </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-199">Habilitar Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="6bf37-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="6bf37-200">Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos de Office 365 con la administración de grupos de autoservicio de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-201">Administrar el acceso delegado a aplicaciones empresariales con la administración de grupos delegada de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-202">Habilitar grupos dinámicos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-203">Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="6bf37-204">Active Directory local y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="6bf37-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="6bf37-206">Para obtener más información sobre Azure Information Protection, consulte <strong>Microsoft Information Protection</strong> más adelante en esta tabla.</span><span class="sxs-lookup"><span data-stu-id="6bf37-206">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="6bf37-207"><strong>Respuesta & de detección</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-207"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="6bf37-208"><strong>Exhibición de documentos electrónicos avanzada</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-208"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="6bf37-209">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="6bf37-209">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-210">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="6bf37-210">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-211">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="6bf37-211">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-212">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-212">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="6bf37-213"><strong>Auditoría avanzada</strong> (solo compatible con E5)</span><span class="sxs-lookup"><span data-stu-id="6bf37-213"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="6bf37-214">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-214">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="6bf37-215">Habilitar la auditoría avanzada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-215">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="6bf37-216">Realizar una interfaz de usuario de registro de auditoría de búsqueda y comandos básicos de PowerShell de auditoría.</span><span class="sxs-lookup"><span data-stu-id="6bf37-216">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="6bf37-217">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-217">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="6bf37-218">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-218">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="6bf37-219">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-219">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="6bf37-220">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-220">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="6bf37-221">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-221">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="6bf37-222">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-222">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="6bf37-223">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-223">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="6bf37-224">

<strong>Lo siguiente está fuera del ámbito </strong> 
</span><span class="sxs-lookup"><span data-stu-id="6bf37-224">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="6bf37-225">Scripting o codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="6bf37-225">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="6bf37-226">API de exhibición de documentos electrónicos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-226">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="6bf37-227">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-227">Data connectors.</span></span> </li>
<li> <span data-ttu-id="6bf37-228">Límites de cumplimiento y filtros de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-228">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="6bf37-229">Investigaciones de datos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-229">Data investigations.</span></span></li>
<li> <span data-ttu-id="6bf37-230">Solicitudes del interesado.</span><span class="sxs-lookup"><span data-stu-id="6bf37-230">Data subject requests.</span></span></li>
<li> <span data-ttu-id="6bf37-231">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-231">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="6bf37-232">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="6bf37-232">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="6bf37-233">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-233">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="6bf37-234">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="6bf37-234">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6bf37-235"><strong>Administración de amenazas de Insider</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-235"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="6bf37-236">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-236">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="6bf37-237">Crear directivas y revisar la configuración.</span><span class="sxs-lookup"><span data-stu-id="6bf37-237">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="6bf37-238">Acceso a informes y alertas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-238">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="6bf37-239">Creación de casos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-239">Creating cases.</span></span></li>
<li> <span data-ttu-id="6bf37-240">Creación de plantillas de aviso.</span><span class="sxs-lookup"><span data-stu-id="6bf37-240">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="6bf37-241">Instrucciones para crear el conector de recursos humanos (HR).</span><span class="sxs-lookup"><span data-stu-id="6bf37-241">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="6bf37-242">

<strong> Cumplimiento de comunicaciones </strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-242">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="6bf37-243">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-243">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="6bf37-244">Crear directivas y revisar la configuración.</span><span class="sxs-lookup"><span data-stu-id="6bf37-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="6bf37-245">Acceso a informes y alertas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="6bf37-246">Creación de plantillas de aviso.</span><span class="sxs-lookup"><span data-stu-id="6bf37-246">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="6bf37-247">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-247">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="6bf37-248">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-248">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="6bf37-249">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-249">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="6bf37-250">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-250">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="6bf37-251">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-251">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="6bf37-252">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-252">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="6bf37-253">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-253">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="6bf37-254">

<strong>Lo siguiente está fuera del ámbito </strong> 
</span><span class="sxs-lookup"><span data-stu-id="6bf37-254">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="6bf37-255">Creación y administración de flujos de Power Automate.</span><span class="sxs-lookup"><span data-stu-id="6bf37-255">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="6bf37-256">Conectores de datos (más allá del conector de RECURSOS HUMANOS).</span><span class="sxs-lookup"><span data-stu-id="6bf37-256">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="6bf37-257">Configuraciones de expresiones regulares personalizadas (RegEx).</span><span class="sxs-lookup"><span data-stu-id="6bf37-257">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="6bf37-258">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-258">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="6bf37-259">Barreras de información.</span><span class="sxs-lookup"><span data-stu-id="6bf37-259">Information barriers.</span></span></li>
<li> <span data-ttu-id="6bf37-260">Administración de acceso con privilegios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-260">Privileged access management.</span></span></li>
<li> <span data-ttu-id="6bf37-261">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="6bf37-261">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="6bf37-262">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-262">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="6bf37-263">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="6bf37-263">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="6bf37-264"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-264"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="6bf37-265">Microsoft 365 Defender es un conjunto unificado de defensa empresarial anterior y posterior a la infracción que coordina de forma nativa la detección, prevención, investigación y respuesta entre puntos de conexión, identidades, correo electrónico y aplicaciones para proporcionar protección integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="6bf37-265">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="6bf37-266">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-266">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="6bf37-267">Proporcionar información general sobre el Centro de seguridad de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-267">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-268">Revisión de incidentes entre productos, incluido el centrarse en lo que es fundamental al garantizar el ámbito de ataque completo, los activos afectados y las acciones de corrección automatizadas que se agrupan.</span><span class="sxs-lookup"><span data-stu-id="6bf37-268">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-269">Demostración de cómo Microsoft 365 Defender puede orquestar la investigación de activos, usuarios, dispositivos y buzones de correo que podrían haber sido comprometidos a través de la recuperación automática.</span><span class="sxs-lookup"><span data-stu-id="6bf37-269">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="6bf37-270">Explicar y proporcionar ejemplos de cómo los clientes pueden buscar proactivamente intentos de intrusión y actividad de infracción que afecten al correo electrónico, los datos, los dispositivos y las cuentas en varios conjuntos de datos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-270">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="6bf37-271">Mostrar a los clientes cómo pueden revisar y mejorar su posición de seguridad de forma holística con Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="6bf37-271">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="6bf37-272"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-272"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="6bf37-273">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="6bf37-273">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="6bf37-274">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="6bf37-274">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="6bf37-275">Instrucciones de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="6bf37-275">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="6bf37-276">Cómo corregir o interpretar los distintos tipos de alerta y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-276">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="6bf37-277">Cómo investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-277">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="6bf37-278">Búsqueda de amenazas personalizada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-278">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="6bf37-279">Información de seguridad y administración de eventos (SIEM) o integración de API.</span><span class="sxs-lookup"><span data-stu-id="6bf37-279">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-280"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-280"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-281">Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una amplia visibilidad, control sobre el desplazamiento de datos y análisis sofisticados para identificar y combatir las amenazas cibernéticas en todos los servicios en la nube de Microsoft y de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-281">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="6bf37-282">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-282">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-283">Configurar el portal, incluidos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-283">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="6bf37-284">Importar grupos de usuarios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-284">Importing user groups.</span></span></li>
<li> <span data-ttu-id="6bf37-285">Administrar el acceso de administrador y la configuración.</span><span class="sxs-lookup"><span data-stu-id="6bf37-285">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="6bf37-286">Ámbito de la implementación para seleccionar determinados grupos de usuarios para supervisar o excluir de la supervisión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="6bf37-287">Establecer intervalos y etiquetas IP.</span><span class="sxs-lookup"><span data-stu-id="6bf37-287">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="6bf37-288">Personalizar la experiencia del usuario final con el logotipo y la mensajería personalizada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-288">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="6bf37-289">Configuración de la detección en la nube para proporcionar UNA instantánea con:</span><span class="sxs-lookup"><span data-stu-id="6bf37-289">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="6bf37-290">Microsoft Defender para puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-290">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="6bf37-291">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="6bf37-291">Zscaler.</span></span></li>
<li> <span data-ttu-id="6bf37-292">iboss.</span><span class="sxs-lookup"><span data-stu-id="6bf37-292">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="6bf37-293">Conectar <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">aplicaciones características con</a> conectores de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-293">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="6bf37-294">Configurar el control de aplicaciones de acceso condicional en los portales de Acceso condicional y Seguridad de aplicaciones en la nube para aplicar controles de sesión en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="6bf37-294">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="6bf37-295">Implementación de los paneles Cloud App Security y Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="6bf37-295">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="6bf37-296">Personalizar las puntuaciones de riesgo de la aplicación en función de las prioridades de la organización.</span><span class="sxs-lookup"><span data-stu-id="6bf37-296">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="6bf37-297">Crear etiquetas y categorías de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-297">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="6bf37-298">Sancionar y deshacer la autorización de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-298">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="6bf37-299">Uso de la actividad y los registros de archivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-299">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="6bf37-300">Administrar aplicaciones de OAuth.</span><span class="sxs-lookup"><span data-stu-id="6bf37-300">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="6bf37-301">Descripción de la correlación de incidentes en el portal de Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="6bf37-301">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="6bf37-302">Proporcionar asistencia de configuración con los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 casos</a> de uso principales para CASB (incluida la creación o actualización de hasta seis (6) directivas), excepto:</span><span class="sxs-lookup"><span data-stu-id="6bf37-302">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="6bf37-303">Auditar la configuración de internet como entornos de servicio (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="6bf37-303">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="6bf37-304">Supervisar las actividades de los usuarios para protegerse contra amenazas en los entornos de IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="6bf37-304">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="6bf37-305"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-305"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="6bf37-306">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="6bf37-306">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="6bf37-307">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="6bf37-307">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="6bf37-308">Configurar la infraestructura, la instalación o la implementación de cargas automáticas de registros para informes continuos con Docker o un recopilador de registros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-308">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="6bf37-309">Vea <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-309">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="6bf37-310">Creación de un informe de instantáneas de detección de nube.</span><span class="sxs-lookup"><span data-stu-id="6bf37-310">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="6bf37-311">Bloquear el uso de la aplicación mediante scripts de bloqueo.</span><span class="sxs-lookup"><span data-stu-id="6bf37-311">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="6bf37-312">Conexión de aplicaciones personalizadas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-312">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="6bf37-313">Integración con proveedores de identidades de terceros (ISP) y proveedores de prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="6bf37-313">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="6bf37-314">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-314">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="6bf37-315">Investigación y corrección automatizadas, incluidos los libros de juegos de Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="6bf37-315">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="6bf37-316">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="6bf37-316">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="6bf37-317">Implementar la detección de aplicaciones en la nube como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-317">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="6bf37-318"><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-319">La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-319">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="6bf37-320">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-320">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-321">Implementar las tecnologías para proteger los puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-321">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-322">Configuración de perfiles de restricción de dispositivos y protección de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-322">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-323">Evaluación de la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios antivirus de Windows Defender u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-323">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-324">Evaluar el estado de los servicios antivirus de Windows u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-324">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-325">Evaluación de servidores proxy y firewalls que restringen el tráfico de red.</span><span class="sxs-lookup"><span data-stu-id="6bf37-325">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-326">Para habilitar el servicio ATP de Microsoft Defender, explique cómo implementar un perfil de agente de ATP con un punto de conexión integrado.</span><span class="sxs-lookup"><span data-stu-id="6bf37-326">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-327">Instrucciones de implementación, asistencia de configuración y educación sobre:</span><span class="sxs-lookup"><span data-stu-id="6bf37-327">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-328">Administración de amenazas y vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="6bf37-328">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-329">Reducción de la superficie de ataque.</span><span class="sxs-lookup"><span data-stu-id="6bf37-329">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-330">Protección de nueva generación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-330">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-331">Detección y respuesta de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-331">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-332">Investigación y corrección automatizadas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-332">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-333">Puntuación de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-333">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-334">Revisión de simulaciones y tutoriales (como escenarios de práctica, malware falso e investigaciones automatizadas).</span><span class="sxs-lookup"><span data-stu-id="6bf37-334">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-335">Información general sobre las características de informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-335">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-336">Integrar Protección contra amenazas avanzadas de Office 365 con Protección contra amenazas avanzada de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="6bf37-336">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-337">Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="6bf37-337">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-338">Los siguientes sistemas operativos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-338">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-339">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-339">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-340">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="6bf37-340">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-341">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="6bf37-341">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-342">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="6bf37-342">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-343">Windows Server Semi-Annual Channel (SAC) versión 1803.</span><span class="sxs-lookup"><span data-stu-id="6bf37-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-344">macOS versiones 10.13, 10.14 y 10.15.</span><span class="sxs-lookup"><span data-stu-id="6bf37-344">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="6bf37-345">
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la versión más reciente de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior).</span><span class="sxs-lookup"><span data-stu-id="6bf37-345">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="6bf37-346"></li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-346"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="6bf37-347">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="6bf37-347">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-348">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-348">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-349">Administración continua y respuesta ante amenazas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-349">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-350">Incorporación o configuración para los siguientes agentes de Protección contra amenazas avanzada de Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="6bf37-350">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-351">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="6bf37-351">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-352">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="6bf37-352">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-353">Linux.</span><span class="sxs-lookup"><span data-stu-id="6bf37-353">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-354">Dispositivos móviles (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="6bf37-354">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="6bf37-355">Infraestructura de escritorio virtual (VDI) (persistente o no persistente).</span><span class="sxs-lookup"><span data-stu-id="6bf37-355">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-356">Configuración y incorporación de servidores:</span><span class="sxs-lookup"><span data-stu-id="6bf37-356">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-357">Configurar un servidor proxy para comunicaciones sin conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-357">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-358">Configuración de paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.</span><span class="sxs-lookup"><span data-stu-id="6bf37-358">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-359">Incorporación de servidores al Centro de seguridad de Azure.</span><span class="sxs-lookup"><span data-stu-id="6bf37-359">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-360">Servidores no administrados por Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="6bf37-360">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-361">Configuración y incorporación de macOS:</span><span class="sxs-lookup"><span data-stu-id="6bf37-361">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-362">Implementación manual basada en Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-362">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-363">Implementación basada en JAMF.</span><span class="sxs-lookup"><span data-stu-id="6bf37-363">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="6bf37-364">Otra implementación basada en productos de administración de dispositivos móviles (MDM).</span><span class="sxs-lookup"><span data-stu-id="6bf37-364">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-365">Implementación manual.</span><span class="sxs-lookup"><span data-stu-id="6bf37-365">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-366">Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:</span><span class="sxs-lookup"><span data-stu-id="6bf37-366">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-367">Aislamiento basado en hardware.</span><span class="sxs-lookup"><span data-stu-id="6bf37-367">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-368">Control de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-368">App control.</span></span>  
  </li>
<li> <span data-ttu-id="6bf37-369">Control de dispositivo.</span><span class="sxs-lookup"><span data-stu-id="6bf37-369">Device control.</span></span></li>
<li>  
  <span data-ttu-id="6bf37-370">Protección contra vulnerabilidades de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-370">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-371">Firewall de red.</span><span class="sxs-lookup"><span data-stu-id="6bf37-371">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="6bf37-372">Configuración o administración de características de protección de cuentas como:</span><span class="sxs-lookup"><span data-stu-id="6bf37-372">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="6bf37-373">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="6bf37-373">Windows Hello</span></span></li>
<li> <span data-ttu-id="6bf37-374">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="6bf37-374">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="6bf37-375">Configuración o administración de BitLocker.</span><span class="sxs-lookup"><span data-stu-id="6bf37-375">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="6bf37-376">Inscripción o configuración de Expertos en amenazas de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="6bf37-376">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-377">Configuración o aprendizaje que revisa las conexiones DE API o de información de seguridad y administración de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="6bf37-377">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-378">Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="6bf37-378">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-379">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-379">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-380">Formación u instrucciones sobre el uso o creación de consultas de Kusto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-380">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="6bf37-381">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-381">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="6bf37-382"><strong>Microsoft Defender para la identidad </strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-382"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="6bf37-383">Microsoft Defender for Identity es una solución de seguridad basada en la nube que aprovecha las señales locales de Active Directory para identificar, detectar e investigar las amenazas avanzadas, las identidades vulnerables y las acciones internas malintencionadas dirigidas a su organización.</span><span class="sxs-lookup"><span data-stu-id="6bf37-383">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="6bf37-384">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-384">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="6bf37-385">Crear la instancia de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="6bf37-385">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="6bf37-386">Conectar Defender for Identity a Active Directory.</span><span class="sxs-lookup"><span data-stu-id="6bf37-386">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="6bf37-387">Evaluar la preparación del entorno para implementar el sensor Defender for Identity en los controladores de dominio, incluidos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-387">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="6bf37-388">Ejecución de la herramienta de tamaño para la planeación de capacidad de recursos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-388">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="6bf37-389">Ejecutar la herramienta de auditoría para evaluar la compatibilidad de los controladores de dominio con el sensor.</span><span class="sxs-lookup"><span data-stu-id="6bf37-389">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="6bf37-390">Implementar el sensor para capturar y analizar el tráfico de red y los eventos de Windows directamente desde los controladores de dominio, incluidos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-390">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="6bf37-391">Descargar el paquete del sensor.</span><span class="sxs-lookup"><span data-stu-id="6bf37-391">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="6bf37-392">Configuración del sensor.</span><span class="sxs-lookup"><span data-stu-id="6bf37-392">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="6bf37-393">Instalar el sensor en el controlador de dominio de forma silenciosa.</span><span class="sxs-lookup"><span data-stu-id="6bf37-393">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="6bf37-394">Implementar el sensor en el entorno de varios bosques.</span><span class="sxs-lookup"><span data-stu-id="6bf37-394">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="6bf37-395">Integración de Defender para la identidad con Microsoft Cloud App Security (no se requieren licencias de Cloud App Security).</span><span class="sxs-lookup"><span data-stu-id="6bf37-395">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="6bf37-396">Proporcionar instrucciones de implementación, asistencia de configuración y educación sobre:</span><span class="sxs-lookup"><span data-stu-id="6bf37-396">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="6bf37-397">Ajustar el entorno para reducir el "ruido".</span><span class="sxs-lookup"><span data-stu-id="6bf37-397">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="6bf37-398">Descripción del informe de evaluación de la postura de seguridad de identidad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-398">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="6bf37-399">Descripción de la puntuación de prioridad de investigación del usuario y el informe de clasificación de la investigación del usuario.</span><span class="sxs-lookup"><span data-stu-id="6bf37-399">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="6bf37-400">Descripción del informe de usuario inactivo.</span><span class="sxs-lookup"><span data-stu-id="6bf37-400">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="6bf37-401">Proporcionar opciones de corrección en una cuenta comprometida.</span><span class="sxs-lookup"><span data-stu-id="6bf37-401">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="6bf37-402">Facilitar la migración de Análisis avanzado de amenazas (ATA) a Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="6bf37-402">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="6bf37-403"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-403"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="6bf37-404">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="6bf37-404">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="6bf37-405">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="6bf37-405">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="6bf37-406">Implementación del sensor Defender for Identity, incluidos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-406">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="6bf37-407">Planeación manual de capacidad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-407">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="6bf37-408">Implementar el sensor en una capacidad independiente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-408">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="6bf37-409">Implementar el sensor mediante un adaptador de equipo de tarjeta de interfaz de red (NIC).</span><span class="sxs-lookup"><span data-stu-id="6bf37-409">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="6bf37-410">Implementar el sensor a través de una herramienta de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-410">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="6bf37-411">Conexión al servicio en la nube de Defender for Identity a través de una conexión de proxy web.</span><span class="sxs-lookup"><span data-stu-id="6bf37-411">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="6bf37-412">Creación y administración de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="6bf37-412">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="6bf37-413">Instrucciones de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="6bf37-413">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="6bf37-414">Corrección o interpretación de diversos tipos de alertas y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-414">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="6bf37-415">Investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-415">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="6bf37-416">Amenaza o búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-416">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="6bf37-417">Respuesta a incidentes.</span><span class="sxs-lookup"><span data-stu-id="6bf37-417">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="6bf37-418">Proporcionar un tutorial de laboratorio de alertas de seguridad para Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="6bf37-418">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="6bf37-419">Proporcionar notificaciones cuando Defender for Identity detecta actividades sospechosas enviando alertas de seguridad al servidor de syslog a través de un sensor designado.</span><span class="sxs-lookup"><span data-stu-id="6bf37-419">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="6bf37-420">Configuración de Defender for Identity para realizar consultas mediante el protocolo de administrador de cuentas de seguridad remoto (SAMR) para identificar a los administradores locales en máquinas específicas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-420">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="6bf37-421">Configuración de soluciones VPN para agregar información desde la conexión VPN a la página de perfil de un usuario.</span><span class="sxs-lookup"><span data-stu-id="6bf37-421">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="6bf37-422">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="6bf37-422">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="6bf37-423">Implementar sensores de Defender for Identity como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-423">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="6bf37-424">Active Directory implementado.</span><span class="sxs-lookup"><span data-stu-id="6bf37-424">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-425">Los controladores de dominio en los que quieres instalar los sensores de Defender for Identity tienen conectividad a Internet con el servicio en la nube de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="6bf37-425">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="6bf37-426">El firewall y el proxy deben estar abiertos para comunicarse con el servicio en la nube de Defender for Identity (\*.atp.azure.com el puerto 443 debe estar abierto).</span><span class="sxs-lookup"><span data-stu-id="6bf37-426">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="6bf37-427">Controladores de dominio que se ejecutan en uno de los siguientes:</span><span class="sxs-lookup"><span data-stu-id="6bf37-427">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="6bf37-428">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="6bf37-428">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="6bf37-429">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="6bf37-429">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="6bf37-430">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="6bf37-430">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="6bf37-431">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="6bf37-431">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="6bf37-432">Windows Server 2019 con KB4487044 (compilación del sistema operativo 17763.316).</span><span class="sxs-lookup"><span data-stu-id="6bf37-432">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="6bf37-433"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-433"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="6bf37-434">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-434">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-435">Crear y publicar directivas y etiquetas de retención (solo se admiten en E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-435">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="6bf37-436">Administración de registros (solo se admite en E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-436">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="6bf37-437">Revisión de la creación del plan de archivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-437">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="6bf37-438">Crear y administrar registros (incluidos los registros basados en eventos).</span><span class="sxs-lookup"><span data-stu-id="6bf37-438">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-439">Revisión de la disposición.</span><span class="sxs-lookup"><span data-stu-id="6bf37-439">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="6bf37-440">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-440">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="6bf37-441">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-441">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="6bf37-442">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-442">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="6bf37-443">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-443">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="6bf37-444">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-444">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="6bf37-445">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-445">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="6bf37-446">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-446">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="6bf37-447">

  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-447">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="6bf37-448">Desarrollo de un plan de archivos de administración de registros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-448">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="6bf37-449">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-449">Data connectors.</span></span></li>
<li> <span data-ttu-id="6bf37-450">Desarrollo de la arquitectura de la información en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6bf37-450">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="6bf37-451">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="6bf37-451">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="6bf37-452">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-452">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="6bf37-453">Compatibilidad con E3.</span><span class="sxs-lookup"><span data-stu-id="6bf37-453">Support for E3.</span></span></li>
<li> <span data-ttu-id="6bf37-454">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="6bf37-454">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="6bf37-455">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-455">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="6bf37-456">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="6bf37-456">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-457"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-457"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-458">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-458">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-459">Clasificación de datos (compatible con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-459">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-460">Tipos de información confidencial (compatibles con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-460">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-461">Crear etiquetas de confidencialidad (admitidas en E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-461">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-462">Aplicar etiquetas de confidencialidad (compatibles con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-462">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-463">Clasificadores entrenables (admitidos en E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-463">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-464">Conocer los datos con el explorador de contenido y el explorador de actividades (compatible con E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-464">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-465">Publicar etiquetas con directivas (manual y automática) (admitidas en E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-465">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-466">Crear directivas de prevención de pérdida de datos de extremo (DLP) para dispositivos Con Windows 10 (compatible con E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-466">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-467">Crear directivas DLP para chats y canales de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="6bf37-467">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="6bf37-468">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-468">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="6bf37-469">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-469">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="6bf37-470">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-470">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="6bf37-471">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-471">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="6bf37-472">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-472">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="6bf37-473">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-473">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="6bf37-474">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-474">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="6bf37-475">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-475">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="6bf37-476">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-476">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="6bf37-477">Activar y configurar el espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="6bf37-477">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-478">Creación y configuración de etiquetas y directivas (compatibles con P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="6bf37-478">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-479">Aplicar protección de información a documentos (admitidos en P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="6bf37-479">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-480">Clasificar y etiquetar automáticamente la información en aplicaciones de Office (como Word, PowerPoint, Excel y Outlook) que se ejecutan en Windows y usan el cliente de Azure Information Protection (compatible con P2).</span><span class="sxs-lookup"><span data-stu-id="6bf37-480">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-481">Detección y etiquetado de archivos en reposo con el escáner de Azure Information Protection (compatible con P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="6bf37-481">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-482">Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="6bf37-482">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="6bf37-483">También proporcionamos instrucciones si desea aplicar protección con Microsoft Azure Rights Management Services (Azure RMS), cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="6bf37-483">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="6bf37-484"><strong>Lo siguiente está fuera del ámbito </strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-484"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="6bf37-485">Clave de cliente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-485">Customer key.</span></span></li>
<li><span data-ttu-id="6bf37-486">Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="6bf37-486">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="6bf37-487">Creación o modificación de diccionarios de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="6bf37-487">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="6bf37-488">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="6bf37-488">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="6bf37-489">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="6bf37-489">Azure Purview.</span></span></li>
<li> <span data-ttu-id="6bf37-490">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-490">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="6bf37-491">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="6bf37-491">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="6bf37-492">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-492">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="6bf37-493">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema a excepción de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="6bf37-493">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="6bf37-494"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-494"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="6bf37-495">Las responsabilidades de requisitos previos del cliente incluyen:</span><span class="sxs-lookup"><span data-stu-id="6bf37-495">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="6bf37-496">Una lista de ubicaciones de recurso compartido de archivos que se examinarán.</span><span class="sxs-lookup"><span data-stu-id="6bf37-496">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-497">Taxonomía de clasificación aprobada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-497">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="6bf37-498">Descripción de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.</span><span class="sxs-lookup"><span data-stu-id="6bf37-498">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-499">Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-499">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="6bf37-500">Etiquetas configuradas para clasificación y protección.</span><span class="sxs-lookup"><span data-stu-id="6bf37-500">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="6bf37-501">Todos los requisitos previos del escáner de Azure Information Protection están en su lugar.</span><span class="sxs-lookup"><span data-stu-id="6bf37-501">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="6bf37-502">Para obtener más información, vea <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-502">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="6bf37-503">Asegúrese de que los dispositivos de usuario ejecuten un sistema operativo compatible y tengan instalados los requisitos previos necesarios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-503">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="6bf37-504">Vea lo siguiente para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="6bf37-504">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="6bf37-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetado unificado de Azure Information Protection para usuarios</a>   </span><span class="sxs-lookup"><span data-stu-id="6bf37-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="6bf37-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="6bf37-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="6bf37-507">Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para compatibilidad híbrida.</span><span class="sxs-lookup"><span data-stu-id="6bf37-507">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="6bf37-508">Configuración y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado solamente) o Hold Your Own Key (HYOK) (solo cliente clásico) si necesita una de estas opciones para la implementación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-508">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-509"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-509"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-510">Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) basado en la nube y administración de aplicaciones móviles (MAM) para sus aplicaciones y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-510">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="6bf37-511">Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-511">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="6bf37-512">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="6bf37-512">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-513">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="6bf37-513">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-514">Configurar las identidades que Intune usará aprovechando las identidades locales de Active Directory o de la nube (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="6bf37-514">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-515">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-515">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-516">Configuración de la entidad mdma, según tus necesidades de administración, incluidos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-516">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-517">Establecer Intune como entidad MDM cuando Intune es la única solución MDM.</span><span class="sxs-lookup"><span data-stu-id="6bf37-517">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-518">Proporcionar instrucciones de MDM para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-518">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-519">Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.</span><span class="sxs-lookup"><span data-stu-id="6bf37-519">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-520">Configurar servicios y directivas de administración de MDM como:</span><span class="sxs-lookup"><span data-stu-id="6bf37-520">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-521">Implementación de aplicaciones para cada plataforma compatible a través de vínculos web o vínculos profundos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-521">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-522">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="6bf37-522">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-523">Implementación de correo electrónico, redes inalámbricas y perfiles vpn si tiene una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en su organización.</span><span class="sxs-lookup"><span data-stu-id="6bf37-523">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-524">Conexión al almacén de datos de Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-524">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-525">Integrar Intune con:</span><span class="sxs-lookup"><span data-stu-id="6bf37-525">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-526">Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="6bf37-526">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-527">Soluciones de partners de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).</span><span class="sxs-lookup"><span data-stu-id="6bf37-527">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-528">Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción a una solución de administración de gastos de telecomunicaciones).</span><span class="sxs-lookup"><span data-stu-id="6bf37-528">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="6bf37-529">Inscribir dispositivos de cada plataforma compatible en Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-529">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="6bf37-530">Proporcionar instrucciones de protección de aplicaciones sobre:</span><span class="sxs-lookup"><span data-stu-id="6bf37-530">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-531">Configurar directivas de protección de aplicaciones para cada plataforma compatible.</span><span class="sxs-lookup"><span data-stu-id="6bf37-531">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-532">Configurar directivas de acceso condicional para aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-532">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-533">Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-533">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-534">Uso de informes de uso de aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-534">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-535">Proporcionar instrucciones de migración desde la administración de equipos heredados a MDM de Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-535">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="6bf37-536">
 
</li>
</ul>
  
<strong>Conexión a la nube</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-536">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="6bf37-537">Le guiaremos para prepararse para adjuntar entornos de Configuration Manager existentes con Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-537">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="6bf37-538">Los pasos detallados dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="6bf37-538">The exact steps depend on your source environment.</span></span> <span data-ttu-id="6bf37-539">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="6bf37-539">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="6bf37-540">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="6bf37-540">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-541">Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="6bf37-541">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-542">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-542">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-543">Proporcionar instrucciones para configurar la unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-543">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-544">Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.</span><span class="sxs-lookup"><span data-stu-id="6bf37-544">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-545">Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.</span><span class="sxs-lookup"><span data-stu-id="6bf37-545">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-546">Configurar cargas de trabajo compatibles que quiera cambiar a Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-546">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-547">Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-547">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="6bf37-548"><strong>Implementar Outlook mobile para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook mobile para iOS y Android de forma segura en su organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.</span><span class="sxs-lookup"><span data-stu-id="6bf37-548"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="6bf37-549">Los pasos para implementar Outlook mobile para iOS y Android de forma segura con Intune dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="6bf37-549">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="6bf37-550">Puede incluir:</span><span class="sxs-lookup"><span data-stu-id="6bf37-550">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-551">Descargar las aplicaciones outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal a través de la Tienda de aplicaciones de Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="6bf37-551">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-552">Proporcionar instrucciones sobre cómo configurar:</span><span class="sxs-lookup"><span data-stu-id="6bf37-552">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-553">La implementación de aplicaciones de Outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal con Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-553">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-554">Directivas de protección de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-554">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-555">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="6bf37-555">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-556">Directivas de configuración de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-556">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="6bf37-557">Los administradores de TI necesitan que las infraestructuras de vpn, red inalámbrica y entidad de certificación ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-557">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="6bf37-558"><strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar autoridades de certificados, redes inalámbricas, infraestructuras VPN o certificados de inserción mdm de Apple para Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-558"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="6bf37-559"><strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube.</span><span class="sxs-lookup"><span data-stu-id="6bf37-559"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="6bf37-560">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-560">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="6bf37-561"><strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-561"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="6bf37-562"><strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con ATP de Microsoft Defender y crear directivas de cumplimiento de dispositivos en función de su evaluación del nivel de riesgo de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-562"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="6bf37-563">No proporcionamos asistencia en compras, licencias o activación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-563">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="6bf37-564">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-564">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="6bf37-565"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-565"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="6bf37-566">Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="6bf37-566">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="6bf37-567"><strong>Protección contra amenazas avanzada de Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-568">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-568">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-569">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="6bf37-569">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-570">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="6bf37-570">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-571">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="6bf37-571">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-572">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-572">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="6bf37-573">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="6bf37-573">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="6bf37-574">Office 365</span><span class="sxs-lookup"><span data-stu-id="6bf37-574">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6bf37-575"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-575"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="6bf37-576"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-576"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="6bf37-577"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-577"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6bf37-578"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-578"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-579">Para Exchange Online, le guiaremos a través del proceso para que su organización esté lista para usar el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="6bf37-579">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="6bf37-580">Los pasos exactos dependen del entorno de origen y de los planes de migración de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="6bf37-580">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="6bf37-581">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-581">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-582">Configuración de las características de Exchange Online Protection (EOP) para todos los dominios habilitados para correo que se han validado en Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-582">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-583">Apuntar los registros de intercambio de correo (MX) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-583">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-584">Configurar la característica ATP de Office 365 si forma parte del servicio de suscripción.</span><span class="sxs-lookup"><span data-stu-id="6bf37-584">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="6bf37-585">Para obtener más información, vea la parte protección contra amenazas avanzada de <strong>Office 365</strong> de esta tabla.</span><span class="sxs-lookup"><span data-stu-id="6bf37-585">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-p127">Configuración de la característica de prevención de pérdida de datos (DLP) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="6bf37-p128">Configuración del cifrado de mensajes de Office 365 (OME) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="6bf37-590">
  <strong>Nota:</strong> El servicio de replicación de buzones (MRS) intenta migrar correos electrónicos de Information Rights Managed (IRM) desde su buzón local al buzón de Exchange Online correspondiente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-590">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="6bf37-591">La capacidad de leer el contenido protegido posterior a la migración dependerá de la asignación de clientes y la copia de las plantillas de Active Directory Rights Management Services (AD RMS) en el servicio Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="6bf37-591">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="6bf37-592">Configurar puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="6bf37-592">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-593">Configuración de DNS, incluida la detección automática, el marco de directivas de remitente (SPF), el correo identificado de domainkeys (DKIM), la autenticación de mensajes basada en dominio, la creación de informes y la conformidad (DMARC) y los registros MX (según sea necesario).</span><span class="sxs-lookup"><span data-stu-id="6bf37-593">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-594">Configuración del flujo de correo electrónico entre su entorno de mensajería de origen y Exchange Online (si procede).</span><span class="sxs-lookup"><span data-stu-id="6bf37-594">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-595">Operación de migración de correo desde el entorno de mensajería de origen a Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-595">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-596">Configuración de clientes de buzón (Outlook para Windows, Outlook en la web y Outlook para iOS y Android).</span><span class="sxs-lookup"><span data-stu-id="6bf37-596">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="6bf37-597">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="6bf37-597">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="6bf37-598">Para obtener información sobre cómo usar la ventaja de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-598">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="6bf37-599">El entorno de origen debe tener uno de los siguientes niveles mínimos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-599">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-600">Una o varias organizaciones de Exchange a partir de Exchange Server 2003.</span><span class="sxs-lookup"><span data-stu-id="6bf37-600">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-601">Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).</span><span class="sxs-lookup"><span data-stu-id="6bf37-601">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-602">Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="6bf37-602">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-603">Para obtener información sobre las capacidades multige geográficas, vea <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-603">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="6bf37-604">El software cliente en línea como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, el cliente de sincronización de OneDrive para la Empresa, Power BI Desktop y Skype Empresarial deben estar en un nivel mínimo como se define en Requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-604">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-605"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-605"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-606">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-606">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-607">Crear y publicar directivas y etiquetas de retención (solo se admiten en E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-607">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="6bf37-608">Administración de registros (solo se admite en E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-608">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="6bf37-609">Revisión de la creación del plan de archivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-609">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="6bf37-610">Crear y administrar registros (incluidos los registros basados en eventos).</span><span class="sxs-lookup"><span data-stu-id="6bf37-610">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-611">Revisión de la disposición.</span><span class="sxs-lookup"><span data-stu-id="6bf37-611">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="6bf37-612">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-612">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="6bf37-613">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-613">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="6bf37-614">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-614">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="6bf37-615">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-615">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="6bf37-616">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-616">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="6bf37-617">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-617">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="6bf37-618">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-618">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="6bf37-619">

  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-619">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="6bf37-620">Desarrollo de un plan de archivos de administración de registros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-620">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="6bf37-621">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-621">Data connectors.</span></span></li>
<li> <span data-ttu-id="6bf37-622">Desarrollo de la arquitectura de la información en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6bf37-622">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="6bf37-623">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="6bf37-623">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="6bf37-624">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-624">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="6bf37-625">Compatibilidad con E3.</span><span class="sxs-lookup"><span data-stu-id="6bf37-625">Support for E3.</span></span></li>
<li> <span data-ttu-id="6bf37-626">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="6bf37-626">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="6bf37-627">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-627">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>


</td>
<td><span data-ttu-id="6bf37-628">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="6bf37-628">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-629"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-629"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-630">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-630">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-631">Clasificación de datos (compatible con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-631">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-632">Tipos de información confidencial (compatibles con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-632">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-633">Crear etiquetas de confidencialidad (admitidas en E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-633">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-634">Aplicar etiquetas de confidencialidad (compatibles con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-634">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-635">Clasificadores entrenables (admitidos en E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-635">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-636">Conocer los datos con el explorador de contenido y el explorador de actividades (compatible con E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-636">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-637">Publicar etiquetas con directivas (manual y automática) (admitidas en E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-637">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-638">Crear directivas de prevención de pérdida de datos de extremo (DLP) para dispositivos Con Windows 10 (compatible con E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-638">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-639">Crear directivas DLP para chats y canales de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="6bf37-639">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="6bf37-640">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-640">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="6bf37-641">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-641">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="6bf37-642">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-642">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="6bf37-643">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-643">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="6bf37-644">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-644">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="6bf37-645">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-645">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="6bf37-646">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-646">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="6bf37-647">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-647">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="6bf37-648">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-648">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="6bf37-649">Activar y configurar el espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="6bf37-649">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-650">Creación y configuración de etiquetas y directivas (compatibles con P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="6bf37-650">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-651">Aplicar protección de información a documentos (admitidos en P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="6bf37-651">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-652">Clasificar y etiquetar automáticamente la información en aplicaciones de Office (como Word, PowerPoint, Excel y Outlook) que se ejecutan en Windows y usan el cliente de Azure Information Protection (compatible con P2).</span><span class="sxs-lookup"><span data-stu-id="6bf37-652">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-653">Detección y etiquetado de archivos en reposo con el escáner de Azure Information Protection (compatible con P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="6bf37-653">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-654">Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="6bf37-654">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
  
<span data-ttu-id="6bf37-655">También proporcionamos instrucciones si desea aplicar protección con Microsoft Azure Rights Management Services (Azure RMS), cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="6bf37-655">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="6bf37-656"><strong>Lo siguiente está fuera del ámbito </strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-656"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="6bf37-657">Clave de cliente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-657">Customer key.</span></span></li>
<li><span data-ttu-id="6bf37-658">Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="6bf37-658">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="6bf37-659">Creación o modificación de diccionarios de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="6bf37-659">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="6bf37-660">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="6bf37-660">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="6bf37-661">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="6bf37-661">Azure Purview.</span></span></li>
<li> <span data-ttu-id="6bf37-662">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-662">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="6bf37-663">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="6bf37-663">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="6bf37-664">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="6bf37-664">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="6bf37-665">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema a excepción de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="6bf37-665">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="6bf37-666"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-666"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="6bf37-667">Las responsabilidades de requisitos previos del cliente incluyen:</span><span class="sxs-lookup"><span data-stu-id="6bf37-667">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="6bf37-668">Una lista de ubicaciones de recurso compartido de archivos que se examinarán.</span><span class="sxs-lookup"><span data-stu-id="6bf37-668">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-669">Taxonomía de clasificación aprobada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-669">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="6bf37-670">Descripción de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.</span><span class="sxs-lookup"><span data-stu-id="6bf37-670">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-671">Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-671">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="6bf37-672">Etiquetas configuradas para clasificación y protección.</span><span class="sxs-lookup"><span data-stu-id="6bf37-672">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="6bf37-673">Todos los requisitos previos del escáner de Azure Information Protection están en su lugar.</span><span class="sxs-lookup"><span data-stu-id="6bf37-673">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="6bf37-674">Para obtener más información, vea <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-674">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="6bf37-675">Asegúrese de que los dispositivos de usuario ejecuten un sistema operativo compatible y tengan instalados los requisitos previos necesarios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-675">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="6bf37-676">Vea lo siguiente para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="6bf37-676">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="6bf37-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetado unificado de Azure Information Protection para usuarios</a>   </span><span class="sxs-lookup"><span data-stu-id="6bf37-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="6bf37-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="6bf37-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="6bf37-679">Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para compatibilidad híbrida.</span><span class="sxs-lookup"><span data-stu-id="6bf37-679">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="6bf37-680">Configuración y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado solamente) o Hold Your Own Key (HYOK) (solo cliente clásico) si necesita una de estas opciones para la implementación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-680">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-681"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-681"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-682">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-682">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-683">Confirmar los requisitos mínimos en Exchange Online, SharePoint Online, Grupos de Office 365 y Azure AD para admitir Teams.</span><span class="sxs-lookup"><span data-stu-id="6bf37-683">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-684">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="6bf37-684">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-685">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="6bf37-685">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-686">Confirmar que se ha habilitado Teams en su espacio empresarial de Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-686">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-687">Habilitar o deshabilitar licencias de usuario.</span><span class="sxs-lookup"><span data-stu-id="6bf37-687">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-688">Evaluación de red para Teams:</span><span class="sxs-lookup"><span data-stu-id="6bf37-688">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-689">Comprobaciones de puertos y puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-689">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-690">Comprobaciones de calidad de la conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-690">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-691">Estimaciones de ancho de banda.</span><span class="sxs-lookup"><span data-stu-id="6bf37-691">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="6bf37-692">Configuración de la directiva de aplicación de Teams (aplicación web de Teams, aplicación de escritorio de Teams y Teams para iOS y aplicación Android).</span><span class="sxs-lookup"><span data-stu-id="6bf37-692">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="6bf37-693">Si procede, también proporcionamos instrucciones para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-693">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-694">Dispositivos de sala de Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="6bf37-694">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="6bf37-695">Creación de cuentas en línea necesarias para los dispositivos de telefonía y salas de conferencias compatibles que aparecen en el <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos de Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-695">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-696">Asistencia remota con configuración del lado del servicio de dispositivos Microsoft Teams Rooms certificados.</span><span class="sxs-lookup"><span data-stu-id="6bf37-696">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-697">Habilitar audioconferencia:</span><span class="sxs-lookup"><span data-stu-id="6bf37-697">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="6bf37-698">Parámetros predeterminados de la configuración de la organización para puente de conferencia.</span><span class="sxs-lookup"><span data-stu-id="6bf37-698">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-699">Asignación de un puente de conferencia a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="6bf37-699">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="6bf37-700">Sistema telefónico:</span><span class="sxs-lookup"><span data-stu-id="6bf37-700">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-701">Configuración de la organización para los parámetros predeterminados de voz en la nube.</span><span class="sxs-lookup"><span data-stu-id="6bf37-701">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-702">Instrucciones de planes de llamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponibles</a>):</span><span class="sxs-lookup"><span data-stu-id="6bf37-702">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-703">Asignación de números a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="6bf37-703">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-704">Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.</span><span class="sxs-lookup"><span data-stu-id="6bf37-704">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-705">Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.</span><span class="sxs-lookup"><span data-stu-id="6bf37-705">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-706">Guía de enrutamiento directo:</span><span class="sxs-lookup"><span data-stu-id="6bf37-706">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-707">Guía de configuración de la organización para el diseño de enrutamiento directo de escenarios hospedados por asociados o escenarios implementados por el cliente para hasta 10 sitios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-707">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="6bf37-708">Revisión de configuración del controlador de borde de sesión (SBC).</span><span class="sxs-lookup"><span data-stu-id="6bf37-708">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="6bf37-709">Asistencia remota con la configuración del plan de marcado.</span><span class="sxs-lookup"><span data-stu-id="6bf37-709">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="6bf37-710">Configuración de ruta de voz.</span><span class="sxs-lookup"><span data-stu-id="6bf37-710">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="6bf37-711">Desvío de medios y optimización de medios locales.</span><span class="sxs-lookup"><span data-stu-id="6bf37-711">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="6bf37-712">Habilitar eventos en directo en Teams</span><span class="sxs-lookup"><span data-stu-id="6bf37-712">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-713">Configuración e integración de la organización en Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="6bf37-713">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-714">Instrucciones para la transición de Skype Empresarial a Teams.</span><span class="sxs-lookup"><span data-stu-id="6bf37-714">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="6bf37-715">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-715">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-716">Usuarios habilitados para SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="6bf37-716">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-717">Los buzones de Exchange están presentes (en línea y local en una configuración híbrida de Exchange).</span><span class="sxs-lookup"><span data-stu-id="6bf37-717">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-718">Habilitado para Grupos de Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-718">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="6bf37-719">
  <strong>Nota:</strong> Si los usuarios no están asignados y habilitados con licencias de SharePoint Online, no tendrán almacenamiento de OneDrive para la Empresa en Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-719">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="6bf37-720">El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin el almacenamiento de OneDrive para la Empresa en Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-720">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="6bf37-721">Teams no admite SharePoint localmente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-721">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="6bf37-722">
  <strong>Nota:</strong> El estado ideal es que todos los usuarios tengan sus buzones en Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="6bf37-722">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="6bf37-723">Los usuarios con buzones de correo locales deben tener sus identidades sincronizadas con el directorio de Office 365 a través de Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="6bf37-723">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="6bf37-724">Para estos clientes híbridos de Exchange, si el buzón del usuario es local, el usuario no puede agregar ni configurar conectores.</span><span class="sxs-lookup"><span data-stu-id="6bf37-724">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="6bf37-725">Los instaladores para los clientes de escritorio de Mac y Windows en Microsoft Teams se pueden descargar de <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-725">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-726"><strong>Protección contra amenazas avanzada de Office 365 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-727">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-727">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-728">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="6bf37-728">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-729">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="6bf37-729">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-730">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="6bf37-730">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-731">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-731">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="6bf37-732">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="6bf37-732">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-733"><strong>Outlook para iOS y Android</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-733"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-734">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-734">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-735">Descargar Outlook para iOS y Android desde la App Store de Apple y Google Play.</span><span class="sxs-lookup"><span data-stu-id="6bf37-735">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-736">Configurar cuentas y acceder al buzón de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="6bf37-736">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-737">Protección de Outlook mobile (vea <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> para obtener más información).</span><span class="sxs-lookup"><span data-stu-id="6bf37-737">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="6bf37-738">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-738">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-739">Exchange Online configurado y licencias asignadas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-739">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-740"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-740"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-741">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-741">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-742">Asignación de licencias de Power BI.</span><span class="sxs-lookup"><span data-stu-id="6bf37-742">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-743">Implementación de la aplicación Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="6bf37-743">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="6bf37-744">El software cliente en línea como Power BI Desktop debe estar en un nivel mínimo según se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-744">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-745"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-745"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-746">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-746">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-747">Comprobación de la funcionalidad básica de SharePoint que se basa en Project Online.</span><span class="sxs-lookup"><span data-stu-id="6bf37-747">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-748">Adición del servicio de Project Online al espacio empresarial (incluida la adición de las suscripciones a los usuarios).</span><span class="sxs-lookup"><span data-stu-id="6bf37-748">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-749">Configuración del grupo de recursos de empresa (ERP).</span><span class="sxs-lookup"><span data-stu-id="6bf37-749">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-750">Creación del primer proyecto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-750">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="6bf37-751">El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-751">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-752"><strong>Project Online Professional y Premium</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-752"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-753">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-753">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-754">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-754">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-755">Asignar licencias de usuario final mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="6bf37-755">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-756">Instalar Cliente de escritorio de Project Online desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="6bf37-756">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-757">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-757">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-758">Configurar un servidor de distribución in situ único para Cliente de escritorio de Project Online, incluida la ayuda para crear un archivo configuration.xml para usarlo con la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-758">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-759">Conectar Cliente de escritorio de Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="6bf37-759">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="6bf37-760">El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-760">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-761"><strong>SharePoint Online y OneDrive para la Empresa</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-761"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-762">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-762">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-763">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="6bf37-763">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-764">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="6bf37-764">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-765">Aprovisionamiento de usuarios y licencias.</span><span class="sxs-lookup"><span data-stu-id="6bf37-765">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="6bf37-766">Habilitar la creación de sitios para el administrador de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="6bf37-766">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="6bf37-767">Planificar las colecciones de sitios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-767">Planning site collections.</span></span></li>
<li><span data-ttu-id="6bf37-768">Proteger el contenido y administrar los permisos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-768">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="6bf37-769">Configurar las características de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="6bf37-769">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="6bf37-770">Configuración de las características de Entorno híbrido de SharePoint, como la búsqueda híbrida, los sitios híbridos, la taxonomía híbrida, los tipos de contenido, la creación híbrida de sitios sin intervención del administrador (solo SharePoint Server 2013), el iniciador de aplicaciones extendido, OneDrive para la Empresa híbrido y los sitios de extranet.</span><span class="sxs-lookup"><span data-stu-id="6bf37-770">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-771">Su enfoque de migración.</span><span class="sxs-lookup"><span data-stu-id="6bf37-771">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="6bf37-772">Se proporcionan instrucciones adicionales para OneDrive para la Empresa en función de la versión de SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="6bf37-772">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-773">Identificar las opciones de integración y revisar el ancho de banda y la infraestructura de red local y en línea.</span><span class="sxs-lookup"><span data-stu-id="6bf37-773">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-774">Instalación de SharePoint Online 2013 SP1 (si corresponde), planeación e implementación de requisitos de sincronización e identidad, e identificación del cliente de sincronización de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="6bf37-774">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-775">Planeación e implementación de un solo lanzamiento para todos los usuarios (o un lanzamiento por fases).</span><span class="sxs-lookup"><span data-stu-id="6bf37-775">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-776">Asignar licencias, redirigir Mis sitios y bibliotecas de documentos personales a Office 365 (aplicable a SharePoint Online 2013), configurar audiencias para controlar el acceso a OneDrive (aplicable a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="6bf37-776">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="6bf37-777">Redirigir o mover carpetas conocidas a OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6bf37-777">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="6bf37-778">Implementación de la sincronización de cliente de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="6bf37-778">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="6bf37-779">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="6bf37-779">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="6bf37-780">Para obtener información sobre cómo usar la ventaja de FastTrack para la migración de datos a Office 365, vea <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-780">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="6bf37-781"><strong>Para SharePoint híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-781"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="6bf37-782">La configuración híbrida de SharePoint incluye la configuración de búsqueda híbrida, sitios, taxonomía, tipos de contenido, OneDrive para la Empresa, un iniciador de aplicaciones extendido, sitios de extranet y creación de sitios de autoservicio conectados desde local a un único entorno de SharePoint Online de destino.</span><span class="sxs-lookup"><span data-stu-id="6bf37-782">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="6bf37-783">
  <strong>Nota:</strong> La creación de sitios sin servicio no está en el ámbito con servidores locales que ejecutan SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="6bf37-783">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="6bf37-784">Para habilitar SharePoint híbrido, debe tener uno de los siguientes entornos locales de SharePoint Server: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="6bf37-784">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="6bf37-785">
  <strong>Nota:</strong> La actualización de entornos locales de SharePoint a SharePoint Server no está en el ámbito.</span><span class="sxs-lookup"><span data-stu-id="6bf37-785">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="6bf37-786">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="6bf37-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="6bf37-787">Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="6bf37-787">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="6bf37-788">
  <strong>Nota:</strong> Para obtener información sobre las capacidades multigeós, vea <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="6bf37-788">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-789"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-789"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="6bf37-790">Proporcionamos instrucciones remotas para habilitar el servicio Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="6bf37-790">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="6bf37-791">El software cliente en línea debe estar en un nivel mínimo tal como se define en los requisitos del sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">para Microsoft 365 y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-791">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="6bf37-792">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="6bf37-792">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6bf37-793"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-793"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="6bf37-794"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-794"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="6bf37-795"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-795"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="6bf37-796"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-796"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-797">Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-797">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="6bf37-798">

<strong>Infraestructura básica segura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="6bf37-798">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="6bf37-799">Configurar y habilitar una autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseñas sin servicio (SSPR).</span><span class="sxs-lookup"><span data-stu-id="6bf37-799">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-800">Para los clientes que no son de Azure AD Premium, se proporcionan instrucciones para proteger las identidades mediante valores predeterminados de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-800">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-801">Para los clientes premium de Azure AD, se proporcionan instrucciones para proteger sus identidades con acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="6bf37-801">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-802">Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="6bf37-802">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-803">Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-803">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-804">Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="6bf37-804">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-805">Habilitar una pantalla de inicio de sesión personalizada, incluidos logotipo, texto e imágenes con personalización de marca personalizada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-805">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-806">Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="6bf37-806">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-807">Administrar el acceso para los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-807">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-808">Configuración de la unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-808">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-809">Configuración de la unión a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-809">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="6bf37-810">
  
<strong>Supervisión e informes</strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-810">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-811">Habilitar la supervisión remota para AD FS, Azure AD Connect y controladores de dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="6bf37-811">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="6bf37-812">
  
<strong>Gobierno</strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-812">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-813">Administrar la identidad de Azure AD y el ciclo de vida de acceso a escala con la administración de derechos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-813">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="6bf37-814">Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-814">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-815">Revisión de los Términos de uso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-815">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-816">Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="6bf37-816">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="6bf37-817">
  
<strong>Automatización y eficiencias </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-817">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-818">Habilitar Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="6bf37-818">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="6bf37-819">Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos de Office 365 con la administración de grupos de autoservicio de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-819">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-820">Administrar el acceso delegado a aplicaciones empresariales con la administración de grupos delegada de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-820">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-821">Habilitar grupos dinámicos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-821">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-822">Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-822">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="6bf37-823">Active Directory local y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="6bf37-823">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6bf37-824"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-824"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="6bf37-825">Para obtener más información sobre Azure Information Protection, consulte <strong>Microsoft Information Protection</strong> in Security and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Compliance.</span><span class="sxs-lookup"><span data-stu-id="6bf37-825">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="6bf37-826"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-826"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-827">Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) basado en la nube y administración de aplicaciones móviles (MAM) para sus aplicaciones y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-827">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="6bf37-828">Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-828">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="6bf37-829">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="6bf37-829">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-830">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="6bf37-830">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-831">Configurar las identidades que Intune usará aprovechando las identidades locales de Active Directory o de la nube (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="6bf37-831">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-832">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-832">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-833">Configuración de la entidad mdma, según tus necesidades de administración, incluidos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-833">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-834">Establecer Intune como entidad MDM cuando Intune es la única solución MDM.</span><span class="sxs-lookup"><span data-stu-id="6bf37-834">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-835">Proporcionar instrucciones de MDM para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-835">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-836">Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.</span><span class="sxs-lookup"><span data-stu-id="6bf37-836">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-837">Configurar servicios y directivas de administración de MDM como:</span><span class="sxs-lookup"><span data-stu-id="6bf37-837">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-838">Implementación de aplicaciones para cada plataforma compatible a través de vínculos web o vínculos profundos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-838">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-839">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="6bf37-839">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-840">Implementación de correo electrónico, redes inalámbricas y perfiles vpn si tiene una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en su organización.</span><span class="sxs-lookup"><span data-stu-id="6bf37-840">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-841">Conexión al almacén de datos de Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-841">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-842">Integrar Intune con:</span><span class="sxs-lookup"><span data-stu-id="6bf37-842">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-843">Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="6bf37-843">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-844">Soluciones de partners de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).</span><span class="sxs-lookup"><span data-stu-id="6bf37-844">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-845">Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción a una solución de administración de gastos de telecomunicaciones).</span><span class="sxs-lookup"><span data-stu-id="6bf37-845">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-846">Inscribir dispositivos de cada plataforma compatible en Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-846">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="6bf37-847">Proporcionar instrucciones de protección de aplicaciones sobre:</span><span class="sxs-lookup"><span data-stu-id="6bf37-847">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-848">Configurar directivas de protección de aplicaciones para cada plataforma compatible.</span><span class="sxs-lookup"><span data-stu-id="6bf37-848">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-849">Configurar directivas de acceso condicional para aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-849">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-850">Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-850">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-851">Uso de informes de uso de aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-851">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-852">Proporcionar instrucciones de migración desde la administración de equipos heredados a MDM de Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-852">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="6bf37-853">
  
</li>
</ul>
  
<strong>Conexión a la nube</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-853">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="6bf37-854">Le guiaremos para prepararse para adjuntar entornos de Configuration Manager existentes con Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-854">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="6bf37-855">Los pasos detallados dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="6bf37-855">The exact steps depend on your source environment.</span></span> <span data-ttu-id="6bf37-856">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="6bf37-856">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="6bf37-857">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="6bf37-857">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-858">Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="6bf37-858">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-859">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="6bf37-859">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-860">Proporcionar instrucciones para configurar la unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6bf37-860">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-861">Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.</span><span class="sxs-lookup"><span data-stu-id="6bf37-861">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-862">Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.</span><span class="sxs-lookup"><span data-stu-id="6bf37-862">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-863">Configurar cargas de trabajo compatibles que quiera cambiar a Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-863">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-864">Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-864">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="6bf37-865"><strong>Implementar Outlook mobile para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarle a implementar Outlook mobile para iOS y Android de forma segura en su organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.</span><span class="sxs-lookup"><span data-stu-id="6bf37-865"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="6bf37-866">Los pasos para implementar Outlook mobile para iOS y Android de forma segura con Intune dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="6bf37-866">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="6bf37-867">Puede incluir:</span><span class="sxs-lookup"><span data-stu-id="6bf37-867">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-868">Descargar las aplicaciones outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal a través de la Tienda de aplicaciones de Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="6bf37-868">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-869">Proporcionar instrucciones sobre cómo configurar:</span><span class="sxs-lookup"><span data-stu-id="6bf37-869">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-870">La implementación de aplicaciones de Outlook para iOS y Android, Microsoft Authenticator e Intune Company Portal con Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-870">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-871">Directivas de protección de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-871">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-872">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="6bf37-872">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-873">Directivas de configuración de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-873">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="6bf37-874">Los administradores de TI necesitan que las infraestructuras de vpn, red inalámbrica y entidad de certificación ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-874">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="6bf37-875"><strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar autoridades de certificados, redes inalámbricas, infraestructuras VPN o certificados de inserción mdm de Apple para Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-875"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="6bf37-876"><strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube.</span><span class="sxs-lookup"><span data-stu-id="6bf37-876"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="6bf37-877">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="6bf37-878"><strong>Intune integrado con la Protección contra amenazas avanzada de Microsoft Defender (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-878"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="6bf37-879"><strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con ATP de Microsoft Defender y crear directivas de cumplimiento de dispositivos en función de su evaluación del nivel de riesgo de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-879"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="6bf37-880">No proporcionamos asistencia en compras, licencias o activación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-880">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="6bf37-881">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-881">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="6bf37-882"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-882"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="6bf37-883">Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="6bf37-883">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="6bf37-884">Windows 10</span><span class="sxs-lookup"><span data-stu-id="6bf37-884">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6bf37-885"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-885"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="6bf37-886"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-886"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="6bf37-887"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-887"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6bf37-888"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-888"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-889">Proporcionamos instrucciones para actualizar de Windows 7 Professional y Windows 8.1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="6bf37-889">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="6bf37-890">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-890">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-891">Comprender la intención de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-891">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-892">Evaluar el entorno de origen y los requisitos (asegúrese de que Microsoft Endpoint Configuration Manager se actualice al nivel requerido para admitir la implementación de Windows 10).</span><span class="sxs-lookup"><span data-stu-id="6bf37-892">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-893">Implementación de Aplicaciones de Windows 10 Enterprise y Microsoft 365 con Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-893">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-894">Te recomendamos opciones para evaluar tus aplicaciones de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-894">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-895">Habilitar el uso de Análisis de escritorio y la guía mediante la creación de un plan de implementación de Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="6bf37-895">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-896">Evaluación de compatibilidad de Aplicaciones de Microsoft 365 aprovechando el panel de preparación de Office 365 en Configuration Manager o con readiness toolkit independiente para Office, además de asistencia para implementar Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-896">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-897">Crear una lista de comprobación de corrección sobre lo que necesita hacer para que el entorno de origen se asemeja a los requisitos mínimos para una implementación correcta.</span><span class="sxs-lookup"><span data-stu-id="6bf37-897">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-898">Proporcionar instrucciones de actualización para los dispositivos existentes a Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesarios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-898">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-899">Proporcionar instrucciones de actualización para admitir el movimiento de implementación existente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-899">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="6bf37-900">FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-900">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="6bf37-901">Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="6bf37-901">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-902">Implementar aplicaciones de Microsoft 365 con Configuration Manager como parte de la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-902">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="6bf37-903">Proporcionar instrucciones para ayudar a su organización a mantenerse al día con Las aplicaciones de Windows 10 Enterprise y Microsoft 365 con su entorno de Configuration Manager existente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-903">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="6bf37-904">
  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-904">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="6bf37-905">Actualizar Configuration Manager a la rama actual.</span><span class="sxs-lookup"><span data-stu-id="6bf37-905">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-906">Crear imágenes personalizadas para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-906">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-907">Crear y admitir scripts de implementación para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-907">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-908">Convertir un sistema Windows 10 del BIOS a la Interfaz de firmware extensible unificado (UEFI).</span><span class="sxs-lookup"><span data-stu-id="6bf37-908">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-909">Habilitar las características de seguridad de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-909">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-910">Configurar los Servicios de implementación de Windows (WDS) para el arranque del Entorno de ejecución previo al inicio (PXE).</span><span class="sxs-lookup"><span data-stu-id="6bf37-910">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-911">Usar Microsoft Deployment Toolkit (MDT) para capturar e implementar imágenes de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-911">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-912">Usar la Herramienta de migración de estado de usuario (USMT).</span><span class="sxs-lookup"><span data-stu-id="6bf37-912">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="6bf37-913">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-913">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="6bf37-914">Para actualizar su PC, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-914">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-915">Sistema operativo de origen: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="6bf37-915">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-916">Dispositivos: factor de forma de escritorio, bloc de notas o tableta.</span><span class="sxs-lookup"><span data-stu-id="6bf37-916">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-917">Sistema operativo de destino: Ventana 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="6bf37-917">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="6bf37-918">Para actualizar la infraestructura, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-918">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-919">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="6bf37-919">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-920">La versión de Configuration Manager debe ser compatible con la versión de destino de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-920">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="6bf37-921">Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Soporte para Windows 10 en Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-921">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="6bf37-922"><strong>Protección contra amenazas avanzada de Microsoft Defender (ATP).</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-923">La Protección contra amenazas avanzada de Microsoft Defender (ATP) es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas y actuar ante ellas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-923">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="6bf37-924">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-924">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-925">Implementar las tecnologías para proteger los puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-925">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-926">Configuración de perfiles de restricción de dispositivos y protección de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-926">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-927">Evaluación de la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios antivirus de Windows Defender u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-927">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-928">Evaluar el estado de los servicios antivirus de Windows u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-928">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-929">Evaluación de servidores proxy y firewalls que restringen el tráfico de red.</span><span class="sxs-lookup"><span data-stu-id="6bf37-929">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-930">Para habilitar el servicio ATP de Microsoft Defender, explique cómo implementar un perfil de agente de ATP con un punto de conexión integrado.</span><span class="sxs-lookup"><span data-stu-id="6bf37-930">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-931">Instrucciones de implementación, asistencia de configuración y educación sobre:</span><span class="sxs-lookup"><span data-stu-id="6bf37-931">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-932">Administración de amenazas y vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="6bf37-932">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-933">Reducción de la superficie de ataque.</span><span class="sxs-lookup"><span data-stu-id="6bf37-933">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-934">Protección de nueva generación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-934">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-935">Detección y respuesta de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-935">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-936">Investigación y corrección automatizadas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-936">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="6bf37-937">Atp de Microsoft Defender (se requieren licencias de Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="6bf37-937">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="6bf37-938">Puntuación de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-938">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-939">Revisión de simulaciones y tutoriales (como escenarios de práctica, malware falso e investigaciones automatizadas).</span><span class="sxs-lookup"><span data-stu-id="6bf37-939">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-940">Información general sobre las características de informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-940">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-941">Integrar Protección contra amenazas avanzadas de Office 365 con Protección contra amenazas avanzada de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="6bf37-941">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-942">Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="6bf37-942">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-943">Los siguientes sistemas operativos:</span><span class="sxs-lookup"><span data-stu-id="6bf37-943">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-944">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="6bf37-944">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-945">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="6bf37-945">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-946">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="6bf37-946">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-947">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="6bf37-947">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-948">Windows Server Semi-Annual Channel (SAC) versión 1803.</span><span class="sxs-lookup"><span data-stu-id="6bf37-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-949">macOS versiones 10.13, 10.14 y 10.15.</span><span class="sxs-lookup"><span data-stu-id="6bf37-949">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="6bf37-950">
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la versión más reciente de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior).</span><span class="sxs-lookup"><span data-stu-id="6bf37-950">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="6bf37-951"></li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-951"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="6bf37-952">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="6bf37-952">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-953">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-953">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-954">Administración continua y respuesta ante amenazas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-954">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-955">Incorporación o configuración para los siguientes agentes de Protección contra amenazas avanzada de Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="6bf37-955">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-956">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="6bf37-956">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-957">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="6bf37-957">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-958">Linux.</span><span class="sxs-lookup"><span data-stu-id="6bf37-958">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-959">Dispositivos móviles (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="6bf37-959">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="6bf37-960">Infraestructura de escritorio virtual (VDI) (persistente o no persistente).</span><span class="sxs-lookup"><span data-stu-id="6bf37-960">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-961">Configuración y incorporación de servidores:</span><span class="sxs-lookup"><span data-stu-id="6bf37-961">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-962">Configurar un servidor proxy para comunicaciones sin conexión.</span><span class="sxs-lookup"><span data-stu-id="6bf37-962">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-963">Configuración de paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.</span><span class="sxs-lookup"><span data-stu-id="6bf37-963">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-964">Incorporación de servidores al Centro de seguridad de Azure.</span><span class="sxs-lookup"><span data-stu-id="6bf37-964">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-965">Servidores no administrados por Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="6bf37-965">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-966">Configuración y incorporación de macOS:</span><span class="sxs-lookup"><span data-stu-id="6bf37-966">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-967">Implementación manual basada en Intune.</span><span class="sxs-lookup"><span data-stu-id="6bf37-967">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-968">Implementación basada en JAMF.</span><span class="sxs-lookup"><span data-stu-id="6bf37-968">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="6bf37-969">Otra implementación basada en productos de administración de dispositivos móviles (MDM).</span><span class="sxs-lookup"><span data-stu-id="6bf37-969">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-970">Implementación manual.</span><span class="sxs-lookup"><span data-stu-id="6bf37-970">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="6bf37-971">Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:</span><span class="sxs-lookup"><span data-stu-id="6bf37-971">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-972">Aislamiento basado en hardware.</span><span class="sxs-lookup"><span data-stu-id="6bf37-972">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-973">Control de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-973">App control.</span></span>  
  </li>
<li> <span data-ttu-id="6bf37-974">Control de dispositivo.</span><span class="sxs-lookup"><span data-stu-id="6bf37-974">Device control.</span></span></li>
<li>  
  <span data-ttu-id="6bf37-975">Protección contra vulnerabilidades de seguridad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-975">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-976">Firewall de red.</span><span class="sxs-lookup"><span data-stu-id="6bf37-976">Network firewall.</span></span>  
  </li>

<ul>
<li> <span data-ttu-id="6bf37-977">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="6bf37-977">Windows Hello</span></span></li>
<li> <span data-ttu-id="6bf37-978">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="6bf37-978">Credential Guard</span></span></li>
</ul>

</ul></li>
<li> <span data-ttu-id="6bf37-979">Configuración o administración de BitLocker.</span><span class="sxs-lookup"><span data-stu-id="6bf37-979">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="6bf37-980">Inscripción o configuración de Expertos en amenazas de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="6bf37-980">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-981">Configuración o aprendizaje que revisa las conexiones DE API o de información de seguridad y administración de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="6bf37-981">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-982">Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="6bf37-982">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-983">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="6bf37-983">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-984">Formación u instrucciones sobre el uso o creación de consultas de Kusto.</span><span class="sxs-lookup"><span data-stu-id="6bf37-984">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="6bf37-985">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-985">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="6bf37-986">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="6bf37-986">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6bf37-987"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-987"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="6bf37-988"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-988"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="6bf37-989"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-989"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6bf37-990"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-990"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="6bf37-991">Proporcionamos instrucciones de implementación para la incorporación a Windows Virtual Desktop (un servicio de virtualización de aplicaciones y escritorio).</span><span class="sxs-lookup"><span data-stu-id="6bf37-991">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="6bf37-992">Windows Virtual Desktop aprovecha la experiencia de varias sesiones de Windows 10 y está optimizado para Aplicaciones de Microsoft 365 para empresas con seguridad y administración integradas para Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-992">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="6bf37-993">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-993">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="6bf37-994">Implementar el entorno de Escritorio virtual de Windows con windows 10 Enterprise multi-sesión y aplicaciones de Microsoft 365 para empresas con lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="6bf37-994">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="6bf37-995">Imagen de Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="6bf37-995">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="6bf37-996">Imagen compartida.</span><span class="sxs-lookup"><span data-stu-id="6bf37-996">Shared image.</span></span></li>
<li><span data-ttu-id="6bf37-997">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="6bf37-997">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="6bf37-998">Configuración de FSLogix:</span><span class="sxs-lookup"><span data-stu-id="6bf37-998">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="6bf37-999">Implementación del agente FSLogix con el contenedor de perfiles.</span><span class="sxs-lookup"><span data-stu-id="6bf37-999">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="6bf37-1000">Implementación del agente FSLogix con el contenedor de Office.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1000">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="6bf37-1001">Configurar la carpeta FSLogix con exclusiones de contenido.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1001">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="6bf37-1002">Implementación de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1002">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="6bf37-1003">Implementación de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1003">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="6bf37-1004">Conexión con clientes de Escritorio virtual de Windows.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1004">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="6bf37-1005">

<strong>Lo siguiente está fuera del ámbito</strong>
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1005">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="6bf37-1006">Administración de proyectos de la implementación de Windows Virtual Desktop del cliente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1006">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="6bf37-1007">Implementación y virtualización de aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1007">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="6bf37-1008">Imágenes personalizadas.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1008">Custom images.</span></span></li>
<li><span data-ttu-id="6bf37-1009">Migraciones y escenarios en los que participan VMware y Citrix.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1009">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="6bf37-1010">Escenarios de Linux.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1010">Linux scenarios.</span></span></li>
<li><span data-ttu-id="6bf37-1011">Conversión o migraciones de perfiles de usuario.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1011">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="6bf37-1012">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1012">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="6bf37-1013">Ya debería tener lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="6bf37-1013">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="6bf37-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licencias de Windows Virtual Desktop</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="6bf37-1015">Redes de Azure:</span><span class="sxs-lookup"><span data-stu-id="6bf37-1015">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="6bf37-1016">Creación y subred de red virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="6bf37-1016">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="6bf37-1017">Firewall y grupos de seguridad de red.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1017">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="6bf37-1018">VPN y ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1018">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="6bf37-1019">Enrutamiento a Azure desde local.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1019">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="6bf37-1020">Reglas de firewall para permitir la conectividad a Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1020">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="6bf37-1021">Para obtener más información, vea <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1021">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="6bf37-1022">Configuración general de Azure AD:</span><span class="sxs-lookup"><span data-stu-id="6bf37-1022">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="6bf37-1023">Estrategia de <i>identidad (solo puede usar una de las tres opciones siguientes):</i>
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1023">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="6bf37-1024">Active Directory con Azure AD Connect en Azure.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1024">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="6bf37-1025">Active Directory con Azure AD Connect local a través de VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1025">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="6bf37-1026">Servicios de dominio de Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="6bf37-1026">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="6bf37-1027">App Assure</span><span class="sxs-lookup"><span data-stu-id="6bf37-1027">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6bf37-1028"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-1028"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="6bf37-1029"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-1029"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="6bf37-1030"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-1030"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="6bf37-1031"><strong>Asesoría de aplicaciones</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-1031"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="6bf37-1032">App Assure es un servicio diseñado para solucionar problemas relacionados con la compatibilidad de aplicaciones de Windows 10 y Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1032">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="6bf37-1033">Cuando solicitas el servicio App Assure, trabajamos contigo para solucionar problemas válidos de la aplicación sin ningún costo adicional para ti con una suscripción elegible.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1033">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="6bf37-1034">También proporcionamos instrucciones a los clientes que se enfrentan a problemas de compatibilidad al implementar Windows Virtual Desktop y Microsoft Edge y hacemos todos los esfuerzos razonables para resolver problemas de compatibilidad.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1034">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="6bf37-1035">Proporcionamos asistencia de corrección para las aplicaciones implementadas en los siguientes productos de Microsoft:</span><span class="sxs-lookup"><span data-stu-id="6bf37-1035">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="6bf37-1036"><strong>Windows 10 </strong> (incluidos los dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="6bf37-1036"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="6bf37-1037"><strong>Aplicaciones de Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="6bf37-1037"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="6bf37-1038"><strong>Microsoft Edge :</strong> Para obtener instrucciones de implementación, vea <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1038"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-1039"><strong>Escritorio virtual de</strong> - Windows Para obtener más información, consulta <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">¿Qué es Windows Virtual Desktop?</a> y Preguntas más frecuentes sobre <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">las múltiples sesiones de Windows 10 Enterprise</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1039"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="6bf37-1040">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1040">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="6bf37-p147">Inventario y pruebas de aplicaciones para determinar lo que funciona y lo que no en Windows 10 y en las Aplicaciones de Microsoft 365. Para obtener más información sobre este proceso, visite el <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de implementación de escritorios</a>. Si está interesado en una evaluación detallada de la preparación para la actualización, complete el formulario <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitud de cliente para la evaluación del escritorio moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-p147">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="6bf37-1044">Buscar instrucciones de compatibilidad y soporte técnico de Windows 10 en aplicaciones ISV de terceros.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1044">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="6bf37-1045">Para más información, vea <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Análisis de escritorio</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1045">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="6bf37-1046">Servicios de solo empaquetado de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1046">App packaging-only services.</span></span> <span data-ttu-id="6bf37-1047">Sin embargo, el equipo de App Assure crea paquetes de aplicaciones que hemos corregido para Windows 10 para asegurarse de que se pueden implementar en el entorno del cliente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1047">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="6bf37-1048">

<strong>Entre las responsabilidades del cliente se incluyen</strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1048">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="6bf37-1049">Creación de un inventario de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1049">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="6bf37-1050">Validación de esas aplicaciones en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1050">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="6bf37-1051">
<strong>Nota:</strong>  Microsoft no puede realizar cambios en el código fuente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1051">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="6bf37-1052">Sin embargo, el equipo de App Assure puede proporcionar instrucciones a los desarrolladores de aplicaciones si el código fuente está disponible para sus aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1052">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="6bf37-1053">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1053">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="6bf37-1054"><strong>Aplicaciones de Windows 10 y Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1054"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-1055">Las aplicaciones que funcionaban en Windows 7, Windows 8.1, Office 2010 y Office 2013 también funcionan en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1055">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="6bf37-1056">
<strong>Windows 10 en ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1056">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="6bf37-1057">Las aplicaciones que funcionaron en Windows 7, Office 2010 o versiones posteriores también funcionan en Aplicaciones de Windows 10 y Microsoft 365 en dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1057">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="6bf37-1058">
  <strong>Nota:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1058">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="6bf37-1059">La emulación de x64 (64 bits) está disponible en versión preliminar para los clientes que participan en <a href="https://insider.windows.com/">el Programa Windows Insider</a>.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1059">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="6bf37-1060">Para clientes que no son de Windows Insider en Windows 10 versión 2004 (o posterior), ARM64 Photoshop es compatible con OpenCL y <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack.</a></span><span class="sxs-lookup"><span data-stu-id="6bf37-1060">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="6bf37-1061">Los clientes del Programa Windows Insider pueden descargar una versión insider del OpenCL y el Paquete de compatibilidad de OpenGL para usarlo con aplicaciones adicionales.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1061">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="6bf37-1062">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1062">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-1063">Si las aplicaciones web o los sitios funcionan en Internet Explorer 11, las versiones compatibles de Google Chrome o cualquier versión de Microsoft Edge, también funcionarán con Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1063">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-1064">A medida que la web está en constante evolución, asegúrese de revisar esta lista publicada de cambios que afectan a la compatibilidad de sitios <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">conocidos para Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="6bf37-1064">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="6bf37-1065">
  <strong>Escritorio virtual de Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1065">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="6bf37-1066">Las aplicaciones virtualizadas que se ejecutan en el host de sesión de Escritorio remoto (RDSH) de Windows Server también se ejecutan en Windows 10 Enterprise multisesión como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1066">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-1067">Las aplicaciones que se ejecutan en cualquier entorno de infraestructura de escritorio virtual (VDI) de Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1067">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-1068">Las aplicaciones que se ejecutan en dispositivos cliente con Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1068">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="6bf37-1069">
  <strong>Nota:</strong> Las exclusiones y limitaciones de compatibilidad de varias sesiones de Windows 10 Enterprise incluyen:</span><span class="sxs-lookup"><span data-stu-id="6bf37-1069">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="6bf37-1070">Redirección limitada del hardware.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1070">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-1071">Las aplicaciones que hacen un uso intensivo de A/V pueden tener una capacidad reducida.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1071">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="6bf37-1072">Las aplicaciones de 16 bits no son compatibles con Windows Virtual Desktop de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1072">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="6bf37-1073">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="6bf37-1073">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6bf37-1074"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-1074"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="6bf37-1075"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-1075"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="6bf37-1076"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="6bf37-1076"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="6bf37-1077"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="6bf37-1077"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="6bf37-1078">Proporcionamos ayuda para la compatibilidad y la implementación remota y la adopción para:</span><span class="sxs-lookup"><span data-stu-id="6bf37-1078">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="6bf37-1079">Implementación de Microsoft Edge en Windows 10 con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="6bf37-1079">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-1080">Configuración de Microsoft Edge (mediante directivas de grupo o configuración de aplicaciones de Intune y directivas de aplicaciones).</span><span class="sxs-lookup"><span data-stu-id="6bf37-1080">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="6bf37-1081">Inventario de la lista de sitios que pueden requerir su uso en modo Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1081">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="6bf37-1082">Habilitar el modo de Internet Explorer con la lista de sitios de empresa existente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1082">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="6bf37-1083">(Para obtener más información, vea <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span><span class="sxs-lookup"><span data-stu-id="6bf37-1083">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="6bf37-1084">Además, si tienes una aplicación web o un sitio que funciona con Internet Explorer o Google Chrome y tienes problemas de compatibilidad, te ofrecemos instrucciones para resolver el problema sin costo adicional.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1084">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="6bf37-1085">Para solicitar compatibilidad con App Assure, inicie sesión en el <a href="https://fasttrack.microsoft.com/portal#/signin">portal de FastTrack</a> para iniciar una interacción.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1085">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="6bf37-1086">Instrucciones de planeación para la adopción y configuración perimetrales para marcadores de Microsoft Search.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1086">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="6bf37-1087">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="6bf37-1087">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="6bf37-1088">Administración de proyectos de la implementación de Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1088">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="6bf37-1089">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="6bf37-1089">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
