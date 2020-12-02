---
title: Migración de datos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 12/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa). El tipo de asistencia que proporcionamos depende del número de licencias de Office 365.
ms.openlocfilehash: 5a64bcbecffa3fd78f54b9a5e0f3f07e76d0b316
ms.sourcegitcommit: d69d3e1e478a817f8279e9da98880499e9302665
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/01/2020
ms.locfileid: "49525367"
---
# <a name="data-migration"></a><span data-ttu-id="8fc67-104">Migración de datos</span><span class="sxs-lookup"><span data-stu-id="8fc67-104">Data Migration</span></span>

<span data-ttu-id="8fc67-105">FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa).</span><span class="sxs-lookup"><span data-stu-id="8fc67-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="8fc67-106">El tipo de asistencia que proporcionamos depende del número de licencias de Office 365 que tenga:</span><span class="sxs-lookup"><span data-stu-id="8fc67-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="8fc67-107">**En el caso de cuentas empresariales de Office 365 con 150-499 licencias**: FastTrack solo proporciona instrucciones para la migración, usted es el responsable de realizar la migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="8fc67-108">Lo guiaremos a través de documentación que le ayudará a planear y a usar herramientas gratuitas para realizar una migración de autoservicio.</span><span class="sxs-lookup"><span data-stu-id="8fc67-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="8fc67-109">**En el caso de cuentas empresariales de Office 365 con más de 500 licencias**: FastTrack proporciona instrucciones para la migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="8fc67-110">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y su espacio empresarial de Office 365 y aprovechar nuestros servicios de migración de datos para migrar sus datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="8fc67-111">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-111">You create and schedule your migration events.</span></span> <span data-ttu-id="8fc67-112">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="8fc67-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="8fc67-113">Si compró o renovó un plan comercial antes del 1° de septiembre de 2017, solo necesita 150 licencias para calificar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="8fc67-114">En el caso de los planes educativos, solo las licencias pagas del profesorado y el personal pueden optar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="8fc67-115">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="8fc67-115">Considerations</span></span>

  - <span data-ttu-id="8fc67-116">Los entornos de origen deben cumplir expectativas específicas para poder migrar datos a Office 365.</span><span class="sxs-lookup"><span data-stu-id="8fc67-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="8fc67-117">Para obtener más información sobre las expectativas del entorno de origen de Exchange, SharePoint y OneDrive para la Empresa, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="8fc67-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="8fc67-118">Requerimos el acceso y los permisos adecuados de acceso a sus entornos de origen y a su cuenta empresarial de Office 365 para proporcionar los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="8fc67-119">Nuestros servicios de migración de datos no están diseñados ni tienen como objetivo fungir como datos de un sujeto interesado para cumplir con obligaciones jurídicas especiales o requisitos legales.</span><span class="sxs-lookup"><span data-stu-id="8fc67-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="8fc67-120">A medida que migramos los datos, se pueden transferir, almacenar y procesar en cualquier lugar en el que mantengamos instalaciones (a menos que se disponga de otro modo en el proyecto de migración de FastTrack).</span><span class="sxs-lookup"><span data-stu-id="8fc67-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="8fc67-121">Microsoft no puede garantizar la velocidad de la migración de archivos o correos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="8fc67-122">Hay problemas imprevistos (como elementos ilegibles o dañados en el entorno de origen) que podrían afectar nuestra capacidad para migrar algunos de los elementos de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="8fc67-123">Los factores externos más allá de nuestro control (como los cambios a las interfaces de programación de aplicaciones (API) de terceros) pueden ocasionar cambios, retrasos o la suspensión de nuestros servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="8fc67-124">Disponibilidad del servicio de migración</span><span class="sxs-lookup"><span data-stu-id="8fc67-124">Migration service availability</span></span>

  - <span data-ttu-id="8fc67-125">**Para clientes comerciales y gubernamentales del Reino Unido:** Proporcionamos servicios de migración de datos las 24 horas del día, los siete (7) días de la semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="8fc67-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="8fc67-126">**Para clientes gubernamentales/DOD de Estados Unidos:** Proporcionamos servicios de migración de datos las 24 horas del día, los cinco (5) días hábiles de la semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="8fc67-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="8fc67-127">Migración a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="8fc67-127">Migration to Exchange Online</span></span>

