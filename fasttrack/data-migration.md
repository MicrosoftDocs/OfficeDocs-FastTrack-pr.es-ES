---
title: Migración de datos
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa). El tipo de asistencia que proporcionamos depende del número de licencias de Office 365.
ms.openlocfilehash: 07165233711d4d4931f8adac4809b56138078f5a
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/21/2021
ms.locfileid: "51927002"
---
# <a name="data-migration"></a><span data-ttu-id="2351b-104">Migración de datos</span><span class="sxs-lookup"><span data-stu-id="2351b-104">Data Migration</span></span>

<span data-ttu-id="2351b-105">FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa).</span><span class="sxs-lookup"><span data-stu-id="2351b-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="2351b-106">El tipo de asistencia que proporcionamos depende del número de licencias de Office 365 que tenga:</span><span class="sxs-lookup"><span data-stu-id="2351b-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="2351b-107">**En el caso de cuentas empresariales de Office 365 con 150-499 licencias**: FastTrack solo proporciona instrucciones para la migración, usted es el responsable de realizar la migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="2351b-108">Lo guiaremos a través de documentación que le ayudará a planear y a usar herramientas gratuitas para realizar una migración de autoservicio.</span><span class="sxs-lookup"><span data-stu-id="2351b-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="2351b-109">**En el caso de cuentas empresariales de Office 365 con más de 500 licencias**: FastTrack proporciona instrucciones para la migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="2351b-110">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y su espacio empresarial de Office 365 y aprovechar nuestros servicios de migración de datos para migrar sus datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="2351b-111">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-111">You create and schedule your migration events.</span></span> <span data-ttu-id="2351b-112">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="2351b-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="2351b-113">Si compró o renovó un plan comercial antes del 1° de septiembre de 2017, solo necesita 150 licencias para calificar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="2351b-114">En el caso de los planes educativos, solo las licencias pagas del profesorado y el personal pueden optar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="2351b-115">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="2351b-115">Considerations</span></span>

  - <span data-ttu-id="2351b-116">Los entornos de origen deben cumplir expectativas específicas para poder migrar datos a Office 365.</span><span class="sxs-lookup"><span data-stu-id="2351b-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="2351b-117">Para obtener más información sobre las expectativas del entorno de origen de Exchange, SharePoint y OneDrive para la Empresa, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="2351b-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="2351b-118">Requerimos el acceso y los permisos adecuados de acceso a sus entornos de origen y a su cuenta empresarial de Office 365 para proporcionar los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="2351b-119">Nuestros servicios de migración de datos no están diseñados ni tienen como objetivo fungir como datos de un sujeto interesado para cumplir con obligaciones jurídicas especiales o requisitos legales.</span><span class="sxs-lookup"><span data-stu-id="2351b-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="2351b-120">A medida que migramos los datos, se pueden transferir, almacenar y procesar en cualquier lugar en el que mantengamos instalaciones (a menos que se disponga de otro modo en el proyecto de migración de FastTrack).</span><span class="sxs-lookup"><span data-stu-id="2351b-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="2351b-121">Microsoft no puede garantizar la velocidad de la migración de archivos o correos.</span><span class="sxs-lookup"><span data-stu-id="2351b-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="2351b-122">Hay problemas imprevistos (como elementos ilegibles o dañados en el entorno de origen) que podrían afectar nuestra capacidad para migrar algunos de los elementos de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="2351b-123">Los factores externos más allá de nuestro control (como los cambios a las interfaces de programación de aplicaciones (API) de terceros) pueden ocasionar cambios, retrasos o la suspensión de nuestros servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="2351b-124">Disponibilidad del servicio de migración</span><span class="sxs-lookup"><span data-stu-id="2351b-124">Migration service availability</span></span>

  - <span data-ttu-id="2351b-125">**Para clientes comerciales y gubernamentales del Reino Unido:** Proporcionamos servicios de migración de datos las 24 horas del día, los siete (7) días de la semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="2351b-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="2351b-126">**Para clientes gubernamentales/DOD de Estados Unidos:** Proporcionamos servicios de migración de datos las 24 horas del día, los cinco (5) días hábiles de la semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="2351b-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="2351b-127">Migración a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="2351b-127">Migration to Exchange Online</span></span>

