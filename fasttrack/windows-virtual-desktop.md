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
# <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>Servicio</strong></th>
<th><strong>Detalles de instrucciones de FastTrack</strong></th>
<th><strong>Expectativas del entorno de origen</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Windows Virtual Desktop</td>
<td><p>FastTrack proporciona instrucciones de implementación de Escritorio virtual de Windows para ayudarle a incorporarse a este servicio de virtualización de aplicaciones y escritorio con facilidad al aprovechar la experiencia de varias sesiones de Windows 10, optimizada para Aplicaciones de Microsoft 365 para empresas con seguridad y administración integradas para Microsoft 365.</p>
<p>Trabaje con los especialistas de FastTrack para:</p>
<ul>
<li><p>Implemente el entorno WVD con Windows 10 Enterprise multi-session + Aplicaciones de Microsoft 365 para empresas con lo siguiente:</p>
<ul>
<li><p>Imagen de Azure Marketplace</p></li>
<li><p>Imagen compartida</p></li>
<li><p>Office Deployment Toolkit (ODT)</p></li>
</ul></li>
<li><p>Configurar FSLogix</p>
<ul>
<li><p>Implementar el agente FSLogix con el contenedor de perfiles</p></li>
<li><p>Implementar el agente FSLogix con el contenedor de Office</p></li>
<li><p>Configurar la carpeta FSLogix con exclusiones de contenido</p></li>
</ul></li>
<li><p>Implementar Microsoft Edge</p></li>
<li><p>Implementar Microsoft Teams</p></li>
<li><p>Conectarse con clientes de Escritorio virtual de Windows</p></li>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>
<li><p>Administración de proyectos de la implementación de Windows Virtual Desktop del cliente.</p></li>
<li><p>Soporte técnico en las instalaciones.</p></li>
<li><p>Implementación e virtualización de aplicaciones de terceros.</p></li>
<li><p>Imágenes personalizadas.</p></li>
<li><p>Migraciones y escenarios en los que participan VMware y Citrix.</p></li>
<li><p>Escenarios de Linux.</p></li>
<li><p>Conversión o migraciones de perfiles de usuario.</p></li>
</ul>
<p>Póngase en <a href="https://go.microsoft.com/fwlink/?linkid=2080150">contacto con un partner de Microsoft</a> para obtener ayuda con estos servicios.</p></td>
<td><p>Ya debería tener lo siguiente:</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisitos de licencias de WVD</a></p></li>
<li><p>Redes de Azure:</p>
<ul>
<li><p>Creación de VNET &amp; Subredes</p></li>
<li><p>Firewall/Grupos de seguridad de red</p></li>
<li><p>VPN /ExpressRoute</p></li>
<li><p>Enrutamiento a Azure desde local</p></li>
<li><p>Reglas de firewall para permitir la conectividad a WVD</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Referencia de documentos</a></p></li>
</ul></li>
</ul></li>
<li><p>Instalación general de Azure Active Directory</p>
<ul>
<li><p>Estrategia de <strong>identidad (seleccione SOLO 1 de las 3 opciones siguientes)</strong></p>
<ul>
<li><p>Active Directory con Azure AD Connect en Azure</p></li>
<li><p>Active Directory con Azure AD Connect On Premise over VPN /ER</p></li>
<li><p>Servicios de dominio de Active Directory</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
