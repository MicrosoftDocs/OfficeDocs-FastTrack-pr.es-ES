---
title: Apéndice A Migración de IBM Domino a Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/02/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'La migración de IBM Domino a Exchange Online tiene varios aspectos importantes, incluido lo que sucede durante las fases siguientes:'
ms.openlocfilehash: 84e861794f540689c948762aedc2dee4fa54021b
ms.sourcegitcommit: 06eb1378c0f3601ca6909765ecacbff23db7e71f
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/01/2019
ms.locfileid: "37342215"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="61965-103">Apéndice A: Migración de IBM Domino a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="61965-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="61965-104">La migración de IBM Domino a Exchange Online tiene varios aspectos importantes, incluido lo que sucede durante las fases siguientes:</span><span class="sxs-lookup"><span data-stu-id="61965-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="61965-105">Fase de inicio</span><span class="sxs-lookup"><span data-stu-id="61965-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="61965-106">Fase de evaluación</span><span class="sxs-lookup"><span data-stu-id="61965-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="61965-107">Fase de corrección</span><span class="sxs-lookup"><span data-stu-id="61965-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="61965-108">Fase de habilitación</span><span class="sxs-lookup"><span data-stu-id="61965-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="61965-109">Fase de migración</span><span class="sxs-lookup"><span data-stu-id="61965-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="61965-110">Identidades</span><span class="sxs-lookup"><span data-stu-id="61965-110">Identities</span></span>

<span data-ttu-id="61965-111">Usted es responsable de crear y administrar las identidades (solo en nube, sincronizadas o federadas con Active Directory local).</span><span class="sxs-lookup"><span data-stu-id="61965-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="61965-112">Debe completar la asignación de identidades (si todavía no está presente) entre Domino y Active Directory local o Azure Active Directory durante las primeras etapas de la incorporación.</span><span class="sxs-lookup"><span data-stu-id="61965-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="61965-113">Coexistencia</span><span class="sxs-lookup"><span data-stu-id="61965-113">Coexistence</span></span>

<span data-ttu-id="61965-114">Ventajas del Centro de FastTrack para Office 365 ofrece flujo del correo bidireccional entre el entorno de Domino local y Exchange Online para todos los clientes.</span><span class="sxs-lookup"><span data-stu-id="61965-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="61965-115">Migración</span><span class="sxs-lookup"><span data-stu-id="61965-115">Migration</span></span>

<span data-ttu-id="61965-p102">El proceso estándar de Centro FastTrack para la migración de Domino a Exchange Online implica la preconfiguración de los datos de Domino en Azure antes de realizar la migración a los buzones de Exchange Online. Las migraciones de FastTrack requieren que tanto el personal de Centro FastTrack como usted realicen actividades en diferentes etapas de la incorporación. Describimos estas actividades en las secciones siguientes.</span><span class="sxs-lookup"><span data-stu-id="61965-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="61965-p103">Los datos que se migran a través de los servicios FastTrack se pueden transferir, almacenar y procesar en los Estados Unidos o en cualquier lugar donde Microsoft disponga de instalaciones. Los servicios FastTrack no están diseñados ni destinados a su uso con datos sujetos a requisitos legales o normativos especiales.</span><span class="sxs-lookup"><span data-stu-id="61965-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="61965-121">Fase de inicio</span><span class="sxs-lookup"><span data-stu-id="61965-121">Initiate phase</span></span>

 <span data-ttu-id="61965-122">**Acciones clave**</span><span class="sxs-lookup"><span data-stu-id="61965-122">**Key actions**</span></span>
  
