---
title: Migración de datos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa). El tipo de asistencia que proporcionamos depende del número de licencias de Office 365.
ms.openlocfilehash: 7b796ea88c884445bd7069c6c7768c8fc3e3d170
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827662"
---
# <a name="data-migration"></a><span data-ttu-id="e240c-104">Migración de datos</span><span class="sxs-lookup"><span data-stu-id="e240c-104">Data Migration</span></span>

<span data-ttu-id="e240c-105">FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa).</span><span class="sxs-lookup"><span data-stu-id="e240c-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="e240c-106">El tipo de asistencia que proporcionamos depende del número de licencias de Office 365 que tenga:</span><span class="sxs-lookup"><span data-stu-id="e240c-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="e240c-107">**En el caso de cuentas empresariales de Office 365 con 150-499 licencias** : FastTrack solo proporciona instrucciones para la migración, usted es el responsable de realizar la migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-107">**For Office 365 tenants with 150-499 licenses** : FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="e240c-108">Lo guiaremos a través de documentación que le ayudará a planear y a usar herramientas gratuitas para realizar una migración de autoservicio.</span><span class="sxs-lookup"><span data-stu-id="e240c-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="e240c-109">**En el caso de cuentas empresariales de Office 365 con más de 500 licencias** : FastTrack proporciona instrucciones para la migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-109">**For Office 365 tenants with 500 or more licenses** : FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="e240c-110">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y su espacio empresarial de Office 365 y aprovechar nuestros servicios de migración de datos para migrar sus datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="e240c-111">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-111">You create and schedule your migration events.</span></span> <span data-ttu-id="e240c-112">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="e240c-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="e240c-113">Si compró o renovó un plan comercial antes del 1° de septiembre de 2017, solo necesita 150 licencias para calificar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="e240c-114">En el caso de los planes educativos, solo las licencias pagas del profesorado y el personal pueden optar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="e240c-115">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="e240c-115">Considerations</span></span>

  - <span data-ttu-id="e240c-116">Los entornos de origen deben cumplir expectativas específicas para poder migrar datos a Office 365.</span><span class="sxs-lookup"><span data-stu-id="e240c-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="e240c-117">Para obtener más información sobre las expectativas del entorno de origen de Exchange, SharePoint y OneDrive para la Empresa, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="e240c-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="e240c-118">Requerimos el acceso y los permisos adecuados de acceso a sus entornos de origen y a su cuenta empresarial de Office 365 para proporcionar los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="e240c-119">Nuestros servicios de migración de datos no están diseñados ni tienen como objetivo fungir como datos de un sujeto interesado para cumplir con obligaciones jurídicas especiales o requisitos legales.</span><span class="sxs-lookup"><span data-stu-id="e240c-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="e240c-120">A medida que migramos los datos, se pueden transferir, almacenar y procesar en cualquier lugar en el que mantengamos instalaciones (a menos que se disponga de otro modo en el proyecto de migración de FastTrack).</span><span class="sxs-lookup"><span data-stu-id="e240c-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="e240c-121">Microsoft no puede garantizar la velocidad de la migración de archivos o correos.</span><span class="sxs-lookup"><span data-stu-id="e240c-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="e240c-122">Hay problemas imprevistos (como elementos ilegibles o dañados en el entorno de origen) que podrían afectar nuestra capacidad para migrar algunos de los elementos de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="e240c-123">Los factores externos más allá de nuestro control (como los cambios a las interfaces de programación de aplicaciones (API) de terceros) pueden ocasionar cambios, retrasos o la suspensión de nuestros servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="e240c-124">Disponibilidad del servicio de migración</span><span class="sxs-lookup"><span data-stu-id="e240c-124">Migration service availability</span></span>

  - <span data-ttu-id="e240c-125">**Para clientes comerciales y gubernamentales del Reino Unido:** Proporcionamos servicios de migración de datos las 24 horas del día, los siete (7) días de la semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="e240c-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="e240c-126">**Para clientes gubernamentales/DOD de Estados Unidos:** Proporcionamos servicios de migración de datos las 24 horas del día, los cinco (5) días hábiles de la semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="e240c-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="e240c-127">Migración a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="e240c-127">Migration to Exchange Online</span></span>

