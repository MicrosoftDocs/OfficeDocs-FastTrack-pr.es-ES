---
title: Migración de datos
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa). El tipo de asistencia que proporcionamos depende del número de licencias de Office 365.
ms.openlocfilehash: fc7f07aea6104fdc6f06b3d624778919b351b34d
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 08/17/2020
ms.locfileid: "46777160"
---
# <a name="data-migration"></a><span data-ttu-id="70424-104">Migración de datos</span><span class="sxs-lookup"><span data-stu-id="70424-104">Data Migration</span></span>

<span data-ttu-id="70424-105">FastTrack puede ayudarle a migrar datos de correo y archivos en los entornos de origen a Office 365 (Exchange Online, SharePoint Online y OneDrive para la Empresa).</span><span class="sxs-lookup"><span data-stu-id="70424-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="70424-106">El tipo de asistencia que proporcionamos depende del número de licencias de Office 365 que tenga:</span><span class="sxs-lookup"><span data-stu-id="70424-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="70424-107">**En el caso de cuentas empresariales de Office 365 con 150-499 licencias**: FastTrack solo proporciona instrucciones para la migración, usted es el responsable de realizar la migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="70424-108">Lo guiaremos a través de documentación que le ayudará a planear y a usar herramientas gratuitas para realizar una migración de autoservicio.</span><span class="sxs-lookup"><span data-stu-id="70424-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="70424-109">**En el caso de cuentas empresariales de Office 365 con más de 500 licencias**: FastTrack proporciona instrucciones para la migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="70424-110">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y su espacio empresarial de Office 365 y aprovechar nuestros servicios de migración de datos para migrar sus datos.</span><span class="sxs-lookup"><span data-stu-id="70424-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="70424-111">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-111">You create and schedule your migration events.</span></span> <span data-ttu-id="70424-112">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="70424-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="70424-113">Si compró o renovó un plan comercial antes del 1° de septiembre de 2017, solo necesita 150 licencias para calificar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="70424-114">En el caso de los planes educativos, solo las licencias pagas del profesorado y el personal pueden optar para los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="70424-115">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="70424-115">Considerations</span></span>

  - <span data-ttu-id="70424-116">Los entornos de origen deben cumplir expectativas específicas para poder migrar datos a Office 365.</span><span class="sxs-lookup"><span data-stu-id="70424-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="70424-117">Para obtener más información sobre las expectativas del entorno de origen de Exchange, SharePoint y OneDrive para la Empresa, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="70424-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="70424-118">Requerimos el acceso y los permisos adecuados de acceso a sus entornos de origen y a su cuenta empresarial de Office 365 para proporcionar los servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="70424-119">Nuestros servicios de migración de datos no están diseñados ni tienen como objetivo fungir como datos de un sujeto interesado para cumplir con obligaciones jurídicas especiales o requisitos legales.</span><span class="sxs-lookup"><span data-stu-id="70424-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="70424-120">A medida que migramos los datos, se pueden transferir, almacenar y procesar en cualquier lugar en el que mantengamos instalaciones (a menos que se disponga de otro modo en el proyecto de migración de FastTrack).</span><span class="sxs-lookup"><span data-stu-id="70424-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="70424-121">Microsoft no puede garantizar la velocidad de la migración de archivos o correos.</span><span class="sxs-lookup"><span data-stu-id="70424-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="70424-122">Hay problemas imprevistos (como elementos ilegibles o dañados en el entorno de origen) que podrían afectar nuestra capacidad para migrar algunos de los elementos de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="70424-123">Los factores externos más allá de nuestro control (como los cambios a las interfaces de programación de aplicaciones (API) de terceros) pueden ocasionar cambios, retrasos o la suspensión de nuestros servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="70424-124">Disponibilidad del servicio de migración</span><span class="sxs-lookup"><span data-stu-id="70424-124">Migration service availability</span></span>

  - <span data-ttu-id="70424-125">**Para clientes comerciales y gubernamentales del Reino Unido:** Proporcionamos servicios de migración de datos las 24 horas del día, los siete (7) días de la semana (24x7).</span><span class="sxs-lookup"><span data-stu-id="70424-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="70424-126">**Para clientes gubernamentales/DOD de Estados Unidos:** Proporcionamos servicios de migración de datos las 24 horas del día, los cinco (5) días hábiles de la semana (24x5).</span><span class="sxs-lookup"><span data-stu-id="70424-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="70424-127">Migración a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="70424-127">Migration to Exchange Online</span></span>