- <span data-ttu-id="61965-123">Identificar Domino como plataforma del correo de origen.</span><span class="sxs-lookup"><span data-stu-id="61965-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="61965-124">Determinar si el Centro FastTrack realiza la migración.</span><span class="sxs-lookup"><span data-stu-id="61965-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="61965-125">**Responsabilidades del cliente**</span><span class="sxs-lookup"><span data-stu-id="61965-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="61965-126">Proporcionar información básica sobre la plataforma de mensajería de origen y confirmar la intención de migración con el centro FastTrack.</span><span class="sxs-lookup"><span data-stu-id="61965-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="61965-127">Participar en un tutorial sobre los procesos del beneficio del centro FastTrack.</span><span class="sxs-lookup"><span data-stu-id="61965-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="61965-128">Firmar el Contrato de servicios de FastTrack.</span><span class="sxs-lookup"><span data-stu-id="61965-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="61965-129">Fase de evaluación</span><span class="sxs-lookup"><span data-stu-id="61965-129">Assess phase</span></span>

 <span data-ttu-id="61965-130">**Acciones clave**</span><span class="sxs-lookup"><span data-stu-id="61965-130">**Key actions**</span></span>
  
- <span data-ttu-id="61965-131">El Centro FastTrack realiza un taller de migración con el cliente.</span><span class="sxs-lookup"><span data-stu-id="61965-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="61965-132">Debe completar los requisitos previos de migración, como el cuestionario de migración y el aprovisionamiento de las estaciones de trabajo de administración.</span><span class="sxs-lookup"><span data-stu-id="61965-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="61965-133">La evaluación de la migración para Domino se lleva a cabo en su entorno local.</span><span class="sxs-lookup"><span data-stu-id="61965-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="61965-134">**Responsabilidades del cliente**</span><span class="sxs-lookup"><span data-stu-id="61965-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="61965-135">Aprovisionar las estaciones de trabajo de administración que el centro FastTrack usa para administrar las tareas de incorporación y migración, como la evaluación, la creación de réplicas, la auditoría, la configuración de reenvío durante la migración, etc.</span><span class="sxs-lookup"><span data-stu-id="61965-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="61965-p104">La evaluación es fundamental para la planificación y la ejecución correctas de las migraciones de velocidad. Se encarga de ello un arquitecto de migración que necesita acceso específico al entorno de Domino. Entre los componentes necesarios de la estación de trabajo de administración se incluyen un cliente de Notes configurado para tener acceso a todos los servidores de correo de Domino de origen y al servidor de implementación de réplicas de Domino de Azure.</span><span class="sxs-lookup"><span data-stu-id="61965-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="61965-p105">Proporcionar al equipo de migración acceso remoto a las estaciones de trabajo de administración y las cuentas, así como permisos para llevar a cabo actividades de evaluación y migración. Esto incluye aprovisionar varias cuentas locales y en Exchange Online con los permisos administrativos necesarios para la migración.</span><span class="sxs-lookup"><span data-stu-id="61965-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="61965-p106">Abrir puertos de firewall. Se deben abrir puertos de salida entre los servidores de correo de Domino de origen y el servidor de implementación de Azure. También deben abrirse otros puertos para la comunicación (como estaciones de trabajo de administración, servidores de Domino de origen y servidores de Exchange locales, si existen).</span><span class="sxs-lookup"><span data-stu-id="61965-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="61965-p107">Habilitar la certificación cruzada entre el entorno de Domino de origen y el servidor de implementación de Azure Domino para facilitar la replicación. Las tareas de certificación cruzada se coordinan entre el administrador de Domino del cliente y el Centro FastTrack.</span><span class="sxs-lookup"><span data-stu-id="61965-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="61965-146">Completar el cuestionario de migración, que recoge la información necesaria para configurar el entorno de migración de Azure (como herramientas, scripts y servidores de migración).</span><span class="sxs-lookup"><span data-stu-id="61965-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="61965-147">Asegúrese de que los buzones de objetivo de Office 365 tienen habilitado el protocolo Interfaz de programación de aplicaciones de mensajería (MAPI).</span><span class="sxs-lookup"><span data-stu-id="61965-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="61965-p108">Algunos planes de Office 365 no admiten el protocolo MAPI. Para poder migrar los datos, es necesario convertir los buzones de estos planes en un plan que admita el protocolo MAPI antes del evento de migración. Después de la migración, estos planes pueden volverse a cambiar.</span><span class="sxs-lookup"><span data-stu-id="61965-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="61965-151">Fase de corrección</span><span class="sxs-lookup"><span data-stu-id="61965-151">Remediate phase</span></span>

 <span data-ttu-id="61965-152">**Acciones clave**</span><span class="sxs-lookup"><span data-stu-id="61965-152">**Key actions**</span></span>
  