<span data-ttu-id="e240c-128">Cuando elige usar FastTrack para migrar su correo electrónico a Exchange Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="e240c-129">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de Exchange Online, y aprovechar nuestros servicios de migración de datos para migrar sus buzones.</span><span class="sxs-lookup"><span data-stu-id="e240c-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="e240c-130">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-130">You create and schedule your migration events.</span></span> <span data-ttu-id="e240c-131">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="e240c-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="e240c-132">Cuando los eventos de migración se completen, encontrará que los correos provenientes de los buzones de origen que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e240c-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="e240c-133">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="e240c-133">Considerations</span></span>

  - <span data-ttu-id="e240c-134">Antes de la migración, debe completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e240c-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="e240c-135">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="e240c-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="e240c-136">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="e240c-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="e240c-137">FastTrack solo migra a buzones de Office 365 que estén activos.</span><span class="sxs-lookup"><span data-stu-id="e240c-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="e240c-138">Si tiene previsto migrar desde un entorno local de Exchange, debe cumplir los requisitos específicos.</span><span class="sxs-lookup"><span data-stu-id="e240c-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="e240c-139">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="e240c-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="e240c-140">Todos los entornos de origen deben tener el Service Pack (SP) y la actualización acumulativa (RU)/paquete acumulativo de actualizaciones (CU) en el último nivel para el producto correspondiente en el entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="e240c-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="e240c-141">Las listas de distribución (objetos *MailEnabledGroup* ) y los contactos externos (objetos *MailEnabledContact* ) que existen en su Active Directory local no forman parte de la migración de datos del buzón.</span><span class="sxs-lookup"><span data-stu-id="e240c-141">Distribution lists ( *MailEnabledGroup* objects) and external contacts ( *MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="e240c-142">Sin embargo, puede sincronizarlos usando Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="e240c-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="e240c-143">Entornos de origen</span><span class="sxs-lookup"><span data-stu-id="e240c-143">Source environments</span></span>

<span data-ttu-id="e240c-144">Nuestro servicio de migración de datos migra los datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="e240c-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="e240c-145">Uno o varios bosques de Active Directory con una o varias organizaciones de Exchange (cada sistema de correo de Exchange debe ser Exchange 2010 o superior).</span><span class="sxs-lookup"><span data-stu-id="e240c-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="e240c-146">Un solo entorno de correo electrónico compatible con IMAP.</span><span class="sxs-lookup"><span data-stu-id="e240c-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="e240c-147">Entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="e240c-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="e240c-148">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="e240c-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e240c-149"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="e240c-150"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="e240c-151"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="e240c-152"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e240c-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="e240c-154">
<strong>Nota:</strong> Para las dependencias de Exchange local, consulte <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">requisitos previos de la implementación híbrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="e240c-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="e240c-155">Migración con implementación híbrida</span><span class="sxs-lookup"><span data-stu-id="e240c-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="e240c-156">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="e240c-156">Emails</span></span></li>
<li><span data-ttu-id="e240c-157">Reglas de buzón</span><span class="sxs-lookup"><span data-stu-id="e240c-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="e240c-158">Delegados</span><span class="sxs-lookup"><span data-stu-id="e240c-158">Delegates</span></span></li>
<li><span data-ttu-id="e240c-159">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="e240c-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="e240c-160">Calendario</span><span class="sxs-lookup"><span data-stu-id="e240c-160">Calendar</span></span> </li>
<li> <span data-ttu-id="e240c-161">Tareas</span><span class="sxs-lookup"><span data-stu-id="e240c-161">Tasks</span></span> </li>
<li> <span data-ttu-id="e240c-162">Correos electrónicos con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="e240c-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="e240c-163">Correos electrónicos cifrados</span><span class="sxs-lookup"><span data-stu-id="e240c-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="e240c-164">Firmas</span><span class="sxs-lookup"><span data-stu-id="e240c-164">Signatures</span></span> </li>
<li> <span data-ttu-id="e240c-165">Archivo personal migrado con el buzón del usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="e240c-166">Elementos recuperables</span><span class="sxs-lookup"><span data-stu-id="e240c-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e240c-167">Carpetas públicas</span><span class="sxs-lookup"><span data-stu-id="e240c-167">Public folders</span></span> </li>
<li> <span data-ttu-id="e240c-168">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="e240c-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="e240c-169">Archivo de registro en diario o cualquier solución de archivo de terceros</span><span class="sxs-lookup"><span data-stu-id="e240c-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="e240c-170">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e240c-171">Datos de archivo procedentes de archivos PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="e240c-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="e240c-172">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="e240c-173">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e240c-174"><strong>Entorno de G Suite (solo Gmail, Contactos y Calendario)</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="e240c-175">
<strong>Nota:</strong> El entorno de G Suite debe cumplir los requisitos previos descritos en <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a g Suite Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="e240c-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="e240c-176">Total o preconfigurada</span><span class="sxs-lookup"><span data-stu-id="e240c-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-177">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="e240c-177">Emails</span></span> </li>
<li> <span data-ttu-id="e240c-178">Contactos del buzón (se migra un máximo de 3 direcciones de correo electrónico por contacto)</span><span class="sxs-lookup"><span data-stu-id="e240c-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="e240c-179">Calendar</span><span class="sxs-lookup"><span data-stu-id="e240c-179">Calendar</span></span> </li>
<li> <span data-ttu-id="e240c-180">Etiquetas</span><span class="sxs-lookup"><span data-stu-id="e240c-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e240c-181">Reglas</span><span class="sxs-lookup"><span data-stu-id="e240c-181">Rules</span></span> </li>
<li> <span data-ttu-id="e240c-182">Delegados</span><span class="sxs-lookup"><span data-stu-id="e240c-182">Delegates</span></span> </li>
<li> <span data-ttu-id="e240c-183">Firmas</span><span class="sxs-lookup"><span data-stu-id="e240c-183">Signatures</span></span> </li>
<li> <span data-ttu-id="e240c-184">Tareas</span><span class="sxs-lookup"><span data-stu-id="e240c-184">Tasks</span></span> </li>
<li> <span data-ttu-id="e240c-185">Cualquier correo electrónico o dato adjunto que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="e240c-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="e240c-186">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e240c-187">Datos de archivo procedentes de archivos PST o de soluciones de archivo de terceros (por ejemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="e240c-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="e240c-188">Mensajes de correo electrónico cifrados o con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="e240c-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="e240c-189">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="e240c-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="e240c-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="e240c-191">Grupos de Google</span><span class="sxs-lookup"><span data-stu-id="e240c-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="e240c-192">Buzones de recursos</span><span class="sxs-lookup"><span data-stu-id="e240c-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="e240c-193">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="e240c-194">Configuración de ausencia por vacaciones y respuesta automática</span><span class="sxs-lookup"><span data-stu-id="e240c-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="e240c-195">Calendarios compartidos, datos adjuntos en la nube, vínculos a Google Hangout y colores del evento</span><span class="sxs-lookup"><span data-stu-id="e240c-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="e240c-196">\*\*Se migran las conversaciones de Hangouts guardadas como etiqueta.</span><span class="sxs-lookup"><span data-stu-id="e240c-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e240c-197"><strong>Origen de IMAP4 (como Domino, GroupWise o Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="e240c-198">Migración con herramientas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="e240c-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="e240c-199">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="e240c-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="e240c-200">Reglas</span><span class="sxs-lookup"><span data-stu-id="e240c-200">Rules</span></span> </li>
<li> <span data-ttu-id="e240c-201">Delegados</span><span class="sxs-lookup"><span data-stu-id="e240c-201">Delegates</span></span> </li>
<li> <span data-ttu-id="e240c-202">Listas de distribución</span><span class="sxs-lookup"><span data-stu-id="e240c-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="e240c-203">Contactos externos</span><span class="sxs-lookup"><span data-stu-id="e240c-203">External contacts</span></span> </li>
<li> <span data-ttu-id="e240c-204">Usuarios habilitados para correo</span><span class="sxs-lookup"><span data-stu-id="e240c-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="e240c-205">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e240c-206">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="e240c-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="e240c-207">Calendario</span><span class="sxs-lookup"><span data-stu-id="e240c-207">Calendar</span></span> </li>
<li> <span data-ttu-id="e240c-208">Firmas</span><span class="sxs-lookup"><span data-stu-id="e240c-208">Signatures</span></span> </li>
<li> <span data-ttu-id="e240c-209">Tareas</span><span class="sxs-lookup"><span data-stu-id="e240c-209">Tasks</span></span> </li>
<li> <span data-ttu-id="e240c-210">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="e240c-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="e240c-211">Datos de archivo</span><span class="sxs-lookup"><span data-stu-id="e240c-211">Archive data</span></span> </li>
<li> <span data-ttu-id="e240c-212">Correo electrónico cifrado</span><span class="sxs-lookup"><span data-stu-id="e240c-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="e240c-213">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="e240c-214">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="e240c-215">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="e240c-215">FastTrack responsibilities</span></span>

<span data-ttu-id="e240c-216">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="e240c-217">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="e240c-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="e240c-218">Nuestros especialistas de FastTrack también realizan las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="e240c-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="e240c-219">Ofrece instrucciones para ayudarle a habilitar la coexistencia de enrutamiento de correo SMTP entre los entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="e240c-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="e240c-220">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="e240c-220">Your responsibilities</span></span>

<span data-ttu-id="e240c-221">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="e240c-222">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="e240c-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="e240c-223">También realizará las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="e240c-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="e240c-224">Completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e240c-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="e240c-225">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="e240c-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="e240c-226">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="e240c-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="e240c-227">Instalar el nivel adecuado del software del cliente según las instrucciones de Office 365.</span><span class="sxs-lookup"><span data-stu-id="e240c-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="e240c-228">Para obtener más información, consulte [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="e240c-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="e240c-229">Cumplir los requerimientos específicos si tiene previsto migrar desde un entorno local de Exchange.</span><span class="sxs-lookup"><span data-stu-id="e240c-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="e240c-230">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="e240c-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="e240c-231">Asegurarse de que cada entorno de origen tenga la versión más reciente del Service Pack (SP) y de la actualización cumulativa (RU)/paquete acumulativo de actualizaciones (CU), si procede.</span><span class="sxs-lookup"><span data-stu-id="e240c-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="e240c-232">Configurar y validar la coexistencia del enrutamiento de correo SMTP entre sus entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="e240c-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="e240c-233">Asegurarse de que el tamaño de su buzón de origen no supere la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="e240c-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="e240c-234">Dependiendo de la plataforma de origen, es posible que deba limitar los datos de origen a 85% de la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="e240c-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="e240c-235">Puede migrar los datos del lado del cliente, si lo desea.</span><span class="sxs-lookup"><span data-stu-id="e240c-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="e240c-236">Esto incluye, entre otras cosas, las libretas de direcciones locales, los datos de los archivos PST locales, las reglas de Outlook y la configuración local de Outlook.</span><span class="sxs-lookup"><span data-stu-id="e240c-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="e240c-237">Ayudar a los usuarios finales con la corrección de los problemas de migración del lado del cliente.</span><span class="sxs-lookup"><span data-stu-id="e240c-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="e240c-238">Migración a SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="e240c-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="e240c-239">Cuando elige usar FastTrack para migrar sus archivos a SharePoint Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="e240c-240">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de SharePoint Online, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="e240c-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="e240c-241">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-241">You create and schedule your migration events.</span></span> <span data-ttu-id="e240c-242">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="e240c-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="e240c-243">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e240c-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="e240c-244">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="e240c-244">Considerations</span></span>

  - <span data-ttu-id="e240c-245">Todas las migraciones están sujetas a las cuotas de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e240c-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="e240c-246">Consulte los [<span class="underline">Límites de software de SharePoint Online y de OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="e240c-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="e240c-247">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="e240c-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="e240c-248">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="e240c-248">Source environment details</span></span>

<span data-ttu-id="e240c-249">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="e240c-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="e240c-250">Recursos compartidos de archivos (recursos compartidos de archivos de Bloqueo de mensajes del servidor (SMB) en dispositivos compatibles a partir de SMB 2.0 en adelante).</span><span class="sxs-lookup"><span data-stu-id="e240c-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="e240c-251">Un solo entorno de G Suite (solo Google Drive).</span><span class="sxs-lookup"><span data-stu-id="e240c-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="e240c-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="e240c-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="e240c-253">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="e240c-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="e240c-254">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="e240c-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e240c-255"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="e240c-256"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="e240c-257"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="e240c-258"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e240c-259"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="e240c-260">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="e240c-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-261">Documentos</span><span class="sxs-lookup"><span data-stu-id="e240c-261">Documents</span></span> </li>
<li> <span data-ttu-id="e240c-262">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e240c-263">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="e240c-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="e240c-264">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="e240c-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="e240c-265">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="e240c-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e240c-266">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="e240c-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e240c-267">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="e240c-267">Created date</span></span> </li>
<li> <span data-ttu-id="e240c-268">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-268">Modified date</span></span> </li>
<li> <span data-ttu-id="e240c-269">Creada por</span><span class="sxs-lookup"><span data-stu-id="e240c-269">Created by</span></span> </li>
<li> <span data-ttu-id="e240c-270">Última modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="e240c-271">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="e240c-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="e240c-272">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="e240c-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="e240c-273">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="e240c-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="e240c-274">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="e240c-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-275">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="e240c-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="e240c-276">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="e240c-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e240c-277">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="e240c-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="e240c-278">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="e240c-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="e240c-279">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="e240c-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="e240c-280">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="e240c-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="e240c-281">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="e240c-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="e240c-282">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="e240c-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="e240c-283">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e240c-284">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="e240c-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="e240c-285">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="e240c-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="e240c-286">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="e240c-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e240c-287"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="e240c-288">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="e240c-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-289">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office), incluidos los de más de 10 MB</span><span class="sxs-lookup"><span data-stu-id="e240c-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="e240c-290">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e240c-291">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-292">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-293">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="e240c-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e240c-294">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="e240c-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e240c-295">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="e240c-295">Created date</span></span> </li>
<li> <span data-ttu-id="e240c-296">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-296">Modified date</span></span> </li>
<li> <span data-ttu-id="e240c-297">Creada por</span><span class="sxs-lookup"><span data-stu-id="e240c-297">Created by</span></span> </li>
<li> <span data-ttu-id="e240c-298">Última modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e240c-299">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="e240c-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="e240c-300">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="e240c-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e240c-301">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="e240c-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e240c-302">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="e240c-303">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-304">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-305">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="e240c-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="e240c-306">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="e240c-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e240c-307">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="e240c-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e240c-308">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="e240c-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="e240c-309">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e240c-310">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e240c-311">Google Fotos, Formularios de Google, Google Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="e240c-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="e240c-312">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="e240c-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="e240c-313">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="e240c-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="e240c-314">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="e240c-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="e240c-315">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="e240c-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="e240c-316">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="e240c-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e240c-317">Permisos de suscripción a una unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="e240c-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="e240c-318">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="e240c-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="e240c-319">Archivos marcados como restringidos o no copiables</span><span class="sxs-lookup"><span data-stu-id="e240c-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="e240c-320">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="e240c-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e240c-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="e240c-322">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="e240c-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-323">Documentos</span><span class="sxs-lookup"><span data-stu-id="e240c-323">Documents</span></span> </li>
<li> <span data-ttu-id="e240c-324">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e240c-325">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-326">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-327">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="e240c-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e240c-328">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="e240c-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e240c-329">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="e240c-329">Created date</span></span> </li>
<li> <span data-ttu-id="e240c-330">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-330">Modified date</span></span> </li>
<li> <span data-ttu-id="e240c-331">Creada por</span><span class="sxs-lookup"><span data-stu-id="e240c-331">Created by</span></span> </li>
<li> <span data-ttu-id="e240c-332">Última modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e240c-333">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="e240c-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e240c-334">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="e240c-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e240c-335">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="e240c-336">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-337">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-338">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="e240c-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="e240c-339">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="e240c-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e240c-340">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="e240c-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e240c-341">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="e240c-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="e240c-342">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e240c-343">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e240c-344">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="e240c-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="e240c-345">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="e240c-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="e240c-346">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="e240c-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="e240c-347">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="e240c-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e240c-348">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="e240c-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e240c-349"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="e240c-350">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="e240c-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-351">Documentos</span><span class="sxs-lookup"><span data-stu-id="e240c-351">Documents</span></span> </li>
<li> <span data-ttu-id="e240c-352">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e240c-353">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-354">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-355">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="e240c-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e240c-356">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="e240c-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e240c-357">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="e240c-357">Created date</span></span> </li>
<li> <span data-ttu-id="e240c-358">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-358">Modified date</span></span> </li>
<li> <span data-ttu-id="e240c-359">Creada por</span><span class="sxs-lookup"><span data-stu-id="e240c-359">Created by</span></span> </li>
<li> <span data-ttu-id="e240c-360">Última modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e240c-361">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="e240c-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="e240c-362">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="e240c-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e240c-363">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="e240c-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e240c-364">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="e240c-365">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-366">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-367">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="e240c-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="e240c-368">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="e240c-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e240c-369">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="e240c-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e240c-370">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="e240c-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="e240c-371">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e240c-372">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="e240c-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="e240c-373">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="e240c-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="e240c-374">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="e240c-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="e240c-375">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="e240c-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="e240c-376">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="e240c-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="e240c-377">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="e240c-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="e240c-378">Informe a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración)</span><span class="sxs-lookup"><span data-stu-id="e240c-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="e240c-379">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="e240c-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="e240c-380">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="e240c-380">FastTrack responsibilities</span></span>

<span data-ttu-id="e240c-381">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="e240c-382">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="e240c-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="e240c-383">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="e240c-383">Your responsibilities</span></span>

<span data-ttu-id="e240c-384">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="e240c-385">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="e240c-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="e240c-386">Usted también realizará las siguientes actividades, específicas para las migraciones de SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="e240c-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="e240c-387">Aprovisionamiento de todos los sitios del grupo de SharePoint que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="e240c-388">Migración a OneDrive para la Empresa</span><span class="sxs-lookup"><span data-stu-id="e240c-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="e240c-389">Cuando elige usar FastTrack para migrar sus archivos a OneDrive para la Empresa, proporcionamos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="e240c-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="e240c-390">Le proporcionamos instrucciones para ayudarle a planear su migración, configurar sus entornos de origen y de OneDrive para la Empresa, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="e240c-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="e240c-391">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-391">You create and schedule your migration events.</span></span> <span data-ttu-id="e240c-392">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="e240c-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="e240c-393">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="e240c-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="e240c-394">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="e240c-394">Considerations</span></span>

  - <span data-ttu-id="e240c-395">Todas las migraciones están sujetas a las cuotas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="e240c-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="e240c-396">Consulte los [<span class="underline">Límites de software de SharePoint Online y OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="e240c-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="e240c-397">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="e240c-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="e240c-398">FastTrack realiza la migración solo para las unidades activas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="e240c-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="e240c-399">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="e240c-399">Source environment details</span></span>

<span data-ttu-id="e240c-400">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="e240c-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="e240c-401">Recursos compartidos de archivos (recursos compartidos de archivos de SMB en dispositivos compatibles a partir de SMB 2.0).</span><span class="sxs-lookup"><span data-stu-id="e240c-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="e240c-402">Un solo entorno de G Suite (solo Google Drive)</span><span class="sxs-lookup"><span data-stu-id="e240c-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="e240c-403">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="e240c-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="e240c-404">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="e240c-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="e240c-405">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="e240c-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="e240c-406"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="e240c-407"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="e240c-408"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="e240c-409"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e240c-410"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="e240c-411">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="e240c-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-412">Documentos</span><span class="sxs-lookup"><span data-stu-id="e240c-412">Documents</span></span> </li>
<li> <span data-ttu-id="e240c-413">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e240c-414">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="e240c-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="e240c-415">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="e240c-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="e240c-416">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="e240c-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e240c-417">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="e240c-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e240c-418">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="e240c-418">Created date</span></span> </li>
<li> <span data-ttu-id="e240c-419">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-419">Modified date</span></span> </li>
<li> <span data-ttu-id="e240c-420">Creada por</span><span class="sxs-lookup"><span data-stu-id="e240c-420">Created by</span></span> </li>
<li> <span data-ttu-id="e240c-421">Última modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="e240c-422">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="e240c-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="e240c-423">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="e240c-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="e240c-424">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="e240c-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="e240c-425">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="e240c-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="e240c-426">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="e240c-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="e240c-427">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="e240c-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e240c-428">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="e240c-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="e240c-429">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="e240c-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="e240c-430">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="e240c-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="e240c-431">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="e240c-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="e240c-432">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="e240c-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="e240c-433">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="e240c-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="e240c-434">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e240c-435">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="e240c-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="e240c-436">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="e240c-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="e240c-437">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="e240c-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e240c-438"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="e240c-439">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="e240c-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-440">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office, incluidos los de más de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="e240c-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="e240c-441">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e240c-442">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-443">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-444">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="e240c-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e240c-445">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="e240c-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e240c-446">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="e240c-446">Created date</span></span> </li>
<li> <span data-ttu-id="e240c-447">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-447">Modified date</span></span> </li>
<li> <span data-ttu-id="e240c-448">Creada por</span><span class="sxs-lookup"><span data-stu-id="e240c-448">Created by</span></span> </li>
<li> <span data-ttu-id="e240c-449">Última modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e240c-450">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="e240c-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="e240c-451">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="e240c-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e240c-452">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="e240c-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e240c-453">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="e240c-454">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-455">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-456">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="e240c-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="e240c-457">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="e240c-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e240c-458">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="e240c-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e240c-459">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="e240c-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="e240c-460">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e240c-461">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e240c-462">Formularios de Google Photos, Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="e240c-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="e240c-463">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="e240c-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="e240c-464">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="e240c-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="e240c-465">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="e240c-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="e240c-466">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="e240c-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="e240c-467">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="e240c-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e240c-468">Permisos de suscripción de la unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="e240c-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="e240c-469">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="e240c-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="e240c-470">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="e240c-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e240c-471"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="e240c-472">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="e240c-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-473">Documentos</span><span class="sxs-lookup"><span data-stu-id="e240c-473">Documents</span></span> </li>
<li> <span data-ttu-id="e240c-474">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e240c-475">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-476">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-477">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="e240c-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e240c-478">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="e240c-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e240c-479">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="e240c-479">Created date</span></span> </li>
<li> <span data-ttu-id="e240c-480">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-480">Modified date</span></span> </li>
<li> <span data-ttu-id="e240c-481">Creada por</span><span class="sxs-lookup"><span data-stu-id="e240c-481">Created by</span></span> </li>
<li> <span data-ttu-id="e240c-482">Última modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e240c-483">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="e240c-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e240c-484">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="e240c-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e240c-485">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="e240c-486">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-487">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-488">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="e240c-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="e240c-489">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="e240c-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e240c-490">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="e240c-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e240c-491">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="e240c-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="e240c-492">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e240c-493">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="e240c-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="e240c-494">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="e240c-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="e240c-495">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="e240c-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="e240c-496">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="e240c-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="e240c-497">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="e240c-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e240c-498">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="e240c-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e240c-499"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="e240c-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="e240c-500">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="e240c-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="e240c-501">Documentos</span><span class="sxs-lookup"><span data-stu-id="e240c-501">Documents</span></span> </li>
<li> <span data-ttu-id="e240c-502">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="e240c-503">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-504">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="e240c-505">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="e240c-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="e240c-506">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="e240c-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="e240c-507">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="e240c-507">Created date</span></span> </li>
<li> <span data-ttu-id="e240c-508">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-508">Modified date</span></span> </li>
<li> <span data-ttu-id="e240c-509">Creada por</span><span class="sxs-lookup"><span data-stu-id="e240c-509">Created by</span></span> </li>
<li> <span data-ttu-id="e240c-510">Última modificación</span><span class="sxs-lookup"><span data-stu-id="e240c-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="e240c-511">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="e240c-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="e240c-512">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="e240c-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="e240c-513">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="e240c-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="e240c-514">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="e240c-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="e240c-515">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="e240c-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-516">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="e240c-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="e240c-517">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="e240c-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="e240c-518">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="e240c-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="e240c-519">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="e240c-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="e240c-520">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="e240c-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="e240c-521">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="e240c-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="e240c-522">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="e240c-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="e240c-523">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="e240c-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="e240c-524">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="e240c-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="e240c-525">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="e240c-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="e240c-526">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="e240c-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="e240c-527">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="e240c-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="e240c-528">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="e240c-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="e240c-529">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="e240c-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="e240c-530">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="e240c-530">FastTrack responsibilities</span></span>

<span data-ttu-id="e240c-531">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="e240c-532">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="e240c-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="e240c-533">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="e240c-533">Your responsibilities</span></span>

<span data-ttu-id="e240c-534">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="e240c-535">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="e240c-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="e240c-536">También realizará las siguientes actividades, específicas para las migraciones de OneDrive para la Empresa:</span><span class="sxs-lookup"><span data-stu-id="e240c-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="e240c-537">Aprovisionamiento de todos los sitios de OneDrive para la Empresa que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="e240c-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
