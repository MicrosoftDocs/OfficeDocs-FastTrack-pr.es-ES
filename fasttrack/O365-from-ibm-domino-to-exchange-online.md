---
title: Apéndice A Migración de IBM Domino a Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 08/02/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'La migración de IBM Domino a Exchange Online tiene varios aspectos importantes, incluido lo que sucede durante las fases siguientes:'
ms.openlocfilehash: 83235a7765aa424baf92d9081fec86b6f688c365
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 08/01/2019
ms.locfileid: "36053983"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>Apéndice A: Migración de IBM Domino a Exchange Online

La migración de IBM Domino a Exchange Online tiene varios aspectos importantes, incluido lo que sucede durante las fases siguientes: 
- [Fase de inicio](#initiate-phase)   
- [Fase de evaluación](#assess-phase)
- [Fase de corrección](#remediate-phase)  
- [Fase de habilitación](#enable-phase)  
- [Fase de migración](#migrate-phase)
    
## <a name="identities"></a>Identidades

Usted es responsable de crear y administrar las identidades (solo en nube, sincronizadas o federadas con Active Directory local). Debe completar la asignación de identidades (si todavía no está presente) entre Domino y Active Directory local o Azure Active Directory durante las primeras etapas de la incorporación.
  
## <a name="coexistence"></a>Coexistencia

Ventajas del Centro de FastTrack para Office 365 ofrece flujo del correo bidireccional entre el entorno de Domino local y Exchange Online para todos los clientes.
  
## <a name="migration"></a>Migración

El proceso estándar de Centro FastTrack para la migración de Domino a Exchange Online implica la preconfiguración de los datos de Domino en Azure antes de realizar la migración a los buzones de Exchange Online. Las migraciones de FastTrack requieren que tanto el personal de Centro FastTrack como usted realicen actividades en diferentes etapas de la incorporación. Describimos estas actividades en las secciones siguientes.
  
> [!NOTE]
> Los datos que se migran a través de los servicios FastTrack se pueden transferir, almacenar y procesar en los Estados Unidos o en cualquier lugar donde Microsoft disponga de instalaciones. Los servicios FastTrack no están diseñados ni destinados a su uso con datos sujetos a requisitos legales o normativos especiales. 
  
## <a name="initiate-phase"></a>Fase de inicio

 **Acciones clave**
  
- Identificar Domino como plataforma del correo de origen.   
- Determinar si el Centro FastTrack realiza la migración.
    
 **Responsabilidades del cliente**
  
- Proporcionar información básica sobre la plataforma de mensajería de origen y confirmar la intención de migración con el centro FastTrack. 
- Participar en un tutorial sobre los procesos del beneficio del centro FastTrack.  
- Firmar el Contrato de servicios de FastTrack.
    
## <a name="assess-phase"></a>Fase de evaluación

 **Acciones clave**
  
- El Centro FastTrack realiza un taller de migración con el cliente. 
- Debe completar los requisitos previos de migración, como el cuestionario de migración y el aprovisionamiento de las estaciones de trabajo de administración.    
- La evaluación de la migración para Domino se lleva a cabo en su entorno local.
    
 **Responsabilidades del cliente**
  
- Aprovisionar las estaciones de trabajo de administración que el centro FastTrack usa para administrar las tareas de incorporación y migración, como la evaluación, la creación de réplicas, la auditoría, la configuración de reenvío durante la migración, etc.
    > [!NOTE]
    > La evaluación es fundamental para la planificación y la ejecución correctas de las migraciones de velocidad. Se encarga de ello un arquitecto de migración que necesita acceso específico al entorno de Domino. Entre los componentes necesarios de la estación de trabajo de administración se incluyen un cliente de Notes configurado para tener acceso a todos los servidores de correo de Domino de origen y al servidor de implementación de réplicas de Domino de Azure. 
- Proporcionar al equipo de migración acceso remoto a las estaciones de trabajo de administración y las cuentas, así como permisos para llevar a cabo actividades de evaluación y migración. Esto incluye aprovisionar varias cuentas locales y en Exchange Online con los permisos administrativos necesarios para la migración.    
- Abrir puertos de firewall. Se deben abrir puertos de salida entre los servidores de correo de Domino de origen y el servidor de implementación de Azure. También deben abrirse otros puertos para la comunicación (como estaciones de trabajo de administración, servidores de Domino de origen y servidores de Exchange locales, si existen). 
- Habilitar la certificación cruzada entre el entorno de Domino de origen y el servidor de implementación de Azure Domino para facilitar la replicación. Las tareas de certificación cruzada se coordinan entre el administrador de Domino del cliente y el Centro FastTrack.  
- Completar el cuestionario de migración, que recoge la información necesaria para configurar el entorno de migración de Azure (como herramientas, scripts y servidores de migración).   
- Asegúrese de que los buzones de objetivo de Office 365 tienen habilitado el protocolo Interfaz de programación de aplicaciones de mensajería (MAPI).  
> [!NOTE]
> Algunos planes de Office 365 no admiten el protocolo MAPI. Para poder migrar los datos, es necesario convertir los buzones de estos planes en un plan que admita el protocolo MAPI antes del evento de migración. Después de la migración, estos planes pueden volverse a cambiar. 
  
## <a name="remediate-phase"></a>Fase de corrección

 **Acciones clave**
  
- El Centro FastTrack revisa el informe de evaluación de la migración y comprueba los detalles que se proporcionan con el cuestionario.   
- Usted debe aplicar los elementos de corrección sugeridos por el centro FastTrack.
    
 **Responsabilidades del cliente**
  
- Corregir el entorno de Domino según las directrices que proporciona el centro FastTrack (por ejemplo, establecer los permisos necesarios que figuran como ausentes en los archivos de correo).  
- Asegurarse de que los buzones de Domino tienen un tamaño máximo inferior al permitido durante la migración.
    > [!NOTE]
    >  Aunque FastTrack migra buzones de hasta el 85 % del tamaño de destino total permitido, el intento de migrar buzones de más de 2 GB conlleva riesgos adicionales como los siguientes:    <br/> Duración más prolongada de las migraciones.    <br/> Uso de recursos que en otras circunstancias se usarían para migrar otros buzones.    <br/> Aumento considerable de las tasas de error. 
- Preparar las bases de datos de correo y sus listas de control de acceso (ACL) para la migración. Debe llevar a cabo algunos pasos de corrección para migrar correctamente las bases de datos de correo y sus permisos a un buzón compartido en Exchange Online. Entre estos pasos se incluyen los siguientes: 
  - Quitar las entradas existentes de la base de datos de correo en el directorio de Domino y crear nuevos registros personales.
  - Crear grupos de seguridad universal habilitados para correo en Active Directory local que se sincronicen con Office 365 Azure Active Directory y se usen para configurar los permisos en el buzón compartido en Exchange Online. Esto transfiere los permisos establecidos en la base de datos de correo al buzón compartido en Exchange Online.
    
> [!NOTE]
> Ahora puede empezar a preparar y a formar al usuario final sobre el nuevo sistema de mensajería y el cliente. 
  
## <a name="enable-phase"></a>Fase de habilitación

 **Acciones clave**
  
- Centro de FastTrack: 
    - Configura el entorno de migración en Azure.  
    - Configura las herramientas de migración en las estaciones de trabajo de administración locales. 
    - Configura y muestra cómo usar la herramienta de importación automática.  
    - Realiza la validación de todos los componentes de la migración y efectúa migraciones de prueba.
    
 **Responsabilidades del cliente**
  
- El personal encargado de programar la migración de buzones debe saber usar la herramienta de importación automática. Esta herramienta se usa para importar la programación de migración a la base de datos de programación que el Centro FastTrack usa para realizar actividades previas a la migración. 
- Realizar actividades previas a la migración tales como importar las programaciones de los usuarios, analizar informes de auditoría, corregir los problemas y volver a importar las cuentas de usuario con problemas.
    
Las actividades previas a la migración se coordinan entre usted y el Centro de FastTrack. La replicación en Azure comienza después de que se importe la programación de migración del usuario. 
    
> [!NOTE]
> El tiempo necesario para replicar depende de la cantidad de datos. Luego el Centro FastTrack realiza una auditoría para determinar la preparación de la migración. Se le proporcionarán los resultados de la auditoría dando por supuesto que se encargará de llevar a cabo las correcciones posteriores. Todos estos pasos se denominan actividades "de cuenta atrás" porque deben empezar antes de la migración programada de los usuarios. 
  
## <a name="migrate-phase"></a>Fase de migración

 **Acciones clave**
  
- Centro de FastTrack:
    - Realiza migraciones piloto y de velocidad.   
    - Lleva a cabo eventos de migración y actividades de cuenta atrás.
    - Proporciona asistencia posterior a la migración.
    
 **Responsabilidades del cliente**
  
- Identificar e importar las programaciones de migración 21 días antes de la migración.
    > [!NOTE]
    > Esta tarea es fundamental, ya que las actividades previas a la migración conllevan medidas de corrección y posibles reintentos de creación de réplicas en diferentes etapas antes del día de migración real (T-0). Mientras se migran unos buzones, en otros se realizan actividades de cuenta atrás. Por ello, son indispensables una planificación y coordinación correctas. 
- Corregir los problemas identificados durante las actividades de cuenta atrás.
- Abordar y corregir los problemas del servidor de Domino que puedan afectar a las actividades de migración. 
- Comunicar al usuario final la fecha de la próxima migración.
- Llevar a cabo actividades para preparar y formar al usuario final sobre el nuevo cliente y sistema de mensajería.   
- Identificar y comunicar los problemas posteriores a la migración. El Centro FastTrack proporciona soporte técnico posterior a la migración hasta cinco días después de la migración. Posteriormente, será responsabilidad del cliente. Después de la migración puede registrar vales con problemas relativos a correos electrónicos, elementos del calendario y contactos perdidos o duplicados en el buzón.
    
El Centro FastTrack no cubre la implementación, las cuotas de licencia ni la asistencia relacionadas con la preparación de directorios (incluida la sincronización de directorios de Domino con Active Directory), los complementos de software de coexistencia para la interoperabilidad de aplicaciones de Notes, la migración de autoservicio o la migración de archivos.
  

  