<span data-ttu-id="70424-128">Cuando elige usar FastTrack para migrar su correo electrónico a Exchange Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="70424-129">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de Exchange Online, y aprovechar nuestros servicios de migración de datos para migrar sus buzones.</span><span class="sxs-lookup"><span data-stu-id="70424-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="70424-130">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-130">You create and schedule your migration events.</span></span> <span data-ttu-id="70424-131">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="70424-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="70424-132">Cuando los eventos de migración se completen, encontrará que los correos provenientes de los buzones de origen que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="70424-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="70424-133">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="70424-133">Considerations</span></span>

  - <span data-ttu-id="70424-134">Antes de la migración, debe completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="70424-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="70424-135">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="70424-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="70424-136">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="70424-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="70424-137">FastTrack solo migra a buzones de Office 365 que estén activos.</span><span class="sxs-lookup"><span data-stu-id="70424-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="70424-138">Si tiene previsto migrar desde un entorno local de Exchange, debe cumplir los requisitos específicos.</span><span class="sxs-lookup"><span data-stu-id="70424-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="70424-139">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="70424-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="70424-140">Todos los entornos de origen deben tener el Service Pack (SP) y la actualización acumulativa (RU)/paquete acumulativo de actualizaciones (CU) en el último nivel para el producto correspondiente en el entorno de origen.</span><span class="sxs-lookup"><span data-stu-id="70424-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="70424-141">Las listas de distribución (objetos *MailEnabledGroup*) y los contactos externos (objetos *MailEnabledContact*) que existen en su Active Directory local no forman parte de la migración de datos del buzón.</span><span class="sxs-lookup"><span data-stu-id="70424-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="70424-142">Sin embargo, puede sincronizarlos usando Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="70424-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="70424-143">Entornos de origen</span><span class="sxs-lookup"><span data-stu-id="70424-143">Source environments</span></span>