- <span data-ttu-id="61965-153">El Centro FastTrack revisa el informe de evaluación de la migración y comprueba los detalles que se proporcionan con el cuestionario.</span><span class="sxs-lookup"><span data-stu-id="61965-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="61965-154">Usted debe aplicar los elementos de corrección sugeridos por el centro FastTrack.</span><span class="sxs-lookup"><span data-stu-id="61965-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="61965-155">**Responsabilidades del cliente**</span><span class="sxs-lookup"><span data-stu-id="61965-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="61965-156">Corregir el entorno de Domino según las directrices que proporciona el centro FastTrack (por ejemplo, establecer los permisos necesarios que figuran como ausentes en los archivos de correo).</span><span class="sxs-lookup"><span data-stu-id="61965-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="61965-157">Asegurarse de que los buzones de Domino tienen un tamaño máximo inferior al permitido durante la migración.</span><span class="sxs-lookup"><span data-stu-id="61965-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="61965-158">Aunque FastTrack migra buzones de hasta el 85 % del tamaño de destino total permitido, el intento de migrar buzones de más de 2 GB conlleva riesgos adicionales como los siguientes:</span><span class="sxs-lookup"><span data-stu-id="61965-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="61965-p109">Duración más prolongada de las migraciones.    </span><span class="sxs-lookup"><span data-stu-id="61965-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="61965-p110">Uso de recursos que en otras circunstancias se usarían para migrar otros buzones.    </span><span class="sxs-lookup"><span data-stu-id="61965-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="61965-161">Aumento considerable de las tasas de error.</span><span class="sxs-lookup"><span data-stu-id="61965-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="61965-p111">Preparar las bases de datos de correo y sus listas de control de acceso (ACL) para la migración. Debe llevar a cabo algunos pasos de corrección para migrar correctamente las bases de datos de correo y sus permisos a un buzón compartido en Exchange Online. Entre estos pasos se incluyen los siguientes:</span><span class="sxs-lookup"><span data-stu-id="61965-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="61965-165">Quitar las entradas existentes de la base de datos de correo en el directorio de Domino y crear nuevos registros personales.</span><span class="sxs-lookup"><span data-stu-id="61965-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="61965-166">Crear grupos de seguridad universal habilitados para correo en Active Directory local que se sincronicen con Office 365 Azure Active Directory y se usen para configurar los permisos en el buzón compartido en Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="61965-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="61965-167">Esto transfiere los permisos establecidos en la base de datos de correo al buzón compartido en Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="61965-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="61965-168">Ahora puede empezar a preparar y a formar al usuario final sobre el nuevo sistema de mensajería y el cliente.</span><span class="sxs-lookup"><span data-stu-id="61965-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="61965-169">Fase de habilitación</span><span class="sxs-lookup"><span data-stu-id="61965-169">Enable phase</span></span>

 <span data-ttu-id="61965-170">**Acciones clave**</span><span class="sxs-lookup"><span data-stu-id="61965-170">**Key actions**</span></span>
  
