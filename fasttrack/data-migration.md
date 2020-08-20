---
title: Migración de datos
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa). El tipo de asistencia que proporcionamos depende del número de licencias de Office 365.
ms.openlocfilehash: 6b2c9cc3afba415c200b14fe34e65f1c3286e450
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817717"
---
# <a name="data-migration"></a><span data-ttu-id="12bd7-104">Migración de datos</span><span class="sxs-lookup"><span data-stu-id="12bd7-104">Data Migration</span></span>

<span data-ttu-id="12bd7-105">FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa).</span><span class="sxs-lookup"><span data-stu-id="12bd7-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="12bd7-106">El tipo de asistencia que proporcionamos depende del número de licencias de Office 365 que tenga:</span><span class="sxs-lookup"><span data-stu-id="12bd7-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="12bd7-107">**En el caso de cuentas empresariales de Office 365 con 150-499 licencias**: FastTrack solo proporciona instrucciones para la migración, usted es el responsable de realizar la migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="12bd7-108">Lo guiaremos a través de documentación que le ayudará a planear y a usar herramientas gratuitas para realizar una migración de autoservicio.</span><span class="sxs-lookup"><span data-stu-id="12bd7-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="12bd7-109">**En el caso de cuentas empresariales de Office 365 con más de 500 licencias**: FastTrack proporciona instrucciones para la migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="12bd7-110">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y su espacio empresarial de Office 365 y aprovechar nuestros servicios de migración de datos para migrar sus datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="12bd7-111">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-111">You create and schedule your migration events.</span></span> <span data-ttu-id="12bd7-112">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="12bd7-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="12bd7-113">Si compró o renovó un plan comercial antes del 1° de septiembre de 2017, solo necesita 150 licencias para calificar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="12bd7-114">En el caso de los planes educativos, solo las licencias pagas del profesorado y el personal pueden optar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="12bd7-115">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="12bd7-115">Considerations</span></span>

  - <span data-ttu-id="12bd7-116">Los entornos de origen deben cumplir expectativas específicas para poder migrar datos a Office 365.</span><span class="sxs-lookup"><span data-stu-id="12bd7-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="12bd7-117">Para obtener más información sobre las expectativas del entorno de origen de Exchange, SharePoint y OneDrive para la Empresa, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="12bd7-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="12bd7-118">Requerimos el acceso y los permisos adecuados de acceso a sus entornos de origen y a su cuenta empresarial de Office 365 para proporcionar los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="12bd7-119">Nuestros servicios de migración de datos no están diseñados ni tienen como objetivo fungir como datos de un sujeto interesado para cumplir con obligaciones jurídicas especiales o requisitos legales.</span><span class="sxs-lookup"><span data-stu-id="12bd7-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="12bd7-120">A medida que migramos los datos, se pueden transferir, almacenar y procesar en cualquier lugar en el que mantengamos instalaciones (a menos que se disponga de otro modo en el proyecto de migración de FastTrack).</span><span class="sxs-lookup"><span data-stu-id="12bd7-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="12bd7-121">Microsoft no puede garantizar la velocidad de la migración de archivos o correos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="12bd7-122">Hay problemas imprevistos (como elementos ilegibles o dañados en el entorno de origen) que podrían afectar nuestra capacidad para migrar algunos de los elementos de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="12bd7-123">Los factores externos más allá de nuestro control (como los cambios a las interfaces de programación de aplicaciones (API) de terceros) pueden ocasionar cambios, retrasos o la suspensión de nuestros servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="12bd7-124">Disponibilidad del servicio de migración</span><span class="sxs-lookup"><span data-stu-id="12bd7-124">Migration service availability</span></span>

  - <span data-ttu-id="12bd7-125">**Para clientes comerciales y gubernamentales del Reino Unido:** Proporcionamos servicios de migración de datos las 24 horas del día, los siete (7) días de la semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="12bd7-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="12bd7-126">**Para clientes gubernamentales/DOD de Estados Unidos:** Proporcionamos servicios de migración de datos las 24 horas del día, los cinco (5) días hábiles de la semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="12bd7-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="12bd7-127">Migración a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="12bd7-127">Migration to Exchange Online</span></span>