<span data-ttu-id="2351b-128">Cuando elige usar FastTrack para migrar su correo electrónico a Exchange Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2351b-129">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de Exchange Online, y aprovechar nuestros servicios de migración de datos para migrar sus buzones.</span><span class="sxs-lookup"><span data-stu-id="2351b-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="2351b-130">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-130">You create and schedule your migration events.</span></span> <span data-ttu-id="2351b-131">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="2351b-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2351b-132">Cuando los eventos de migración se completen, encontrará que los correos provenientes de los buzones de origen que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2351b-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="2351b-133">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="2351b-133">Considerations</span></span>

  - <span data-ttu-id="2351b-134">Antes de la migración, debe completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2351b-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="2351b-135">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="2351b-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="2351b-136">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="2351b-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="2351b-137">FastTrack solo migra a buzones de Office 365 que estén activos.</span><span class="sxs-lookup"><span data-stu-id="2351b-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="2351b-138">Si tiene previsto migrar desde un entorno local de Exchange, debe cumplir los requisitos específicos.</span><span class="sxs-lookup"><span data-stu-id="2351b-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="2351b-139">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="2351b-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="2351b-140">Todos los entornos de origen deben tener el Service Pack (SP) y la actualización acumulativa (RU)/paquete acumulativo de actualizaciones (CU) en el último nivel para el producto correspondiente en el entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="2351b-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="2351b-141">Las listas de distribución (objetos *MailEnabledGroup*) y los contactos externos (objetos *MailEnabledContact*) que existen en su Active Directory local no forman parte de la migración de datos del buzón.</span><span class="sxs-lookup"><span data-stu-id="2351b-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="2351b-142">Sin embargo, puede sincronizarlos usando Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="2351b-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="2351b-143">Entornos de origen</span><span class="sxs-lookup"><span data-stu-id="2351b-143">Source environments</span></span>

