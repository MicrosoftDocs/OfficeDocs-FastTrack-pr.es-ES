---
title: Productos y capacidades
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias antes de poder comenzar. En función de la configuración actual, trabajamos con usted para crear un plan de corrección que haga que el entorno de origen se ajuste a los requisitos mínimos para una incorporación correcta.
ms.openlocfilehash: 43c8edc915d45c1af84155d82d995860cd966950
ms.sourcegitcommit: c4f9375811fd23d01edd308108340ace15ec4db7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/02/2021
ms.locfileid: "53255509"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="b6b3c-104">Productos y capacidades</span><span class="sxs-lookup"><span data-stu-id="b6b3c-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="b6b3c-105">Servicios y escenarios admitidos por FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="b6b3c-106">En este tema se incluyen detalles sobre los escenarios de carga de trabajo admitidos por FastTrack y las expectativas del entorno de origen necesarias antes de poder comenzar.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="b6b3c-107">En función de la configuración actual, trabajamos con usted para crear un plan de corrección que haga que el entorno de origen se ajuste a los requisitos mínimos para una incorporación correcta.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="b6b3c-108">FastTrack proporciona instrucciones para ayudarle primero con las funcionalidades principales (comunes para todos los Microsoft Online Services) y luego con la incorporación de cada servicio elegible:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="b6b3c-109">General</span><span class="sxs-lookup"><span data-stu-id="b6b3c-109">General</span></span>](#general)
  - [<span data-ttu-id="b6b3c-110">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="b6b3c-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="b6b3c-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="b6b3c-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="b6b3c-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="b6b3c-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="b6b3c-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="b6b3c-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="b6b3c-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="b6b3c-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="b6b3c-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="b6b3c-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="b6b3c-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="b6b3c-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="b6b3c-117">Para obtener información sobre las expectativas de entorno de origen para Office 365 Administración Pública, vea [Expectativas de entorno de origen para Office 365 Administración Pública](/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="b6b3c-118">General</span><span class="sxs-lookup"><span data-stu-id="b6b3c-118">General</span></span>

<table>
<table style="width: 100%">
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6b3c-119">Servicio</span><span class="sxs-lookup"><span data-stu-id="b6b3c-119">Service</span></span></th>
<th><span data-ttu-id="b6b3c-120">Detalles de instrucciones de FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-120">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="b6b3c-121">Expectativas del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="b6b3c-121">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b6b3c-122"><strong>Incorporación principal</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-123">Proporcionamos instrucciones remotas sobre la incorporación principal, que implica el aprovisionamiento de servicios, el inquilino y la integración de identidades.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="b6b3c-124">También incluye pasos para proporcionar una base para la incorporación de servicios como Exchange Online, SharePoint Online y Microsoft Teams, incluida una discusión sobre <a href="/office365/enterprise/office-365-network-connectivity-principles">seguridad,</a>conectividad de red y cumplimiento .</span><span class="sxs-lookup"><span data-stu-id="b6b3c-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="b6b3c-125">La incorporación de uno o más servicios elegibles puede empezar al finalizar la incorporación principal.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="b6b3c-126"></li>
</ul>  

<strong> Integración de identidades </strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="b6b3c-127">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="b6b3c-128">Preparación de identidades locales de Active Directory para la sincronización con Azure Active Directory (Azure AD), incluida la instalación y configuración de Azure AD Conectar (bosque único o múltiple) y licencias (incluidas las licencias basadas en grupos).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="b6b3c-129">Creación de identidades en la nube, incluida la importación masiva y las licencias, incluido el uso de licencias basadas en grupos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="b6b3c-130">Elegir y habilitar el método de autenticación correcto para el recorrido en la nube, la sincronización hash de contraseña, la autenticación de paso a través o los servicios de federación de Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="b6b3c-131">Elegir y habilitar una experiencia de autenticación más conveniente para los usuarios con autenticación sin contraseña (Fast Identity Online (FIDO)2 o Microsoft Authenticator App).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="b6b3c-132">Habilitar AD FS para clientes con un único bosque de Active Directory e identidades sincronizadas con la herramienta de Conectar Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="b6b3c-133">Esto requiere Windows Server 2012 R2 Active Directory Federation Services 2.0 o posterior.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="b6b3c-134">Migrar la autenticación de AD FS a Azure AD mediante la sincronización hash de contraseña o la autenticación de paso a través.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="b6b3c-135">Migración de aplicaciones preinstaladas (como aplicaciones saas) de software como servicio (SaaS) de la galería de Azure AD) de AD FS a Azure AD para el inicio de sesión único (SSO).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="b6b3c-136">Habilitar integraciones de aplicaciones SaaS con SSO desde la galería de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="b6b3c-137">Habilitar el aprovisionamiento automático de usuarios para aplicaciones SaaS integradas previamente, tal como se muestra en la lista de <a href="/azure/active-directory/saas-apps/tutorial-list">tutoriales </a> de integración de aplicaciones (limitado a aplicaciones SaaS de la galería de Azure AD y aprovisionamiento saliente solamente).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="b6b3c-138"><strong>Habilitación de red </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="b6b3c-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="b6b3c-139">Como parte de las ventajas de FastTrack, le recomendamos que se informe de los procedimientos recomendados para conectarse a los servicios en la nube para garantizar los niveles más altos de rendimiento de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="b6b3c-140"><strong>Bosques de Active Directory</strong> Tienen el nivel de bosque funcional establecido en Windows Server 2003 en adelante, con la siguiente configuración de bosque:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-141">Un solo bosque de Active Directory.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-142">Un solo bosque de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-143">Varios bosques de cuentas de Active Directory y topologías de bosques de recursos (Exchange o Lync 2010, Lync 2013 o Skype Empresarial).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-144">Varios bosques de cuentas de Active Directory con uno de los bosques que es un bosque de cuentas de Active Directory centralizado que incluye Exchange o Lync 2010, Lync 2013 o Skype Empresarial.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-145">Varios bosques de cuentas de Active Directory, cada uno con su propia organización de Exchange.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-146">Tareas necesarias para la configuración e integración del espacio empresarial con Azure Active Directory, si es necesario.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="b6b3c-147">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="b6b3c-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="b6b3c-148">Para escenarios de Active Directory con varios bosques, si se implementa Lync 2010, Lync 2013 o Skype Empresarial, debe implementarse en el mismo bosque de Active Directory que Exchange.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-149">Al implementar varios bosques de Active Directory con varias organizaciones de Exchange en una configuración multi híbrido de Exchange, no se admiten espacios de nombres de nombre principal de usuario compartido (UPN) entre bosques de origen.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="b6b3c-150">Los espacios de nombres SMTP principales entre las organizaciones de Exchange también deben estar separados.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="b6b3c-151">Para más información, consulte <a href="https://go.microsoft.com/fwlink/?linkid=845444">Implementaciones híbridas con varios bosques de Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-152">Para todas las configuraciones de varios bosques, la implementación de Servicios de federación de Active Directory (AD FS) está fuera del ámbito.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="b6b3c-153">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6b3c-154"><strong>Aplicaciones de Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-155">Proporcionamos instrucciones de implementación remota para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-156">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-157">Asignar licencias de usuario final y basadas en dispositivos mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-158">Instalar Aplicaciones de Microsoft 365 desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-159">Instalar aplicaciones de Office Mobile (como Outlook Mobile, Word Mobile, Excel Mobile y PowerPoint Mobile) en los dispositivos iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-160">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-161">Selección y configuración de una instalación local o en la nube.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-162">Creación de la configuración XML de la herramienta de implementación de Office con la herramienta de personalización de Office o XML nativo para configurar el paquete de implementación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-163">Implementar mediante Microsoft Endpoint Configuration Manager, incluida la ayuda con la creación del empaquetado de Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="b6b3c-164">Además, si tienes una macro o complemento que funcionaba con versiones anteriores de Office y experimentas problemas de compatibilidad, proporcionamos instrucciones para corregir el problema de compatibilidad sin costo adicional a través del programa App Assure.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="b6b3c-165">Consulta la <strong>parte de App Assure</strong> de <a href="#windows-10">Windows 10</a> para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="b6b3c-166">El software cliente en línea debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6b3c-167"><strong>Estado de la red</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-168">Proporcionamos instrucciones remotas para obtener e interpretar datos clave de conectividad de red de su entorno que muestran cómo se alinean los sitios de su organización con los <a href="/office365/enterprise/office-365-network-connectivity-principles">principios</a>de conectividad de red de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="b6b3c-169">Esto resalta la puntuación de red que afecta directamente a la velocidad de migración, la experiencia del usuario, el rendimiento del servicio y la confiabilidad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="b6b3c-170">También le guiaremos a través de los pasos de corrección resaltados por estos datos para ayudarle a mejorar la puntuación de red.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="b6b3c-171">Administración de Microsoft 365 Acceso al centro.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-172">Se requieren versiones actualizadas de Microsoft 365 aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-173">Servicios de ubicación habilitados según las recomendaciones de rendimiento de red <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">en el Centro de Administración de Microsoft 365 (versión preliminar).</a></span><span class="sxs-lookup"><span data-stu-id="b6b3c-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="b6b3c-174">Seguridad y cumplimiento</span><span class="sxs-lookup"><span data-stu-id="b6b3c-174">Security and Compliance</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6b3c-175">Servicio</span><span class="sxs-lookup"><span data-stu-id="b6b3c-175">Service</span></span></th>
<th><span data-ttu-id="b6b3c-176">Detalles de instrucciones de FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-176">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="b6b3c-177">Expectativas del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="b6b3c-177">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="b6b3c-178"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-179">Proporcionamos instrucciones remotas para proteger las identidades de la nube para los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="b6b3c-180">

<strong>Infraestructura básica segura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="b6b3c-181">Configurar y habilitar una autenticación segura para sus identidades, incluida la protección con Azure Multi-Factor Authentication (MFA) (solo en la nube), la aplicación Microsoft Authenticator y el registro combinado para Azure MFA y el restablecimiento de contraseñas sin servicio (SSPR).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="b6b3c-182">Implementación de FIDO2 o Microsoft Authenticator app.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-183">Para clientes que no Azure AD Premium, se proporcionan instrucciones para proteger las identidades mediante valores predeterminados de seguridad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-184">Para los clientes premium de Azure AD, se proporcionan instrucciones para proteger sus identidades con acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-185">Detectar y bloquear el uso de contraseñas débiles con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-186">Proteger el acceso remoto a aplicaciones web locales con el proxy de aplicación de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-187">Habilitar la detección y corrección basadas en riesgos con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-188">Habilitar una pantalla de inicio de sesión personalizada, incluidos logotipo, texto e imágenes con personalización de marca personalizada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-189">Compartir de forma segura aplicaciones y servicios con usuarios invitados mediante Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-190">Administrar el acceso de los administradores de Office 365 mediante roles administrativos integrados de control de acceso basado en roles (RBAC) y reducir el número de cuentas de administrador con privilegios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-191">Configuración de la unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-192">Configuración de la unión a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="b6b3c-193">
  