<span data-ttu-id="70424-144">Nuestro servicio de migración de datos migra los datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="70424-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="70424-145">Uno o varios bosques de Active Directory con una o varias organizaciones de Exchange (cada sistema de correo de Exchange debe ser Exchange 2010 o superior).</span><span class="sxs-lookup"><span data-stu-id="70424-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="70424-146">Un solo entorno de correo electrónico compatible con IMAP.</span><span class="sxs-lookup"><span data-stu-id="70424-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="70424-147">Entorno de G Suite (solo Gmail, Contactos y Calendario).</span><span class="sxs-lookup"><span data-stu-id="70424-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="70424-148">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="70424-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="70424-149"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="70424-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="70424-150"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="70424-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="70424-151"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="70424-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="70424-152"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="70424-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="70424-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="70424-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="70424-154">
<strong>Nota:</strong> Para conocer las dependencias de Exchange local, vea los  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Requisitos previos para la implementación híbrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="70424-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="70424-155">Migración con implementación híbrida</span><span class="sxs-lookup"><span data-stu-id="70424-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="70424-156">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="70424-156">Emails</span></span></li>
<li><span data-ttu-id="70424-157">Reglas de buzón</span><span class="sxs-lookup"><span data-stu-id="70424-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="70424-158">Delegados</span><span class="sxs-lookup"><span data-stu-id="70424-158">Delegates</span></span></li>
<li><span data-ttu-id="70424-159">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="70424-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="70424-160">Calendario</span><span class="sxs-lookup"><span data-stu-id="70424-160">Calendar</span></span> </li>
<li> <span data-ttu-id="70424-161">Tareas</span><span class="sxs-lookup"><span data-stu-id="70424-161">Tasks</span></span> </li>
<li> <span data-ttu-id="70424-162">Correos electrónicos con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="70424-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="70424-163">Correos electrónicos cifrados</span><span class="sxs-lookup"><span data-stu-id="70424-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="70424-164">Firmas</span><span class="sxs-lookup"><span data-stu-id="70424-164">Signatures</span></span> </li>
<li> <span data-ttu-id="70424-165">Archivo personal migrado con el buzón del usuario</span><span class="sxs-lookup"><span data-stu-id="70424-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="70424-166">Elementos recuperables</span><span class="sxs-lookup"><span data-stu-id="70424-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="70424-167">Carpetas públicas</span><span class="sxs-lookup"><span data-stu-id="70424-167">Public folders</span></span> </li>
<li> <span data-ttu-id="70424-168">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="70424-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="70424-169">Archivo de registro en diario o cualquier solución de archivo de terceros</span><span class="sxs-lookup"><span data-stu-id="70424-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="70424-170">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="70424-171">Datos de archivo procedentes de archivos PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="70424-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="70424-172">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="70424-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="70424-173">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="70424-174"><strong>Entorno de G Suite (solo Gmail, Contactos y Calendario)</strong></span><span class="sxs-lookup"><span data-stu-id="70424-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="70424-175">
<strong>Nota:</strong> Su entorno de G Suite debe cumplir los requisitos previos descritos en <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Realizar una migración de G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="70424-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="70424-176">Total o preconfigurada</span><span class="sxs-lookup"><span data-stu-id="70424-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-177">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="70424-177">Emails</span></span> </li>
<li> <span data-ttu-id="70424-178">Contactos del buzón (se migra un máximo de 3 direcciones de correo electrónico por contacto)</span><span class="sxs-lookup"><span data-stu-id="70424-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="70424-179">Calendar</span><span class="sxs-lookup"><span data-stu-id="70424-179">Calendar</span></span> </li>
<li> <span data-ttu-id="70424-180">Etiquetas</span><span class="sxs-lookup"><span data-stu-id="70424-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="70424-181">Reglas</span><span class="sxs-lookup"><span data-stu-id="70424-181">Rules</span></span> </li>
<li> <span data-ttu-id="70424-182">Delegados</span><span class="sxs-lookup"><span data-stu-id="70424-182">Delegates</span></span> </li>
<li> <span data-ttu-id="70424-183">Firmas</span><span class="sxs-lookup"><span data-stu-id="70424-183">Signatures</span></span> </li>
<li> <span data-ttu-id="70424-184">Tareas</span><span class="sxs-lookup"><span data-stu-id="70424-184">Tasks</span></span> </li>
<li> <span data-ttu-id="70424-185">Cualquier correo electrónico o dato adjunto que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="70424-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="70424-186">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="70424-187">Datos de archivo procedentes de archivos PST o de soluciones de archivo de terceros (por ejemplo, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="70424-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="70424-188">Mensajes de correo electrónico cifrados o con derechos administrados</span><span class="sxs-lookup"><span data-stu-id="70424-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="70424-189">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="70424-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="70424-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="70424-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="70424-191">Grupos de Google</span><span class="sxs-lookup"><span data-stu-id="70424-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="70424-192">Buzones de recursos</span><span class="sxs-lookup"><span data-stu-id="70424-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="70424-193">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="70424-194">Configuración de ausencia por vacaciones y respuesta automática</span><span class="sxs-lookup"><span data-stu-id="70424-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="70424-195">Calendarios compartidos, datos adjuntos en la nube, vínculos a Google Hangout y colores del evento</span><span class="sxs-lookup"><span data-stu-id="70424-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="70424-196">\*\*Se migran las conversaciones de Hangouts guardadas como etiqueta.</span><span class="sxs-lookup"><span data-stu-id="70424-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="70424-197"><strong>Origen de IMAP4 (como Domino, GroupWise o Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="70424-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="70424-198">Migración con herramientas nativas de IMAP4</span><span class="sxs-lookup"><span data-stu-id="70424-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="70424-199">Mensajes de correo electrónico</span><span class="sxs-lookup"><span data-stu-id="70424-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="70424-200">Reglas</span><span class="sxs-lookup"><span data-stu-id="70424-200">Rules</span></span> </li>
<li> <span data-ttu-id="70424-201">Delegados</span><span class="sxs-lookup"><span data-stu-id="70424-201">Delegates</span></span> </li>
<li> <span data-ttu-id="70424-202">Listas de distribución</span><span class="sxs-lookup"><span data-stu-id="70424-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="70424-203">Contactos externos</span><span class="sxs-lookup"><span data-stu-id="70424-203">External contacts</span></span> </li>
<li> <span data-ttu-id="70424-204">Usuarios habilitados para correo</span><span class="sxs-lookup"><span data-stu-id="70424-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="70424-205">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="70424-206">Contactos de buzón de correo</span><span class="sxs-lookup"><span data-stu-id="70424-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="70424-207">Calendario</span><span class="sxs-lookup"><span data-stu-id="70424-207">Calendar</span></span> </li>
<li> <span data-ttu-id="70424-208">Firmas</span><span class="sxs-lookup"><span data-stu-id="70424-208">Signatures</span></span> </li>
<li> <span data-ttu-id="70424-209">Tareas</span><span class="sxs-lookup"><span data-stu-id="70424-209">Tasks</span></span> </li>
<li> <span data-ttu-id="70424-210">Cualquier correo electrónico que supere el límite de tamaño de mensaje</span><span class="sxs-lookup"><span data-stu-id="70424-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="70424-211">Datos de archivo</span><span class="sxs-lookup"><span data-stu-id="70424-211">Archive data</span></span> </li>
<li> <span data-ttu-id="70424-212">Correo electrónico cifrado</span><span class="sxs-lookup"><span data-stu-id="70424-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="70424-213">Elementos dañados</span><span class="sxs-lookup"><span data-stu-id="70424-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="70424-214">Buzones de correo inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="70424-215">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="70424-215">FastTrack responsibilities</span></span>

<span data-ttu-id="70424-216">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="70424-217">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="70424-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="70424-218">Nuestros especialistas de FastTrack también realizan las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="70424-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="70424-219">Ofrece instrucciones para ayudarle a habilitar la coexistencia de enrutamiento de correo SMTP entre los entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="70424-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="70424-220">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="70424-220">Your responsibilities</span></span>