<span data-ttu-id="2351b-144">Nuestro servicio de migración de datos migra los datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="2351b-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="2351b-145">Uno o varios bosques de Active Directory con una o varias organizaciones de Exchange (cada sistema de correo de Exchange debe ser Exchange 2010 o superior).</span><span class="sxs-lookup"><span data-stu-id="2351b-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="2351b-146">Un solo entorno de correo electrónico compatible con IMAP.</span><span class="sxs-lookup"><span data-stu-id="2351b-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="2351b-147">Entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="2351b-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="2351b-148">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="2351b-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2351b-149"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="2351b-150"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="2351b-151"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="2351b-152"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2351b-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="2351b-154">
<strong>Nota:</strong> Para las dependencias locales de Exchange, vea <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Requisitos previos de implementación híbrida.</span></a></span><span class="sxs-lookup"><span data-stu-id="2351b-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="2351b-155">Migración con implementación híbrida</span><span class="sxs-lookup"><span data-stu-id="2351b-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="2351b-156">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="2351b-156">Emails</span></span></li>
<li><span data-ttu-id="2351b-157">Reglas de buzón del lado servidor</span><span class="sxs-lookup"><span data-stu-id="2351b-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="2351b-158">Delegados</span><span class="sxs-lookup"><span data-stu-id="2351b-158">Delegates</span></span></li>
<li><span data-ttu-id="2351b-159">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="2351b-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="2351b-160">Calendario</span><span class="sxs-lookup"><span data-stu-id="2351b-160">Calendar</span></span> </li>
<li> <span data-ttu-id="2351b-161">Tareas</span><span class="sxs-lookup"><span data-stu-id="2351b-161">Tasks</span></span> </li>
<li> <span data-ttu-id="2351b-162">Correos electrónicos con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="2351b-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="2351b-163">Correos electrónicos cifrados</span><span class="sxs-lookup"><span data-stu-id="2351b-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="2351b-164">Firmas</span><span class="sxs-lookup"><span data-stu-id="2351b-164">Signatures</span></span> </li>
<li> <span data-ttu-id="2351b-165">Archivo personal migrado con el buzón del usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="2351b-166">Elementos recuperables</span><span class="sxs-lookup"><span data-stu-id="2351b-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2351b-167">Carpetas públicas</span><span class="sxs-lookup"><span data-stu-id="2351b-167">Public folders</span></span> </li>
<li> <span data-ttu-id="2351b-168">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="2351b-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2351b-169">Archivo de registro en diario o cualquier solución de archivo de terceros</span><span class="sxs-lookup"><span data-stu-id="2351b-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="2351b-170">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-171">Datos de archivo procedentes de archivos PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="2351b-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="2351b-172">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2351b-173">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="2351b-174">Reglas de buzón del lado cliente</span><span class="sxs-lookup"><span data-stu-id="2351b-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2351b-175"><strong>Entorno de G Suite (solo Gmail, Contactos y Calendario)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="2351b-176">
<strong>Nota:</strong> El entorno de G Suite debe cumplir los requisitos previos descritos en <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Realizar una migración de G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="2351b-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="2351b-177">Total o preconfigurada</span><span class="sxs-lookup"><span data-stu-id="2351b-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-178">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="2351b-178">Emails</span></span> </li>
<li> <span data-ttu-id="2351b-179">Contactos del buzón (se migra un máximo de 3 direcciones de correo electrónico por contacto)</span><span class="sxs-lookup"><span data-stu-id="2351b-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="2351b-180">Calendar</span><span class="sxs-lookup"><span data-stu-id="2351b-180">Calendar</span></span> </li>
<li> <span data-ttu-id="2351b-181">Etiquetas</span><span class="sxs-lookup"><span data-stu-id="2351b-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2351b-182">Reglas</span><span class="sxs-lookup"><span data-stu-id="2351b-182">Rules</span></span> </li>
<li> <span data-ttu-id="2351b-183">Delegados</span><span class="sxs-lookup"><span data-stu-id="2351b-183">Delegates</span></span> </li>
<li> <span data-ttu-id="2351b-184">Firmas</span><span class="sxs-lookup"><span data-stu-id="2351b-184">Signatures</span></span> </li>
<li> <span data-ttu-id="2351b-185">Tareas</span><span class="sxs-lookup"><span data-stu-id="2351b-185">Tasks</span></span> </li>
<li> <span data-ttu-id="2351b-186">Cualquier correo electrónico o dato adjunto que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="2351b-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2351b-187">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-188">Datos de archivo procedentes de archivos PST o de soluciones de archivo de terceros (por ejemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="2351b-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="2351b-189">Mensajes de correo electrónico cifrados o con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="2351b-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="2351b-190">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2351b-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="2351b-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="2351b-192">Grupos de Google</span><span class="sxs-lookup"><span data-stu-id="2351b-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="2351b-193">Buzones de recursos</span><span class="sxs-lookup"><span data-stu-id="2351b-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="2351b-194">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="2351b-195">Configuración de ausencia por vacaciones y respuesta automática</span><span class="sxs-lookup"><span data-stu-id="2351b-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="2351b-196">Calendarios compartidos, datos adjuntos en la nube, vínculos a Google Hangout y colores del evento</span><span class="sxs-lookup"><span data-stu-id="2351b-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="2351b-197">\*\*Se migran las conversaciones de Hangouts guardadas como etiqueta.</span><span class="sxs-lookup"><span data-stu-id="2351b-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2351b-198"><strong>Origen de IMAP4 (como Domino, GroupWise o Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="2351b-199">Migración con herramientas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="2351b-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="2351b-200">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="2351b-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="2351b-201">Reglas</span><span class="sxs-lookup"><span data-stu-id="2351b-201">Rules</span></span> </li>
<li> <span data-ttu-id="2351b-202">Delegados</span><span class="sxs-lookup"><span data-stu-id="2351b-202">Delegates</span></span> </li>
<li> <span data-ttu-id="2351b-203">Listas de distribución</span><span class="sxs-lookup"><span data-stu-id="2351b-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="2351b-204">Contactos externos</span><span class="sxs-lookup"><span data-stu-id="2351b-204">External contacts</span></span> </li>
<li> <span data-ttu-id="2351b-205">Usuarios habilitados para correo</span><span class="sxs-lookup"><span data-stu-id="2351b-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="2351b-206">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-207">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="2351b-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="2351b-208">Calendario</span><span class="sxs-lookup"><span data-stu-id="2351b-208">Calendar</span></span> </li>
<li> <span data-ttu-id="2351b-209">Firmas</span><span class="sxs-lookup"><span data-stu-id="2351b-209">Signatures</span></span> </li>
<li> <span data-ttu-id="2351b-210">Tareas</span><span class="sxs-lookup"><span data-stu-id="2351b-210">Tasks</span></span> </li>
<li> <span data-ttu-id="2351b-211">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="2351b-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2351b-212">Datos de archivo</span><span class="sxs-lookup"><span data-stu-id="2351b-212">Archive data</span></span> </li>
<li> <span data-ttu-id="2351b-213">Correo electrónico cifrado</span><span class="sxs-lookup"><span data-stu-id="2351b-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="2351b-214">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2351b-215">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2351b-216">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="2351b-216">FastTrack responsibilities</span></span>

<span data-ttu-id="2351b-217">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2351b-218">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="2351b-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2351b-219">Nuestros especialistas de FastTrack también realizan las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="2351b-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="2351b-220">Ofrece instrucciones para ayudarle a habilitar la coexistencia de enrutamiento de correo SMTP entre los entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="2351b-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2351b-221">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="2351b-221">Your responsibilities</span></span>

<span data-ttu-id="2351b-222">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2351b-223">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="2351b-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2351b-224">También realizará las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="2351b-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="2351b-225">Completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2351b-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="2351b-226">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="2351b-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="2351b-227">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="2351b-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="2351b-228">Instalar el nivel adecuado del software del cliente según las instrucciones de Office 365.</span><span class="sxs-lookup"><span data-stu-id="2351b-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="2351b-229">Para obtener más información, consulte [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="2351b-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="2351b-230">Cumplir los requerimientos específicos si tiene previsto migrar desde un entorno local de Exchange.</span><span class="sxs-lookup"><span data-stu-id="2351b-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="2351b-231">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="2351b-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="2351b-232">Asegurarse de que cada entorno de origen tenga la versión más reciente del Service Pack (SP) y de la actualización cumulativa (RU)/paquete acumulativo de actualizaciones (CU), si procede.</span><span class="sxs-lookup"><span data-stu-id="2351b-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="2351b-233">Configurar y validar la coexistencia del enrutamiento de correo SMTP entre sus entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="2351b-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="2351b-234">Asegurarse de que el tamaño de su buzón de origen no supere la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="2351b-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="2351b-235">Dependiendo de la plataforma de origen, es posible que deba limitar los datos de origen a 85% de la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="2351b-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="2351b-236">Puede migrar los datos del lado del cliente, si lo desea.</span><span class="sxs-lookup"><span data-stu-id="2351b-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="2351b-237">Esto incluye, entre otras cosas, las libretas de direcciones locales, los datos de los archivos PST locales, las reglas de Outlook y la configuración local de Outlook.</span><span class="sxs-lookup"><span data-stu-id="2351b-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="2351b-238">Ayudar a los usuarios finales con la corrección de los problemas de migración del lado del cliente.</span><span class="sxs-lookup"><span data-stu-id="2351b-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="2351b-239">Migración a SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="2351b-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="2351b-240">Cuando elige usar FastTrack para migrar sus archivos a SharePoint Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2351b-241">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de SharePoint Online, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="2351b-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="2351b-242">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-242">You create and schedule your migration events.</span></span> <span data-ttu-id="2351b-243">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="2351b-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2351b-244">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2351b-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="2351b-245">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="2351b-245">Considerations</span></span>

 - <span data-ttu-id="2351b-246">Todas las migraciones están sujetas a las cuotas de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2351b-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="2351b-247">Para obtener más información, consulte <a href="https://go.microsoft.com/fwlink/?LinkId=698855">Límites de SharePoint.</a></span><span class="sxs-lookup"><span data-stu-id="2351b-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="2351b-248">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="2351b-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="2351b-249">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="2351b-249">Source environment details</span></span>

<span data-ttu-id="2351b-250">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="2351b-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="2351b-251">Recursos compartidos de archivos (recursos compartidos de archivos de Bloqueo de mensajes del servidor (SMB) en dispositivos compatibles a partir de SMB 2.0 en adelante).</span><span class="sxs-lookup"><span data-stu-id="2351b-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="2351b-252">Un solo entorno de G Suite (solo Google Drive).</span><span class="sxs-lookup"><span data-stu-id="2351b-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="2351b-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="2351b-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="2351b-254">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="2351b-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="2351b-255">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="2351b-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2351b-256"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="2351b-257"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="2351b-258"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="2351b-259"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2351b-260"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="2351b-261">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-262">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-262">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-263">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-264">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="2351b-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-265">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="2351b-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-266">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-267">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-268">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-268">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-269">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-269">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-270">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-270">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-271">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="2351b-272">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="2351b-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="2351b-273">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="2351b-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="2351b-274">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="2351b-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="2351b-275">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="2351b-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-276">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="2351b-277">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-278">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="2351b-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="2351b-279">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="2351b-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="2351b-280">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="2351b-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="2351b-281">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="2351b-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="2351b-282">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="2351b-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="2351b-283">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="2351b-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="2351b-284">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-285">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="2351b-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="2351b-286">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="2351b-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="2351b-287">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2351b-288"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="2351b-289">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-290">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office), incluidos los de más de 10 MB</span><span class="sxs-lookup"><span data-stu-id="2351b-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="2351b-291">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-292">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-293">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-294">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-295">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-296">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-296">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-297">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-297">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-298">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-298">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-299">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-300">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="2351b-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="2351b-301">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="2351b-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2351b-302">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-303">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="2351b-304">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-305">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-306">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="2351b-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-307">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-308">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-309">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-310">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-311">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-312">Google Fotos, Formularios de Google, Google Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="2351b-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="2351b-313">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="2351b-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="2351b-314">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="2351b-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="2351b-315">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="2351b-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="2351b-316">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-317">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-318">Permisos de suscripción a una unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="2351b-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="2351b-319">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-320">Archivos marcados como restringidos o no copiables</span><span class="sxs-lookup"><span data-stu-id="2351b-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="2351b-321">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2351b-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="2351b-323">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-324">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-324">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-325">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-326">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-327">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-328">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-329">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-330">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-330">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-331">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-331">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-332">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-332">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-333">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-334">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="2351b-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="2351b-335">Notas del cuadro (convertida a formato de documento de Word)</span><span class="sxs-lookup"><span data-stu-id="2351b-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2351b-336">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-337">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2351b-338">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-339">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-340">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="2351b-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-341">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-342">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-343">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-344">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-345">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-346">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="2351b-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="2351b-347">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="2351b-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="2351b-348">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-349">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-350">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2351b-351"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="2351b-352">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-353">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-353">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-354">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-355">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-356">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-357">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-358">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-359">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-359">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-360">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-360">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-361">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-361">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-362">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-363">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="2351b-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="2351b-364">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="2351b-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2351b-365">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-366">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2351b-367">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-368">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-369">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="2351b-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-370">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-371">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-372">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-373">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-374">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="2351b-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="2351b-375">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="2351b-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="2351b-376">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="2351b-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="2351b-377">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="2351b-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="2351b-378">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="2351b-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="2351b-379">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-380">Informe a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración)</span><span class="sxs-lookup"><span data-stu-id="2351b-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="2351b-381">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2351b-382">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="2351b-382">FastTrack responsibilities</span></span>