- <span data-ttu-id="61965-171">Centro de FastTrack:</span><span class="sxs-lookup"><span data-stu-id="61965-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="61965-172">Configura el entorno de migración en Azure.</span><span class="sxs-lookup"><span data-stu-id="61965-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="61965-173">Configura las herramientas de migración en las estaciones de trabajo de administración locales.</span><span class="sxs-lookup"><span data-stu-id="61965-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="61965-174">Configura y muestra cómo usar la herramienta de importación automática.</span><span class="sxs-lookup"><span data-stu-id="61965-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="61965-175">Realiza la validación de todos los componentes de la migración y efectúa migraciones de prueba.</span><span class="sxs-lookup"><span data-stu-id="61965-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="61965-176">**Responsabilidades del cliente**</span><span class="sxs-lookup"><span data-stu-id="61965-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="61965-p113">El personal encargado de programar la migración de buzones debe saber usar la herramienta de importación automática. Esta herramienta se usa para importar la programación de migración a la base de datos de programación que el Centro FastTrack usa para realizar actividades previas a la migración.</span><span class="sxs-lookup"><span data-stu-id="61965-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="61965-179">Realizar actividades previas a la migración tales como importar las programaciones de los usuarios, analizar informes de auditoría, corregir los problemas y volver a importar las cuentas de usuario con problemas.</span><span class="sxs-lookup"><span data-stu-id="61965-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="61965-p114">Las actividades previas a la migración se coordinan entre usted y el Centro de FastTrack. La replicación en Azure comienza después de que se importe la programación de migración del usuario.</span><span class="sxs-lookup"><span data-stu-id="61965-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="61965-p115">El tiempo necesario para replicar depende de la cantidad de datos. Luego el Centro FastTrack realiza una auditoría para determinar la preparación de la migración. Se le proporcionarán los resultados de la auditoría dando por supuesto que se encargará de llevar a cabo las correcciones posteriores. Todos estos pasos se denominan actividades "de cuenta atrás" porque deben empezar antes de la migración programada de los usuarios.</span><span class="sxs-lookup"><span data-stu-id="61965-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="61965-186">Fase de migración</span><span class="sxs-lookup"><span data-stu-id="61965-186">Migrate phase</span></span>

 <span data-ttu-id="61965-187">**Acciones clave**</span><span class="sxs-lookup"><span data-stu-id="61965-187">**Key actions**</span></span>
  
- <span data-ttu-id="61965-188">Centro de FastTrack:</span><span class="sxs-lookup"><span data-stu-id="61965-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="61965-189">Realiza migraciones piloto y de velocidad. </span><span class="sxs-lookup"><span data-stu-id="61965-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="61965-190">Lleva a cabo eventos de migración y actividades de cuenta atrás.</span><span class="sxs-lookup"><span data-stu-id="61965-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="61965-191">Proporciona asistencia posterior a la migración.</span><span class="sxs-lookup"><span data-stu-id="61965-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="61965-192">**Responsabilidades del cliente**</span><span class="sxs-lookup"><span data-stu-id="61965-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="61965-193">Identificar e importar las programaciones de migración 21 días antes de la migración.</span><span class="sxs-lookup"><span data-stu-id="61965-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="61965-p116">Esta tarea es fundamental, ya que las actividades previas a la migración conllevan medidas de corrección y posibles reintentos de creación de réplicas en diferentes etapas antes del día de migración real (T-0). Mientras se migran unos buzones, en otros se realizan actividades de cuenta atrás. Por ello, son indispensables una planificación y coordinación correctas.</span><span class="sxs-lookup"><span data-stu-id="61965-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="61965-197">Corregir los problemas identificados durante las actividades de cuenta atrás.</span><span class="sxs-lookup"><span data-stu-id="61965-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="61965-198">Abordar y corregir los problemas del servidor de Domino que puedan afectar a las actividades de migración.</span><span class="sxs-lookup"><span data-stu-id="61965-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="61965-199">Comunicar al usuario final la fecha de la próxima migración.</span><span class="sxs-lookup"><span data-stu-id="61965-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="61965-200">Llevar a cabo actividades para preparar y formar al usuario final sobre el nuevo cliente y sistema de mensajería.</span><span class="sxs-lookup"><span data-stu-id="61965-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="61965-p117">Identificar y comunicar los problemas posteriores a la migración. El Centro FastTrack proporciona soporte técnico posterior a la migración hasta cinco días después de la migración. Posteriormente, será responsabilidad del cliente. Después de la migración puede registrar vales con problemas relativos a correos electrónicos, elementos del calendario y contactos perdidos o duplicados en el buzón.</span><span class="sxs-lookup"><span data-stu-id="61965-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="61965-204">El Centro FastTrack no cubre la implementación, las cuotas de licencia ni la asistencia relacionadas con la preparación de directorios (incluida la sincronización de directorios de Domino con Active Directory), los complementos de software de coexistencia para la interoperabilidad de aplicaciones de Notes, la migración de autoservicio o la migración de archivos.</span><span class="sxs-lookup"><span data-stu-id="61965-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