<strong>Supervisión e informes</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="b6b3c-194">Habilitar la supervisión remota para AD FS, Azure AD Conectar y controladores de dominio con Azure AD Conectar Health.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="b6b3c-195">
  
<strong>Gobierno</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="b6b3c-196">Administrar la identidad de Azure AD y el ciclo de vida de acceso a escala con la administración de derechos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="b6b3c-197">Administración de pertenencias a grupos de Azure AD, acceso a aplicaciones empresariales y asignaciones de roles con revisiones de acceso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-198">Revisión de los Términos de uso de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-199">Administrar y controlar el acceso a cuentas de administrador con privilegios con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="b6b3c-200">
  
<strong>Automatización y eficiencias </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="b6b3c-201">Habilitar Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="b6b3c-202">Permitir a los usuarios crear y administrar su propia seguridad en la nube o grupos Office 365 con la administración de grupos de autoservicio de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-203">Administrar el acceso delegado a aplicaciones empresariales con la administración de grupos delegada de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-204">Habilitar grupos dinámicos de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-205">Organizar aplicaciones en el portal de Mis aplicaciones mediante colecciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b6b3c-206">Active Directory local y su entorno se han preparado para Azure AD Premium, incluida la corrección de problemas identificados que impiden la integración con Azure AD y Azure AD Premium características.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6b3c-207"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-208">Para obtener más información sobre Azure Information Protection, <strong>consulte Microsoft Information Protection</strong> en esta tabla.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="b6b3c-209"><strong>Descubrir & responder</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="b6b3c-210"><strong>eDiscovery avanzado</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="b6b3c-211">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="b6b3c-212">Crear un nuevo caso.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="b6b3c-213">Poner a los custodios en espera.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-214">Realizar búsquedas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-215">Agregar los resultados de búsqueda a un conjunto de revisión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-216">Ejecutar análisis en un conjunto de revisión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-217">Revisar y etiquetar documentos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-218">Exportar datos desde el conjunto de revisión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-219">Importar datos que no Office 365 datos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="b6b3c-220"><strong>Auditoría avanzada</strong> (solo compatible con E5)</span><span class="sxs-lookup"><span data-stu-id="b6b3c-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="b6b3c-221">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="b6b3c-222">Habilitar la auditoría avanzada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="b6b3c-223">Realizar una interfaz de usuario de registro de auditoría de búsqueda y comandos básicos de PowerShell de auditoría.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="b6b3c-224">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="b6b3c-225">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="b6b3c-226">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-227">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="b6b3c-228">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="b6b3c-229">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="b6b3c-230">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="b6b3c-231">

<strong>Lo siguiente está fuera del ámbito </strong> 
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="b6b3c-232">Scripting o codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="b6b3c-233">API de exhibición de documentos electrónicos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="b6b3c-234">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="b6b3c-235">Límites de cumplimiento y filtros de seguridad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="b6b3c-236">Investigaciones de datos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="b6b3c-237">Solicitudes del interesado.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="b6b3c-238">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="b6b3c-239">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="b6b3c-240">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="b6b3c-241">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6b3c-242"><strong>Administración de riesgos de Insider</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="b6b3c-243">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="b6b3c-244">Crear directivas y revisar la configuración.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="b6b3c-245">Acceso a informes y alertas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="b6b3c-246">Creación de casos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="b6b3c-247">Creación de plantillas de aviso.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="b6b3c-248">Instrucciones para crear el conector de recursos humanos (HR).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="b6b3c-249">

<strong> Cumplimiento de comunicaciones </strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="b6b3c-250">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="b6b3c-251">Crear directivas y revisar la configuración.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="b6b3c-252">Acceso a informes y alertas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="b6b3c-253">Creación de plantillas de aviso.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="b6b3c-254">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="b6b3c-255">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="b6b3c-256">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-257">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="b6b3c-258">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="b6b3c-259">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="b6b3c-260">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="b6b3c-261">

<strong>Lo siguiente está fuera del ámbito </strong> 
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="b6b3c-262">Creación y administración de Power Automate flujos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="b6b3c-263">Conectores de datos (más allá del conector de RECURSOS HUMANOS).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="b6b3c-264">Configuraciones de expresiones regulares personalizadas (RegEx).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="b6b3c-265">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="b6b3c-266">Barreras de información.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="b6b3c-267">Administración de acceso con privilegios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="b6b3c-268">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="b6b3c-269">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="b6b3c-270">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6b3c-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="b6b3c-272">Microsoft 365 Defender es un conjunto unificado de defensa empresarial anterior y posterior a la infracción que coordina de forma nativa la detección, prevención, investigación y respuesta entre puntos de conexión, identidades, correo electrónico y aplicaciones para proporcionar protección integrada contra ataques sofisticados.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="b6b3c-273">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="b6b3c-274">Proporciona información general sobre el centro Microsoft 365 seguridad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-275">Revisión de incidentes entre productos, incluido el centrarse en lo que es fundamental al garantizar el ámbito de ataque completo, los activos afectados y las acciones de corrección automatizadas que se agrupan.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-276">Demostración de Microsoft 365 Defender puede organizar la investigación de activos, usuarios, dispositivos y buzones que podrían haber sido comprometidos a través de la recuperación automática.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-277">Explicar y proporcionar ejemplos de cómo los clientes pueden buscar proactivamente intentos de intrusión y actividad de infracción que afecten al correo electrónico, los datos, los dispositivos y las cuentas en varios conjuntos de datos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="b6b3c-278">Mostrar a los clientes cómo pueden revisar y mejorar su posición de seguridad de forma holística con Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="b6b3c-279"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="b6b3c-280">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="b6b3c-281">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="b6b3c-282">Instrucciones de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="b6b3c-283">Cómo corregir o interpretar los distintos tipos de alerta y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="b6b3c-284">Cómo investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="b6b3c-285">Búsqueda de amenazas personalizada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="b6b3c-286">Admitir GCC-High <a href=" /fasttrack/us-gov-appendix-overview">o GCC-DoD (Office 365 Us Government)</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-286">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="b6b3c-287">Información de seguridad y administración de eventos (SIEM) o integración de API.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-287">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6b3c-288"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-288"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-289">Microsoft Cloud App Security es un agente de seguridad de acceso a la nube (CASB) que proporciona una amplia visibilidad, control sobre el viaje de datos y análisis sofisticados para identificar y combatir las amenazas cibernéticas en todos los servicios en la nube de Microsoft y de terceros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-289">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="b6b3c-290">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-291">Configurar el portal, incluidos:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-291">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="b6b3c-292">Importar grupos de usuarios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-292">Importing user groups.</span></span></li>
<li> <span data-ttu-id="b6b3c-293">Administrar el acceso de administrador y la configuración.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-293">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-294">Ámbito de la implementación para seleccionar determinados grupos de usuarios para supervisar o excluir de la supervisión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-294">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="b6b3c-295">Cómo configurar intervalos y etiquetas IP.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-295">How to set up IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="b6b3c-296">Personalizar la experiencia del usuario final con el logotipo y la mensajería personalizada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-296">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="b6b3c-297">Integración de servicios de primera como:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-297">Integrating first-party services including:</span></span>
<ul>
<li> <span data-ttu-id="b6b3c-298">Microsoft Defender para punto de conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-298">Microsoft Defender for Endpoint.</span></span></li>
<li> <span data-ttu-id="b6b3c-299">Microsoft Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-299">Microsoft Defender for Identity.</span></span></li>
<li> <span data-ttu-id="b6b3c-300">Azure AD Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-300">Azure AD Identity Protection.</span></span></li>
<li> <span data-ttu-id="b6b3c-301">Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-301">Azure Information Protection.</span></span></li>
</ul>
<li> <span data-ttu-id="b6b3c-302">Configurar la detección en la nube mediante:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-302">Setting up cloud discovery using:</span></span></li>
<ul>
<li> <span data-ttu-id="b6b3c-303">Microsoft Defender para puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-303">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="b6b3c-304">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-304">Zscaler.</span></span></li>
<li> <span data-ttu-id="b6b3c-305">iboss.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-305">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="b6b3c-306">Crear etiquetas y categorías de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-306">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="b6b3c-307">Personalizar las puntuaciones de riesgo de la aplicación en función de las prioridades de la organización.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-307">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="b6b3c-308">Sancionar y deshacer la autorización de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-308">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="b6b3c-309">Revisar los paneles Cloud App Security y Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-309">Reviewing the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="b6b3c-310">Conectar <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> aplicaciones características con</a> conectores de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-310">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="b6b3c-311">Protección de aplicaciones con control de aplicaciones de acceso condicional en el acceso condicional dentro de Azure AD y Cloud App Security portales.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-311">Protecting apps with Conditional Access App Control in the Conditional Access within Azure AD and Cloud App Security portals.</span></span></li>
<li> <span data-ttu-id="b6b3c-312">Implementación del control de aplicaciones de acceso condicional para aplicaciones características.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-312">Deploying Conditional Access App Control for featured apps.</span></span></li>
<li> <span data-ttu-id="b6b3c-313">Uso de la actividad y los registros de archivos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-313">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="b6b3c-314">Administrar aplicaciones de OAuth.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-314">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="b6b3c-315">Revisión y configuración de plantillas de directiva.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-315">Reviewing and configuring policy templates.</span></span></li>
<li> <span data-ttu-id="b6b3c-316">Proporcionar asistencia de configuración con los <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 casos</a> de uso principales para CASB (incluida la creación o actualización de hasta seis (6) directivas), excepto:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-316">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="b6b3c-317">Auditar la configuración de internet como entornos de servicio (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-317">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="b6b3c-318">Supervisar las actividades de los usuarios para protegerse contra amenazas en los entornos de IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-318">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
<li> <span data-ttu-id="b6b3c-319">Descripción de la correlación de incidentes en Microsoft 365 Defender portal.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-319">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="b6b3c-320"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-320"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="b6b3c-321">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-321">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="b6b3c-322">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-322">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="b6b3c-323">Discusiones que comparan Cloud App Security con otras ofertas casb.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-323">Discussions comparing Cloud App Security to other CASB offerings.</span></span></li>
<li> <span data-ttu-id="b6b3c-324">Configuración de Cloud App Security para cumplir requisitos normativos o de cumplimiento específicos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-324">Configuring Cloud App Security to meet specific compliance or regulatory requirements.</span></span></li>
<li> <span data-ttu-id="b6b3c-325">Implementar el servicio en un entorno de producción que no es de prueba.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-325">Deploying the service to a non-test production environment.</span></span></li>
<li> <span data-ttu-id="b6b3c-326">Implementar la detección de aplicaciones en la nube como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-326">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
<li> <span data-ttu-id="b6b3c-327">Admitir GCC-High <a href=" /fasttrack/us-gov-appendix-overview">o GCC-DoD (Office 365 Us Government)</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-327">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="b6b3c-328">Configurar la infraestructura, la instalación o la implementación de cargas automáticas de registros para informes continuos con Docker o un recopilador de registros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-328">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> </li>
<li> <span data-ttu-id="b6b3c-329">Creación de un informe de instantáneas de detección de nube.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-329">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="b6b3c-330">Bloquear el uso de la aplicación mediante scripts de bloqueo.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-330">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="b6b3c-331">Conexión de aplicaciones personalizadas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-331">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="b6b3c-332">Incorporación e implementación de Control de aplicaciones de acceso condicional para aplicaciones no características.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-332">Onboarding and deploying Conditional Access App Control for non-featured apps.</span></span></li>
<li> <span data-ttu-id="b6b3c-333">Integración con proveedores de identidades de terceros (ISP) y proveedores de prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-333">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="b6b3c-334">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-334">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="b6b3c-335">Investigación y corrección automatizadas, incluidos los libros Power Automate Microsoft.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-335">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="b6b3c-336">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-336">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>