<span data-ttu-id="2351b-383">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2351b-384">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="2351b-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2351b-385">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="2351b-385">Your responsibilities</span></span>

<span data-ttu-id="2351b-386">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2351b-387">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="2351b-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="2351b-388">Usted también realizará las siguientes actividades, específicas para las migraciones de SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="2351b-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="2351b-389">Aprovisionamiento de todos los sitios del grupo de SharePoint que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="2351b-390">Migración a OneDrive para la Empresa</span><span class="sxs-lookup"><span data-stu-id="2351b-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="2351b-391">Cuando elige usar FastTrack para migrar sus archivos a OneDrive para la Empresa, proporcionamos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2351b-392">Le proporcionamos instrucciones para ayudarle a planear su migración, configurar sus entornos de origen y de OneDrive para la Empresa, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="2351b-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="2351b-393">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-393">You create and schedule your migration events.</span></span> <span data-ttu-id="2351b-394">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="2351b-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2351b-395">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="2351b-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="2351b-396">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="2351b-396">Considerations</span></span>

  - <span data-ttu-id="2351b-397">Todas las migraciones están sujetas a las cuotas de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2351b-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="2351b-398">Para obtener más información, consulte <a href="https://go.microsoft.com/fwlink/?LinkId=698855">Límites de SharePoint.</a></span><span class="sxs-lookup"><span data-stu-id="2351b-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="2351b-399">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="2351b-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="2351b-400">FastTrack realiza la migración solo para las unidades activas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="2351b-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="2351b-401">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="2351b-401">Source environment details</span></span>

