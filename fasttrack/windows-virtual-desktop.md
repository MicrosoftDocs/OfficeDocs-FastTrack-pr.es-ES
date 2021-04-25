---
title: Windows Virtual Desktop
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack proporciona instrucciones de implementación de Escritorio virtual de Windows para ayudarte a incorporarte a este escritorio.
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996243"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="bd388-103">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="bd388-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="bd388-104"><strong>Servicio</strong></span><span class="sxs-lookup"><span data-stu-id="bd388-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="bd388-105"><strong>Detalles de instrucciones de FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="bd388-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="bd388-106"><strong>Expectativas del entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="bd388-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="bd388-107">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="bd388-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="bd388-108">FastTrack proporciona instrucciones de implementación de Escritorio virtual de Windows para ayudarle a incorporarse a este servicio de virtualización de aplicaciones y escritorio con facilidad al aprovechar la experiencia de varias sesiones de Windows 10, optimizada para Aplicaciones de Microsoft 365 para empresas con seguridad y administración integradas para Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="bd388-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="bd388-109">Trabaje con los especialistas de FastTrack para:</span><span class="sxs-lookup"><span data-stu-id="bd388-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-110">Implemente el entorno WVD con Windows 10 Enterprise multi-session + Aplicaciones de Microsoft 365 para empresas con lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="bd388-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-111">Imagen de Azure Marketplace</span><span class="sxs-lookup"><span data-stu-id="bd388-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="bd388-112">Imagen compartida</span><span class="sxs-lookup"><span data-stu-id="bd388-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="bd388-113">Office Deployment Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="bd388-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="bd388-114">Configurar FSLogix</span><span class="sxs-lookup"><span data-stu-id="bd388-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-115">Implementar el agente FSLogix con el contenedor de perfiles</span><span class="sxs-lookup"><span data-stu-id="bd388-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="bd388-116">Implementar el agente FSLogix con el contenedor de Office</span><span class="sxs-lookup"><span data-stu-id="bd388-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="bd388-117">Configurar la carpeta FSLogix con exclusiones de contenido</span><span class="sxs-lookup"><span data-stu-id="bd388-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="bd388-118">Implementar Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="bd388-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="bd388-119">Implementar Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="bd388-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="bd388-120">Conectarse con clientes de Escritorio virtual de Windows</span><span class="sxs-lookup"><span data-stu-id="bd388-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="bd388-121"><strong>Lo siguiente está fuera del ámbito</strong></span><span class="sxs-lookup"><span data-stu-id="bd388-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-122">Administración de proyectos de la implementación de Windows Virtual Desktop del cliente.</span><span class="sxs-lookup"><span data-stu-id="bd388-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="bd388-123">Soporte técnico en las instalaciones.</span><span class="sxs-lookup"><span data-stu-id="bd388-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="bd388-124">Implementación e virtualización de aplicaciones de terceros.</span><span class="sxs-lookup"><span data-stu-id="bd388-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="bd388-125">Imágenes personalizadas.</span><span class="sxs-lookup"><span data-stu-id="bd388-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="bd388-126">Migraciones y escenarios en los que participan VMware y Citrix.</span><span class="sxs-lookup"><span data-stu-id="bd388-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="bd388-127">Escenarios de Linux.</span><span class="sxs-lookup"><span data-stu-id="bd388-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="bd388-128">Conversión o migraciones de perfiles de usuario.</span><span class="sxs-lookup"><span data-stu-id="bd388-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="bd388-129">Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</span><span class="sxs-lookup"><span data-stu-id="bd388-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="bd388-130">Ya debería tener lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="bd388-130">You should already have the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licencias de WVD</a></span><span class="sxs-lookup"><span data-stu-id="bd388-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD Licensing Requirements</a></span></span></p></li>
<li><p><span data-ttu-id="bd388-132">Redes de Azure:</span><span class="sxs-lookup"><span data-stu-id="bd388-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-133">Creación de VNET &amp; Subredes</span><span class="sxs-lookup"><span data-stu-id="bd388-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="bd388-134">Firewall/Grupos de seguridad de red</span><span class="sxs-lookup"><span data-stu-id="bd388-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="bd388-135">VPN /ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="bd388-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="bd388-136">Enrutamiento a Azure desde local</span><span class="sxs-lookup"><span data-stu-id="bd388-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="bd388-137">Reglas de firewall para permitir la conectividad a WVD</span><span class="sxs-lookup"><span data-stu-id="bd388-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Referencia de documentos</a></span><span class="sxs-lookup"><span data-stu-id="bd388-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Docs Reference</a></span></span></p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="bd388-139">Instalación general de Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="bd388-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-140">Estrategia de <strong>identidad (seleccione SOLO 1 de las 3 opciones siguientes)</strong></span><span class="sxs-lookup"><span data-stu-id="bd388-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="bd388-141">Active Directory con Azure AD Connect en Azure</span><span class="sxs-lookup"><span data-stu-id="bd388-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="bd388-142">Active Directory con Azure AD Connect On Premise over VPN /ER</span><span class="sxs-lookup"><span data-stu-id="bd388-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="bd388-143">Servicios de dominio de Active Directory</span><span class="sxs-lookup"><span data-stu-id="bd388-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
