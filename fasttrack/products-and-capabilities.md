---
title: Productos y capacidades
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias antes de poder comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que haga que el entorno de origen se ajuste a los requisitos mínimos para una incorporación correcta.
ms.openlocfilehash: 9a4546b248a739ee980f1300b9575e780e383c1a
ms.sourcegitcommit: 736a256276ead91385e1ec37b8a120b22259c4ea
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/24/2021
ms.locfileid: "52626689"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="7dff9-104">Productos y capacidades</span><span class="sxs-lookup"><span data-stu-id="7dff9-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="7dff9-105">Servicios y escenarios admitidos por FastTrack</span><span class="sxs-lookup"><span data-stu-id="7dff9-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="7dff9-106">En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias antes de poder comenzar.</span><span class="sxs-lookup"><span data-stu-id="7dff9-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="7dff9-107">En función de la configuración actual, trabajamos con usted para crear un plan de corrección que haga que el entorno de origen se ajuste a los requisitos mínimos para una incorporación correcta.</span><span class="sxs-lookup"><span data-stu-id="7dff9-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="7dff9-108">FastTrack proporciona instrucciones para ayudarle primero con las funcionalidades principales (comunes para todos los Microsoft Online Services) y luego con la incorporación de cada servicio elegible:</span><span class="sxs-lookup"><span data-stu-id="7dff9-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="7dff9-109">General</span><span class="sxs-lookup"><span data-stu-id="7dff9-109">General</span></span>](#general)
  - [<span data-ttu-id="7dff9-110">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="7dff9-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="7dff9-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="7dff9-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="7dff9-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="7dff9-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="7dff9-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="7dff9-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="7dff9-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="7dff9-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="7dff9-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="7dff9-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="7dff9-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="7dff9-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="7dff9-117">Para obtener información sobre las expectativas de entorno de origen para Office 365 Administración Pública, vea [Expectativas de entorno de origen para Office 365 Administración Pública](/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="7dff9-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="7dff9-118">General</span><span class="sxs-lookup"><span data-stu-id="7dff9-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7dff9-119"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7dff9-120"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="7dff9-121"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="7dff9-122"><strong>Incorporación principal</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-123">Proporcionamos instrucciones remotas sobre la incorporación principal, que implica el aprovisionamiento de servicios, el inquilino y la integración de identidades.</span><span class="sxs-lookup"><span data-stu-id="7dff9-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="7dff9-124">También incluye pasos para proporcionar una base para la incorporación de servicios como Exchange Online, SharePoint Online y Microsoft Teams, incluida una discusión sobre <a href="/office365/enterprise/office-365-network-connectivity-principles">seguridad,</a>conectividad de red y cumplimiento .</span><span class="sxs-lookup"><span data-stu-id="7dff9-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="7dff9-125">La incorporación de uno o más servicios elegibles puede empezar al finalizar la incorporación principal.</span><span class="sxs-lookup"><span data-stu-id="7dff9-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="7dff9-126"></li>
</ul>  

<strong> Integración de identidades </strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="7dff9-127">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="7dff9-128">Preparación de identidades locales de Active Directory para la sincronización con Azure Active Directory (Azure AD), incluida la instalación y configuración de Azure AD Conectar (bosque único o múltiple) y licencias (incluidas las licencias basadas en grupos).</span><span class="sxs-lookup"><span data-stu-id="7dff9-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="7dff9-129">Creación de identidades en la nube, incluida la importación masiva y las licencias, incluido el uso de licencias basadas en grupos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="7dff9-130">Elegir y habilitar el método de autenticación correcto para el recorrido en la nube, la sincronización hash de contraseña, la autenticación de paso a través o los servicios de federación de Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="7dff9-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="7dff9-131">Elegir y habilitar una experiencia de autenticación más conveniente para los usuarios con autenticación sin contraseña (Fast Identity Online (FIDO)2 o Microsoft Authenticator App).</span><span class="sxs-lookup"><span data-stu-id="7dff9-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="7dff9-132">Habilitar AD FS para clientes con un único bosque de Active Directory e identidades sincronizadas con la herramienta de Conectar Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="7dff9-133">Esto requiere Windows Server 2012 R2 Active Directory Federation Services 2.0 o posterior.</span><span class="sxs-lookup"><span data-stu-id="7dff9-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="7dff9-134">Migrar la autenticación de AD FS a Azure AD mediante la sincronización hash de contraseña o la autenticación de paso a través.</span><span class="sxs-lookup"><span data-stu-id="7dff9-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="7dff9-135">Migración de aplicaciones preinstaladas (como aplicaciones saas) de software como servicio (SaaS) de la galería de Azure AD) de AD FS a Azure AD para el inicio de sesión único (SSO).</span><span class="sxs-lookup"><span data-stu-id="7dff9-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="7dff9-136">Habilitar integraciones de aplicaciones SaaS con SSO desde la galería de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="7dff9-137">Habilitar el aprovisionamiento automático de usuarios para aplicaciones SaaS integradas previamente, tal como se muestra en la lista de <a href="/azure/active-directory/saas-apps/tutorial-list">tutoriales </a> de integración de aplicaciones (limitado a aplicaciones SaaS de la galería de Azure AD y aprovisionamiento saliente solamente).</span><span class="sxs-lookup"><span data-stu-id="7dff9-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="7dff9-138"><strong>Habilitación de red </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="7dff9-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="7dff9-139">Como parte de las ventajas de FastTrack, le recomendamos que se informe de los procedimientos recomendados para conectarse a los servicios en la nube para garantizar los niveles más altos de rendimiento de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="7dff9-140"><strong>Bosques de Active Directory</strong> Tienen el nivel de bosque funcional establecido en Windows Server 2003 en adelante, con la siguiente configuración de bosque:</span><span class="sxs-lookup"><span data-stu-id="7dff9-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-141">Un solo bosque de Active Directory.</span><span class="sxs-lookup"><span data-stu-id="7dff9-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-142">Un solo bosque de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="7dff9-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-143">Varios bosques de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="7dff9-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-144">Varios bosques de cuentas de Active Directory con uno de los bosques que es un bosque de cuentas de Active Directory centralizado que incluye Exchange o Lync 2010, Lync 2013 o Skype Empresarial.</span><span class="sxs-lookup"><span data-stu-id="7dff9-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-145">Varios bosques de cuentas de Active Directory, cada uno con su propia organización de Exchange.</span><span class="sxs-lookup"><span data-stu-id="7dff9-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-146">Tareas necesarias para la configuración e integración del espacio empresarial con Azure Active Directory, si es necesario.</span><span class="sxs-lookup"><span data-stu-id="7dff9-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="7dff9-147">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="7dff9-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="7dff9-148">Para escenarios de Active Directory con varios bosques, si se implementa Lync 2010, Lync 2013 o Skype Empresarial, debe implementarse en el mismo bosque de Active Directory que Exchange.</span><span class="sxs-lookup"><span data-stu-id="7dff9-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-149">Al implementar varios bosques de Active Directory con varias organizaciones de Exchange en una configuración multi híbrido de Exchange, no se admiten espacios de nombres de nombre principal de usuario compartido (UPN) entre bosques de origen.</span><span class="sxs-lookup"><span data-stu-id="7dff9-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="7dff9-150">Los espacios de nombres SMTP principales entre las organizaciones de Exchange también deben estar separados.</span><span class="sxs-lookup"><span data-stu-id="7dff9-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="7dff9-151">Para más información, consulte <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implementaciones híbridas con varios bosques de Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-152">Para todas las configuraciones de varios bosques, la implementación de Servicios de federación de Active Directory (AD FS) está fuera del ámbito.</span><span class="sxs-lookup"><span data-stu-id="7dff9-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="7dff9-153">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="7dff9-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="7dff9-154"><strong>Aplicaciones de Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-155">Proporcionamos instrucciones de implementación remota para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-156">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-157">Asignar licencias de usuario final y basadas en dispositivos mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="7dff9-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-158">Instalar Aplicaciones de Microsoft 365 desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="7dff9-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-159">Instalar aplicaciones de Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile y PowerPoint Mobile) en los dispositivos iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="7dff9-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-160">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-161">Selección y configuración de una instalación local o en la nube.</span><span class="sxs-lookup"><span data-stu-id="7dff9-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-162">Creación de la configuración XML de la herramienta de implementación de Office con la herramienta de personalización de Office o XML nativo para configurar el paquete de implementación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-163">Implementar mediante Microsoft Endpoint Configuration Manager, incluida la ayuda con la creación del empaquetado de Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="7dff9-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="7dff9-164">Además, si tienes una macro o complemento que funcionaba con versiones anteriores de Office y experimentas problemas de compatibilidad, proporcionamos instrucciones para corregir el problema de compatibilidad sin costo adicional a través del programa App Assure.</span><span class="sxs-lookup"><span data-stu-id="7dff9-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="7dff9-165">Consulta la <strong>parte de App Assure</strong> de <a href="#windows-10">Windows 10</a> para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="7dff9-166">El software cliente en línea debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="7dff9-167"><strong>Estado de la red</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-168">Proporcionamos instrucciones remotas para obtener e interpretar datos clave de conectividad de red de su entorno que muestran cómo se alinean los sitios de su organización con los <a href="/office365/enterprise/office-365-network-connectivity-principles">principios</a>de conectividad de red de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="7dff9-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="7dff9-169">Esto resalta la puntuación de red que afecta directamente a la velocidad de migración, la experiencia del usuario, el rendimiento del servicio y la confiabilidad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="7dff9-170">También le guiaremos a través de los pasos de corrección resaltados por estos datos para ayudarle a mejorar la puntuación de red.</span><span class="sxs-lookup"><span data-stu-id="7dff9-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="7dff9-171">Microsoft 365 Acceso al Centro de administración.</span><span class="sxs-lookup"><span data-stu-id="7dff9-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-172">Se requieren versiones actualizadas de Microsoft 365 aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-173">Servicios de ubicación habilitados según las recomendaciones de rendimiento de red <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">en el Centro Microsoft 365 administración (versión preliminar).</a></span><span class="sxs-lookup"><span data-stu-id="7dff9-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="7dff9-174">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="7dff9-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7dff9-175"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7dff9-176"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="7dff9-177"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="7dff9-178"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-179">Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="7dff9-180">