<span data-ttu-id="70424-221">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="70424-222">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="70424-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="70424-223">También realizará las siguientes actividades específicas para las migraciones de Exchange:</span><span class="sxs-lookup"><span data-stu-id="70424-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="70424-224">Completar la incorporación básica de FastTrack para Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="70424-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="70424-225">Si ya ha realizado la incorporación por su cuenta, debe pasar las comprobaciones necesarias y los requisitos previos.</span><span class="sxs-lookup"><span data-stu-id="70424-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="70424-226">Para obtener más información, consulte [Productos y funciones](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="70424-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="70424-227">Instalar el nivel adecuado del software del cliente según las instrucciones de Office 365.</span><span class="sxs-lookup"><span data-stu-id="70424-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="70424-228">Para obtener más información, consulte [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="70424-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="70424-229">Cumplir los requerimientos específicos si tiene previsto migrar desde un entorno local de Exchange.</span><span class="sxs-lookup"><span data-stu-id="70424-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="70424-230">Para obtener más información, consulte [Requisitos previos para la implementación híbrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="70424-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="70424-231">Asegurarse de que cada entorno de origen tenga la versión más reciente del Service Pack (SP) y de la actualización cumulativa (RU)/paquete acumulativo de actualizaciones (CU), si procede.</span><span class="sxs-lookup"><span data-stu-id="70424-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="70424-232">Configurar y validar la coexistencia del enrutamiento de correo SMTP entre sus entornos de origen y Exchange Online, si procede.</span><span class="sxs-lookup"><span data-stu-id="70424-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="70424-233">Asegurarse de que el tamaño de su buzón de origen no supere la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="70424-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="70424-234">Dependiendo de la plataforma de origen, es posible que deba limitar los datos de origen a 85% de la cuota del buzón de destino.</span><span class="sxs-lookup"><span data-stu-id="70424-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="70424-235">Puede migrar los datos del lado del cliente, si lo desea.</span><span class="sxs-lookup"><span data-stu-id="70424-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="70424-236">Esto incluye, entre otras cosas, las libretas de direcciones locales, los datos de los archivos PST locales, las reglas de Outlook y la configuración local de Outlook.</span><span class="sxs-lookup"><span data-stu-id="70424-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="70424-237">Ayudar a los usuarios finales con la corrección de los problemas de migración del lado del cliente.</span><span class="sxs-lookup"><span data-stu-id="70424-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="70424-238">Migración a SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="70424-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="70424-239">Cuando elige usar FastTrack para migrar sus archivos a SharePoint Online, ofrecemos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="70424-240">Le proporcionamos instrucciones para ayudarle a planear la migración, configurar sus entornos de origen y de SharePoint Online, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="70424-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="70424-241">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-241">You create and schedule your migration events.</span></span> <span data-ttu-id="70424-242">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="70424-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="70424-243">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="70424-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="70424-244">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="70424-244">Considerations</span></span>

  - <span data-ttu-id="70424-245">Todas las migraciones están sujetas a las cuotas de SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="70424-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="70424-246">Consulte los [<span class="underline">Límites de software de SharePoint Online y de OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="70424-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="70424-247">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="70424-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="70424-248">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="70424-248">Source environment details</span></span>

<span data-ttu-id="70424-249">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="70424-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="70424-250">Recursos compartidos de archivos (recursos compartidos de archivos de Bloqueo de mensajes del servidor (SMB) en dispositivos compatibles a partir de SMB 2.0 en adelante).</span><span class="sxs-lookup"><span data-stu-id="70424-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="70424-251">Un solo entorno de G Suite (solo Google Drive).</span><span class="sxs-lookup"><span data-stu-id="70424-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="70424-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="70424-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="70424-253">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="70424-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="70424-254">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="70424-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="70424-255"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="70424-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="70424-256"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="70424-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="70424-257"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="70424-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="70424-258"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="70424-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="70424-259"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="70424-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="70424-260">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="70424-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-261">Documentos</span><span class="sxs-lookup"><span data-stu-id="70424-261">Documents</span></span> </li>
<li> <span data-ttu-id="70424-262">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="70424-263">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="70424-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="70424-264">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="70424-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="70424-265">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="70424-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="70424-266">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="70424-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="70424-267">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="70424-267">Created date</span></span> </li>
<li> <span data-ttu-id="70424-268">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="70424-268">Modified date</span></span> </li>
<li> <span data-ttu-id="70424-269">Creada por</span><span class="sxs-lookup"><span data-stu-id="70424-269">Created by</span></span> </li>
<li> <span data-ttu-id="70424-270">Última modificación</span><span class="sxs-lookup"><span data-stu-id="70424-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="70424-271">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="70424-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="70424-272">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="70424-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="70424-273">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="70424-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="70424-274">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="70424-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-275">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="70424-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="70424-276">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="70424-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="70424-277">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="70424-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="70424-278">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="70424-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="70424-279">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="70424-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="70424-280">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="70424-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="70424-281">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="70424-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="70424-282">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="70424-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="70424-283">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="70424-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="70424-284">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="70424-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="70424-285">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="70424-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="70424-286">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="70424-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="70424-287"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="70424-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="70424-288">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="70424-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-289">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office), incluidos los de más de 10 MB</span><span class="sxs-lookup"><span data-stu-id="70424-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="70424-290">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="70424-291">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-292">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-293">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="70424-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="70424-294">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="70424-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="70424-295">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="70424-295">Created date</span></span> </li>
<li> <span data-ttu-id="70424-296">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="70424-296">Modified date</span></span> </li>
<li> <span data-ttu-id="70424-297">Creada por</span><span class="sxs-lookup"><span data-stu-id="70424-297">Created by</span></span> </li>
<li> <span data-ttu-id="70424-298">Última modificación</span><span class="sxs-lookup"><span data-stu-id="70424-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="70424-299">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="70424-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="70424-300">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="70424-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="70424-301">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="70424-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="70424-302">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="70424-303">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-304">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-305">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="70424-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="70424-306">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="70424-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="70424-307">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="70424-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="70424-308">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="70424-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="70424-309">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="70424-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="70424-310">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="70424-311">Google Fotos, Formularios de Google, Google Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="70424-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="70424-312">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="70424-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="70424-313">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="70424-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="70424-314">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="70424-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="70424-315">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="70424-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="70424-316">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="70424-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="70424-317">Permisos de suscripción a una unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="70424-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="70424-318">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="70424-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="70424-319">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="70424-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="70424-320"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="70424-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="70424-321">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="70424-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-322">Documentos</span><span class="sxs-lookup"><span data-stu-id="70424-322">Documents</span></span> </li>
<li> <span data-ttu-id="70424-323">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="70424-324">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-325">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-326">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="70424-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="70424-327">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="70424-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="70424-328">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="70424-328">Created date</span></span> </li>
<li> <span data-ttu-id="70424-329">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="70424-329">Modified date</span></span> </li>
<li> <span data-ttu-id="70424-330">Creada por</span><span class="sxs-lookup"><span data-stu-id="70424-330">Created by</span></span> </li>
<li> <span data-ttu-id="70424-331">Última modificación</span><span class="sxs-lookup"><span data-stu-id="70424-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="70424-332">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="70424-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="70424-333">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="70424-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="70424-334">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="70424-335">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-336">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-337">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="70424-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="70424-338">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="70424-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="70424-339">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="70424-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="70424-340">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="70424-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="70424-341">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="70424-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="70424-342">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="70424-343">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="70424-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="70424-344">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="70424-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="70424-345">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="70424-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="70424-346">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="70424-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="70424-347">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="70424-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="70424-348"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="70424-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="70424-349">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="70424-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-350">Documentos</span><span class="sxs-lookup"><span data-stu-id="70424-350">Documents</span></span> </li>
<li> <span data-ttu-id="70424-351">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="70424-352">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-353">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-354">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="70424-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="70424-355">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="70424-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="70424-356">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="70424-356">Created date</span></span> </li>
<li> <span data-ttu-id="70424-357">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="70424-357">Modified date</span></span> </li>
<li> <span data-ttu-id="70424-358">Creada por</span><span class="sxs-lookup"><span data-stu-id="70424-358">Created by</span></span> </li>
<li> <span data-ttu-id="70424-359">Última modificación</span><span class="sxs-lookup"><span data-stu-id="70424-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="70424-360">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="70424-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="70424-361">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="70424-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="70424-362">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="70424-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="70424-363">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="70424-364">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-365">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-366">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="70424-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="70424-367">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="70424-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="70424-368">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="70424-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="70424-369">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="70424-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="70424-370">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="70424-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="70424-371">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="70424-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="70424-372">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="70424-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="70424-373">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="70424-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="70424-374">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="70424-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="70424-375">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="70424-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="70424-376">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="70424-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="70424-377">Informe a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración)</span><span class="sxs-lookup"><span data-stu-id="70424-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="70424-378">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="70424-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="70424-379">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="70424-379">FastTrack responsibilities</span></span>

<span data-ttu-id="70424-380">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="70424-381">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="70424-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="70424-382">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="70424-382">Your responsibilities</span></span>

<span data-ttu-id="70424-383">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="70424-384">Consulte la información acerca de las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="70424-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="70424-385">Usted también realizará las siguientes actividades, específicas para las migraciones de SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="70424-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="70424-386">Aprovisionamiento de todos los sitios del grupo de SharePoint que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="70424-387">Migración a OneDrive para la Empresa</span><span class="sxs-lookup"><span data-stu-id="70424-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="70424-388">Cuando elige usar FastTrack para migrar sus archivos a OneDrive para la Empresa, proporcionamos instrucciones de migración y servicios de migración de datos.</span><span class="sxs-lookup"><span data-stu-id="70424-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="70424-389">Le proporcionamos instrucciones para ayudarle a planear su migración, configurar sus entornos de origen y de OneDrive para la Empresa, y aprovechar nuestros servicios de migración de datos para migrar sus archivos.</span><span class="sxs-lookup"><span data-stu-id="70424-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="70424-390">Cree y programe sus eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-390">You create and schedule your migration events.</span></span> <span data-ttu-id="70424-391">Iniciamos los eventos de migración de acuerdo con su programación, supervisamos el progreso y proporcionamos informes de estado.</span><span class="sxs-lookup"><span data-stu-id="70424-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="70424-392">Cuando los eventos de migración se completen, encontrará que los archivos provenientes de los orígenes que sean elegibles y que hayan sido apropiadamente programados fueron migrados de sus entornos de origen a OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="70424-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="70424-393">Consideraciones</span><span class="sxs-lookup"><span data-stu-id="70424-393">Considerations</span></span>

  - <span data-ttu-id="70424-394">Todas las migraciones están sujetas a las cuotas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="70424-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="70424-395">Consulte los [<span class="underline">Límites de software de SharePoint Online y OneDrive para la Empresa</span>](https://go.microsoft.com/fwlink/?LinkId=698855) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="70424-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="70424-396">Le recomendamos limitar la cantidad general de datos de migración a 75% de la cuota de almacenamiento general de SharePoint Online a la que tenga derecho (incluido el almacenamiento adicional que haya adquirido por separado).</span><span class="sxs-lookup"><span data-stu-id="70424-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="70424-397">FastTrack realiza la migración solo para las unidades activas de OneDrive para la Empresa.</span><span class="sxs-lookup"><span data-stu-id="70424-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="70424-398">Detalles del entorno de origen</span><span class="sxs-lookup"><span data-stu-id="70424-398">Source environment details</span></span>

<span data-ttu-id="70424-399">Nuestros servicios de migración de datos migran datos desde los siguientes entornos de origen:</span><span class="sxs-lookup"><span data-stu-id="70424-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="70424-400">Recursos compartidos de archivos (recursos compartidos de archivos de SMB en dispositivos compatibles a partir de SMB 2.0).</span><span class="sxs-lookup"><span data-stu-id="70424-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="70424-401">Un solo entorno de G Suite (solo Google Drive)</span><span class="sxs-lookup"><span data-stu-id="70424-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="70424-402">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="70424-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="70424-403">Dropbox para Equipos (estándar y avanzado).</span><span class="sxs-lookup"><span data-stu-id="70424-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="70424-404">En la siguiente tabla se muestran los detalles de la migración específicos para cada entorno de origen:</span><span class="sxs-lookup"><span data-stu-id="70424-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="70424-405"><strong>Entorno de origen</strong></span><span class="sxs-lookup"><span data-stu-id="70424-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="70424-406"><strong>Tipo de migración</strong></span><span class="sxs-lookup"><span data-stu-id="70424-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="70424-407"><strong>Qué se migra</strong></span><span class="sxs-lookup"><span data-stu-id="70424-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="70424-408"><strong>Qué no se migra</strong></span><span class="sxs-lookup"><span data-stu-id="70424-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="70424-409"><strong>Cualquier dispositivo de recurso compartido de archivos compatible con SMB 2.0 o versiones posteriores</strong></span><span class="sxs-lookup"><span data-stu-id="70424-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="70424-410">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="70424-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-411">Documentos</span><span class="sxs-lookup"><span data-stu-id="70424-411">Documents</span></span> </li>
<li> <span data-ttu-id="70424-412">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="70424-413">Permisos de archivos y carpetas del nivel del usuario\*</span><span class="sxs-lookup"><span data-stu-id="70424-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="70424-414">Permisos de archivos y carpetas del nivel del grupo\*</span><span class="sxs-lookup"><span data-stu-id="70424-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="70424-415">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="70424-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="70424-416">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="70424-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="70424-417">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="70424-417">Created date</span></span> </li>
<li> <span data-ttu-id="70424-418">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="70424-418">Modified date</span></span> </li>
<li> <span data-ttu-id="70424-419">Creada por</span><span class="sxs-lookup"><span data-stu-id="70424-419">Created by</span></span> </li>
<li> <span data-ttu-id="70424-420">Última modificación</span><span class="sxs-lookup"><span data-stu-id="70424-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="70424-421">\* Se requiere la configuración de sincronización de directorios.</span><span class="sxs-lookup"><span data-stu-id="70424-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="70424-422">Solo se migran permisos de NTFS expuestos en el Explorador de archivos de Windows.</span><span class="sxs-lookup"><span data-stu-id="70424-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="70424-423">No se migran los permisos administrados directamente en los dispositivos de recursos compartidos de archivos.</span><span class="sxs-lookup"><span data-stu-id="70424-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="70424-424">Si los datos se almacenan en un dispositivo SMB 2.0, se migran los permisos equivalentes a NTFS expuestos por el protocolo SMB.</span><span class="sxs-lookup"><span data-stu-id="70424-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="70424-425">Versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="70424-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="70424-426">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="70424-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="70424-427">Versiones anteriores</span><span class="sxs-lookup"><span data-stu-id="70424-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="70424-428">Atributos de carpetas y archivos de Windows (por ejemplo, Solo lectura u Oculto)</span><span class="sxs-lookup"><span data-stu-id="70424-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="70424-429">Configuración especial y permisos avanzados de New Technology File System (NTFS) y NTFS que no sea para Windows:</span><span class="sxs-lookup"><span data-stu-id="70424-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="70424-430">Denegar explícitamente los permisos (eliminados después de la migración, con contenido sujeto a los permisos paralelos o permisos en la carpeta principal)</span><span class="sxs-lookup"><span data-stu-id="70424-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="70424-431">Configuración de auditoría de NTFS</span><span class="sxs-lookup"><span data-stu-id="70424-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="70424-432">Metadatos de archivo adicionales proporcionados por la Infraestructura de clasificación de archivos (FCI)</span><span class="sxs-lookup"><span data-stu-id="70424-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="70424-433">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="70424-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="70424-434">Recursos compartidos ocultos</span><span class="sxs-lookup"><span data-stu-id="70424-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="70424-435">Uso compartido (por ejemplo, los permisos concedidos en el nivel de uso compartido)</span><span class="sxs-lookup"><span data-stu-id="70424-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="70424-436">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="70424-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="70424-437"><strong>Un solo entorno de G Suite (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="70424-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="70424-438">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="70424-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-439">Documentos, Hojas de Cálculo y Presentaciones de Google (los archivos se convierten al formato equivalente de Office, incluidos los de más de 10 MB)</span><span class="sxs-lookup"><span data-stu-id="70424-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="70424-440">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="70424-441">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-442">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-443">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="70424-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="70424-444">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="70424-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="70424-445">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="70424-445">Created date</span></span> </li>
<li> <span data-ttu-id="70424-446">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="70424-446">Modified date</span></span> </li>
<li> <span data-ttu-id="70424-447">Creada por</span><span class="sxs-lookup"><span data-stu-id="70424-447">Created by</span></span> </li>
<li> <span data-ttu-id="70424-448">Última modificación</span><span class="sxs-lookup"><span data-stu-id="70424-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="70424-449">Unidades compartidas (carpetas y archivos)</span><span class="sxs-lookup"><span data-stu-id="70424-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="70424-450">Contenido compartido propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="70424-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="70424-451">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="70424-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="70424-452">Descripciones de archivos y carpetas, colores de las carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="70424-453">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-454">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-455">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="70424-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="70424-456">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="70424-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="70424-457">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="70424-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="70424-458">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="70424-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="70424-459">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="70424-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="70424-460">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="70424-461">Formularios de Google Photos, Maps y otras aplicaciones conectadas</span><span class="sxs-lookup"><span data-stu-id="70424-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="70424-462">Dibujos de Google</span><span class="sxs-lookup"><span data-stu-id="70424-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="70424-463">Contenido de uso compartido que es externo a su organización</span><span class="sxs-lookup"><span data-stu-id="70424-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="70424-464">Contenido que no es propiedad de la cuenta de Google Drive que se migra</span><span class="sxs-lookup"><span data-stu-id="70424-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="70424-465">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="70424-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="70424-466">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="70424-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="70424-467">Permisos de suscripción de la unidad compartida (<strong>Nota</strong>: Use los informes de administrador de Google Drive para identificar las suscripciones a las unidades compartidas.</span><span class="sxs-lookup"><span data-stu-id="70424-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="70424-468">Indique a los usuarios finales que configuren estas opciones de suscripción en el destino antes de la migración).</span><span class="sxs-lookup"><span data-stu-id="70424-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="70424-469">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="70424-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="70424-470"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="70424-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="70424-471">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="70424-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-472">Documentos</span><span class="sxs-lookup"><span data-stu-id="70424-472">Documents</span></span> </li>
<li> <span data-ttu-id="70424-473">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="70424-474">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-475">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-476">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="70424-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="70424-477">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="70424-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="70424-478">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="70424-478">Created date</span></span> </li>
<li> <span data-ttu-id="70424-479">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="70424-479">Modified date</span></span> </li>
<li> <span data-ttu-id="70424-480">Creada por</span><span class="sxs-lookup"><span data-stu-id="70424-480">Created by</span></span> </li>
<li> <span data-ttu-id="70424-481">Última modificación</span><span class="sxs-lookup"><span data-stu-id="70424-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="70424-482">Contenido compartido que es propiedad de la cuenta de Box que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="70424-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="70424-483">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="70424-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="70424-484">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="70424-485">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-486">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-487">Metadatos avanzados y etiquetas de Box</span><span class="sxs-lookup"><span data-stu-id="70424-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="70424-488">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="70424-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="70424-489">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="70424-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="70424-490">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="70424-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="70424-491">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="70424-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="70424-492">Usuarios bloqueados o inactivos</span><span class="sxs-lookup"><span data-stu-id="70424-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="70424-493">Aplicaciones de Box, Marcadores, Favoritos y Flujos de trabajo</span><span class="sxs-lookup"><span data-stu-id="70424-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="70424-494">Contenido que no es propiedad de la cuenta de Box migrada</span><span class="sxs-lookup"><span data-stu-id="70424-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="70424-495">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Box para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="70424-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="70424-496">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="70424-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="70424-497">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="70424-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="70424-498"><strong>Dropbox para Equipos (estándar y avanzado)</strong></span><span class="sxs-lookup"><span data-stu-id="70424-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="70424-499">Una o varias fases</span><span class="sxs-lookup"><span data-stu-id="70424-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="70424-500">Documentos</span><span class="sxs-lookup"><span data-stu-id="70424-500">Documents</span></span> </li>
<li> <span data-ttu-id="70424-501">Estructura de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="70424-502">Permisos de carpeta de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-503">Permisos de carpeta de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="70424-504">Archivos de menos de 15 GB</span><span class="sxs-lookup"><span data-stu-id="70424-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="70424-505">Metadatos básicos de documentos y carpetas:</span><span class="sxs-lookup"><span data-stu-id="70424-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="70424-506">Fecha de creación</span><span class="sxs-lookup"><span data-stu-id="70424-506">Created date</span></span> </li>
<li> <span data-ttu-id="70424-507">Fecha de modificación</span><span class="sxs-lookup"><span data-stu-id="70424-507">Modified date</span></span> </li>
<li> <span data-ttu-id="70424-508">Creada por</span><span class="sxs-lookup"><span data-stu-id="70424-508">Created by</span></span> </li>
<li> <span data-ttu-id="70424-509">Última modificación</span><span class="sxs-lookup"><span data-stu-id="70424-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="70424-510">Contenido y carpetas de equipo de uso compartido</span><span class="sxs-lookup"><span data-stu-id="70424-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="70424-511">Contenido compartido que es propiedad de la cuenta de Dropbox que se va a migrar</span><span class="sxs-lookup"><span data-stu-id="70424-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="70424-512">Comentarios, versiones anteriores e historial de propiedad</span><span class="sxs-lookup"><span data-stu-id="70424-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="70424-513">Descripciones de archivos y carpetas</span><span class="sxs-lookup"><span data-stu-id="70424-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="70424-514">Permisos de archivo de nivel de usuario</span><span class="sxs-lookup"><span data-stu-id="70424-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-515">Permisos de archivo de nivel de grupo</span><span class="sxs-lookup"><span data-stu-id="70424-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="70424-516">Metadatos avanzados</span><span class="sxs-lookup"><span data-stu-id="70424-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="70424-517">Atributos de bloqueo de archivos</span><span class="sxs-lookup"><span data-stu-id="70424-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="70424-518">Conversión de URL insertadas en el contenido</span><span class="sxs-lookup"><span data-stu-id="70424-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="70424-519">Elementos desechados</span><span class="sxs-lookup"><span data-stu-id="70424-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="70424-520">Documentos inaccesibles o dañados</span><span class="sxs-lookup"><span data-stu-id="70424-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="70424-521">Carpetas de Dropbox desmontadas</span><span class="sxs-lookup"><span data-stu-id="70424-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="70424-522">Usuarios eliminados o desconectados</span><span class="sxs-lookup"><span data-stu-id="70424-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="70424-523">Dropbox Paper, Showcases y Spaces</span><span class="sxs-lookup"><span data-stu-id="70424-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="70424-524">Aplicaciones y favoritos de Dropbox (Pins/Estrellas)</span><span class="sxs-lookup"><span data-stu-id="70424-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="70424-525">Contenido que no es propiedad de la cuenta de Dropbox migrada</span><span class="sxs-lookup"><span data-stu-id="70424-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="70424-526">Permisos y metadatos básicos de usuarios externos (<strong>Nota</strong>: Use los informes de Dropbox para identificar el contenido compartido con usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="70424-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="70424-527">Indique a los usuarios finales que deben volver a compartir el contenido con los usuarios externos después de la migración).</span><span class="sxs-lookup"><span data-stu-id="70424-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="70424-528">Archivos o carpetas que superen las actuales  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Restricciones y limitaciones de SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="70424-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="70424-529">Responsabilidades de FastTrack</span><span class="sxs-lookup"><span data-stu-id="70424-529">FastTrack responsibilities</span></span>

<span data-ttu-id="70424-530">Nuestros especialistas de FastTrack llevan a cabo actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="70424-531">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="70424-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="70424-532">Sus responsabilidades</span><span class="sxs-lookup"><span data-stu-id="70424-532">Your responsibilities</span></span>

<span data-ttu-id="70424-533">Usted realizará actividades estándares durante el proyecto de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="70424-534">Consulte la información sobre las responsabilidades de la migración de datos en [Proceso y expectativas](process-and-expectations.md) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="70424-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="70424-535">También realizará las siguientes actividades, específicas para las migraciones de OneDrive para la Empresa:</span><span class="sxs-lookup"><span data-stu-id="70424-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="70424-536">Aprovisionamiento de todos los sitios de OneDrive para la Empresa que se incluirán en los eventos de migración.</span><span class="sxs-lookup"><span data-stu-id="70424-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