</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="b6b3c-337"><strong>Microsoft Defender para punto de conexión</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-337"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-338">Microsoft Defender para endpoint es una plataforma diseñada para ayudar a las redes empresariales a prevenir, detectar, investigar y responder a amenazas avanzadas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-338">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="b6b3c-339">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-339">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-340">Implementar las tecnologías para proteger los puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-340">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-341">Configuración de perfiles de restricción de dispositivos y protección de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-341">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-342">Evaluar la versión del sistema operativo y la administración de dispositivos (incluidos Intune, Microsoft Endpoint Configuration Manager, objetos de directiva de grupo (GPO) y configuraciones de terceros), así como el estado de los servicios antivirus de Windows Defender u otro software de seguridad de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-342">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-343">Evaluar el estado de su Windows antivirus u otro software de seguridad de extremo.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-343">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-344">Evaluación de servidores proxy y firewalls que restringen el tráfico de red.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-344">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-345">Para habilitar el servicio microsoft defender para puntos de conexión, se explica cómo implementar un perfil de agente de Defender for Endpoint mediante un extremo integrado.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-345">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-346">Instrucciones de implementación, asistencia de configuración y educación sobre:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-346">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="b6b3c-347">Administración de amenazas y vulnerabilidades.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-347">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-348">Reducción de la superficie de ataque.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-348">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-349">Protección de nueva generación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-349">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-350">Detección y respuesta de puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-350">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-351">Investigación y corrección automatizadas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-351">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-352">Puntuación segura para dispositivos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-352">Secure score for devices.</span></span>  
  </li>
<li> <span data-ttu-id="b6b3c-353">SmartScreen de Microsoft Defender configuración mediante Microsoft Endpoint Manager.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-353">Microsoft Defender SmartScreen configuration using Microsoft Endpoint Manager.</span></span></li>

</ul></li>
<li>  <span data-ttu-id="b6b3c-354">Revisión de simulaciones y tutoriales (como escenarios de práctica, malware falso e investigaciones automatizadas).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-354">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-355">Información general sobre las características de informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-355">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-356">Integración de Microsoft Defender para Office 365 con Microsoft Defender para endpoint.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-356">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-357">Realizar tutoriales sobre el portal del Centro de seguridad de Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-357">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-358">Los siguientes sistemas operativos:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-358">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="b6b3c-359">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-359">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-360">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-360">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-361">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-361">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-362">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-362">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-363">Windows Server Semi-Annual Channel (SAC) versión 1803.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-363">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-364">macOS versiones 10.13, 10.14 y 10.15.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-364">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="b6b3c-365">
<strong>Nota:</strong> Todas las versiones de Windows Server deben administrarse mediante la última versión de System Center Configuration Manager 2012 (versiones 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versión 2002 o posterior).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-365">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="b6b3c-366"></li>
</ul>

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-366"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="b6b3c-367">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-367">Project management of the customer's remediation activities.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-368">Admitir GCC-High <a href=" /fasttrack/us-gov-appendix-overview">o GCC-DoD (Office 365 Us Government)</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-368">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li>  <span data-ttu-id="b6b3c-369">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-369">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-370">Administración continua y respuesta ante amenazas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-370">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-371">Incorporación o configuración de los siguientes agentes de Microsoft Defender para endpoints:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-371">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="b6b3c-372">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-372">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-373">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-373">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-374">Linux.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-374">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-375">Dispositivos móviles (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-375">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="b6b3c-376">Infraestructura de escritorio virtual (VDI) (persistente o no persistente).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-376">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b6b3c-377">Configuración y incorporación de servidores:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-377">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="b6b3c-378">Configurar un servidor proxy para comunicaciones sin conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-378">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-379">Configuración de paquetes de implementación de Configuration Manager en versiones y instancias de Configuration Manager de nivel inferior.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-379">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-380">Incorporación de servidores al Centro de seguridad de Azure.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-380">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-381">Servidores no administrados por Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-381">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="b6b3c-382">Configuración y incorporación de macOS:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-382">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="b6b3c-383">Implementación manual basada en Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-383">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-384">Implementación basada en JAMF.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-384">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="b6b3c-385">Otra implementación basada en productos de administración de dispositivos móviles (MDM).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-385">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-386">Implementación manual.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-386">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="b6b3c-387">Configuración de las siguientes funcionalidades de reducción de la superficie de ataque:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-387">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="b6b3c-388">Aislamiento basado en hardware.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-388">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-389">Control de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-389">App control.</span></span>  
  </li>
<li> <span data-ttu-id="b6b3c-390">Control de dispositivo.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-390">Device control.</span></span></li>
<li>  
  <span data-ttu-id="b6b3c-391">Protección contra vulnerabilidades de seguridad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-391">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-392">Firewall de red.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-392">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="b6b3c-393">Configuración o administración de características de protección de cuentas como:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-393">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="b6b3c-394">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="b6b3c-394">Windows Hello</span></span></li>
<li> <span data-ttu-id="b6b3c-395">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="b6b3c-395">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="b6b3c-396">Configuración o administración de BitLocker.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-396">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="b6b3c-397">Inscripción o configuración de Expertos en amenazas de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-397">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-398">Configuración o aprendizaje que revisa las conexiones DE API o de información de seguridad y administración de eventos (SIEM).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-398">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-399">Inscripción o configuración de Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-399">Enrollment or configuration of Microsoft 365 Defender.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-400">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-400">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-401">Formación u instrucciones sobre el uso o creación de consultas de Kusto.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-401">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
<li> <span data-ttu-id="b6b3c-402">Formación o instrucciones sobre la configuración de SmartScreen de Defender mediante objetos de directiva de grupo (GPO), Seguridad de Windows o Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-402">Training or guidance covering Defender SmartScreen configuration using Group Policy Objects (GPOs), Windows Security, or Microsoft Edge.</span></span></li>
</li>
</ul>
<span data-ttu-id="b6b3c-403">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-403">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="b6b3c-404"><strong>Microsoft Defender para la identidad </strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-404"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-405">Microsoft Defender for Identity es una solución de seguridad basada en la nube que aprovecha las señales locales de Active Directory para identificar, detectar e investigar las amenazas avanzadas, las identidades vulnerables y las acciones internas malintencionadas dirigidas a su organización.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-405">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="b6b3c-406">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-406">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-407">Ejecución de la herramienta de tamaño para la planeación de capacidad de recursos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-407">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>   <span data-ttu-id="b6b3c-408">Crear la instancia de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-408">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="b6b3c-409">Conectar Defender for Identity a Active Directory.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-409">Connecting Defender for Identity to Active Directory.</span></span> </li>