<span data-ttu-id="12bd7-128">Cuando elige usar FastTrack para migrar su correo electrónico a Exchange Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="12bd7-129">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de Exchange Online, y aprovechar nuestros servicios de migración de datos para migrar sus buzones.</span><span class="sxs-lookup"><span data-stu-id="12bd7-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="12bd7-130">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-130">You create and schedule your migration events.</span></span> <span data-ttu-id="12bd7-131">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="12bd7-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="12bd7-132">Cuando los eventos de migración se completen, encontrará que los correos provenientes de los buzones de origen que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="12bd7-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="12bd7-133">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="12bd7-133">Considerations</span></span>

  - <span data-ttu-id="12bd7-134">Antes de la migración, debe completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="12bd7-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="12bd7-135">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="12bd7-136">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="12bd7-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="12bd7-137">FastTrack solo migra a buzones de Office 365 que estén activos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="12bd7-138">Si tiene previsto migrar desde un entorno local de Exchange, debe cumplir los requisitos específicos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="12bd7-139">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="12bd7-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="12bd7-140">Todos los entornos de origen deben tener el Service Pack (SP) y la actualización acumulativa (RU)/paquete acumulativo de actualizaciones (CU) en el último nivel para el producto correspondiente en el entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="12bd7-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="12bd7-141">Las listas de distribución (objetos *MailEnabledGroup*) y los contactos externos (objetos *MailEnabledContact*) que existen en su Active Directory local no forman parte de la migración de datos del buzón.</span><span class="sxs-lookup"><span data-stu-id="12bd7-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="12bd7-142">Sin embargo, puede sincronizarlos usando Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="12bd7-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="12bd7-143">Entornos de origen</span><span class="sxs-lookup"><span data-stu-id="12bd7-143">Source environments</span></span>