<span data-ttu-id="2351b-402">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="2351b-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="2351b-403">Recursos compartidos de archivos (recursos compartidos de archivos de SMB en dispositivos compatibles a partir de SMB 2.0).</span><span class="sxs-lookup"><span data-stu-id="2351b-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="2351b-404">Un solo entorno de G Suite (solo Google Drive)</span><span class="sxs-lookup"><span data-stu-id="2351b-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="2351b-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="2351b-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="2351b-406">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="2351b-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="2351b-407">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="2351b-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="2351b-408"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="2351b-409"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="2351b-410"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="2351b-411"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2351b-412"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="2351b-413">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-414">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-414">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-415">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-416">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="2351b-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-417">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="2351b-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-418">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-419">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-420">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-420">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-421">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-421">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-422">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-422">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-423">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="2351b-424">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="2351b-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="2351b-425">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="2351b-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="2351b-426">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="2351b-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="2351b-427">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="2351b-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="2351b-428">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="2351b-429">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-430">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="2351b-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="2351b-431">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="2351b-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="2351b-432">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="2351b-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="2351b-433">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="2351b-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="2351b-434">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="2351b-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="2351b-435">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="2351b-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="2351b-436">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-437">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="2351b-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="2351b-438">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="2351b-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="2351b-439">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2351b-440"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="2351b-441">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-442">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office, incluidos los de más de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="2351b-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="2351b-443">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-444">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-445">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-446">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-447">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-448">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-448">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-449">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-449">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-450">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-450">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-451">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-452">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="2351b-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="2351b-453">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="2351b-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2351b-454">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-455">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="2351b-456">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-457">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-458">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="2351b-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-459">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-460">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-461">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-462">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-463">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-464">Formularios de Google Photos, Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="2351b-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="2351b-465">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="2351b-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="2351b-466">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="2351b-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="2351b-467">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="2351b-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="2351b-468">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-469">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-470">Permisos de suscripción de la unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="2351b-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="2351b-471">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-472">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2351b-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="2351b-474">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-475">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-475">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-476">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-477">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-478">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-479">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-480">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-481">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-481">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-482">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-482">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-483">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-483">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-484">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-485">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="2351b-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2351b-486">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-487">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2351b-488">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-489">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-490">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="2351b-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-491">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-492">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-493">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-494">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-495">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-496">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="2351b-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="2351b-497">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="2351b-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="2351b-498">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-499">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-500">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2351b-501"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="2351b-502">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-503">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-503">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-504">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-505">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-506">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2351b-507">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-508">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-509">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-509">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-510">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-510">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-511">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-511">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-512">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-513">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="2351b-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="2351b-514">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="2351b-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2351b-515">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-516">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2351b-517">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-518">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-519">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="2351b-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-520">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-521">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-522">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-523">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-524">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="2351b-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="2351b-525">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="2351b-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="2351b-526">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="2351b-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="2351b-527">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="2351b-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="2351b-528">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="2351b-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="2351b-529">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-530">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-531">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2351b-532">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="2351b-532">FastTrack responsibilities</span></span>