<span data-ttu-id="8fc67-128">Cuando elige usar FastTrack para migrar su correo electrónico a Exchange Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8fc67-129">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de Exchange Online, y aprovechar nuestros servicios de migración de datos para migrar sus buzones.</span><span class="sxs-lookup"><span data-stu-id="8fc67-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="8fc67-130">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-130">You create and schedule your migration events.</span></span> <span data-ttu-id="8fc67-131">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="8fc67-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8fc67-132">Cuando los eventos de migración se completen, encontrará que los correos provenientes de los buzones de origen que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8fc67-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="8fc67-133">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="8fc67-133">Considerations</span></span>

  - <span data-ttu-id="8fc67-134">Antes de la migración, debe completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8fc67-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="8fc67-135">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8fc67-136">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="8fc67-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="8fc67-137">FastTrack solo migra a buzones de Office 365 que estén activos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="8fc67-138">Si tiene previsto migrar desde un entorno local de Exchange, debe cumplir los requisitos específicos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8fc67-139">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="8fc67-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="8fc67-140">Todos los entornos de origen deben tener el Service Pack (SP) y la actualización acumulativa (RU)/paquete acumulativo de actualizaciones (CU) en el último nivel para el producto correspondiente en el entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="8fc67-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="8fc67-141">Las listas de distribución (objetos *MailEnabledGroup*) y los contactos externos (objetos *MailEnabledContact*) que existen en su Active Directory local no forman parte de la migración de datos del buzón.</span><span class="sxs-lookup"><span data-stu-id="8fc67-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="8fc67-142">Sin embargo, puede sincronizarlos usando Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="8fc67-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="8fc67-143">Entornos de origen</span><span class="sxs-lookup"><span data-stu-id="8fc67-143">Source environments</span></span>

