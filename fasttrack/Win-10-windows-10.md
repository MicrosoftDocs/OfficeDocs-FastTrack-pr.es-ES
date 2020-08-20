---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack proporciona instrucciones de implementación para Windows 10 para ayudarle a actualizar de Windows 7 Professional y Windows 8,1 Professional a Windows 10 Enterprise.
ms.openlocfilehash: 0b19ada41624d8c8fa8d3ab5e85a14b42edd53f3
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817141"
---
# <a name="windows-10"></a><span data-ttu-id="7a43d-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="7a43d-103">Windows 10</span></span>

> [!CAUTION]
> <span data-ttu-id="7a43d-104">Este contenido ya no está actualizado y está programado para su eliminación.</span><span class="sxs-lookup"><span data-stu-id="7a43d-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="7a43d-105">Use la tabla de contenido en el panel de navegación izquierdo para el contenido actual.</span><span class="sxs-lookup"><span data-stu-id="7a43d-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="7a43d-106">FastTrack proporciona instrucciones de implementación para Windows 10 para ayudarle a actualizar de Windows 7 Professional y Windows 8,1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="7a43d-106">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="7a43d-107">Trabaje con los especialistas de FastTrack para:</span><span class="sxs-lookup"><span data-stu-id="7a43d-107">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="7a43d-108">Implemente Windows 10 Enterprise usando Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7a43d-108">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="7a43d-109">Implementación de Aplicaciones de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7a43d-109">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="7a43d-110">Actualizar Windows 10 Enterprise y Aplicaciones de Microsoft 365 con Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7a43d-110">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="7a43d-111">Conectar Configuration Manager con Microsoft Intune en la nube o implementar Intune como única solución de administración en la nube.</span><span class="sxs-lookup"><span data-stu-id="7a43d-111">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="7a43d-112">FastTrack proporciona a los clientes los procedimientos, la ayuda y el enfoque recomendados diseñados para entregar resultados rápidos y previsibles.</span><span class="sxs-lookup"><span data-stu-id="7a43d-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="7a43d-113">Si decide implementar sin tener en cuenta esta orientación, su experiencia puede verse afectada.</span><span class="sxs-lookup"><span data-stu-id="7a43d-113">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="7a43d-114">La guía se define como una combinación de asistencia verbal y escrita.</span><span class="sxs-lookup"><span data-stu-id="7a43d-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="7a43d-115">Cuando los especialistas de FastTrack proporcionan orientación, el personal de FastTrack no puede actuar en su nombre.</span><span class="sxs-lookup"><span data-stu-id="7a43d-115">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="7a43d-116">Puede usar los servicios de FastTrack para los planes válidos siempre y cuando la suscripción esté actualizada.</span><span class="sxs-lookup"><span data-stu-id="7a43d-116">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="7a43d-117">En la tabla siguiente se incluyen los roles y las responsabilidades para el proceso.</span><span class="sxs-lookup"><span data-stu-id="7a43d-117">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="7a43d-118">**Rol**</span><span class="sxs-lookup"><span data-stu-id="7a43d-118">**Role**</span></span> <br/> |<span data-ttu-id="7a43d-119">**Responsabilidad**</span><span class="sxs-lookup"><span data-stu-id="7a43d-119">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="7a43d-120">**Especialista de FastTrack**</span><span class="sxs-lookup"><span data-stu-id="7a43d-120">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="7a43d-121">Ofrece todos los servicios de implementación y actualización de forma remota.</span><span class="sxs-lookup"><span data-stu-id="7a43d-121">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="7a43d-122">Le ayuda de forma remota con una combinación de herramientas y documentación publicada.</span><span class="sxs-lookup"><span data-stu-id="7a43d-122">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="7a43d-123">Trabaja directamente con usted o su representante.</span><span class="sxs-lookup"><span data-stu-id="7a43d-123">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="7a43d-124">**Centro de FastTrack**</span><span class="sxs-lookup"><span data-stu-id="7a43d-124">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="7a43d-125">Ofrece instrucciones para planear e implementar Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="7a43d-125">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="7a43d-126">Presta asistencia y está disponible durante el horario laboral normal de cada región.</span><span class="sxs-lookup"><span data-stu-id="7a43d-126">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="7a43d-127">Presta asistencia en chino tradicional y simplificado (el personal solo habla mandarín), inglés, francés, alemán, italiano, japonés, coreano, portugués (Brasil), español, tailandés y vietnamita.</span><span class="sxs-lookup"><span data-stu-id="7a43d-127">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="7a43d-128">Puede obtener ayuda mediante el [Centro de administración de Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704) o el [sitio de FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).</span><span class="sxs-lookup"><span data-stu-id="7a43d-128">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="7a43d-129">Para iniciar sesión, debe tener una cuenta profesional o educativa activa (ID. de organización o ID. de Azure Active Directory) en un inquilino activo.</span><span class="sxs-lookup"><span data-stu-id="7a43d-129">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="7a43d-130">Para obtener ayuda a través del [sitio de FastTrack](https://go.microsoft.com/fwlink/?linkid=780698):</span><span class="sxs-lookup"><span data-stu-id="7a43d-130">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="7a43d-131">Inicie sesión en el [sitio de FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).</span><span class="sxs-lookup"><span data-stu-id="7a43d-131">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="7a43d-132">Seleccione **Solicitar asistencia con Microsoft 365** en las **acciones rápidas** en la parte superior de la página de aterrizaje.</span><span class="sxs-lookup"><span data-stu-id="7a43d-132">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="7a43d-133">Complete el formulario **Solicitar asistencia con Microsoft 365**.</span><span class="sxs-lookup"><span data-stu-id="7a43d-133">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="7a43d-p105">Los partners también pueden obtener ayuda en el [sitio de FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) en nombre de un cliente. Para hacerlo:</span><span class="sxs-lookup"><span data-stu-id="7a43d-p105">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="7a43d-136">Inicie sesión en el [sitio de FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).</span><span class="sxs-lookup"><span data-stu-id="7a43d-136">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="7a43d-137">Seleccione **Solicitar asistencia con Microsoft 365** en las **acciones rápidas** en la parte superior de la página de aterrizaje.</span><span class="sxs-lookup"><span data-stu-id="7a43d-137">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="7a43d-138">Para buscar el cliente, escriba el nombre del cliente, dominio o TPID.</span><span class="sxs-lookup"><span data-stu-id="7a43d-138">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="7a43d-139">Seleccione el cliente en los resultados de la búsqueda.</span><span class="sxs-lookup"><span data-stu-id="7a43d-139">Select customer from the search results.</span></span>
5.    <span data-ttu-id="7a43d-140">Complete el formulario **Solicitar asistencia con Microsoft 365**.</span><span class="sxs-lookup"><span data-stu-id="7a43d-140">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