<span data-ttu-id="12bd7-144">Nuestro servicio de migración de datos migra los datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="12bd7-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="12bd7-145">Uno o varios bosques de Active Directory con una o varias organizaciones de Exchange (cada sistema de correo de Exchange debe ser Exchange 2010 o superior).</span><span class="sxs-lookup"><span data-stu-id="12bd7-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="12bd7-146">Un solo entorno de correo electrónico compatible con IMAP.</span><span class="sxs-lookup"><span data-stu-id="12bd7-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="12bd7-147">Entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="12bd7-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="12bd7-148">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="12bd7-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="12bd7-149"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="12bd7-150"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="12bd7-151"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="12bd7-152"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="12bd7-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="12bd7-154">
<strong>Nota:</strong> Para conocer las dependencias de Exchange local, vea los  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Requisitos previos para la implementación híbrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="12bd7-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="12bd7-155">Migración con implementación híbrida</span><span class="sxs-lookup"><span data-stu-id="12bd7-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="12bd7-156">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="12bd7-156">Emails</span></span></li>
<li><span data-ttu-id="12bd7-157">Reglas de buzón</span><span class="sxs-lookup"><span data-stu-id="12bd7-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="12bd7-158">Delegados</span><span class="sxs-lookup"><span data-stu-id="12bd7-158">Delegates</span></span></li>
<li><span data-ttu-id="12bd7-159">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="12bd7-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="12bd7-160">Calendario</span><span class="sxs-lookup"><span data-stu-id="12bd7-160">Calendar</span></span> </li>
<li> <span data-ttu-id="12bd7-161">Tareas</span><span class="sxs-lookup"><span data-stu-id="12bd7-161">Tasks</span></span> </li>
<li> <span data-ttu-id="12bd7-162">Correos electrónicos con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="12bd7-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="12bd7-163">Correos electrónicos cifrados</span><span class="sxs-lookup"><span data-stu-id="12bd7-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="12bd7-164">Firmas</span><span class="sxs-lookup"><span data-stu-id="12bd7-164">Signatures</span></span> </li>
<li> <span data-ttu-id="12bd7-165">Archivo personal migrado con el buzón del usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="12bd7-166">Elementos recuperables</span><span class="sxs-lookup"><span data-stu-id="12bd7-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="12bd7-167">Carpetas públicas</span><span class="sxs-lookup"><span data-stu-id="12bd7-167">Public folders</span></span> </li>
<li> <span data-ttu-id="12bd7-168">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="12bd7-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="12bd7-169">Archivo de registro en diario o cualquier solución de archivo de terceros</span><span class="sxs-lookup"><span data-stu-id="12bd7-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="12bd7-170">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="12bd7-171">Datos de archivo procedentes de archivos PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="12bd7-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="12bd7-172">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="12bd7-173">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="12bd7-174"><strong>Entorno de G Suite (solo Gmail, Contactos y Calendario)</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="12bd7-175">
<strong>Nota:</strong> Su entorno de G Suite debe cumplir los requisitos previos descritos en <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Realizar una migración de G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="12bd7-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="12bd7-176">Total o preconfigurada</span><span class="sxs-lookup"><span data-stu-id="12bd7-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-177">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="12bd7-177">Emails</span></span> </li>
<li> <span data-ttu-id="12bd7-178">Contactos del buzón (se migra un máximo de 3 direcciones de correo electrónico por contacto)</span><span class="sxs-lookup"><span data-stu-id="12bd7-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="12bd7-179">Calendar</span><span class="sxs-lookup"><span data-stu-id="12bd7-179">Calendar</span></span> </li>
<li> <span data-ttu-id="12bd7-180">Etiquetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="12bd7-181">Reglas</span><span class="sxs-lookup"><span data-stu-id="12bd7-181">Rules</span></span> </li>
<li> <span data-ttu-id="12bd7-182">Delegados</span><span class="sxs-lookup"><span data-stu-id="12bd7-182">Delegates</span></span> </li>
<li> <span data-ttu-id="12bd7-183">Firmas</span><span class="sxs-lookup"><span data-stu-id="12bd7-183">Signatures</span></span> </li>
<li> <span data-ttu-id="12bd7-184">Tareas</span><span class="sxs-lookup"><span data-stu-id="12bd7-184">Tasks</span></span> </li>
<li> <span data-ttu-id="12bd7-185">Cualquier correo electrónico o dato adjunto que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="12bd7-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="12bd7-186">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="12bd7-187">Datos de archivo procedentes de archivos PST o de soluciones de archivo de terceros (por ejemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="12bd7-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="12bd7-188">Mensajes de correo electrónico cifrados o con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="12bd7-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="12bd7-189">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="12bd7-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="12bd7-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="12bd7-191">Grupos de Google</span><span class="sxs-lookup"><span data-stu-id="12bd7-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="12bd7-192">Buzones de recursos</span><span class="sxs-lookup"><span data-stu-id="12bd7-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="12bd7-193">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="12bd7-194">Configuración de ausencia por vacaciones y respuesta automática</span><span class="sxs-lookup"><span data-stu-id="12bd7-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="12bd7-195">Calendarios compartidos, datos adjuntos en la nube, vínculos a Google Hangout y colores del evento</span><span class="sxs-lookup"><span data-stu-id="12bd7-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="12bd7-196">\*\*Se migran las conversaciones de Hangouts guardadas como etiqueta.</span><span class="sxs-lookup"><span data-stu-id="12bd7-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="12bd7-197"><strong>Origen de IMAP4 (como Domino, GroupWise o Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="12bd7-198">Migración con herramientas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="12bd7-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="12bd7-199">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="12bd7-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="12bd7-200">Reglas</span><span class="sxs-lookup"><span data-stu-id="12bd7-200">Rules</span></span> </li>
<li> <span data-ttu-id="12bd7-201">Delegados</span><span class="sxs-lookup"><span data-stu-id="12bd7-201">Delegates</span></span> </li>
<li> <span data-ttu-id="12bd7-202">Listas de distribución</span><span class="sxs-lookup"><span data-stu-id="12bd7-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="12bd7-203">Contactos externos</span><span class="sxs-lookup"><span data-stu-id="12bd7-203">External contacts</span></span> </li>
<li> <span data-ttu-id="12bd7-204">Usuarios habilitados para correo</span><span class="sxs-lookup"><span data-stu-id="12bd7-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="12bd7-205">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="12bd7-206">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="12bd7-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="12bd7-207">Calendario</span><span class="sxs-lookup"><span data-stu-id="12bd7-207">Calendar</span></span> </li>
<li> <span data-ttu-id="12bd7-208">Firmas</span><span class="sxs-lookup"><span data-stu-id="12bd7-208">Signatures</span></span> </li>
<li> <span data-ttu-id="12bd7-209">Tareas</span><span class="sxs-lookup"><span data-stu-id="12bd7-209">Tasks</span></span> </li>
<li> <span data-ttu-id="12bd7-210">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="12bd7-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="12bd7-211">Datos de archivo</span><span class="sxs-lookup"><span data-stu-id="12bd7-211">Archive data</span></span> </li>
<li> <span data-ttu-id="12bd7-212">Correo electrónico cifrado</span><span class="sxs-lookup"><span data-stu-id="12bd7-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="12bd7-213">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="12bd7-214">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="12bd7-215">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="12bd7-215">FastTrack responsibilities</span></span>

<span data-ttu-id="12bd7-216">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="12bd7-217">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="12bd7-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="12bd7-218">Nuestros especialistas de FastTrack también realizan las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="12bd7-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="12bd7-219">Ofrece instrucciones para ayudarle a habilitar la coexistencia de enrutamiento de correo SMTP entre los entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="12bd7-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="12bd7-220">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="12bd7-220">Your responsibilities</span></span>

<span data-ttu-id="12bd7-221">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="12bd7-222">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="12bd7-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="12bd7-223">También realizará las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="12bd7-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="12bd7-224">Completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="12bd7-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="12bd7-225">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="12bd7-226">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="12bd7-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="12bd7-227">Instalar el nivel adecuado del software del cliente según las instrucciones de Office 365.</span><span class="sxs-lookup"><span data-stu-id="12bd7-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="12bd7-228">Para obtener más información, consulte [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="12bd7-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="12bd7-229">Cumplir los requerimientos específicos si tiene previsto migrar desde un entorno local de Exchange.</span><span class="sxs-lookup"><span data-stu-id="12bd7-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="12bd7-230">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="12bd7-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="12bd7-231">Asegurarse de que cada entorno de origen tenga la versión más reciente del Service Pack (SP) y de la actualización cumulativa (RU)/paquete acumulativo de actualizaciones (CU), si procede.</span><span class="sxs-lookup"><span data-stu-id="12bd7-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="12bd7-232">Configurar y validar la coexistencia del enrutamiento de correo SMTP entre sus entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="12bd7-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="12bd7-233">Asegurarse de que el tamaño de su buzón de origen no supere la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="12bd7-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="12bd7-234">Dependiendo de la plataforma de origen, es posible que deba limitar los datos de origen a 85% de la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="12bd7-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="12bd7-235">Puede migrar los datos del lado del cliente, si lo desea.</span><span class="sxs-lookup"><span data-stu-id="12bd7-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="12bd7-236">Esto incluye, entre otras cosas, las libretas de direcciones locales, los datos de los archivos PST locales, las reglas de Outlook y la configuración local de Outlook.</span><span class="sxs-lookup"><span data-stu-id="12bd7-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="12bd7-237">Ayudar a los usuarios finales con la corrección de los problemas de migración del lado del cliente.</span><span class="sxs-lookup"><span data-stu-id="12bd7-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="12bd7-238">Migración a SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="12bd7-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="12bd7-239">Cuando elige usar FastTrack para migrar sus archivos a SharePoint Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="12bd7-240">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de SharePoint Online, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="12bd7-241">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-241">You create and schedule your migration events.</span></span> <span data-ttu-id="12bd7-242">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="12bd7-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="12bd7-243">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="12bd7-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="12bd7-244">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="12bd7-244">Considerations</span></span>

  - <span data-ttu-id="12bd7-245">Todas las migraciones están sujetas a las cuotas de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="12bd7-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="12bd7-246">Consulte los [<span class="underline">Límites de software de SharePoint Online y de OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="12bd7-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="12bd7-247">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="12bd7-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="12bd7-248">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="12bd7-248">Source environment details</span></span>

<span data-ttu-id="12bd7-249">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="12bd7-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="12bd7-250">Recursos compartidos de archivos (recursos compartidos de archivos de Bloqueo de mensajes del servidor (SMB) en dispositivos compatibles a partir de SMB 2.0 en adelante).</span><span class="sxs-lookup"><span data-stu-id="12bd7-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="12bd7-251">Un solo entorno de G Suite (solo Google Drive).</span><span class="sxs-lookup"><span data-stu-id="12bd7-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="12bd7-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="12bd7-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="12bd7-253">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="12bd7-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="12bd7-254">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="12bd7-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="12bd7-255"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="12bd7-256"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="12bd7-257"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="12bd7-258"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="12bd7-259"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="12bd7-260">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="12bd7-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-261">Documentos</span><span class="sxs-lookup"><span data-stu-id="12bd7-261">Documents</span></span> </li>
<li> <span data-ttu-id="12bd7-262">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="12bd7-263">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="12bd7-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="12bd7-264">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="12bd7-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="12bd7-265">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="12bd7-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="12bd7-266">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="12bd7-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="12bd7-267">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="12bd7-267">Created date</span></span> </li>
<li> <span data-ttu-id="12bd7-268">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-268">Modified date</span></span> </li>
<li> <span data-ttu-id="12bd7-269">Creada por</span><span class="sxs-lookup"><span data-stu-id="12bd7-269">Created by</span></span> </li>
<li> <span data-ttu-id="12bd7-270">Última modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="12bd7-271">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="12bd7-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="12bd7-272">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="12bd7-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="12bd7-273">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="12bd7-274">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="12bd7-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-275">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="12bd7-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="12bd7-276">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="12bd7-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="12bd7-277">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="12bd7-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="12bd7-278">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="12bd7-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="12bd7-279">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="12bd7-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="12bd7-280">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="12bd7-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="12bd7-281">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="12bd7-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="12bd7-282">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="12bd7-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="12bd7-283">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="12bd7-284">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="12bd7-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="12bd7-285">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="12bd7-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="12bd7-286">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="12bd7-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="12bd7-287"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="12bd7-288">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="12bd7-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-289">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office), incluidos los de más de 10 MB</span><span class="sxs-lookup"><span data-stu-id="12bd7-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="12bd7-290">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="12bd7-291">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-292">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-293">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="12bd7-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="12bd7-294">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="12bd7-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="12bd7-295">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="12bd7-295">Created date</span></span> </li>
<li> <span data-ttu-id="12bd7-296">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-296">Modified date</span></span> </li>
<li> <span data-ttu-id="12bd7-297">Creada por</span><span class="sxs-lookup"><span data-stu-id="12bd7-297">Created by</span></span> </li>
<li> <span data-ttu-id="12bd7-298">Última modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="12bd7-299">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="12bd7-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="12bd7-300">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="12bd7-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="12bd7-301">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="12bd7-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="12bd7-302">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="12bd7-303">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-304">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-305">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="12bd7-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="12bd7-306">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="12bd7-307">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="12bd7-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="12bd7-308">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="12bd7-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="12bd7-309">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="12bd7-310">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="12bd7-311">Google Fotos, Formularios de Google, Google Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="12bd7-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="12bd7-312">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="12bd7-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="12bd7-313">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="12bd7-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="12bd7-314">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="12bd7-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="12bd7-315">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="12bd7-316">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="12bd7-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="12bd7-317">Permisos de suscripción a una unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="12bd7-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="12bd7-318">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="12bd7-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="12bd7-319">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="12bd7-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="12bd7-320"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="12bd7-321">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="12bd7-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-322">Documentos</span><span class="sxs-lookup"><span data-stu-id="12bd7-322">Documents</span></span> </li>
<li> <span data-ttu-id="12bd7-323">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="12bd7-324">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-325">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-326">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="12bd7-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="12bd7-327">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="12bd7-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="12bd7-328">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="12bd7-328">Created date</span></span> </li>
<li> <span data-ttu-id="12bd7-329">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-329">Modified date</span></span> </li>
<li> <span data-ttu-id="12bd7-330">Creada por</span><span class="sxs-lookup"><span data-stu-id="12bd7-330">Created by</span></span> </li>
<li> <span data-ttu-id="12bd7-331">Última modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="12bd7-332">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="12bd7-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="12bd7-333">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="12bd7-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="12bd7-334">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="12bd7-335">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-336">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-337">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="12bd7-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="12bd7-338">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="12bd7-339">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="12bd7-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="12bd7-340">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="12bd7-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="12bd7-341">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="12bd7-342">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="12bd7-343">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="12bd7-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="12bd7-344">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="12bd7-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="12bd7-345">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="12bd7-346">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="12bd7-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="12bd7-347">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="12bd7-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="12bd7-348"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="12bd7-349">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="12bd7-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-350">Documentos</span><span class="sxs-lookup"><span data-stu-id="12bd7-350">Documents</span></span> </li>
<li> <span data-ttu-id="12bd7-351">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="12bd7-352">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-353">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-354">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="12bd7-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="12bd7-355">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="12bd7-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="12bd7-356">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="12bd7-356">Created date</span></span> </li>
<li> <span data-ttu-id="12bd7-357">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-357">Modified date</span></span> </li>
<li> <span data-ttu-id="12bd7-358">Creada por</span><span class="sxs-lookup"><span data-stu-id="12bd7-358">Created by</span></span> </li>
<li> <span data-ttu-id="12bd7-359">Última modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="12bd7-360">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="12bd7-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="12bd7-361">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="12bd7-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="12bd7-362">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="12bd7-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="12bd7-363">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="12bd7-364">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-365">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-366">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="12bd7-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="12bd7-367">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="12bd7-368">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="12bd7-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="12bd7-369">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="12bd7-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="12bd7-370">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="12bd7-371">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="12bd7-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="12bd7-372">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="12bd7-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="12bd7-373">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="12bd7-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="12bd7-374">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="12bd7-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="12bd7-375">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="12bd7-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="12bd7-376">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="12bd7-377">Informe a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración)</span><span class="sxs-lookup"><span data-stu-id="12bd7-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="12bd7-378">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="12bd7-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="12bd7-379">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="12bd7-379">FastTrack responsibilities</span></span>

<span data-ttu-id="12bd7-380">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="12bd7-381">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="12bd7-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="12bd7-382">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="12bd7-382">Your responsibilities</span></span>

<span data-ttu-id="12bd7-383">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="12bd7-384">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="12bd7-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="12bd7-385">Usted también realizará las siguientes actividades, específicas para las migraciones de SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="12bd7-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="12bd7-386">Aprovisionamiento de todos los sitios del grupo de SharePoint que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="12bd7-387">Migración a OneDrive para la Empresa</span><span class="sxs-lookup"><span data-stu-id="12bd7-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="12bd7-388">Cuando elige usar FastTrack para migrar sus archivos a OneDrive para la Empresa, proporcionamos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="12bd7-389">Le proporcionamos instrucciones para ayudarle a planear su migración, configurar sus entornos de origen y de OneDrive para la Empresa, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="12bd7-390">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-390">You create and schedule your migration events.</span></span> <span data-ttu-id="12bd7-391">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="12bd7-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="12bd7-392">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="12bd7-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="12bd7-393">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="12bd7-393">Considerations</span></span>

  - <span data-ttu-id="12bd7-394">Todas las migraciones están sujetas a las cuotas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="12bd7-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="12bd7-395">Consulte los [<span class="underline">Límites de software de SharePoint Online y OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="12bd7-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="12bd7-396">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="12bd7-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="12bd7-397">FastTrack realiza la migración solo para las unidades activas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="12bd7-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="12bd7-398">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="12bd7-398">Source environment details</span></span>

<span data-ttu-id="12bd7-399">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="12bd7-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="12bd7-400">Recursos compartidos de archivos (recursos compartidos de archivos de SMB en dispositivos compatibles a partir de SMB 2.0).</span><span class="sxs-lookup"><span data-stu-id="12bd7-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="12bd7-401">Un solo entorno de G Suite (solo Google Drive)</span><span class="sxs-lookup"><span data-stu-id="12bd7-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="12bd7-402">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="12bd7-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="12bd7-403">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="12bd7-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="12bd7-404">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="12bd7-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="12bd7-405"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="12bd7-406"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="12bd7-407"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="12bd7-408"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="12bd7-409"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="12bd7-410">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="12bd7-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-411">Documentos</span><span class="sxs-lookup"><span data-stu-id="12bd7-411">Documents</span></span> </li>
<li> <span data-ttu-id="12bd7-412">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="12bd7-413">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="12bd7-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="12bd7-414">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="12bd7-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="12bd7-415">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="12bd7-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="12bd7-416">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="12bd7-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="12bd7-417">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="12bd7-417">Created date</span></span> </li>
<li> <span data-ttu-id="12bd7-418">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-418">Modified date</span></span> </li>
<li> <span data-ttu-id="12bd7-419">Creada por</span><span class="sxs-lookup"><span data-stu-id="12bd7-419">Created by</span></span> </li>
<li> <span data-ttu-id="12bd7-420">Última modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="12bd7-421">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="12bd7-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="12bd7-422">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="12bd7-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="12bd7-423">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="12bd7-424">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="12bd7-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="12bd7-425">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="12bd7-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="12bd7-426">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="12bd7-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="12bd7-427">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="12bd7-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="12bd7-428">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="12bd7-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="12bd7-429">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="12bd7-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="12bd7-430">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="12bd7-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="12bd7-431">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="12bd7-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="12bd7-432">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="12bd7-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="12bd7-433">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="12bd7-434">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="12bd7-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="12bd7-435">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="12bd7-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="12bd7-436">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="12bd7-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="12bd7-437"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="12bd7-438">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="12bd7-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-439">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office, incluidos los de más de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="12bd7-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="12bd7-440">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="12bd7-441">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-442">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-443">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="12bd7-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="12bd7-444">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="12bd7-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="12bd7-445">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="12bd7-445">Created date</span></span> </li>
<li> <span data-ttu-id="12bd7-446">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-446">Modified date</span></span> </li>
<li> <span data-ttu-id="12bd7-447">Creada por</span><span class="sxs-lookup"><span data-stu-id="12bd7-447">Created by</span></span> </li>
<li> <span data-ttu-id="12bd7-448">Última modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="12bd7-449">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="12bd7-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="12bd7-450">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="12bd7-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="12bd7-451">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="12bd7-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="12bd7-452">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="12bd7-453">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-454">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-455">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="12bd7-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="12bd7-456">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="12bd7-457">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="12bd7-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="12bd7-458">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="12bd7-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="12bd7-459">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="12bd7-460">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="12bd7-461">Formularios de Google Photos, Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="12bd7-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="12bd7-462">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="12bd7-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="12bd7-463">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="12bd7-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="12bd7-464">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="12bd7-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="12bd7-465">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="12bd7-466">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="12bd7-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="12bd7-467">Permisos de suscripción de la unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="12bd7-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="12bd7-468">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="12bd7-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="12bd7-469">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="12bd7-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="12bd7-470"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="12bd7-471">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="12bd7-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-472">Documentos</span><span class="sxs-lookup"><span data-stu-id="12bd7-472">Documents</span></span> </li>
<li> <span data-ttu-id="12bd7-473">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="12bd7-474">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-475">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-476">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="12bd7-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="12bd7-477">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="12bd7-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="12bd7-478">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="12bd7-478">Created date</span></span> </li>
<li> <span data-ttu-id="12bd7-479">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-479">Modified date</span></span> </li>
<li> <span data-ttu-id="12bd7-480">Creada por</span><span class="sxs-lookup"><span data-stu-id="12bd7-480">Created by</span></span> </li>
<li> <span data-ttu-id="12bd7-481">Última modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="12bd7-482">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="12bd7-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="12bd7-483">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="12bd7-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="12bd7-484">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="12bd7-485">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-486">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-487">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="12bd7-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="12bd7-488">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="12bd7-489">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="12bd7-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="12bd7-490">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="12bd7-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="12bd7-491">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="12bd7-492">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="12bd7-493">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="12bd7-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="12bd7-494">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="12bd7-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="12bd7-495">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="12bd7-496">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="12bd7-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="12bd7-497">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="12bd7-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="12bd7-498"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="12bd7-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="12bd7-499">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="12bd7-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="12bd7-500">Documentos</span><span class="sxs-lookup"><span data-stu-id="12bd7-500">Documents</span></span> </li>
<li> <span data-ttu-id="12bd7-501">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="12bd7-502">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-503">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-504">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="12bd7-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="12bd7-505">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="12bd7-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="12bd7-506">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="12bd7-506">Created date</span></span> </li>
<li> <span data-ttu-id="12bd7-507">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-507">Modified date</span></span> </li>
<li> <span data-ttu-id="12bd7-508">Creada por</span><span class="sxs-lookup"><span data-stu-id="12bd7-508">Created by</span></span> </li>
<li> <span data-ttu-id="12bd7-509">Última modificación</span><span class="sxs-lookup"><span data-stu-id="12bd7-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="12bd7-510">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="12bd7-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="12bd7-511">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="12bd7-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="12bd7-512">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="12bd7-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="12bd7-513">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="12bd7-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="12bd7-514">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="12bd7-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-515">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="12bd7-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="12bd7-516">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="12bd7-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="12bd7-517">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="12bd7-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="12bd7-518">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="12bd7-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="12bd7-519">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="12bd7-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="12bd7-520">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="12bd7-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="12bd7-521">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="12bd7-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="12bd7-522">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="12bd7-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="12bd7-523">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="12bd7-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="12bd7-524">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="12bd7-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="12bd7-525">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="12bd7-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="12bd7-526">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="12bd7-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="12bd7-527">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="12bd7-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="12bd7-528">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="12bd7-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="12bd7-529">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="12bd7-529">FastTrack responsibilities</span></span>

<span data-ttu-id="12bd7-530">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="12bd7-531">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="12bd7-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="12bd7-532">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="12bd7-532">Your responsibilities</span></span>

<span data-ttu-id="12bd7-533">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="12bd7-534">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="12bd7-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="12bd7-535">También realizará las siguientes actividades, específicas para las migraciones de OneDrive para la Empresa:</span><span class="sxs-lookup"><span data-stu-id="12bd7-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="12bd7-536">Aprovisionamiento de todos los sitios de OneDrive para la Empresa que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="12bd7-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