<strong>Infraestructura básica segura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="7dff9-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="7dff9-181">Configurar y habilitar una autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseñas sin servicio (SSPR).</span><span class="sxs-lookup"><span data-stu-id="7dff9-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="7dff9-182">Implementación de FIDO2 o Microsoft Authenticator app.</span><span class="sxs-lookup"><span data-stu-id="7dff9-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="7dff9-183">Para clientes que no son de Azure AD Premium, se proporcionan instrucciones para proteger las identidades mediante valores predeterminados de seguridad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-184">Para los clientes premium de Azure AD, se proporcionan instrucciones para proteger sus identidades con acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="7dff9-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-185">Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="7dff9-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-186">Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-187">Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="7dff9-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-188">Habilitar una pantalla de inicio de sesión personalizada, incluidos logotipo, texto e imágenes con personalización de marca personalizada.</span><span class="sxs-lookup"><span data-stu-id="7dff9-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-189">Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="7dff9-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-190">Administrar el acceso de los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-191">Configuración de la unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-192">Configuración de la unión a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="7dff9-193">
  
<strong>Supervisión e informes</strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="7dff9-194">Habilitar la supervisión remota para AD FS, Azure AD Conectar y controladores de dominio con Azure AD Conectar Health.</span><span class="sxs-lookup"><span data-stu-id="7dff9-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="7dff9-195">
  
<strong>Gobierno</strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="7dff9-196">Administrar la identidad de Azure AD y el ciclo de vida de acceso a escala con la administración de derechos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="7dff9-197">Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-198">Revisión de los Términos de uso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-199">Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="7dff9-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="7dff9-200">
  
<strong>Automatización y eficiencias </strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="7dff9-201">Habilitar Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="7dff9-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="7dff9-202">Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos Office 365 con la administración de grupos de autoservicio de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-203">Administrar el acceso delegado a aplicaciones empresariales con la administración de grupos delegada de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-204">Habilitar grupos dinámicos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-205">Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="7dff9-206">Active Directory local y su entorno se han preparado para azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con las características de Azure AD y Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="7dff9-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="7dff9-207"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="7dff9-208">Para obtener más información sobre Azure Information Protection, consulte <strong>Microsoft Information Protection</strong> más adelante en esta tabla.</span><span class="sxs-lookup"><span data-stu-id="7dff9-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="7dff9-209"><strong>Descubrir & responder</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="7dff9-210"><strong>eDiscovery avanzado</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="7dff9-211">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="7dff9-212">Crear un nuevo caso.</span><span class="sxs-lookup"><span data-stu-id="7dff9-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="7dff9-213">Poner a los custodios en espera.</span><span class="sxs-lookup"><span data-stu-id="7dff9-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-214">Realizar búsquedas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="7dff9-215">Agregar los resultados de búsqueda a un conjunto de revisión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="7dff9-216">Ejecutar análisis en un conjunto de revisión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-217">Revisar y etiquetar documentos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-218">Exportar datos desde el conjunto de revisión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="7dff9-219">Importar datos que no Office 365 datos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="7dff9-220"><strong>Auditoría avanzada</strong> (solo compatible con E5)</span><span class="sxs-lookup"><span data-stu-id="7dff9-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="7dff9-221">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="7dff9-222">Habilitar la auditoría avanzada.</span><span class="sxs-lookup"><span data-stu-id="7dff9-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="7dff9-223">Realizar una interfaz de usuario de registro de auditoría de búsqueda y comandos básicos de PowerShell de auditoría.</span><span class="sxs-lookup"><span data-stu-id="7dff9-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="7dff9-224">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="7dff9-225">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="7dff9-226">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="7dff9-227">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="7dff9-228">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="7dff9-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="7dff9-229">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="7dff9-230">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="7dff9-231">

<strong>Lo siguiente está fuera del ámbito </strong> 
</span><span class="sxs-lookup"><span data-stu-id="7dff9-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="7dff9-232">Scripting o codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="7dff9-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="7dff9-233">API de exhibición de documentos electrónicos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="7dff9-234">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="7dff9-235">Límites de cumplimiento y filtros de seguridad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="7dff9-236">Investigaciones de datos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="7dff9-237">Solicitudes del interesado.</span><span class="sxs-lookup"><span data-stu-id="7dff9-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="7dff9-238">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="7dff9-239">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="7dff9-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="7dff9-240">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="7dff9-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="7dff9-241">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="7dff9-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="7dff9-242"><strong>Administración de riesgos de Insider</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="7dff9-243">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="7dff9-244">Crear directivas y revisar la configuración.</span><span class="sxs-lookup"><span data-stu-id="7dff9-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="7dff9-245">Acceso a informes y alertas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="7dff9-246">Creación de casos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="7dff9-247">Creación de plantillas de aviso.</span><span class="sxs-lookup"><span data-stu-id="7dff9-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="7dff9-248">Instrucciones para crear el conector de recursos humanos (HR).</span><span class="sxs-lookup"><span data-stu-id="7dff9-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="7dff9-249">

<strong> Cumplimiento de comunicaciones </strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="7dff9-250">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="7dff9-251">Crear directivas y revisar la configuración.</span><span class="sxs-lookup"><span data-stu-id="7dff9-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="7dff9-252">Acceso a informes y alertas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="7dff9-253">Creación de plantillas de aviso.</span><span class="sxs-lookup"><span data-stu-id="7dff9-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="7dff9-254">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="7dff9-255">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="7dff9-256">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="7dff9-257">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="7dff9-258">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="7dff9-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="7dff9-259">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="7dff9-260">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="7dff9-261">