<span data-ttu-id="8fc67-144">Nuestro servicio de migración de datos migra los datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="8fc67-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="8fc67-145">Uno o varios bosques de Active Directory con una o varias organizaciones de Exchange (cada sistema de correo de Exchange debe ser Exchange 2010 o superior).</span><span class="sxs-lookup"><span data-stu-id="8fc67-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="8fc67-146">Un solo entorno de correo electrónico compatible con IMAP.</span><span class="sxs-lookup"><span data-stu-id="8fc67-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="8fc67-147">Entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="8fc67-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="8fc67-148">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="8fc67-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8fc67-149"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8fc67-150"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8fc67-151"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="8fc67-152"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8fc67-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="8fc67-154">
<strong>Nota:</strong> Para las dependencias de Exchange local, consulte <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">requisitos previos de la implementación híbrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="8fc67-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="8fc67-155">Migración con implementación híbrida</span><span class="sxs-lookup"><span data-stu-id="8fc67-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="8fc67-156">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="8fc67-156">Emails</span></span></li>
<li><span data-ttu-id="8fc67-157">Reglas de buzón</span><span class="sxs-lookup"><span data-stu-id="8fc67-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="8fc67-158">Delegados</span><span class="sxs-lookup"><span data-stu-id="8fc67-158">Delegates</span></span></li>
<li><span data-ttu-id="8fc67-159">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="8fc67-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8fc67-160">Calendario</span><span class="sxs-lookup"><span data-stu-id="8fc67-160">Calendar</span></span> </li>
<li> <span data-ttu-id="8fc67-161">Tareas</span><span class="sxs-lookup"><span data-stu-id="8fc67-161">Tasks</span></span> </li>
<li> <span data-ttu-id="8fc67-162">Correos electrónicos con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="8fc67-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="8fc67-163">Correos electrónicos cifrados</span><span class="sxs-lookup"><span data-stu-id="8fc67-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="8fc67-164">Firmas</span><span class="sxs-lookup"><span data-stu-id="8fc67-164">Signatures</span></span> </li>
<li> <span data-ttu-id="8fc67-165">Archivo personal migrado con el buzón del usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="8fc67-166">Elementos recuperables</span><span class="sxs-lookup"><span data-stu-id="8fc67-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8fc67-167">Carpetas públicas</span><span class="sxs-lookup"><span data-stu-id="8fc67-167">Public folders</span></span> </li>
<li> <span data-ttu-id="8fc67-168">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="8fc67-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8fc67-169">Archivo de registro en diario o cualquier solución de archivo de terceros</span><span class="sxs-lookup"><span data-stu-id="8fc67-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="8fc67-170">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8fc67-171">Datos de archivo procedentes de archivos PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="8fc67-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="8fc67-172">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8fc67-173">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8fc67-174"><strong>Entorno de G Suite (solo Gmail, Contactos y Calendario)</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="8fc67-175">
<strong>Nota:</strong> El entorno de G Suite debe cumplir los requisitos previos descritos en <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a g Suite Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="8fc67-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="8fc67-176">Total o preconfigurada</span><span class="sxs-lookup"><span data-stu-id="8fc67-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-177">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="8fc67-177">Emails</span></span> </li>
<li> <span data-ttu-id="8fc67-178">Contactos del buzón (se migra un máximo de 3 direcciones de correo electrónico por contacto)</span><span class="sxs-lookup"><span data-stu-id="8fc67-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="8fc67-179">Calendar</span><span class="sxs-lookup"><span data-stu-id="8fc67-179">Calendar</span></span> </li>
<li> <span data-ttu-id="8fc67-180">Etiquetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8fc67-181">Reglas</span><span class="sxs-lookup"><span data-stu-id="8fc67-181">Rules</span></span> </li>
<li> <span data-ttu-id="8fc67-182">Delegados</span><span class="sxs-lookup"><span data-stu-id="8fc67-182">Delegates</span></span> </li>
<li> <span data-ttu-id="8fc67-183">Firmas</span><span class="sxs-lookup"><span data-stu-id="8fc67-183">Signatures</span></span> </li>
<li> <span data-ttu-id="8fc67-184">Tareas</span><span class="sxs-lookup"><span data-stu-id="8fc67-184">Tasks</span></span> </li>
<li> <span data-ttu-id="8fc67-185">Cualquier correo electrónico o dato adjunto que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="8fc67-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8fc67-186">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8fc67-187">Datos de archivo procedentes de archivos PST o de soluciones de archivo de terceros (por ejemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="8fc67-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="8fc67-188">Mensajes de correo electrónico cifrados o con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="8fc67-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="8fc67-189">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8fc67-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="8fc67-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="8fc67-191">Grupos de Google</span><span class="sxs-lookup"><span data-stu-id="8fc67-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="8fc67-192">Buzones de recursos</span><span class="sxs-lookup"><span data-stu-id="8fc67-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="8fc67-193">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="8fc67-194">Configuración de ausencia por vacaciones y respuesta automática</span><span class="sxs-lookup"><span data-stu-id="8fc67-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="8fc67-195">Calendarios compartidos, datos adjuntos en la nube, vínculos a Google Hangout y colores del evento</span><span class="sxs-lookup"><span data-stu-id="8fc67-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="8fc67-196">\*\*Se migran las conversaciones de Hangouts guardadas como etiqueta.</span><span class="sxs-lookup"><span data-stu-id="8fc67-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8fc67-197"><strong>Origen de IMAP4 (como Domino, GroupWise o Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="8fc67-198">Migración con herramientas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="8fc67-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="8fc67-199">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="8fc67-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="8fc67-200">Reglas</span><span class="sxs-lookup"><span data-stu-id="8fc67-200">Rules</span></span> </li>
<li> <span data-ttu-id="8fc67-201">Delegados</span><span class="sxs-lookup"><span data-stu-id="8fc67-201">Delegates</span></span> </li>
<li> <span data-ttu-id="8fc67-202">Listas de distribución</span><span class="sxs-lookup"><span data-stu-id="8fc67-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="8fc67-203">Contactos externos</span><span class="sxs-lookup"><span data-stu-id="8fc67-203">External contacts</span></span> </li>
<li> <span data-ttu-id="8fc67-204">Usuarios habilitados para correo</span><span class="sxs-lookup"><span data-stu-id="8fc67-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="8fc67-205">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8fc67-206">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="8fc67-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8fc67-207">Calendario</span><span class="sxs-lookup"><span data-stu-id="8fc67-207">Calendar</span></span> </li>
<li> <span data-ttu-id="8fc67-208">Firmas</span><span class="sxs-lookup"><span data-stu-id="8fc67-208">Signatures</span></span> </li>
<li> <span data-ttu-id="8fc67-209">Tareas</span><span class="sxs-lookup"><span data-stu-id="8fc67-209">Tasks</span></span> </li>
<li> <span data-ttu-id="8fc67-210">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="8fc67-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8fc67-211">Datos de archivo</span><span class="sxs-lookup"><span data-stu-id="8fc67-211">Archive data</span></span> </li>
<li> <span data-ttu-id="8fc67-212">Correo electrónico cifrado</span><span class="sxs-lookup"><span data-stu-id="8fc67-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="8fc67-213">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8fc67-214">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8fc67-215">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="8fc67-215">FastTrack responsibilities</span></span>

<span data-ttu-id="8fc67-216">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8fc67-217">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="8fc67-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8fc67-218">Nuestros especialistas de FastTrack también realizan las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="8fc67-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="8fc67-219">Ofrece instrucciones para ayudarle a habilitar la coexistencia de enrutamiento de correo SMTP entre los entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="8fc67-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8fc67-220">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="8fc67-220">Your responsibilities</span></span>

<span data-ttu-id="8fc67-221">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8fc67-222">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="8fc67-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8fc67-223">También realizará las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="8fc67-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="8fc67-224">Completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8fc67-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="8fc67-225">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8fc67-226">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="8fc67-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="8fc67-227">Instalar el nivel adecuado del software del cliente según las instrucciones de Office 365.</span><span class="sxs-lookup"><span data-stu-id="8fc67-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="8fc67-228">Para obtener más información, consulte [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="8fc67-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="8fc67-229">Cumplir los requerimientos específicos si tiene previsto migrar desde un entorno local de Exchange.</span><span class="sxs-lookup"><span data-stu-id="8fc67-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8fc67-230">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="8fc67-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="8fc67-231">Asegurarse de que cada entorno de origen tenga la versión más reciente del Service Pack (SP) y de la actualización cumulativa (RU)/paquete acumulativo de actualizaciones (CU), si procede.</span><span class="sxs-lookup"><span data-stu-id="8fc67-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="8fc67-232">Configurar y validar la coexistencia del enrutamiento de correo SMTP entre sus entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="8fc67-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="8fc67-233">Asegurarse de que el tamaño de su buzón de origen no supere la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="8fc67-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="8fc67-234">Dependiendo de la plataforma de origen, es posible que deba limitar los datos de origen a 85% de la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="8fc67-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="8fc67-235">Puede migrar los datos del lado del cliente, si lo desea.</span><span class="sxs-lookup"><span data-stu-id="8fc67-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="8fc67-236">Esto incluye, entre otras cosas, las libretas de direcciones locales, los datos de los archivos PST locales, las reglas de Outlook y la configuración local de Outlook.</span><span class="sxs-lookup"><span data-stu-id="8fc67-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="8fc67-237">Ayudar a los usuarios finales con la corrección de los problemas de migración del lado del cliente.</span><span class="sxs-lookup"><span data-stu-id="8fc67-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="8fc67-238">Migración a SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="8fc67-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="8fc67-239">Cuando elige usar FastTrack para migrar sus archivos a SharePoint Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8fc67-240">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de SharePoint Online, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8fc67-241">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-241">You create and schedule your migration events.</span></span> <span data-ttu-id="8fc67-242">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="8fc67-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8fc67-243">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8fc67-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="8fc67-244">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="8fc67-244">Considerations</span></span>

  - <span data-ttu-id="8fc67-245">Todas las migraciones están sujetas a las cuotas de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8fc67-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="8fc67-246">Consulte los [<span class="underline">Límites de software de SharePoint Online y de OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="8fc67-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8fc67-247">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="8fc67-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8fc67-248">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="8fc67-248">Source environment details</span></span>

<span data-ttu-id="8fc67-249">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="8fc67-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8fc67-250">Recursos compartidos de archivos (recursos compartidos de archivos de Bloqueo de mensajes del servidor (SMB) en dispositivos compatibles a partir de SMB 2.0 en adelante).</span><span class="sxs-lookup"><span data-stu-id="8fc67-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8fc67-251">Un solo entorno de G Suite (solo Google Drive).</span><span class="sxs-lookup"><span data-stu-id="8fc67-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8fc67-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="8fc67-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8fc67-253">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="8fc67-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8fc67-254">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="8fc67-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8fc67-255"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8fc67-256"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8fc67-257"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8fc67-258"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8fc67-259"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8fc67-260">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="8fc67-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-261">Documentos</span><span class="sxs-lookup"><span data-stu-id="8fc67-261">Documents</span></span> </li>
<li> <span data-ttu-id="8fc67-262">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8fc67-263">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="8fc67-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8fc67-264">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="8fc67-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8fc67-265">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="8fc67-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8fc67-266">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="8fc67-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8fc67-267">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="8fc67-267">Created date</span></span> </li>
<li> <span data-ttu-id="8fc67-268">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-268">Modified date</span></span> </li>
<li> <span data-ttu-id="8fc67-269">Creada por</span><span class="sxs-lookup"><span data-stu-id="8fc67-269">Created by</span></span> </li>
<li> <span data-ttu-id="8fc67-270">Última modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="8fc67-271">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="8fc67-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8fc67-272">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="8fc67-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8fc67-273">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8fc67-274">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="8fc67-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-275">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="8fc67-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8fc67-276">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="8fc67-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8fc67-277">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="8fc67-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="8fc67-278">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="8fc67-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8fc67-279">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="8fc67-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8fc67-280">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="8fc67-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8fc67-281">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="8fc67-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8fc67-282">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="8fc67-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8fc67-283">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8fc67-284">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="8fc67-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8fc67-285">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="8fc67-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8fc67-286">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8fc67-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8fc67-287"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8fc67-288">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="8fc67-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-289">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office), incluidos los de más de 10 MB</span><span class="sxs-lookup"><span data-stu-id="8fc67-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="8fc67-290">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8fc67-291">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-292">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-293">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="8fc67-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8fc67-294">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="8fc67-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8fc67-295">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="8fc67-295">Created date</span></span> </li>
<li> <span data-ttu-id="8fc67-296">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-296">Modified date</span></span> </li>
<li> <span data-ttu-id="8fc67-297">Creada por</span><span class="sxs-lookup"><span data-stu-id="8fc67-297">Created by</span></span> </li>
<li> <span data-ttu-id="8fc67-298">Última modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8fc67-299">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="8fc67-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8fc67-300">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="8fc67-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8fc67-301">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="8fc67-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8fc67-302">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8fc67-303">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-304">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-305">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="8fc67-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8fc67-306">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8fc67-307">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="8fc67-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8fc67-308">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="8fc67-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="8fc67-309">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8fc67-310">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8fc67-311">Google Fotos, Formularios de Google, Google Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="8fc67-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8fc67-312">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="8fc67-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8fc67-313">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="8fc67-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8fc67-314">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="8fc67-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8fc67-315">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8fc67-316">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="8fc67-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8fc67-317">Permisos de suscripción a una unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="8fc67-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8fc67-318">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="8fc67-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8fc67-319">Archivos marcados como restringidos o no copiables</span><span class="sxs-lookup"><span data-stu-id="8fc67-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="8fc67-320">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8fc67-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8fc67-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8fc67-322">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="8fc67-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-323">Documentos</span><span class="sxs-lookup"><span data-stu-id="8fc67-323">Documents</span></span> </li>
<li> <span data-ttu-id="8fc67-324">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8fc67-325">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-326">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-327">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="8fc67-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8fc67-328">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="8fc67-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8fc67-329">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="8fc67-329">Created date</span></span> </li>
<li> <span data-ttu-id="8fc67-330">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-330">Modified date</span></span> </li>
<li> <span data-ttu-id="8fc67-331">Creada por</span><span class="sxs-lookup"><span data-stu-id="8fc67-331">Created by</span></span> </li>
<li> <span data-ttu-id="8fc67-332">Última modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8fc67-333">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="8fc67-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="8fc67-334">Notas del cuadro (convertidas al formato de documento de Word)</span><span class="sxs-lookup"><span data-stu-id="8fc67-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8fc67-335">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="8fc67-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8fc67-336">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8fc67-337">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-338">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-339">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="8fc67-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8fc67-340">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8fc67-341">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="8fc67-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8fc67-342">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="8fc67-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="8fc67-343">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8fc67-344">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8fc67-345">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="8fc67-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8fc67-346">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="8fc67-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8fc67-347">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8fc67-348">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="8fc67-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8fc67-349">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8fc67-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8fc67-350"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8fc67-351">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="8fc67-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-352">Documentos</span><span class="sxs-lookup"><span data-stu-id="8fc67-352">Documents</span></span> </li>
<li> <span data-ttu-id="8fc67-353">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8fc67-354">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-355">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-356">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="8fc67-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8fc67-357">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="8fc67-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8fc67-358">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="8fc67-358">Created date</span></span> </li>
<li> <span data-ttu-id="8fc67-359">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-359">Modified date</span></span> </li>
<li> <span data-ttu-id="8fc67-360">Creada por</span><span class="sxs-lookup"><span data-stu-id="8fc67-360">Created by</span></span> </li>
<li> <span data-ttu-id="8fc67-361">Última modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8fc67-362">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="8fc67-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8fc67-363">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="8fc67-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8fc67-364">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="8fc67-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8fc67-365">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8fc67-366">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-367">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-368">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="8fc67-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8fc67-369">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8fc67-370">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="8fc67-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8fc67-371">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="8fc67-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="8fc67-372">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8fc67-373">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="8fc67-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8fc67-374">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="8fc67-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8fc67-375">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="8fc67-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8fc67-376">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="8fc67-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8fc67-377">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="8fc67-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8fc67-378">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8fc67-379">Informe a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración)</span><span class="sxs-lookup"><span data-stu-id="8fc67-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="8fc67-380">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8fc67-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8fc67-381">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="8fc67-381">FastTrack responsibilities</span></span>

<span data-ttu-id="8fc67-382">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8fc67-383">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="8fc67-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8fc67-384">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="8fc67-384">Your responsibilities</span></span>

<span data-ttu-id="8fc67-385">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8fc67-386">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="8fc67-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="8fc67-387">Usted también realizará las siguientes actividades, específicas para las migraciones de SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="8fc67-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="8fc67-388">Aprovisionamiento de todos los sitios del grupo de SharePoint que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="8fc67-389">Migración a OneDrive para la Empresa</span><span class="sxs-lookup"><span data-stu-id="8fc67-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="8fc67-390">Cuando elige usar FastTrack para migrar sus archivos a OneDrive para la Empresa, proporcionamos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8fc67-391">Le proporcionamos instrucciones para ayudarle a planear su migración, configurar sus entornos de origen y de OneDrive para la Empresa, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8fc67-392">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-392">You create and schedule your migration events.</span></span> <span data-ttu-id="8fc67-393">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="8fc67-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8fc67-394">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="8fc67-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="8fc67-395">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="8fc67-395">Considerations</span></span>

  - <span data-ttu-id="8fc67-396">Todas las migraciones están sujetas a las cuotas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="8fc67-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="8fc67-397">Consulte los [<span class="underline">Límites de software de SharePoint Online y OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="8fc67-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8fc67-398">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="8fc67-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="8fc67-399">FastTrack realiza la migración solo para las unidades activas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="8fc67-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8fc67-400">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="8fc67-400">Source environment details</span></span>

<span data-ttu-id="8fc67-401">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="8fc67-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8fc67-402">Recursos compartidos de archivos (recursos compartidos de archivos de SMB en dispositivos compatibles a partir de SMB 2.0).</span><span class="sxs-lookup"><span data-stu-id="8fc67-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8fc67-403">Un solo entorno de G Suite (solo Google Drive)</span><span class="sxs-lookup"><span data-stu-id="8fc67-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8fc67-404">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="8fc67-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8fc67-405">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="8fc67-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8fc67-406">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="8fc67-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="8fc67-407"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="8fc67-408"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="8fc67-409"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8fc67-410"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8fc67-411"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8fc67-412">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="8fc67-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-413">Documentos</span><span class="sxs-lookup"><span data-stu-id="8fc67-413">Documents</span></span> </li>
<li> <span data-ttu-id="8fc67-414">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8fc67-415">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="8fc67-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8fc67-416">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="8fc67-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8fc67-417">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="8fc67-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8fc67-418">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="8fc67-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8fc67-419">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="8fc67-419">Created date</span></span> </li>
<li> <span data-ttu-id="8fc67-420">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-420">Modified date</span></span> </li>
<li> <span data-ttu-id="8fc67-421">Creada por</span><span class="sxs-lookup"><span data-stu-id="8fc67-421">Created by</span></span> </li>
<li> <span data-ttu-id="8fc67-422">Última modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="8fc67-423">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="8fc67-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8fc67-424">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="8fc67-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8fc67-425">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8fc67-426">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="8fc67-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="8fc67-427">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="8fc67-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8fc67-428">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="8fc67-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8fc67-429">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="8fc67-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="8fc67-430">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="8fc67-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8fc67-431">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="8fc67-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8fc67-432">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="8fc67-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8fc67-433">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="8fc67-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8fc67-434">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="8fc67-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8fc67-435">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8fc67-436">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="8fc67-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8fc67-437">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="8fc67-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8fc67-438">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8fc67-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8fc67-439"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8fc67-440">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="8fc67-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-441">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office, incluidos los de más de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="8fc67-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="8fc67-442">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8fc67-443">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-444">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-445">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="8fc67-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8fc67-446">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="8fc67-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8fc67-447">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="8fc67-447">Created date</span></span> </li>
<li> <span data-ttu-id="8fc67-448">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-448">Modified date</span></span> </li>
<li> <span data-ttu-id="8fc67-449">Creada por</span><span class="sxs-lookup"><span data-stu-id="8fc67-449">Created by</span></span> </li>
<li> <span data-ttu-id="8fc67-450">Última modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8fc67-451">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="8fc67-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8fc67-452">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="8fc67-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8fc67-453">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="8fc67-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8fc67-454">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8fc67-455">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-456">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-457">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="8fc67-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8fc67-458">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8fc67-459">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="8fc67-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8fc67-460">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="8fc67-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="8fc67-461">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8fc67-462">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8fc67-463">Formularios de Google Photos, Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="8fc67-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8fc67-464">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="8fc67-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8fc67-465">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="8fc67-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8fc67-466">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="8fc67-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8fc67-467">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8fc67-468">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="8fc67-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8fc67-469">Permisos de suscripción de la unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="8fc67-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8fc67-470">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="8fc67-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8fc67-471">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8fc67-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8fc67-472"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8fc67-473">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="8fc67-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-474">Documentos</span><span class="sxs-lookup"><span data-stu-id="8fc67-474">Documents</span></span> </li>
<li> <span data-ttu-id="8fc67-475">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8fc67-476">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-477">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-478">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="8fc67-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8fc67-479">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="8fc67-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8fc67-480">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="8fc67-480">Created date</span></span> </li>
<li> <span data-ttu-id="8fc67-481">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-481">Modified date</span></span> </li>
<li> <span data-ttu-id="8fc67-482">Creada por</span><span class="sxs-lookup"><span data-stu-id="8fc67-482">Created by</span></span> </li>
<li> <span data-ttu-id="8fc67-483">Última modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8fc67-484">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="8fc67-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8fc67-485">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="8fc67-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8fc67-486">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8fc67-487">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-488">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-489">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="8fc67-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8fc67-490">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8fc67-491">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="8fc67-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8fc67-492">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="8fc67-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="8fc67-493">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8fc67-494">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8fc67-495">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="8fc67-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8fc67-496">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="8fc67-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8fc67-497">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8fc67-498">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="8fc67-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8fc67-499">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8fc67-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8fc67-500"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="8fc67-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8fc67-501">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="8fc67-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8fc67-502">Documentos</span><span class="sxs-lookup"><span data-stu-id="8fc67-502">Documents</span></span> </li>
<li> <span data-ttu-id="8fc67-503">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8fc67-504">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-505">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-506">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="8fc67-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8fc67-507">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="8fc67-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8fc67-508">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="8fc67-508">Created date</span></span> </li>
<li> <span data-ttu-id="8fc67-509">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-509">Modified date</span></span> </li>
<li> <span data-ttu-id="8fc67-510">Creada por</span><span class="sxs-lookup"><span data-stu-id="8fc67-510">Created by</span></span> </li>
<li> <span data-ttu-id="8fc67-511">Última modificación</span><span class="sxs-lookup"><span data-stu-id="8fc67-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8fc67-512">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="8fc67-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8fc67-513">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="8fc67-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8fc67-514">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="8fc67-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8fc67-515">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="8fc67-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8fc67-516">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="8fc67-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-517">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="8fc67-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8fc67-518">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="8fc67-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8fc67-519">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="8fc67-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8fc67-520">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="8fc67-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8fc67-521">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="8fc67-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="8fc67-522">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="8fc67-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8fc67-523">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="8fc67-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8fc67-524">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="8fc67-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8fc67-525">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="8fc67-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8fc67-526">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="8fc67-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8fc67-527">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="8fc67-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8fc67-528">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="8fc67-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8fc67-529">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="8fc67-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8fc67-530">Archivos o carpetas que superen las <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">restricciones y limitaciones actuales de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8fc67-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8fc67-531">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="8fc67-531">FastTrack responsibilities</span></span>

<span data-ttu-id="8fc67-532">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8fc67-533">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="8fc67-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8fc67-534">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="8fc67-534">Your responsibilities</span></span>

<span data-ttu-id="8fc67-535">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8fc67-536">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="8fc67-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8fc67-537">También realizará las siguientes actividades, específicas para las migraciones de OneDrive para la Empresa:</span><span class="sxs-lookup"><span data-stu-id="8fc67-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="8fc67-538">Aprovisionamiento de todos los sitios de OneDrive para la Empresa que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="8fc67-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