<span data-ttu-id="2351b-533">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2351b-534">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="2351b-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2351b-535">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="2351b-535">Your responsibilities</span></span>

<span data-ttu-id="2351b-536">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2351b-537">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="2351b-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2351b-538">También realizará las siguientes actividades, específicas para las migraciones de OneDrive para la Empresa:</span><span class="sxs-lookup"><span data-stu-id="2351b-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="2351b-539">Aprovisionamiento de todos los sitios de OneDrive para la Empresa que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="2351b-540">Migración a Grupos de Microsoft Teams y Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="2351b-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="2351b-541">Cuando elige usar FastTrack para migrar los archivos a Grupos de Microsoft Teams y Microsoft 365, proporcionamos orientación sobre migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="2351b-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2351b-542">Proporcionamos instrucciones para ayudarle a planear la migración, configurar los entornos de origen y grupos de Teams y Microsoft 365 y aprovechar nuestros servicios de migración de datos para migrar los archivos.</span><span class="sxs-lookup"><span data-stu-id="2351b-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="2351b-543">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-543">You create and schedule your migration events.</span></span> <span data-ttu-id="2351b-544">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="2351b-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2351b-545">Cuando se completen los eventos de migración, puede esperar que los archivos de los orígenes programados y elegibles adecuados de los entornos de origen se hayan migrado a Teams y Grupos de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2351b-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="2351b-546">Los canales de Teams y los grupos de Microsoft 365 deben ser aprovisionados previamente por el cliente para poder migrar datos a estos tipos de destino.</span><span class="sxs-lookup"><span data-stu-id="2351b-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="2351b-547">Teams y Grupos de Microsoft 365 afectan a los permisos en la ubicación de destino del archivo.</span><span class="sxs-lookup"><span data-stu-id="2351b-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="2351b-548">Teams y grupos de Microsoft 365 están creados para permitir la colaboración.</span><span class="sxs-lookup"><span data-stu-id="2351b-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="2351b-549">El canal de Teams o el grupo de Microsoft 365 determinan quién tiene acceso a esos archivos al migrar a esos destinos.</span><span class="sxs-lookup"><span data-stu-id="2351b-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="2351b-550">FastTrack no agrega usuarios finales ni grupos a ningún canal de Teams o a grupos de Microsoft 365 durante la migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="2351b-551">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="2351b-551">Considerations</span></span>