<strong>Lo siguiente está fuera del ámbito </strong> 
</span><span class="sxs-lookup"><span data-stu-id="7dff9-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="7dff9-262">Creación y administración de Power Automate flujos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="7dff9-263">Conectores de datos (más allá del conector de RECURSOS HUMANOS).</span><span class="sxs-lookup"><span data-stu-id="7dff9-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="7dff9-264">Configuraciones de expresiones regulares personalizadas (RegEx).</span><span class="sxs-lookup"><span data-stu-id="7dff9-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="7dff9-265">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="7dff9-266">Barreras de información.</span><span class="sxs-lookup"><span data-stu-id="7dff9-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="7dff9-267">Administración de acceso con privilegios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="7dff9-268">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="7dff9-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="7dff9-269">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="7dff9-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="7dff9-270">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="7dff9-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="7dff9-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="7dff9-272">Microsoft 365 Defender es un conjunto unificado de defensa empresarial anterior y posterior a la infracción que coordina de forma nativa la detección, prevención, investigación y respuesta entre puntos de conexión, identidades, correo electrónico y aplicaciones para proporcionar protección integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="7dff9-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="7dff9-273">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="7dff9-274">Proporciona información general sobre el centro Microsoft 365 seguridad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-275">Revisión de incidentes entre productos, incluido el centrarse en lo que es fundamental al garantizar el ámbito de ataque completo, los activos afectados y las acciones de corrección automatizadas que se agrupan.</span><span class="sxs-lookup"><span data-stu-id="7dff9-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-276">Demostración de cómo Microsoft 365 Defender puede organizar la investigación de activos, usuarios, dispositivos y buzones que podrían haber sido comprometidos a través de la recuperación automática.</span><span class="sxs-lookup"><span data-stu-id="7dff9-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="7dff9-277">Explicar y proporcionar ejemplos de cómo los clientes pueden buscar proactivamente intentos de intrusión y actividad de infracción que afecten al correo electrónico, los datos, los dispositivos y las cuentas en varios conjuntos de datos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="7dff9-278">Mostrar a los clientes cómo pueden revisar y mejorar su posición de seguridad de forma holística con Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="7dff9-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="7dff9-279"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="7dff9-280">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="7dff9-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="7dff9-281">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="7dff9-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="7dff9-282">Instrucciones de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="7dff9-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="7dff9-283">Cómo corregir o interpretar los distintos tipos de alerta y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="7dff9-284">Cómo investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="7dff9-285">Búsqueda de amenazas personalizada.</span><span class="sxs-lookup"><span data-stu-id="7dff9-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="7dff9-286">Información de seguridad y administración de eventos (SIEM) o integración de API.</span><span class="sxs-lookup"><span data-stu-id="7dff9-286">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="7dff9-287"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-287"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-288">Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una amplia visibilidad, control sobre el viaje de datos y análisis sofisticados para identificar y combatir las amenazas cibernéticas en todos los servicios en la nube de Microsoft y de terceros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-288">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="7dff9-289">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-289">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-290">Configurar el portal, incluidos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-290">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="7dff9-291">Importar grupos de usuarios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-291">Importing user groups.</span></span></li>
<li> <span data-ttu-id="7dff9-292">Administrar el acceso de administrador y la configuración.</span><span class="sxs-lookup"><span data-stu-id="7dff9-292">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="7dff9-293">Ámbito de la implementación para seleccionar determinados grupos de usuarios para supervisar o excluir de la supervisión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="7dff9-294">Establecer intervalos y etiquetas IP.</span><span class="sxs-lookup"><span data-stu-id="7dff9-294">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="7dff9-295">Personalizar la experiencia del usuario final con el logotipo y la mensajería personalizada.</span><span class="sxs-lookup"><span data-stu-id="7dff9-295">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="7dff9-296">Configuración de la detección en la nube para proporcionar UNA instantánea con:</span><span class="sxs-lookup"><span data-stu-id="7dff9-296">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="7dff9-297">Microsoft Defender para puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-297">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="7dff9-298">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="7dff9-298">Zscaler.</span></span></li>
<li> <span data-ttu-id="7dff9-299">iboss.</span><span class="sxs-lookup"><span data-stu-id="7dff9-299">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="7dff9-300">Conectar <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> aplicaciones características con</a> conectores de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-300">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="7dff9-301">Configurar el control de aplicaciones de acceso condicional en los portales de acceso condicional y Cloud App Security para aplicar controles de sesión en tiempo real.</span><span class="sxs-lookup"><span data-stu-id="7dff9-301">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="7dff9-302">Implementar los paneles Cloud App Security y Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="7dff9-302">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="7dff9-303">Personalizar las puntuaciones de riesgo de la aplicación en función de las prioridades de la organización.</span><span class="sxs-lookup"><span data-stu-id="7dff9-303">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="7dff9-304">Crear etiquetas y categorías de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-304">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="7dff9-305">Sancionar y deshacer la autorización de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-305">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="7dff9-306">Uso de la actividad y los registros de archivos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-306">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="7dff9-307">Administrar aplicaciones de OAuth.</span><span class="sxs-lookup"><span data-stu-id="7dff9-307">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="7dff9-308">Descripción de la correlación de incidentes en el portal Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="7dff9-308">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="7dff9-309">Proporcionar asistencia de configuración con los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 casos</a> de uso principales para CASB (incluida la creación o actualización de hasta seis (6) directivas), excepto:</span><span class="sxs-lookup"><span data-stu-id="7dff9-309">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="7dff9-310">Auditar la configuración de internet como entornos de servicio (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="7dff9-310">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="7dff9-311">Supervisar las actividades de los usuarios para protegerse contra amenazas en los entornos de IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="7dff9-311">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="7dff9-312"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-312"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="7dff9-313">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="7dff9-313">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="7dff9-314">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="7dff9-314">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="7dff9-315">Configurar la infraestructura, la instalación o la implementación de cargas automáticas de registros para informes continuos con Docker o un recopilador de registros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-315">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="7dff9-316">Vea <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-316">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="7dff9-317">Creación de un informe de instantáneas de detección de nube.</span><span class="sxs-lookup"><span data-stu-id="7dff9-317">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="7dff9-318">Bloquear el uso de la aplicación mediante scripts de bloqueo.</span><span class="sxs-lookup"><span data-stu-id="7dff9-318">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="7dff9-319">Conexión de aplicaciones personalizadas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-319">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="7dff9-320">Integración con proveedores de identidades de terceros (ISP) y proveedores de prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="7dff9-320">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="7dff9-321">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="7dff9-321">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="7dff9-322">Investigación y corrección automatizadas, incluidos los libros Power Automate Microsoft.</span><span class="sxs-lookup"><span data-stu-id="7dff9-322">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="7dff9-323">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="7dff9-323">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="7dff9-324">Implementar la detección de aplicaciones en la nube como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="7dff9-324">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="7dff9-325"><strong>Microsoft Defender para punto de conexión</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-325"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-326">Microsoft Defender para endpoint es una plataforma diseñada para ayudar a las redes empresariales a prevenir, detectar, investigar y responder a amenazas avanzadas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-326">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="7dff9-327">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-328">Implementar las tecnologías para proteger los puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-328">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-329">Configuración de perfiles de restricción de dispositivos y protección de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-329">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-330">Evaluar la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios antivirus de Windows Defender u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-330">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-331">Evaluar el estado de su Windows antivirus u otro software de seguridad de extremo.</span><span class="sxs-lookup"><span data-stu-id="7dff9-331">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-332">Evaluación de servidores proxy y firewalls que restringen el tráfico de red.</span><span class="sxs-lookup"><span data-stu-id="7dff9-332">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-333">Para habilitar el servicio microsoft defender para puntos de conexión, se explica cómo implementar un perfil de agente de Defender for Endpoint mediante un extremo integrado.</span><span class="sxs-lookup"><span data-stu-id="7dff9-333">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-334">Instrucciones de implementación, asistencia de configuración y educación sobre:</span><span class="sxs-lookup"><span data-stu-id="7dff9-334">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="7dff9-335">Administración de amenazas y vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="7dff9-335">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-336">Reducción de la superficie de ataque.</span><span class="sxs-lookup"><span data-stu-id="7dff9-336">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-337">Protección de nueva generación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-337">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-338">Detección y respuesta de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-338">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-339">Investigación y corrección automatizadas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-339">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-340">Puntuación de seguridad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-340">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="7dff9-341">Revisión de simulaciones y tutoriales (como escenarios de práctica, malware falso e investigaciones automatizadas).</span><span class="sxs-lookup"><span data-stu-id="7dff9-341">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-342">Información general sobre las características de informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-342">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-343">Integración de Microsoft Defender para Office 365 con Microsoft Defender para endpoint.</span><span class="sxs-lookup"><span data-stu-id="7dff9-343">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-344">Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="7dff9-344">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-345">Los siguientes sistemas operativos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-345">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="7dff9-346">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="7dff9-346">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-347">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="7dff9-347">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-348">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="7dff9-348">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-349">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="7dff9-349">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-350">Windows Server Semi-Annual Channel (SAC) versión 1803.</span><span class="sxs-lookup"><span data-stu-id="7dff9-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-351">macOS versiones 10.13, 10.14 y 10.15.</span><span class="sxs-lookup"><span data-stu-id="7dff9-351">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="7dff9-352">
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la última versión de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior).</span><span class="sxs-lookup"><span data-stu-id="7dff9-352">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="7dff9-353"></li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-353"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="7dff9-354">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="7dff9-354">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-355">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-355">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-356">Administración continua y respuesta ante amenazas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-356">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-357">Incorporación o configuración de los siguientes agentes de Microsoft Defender para endpoints:</span><span class="sxs-lookup"><span data-stu-id="7dff9-357">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="7dff9-358">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="7dff9-358">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-359">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="7dff9-359">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-360">Linux.</span><span class="sxs-lookup"><span data-stu-id="7dff9-360">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-361">Dispositivos móviles (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="7dff9-361">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="7dff9-362">Infraestructura de escritorio virtual (VDI) (persistente o no persistente).</span><span class="sxs-lookup"><span data-stu-id="7dff9-362">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="7dff9-363">Configuración y incorporación de servidores:</span><span class="sxs-lookup"><span data-stu-id="7dff9-363">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="7dff9-364">Configurar un servidor proxy para comunicaciones sin conexión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-364">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-365">Configuración de paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.</span><span class="sxs-lookup"><span data-stu-id="7dff9-365">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-366">Incorporación de servidores al Centro de seguridad de Azure.</span><span class="sxs-lookup"><span data-stu-id="7dff9-366">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-367">Servidores no administrados por Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="7dff9-367">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="7dff9-368">Configuración y incorporación de macOS:</span><span class="sxs-lookup"><span data-stu-id="7dff9-368">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="7dff9-369">Implementación manual basada en Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-369">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-370">Implementación basada en JAMF.</span><span class="sxs-lookup"><span data-stu-id="7dff9-370">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="7dff9-371">Otra implementación basada en productos de administración de dispositivos móviles (MDM).</span><span class="sxs-lookup"><span data-stu-id="7dff9-371">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-372">Implementación manual.</span><span class="sxs-lookup"><span data-stu-id="7dff9-372">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="7dff9-373">Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:</span><span class="sxs-lookup"><span data-stu-id="7dff9-373">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="7dff9-374">Aislamiento basado en hardware.</span><span class="sxs-lookup"><span data-stu-id="7dff9-374">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-375">Control de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-375">App control.</span></span>  
  </li>
<li> <span data-ttu-id="7dff9-376">Control de dispositivo.</span><span class="sxs-lookup"><span data-stu-id="7dff9-376">Device control.</span></span></li>
<li>  
  <span data-ttu-id="7dff9-377">Protección contra vulnerabilidades de seguridad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-377">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-378">Firewall de red.</span><span class="sxs-lookup"><span data-stu-id="7dff9-378">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="7dff9-379">Configuración o administración de características de protección de cuentas como:</span><span class="sxs-lookup"><span data-stu-id="7dff9-379">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="7dff9-380">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="7dff9-380">Windows Hello</span></span></li>