<li>  <span data-ttu-id="b6b3c-410">Implementar el sensor para capturar y analizar el tráfico de red y Windows eventos directamente desde los controladores de dominio, incluidos:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-410">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="b6b3c-411">Descargar el paquete del sensor.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-411">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-412">Configuración del sensor.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-412">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-413">Instalar el sensor en el controlador de dominio de forma silenciosa.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-413">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-414">Implementar el sensor en el entorno de varios bosques.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-414">Deploying the sensor to your multi-forest environment.</span></span> </li>
<li> <span data-ttu-id="b6b3c-415">Configurar el recopilador Windows eventos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-415">Configuring the Windows Event Collector.</span></span></li>
</ul>
<li>  <span data-ttu-id="b6b3c-416">Configurar el portal, incluidos:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-416">Configuring the portal, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="b6b3c-417">Integración de Defender for Identity con Microsoft Cloud App Security (Cloud App Security no es necesaria la licencia).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-417">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li> <span data-ttu-id="b6b3c-418">Configuración de etiquetas de entidad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-418">Configuring entity tags.</span></span></li>
<li> <span data-ttu-id="b6b3c-419">Etiquetar cuentas confidenciales.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-419">Tagging sensitive accounts.</span></span> </li>
<li> <span data-ttu-id="b6b3c-420">Recibir notificaciones por correo electrónico para problemas de estado y alertas de seguridad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-420">Receiving email notifications for health issues and security alerts.</span></span> </li>
<li> <span data-ttu-id="b6b3c-421">Configuración de exclusiones de alertas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-421">Configuring alert exclusions.</span></span>  </li>
</ul>
<li> <span data-ttu-id="b6b3c-422">Proporcionar instrucciones de implementación, asistencia de configuración y educación sobre:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-422">Providing deployment guidance, configuration assistance, and education on:</span></span></li>
<ul>
<li> <span data-ttu-id="b6b3c-423">Descripción del informe de evaluación de la postura de seguridad de identidad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-423">Understanding the Identity Security Posture Assessment report.</span></span></li>
<li> <span data-ttu-id="b6b3c-424">Descripción de la puntuación de prioridad de la investigación del usuario y el informe de clasificación de la investigación del usuario.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-424">Understanding the User Investigation Priority Score and User Investigation ranking report.</span></span></li>
<li> <span data-ttu-id="b6b3c-425">Descripción del informe de usuario inactivo.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-425">Understanding the inactive user report.</span></span></li>
<li> <span data-ttu-id="b6b3c-426">Explicación de las opciones de corrección en una cuenta comprometida.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-426">Explanation of the remediation options on a compromised account.</span></span></li>
</ul>
<li>  <span data-ttu-id="b6b3c-427">Facilitar la migración de Análisis avanzado de amenazas (ATA) a Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-427">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="b6b3c-428"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-428"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="b6b3c-429">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-429">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="b6b3c-430">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-430">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-431">Implementación de Defender for Identity como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-431">Deploying Defender for Identity as a proof of concept.</span></span></li>
<li> <span data-ttu-id="b6b3c-432">Admitir GCC-High <a href=" /fasttrack/us-gov-appendix-overview">o GCC-DoD (Office 365 Us Government)</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-432">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="b6b3c-433">Implementar o realizar las siguientes actividades del sensor Defender for Identity:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-433">Deploying or performing the following Defender for Identity sensor activities:</span></span> </li>
<ul>
<li> <span data-ttu-id="b6b3c-434">Planeación manual de capacidad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-434">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="b6b3c-435">Ejecución de la herramienta auditoría.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-435">Running the Auditing tool.</span></span> </li>
<li> <span data-ttu-id="b6b3c-436">Implementar el sensor independiente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-436">Deploying the standalone sensor.</span></span> </li>
<li> <span data-ttu-id="b6b3c-437">Implementación en servidores de Servicios de federación de Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-437">Deploying to Active Directory Federation Services (AD FS) servers.</span></span>
<li> <span data-ttu-id="b6b3c-438">Implementar el sensor mediante un adaptador de equipo de tarjeta de interfaz de red (NIC).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-438">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="b6b3c-439">Implementar el sensor a través de una herramienta de terceros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-439">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="b6b3c-440">Conexión al servicio en la nube de Defender for Identity a través de una conexión de proxy web.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-440">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="b6b3c-441">Configuración de la cuenta de Microsoft (MSA) en Active Directory.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-441">Configuring the Microsoft account (MSA) in Active Directory.</span></span>
<li> <span data-ttu-id="b6b3c-442">Creación y administración de honeytokens.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-442">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="b6b3c-443">Habilitar la resolución de nombres de red (NNR).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-443">Enabling Network Name Resolution (NNR).</span></span> </li>
<li> <span data-ttu-id="b6b3c-444">Configuración del contenedor objetos eliminados.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-444">Configuration of Deleted Objects container.</span></span></li>
<li> <span data-ttu-id="b6b3c-445">Instrucciones de implementación o educación sobre:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-445">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="b6b3c-446">Corrección o interpretación de diversos tipos de alertas y actividades supervisadas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-446">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-447">Investigar un usuario, un equipo, una ruta de movimiento lateral o una entidad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-447">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="b6b3c-448">Amenaza o búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-448">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="b6b3c-449">Respuesta a incidentes.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-449">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="b6b3c-450">Proporcionar un tutorial de laboratorio de alertas de seguridad para Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-450">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="b6b3c-451">Proporcionar notificaciones cuando Defender for Identity detecta actividades sospechosas enviando alertas de seguridad al servidor de syslog a través de un sensor designado.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-451">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-452">Configuración de Defender for Identity para realizar consultas mediante el protocolo de administrador de cuentas de seguridad remoto (SAMR) para identificar a los administradores locales en máquinas específicas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-452">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="b6b3c-453">Configuración de soluciones VPN para agregar información desde la conexión VPN a la página de perfil de un usuario.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-453">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-454">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-454">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b6b3c-455">Alineado con los <a href="/defender-for-identity/prerequisites"> requisitos previos de Microsoft Defender para identity</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-455">Aligned with <a href="/defender-for-identity/prerequisites"> Microsoft Defender for Identity prerequisites</a>.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-456">Active Directory implementado.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-456">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-457">Los controladores de dominio en los que quieres instalar los sensores de Defender for Identity tienen conectividad a Internet con el servicio en la nube de Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-457">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="b6b3c-458">El firewall y el proxy deben estar abiertos para comunicarse con el servicio en la nube de Defender for Identity (\*.atp.azure.com el puerto 443 debe estar abierto).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-458">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="b6b3c-459">Controladores de dominio que se ejecutan en uno de los siguientes:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-459">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="b6b3c-460">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-460">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="b6b3c-461">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-461">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="b6b3c-462">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-462">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="b6b3c-463">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-463">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="b6b3c-464">Windows Servidor 2019 con KB4487044 (compilación del sistema operativo 17763.316 o posterior).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-464">Windows Server 2019 with KB4487044 (OS Build 17763.316 or later).</span></span></li>
</ul>
<li> <span data-ttu-id="b6b3c-465">Microsoft .NET Framework 4.7 o posterior.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-465">Microsoft .NET Framework 4.7 or later.</span></span></li>
<li> <span data-ttu-id="b6b3c-466">Se requiere un mínimo de cinco (5) GB de espacio en disco y se recomiendan 10 GB.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-466">A minimum of five (5) GB of disk space is required and 10 GB is recommended.</span></span></li>
<li> <span data-ttu-id="b6b3c-467">Dos (2) núcleos y seis (6) GB de RAM instalados en el controlador de dominio.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-467">Two (2) cores and six (6) GB of RAM installed on the domain controller.</span></span></li>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="b6b3c-468"><strong>Microsoft Defender para Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-468"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-p114">Microsoft Defender para Office 365 protege su organización frente a las amenazas dañinas que representan los mensajes de correo electrónico, vínculos (URL) y herramientas de colaboración. Microsoft Defender para Office 365 incluye:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-p114">Microsoft Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs), and collaboration tools. Defender for Office 365 includes: </span></span><ul>
<li> <span data-ttu-id="b6b3c-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Directivas de protección contra amenazas:</a>defina directivas de protección contra amenazas para establecer el nivel de protección adecuado para su organización.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Threat protection policies</a>: Define threat-protection policies to set the appropriate level of protection for your organization.</span></span></li>
<li> <span data-ttu-id="b6b3c-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Informes:</a>vea informes en tiempo real para supervisar el rendimiento Office 365 defender en su organización.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Reports</a>: View real-time reports to monitor Defender for Office 365 performance in your organization.</span></span></li>
<li> <span data-ttu-id="b6b3c-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Investigación de amenazas y capacidades de respuesta</a>: use las herramientas más avanzadas para investigar, entender, simular y evitar las amenazas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Threat investigation and response capabilities</a>: Use leading-edge tools to investigate, understand, simulate, and prevent threats.</span></span></li>
<li> <span data-ttu-id="b6b3c-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Investigación y respuestas automáticas</a>: ahorre tiempo y esfuerzo al investigar y mitigar amenazas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Automated investigation and response capabilities</a>: Save time and effort investigating and mitigating threats.</span></span></li>
</ul>