- <span data-ttu-id="2351b-552">Todas las migraciones están sujetas a las cuotas de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2351b-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="2351b-553">Para obtener más información, consulte <a href="https://go.microsoft.com/fwlink/?LinkId=698855">Límites de SharePoint.</a></span><span class="sxs-lookup"><span data-stu-id="2351b-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="2351b-554">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="2351b-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="2351b-555">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="2351b-555">Source environment details</span></span>

<span data-ttu-id="2351b-556">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="2351b-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="2351b-557">Recursos compartidos de archivos (recursos compartidos de archivos de Bloqueo de mensajes del servidor (SMB) en dispositivos compatibles a partir de SMB 2.0 en adelante).</span><span class="sxs-lookup"><span data-stu-id="2351b-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="2351b-558">Un solo entorno de G Suite (solo Google Drive).</span><span class="sxs-lookup"><span data-stu-id="2351b-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="2351b-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="2351b-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="2351b-560">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="2351b-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="2351b-561">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="2351b-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="2351b-562"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="2351b-563"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="2351b-564"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="2351b-565"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2351b-566"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="2351b-567">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-568">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-568">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-569">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-570">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="2351b-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-571">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="2351b-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-572">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-573">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-574">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-574">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-575">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-575">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-576">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-576">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-577">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="2351b-578">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="2351b-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="2351b-579">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="2351b-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="2351b-580">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="2351b-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="2351b-581">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="2351b-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="2351b-582">Los permisos se verán afectados por el grupo de Microsoft 365 o el canal de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2351b-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="2351b-583">Si el destino es un grupo de Microsoft 365 o un canal de Microsoft Teams, el grupo o canal determina el perfil de permisos final en los archivos migrados.</span><span class="sxs-lookup"><span data-stu-id="2351b-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="2351b-584">Se recomienda no migrar permisos en archivos que migran a un canal de Microsoft 365 Group o Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2351b-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-585">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="2351b-586">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-587">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="2351b-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="2351b-588">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="2351b-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="2351b-589">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="2351b-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="2351b-590">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="2351b-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="2351b-591">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="2351b-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="2351b-592">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="2351b-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="2351b-593">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-594">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="2351b-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="2351b-595">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="2351b-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="2351b-596">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2351b-597"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="2351b-598">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-599">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office, incluidos los de más de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="2351b-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="2351b-600">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-601">Permisos de carpeta de nivel de usuario\*</span><span class="sxs-lookup"><span data-stu-id="2351b-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-602">Permisos de carpeta de nivel de grupo\*</span><span class="sxs-lookup"><span data-stu-id="2351b-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-603">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-604">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-605">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-605">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-606">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-606">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-607">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-607">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-608">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-609">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="2351b-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="2351b-610">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="2351b-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="2351b-611">\*Los permisos se verán afectados por el grupo de Microsoft 365 o el canal de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2351b-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="2351b-612">Si el destino es un grupo de Microsoft 365 o un canal de Microsoft Teams, el grupo o canal determina el perfil de permisos final en los archivos migrados.</span><span class="sxs-lookup"><span data-stu-id="2351b-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="2351b-613">Se recomienda no migrar permisos en archivos que migran a un canal de Microsoft 365 Group o Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2351b-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="2351b-614">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-615">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="2351b-616">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-617">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-618">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="2351b-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-619">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-620">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-621">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-622">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-623">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-624">Formularios de Google Photos, Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="2351b-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="2351b-625">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="2351b-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="2351b-626">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="2351b-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="2351b-627">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="2351b-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="2351b-628">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-629">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-630">Permisos de suscripción de la unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="2351b-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="2351b-631">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-632">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2351b-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="2351b-634">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-635">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-635">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-636">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-637">Permisos de carpeta de nivel de usuario\*</span><span class="sxs-lookup"><span data-stu-id="2351b-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-638">Permisos de carpeta de nivel de grupo\*</span><span class="sxs-lookup"><span data-stu-id="2351b-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-639">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-640">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-641">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-641">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-642">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-642">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-643">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-643">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-644">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-645">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="2351b-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="2351b-646">Notas del cuadro (convertida a formato de documento de Word)</span><span class="sxs-lookup"><span data-stu-id="2351b-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="2351b-647">\*Los permisos se verán afectados por el grupo de Microsoft 365 o el canal de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2351b-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="2351b-648">Si el destino es un grupo de Microsoft 365 o un canal de Microsoft Teams, el grupo o canal determina el perfil de permisos final en los archivos migrados.</span><span class="sxs-lookup"><span data-stu-id="2351b-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="2351b-649">Se recomienda no migrar permisos en archivos que migran a un canal de Microsoft 365 Group o Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2351b-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="2351b-650">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-651">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2351b-652">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-653">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-654">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="2351b-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-655">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-656">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-657">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-658">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-659">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="2351b-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2351b-660">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="2351b-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="2351b-661">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="2351b-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="2351b-662">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-663">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-664">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2351b-665"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="2351b-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="2351b-666">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="2351b-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2351b-667">Documentos</span><span class="sxs-lookup"><span data-stu-id="2351b-667">Documents</span></span> </li>
<li> <span data-ttu-id="2351b-668">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2351b-669">Permisos de carpeta de nivel de usuario\*</span><span class="sxs-lookup"><span data-stu-id="2351b-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-670">Permisos de carpeta de nivel de grupo\*</span><span class="sxs-lookup"><span data-stu-id="2351b-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2351b-671">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="2351b-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2351b-672">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="2351b-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2351b-673">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="2351b-673">Created date</span></span> </li>
<li> <span data-ttu-id="2351b-674">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-674">Modified date</span></span> </li>
<li> <span data-ttu-id="2351b-675">Creada por</span><span class="sxs-lookup"><span data-stu-id="2351b-675">Created by</span></span> </li>
<li> <span data-ttu-id="2351b-676">Última modificación</span><span class="sxs-lookup"><span data-stu-id="2351b-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2351b-677">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="2351b-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="2351b-678">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="2351b-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="2351b-679">\*Los permisos se verán afectados por el grupo de Microsoft 365 o el canal de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2351b-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="2351b-680">Si el destino es un grupo de Microsoft 365 o un canal de Microsoft Teams, el grupo o canal determina el perfil de permisos final en los archivos migrados.</span><span class="sxs-lookup"><span data-stu-id="2351b-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="2351b-681">Se recomienda no migrar permisos en archivos que migran a un canal de Microsoft 365 Group o Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="2351b-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="2351b-682">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="2351b-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2351b-683">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="2351b-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2351b-684">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="2351b-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-685">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="2351b-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2351b-686">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="2351b-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2351b-687">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="2351b-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2351b-688">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="2351b-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2351b-689">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="2351b-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="2351b-690">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="2351b-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2351b-691">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="2351b-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="2351b-692">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="2351b-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="2351b-693">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="2351b-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="2351b-694">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="2351b-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="2351b-695">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="2351b-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="2351b-696">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="2351b-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="2351b-697">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="2351b-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2351b-698">Archivos o carpetas que superan las restricciones y limitaciones actuales <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="2351b-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2351b-699">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="2351b-699">FastTrack responsibilities</span></span>

<span data-ttu-id="2351b-700">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2351b-701">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="2351b-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2351b-702">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="2351b-702">Your responsibilities</span></span> 

<span data-ttu-id="2351b-703">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2351b-704">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="2351b-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="2351b-705">También realiza las siguientes actividades, específicas de las migraciones de Microsoft Teams y Grupos de Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="2351b-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="2351b-706">Aprovisione todos los canales de Microsoft Teams y grupos de Microsoft 365 como destino de los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="2351b-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="2351b-707">FastTrack no aprovisiona previamente canales de Microsoft Teams ni grupos de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2351b-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="2351b-708">FastTrack no agrega usuarios o grupos finales a los canales de Microsoft Teams ni a los grupos de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2351b-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="2351b-709">Debe agregar los usuarios finales o grupos a todos los canales de Microsoft Teams y grupos de Microsoft 365 antes de migrar datos a esos destinos para que los usuarios finales tengan acceso a esos documentos recién migrados</span><span class="sxs-lookup"><span data-stu-id="2351b-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>