<li> <span data-ttu-id="7dff9-381">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="7dff9-381">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="7dff9-382">Configuración o administración de BitLocker.</span><span class="sxs-lookup"><span data-stu-id="7dff9-382">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="7dff9-383">Inscripción o configuración de Expertos en amenazas de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="7dff9-383">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-384">Configuración o aprendizaje que revisa las conexiones DE API o de información de seguridad y administración de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="7dff9-384">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-385">Inscripción o configuración de Protección contra amenazas de Microsoft (MTP).</span><span class="sxs-lookup"><span data-stu-id="7dff9-385">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-386">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="7dff9-386">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-387">Formación u instrucciones sobre el uso o creación de consultas de Kusto.</span><span class="sxs-lookup"><span data-stu-id="7dff9-387">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="7dff9-388">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-388">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="7dff9-389"><strong>Microsoft Defender para la identidad </strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-389"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="7dff9-390">Microsoft Defender for Identity es una solución de seguridad basada en la nube que aprovecha las señales locales de Active Directory para identificar, detectar e investigar las amenazas avanzadas, las identidades vulnerables y las acciones internas malintencionadas dirigidas a su organización.</span><span class="sxs-lookup"><span data-stu-id="7dff9-390">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="7dff9-391">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-391">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="7dff9-392">Crear la instancia de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="7dff9-392">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="7dff9-393">Conectar Defender for Identity a Active Directory.</span><span class="sxs-lookup"><span data-stu-id="7dff9-393">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="7dff9-394">Evaluar la preparación del entorno para implementar el sensor Defender for Identity en los controladores de dominio, incluidos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-394">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="7dff9-395">Ejecución de la herramienta de tamaño para la planeación de capacidad de recursos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-395">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="7dff9-396">Ejecutar la herramienta de auditoría para evaluar la compatibilidad de los controladores de dominio con el sensor.</span><span class="sxs-lookup"><span data-stu-id="7dff9-396">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="7dff9-397">Implementar el sensor para capturar y analizar el tráfico de red y Windows eventos directamente desde los controladores de dominio, incluidos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-397">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="7dff9-398">Descargar el paquete del sensor.</span><span class="sxs-lookup"><span data-stu-id="7dff9-398">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="7dff9-399">Configuración del sensor.</span><span class="sxs-lookup"><span data-stu-id="7dff9-399">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="7dff9-400">Instalar el sensor en el controlador de dominio de forma silenciosa.</span><span class="sxs-lookup"><span data-stu-id="7dff9-400">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="7dff9-401">Implementar el sensor en el entorno de varios bosques.</span><span class="sxs-lookup"><span data-stu-id="7dff9-401">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="7dff9-402">Integración de Defender for Identity con Microsoft Cloud App Security (Cloud App Security no es necesaria la licencia).</span><span class="sxs-lookup"><span data-stu-id="7dff9-402">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="7dff9-403">Proporcionar instrucciones de implementación, asistencia de configuración y educación sobre:</span><span class="sxs-lookup"><span data-stu-id="7dff9-403">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="7dff9-404">Ajustar el entorno para reducir el "ruido".</span><span class="sxs-lookup"><span data-stu-id="7dff9-404">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="7dff9-405">Descripción del informe de evaluación de la postura de seguridad de identidad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-405">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="7dff9-406">Descripción de la puntuación de prioridad de investigación del usuario y el informe de clasificación de la investigación del usuario.</span><span class="sxs-lookup"><span data-stu-id="7dff9-406">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="7dff9-407">Descripción del informe de usuario inactivo.</span><span class="sxs-lookup"><span data-stu-id="7dff9-407">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="7dff9-408">Proporcionar opciones de corrección en una cuenta comprometida.</span><span class="sxs-lookup"><span data-stu-id="7dff9-408">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="7dff9-409">Facilitar la migración de Análisis avanzado de amenazas (ATA) a Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="7dff9-409">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="7dff9-410"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-410"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="7dff9-411">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="7dff9-411">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="7dff9-412">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="7dff9-412">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="7dff9-413">Implementación del sensor Defender for Identity, incluidos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-413">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="7dff9-414">Planeación manual de capacidad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-414">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="7dff9-415">Implementar el sensor en una capacidad independiente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-415">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="7dff9-416">Implementar el sensor mediante un adaptador de equipo de tarjeta de interfaz de red (NIC).</span><span class="sxs-lookup"><span data-stu-id="7dff9-416">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="7dff9-417">Implementar el sensor a través de una herramienta de terceros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-417">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="7dff9-418">Conexión al servicio en la nube de Defender for Identity a través de una conexión de proxy web.</span><span class="sxs-lookup"><span data-stu-id="7dff9-418">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="7dff9-419">Creación y administración de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="7dff9-419">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="7dff9-420">Instrucciones de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="7dff9-420">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="7dff9-421">Corrección o interpretación de diversos tipos de alertas y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-421">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="7dff9-422">Investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-422">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="7dff9-423">Amenaza o búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="7dff9-423">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="7dff9-424">Respuesta a incidentes.</span><span class="sxs-lookup"><span data-stu-id="7dff9-424">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="7dff9-425">Proporcionar un tutorial de laboratorio de alertas de seguridad para Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="7dff9-425">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="7dff9-426">Proporcionar notificaciones cuando Defender for Identity detecta actividades sospechosas enviando alertas de seguridad al servidor de syslog a través de un sensor designado.</span><span class="sxs-lookup"><span data-stu-id="7dff9-426">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="7dff9-427">Configuración de Defender for Identity para realizar consultas mediante el protocolo de administrador de cuentas de seguridad remoto (SAMR) para identificar a los administradores locales en máquinas específicas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="7dff9-428">Configuración de soluciones VPN para agregar información desde la conexión VPN a la página de perfil de un usuario.</span><span class="sxs-lookup"><span data-stu-id="7dff9-428">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="7dff9-429">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="7dff9-429">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="7dff9-430">Implementar sensores de Defender for Identity como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="7dff9-430">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="7dff9-431">Active Directory implementado.</span><span class="sxs-lookup"><span data-stu-id="7dff9-431">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-432">Los controladores de dominio en los que quieres instalar los sensores de Defender for Identity tienen conectividad a Internet con el servicio en la nube de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="7dff9-432">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="7dff9-433">El firewall y el proxy deben estar abiertos para comunicarse con el servicio en la nube de Defender for Identity (\*.atp.azure.com el puerto 443 debe estar abierto).</span><span class="sxs-lookup"><span data-stu-id="7dff9-433">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="7dff9-434">Controladores de dominio que se ejecutan en uno de los siguientes:</span><span class="sxs-lookup"><span data-stu-id="7dff9-434">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="7dff9-435">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="7dff9-435">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="7dff9-436">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="7dff9-436">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="7dff9-437">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="7dff9-437">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="7dff9-438">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="7dff9-438">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="7dff9-439">Windows Servidor 2019 con KB4487044 (compilación del sistema operativo 17763.316).</span><span class="sxs-lookup"><span data-stu-id="7dff9-439">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="7dff9-440"><strong>Microsoft Defender para Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-440"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-441">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-441">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-442">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="7dff9-442">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-443">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="7dff9-443">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-444">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="7dff9-444">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-445">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-445">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="7dff9-446">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="7dff9-446">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="7dff9-447"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-447"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="7dff9-448">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-448">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-449">Crear y publicar directivas y etiquetas de retención (solo se admiten en E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-449">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="7dff9-450">Administración de registros (solo se admite en E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-450">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="7dff9-451">Revisión de la creación del plan de archivos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-451">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="7dff9-452">Crear y administrar registros (incluidos los registros basados en eventos).</span><span class="sxs-lookup"><span data-stu-id="7dff9-452">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-453">Revisión de la disposición.</span><span class="sxs-lookup"><span data-stu-id="7dff9-453">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="7dff9-454">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-454">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="7dff9-455">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-455">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="7dff9-456">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-456">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="7dff9-457">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-457">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="7dff9-458">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="7dff9-458">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="7dff9-459">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-459">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="7dff9-460">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-460">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="7dff9-461">

  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-461">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="7dff9-462">Desarrollo de un plan de archivos de administración de registros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-462">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="7dff9-463">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-463">Data connectors.</span></span></li>
<li> <span data-ttu-id="7dff9-464">Desarrollo de la arquitectura de la información en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="7dff9-464">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="7dff9-465">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="7dff9-465">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="7dff9-466">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-466">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="7dff9-467">Compatibilidad con E3.</span><span class="sxs-lookup"><span data-stu-id="7dff9-467">Support for E3.</span></span></li>
<li> <span data-ttu-id="7dff9-468">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="7dff9-468">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="7dff9-469">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="7dff9-469">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="7dff9-470">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="7dff9-470">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="7dff9-471"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-471"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-472">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-472">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-473">Clasificación de datos (compatible con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-473">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-474">Tipos de información confidencial (compatibles con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-474">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-475">Crear etiquetas de confidencialidad (admitidas en E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-475">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-476">Aplicar etiquetas de confidencialidad (compatibles con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-476">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-477">Clasificadores entrenables (admitidos en E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-477">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-478">Conocer los datos con el explorador de contenido y el explorador de actividades (compatible con E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-478">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-479">Publicar etiquetas con directivas (manual y automática) (admitidas en E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-479">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-480">Crear directivas de prevención de pérdida de datos de extremo (DLP) para Windows 10 dispositivos (compatibles con E5).</span><span class="sxs-lookup"><span data-stu-id="7dff9-480">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-481">Crear directivas DLP para Microsoft Teams chats y canales.</span><span class="sxs-lookup"><span data-stu-id="7dff9-481">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="7dff9-482">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-482">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="7dff9-483">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-483">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="7dff9-484">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-484">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="7dff9-485">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-485">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="7dff9-486">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="7dff9-486">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="7dff9-487">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-487">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="7dff9-488">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-488">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="7dff9-489">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-489">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="7dff9-490">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-490">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="7dff9-491">Activar y configurar el espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="7dff9-491">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-492">Creación y configuración de etiquetas y directivas (compatibles con P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="7dff9-492">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-493">Aplicar protección de información a documentos (admitidos en P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="7dff9-493">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-494">Clasificar y etiquetar automáticamente la información en aplicaciones de Office (como Word, PowerPoint, Excel y Outlook) que se ejecutan en Windows y usan el cliente de Azure Information Protection (compatible con P2).</span><span class="sxs-lookup"><span data-stu-id="7dff9-494">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-495">Detección y etiquetado de archivos en reposo con el escáner de Azure Information Protection (compatible con P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="7dff9-495">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-496">Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="7dff9-496">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="7dff9-497">También proporcionamos instrucciones si desea aplicar protección mediante Microsoft Azure Rights Management Services (Azure RMS), Cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="7dff9-497">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="7dff9-498"><strong>Lo siguiente está fuera del ámbito </strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-498"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="7dff9-499">Clave de cliente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-499">Customer key.</span></span></li>
<li><span data-ttu-id="7dff9-500">Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="7dff9-500">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="7dff9-501">Creación o modificación de diccionarios de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="7dff9-501">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="7dff9-502">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="7dff9-502">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="7dff9-503">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="7dff9-503">Azure Purview.</span></span></li>
<li> <span data-ttu-id="7dff9-504">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-504">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="7dff9-505">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="7dff9-505">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="7dff9-506">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="7dff9-506">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="7dff9-507">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema a excepción de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="7dff9-507">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="7dff9-508"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-508"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="7dff9-509">Las responsabilidades de requisitos previos del cliente incluyen:</span><span class="sxs-lookup"><span data-stu-id="7dff9-509">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="7dff9-510">Una lista de ubicaciones de recurso compartido de archivos que se examinarán.</span><span class="sxs-lookup"><span data-stu-id="7dff9-510">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-511">Taxonomía de clasificación aprobada.</span><span class="sxs-lookup"><span data-stu-id="7dff9-511">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="7dff9-512">Descripción de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.</span><span class="sxs-lookup"><span data-stu-id="7dff9-512">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-513">Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-513">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="7dff9-514">Etiquetas configuradas para clasificación y protección.</span><span class="sxs-lookup"><span data-stu-id="7dff9-514">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="7dff9-515">Todos los requisitos previos del escáner de Azure Information Protection están en su lugar.</span><span class="sxs-lookup"><span data-stu-id="7dff9-515">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="7dff9-516">Para obtener más información, vea <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-516">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="7dff9-517">Asegúrese de que los dispositivos de usuario ejecuten un sistema operativo compatible y tengan instalados los requisitos previos necesarios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-517">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="7dff9-518">Vea lo siguiente para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="7dff9-518">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="7dff9-519"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetado unificado de Azure Information Protection para usuarios</a>   </span><span class="sxs-lookup"><span data-stu-id="7dff9-519"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="7dff9-520"><a href="/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="7dff9-520"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="7dff9-521">Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para compatibilidad híbrida.</span><span class="sxs-lookup"><span data-stu-id="7dff9-521">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="7dff9-522">Configuración y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado solamente) o Hold Your Own Key (HYOK) (solo cliente clásico) si necesita una de estas opciones para la implementación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-522">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="7dff9-523"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-523"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-524">Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) basado en la nube y administración de aplicaciones móviles (MAM) para sus aplicaciones y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-524">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="7dff9-525">Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-525">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="7dff9-526">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="7dff9-526">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-527">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="7dff9-527">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-528">Configurar las identidades que Intune usará aprovechando las identidades locales de Active Directory o de la nube (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="7dff9-528">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-529">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-529">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-530">Configuración de la entidad mdma, según tus necesidades de administración, incluidos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-530">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-531">Establecer Intune como entidad MDM cuando Intune es la única solución MDM.</span><span class="sxs-lookup"><span data-stu-id="7dff9-531">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="7dff9-532">Proporcionar instrucciones de MDM para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-532">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-533">Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.</span><span class="sxs-lookup"><span data-stu-id="7dff9-533">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-534">Configurar servicios y directivas de administración de MDM como:</span><span class="sxs-lookup"><span data-stu-id="7dff9-534">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-535">Implementación de aplicaciones para cada plataforma compatible a través de vínculos web o vínculos profundos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-535">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-536">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="7dff9-536">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-537">Implementación de correo electrónico, redes inalámbricas y perfiles vpn si tiene una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en su organización.</span><span class="sxs-lookup"><span data-stu-id="7dff9-537">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-538">Conexión al almacén de datos de Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-538">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-539">Integrar Intune con:</span><span class="sxs-lookup"><span data-stu-id="7dff9-539">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-540">Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="7dff9-540">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-541">Soluciones de partners de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).</span><span class="sxs-lookup"><span data-stu-id="7dff9-541">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-542">Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción a una solución de administración de gastos de telecomunicaciones).</span><span class="sxs-lookup"><span data-stu-id="7dff9-542">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="7dff9-543">Inscribir dispositivos de cada plataforma compatible en Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-543">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="7dff9-544">Proporcionar instrucciones de protección de aplicaciones sobre:</span><span class="sxs-lookup"><span data-stu-id="7dff9-544">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-545">Configurar directivas de protección de aplicaciones para cada plataforma compatible.</span><span class="sxs-lookup"><span data-stu-id="7dff9-545">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-546">Configurar directivas de acceso condicional para aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-546">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-547">Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-547">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-548">Uso de informes de uso de aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-548">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="7dff9-549">Proporcionar instrucciones de migración desde la administración de equipos heredados a MDM de Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-549">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="7dff9-550">
 
</li>
</ul>
  
<strong>Conexión a la nube</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-550">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="7dff9-551">Le guiaremos para prepararse para adjuntar entornos de Configuration Manager existentes con Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-551">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="7dff9-552">Los pasos detallados dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="7dff9-552">The exact steps depend on your source environment.</span></span> <span data-ttu-id="7dff9-553">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="7dff9-553">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="7dff9-554">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="7dff9-554">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-555">Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="7dff9-555">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-556">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-556">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-557">Proporcionar instrucciones para configurar la unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7dff9-557">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-558">Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.</span><span class="sxs-lookup"><span data-stu-id="7dff9-558">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-559">Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.</span><span class="sxs-lookup"><span data-stu-id="7dff9-559">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-560">Configurar cargas de trabajo compatibles que quiera cambiar a Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-560">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-561">Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-561">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="7dff9-562"><strong>Implementar Outlook móvil para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarte a implementar Outlook móvil para iOS y Android de forma segura en tu organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.</span><span class="sxs-lookup"><span data-stu-id="7dff9-562"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="7dff9-563">Los pasos para implementar de forma segura Outlook móvil para iOS y Android con Intune dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="7dff9-563">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="7dff9-564">Puede incluir:</span><span class="sxs-lookup"><span data-stu-id="7dff9-564">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-565">Descargar el Outlook para iOS y Android, Microsoft Authenticator y Portal de empresa de Intune aplicaciones a través de la Tienda de aplicaciones de Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="7dff9-565">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-566">Proporcionar instrucciones sobre cómo configurar:</span><span class="sxs-lookup"><span data-stu-id="7dff9-566">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-567">El Outlook para iOS y Android, Microsoft Authenticator y Portal de empresa de Intune de aplicaciones con Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-567">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-568">Directivas de protección de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-568">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-569">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="7dff9-569">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-570">Directivas de configuración de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-570">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="7dff9-571">Los administradores de TI necesitan que las infraestructuras de vpn, red inalámbrica y entidad de certificación ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-571">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="7dff9-572"><strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar autoridades de certificados, redes inalámbricas, infraestructuras VPN o certificados de inserción mdm de Apple para Intune.</span><span class="sxs-lookup"><span data-stu-id="7dff9-572"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="7dff9-573"><strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube.</span><span class="sxs-lookup"><span data-stu-id="7dff9-573"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="7dff9-574">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="7dff9-574">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="7dff9-575"><strong>Intune integrado con Microsoft Defender para endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-575"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="7dff9-576"><strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con Microsoft Defender para Endpoint y crear directivas de cumplimiento de dispositivos en función de su Windows 10 nivel de riesgo.</span><span class="sxs-lookup"><span data-stu-id="7dff9-576"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="7dff9-577">No proporcionamos asistencia en compras, licencias o activación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-577">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="7dff9-578">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="7dff9-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="7dff9-579"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-579"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="7dff9-580">Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="7dff9-580">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="7dff9-581">Office 365</span><span class="sxs-lookup"><span data-stu-id="7dff9-581">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7dff9-582"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-582"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7dff9-583"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-583"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="7dff9-584"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-584"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="7dff9-585"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-585"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-586">Por Exchange Online, le guiaremos a través del proceso para que su organización esté lista para usar el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="7dff9-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="7dff9-587">Los pasos exactos dependen del entorno de origen y de los planes de migración de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="7dff9-587">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="7dff9-588">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-588">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-589">Configuración de las características de Exchange Online Protection (EOP) para todos los dominios habilitados para correo que se han validado en Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-589">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-590">Apuntar los registros de intercambio de correo (MX) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-590">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-591">Configurar la característica de Microsoft Defender para Office 365 si forma parte del servicio de suscripción.</span><span class="sxs-lookup"><span data-stu-id="7dff9-591">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="7dff9-592">Para obtener más información, consulte <strong>microsoft defender para obtener Office 365</strong> parte de esta tabla.</span><span class="sxs-lookup"><span data-stu-id="7dff9-592">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-p126">Configuración de la característica de prevención de pérdida de datos (DLP) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="7dff9-p127">Configuración del cifrado de mensajes de Office 365 (OME) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="7dff9-597">
  <strong>Nota:</strong> El servicio de replicación de buzones de correo (MRS) intenta migrar correos electrónicos de Information Rights Managed (IRM) desde su buzón local al buzón de correo Exchange Online buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="7dff9-597">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="7dff9-598">La capacidad de leer el contenido protegido posterior a la migración dependerá de la asignación de clientes y la copia de las plantillas de Active Directory Rights Management Services (AD RMS) en el servicio Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="7dff9-598">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="7dff9-599">Configurar puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="7dff9-599">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-600">Configuración de DNS, incluida la detección automática, el marco de directivas de remitente (SPF), el correo identificado de domainkeys (DKIM), la autenticación de mensajes basada en dominio, la creación de informes y la conformidad (DMARC) y los registros MX (según sea necesario).</span><span class="sxs-lookup"><span data-stu-id="7dff9-600">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-601">Configuración del flujo de correo electrónico entre su entorno de mensajería de origen y Exchange Online (si procede).</span><span class="sxs-lookup"><span data-stu-id="7dff9-601">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-602">Operación de migración de correo desde el entorno de mensajería de origen a Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-602">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-603">Configuración de clientes de buzón (Outlook para Windows, Outlook en la web y Outlook para iOS y Android).</span><span class="sxs-lookup"><span data-stu-id="7dff9-603">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="7dff9-604">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="7dff9-604">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="7dff9-605">Para obtener información sobre cómo usar la ventaja de FastTrack para la migración de datos a Office 365, vea <a href="/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-605">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="7dff9-606">El entorno de origen debe tener uno de los siguientes niveles mínimos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-606">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-607">Una o varias organizaciones de Exchange a partir de Exchange Server 2003.</span><span class="sxs-lookup"><span data-stu-id="7dff9-607">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-608">Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).</span><span class="sxs-lookup"><span data-stu-id="7dff9-608">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-609">Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="7dff9-609">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-610">Para obtener información sobre las capacidades multige geográficas, vea <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-610">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="7dff9-611">El software cliente en línea como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, cliente de sincronización de OneDrive para la Empresa, Power BI Desktop y Skype Empresarial deben estar en un nivel mínimo según se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos</a>del sistema para Microsoft 365 Office .</span><span class="sxs-lookup"><span data-stu-id="7dff9-611">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="7dff9-612"><strong>Microsoft Defender para Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-612"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-613">Para obtener más información, vea <strong>Microsoft Defender for Office 365</strong> en Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-613">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="7dff9-614"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-614"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-615">Para obtener más información, vea <strong> Microsoft Information Governance</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-615">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="7dff9-616"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-616"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="7dff9-617">Para obtener más información, vea <strong>Microsoft Information Protection </strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-617">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="7dff9-618"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-618"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-619">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-619">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-620">Confirmar los requisitos mínimos en Exchange Online, SharePoint Online, Office 365 Grupos y Azure AD para admitir Teams.</span><span class="sxs-lookup"><span data-stu-id="7dff9-620">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-621">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="7dff9-621">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-622">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="7dff9-622">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-623">Confirmar que se ha habilitado Teams en su espacio empresarial de Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-623">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-624">Habilitar o deshabilitar licencias de usuario.</span><span class="sxs-lookup"><span data-stu-id="7dff9-624">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-625">Evaluación de red para Teams:</span><span class="sxs-lookup"><span data-stu-id="7dff9-625">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-626">Comprobaciones de puertos y puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-626">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-627">Comprobaciones de calidad de la conexión.</span><span class="sxs-lookup"><span data-stu-id="7dff9-627">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-628">Estimaciones de ancho de banda.</span><span class="sxs-lookup"><span data-stu-id="7dff9-628">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="7dff9-629">Configuración de Teams de aplicaciones (Teams web, Teams de escritorio y Teams para iOS y android app).</span><span class="sxs-lookup"><span data-stu-id="7dff9-629">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="7dff9-630">Si procede, también proporcionamos instrucciones para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-630">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-631">Microsoft Teams Dispositivos de sala:</span><span class="sxs-lookup"><span data-stu-id="7dff9-631">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="7dff9-632">Creación de cuentas en línea necesarias para los dispositivos de telefonía y salas de conferencias compatibles que aparecen en el <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos de Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-632">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-633">Asistencia remota con la configuración del lado de servicio de dispositivos Salas de Microsoft Teams certificados.</span><span class="sxs-lookup"><span data-stu-id="7dff9-633">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-634">Habilitar audioconferencia:</span><span class="sxs-lookup"><span data-stu-id="7dff9-634">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="7dff9-635">Parámetros predeterminados de la configuración de la organización para puente de conferencia.</span><span class="sxs-lookup"><span data-stu-id="7dff9-635">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-636">Asignación de un puente de conferencia a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="7dff9-636">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="7dff9-637">Sistema telefónico:</span><span class="sxs-lookup"><span data-stu-id="7dff9-637">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-638">Configuración de la organización para los parámetros predeterminados de voz en la nube.</span><span class="sxs-lookup"><span data-stu-id="7dff9-638">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-639">Instrucciones de planes de llamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponibles</a>):</span><span class="sxs-lookup"><span data-stu-id="7dff9-639">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-640">Asignación de números a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="7dff9-640">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-641">Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.</span><span class="sxs-lookup"><span data-stu-id="7dff9-641">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-642">Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.</span><span class="sxs-lookup"><span data-stu-id="7dff9-642">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="7dff9-643">Guía de enrutamiento directo:</span><span class="sxs-lookup"><span data-stu-id="7dff9-643">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-644">Guía de configuración de la organización para el diseño de enrutamiento directo de escenarios hospedados por asociados o escenarios implementados por el cliente para hasta 10 sitios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-644">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="7dff9-645">Revisión de configuración del controlador de borde de sesión (SBC).</span><span class="sxs-lookup"><span data-stu-id="7dff9-645">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="7dff9-646">Asistencia remota con la configuración del plan de marcado.</span><span class="sxs-lookup"><span data-stu-id="7dff9-646">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="7dff9-647">Configuración de ruta de voz.</span><span class="sxs-lookup"><span data-stu-id="7dff9-647">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="7dff9-648">Desvío de medios y optimización de medios locales.</span><span class="sxs-lookup"><span data-stu-id="7dff9-648">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="7dff9-649">Habilitar eventos en directo en Teams</span><span class="sxs-lookup"><span data-stu-id="7dff9-649">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-650">Configuración e integración de la organización en Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="7dff9-650">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-651">Instrucciones para Skype Empresarial para Teams transición.</span><span class="sxs-lookup"><span data-stu-id="7dff9-651">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="7dff9-652">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-652">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-653">Usuarios habilitados para SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="7dff9-653">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-654">Exchange buzones de correo están presentes (en línea y local en una Exchange de configuración híbrida).</span><span class="sxs-lookup"><span data-stu-id="7dff9-654">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-655">Habilitado para Grupos de Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-655">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="7dff9-656">
  <strong>Nota:</strong> Si los usuarios no están asignados y habilitados con SharePoint online, no tendrán OneDrive para la Empresa almacenamiento en Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-656">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="7dff9-657">El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin OneDrive para la Empresa almacenamiento en Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-657">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="7dff9-658">Teams no admite SharePoint local.</span><span class="sxs-lookup"><span data-stu-id="7dff9-658">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="7dff9-659">
  <strong>Nota:</strong> El estado ideal es que todos los usuarios tengan sus buzones en Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="7dff9-659">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="7dff9-660">Los usuarios con buzones de correo locales deben tener sus identidades sincronizadas con el directorio Office 365 a través de Azure AD Conectar.</span><span class="sxs-lookup"><span data-stu-id="7dff9-660">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="7dff9-661">Para estos Exchange híbridos, si el buzón del usuario es local, el usuario no puede agregar ni configurar conectores.</span><span class="sxs-lookup"><span data-stu-id="7dff9-661">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="7dff9-662">Los instaladores para los clientes de escritorio de Mac y Windows en Microsoft Teams se pueden descargar de <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-662">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="7dff9-663"><strong>Outlook para iOS y Android</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-663"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-664">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-665">Descargar Outlook para iOS y Android desde la App Store de Apple y Google Play.</span><span class="sxs-lookup"><span data-stu-id="7dff9-665">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-666">Configurar cuentas y acceder al buzón de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="7dff9-666">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-667">Proteger Outlook móvil (consulte <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> para obtener más información).</span><span class="sxs-lookup"><span data-stu-id="7dff9-667">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="7dff9-668">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-668">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-669">Exchange Online configurado y licencias asignadas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-669">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="7dff9-670"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-670"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-671">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-671">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-672">Asignación de licencias de Power BI.</span><span class="sxs-lookup"><span data-stu-id="7dff9-672">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-673">Implementación de la aplicación Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="7dff9-673">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="7dff9-674">El software cliente en línea como Power BI Desktop debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-674">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="7dff9-675"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-675"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-676">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-676">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-677">Comprobación de la funcionalidad básica de SharePoint que se basa en Project Online.</span><span class="sxs-lookup"><span data-stu-id="7dff9-677">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-678">Adición del servicio de Project Online al espacio empresarial (incluida la adición de las suscripciones a los usuarios).</span><span class="sxs-lookup"><span data-stu-id="7dff9-678">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-679">Configuración del grupo de recursos de empresa (ERP).</span><span class="sxs-lookup"><span data-stu-id="7dff9-679">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-680">Creación del primer proyecto.</span><span class="sxs-lookup"><span data-stu-id="7dff9-680">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="7dff9-681">El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-681">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="7dff9-682"><strong>Project Online Professional y Premium</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-682"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-683">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-683">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-684">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-684">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-685">Asignar licencias de usuario final mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="7dff9-685">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-686">Instalar Cliente de escritorio de Project Online desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="7dff9-686">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-687">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-687">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-688">Configurar un servidor de distribución in situ único para Cliente de escritorio de Project Online, incluida la ayuda para crear un archivo configuration.xml para usarlo con la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-688">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-689">Conectar Cliente de escritorio de Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="7dff9-689">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="7dff9-690">El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-690">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="7dff9-691"><strong>SharePoint Online y OneDrive para la Empresa</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-691"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-692">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-692">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-693">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="7dff9-693">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-694">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="7dff9-694">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-695">Aprovisionamiento de usuarios y licencias.</span><span class="sxs-lookup"><span data-stu-id="7dff9-695">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="7dff9-696">Habilitar la creación de sitios para el administrador de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="7dff9-696">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="7dff9-697">Planificar las colecciones de sitios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-697">Planning site collections.</span></span></li>
<li><span data-ttu-id="7dff9-698">Proteger el contenido y administrar los permisos.</span><span class="sxs-lookup"><span data-stu-id="7dff9-698">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="7dff9-699">Configurar las características de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="7dff9-699">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="7dff9-700">Configuración de las características de Entorno híbrido de SharePoint, como la búsqueda híbrida, los sitios híbridos, la taxonomía híbrida, los tipos de contenido, la creación híbrida de sitios sin intervención del administrador (solo SharePoint Server 2013), el iniciador de aplicaciones extendido, OneDrive para la Empresa híbrido y los sitios de extranet.</span><span class="sxs-lookup"><span data-stu-id="7dff9-700">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-701">Su enfoque de migración.</span><span class="sxs-lookup"><span data-stu-id="7dff9-701">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="7dff9-702">Se proporcionan instrucciones adicionales para OneDrive para la Empresa según la versión SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="7dff9-702">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-703">Identificar las opciones de integración y revisar el ancho de banda y la infraestructura de red local y en línea.</span><span class="sxs-lookup"><span data-stu-id="7dff9-703">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-704">Instalar SharePoint Online 2013 SP1 (si corresponde), planear e implementar requisitos de sincronización e identidad, e identificar el OneDrive para la Empresa de sincronización.</span><span class="sxs-lookup"><span data-stu-id="7dff9-704">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-705">Planeación e implementación de un solo lanzamiento para todos los usuarios (o un lanzamiento por fases).</span><span class="sxs-lookup"><span data-stu-id="7dff9-705">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-706">Asignar licencias, redirigir Mis sitios y bibliotecas de documentos personales a Office 365 (aplicable a SharePoint Online 2013), configurar audiencias para controlar el acceso a OneDrive (aplicable a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="7dff9-706">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="7dff9-707">Redirigir o mover carpetas conocidas a OneDrive.</span><span class="sxs-lookup"><span data-stu-id="7dff9-707">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="7dff9-708">Implementar la sincronización OneDrive para la Empresa cliente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-708">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="7dff9-709">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="7dff9-709">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="7dff9-710">Para obtener información sobre cómo usar la ventaja de FastTrack para la migración de datos a Office 365, vea <a href="/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-710">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="7dff9-711"><strong>Para SharePoint híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-711"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="7dff9-712">SharePoint configuración híbrida incluye la configuración de búsqueda híbrida, sitios, taxonomía, tipos de contenido, OneDrive para la Empresa, un iniciador de aplicaciones extendido, sitios de extranet y creación de sitios de autoservicio conectados desde local a un único entorno de SharePoint Online de destino.</span><span class="sxs-lookup"><span data-stu-id="7dff9-712">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="7dff9-713">
  <strong>Nota:</strong> La creación de sitios sin servicio no está en el ámbito con servidores locales que se ejecutan SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="7dff9-713">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="7dff9-714">Para habilitar SharePoint híbrido, debe tener uno de los siguientes entornos de servidor SharePoint locales: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="7dff9-714">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="7dff9-715">
  <strong>Nota:</strong> La actualización de entornos SharePoint locales a SharePoint server no está en el ámbito.</span><span class="sxs-lookup"><span data-stu-id="7dff9-715">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="7dff9-716">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="7dff9-716">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="7dff9-717">Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="7dff9-717">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="7dff9-718">
  <strong>Nota:</strong> Para obtener información sobre las capacidades multigeo, vea <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="7dff9-718">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="7dff9-719"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-719"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="7dff9-720">Proporcionamos instrucciones remotas para habilitar el Yammer Enterprise servicio.</span><span class="sxs-lookup"><span data-stu-id="7dff9-720">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="7dff9-721">El software cliente en línea debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-721">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="7dff9-722">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="7dff9-722">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7dff9-723"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-723"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7dff9-724"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-724"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="7dff9-725"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-725"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="7dff9-726"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-726"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-727">Para obtener más información, <strong>vea Azure Active Directory (Azure AD) y Azure AD Premium</strong> seguridad y <a href="/fasttrack/products-and-capabilities#security-and-compliance">cumplimiento</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-727">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd"><span data-ttu-id="7dff9-728">#seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="7dff9-728">#security-and-compliance</span></span>
<td><span data-ttu-id="7dff9-729"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-729"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="7dff9-730">Para obtener más información sobre Azure Information Protection, vea <strong>Microsoft Information Protection</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-730">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="7dff9-731"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-731"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-732">Para obtener más información, <strong>vea Microsoft Intune</strong> en Seguridad <a href="/fasttrack/products-and-capabilities#security-and-compliance">y cumplimiento</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-732">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="7dff9-733">Windows 10</span><span class="sxs-lookup"><span data-stu-id="7dff9-733">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7dff9-734"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-734"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7dff9-735"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-735"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="7dff9-736"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-736"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="7dff9-737"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-737"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-738">Proporcionamos instrucciones para actualizar de Windows 7 Professional y Windows 8.1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="7dff9-738">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="7dff9-739">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-739">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-740">Comprender su Windows 10 intenciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-740">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-741">Evaluar el entorno de origen y los requisitos (asegúrese de que Microsoft Endpoint Configuration Manager se actualice al nivel requerido para admitir la Windows 10 implementación).</span><span class="sxs-lookup"><span data-stu-id="7dff9-741">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-742">Implementar Windows 10 Enterprise y Aplicaciones Microsoft 365 mediante Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-742">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-743">Te recomendamos opciones para que evalúes tus Windows 10 aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-743">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-744">Habilitar el uso de Análisis de escritorio y la guía mediante la creación de un plan de implementación de Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="7dff9-744">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-745">Aplicaciones Microsoft 365 de compatibilidad aprovechando el panel de preparación de Office 365 en Configuration Manager o con el Toolkit de preparación independiente para Office además de la asistencia para implementar Aplicaciones Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-745">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-746">Crear una lista de comprobación de corrección sobre lo que necesita hacer para que el entorno de origen se asemeja a los requisitos mínimos para una implementación correcta.</span><span class="sxs-lookup"><span data-stu-id="7dff9-746">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-747">Proporcionar instrucciones de actualización para que los dispositivos existentes Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesarios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-747">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-748">Proporcionar instrucciones de actualización para admitir el movimiento de implementación existente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-748">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="7dff9-749">FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="7dff9-749">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="7dff9-750">Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="7dff9-750">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-751">Implementar Aplicaciones Microsoft 365 con Configuration Manager como parte de la Windows 10 implementación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-751">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="7dff9-752">Proporcionar instrucciones para ayudar a su organización a mantenerse al día con Windows 10 Enterprise y Aplicaciones Microsoft 365 el entorno de Configuration Manager existente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-752">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="7dff9-753">
  
<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-753">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="7dff9-754">Actualizar Configuration Manager a la rama actual.</span><span class="sxs-lookup"><span data-stu-id="7dff9-754">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-755">Crear imágenes personalizadas para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="7dff9-755">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-756">Crear y admitir scripts de implementación para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="7dff9-756">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-757">Convertir un sistema Windows 10 del BIOS a la Interfaz de firmware extensible unificado (UEFI).</span><span class="sxs-lookup"><span data-stu-id="7dff9-757">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-758">Habilitar las características de seguridad de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="7dff9-758">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-759">Configurar los Servicios de implementación de Windows (WDS) para el arranque del Entorno de ejecución previo al inicio (PXE).</span><span class="sxs-lookup"><span data-stu-id="7dff9-759">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-760">Usar Microsoft Deployment Toolkit (MDT) para capturar e implementar imágenes de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="7dff9-760">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-761">Usar la Herramienta de migración de estado de usuario (USMT).</span><span class="sxs-lookup"><span data-stu-id="7dff9-761">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="7dff9-762">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-762">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="7dff9-763">Para actualizar su PC, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-763">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-764">Sistema operativo de origen: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="7dff9-764">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-765">Dispositivos: factor de forma de escritorio, bloc de notas o tableta.</span><span class="sxs-lookup"><span data-stu-id="7dff9-765">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-766">Sistema operativo de destino: ventana 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="7dff9-766">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="7dff9-767">Para actualizar la infraestructura, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="7dff9-767">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-768">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="7dff9-768">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-769">La versión de Configuration Manager debe ser compatible con la Windows 10 de destino.</span><span class="sxs-lookup"><span data-stu-id="7dff9-769">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="7dff9-770">Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en <a href="/sccm/core/plan-design/configs/support-for-windows-10">Soporte para Windows 10 en Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-770">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="7dff9-771"><strong>Microsoft Defender para punto de conexión</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-771"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-772">Para obtener más información, vea <strong> Microsoft Defender for Endpoint</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-772">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="7dff9-773">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="7dff9-773">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7dff9-774"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-774"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7dff9-775"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-775"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="7dff9-776"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-776"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="7dff9-777"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-777"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="7dff9-778">Proporcionamos instrucciones de implementación para la incorporación Windows Virtual Desktop (un servicio de virtualización de aplicaciones y escritorio).</span><span class="sxs-lookup"><span data-stu-id="7dff9-778">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="7dff9-779">Windows Virtual Desktop aprovecha la Windows 10 de varias sesiones y está optimizado para Aplicaciones Microsoft 365 para Enterprise con seguridad y administración integradas para Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-779">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="7dff9-780">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-780">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="7dff9-781">Implementar el entorno Windows Escritorio virtual con Windows 10 Enterprise multi-sesión y Aplicaciones Microsoft 365 para Enterprise mediante lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="7dff9-781">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="7dff9-782">Imagen de Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="7dff9-782">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="7dff9-783">Imagen compartida.</span><span class="sxs-lookup"><span data-stu-id="7dff9-783">Shared image.</span></span></li>
<li><span data-ttu-id="7dff9-784">Office Implementación Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="7dff9-784">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="7dff9-785">Configuración de FSLogix:</span><span class="sxs-lookup"><span data-stu-id="7dff9-785">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="7dff9-786">Implementación del agente FSLogix con el contenedor de perfiles.</span><span class="sxs-lookup"><span data-stu-id="7dff9-786">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="7dff9-787">Implementación del agente FSLogix con Office contenedor.</span><span class="sxs-lookup"><span data-stu-id="7dff9-787">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="7dff9-788">Configurar la carpeta FSLogix con exclusiones de contenido.</span><span class="sxs-lookup"><span data-stu-id="7dff9-788">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="7dff9-789">Implementación de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="7dff9-789">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="7dff9-790">Implementación de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="7dff9-790">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="7dff9-791">Conectarse con Windows cliente de Escritorio virtual.</span><span class="sxs-lookup"><span data-stu-id="7dff9-791">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="7dff9-792">

<strong>Lo siguiente está fuera del ámbito</strong>
</span><span class="sxs-lookup"><span data-stu-id="7dff9-792">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="7dff9-793">Project administración de la implementación de Escritorio virtual Windows cliente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-793">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="7dff9-794">Implementación y virtualización de aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-794">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="7dff9-795">Imágenes personalizadas.</span><span class="sxs-lookup"><span data-stu-id="7dff9-795">Custom images.</span></span></li>
<li><span data-ttu-id="7dff9-796">Migraciones y escenarios en los que participan VMware y Citrix.</span><span class="sxs-lookup"><span data-stu-id="7dff9-796">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="7dff9-797">Escenarios de Linux.</span><span class="sxs-lookup"><span data-stu-id="7dff9-797">Linux scenarios.</span></span></li>
<li><span data-ttu-id="7dff9-798">Conversión o migraciones de perfiles de usuario.</span><span class="sxs-lookup"><span data-stu-id="7dff9-798">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="7dff9-799">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-799">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="7dff9-800">Ya debería tener lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="7dff9-800">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="7dff9-801"><a href="/azure/virtual-desktop/overview#requirements">Windows de licencias de Escritorio virtual</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-801"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="7dff9-802">Redes de Azure:</span><span class="sxs-lookup"><span data-stu-id="7dff9-802">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="7dff9-803">Creación y subred de red virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="7dff9-803">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="7dff9-804">Firewall y grupos de seguridad de red.</span><span class="sxs-lookup"><span data-stu-id="7dff9-804">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="7dff9-805">VPN y ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="7dff9-805">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="7dff9-806">Enrutamiento a Azure desde local.</span><span class="sxs-lookup"><span data-stu-id="7dff9-806">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="7dff9-807">Reglas de firewall para permitir la conectividad Windows Escritorio virtual.</span><span class="sxs-lookup"><span data-stu-id="7dff9-807">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="7dff9-808">Para obtener más información, vea <a href="//azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-808">For more information, see <a href="//azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="7dff9-809">Configuración general de Azure AD:</span><span class="sxs-lookup"><span data-stu-id="7dff9-809">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="7dff9-810">Estrategia de <i>identidad (solo puede usar una de las tres opciones siguientes):</i>
</span><span class="sxs-lookup"><span data-stu-id="7dff9-810">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="7dff9-811">Active Directory con Azure AD Conectar azure.</span><span class="sxs-lookup"><span data-stu-id="7dff9-811">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="7dff9-812">Active Directory con Azure AD Conectar local a través de VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="7dff9-812">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="7dff9-813">Servicios de dominio de Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="7dff9-813">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="7dff9-814">App Assure</span><span class="sxs-lookup"><span data-stu-id="7dff9-814">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7dff9-815"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-815"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7dff9-816"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-816"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="7dff9-817"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-817"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="7dff9-818"><strong>Asesoría de aplicaciones</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-818"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="7dff9-819">App Assure es un servicio diseñado para solucionar problemas con Windows 10 y Aplicaciones Microsoft 365 de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-819">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="7dff9-820">Cuando solicitas el servicio App Assure, trabajamos contigo para solucionar problemas válidos de la aplicación sin ningún costo adicional para ti con una suscripción elegible.</span><span class="sxs-lookup"><span data-stu-id="7dff9-820">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="7dff9-821">También proporcionamos instrucciones a los clientes que se enfrentan a problemas de compatibilidad al implementar Windows Escritorio virtual y Microsoft Edge y hacemos todos los esfuerzos razonables para resolver problemas de compatibilidad.</span><span class="sxs-lookup"><span data-stu-id="7dff9-821">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="7dff9-822">Proporcionamos asistencia de corrección para las aplicaciones implementadas en los siguientes productos de Microsoft:</span><span class="sxs-lookup"><span data-stu-id="7dff9-822">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="7dff9-823"><strong>Windows 10</strong> (incluidos los dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="7dff9-823"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="7dff9-824"><strong>Aplicaciones Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="7dff9-824"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="7dff9-825"><strong>Microsoft Edge -</strong> Para obtener instrucciones de implementación, vea <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-825"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-826"><strong>Windows Virtual Desktop</strong> - Para obtener más información, vea <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> y Windows 10 Enterprise preguntas más frecuentes de varias <a href="/azure/virtual-desktop/windows-10-multisession-faq">sesiones.</a></span><span class="sxs-lookup"><span data-stu-id="7dff9-826"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="7dff9-827">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-827">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="7dff9-p136">Inventario y pruebas de aplicaciones para determinar lo que funciona y lo que no en Windows 10 y en las Aplicaciones de Microsoft 365. Para obtener más información sobre este proceso, visite el <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de implementación de escritorios</a>. Si está interesado en una evaluación detallada de la preparación para la actualización, complete el formulario <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitud de cliente para la evaluación del escritorio moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-p136">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="7dff9-831">Buscar instrucciones de compatibilidad y soporte técnico de Windows 10 en aplicaciones ISV de terceros.</span><span class="sxs-lookup"><span data-stu-id="7dff9-831">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="7dff9-832">Para más información, vea <a href="/sccm/desktop-analytics/overview">Análisis de escritorio</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-832">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="7dff9-833">Servicios de solo empaquetado de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="7dff9-833">App packaging-only services.</span></span> <span data-ttu-id="7dff9-834">Sin embargo, el equipo de App Assure crea paquetes de aplicaciones que hemos corregido para Windows 10 para asegurarse de que se pueden implementar en el entorno del cliente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-834">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="7dff9-835">

<strong>Entre las responsabilidades del cliente se incluyen</strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-835">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="7dff9-836">Creación de un inventario de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-836">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="7dff9-837">Validación de esas aplicaciones en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-837">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="7dff9-838">
<strong>Nota:</strong>  Microsoft no puede realizar cambios en el código fuente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-838">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="7dff9-839">Sin embargo, el equipo de App Assure puede proporcionar instrucciones a los desarrolladores de aplicaciones si el código fuente está disponible para sus aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-839">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="7dff9-840">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="7dff9-840">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="7dff9-841"><strong>Windows 10 y Aplicaciones Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="7dff9-841"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="7dff9-842">Las aplicaciones que funcionaban en Windows 7, Windows 8.1, Office 2010 y Office 2013 también funcionan en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7dff9-842">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="7dff9-843">
<strong>Windows 10 en ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="7dff9-843">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="7dff9-844">Las aplicaciones que funcionaban Windows 7, Office 2010 o versiones posteriores también funcionan en Windows 10 y Aplicaciones Microsoft 365 dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="7dff9-844">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="7dff9-845">
  <strong>Nota:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="7dff9-845">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="7dff9-846">La emulación x64 (64 bits) está disponible en versión preliminar para los clientes que participan en el <a href="https://insider.windows.com/">Windows Insider Program</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-846">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="7dff9-847">Para clientes no Windows Insider en Windows 10 versión 2004 (o posterior), ARM64 Photoshop es compatible con OpenCL y <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-847">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="7dff9-848">Los clientes del programa Windows Insider pueden descargar una versión insider del Paquete de compatibilidad de OpenCL y OpenGL para usarla con aplicaciones adicionales.</span><span class="sxs-lookup"><span data-stu-id="7dff9-848">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="7dff9-849">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="7dff9-849">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="7dff9-850">Si las aplicaciones web o los sitios funcionan en Internet Explorer 11, las versiones compatibles de Google Chrome o cualquier versión de Microsoft Edge, también funcionarán con Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="7dff9-850">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-851">A medida que la web está en constante evolución, asegúrese de revisar esta lista publicada de cambios conocidos que afectan a la compatibilidad de sitios para <a href="/microsoft-edge/web-platform/site-impacting-changes">Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-851">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="7dff9-852">
  <strong>Windows Escritorio virtual</strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-852">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="7dff9-853">Las aplicaciones virtualizadas que se ejecutan en el host de sesión de Escritorio remoto (RDSH) de Windows Server también se ejecutan en Windows 10 Enterprise multisesión como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="7dff9-853">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-854">Las aplicaciones que se ejecutan en cualquier entorno de infraestructura de escritorio virtual (VDI) Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="7dff9-854">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-855">Las aplicaciones que se ejecutan en dispositivos cliente con Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="7dff9-855">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="7dff9-856">
  <strong>Nota: Windows 10 Enterprise</strong> exclusiones y limitaciones de compatibilidad de varias sesiones incluyen:</span><span class="sxs-lookup"><span data-stu-id="7dff9-856">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="7dff9-857">Redirección limitada del hardware.</span><span class="sxs-lookup"><span data-stu-id="7dff9-857">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-858">Las aplicaciones que hacen un uso intensivo de A/V pueden tener una capacidad reducida.</span><span class="sxs-lookup"><span data-stu-id="7dff9-858">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="7dff9-859">Las aplicaciones de 16 bits no son compatibles con Windows Virtual Desktop de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="7dff9-859">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="7dff9-860">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="7dff9-860">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7dff9-861"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-861"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7dff9-862"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-862"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="7dff9-863"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="7dff9-863"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="7dff9-864"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="7dff9-864"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="7dff9-865">Proporcionamos ayuda para la compatibilidad y la implementación remota y la adopción para:</span><span class="sxs-lookup"><span data-stu-id="7dff9-865">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="7dff9-866">Implementación de Microsoft Edge en Windows 10 con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="7dff9-866">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-867">Configuración de Microsoft Edge (mediante directivas de grupo o configuración de aplicaciones de Intune y directivas de aplicaciones).</span><span class="sxs-lookup"><span data-stu-id="7dff9-867">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="7dff9-868">Inventario de la lista de sitios que pueden requerir su uso en modo Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="7dff9-868">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="7dff9-869">Habilitar el modo de Internet Explorer con la lista Enterprise sitio existente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-869">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="7dff9-870">(Para obtener más información, vea <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span><span class="sxs-lookup"><span data-stu-id="7dff9-870">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="7dff9-871">Además, si tienes una aplicación web o un sitio que funciona con Internet Explorer o Google Chrome y tienes problemas de compatibilidad, te ofrecemos instrucciones para resolver el problema sin costo adicional.</span><span class="sxs-lookup"><span data-stu-id="7dff9-871">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="7dff9-872">Para solicitar compatibilidad con App Assure, inicie sesión en el <a href="https://fasttrack.microsoft.com/portal#/signin">portal de FastTrack</a> para iniciar una interacción.</span><span class="sxs-lookup"><span data-stu-id="7dff9-872">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="7dff9-873">Instrucciones de planeación para la adopción y configuración perimetrales para marcadores de Microsoft Search.</span><span class="sxs-lookup"><span data-stu-id="7dff9-873">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="7dff9-874">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="7dff9-874">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="7dff9-875">Administración de proyectos de la implementación de Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="7dff9-875">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="7dff9-876">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="7dff9-876">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