<span data-ttu-id="b6b3c-475">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-475">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="b6b3c-476">Habilitar vínculos seguros, datos adjuntos seguros y protección contra suplantación de identidad (anti-phishing).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-476">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-477">Configurar la automatización, la investigación y la respuesta.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-477">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-478">Usar el Simulador de ataques.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-478">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-479">Elaborar informes y análisis de amenazas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-479">Reporting and threat analytics.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-480">Descripción de la correlación de incidentes en Microsoft 365 Defender portal.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-480">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="b6b3c-481"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-481"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="b6b3c-482">Administración de proyectos de las actividades de corrección de los clientes.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-482">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="b6b3c-483">Administración continua, respuesta a amenazas y corrección.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-483">Ongoing management, threat response, and remediation.</span></span></li>
<li> <span data-ttu-id="b6b3c-484">Admitir GCC-High <a href=" /fasttrack/us-gov-appendix-overview">o GCC-DoD (Office 365 Us Government)</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-484">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="b6b3c-485">Discusiones que comparan Defender Office 365 con otras ofertas de seguridad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-485">Discussions comparing Defender for Office 365 to other security offerings.</span></span></li>
<li> <span data-ttu-id="b6b3c-486">Implementar Defender para Office 365 como una prueba de concepto.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-486">Deploying Defender for Office 365 as a proof of concept.</span></span></li>
<li> <span data-ttu-id="b6b3c-487">Conexión de aplicaciones personalizadas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-487">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="b6b3c-488">Aprendizaje o instrucciones sobre la búsqueda avanzada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-488">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="b6b3c-489">Investigación y corrección automatizadas, incluidos los libros Power Automate Microsoft.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-489">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="b6b3c-490">Información de seguridad y administración de eventos (SIEM) o integración de API (incluido Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-490">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
</ul>
</td>
<td><span data-ttu-id="b6b3c-491">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-491">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="b6b3c-492"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-492"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="b6b3c-493">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-493">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-494">Crear y publicar directivas y etiquetas de retención (solo se admiten en E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-494">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="b6b3c-495">Administración de registros (solo se admite en E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-495">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="b6b3c-496">Revisión de la creación del plan de archivos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-496">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-497">Crear y administrar registros (incluidos los registros basados en eventos).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-497">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-498">Revisión de la disposición.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-498">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="b6b3c-499">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-499">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="b6b3c-500">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-500">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="b6b3c-501">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-501">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-502">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-502">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="b6b3c-503">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-503">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="b6b3c-504">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-504">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="b6b3c-505">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-505">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="b6b3c-506">

  <strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-506">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="b6b3c-507">Desarrollo de un plan de archivos de administración de registros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-507">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="b6b3c-508">Conectores de datos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-508">Data connectors.</span></span></li>
<li> <span data-ttu-id="b6b3c-509">Desarrollo de la arquitectura de la información en SharePoint.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-509">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="b6b3c-510">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-510">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="b6b3c-511">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-511">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="b6b3c-512">Compatibilidad con E3.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-512">Support for E3.</span></span></li>
<li> <span data-ttu-id="b6b3c-513">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-513">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="b6b3c-514">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-514">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="b6b3c-515">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-515">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6b3c-516"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-516"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-517">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-517">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-518">Clasificación de datos (compatible con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-518">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-519">Tipos de información confidencial (compatibles con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-519">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-520">Crear etiquetas de confidencialidad (admitidas en E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-520">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-521">Aplicar etiquetas de confidencialidad (compatibles con E3 y E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-521">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-522">Clasificadores entrenables (admitidos en E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-522">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-523">Conocer los datos con el explorador de contenido y el explorador de actividades (compatible con E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-523">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-524">Publicar etiquetas con directivas (manual y automática) (admitidas en E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-524">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-525">Crear directivas de prevención de pérdida de datos de extremo (DLP) para Windows 10 dispositivos (compatibles con E5).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-525">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-526">Crear directivas DLP para Microsoft Teams chats y canales.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-526">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="b6b3c-527">

<strong> Administrador de cumplimiento</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-527">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="b6b3c-528">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-528">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="b6b3c-529">Revisión de tipos de roles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-529">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-530">Agregar y configurar evaluaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-530">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="b6b3c-531">Evaluar el cumplimiento mediante la implementación de acciones de mejora y la determinación de cómo afecta esto a la puntuación de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-531">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="b6b3c-532">Revisión de controles integrados de asignación y evaluación de controles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-532">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="b6b3c-533">Generar un informe dentro de una evaluación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-533">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="b6b3c-534">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-534">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="b6b3c-535">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-535">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="b6b3c-536">Activar y configurar el espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-536">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-537">Creación y configuración de etiquetas y directivas (compatibles con P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-537">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-538">Aplicar protección de información a documentos (admitidos en P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-538">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-539">Clasificar y etiquetar automáticamente la información en aplicaciones de Office (como Word, PowerPoint, Excel y Outlook) que se ejecutan en Windows y usan el cliente de Azure Information Protection (compatible con P2).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-539">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-540">Detección y etiquetado de archivos en reposo con el escáner de Azure Information Protection (compatible con P1 y P2).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-540">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-541">Supervisar mensajes de correo electrónico en tránsito con reglas de flujo de correo de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-541">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="b6b3c-542">También proporcionamos instrucciones si desea aplicar protección mediante Microsoft Azure Rights Management Services (Azure RMS), Cifrado de mensajes de Office 365 (OME) y prevención de pérdida de datos (DLP).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-542">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="b6b3c-543"><strong>Lo siguiente está fuera del ámbito </strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-543"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="b6b3c-544">Clave de cliente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-544">Customer key.</span></span></li>
<li><span data-ttu-id="b6b3c-545">Desarrollo de expresiones regulares personalizadas (RegEx) para tipos de información confidencial.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-545">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="b6b3c-546">Creación o modificación de diccionarios de palabras clave.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-546">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="b6b3c-547">Scripting y codificación personalizados.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-547">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="b6b3c-548">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-548">Azure Purview.</span></span></li>
<li> <span data-ttu-id="b6b3c-549">Diseño, arquitecto y revisión de documentos de terceros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-549">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="b6b3c-550">Cumplimiento de las normativas y requisitos regionales y del sector.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-550">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="b6b3c-551">Implementación práctica de acciones de mejora recomendadas para evaluaciones en el Administrador de cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-551">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="b6b3c-552">Aparte de la <strong>parte de incorporación</strong> principal en <a href="#general">General,</a>no hay requisitos mínimos del sistema a excepción de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-552">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="b6b3c-553"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-553"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="b6b3c-554">Las responsabilidades de requisitos previos del cliente incluyen:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-554">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="b6b3c-555">Una lista de ubicaciones de recurso compartido de archivos que se examinarán.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-555">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-556">Taxonomía de clasificación aprobada.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-556">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="b6b3c-557">Descripción de cualquier restricción reglamentaria o requisitos relativos a la administración de claves.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-557">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-558">Una cuenta de servicio creada para su Active Directory local que se ha sincronizado con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-558">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-559">Etiquetas configuradas para clasificación y protección.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-559">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="b6b3c-560">Todos los requisitos previos del escáner de Azure Information Protection están en su lugar.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-560">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="b6b3c-561">Para obtener más información, vea <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-561">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="b6b3c-562">Asegúrese de que los dispositivos de usuario ejecuten un sistema operativo compatible y tengan instalados los requisitos previos necesarios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-562">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="b6b3c-563">Vea lo siguiente para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-563">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="b6b3c-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Guía de administración: instalar el cliente de etiquetado unificado de Azure Information Protection para usuarios</a>   </span><span class="sxs-lookup"><span data-stu-id="b6b3c-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="b6b3c-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">¿Qué es la aplicación de Azure Information Protection para iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="b6b3c-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="b6b3c-566">Instalación y configuración del conector y servidores de Azure RMS, incluido el conector RMS de Active Directory (AD RMS) para compatibilidad híbrida.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-566">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-567">Configuración y configuración de Bring Your Own Key (BYOK), Double Key Encryption (DKE) (cliente de etiquetado unificado solamente) o Hold Your Own Key (HYOK) (solo cliente clásico) si necesita una de estas opciones para la implementación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-567">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6b3c-568"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-568"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-569">Proporcionamos instrucciones remotas sobre cómo prepararse para usar Intune como proveedor de administración de dispositivos móviles (MDM) basado en la nube y administración de aplicaciones móviles (MAM) para sus aplicaciones y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-569">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="b6b3c-570">Los pasos detallados dependen de su entorno de origen y se basan en su dispositivo móvil y necesidades de administración de aplicaciones móviles.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-570">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="b6b3c-571">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-571">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-572">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-572">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-573">Configurar las identidades que Intune usará aprovechando las identidades locales de Active Directory o de la nube (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-573">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-574">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-574">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-575">Configuración de la entidad mdma, según tus necesidades de administración, incluidos:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-575">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-576">Establecer Intune como entidad MDM cuando Intune es la única solución MDM.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-576">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b6b3c-577">Proporcionar instrucciones de MDM para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-577">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-578">Configurar los grupos de pruebas que se usarán para validar las directivas de administración de MDM.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-578">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-579">Configurar servicios y directivas de administración de MDM como:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-579">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-580">Implementación de aplicaciones para cada plataforma compatible a través de vínculos web o vínculos profundos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-580">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-581">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-581">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-582">Implementación de correo electrónico, redes inalámbricas y perfiles vpn si tiene una entidad de certificación existente, una red inalámbrica o una infraestructura VPN en su organización.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-582">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-583">Conexión al almacén de datos de Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-583">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-584">Integrar Intune con:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-584">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-585">Visor de equipo para asistencia remota (se requiere una suscripción a Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-585">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-586">Soluciones de partners de Mobile Threat Defense (MTD) (se requiere una suscripción a MTD).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-586">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-587">Una solución de administración de gastos de telecomunicaciones (se requiere una suscripción a una solución de administración de gastos de telecomunicaciones).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-587">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="b6b3c-588">Inscribir dispositivos de cada plataforma compatible en Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-588">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="b6b3c-589">Proporcionar instrucciones de protección de aplicaciones sobre:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-589">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-590">Configurar directivas de protección de aplicaciones para cada plataforma compatible.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-590">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-591">Configurar directivas de acceso condicional para aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-591">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-592">Dirigirse a los grupos de usuarios adecuados con las directivas MAM mencionadas anteriormente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-592">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-593">Uso de informes de uso de aplicaciones administradas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-593">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b6b3c-594">Proporcionar instrucciones de migración desde la administración de equipos heredados a MDM de Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-594">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="b6b3c-595">
 
</li>
</ul>
  
<strong>Conexión a la nube</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-595">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="b6b3c-596">Le guiaremos para prepararse para adjuntar entornos de Configuration Manager existentes con Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-596">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="b6b3c-597">Los pasos detallados dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-597">The exact steps depend on your source environment.</span></span> <span data-ttu-id="b6b3c-598">Los pasos pueden incluir:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-598">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="b6b3c-599">Conceder licencias a los usuarios finales.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-599">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-600">Configurar las identidades que se van a usar en Intune, al usar las identidades de la nube y Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-600">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-601">Agregar usuarios a su suscripción de Intune, definir roles de administrador de TI y crear grupos de usuarios y dispositivos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-601">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-602">Proporcionar instrucciones para configurar la unión híbrida de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-602">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-603">Proporcionar instrucciones sobre cómo configurar Azure AD para la inscripción automática de MDM.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-603">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-604">Proporcionar instrucciones sobre cómo configurar la puerta de enlace de administración en la nube cuando se usa como solución para la administración en conjunto de la administración remota de dispositivos basados en Internet.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-604">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-605">Configurar cargas de trabajo compatibles que quiera cambiar a Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-605">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-606">Instalar el cliente de Configuration Manager en dispositivos inscritos en Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-606">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="b6b3c-607"><strong>Implementar Outlook móvil para iOS y Android de forma segura</strong> Podemos proporcionar instrucciones para ayudarte a implementar Outlook móvil para iOS y Android de forma segura en tu organización para garantizar que los usuarios tengan instaladas todas las aplicaciones necesarias.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-607"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="b6b3c-608">Los pasos para implementar de forma segura Outlook móvil para iOS y Android con Intune dependen del entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-608">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="b6b3c-609">Puede incluir:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-609">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-610">Descargar el Outlook para iOS y Android, Microsoft Authenticator y Portal de empresa de Intune aplicaciones a través de la Tienda de aplicaciones de Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-610">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-611">Proporcionar instrucciones sobre cómo configurar:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-611">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-612">El Outlook para iOS y Android, Microsoft Authenticator y Portal de empresa de Intune de aplicaciones con Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-612">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-613">Directivas de protección de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-613">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-614">Directivas de acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-614">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-615">Directivas de configuración de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-615">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="b6b3c-616">Los administradores de TI necesitan que las infraestructuras de vpn, red inalámbrica y entidad de certificación ya funcionen en sus entornos de producción al planear la implementación de perfiles de VPN y redes inalámbricas con Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-616">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="b6b3c-617"><strong>Nota:</strong>La ventaja del servicio FastTrack no incluye asistencia para configurar o configurar autoridades de certificados, redes inalámbricas, infraestructuras VPN o certificados de inserción mdm de Apple para Intune.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-617"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="b6b3c-618"><strong>Nota</strong>: las ventajas del servicio de FastTrack no incluyen asistencia para configurar o actualizar el servidor de sitio de Configuration Manager ni el cliente de Configuration Manager con los requisitos mínimos necesarios para admitir la conexión a la nube.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-618"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="b6b3c-619">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="b6b3c-620"><strong>Intune integrado con Microsoft Defender para endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-620"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="b6b3c-621"><strong>Nota:</strong>Proporcionamos asistencia para integrar Intune con Microsoft Defender para Endpoint y crear directivas de cumplimiento de dispositivos en función de su Windows 10 nivel de riesgo.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-621"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="b6b3c-622">No proporcionamos asistencia en compras, licencias o activación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-622">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="b6b3c-623">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con esto.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-623">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="b6b3c-624"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-624"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="b6b3c-625">Los administradores de TI son responsables del registro de sus dispositivos en la organización, haciendo que el proveedor de hardware cargue sus id. de hardware en su nombre o cargándolos ellos mismos en el servicio de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-625">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="b6b3c-626">Office 365</span><span class="sxs-lookup"><span data-stu-id="b6b3c-626">Office 365</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6b3c-627">Servicio</span><span class="sxs-lookup"><span data-stu-id="b6b3c-627">Service</span></span></th>
<th><span data-ttu-id="b6b3c-628">Detalles de instrucciones de FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-628">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="b6b3c-629">Expectativas del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="b6b3c-629">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b6b3c-630"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-630"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-631">Por Exchange Online, le guiaremos a través del proceso para que su organización esté lista para usar el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-631">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="b6b3c-632">Los pasos exactos dependen del entorno de origen y de los planes de migración de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-632">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="b6b3c-633">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-634">Configuración de las características de Exchange Online Protection (EOP) para todos los dominios habilitados para correo que se han validado en Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-634">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-635">Apuntar los registros de intercambio de correo (MX) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-635">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-636">Configurar la característica de Microsoft Defender para Office 365 si forma parte del servicio de suscripción.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-636">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="b6b3c-637">Para obtener más información, consulte <strong>microsoft defender para obtener Office 365</strong> parte de esta tabla.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-637">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-p126">Configuración de la característica de prevención de pérdida de datos (DLP) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="b6b3c-p127">Configuración del cifrado de mensajes de Office 365 (OME) para todos los dominios habilitados para correo validados en Office 365 como parte de su servicio de suscripción. Esto se realiza una vez que los registros MX apunten a Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="b6b3c-642">
  <strong>Nota:</strong> El servicio de replicación de buzones de correo (MRS) intenta migrar correos electrónicos de Information Rights Managed (IRM) desde su buzón local al buzón de correo Exchange Online buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-642">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="b6b3c-643">La capacidad de leer el contenido protegido posterior a la migración dependerá de la asignación de clientes y la copia de las plantillas de Active Directory Rights Management Services (AD RMS) en el servicio Azure Rights Management (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-643">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="b6b3c-644">Configurar puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-645">Configuración de DNS, incluida la detección automática, el marco de directivas de remitente (SPF), el correo identificado de domainkeys (DKIM), la autenticación de mensajes basada en dominio, la creación de informes y la conformidad (DMARC) y los registros MX (según sea necesario).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-645">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-646">Configuración del flujo de correo electrónico entre su entorno de mensajería de origen y Exchange Online (si procede).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-646">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-647">Operación de migración de correo desde el entorno de mensajería de origen a Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-647">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-648">Configuración de clientes de buzón (Outlook para Windows, Outlook en la web y Outlook para iOS y Android).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-648">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="b6b3c-649">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="b6b3c-649">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="b6b3c-650">Para obtener información sobre cómo usar la ventaja de FastTrack para la migración de datos a Office 365, vea <a href="/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-650">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="b6b3c-651">El entorno de origen debe tener uno de los siguientes niveles mínimos:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-651">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-652">Una o varias organizaciones de Exchange a partir de Exchange Server 2003.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-652">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-653">Un solo entorno de correo electrónico compatible con el protocolo de acceso a mensajes de Internet (IMAP).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-653">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-654">Un solo entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-654">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-655">Para obtener información sobre las capacidades multige geográficas, vea <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-655">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="b6b3c-656">El software cliente en línea como Project para Office 365, Outlook para Windows, Outlook para iOS y Android, cliente de sincronización de OneDrive para la Empresa, Power BI Desktop y Skype Empresarial deben estar en un nivel mínimo según se define en <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Requisitos</a>del sistema para Microsoft 365 Office .</span><span class="sxs-lookup"><span data-stu-id="b6b3c-656">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="b6b3c-657"><strong>Microsoft Defender para Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-657"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-658">Para obtener más información, vea <strong>Microsoft Defender for Office 365</strong> en Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-658">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="b6b3c-659"><strong>Gobierno de información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-659"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-660">Para obtener más información, vea <strong> Microsoft Information Governance</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-660">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6b3c-661"><strong>Protección de la información de Microsoft</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-661"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="b6b3c-662">Para obtener más información, <strong>vea Microsoft Information Protection</strong> en Seguridad <a href="/fasttrack/products-and-capabilities#security-and-compliance">y cumplimiento</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-662">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6b3c-663"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-663"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-664">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-665">Confirmar los requisitos mínimos en Exchange Online, SharePoint Online, Office 365 Grupos y Azure AD para admitir Teams.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-665">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-666">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-666">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-667">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-667">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-668">Confirmar que se ha habilitado Teams en su espacio empresarial de Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-668">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-669">Habilitar o deshabilitar licencias de usuario.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-669">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-670">Evaluación de red para Teams:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-670">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-671">Comprobaciones de puertos y puntos de conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-671">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-672">Comprobaciones de calidad de la conexión.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-672">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-673">Estimaciones de ancho de banda.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-673">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="b6b3c-674">Configuración de Teams de aplicaciones (Teams web, Teams de escritorio y Teams para iOS y android app).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-674">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="b6b3c-675">Si procede, también proporcionamos instrucciones para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-675">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-676">Microsoft Teams Dispositivos de sala:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-676">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="b6b3c-677">Creación de cuentas en línea necesarias para los dispositivos de telefonía y salas de conferencias compatibles que aparecen en el <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catálogo de dispositivos de Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-677">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-678">Asistencia remota con la configuración del lado de servicio de dispositivos Salas de Microsoft Teams certificados.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-678">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-679">Habilitar audioconferencia:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-679">Enabling Audio Conferencing:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="b6b3c-680">Parámetros predeterminados de la configuración de la organización para puente de conferencia.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-680">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-681">Asignación de un puente de conferencia a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-681">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="b6b3c-682">Sistema telefónico:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-682">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-683">Configuración de la organización para los parámetros predeterminados de voz en la nube.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-683">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-684">Instrucciones de planes de llamada (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercados disponibles</a>):</span><span class="sxs-lookup"><span data-stu-id="b6b3c-684">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-685">Asignación de números a usuarios con licencia.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-685">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-686">Instrucciones para la migración de números locales a través de la interfaz de usuario hasta 999.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-686">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-687">Soporte técnico de solicitudes de servicio de migración de números locales a partir de 999.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-687">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b6b3c-688">Guía de enrutamiento directo:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-688">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-689">Guía de configuración de la organización para el diseño de enrutamiento directo de escenarios hospedados por asociados o escenarios implementados por el cliente para hasta 10 sitios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-689">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-690">Revisión de configuración del controlador de borde de sesión (SBC).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-690">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="b6b3c-691">Asistencia remota con la configuración del plan de marcado.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-691">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="b6b3c-692">Configuración de ruta de voz.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-692">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="b6b3c-693">Desvío de medios y optimización de medios locales.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-693">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="b6b3c-694">Habilitar eventos en directo en Teams</span><span class="sxs-lookup"><span data-stu-id="b6b3c-694">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-695">Configuración e integración de la organización en Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-695">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-696">Instrucciones para Skype Empresarial para Teams transición.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-696">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="b6b3c-697">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-697">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-698">Usuarios habilitados para SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-698">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-699">Exchange buzones de correo están presentes (en línea y local en una Exchange de configuración híbrida).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-699">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-700">Habilitado para Grupos de Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-700">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="b6b3c-701">
  <strong>Nota:</strong> Si los usuarios no están asignados y habilitados con SharePoint online, no tendrán OneDrive para la Empresa almacenamiento en Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-701">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="b6b3c-702">El uso compartido de archivos sigue funcionando en canales, pero los usuarios no pueden compartir archivos en chats sin OneDrive para la Empresa almacenamiento en Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-702">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="b6b3c-703">Teams no admite SharePoint local.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-703">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="b6b3c-704">
  <strong>Nota:</strong> El estado ideal es que todos los usuarios tengan sus buzones en Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-704">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="b6b3c-705">Los usuarios con buzones de correo locales deben tener sus identidades sincronizadas con el directorio Office 365 a través de Azure AD Conectar.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-705">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="b6b3c-706">Para estos Exchange híbridos, si el buzón del usuario es local, el usuario no puede agregar ni configurar conectores.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-706">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="b6b3c-707">Los instaladores para los clientes de escritorio de Mac y Windows en Microsoft Teams se pueden descargar de <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-707">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="b6b3c-708"><strong>Outlook para iOS y Android</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-708"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-709">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-709">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-710">Descargar Outlook para iOS y Android desde la App Store de Apple y Google Play.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-710">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-711">Configurar cuentas y acceder al buzón de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-711">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-712">Proteger Outlook móvil (consulte <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> para obtener más información).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-712">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="b6b3c-713">Identidades habilitadas en Azure AD para Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-713">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-714">Exchange Online configurado y licencias asignadas.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-714">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6b3c-715"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-715"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-716">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-716">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-717">Asignación de licencias de Power BI.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-717">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-718">Implementación de la aplicación Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-718">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b6b3c-719">El software cliente en línea como Power BI Desktop debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-719">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6b3c-720"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-720"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-721">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-721">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-722">Comprobación de la funcionalidad básica de SharePoint que se basa en Project Online.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-722">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-723">Adición del servicio de Project Online al espacio empresarial (incluida la adición de las suscripciones a los usuarios).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-723">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-724">Configuración del grupo de recursos de empresa (ERP).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-724">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-725">Creación del primer proyecto.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-725">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b6b3c-726">El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-726">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6b3c-727"><strong>Project Online Professional y Premium</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-727"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-728">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-728">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-729">Solucionar los problemas de implementación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-729">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-730">Asignar licencias de usuario final mediante el Centro de administración de Microsoft 365 y Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-730">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-731">Instalar Cliente de escritorio de Project Online desde el Portal de Office 365 con la opción Hacer clic y ejecutar.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-731">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-732">Configurar las opciones de actualización mediante la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-732">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-733">Configurar un servidor de distribución in situ único para Cliente de escritorio de Project Online, incluida la ayuda para crear un archivo configuration.xml para usarlo con la Herramienta de implementación de Office 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-733">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-734">Conectar Cliente de escritorio de Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-734">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b6b3c-735">El software cliente en línea como Project para Office 365 debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-735">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6b3c-736"><strong>SharePoint Online y OneDrive para la Empresa</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-736"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-737">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-737">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-738">Configuración de DNS.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-738">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-739">Configuración de puertos del firewall.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-739">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-740">Aprovisionamiento de usuarios y licencias.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-740">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="b6b3c-741">Habilitar la creación de sitios para el administrador de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-741">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="b6b3c-742">Planificar las colecciones de sitios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-742">Planning site collections.</span></span></li>
<li><span data-ttu-id="b6b3c-743">Proteger el contenido y administrar los permisos.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-743">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="b6b3c-744">Configurar las características de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-744">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="b6b3c-745">Configuración de las características de Entorno híbrido de SharePoint, como la búsqueda híbrida, los sitios híbridos, la taxonomía híbrida, los tipos de contenido, la creación híbrida de sitios sin intervención del administrador (solo SharePoint Server 2013), el iniciador de aplicaciones extendido, OneDrive para la Empresa híbrido y los sitios de extranet.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-745">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-746">Su enfoque de migración.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-746">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="b6b3c-747">Se proporcionan instrucciones adicionales para OneDrive para la Empresa según la versión SharePoint, como:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-747">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-748">Identificar las opciones de integración y revisar el ancho de banda y la infraestructura de red local y en línea.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-748">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-749">Instalar SharePoint Online 2013 SP1 (si corresponde), planear e implementar requisitos de sincronización e identidad, e identificar el OneDrive para la Empresa de sincronización.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-749">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-750">Planeación e implementación de un solo lanzamiento para todos los usuarios (o un lanzamiento por fases).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-750">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-751">Asignar licencias, redirigir Mis sitios y bibliotecas de documentos personales a Office 365 (aplicable a SharePoint Online 2013), configurar audiencias para controlar el acceso a OneDrive (aplicable a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-751">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="b6b3c-752">Redirigir o mover carpetas conocidas a OneDrive.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-752">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="b6b3c-753">Implementar la sincronización OneDrive para la Empresa cliente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-753">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="b6b3c-754">
  <strong>Migración de datos</strong>  </span><span class="sxs-lookup"><span data-stu-id="b6b3c-754">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="b6b3c-755">Para obtener información sobre cómo usar la ventaja de FastTrack para la migración de datos a Office 365, vea <a href="/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-755">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="b6b3c-756"><strong>Para SharePoint híbrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-756"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="b6b3c-757">SharePoint configuración híbrida incluye la configuración de búsqueda híbrida, sitios, taxonomía, tipos de contenido, OneDrive para la Empresa, un iniciador de aplicaciones extendido, sitios de extranet y creación de sitios de autoservicio conectados desde local a un único entorno de SharePoint Online de destino.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-757">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="b6b3c-758">
  <strong>Nota:</strong> La creación de sitios sin servicio no está en el ámbito con servidores locales que se ejecutan SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-758">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="b6b3c-759">Para habilitar SharePoint híbrido, debe tener uno de los siguientes entornos de servidor SharePoint locales: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-759">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="b6b3c-760">
  <strong>Nota:</strong> La actualización de entornos SharePoint locales a SharePoint server no está en el ámbito.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-760">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="b6b3c-761">Póngase en contacto <a href="https://go.microsoft.com/fwlink/?linkid=2080150">con un partner de Microsoft</a> para obtener ayuda.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="b6b3c-762">Para obtener más información, vea <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="b6b3c-762">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="b6b3c-763">
  <strong>Nota:</strong> Para obtener información sobre las capacidades multigeo, vea <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="b6b3c-763">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6b3c-764"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-764"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="b6b3c-765">Proporcionamos instrucciones remotas para habilitar el Yammer Enterprise servicio.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-765">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="b6b3c-766">El software cliente en línea debe estar en un nivel mínimo según se define en los requisitos del sistema para Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">y Office</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-766">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="b6b3c-767">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="b6b3c-767">Enterprise Mobility + Security</span></span> 

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6b3c-768">Servicio</span><span class="sxs-lookup"><span data-stu-id="b6b3c-768">Service</span></span></th>
<th><span data-ttu-id="b6b3c-769">Detalles de instrucciones de FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-769">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="b6b3c-770">Expectativas del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="b6b3c-770">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="b6b3c-771"><strong>Azure Active Directory (Azure AD) y Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-771"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-772">Para obtener más información, <strong>vea Azure Active Directory (Azure AD) y Azure AD Premium</strong> en Seguridad y <a href="/fasttrack/products-and-capabilities#security-and-compliance">cumplimiento</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-772">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b6b3c-773"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-773"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-774">Para obtener más información sobre Azure Information Protection, consulte <strong>Microsoft Information Protection</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">en Security and Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-774">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="b6b3c-775"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-775"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-776">Para obtener más información, <strong>vea Microsoft Intune</strong> en Seguridad <a href="/fasttrack/products-and-capabilities#security-and-compliance">y cumplimiento</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-776">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="b6b3c-777">Windows 10</span><span class="sxs-lookup"><span data-stu-id="b6b3c-777">Windows 10</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6b3c-778">Servicio</span><span class="sxs-lookup"><span data-stu-id="b6b3c-778">Service</span></span></th>
<th><span data-ttu-id="b6b3c-779">Detalles de instrucciones de FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-779">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="b6b3c-780">Expectativas del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="b6b3c-780">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b6b3c-781"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-781"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-782">Proporcionamos instrucciones para actualizar de Windows 7 Professional y Windows 8.1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-782">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="b6b3c-783">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-783">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-784">Comprender su Windows 10 intenciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-784">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-785">Evaluar el entorno de origen y los requisitos (asegúrese de que Microsoft Endpoint Configuration Manager se actualice al nivel requerido para admitir la Windows 10 implementación).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-785">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-786">Implementar Windows 10 Enterprise y Aplicaciones Microsoft 365 mediante Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-786">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-787">Te recomendamos opciones para que evalúes tus Windows 10 aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-787">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-788">Habilitar el uso de Análisis de escritorio y la guía mediante la creación de un plan de implementación de Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-788">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-789">Aplicaciones Microsoft 365 de compatibilidad aprovechando el panel de preparación de Office 365 en Configuration Manager o con el Toolkit de preparación independiente para Office además de la asistencia para implementar Aplicaciones Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-789">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-790">Crear una lista de comprobación de corrección sobre lo que necesita hacer para que el entorno de origen se asemeja a los requisitos mínimos para una implementación correcta.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-790">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-791">Proporcionar instrucciones de actualización para que los dispositivos existentes Windows 10 Enterprise si cumplen los requisitos de hardware del dispositivo necesarios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-791">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-792">Proporcionar instrucciones de actualización para admitir el movimiento de implementación existente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-792">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="b6b3c-793">FastTrack recomienda y proporciona instrucciones para una actualización local a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-793">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="b6b3c-794">Las instrucciones también están disponibles para la instalación de imágenes limpias y escenarios de implementación de Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-794">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-795">Implementar Aplicaciones Microsoft 365 con Configuration Manager como parte de la Windows 10 implementación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-795">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="b6b3c-796">Proporcionar instrucciones para ayudar a su organización a mantenerse al día con Windows 10 Enterprise y Aplicaciones Microsoft 365 el entorno de Configuration Manager existente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-796">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li> 
</ul><span data-ttu-id="b6b3c-797">
  
<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-797">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="b6b3c-798">Actualizar Configuration Manager a la rama actual.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-798">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-799">Crear imágenes personalizadas para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-799">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-800">Crear y admitir scripts de implementación para la implementación de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-800">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-801">Convertir un sistema Windows 10 del BIOS a la Interfaz de firmware extensible unificado (UEFI).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-801">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-802">Habilitar las características de seguridad de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-802">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-803">Configurar los Servicios de implementación de Windows (WDS) para el arranque del Entorno de ejecución previo al inicio (PXE).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-803">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-804">Usar Microsoft Deployment Toolkit (MDT) para capturar e implementar imágenes de Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-804">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-805">Usar la Herramienta de migración de estado de usuario (USMT).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-805">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="b6b3c-806">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-806">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="b6b3c-807">Para actualizar su PC, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-807">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-808">Sistema operativo de origen: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-808">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-809">Dispositivos: factor de forma de escritorio, bloc de notas o tableta.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-809">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-810">Sistema operativo de destino: ventana 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-810">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="b6b3c-811">Para actualizar la infraestructura, debe cumplir con estos requisitos:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-811">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-812">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-812">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-813">La versión de Configuration Manager debe ser compatible con la Windows 10 de destino.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-813">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="b6b3c-814">Para obtener más información, vea la tabla de soporte técnico de Configuration Manager en <a href="/sccm/core/plan-design/configs/support-for-windows-10">Soporte para Windows 10 en Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-814">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="b6b3c-815"><strong>Microsoft Defender para punto de conexión</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-815"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-816">Para obtener más información, vea <strong> Microsoft Defender for Endpoint</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-816">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="b6b3c-817">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="b6b3c-817">Windows Virtual Desktop</span></span>

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6b3c-818">Servicio</span><span class="sxs-lookup"><span data-stu-id="b6b3c-818">Service</span></span></th>
<th><span data-ttu-id="b6b3c-819">Detalles de instrucciones de FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-819">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="b6b3c-820">Expectativas del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="b6b3c-820">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b6b3c-821"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-821"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="b6b3c-822">Proporcionamos instrucciones de implementación para la incorporación Windows Virtual Desktop (un servicio de virtualización de aplicaciones y escritorio).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-822">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="b6b3c-823">Windows Virtual Desktop aprovecha la Windows 10 de varias sesiones y está optimizado para Aplicaciones Microsoft 365 para Enterprise con seguridad y administración integradas para Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-823">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="b6b3c-824">Proporcionamos instrucciones remotas para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-824">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="b6b3c-825">La implementación Windows 10 Enterprise varias sesiones y Aplicaciones Microsoft 365 para Enterprise mediante lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-825">Deploying Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="b6b3c-826">Imagen de Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-826">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="b6b3c-827">Imagen compartida.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-827">Shared image.</span></span></li>
<li><span data-ttu-id="b6b3c-828">Office Implementación Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-828">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="b6b3c-829">Configuración de Aplicaciones Microsoft 365 FSLogix en un escritorio Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-829">Configuring Microsoft 365 Apps for FSLogix in a native Windows Virtual Desktop.</span></span> <span data-ttu-id="b6b3c-830">Para FSLogix:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-830">For FSLogix:</span></span>
<ul>
<li><span data-ttu-id="b6b3c-831">Implementación del agente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-831">Deploying the Agent.</span></span></li>
<li><span data-ttu-id="b6b3c-832">Configuración de contenedores de Office perfil.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-832">Configuring Profile and Office containers.</span></span></li>
<li><span data-ttu-id="b6b3c-833">Configuración de exclusiones de contenido y redireccionamientos de carpetas para Aplicaciones Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-833">Configuring content exclusions and folder redirections for Microsoft 365 Apps.</span></span></li>
</ul></li>
<li><span data-ttu-id="b6b3c-834">Implementación de Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-834">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="b6b3c-835">Implementación de Microsoft Teams con optimización.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-835">Deploying Microsoft Teams with optimization.</span></span></li>
</ul><span data-ttu-id="b6b3c-836">

<strong>Lo siguiente está fuera del ámbito</strong>
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-836">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="b6b3c-837">Project administración de la implementación de la infraestructura de Escritorio virtual Windows cliente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-837">Project management of the customer's Windows Virtual Desktop infrastructure deployment.</span></span></li>
<li><span data-ttu-id="b6b3c-838">Implementación y virtualización de aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-838">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="b6b3c-839">Creación de imágenes personalizadas para Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-839">Creation of custom images for Windows Virtual Desktop.</span></span></li>
<li><span data-ttu-id="b6b3c-840">Migraciones y escenarios en los que participan VMware y Citrix.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-840">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="b6b3c-841">Escenarios de Linux.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-841">Linux scenarios.</span></span></li>
<li><span data-ttu-id="b6b3c-842">Conversión o migraciones de perfiles de usuario.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-842">Conversion or migrations of user profiles.</span></span></li>
<li><span data-ttu-id="b6b3c-843">Microsoft Endpoint Configuration Manager y Microsoft Endpoint Manager configuración para Windows Virtual Desktop (incluida la aplicación de revisiones y la administración).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-843">Microsoft Endpoint Configuration Manager and Microsoft Endpoint Manager configuration for Windows Virtual Desktop (including patching and management).</span></span> </li>
<li><span data-ttu-id="b6b3c-844">Microsoft 365 Defender con Windows 10 sesión múltiple.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-844">Microsoft 365 Defender with Windows 10 multi-session.</span></span></li>
</ul>
<span data-ttu-id="b6b3c-845">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-845">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="b6b3c-846">Ya debería tener lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-846">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="b6b3c-847"><a href="/azure/virtual-desktop/overview#requirements">Windows de licencias de Escritorio virtual</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-847"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li> <span data-ttu-id="b6b3c-848">La <a href="/azure/virtual-desktop/overview">infraestructura necesaria para admitir Windows Virtual Deskstop</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-848">The <a href="/azure/virtual-desktop/overview"> required infrastructure to support Windows Virtual Deskstop</a>.</span></span> </li>
<ul>
<li><span data-ttu-id="b6b3c-849"><a href="/azure/virtual-desktop/store-fslogix-profile">Storage contenedores de perfil FSLogix en Windows Virtual Deskstop</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-849"><a href="/azure/virtual-desktop/store-fslogix-profile"> Storage for FSLogix profile containers in Windows Virtual Deskstop</a>.</span></span> </li>
</ul>
<li><span data-ttu-id="b6b3c-850">Redes de Azure:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-850">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="b6b3c-851">Creación y subred de red virtual (VNET).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-851">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="b6b3c-852">Firewall y grupos de seguridad de red.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-852">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="b6b3c-853">VPN y ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-853">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="b6b3c-854">Enrutamiento a Azure desde local.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-854">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="b6b3c-855">Reglas de firewall para permitir la conectividad Windows Escritorio virtual.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-855">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="b6b3c-856">Para obtener más información, vea <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-856">For more information, see <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="b6b3c-857">Configuración general de Azure AD:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-857">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="b6b3c-858">Estrategia de <i>identidad (solo puede usar una de las tres opciones siguientes):</i>
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-858">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="b6b3c-859">Active Directory con Azure AD Conectar azure.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-859">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="b6b3c-860">Active Directory con Azure AD Conectar local a través de VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-860">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="b6b3c-861">Servicios de dominio de Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-861">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="b6b3c-862">App Assure</span><span class="sxs-lookup"><span data-stu-id="b6b3c-862">App Assure</span></span>


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6b3c-863">Servicio</span><span class="sxs-lookup"><span data-stu-id="b6b3c-863">Service</span></span></th>
<th><span data-ttu-id="b6b3c-864">Detalles de instrucciones de FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-864">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="b6b3c-865">Expectativas del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="b6b3c-865">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="b6b3c-866"><strong>Asesoría de aplicaciones</strong></span><span class="sxs-lookup"><span data-stu-id="b6b3c-866"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="b6b3c-867">App Assure es un servicio diseñado para solucionar problemas con Windows 10 y Aplicaciones Microsoft 365 de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-867">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="b6b3c-868">Cuando solicitas el servicio App Assure, trabajamos contigo para solucionar problemas válidos de la aplicación sin ningún costo adicional para ti con una suscripción elegible.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-868">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="b6b3c-869">También proporcionamos instrucciones a los clientes que se enfrentan a problemas de compatibilidad al implementar Windows Escritorio virtual y Microsoft Edge y hacemos todos los esfuerzos razonables para resolver problemas de compatibilidad.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-869">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="b6b3c-870">Proporcionamos asistencia de corrección para las aplicaciones implementadas en los siguientes productos de Microsoft:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-870">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="b6b3c-871"><strong>Windows 10</strong> (incluidos los dispositivos ARM64)</span><span class="sxs-lookup"><span data-stu-id="b6b3c-871"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="b6b3c-872"><strong>Aplicaciones Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="b6b3c-872"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="b6b3c-873"><strong>Microsoft Edge -</strong> Para obtener instrucciones de implementación, vea <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-873"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-874"><strong>Windows Virtual Desktop</strong> - Para obtener más información, vea <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> y Windows 10 Enterprise preguntas más frecuentes de varias <a href="/azure/virtual-desktop/windows-10-multisession-faq">sesiones.</a></span><span class="sxs-lookup"><span data-stu-id="b6b3c-874"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="b6b3c-875">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-875">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="b6b3c-p137">Inventario y pruebas de aplicaciones para determinar lo que funciona y lo que no en Windows 10 y en las Aplicaciones de Microsoft 365. Para obtener más información sobre este proceso, visite el <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro de implementación de escritorios</a>. Si está interesado en una evaluación detallada de la preparación para la actualización, complete el formulario <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Solicitud de cliente para la evaluación del escritorio moderno</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-p137">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="b6b3c-879">Buscar instrucciones de compatibilidad y soporte técnico de Windows 10 en aplicaciones ISV de terceros.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-879">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="b6b3c-880">Para más información, vea <a href="/sccm/desktop-analytics/overview">Análisis de escritorio</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-880">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="b6b3c-881">Servicios de solo empaquetado de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-881">App packaging-only services.</span></span> <span data-ttu-id="b6b3c-882">Sin embargo, el equipo de App Assure crea paquetes de aplicaciones que hemos corregido para Windows 10 para asegurarse de que se pueden implementar en el entorno del cliente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-882">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="b6b3c-883">

<strong>Entre las responsabilidades del cliente se incluyen</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-883">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="b6b3c-884">Creación de un inventario de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-884">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="b6b3c-885">Validación de esas aplicaciones en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-885">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="b6b3c-886">
<strong>Nota:</strong>  Microsoft no puede realizar cambios en el código fuente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-886">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="b6b3c-887">Sin embargo, el equipo de App Assure puede proporcionar instrucciones a los desarrolladores de aplicaciones si el código fuente está disponible para sus aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-887">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="b6b3c-888">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-888">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="b6b3c-889"><strong>Windows 10 y Aplicaciones Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-889"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="b6b3c-890">Las aplicaciones que funcionaban en Windows 7, Windows 8.1, Office 2010 y Office 2013 también funcionan en Windows 10 y en las Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-890">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="b6b3c-891">
<strong>Windows 10 en ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-891">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="b6b3c-892">Las aplicaciones que funcionaban Windows 7, Office 2010 o versiones posteriores también funcionan en Windows 10 y Aplicaciones Microsoft 365 dispositivos ARM64.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-892">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="b6b3c-893">
  <strong>Nota:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-893">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="b6b3c-894">La emulación x64 (64 bits) está disponible en versión preliminar para los clientes que participan en el <a href="https://insider.windows.com/">Windows Insider Program</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-894">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="b6b3c-895">Para clientes no Windows Insider en Windows 10 versión 2004 (o posterior), ARM64 Photoshop es compatible con OpenCL y <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-895">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="b6b3c-896">Los clientes del programa Windows Insider pueden descargar una versión insider del Paquete de compatibilidad de OpenCL y OpenGL para usarla con aplicaciones adicionales.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-896">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="b6b3c-897">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-897">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="b6b3c-898">Si las aplicaciones web o los sitios funcionan en Internet Explorer 11, las versiones compatibles de Google Chrome o cualquier versión de Microsoft Edge, también funcionarán con Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-898">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-899">A medida que la web está en constante evolución, asegúrese de revisar esta lista publicada de cambios conocidos que afectan a la compatibilidad de sitios para <a href="/microsoft-edge/web-platform/site-impacting-changes">Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-899">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="b6b3c-900">
  <strong>Windows Escritorio virtual</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-900">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="b6b3c-901">Las aplicaciones virtualizadas que se ejecutan en el host de sesión de Escritorio remoto (RDSH) de Windows Server también se ejecutan en Windows 10 Enterprise multisesión como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-901">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-902">Las aplicaciones que se ejecutan en cualquier entorno de infraestructura de escritorio virtual (VDI) Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-902">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-903">Las aplicaciones que se ejecutan en dispositivos cliente con Windows 7 o Windows 10 también se ejecutan en Windows 7 Enterprise y Windows 10 Enterprise como parte de Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-903">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="b6b3c-904">
  <strong>Nota: Windows 10 Enterprise</strong> exclusiones y limitaciones de compatibilidad de varias sesiones incluyen:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-904">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="b6b3c-905">Redirección limitada del hardware.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-905">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-906">Las aplicaciones que hacen un uso intensivo de A/V pueden tener una capacidad reducida.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-906">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b6b3c-907">Las aplicaciones de 16 bits no son compatibles con Windows Virtual Desktop de 64 bits.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-907">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="b6b3c-908">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="b6b3c-908">Microsoft Edge</span></span>


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b6b3c-909">Servicio</span><span class="sxs-lookup"><span data-stu-id="b6b3c-909">Service</span></span></th>
<th><span data-ttu-id="b6b3c-910">Detalles de instrucciones de FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6b3c-910">FastTrack guidance details</span></span></th>
<th><span data-ttu-id="b6b3c-911">Expectativas del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="b6b3c-911">Source environment expectations</span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="b6b3c-912"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="b6b3c-912"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="b6b3c-913">Proporcionamos ayuda para la compatibilidad y la implementación remota y la adopción para:</span><span class="sxs-lookup"><span data-stu-id="b6b3c-913">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="b6b3c-914">Implementación de Microsoft Edge en Windows 10 con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-914">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-915">Configuración de Microsoft Edge (mediante directivas de grupo o configuración de aplicaciones de Intune y directivas de aplicaciones).</span><span class="sxs-lookup"><span data-stu-id="b6b3c-915">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-916">Inventario de la lista de sitios que pueden requerir su uso en modo Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-916">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="b6b3c-917">Habilitar el modo de Internet Explorer con la lista Enterprise sitio existente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-917">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="b6b3c-918">(Para obtener más información, vea <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-918">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="b6b3c-919">Además, si tienes una aplicación web o un sitio que funciona con Internet Explorer o Google Chrome y tienes problemas de compatibilidad, te ofrecemos instrucciones para resolver el problema sin costo adicional.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-919">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="b6b3c-920">Para solicitar compatibilidad con App Assure, inicie sesión en el <a href="https://fasttrack.microsoft.com/portal#/signin">portal de FastTrack</a> para iniciar una interacción.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-920">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="b6b3c-921">Instrucciones de planeación para la adopción y configuración perimetrales para Búsqueda de Microsoft marcadores.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-921">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="b6b3c-922">

<strong>Lo siguiente está fuera del ámbito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b6b3c-922">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="b6b3c-923">Administración de proyectos de la implementación de Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-923">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="b6b3c-924">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="b6b3c-924">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
