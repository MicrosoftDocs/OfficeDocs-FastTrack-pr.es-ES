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
description: FastTrack proporciona Windows de implementación de Escritorio virtual para ayudarle a incorporarse a este escritorio.
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592443"
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
<td><p>FastTrack proporciona una guía de implementación de Escritorio virtual de Windows para ayudarle Windows 10 incorporarse a este servicio de virtualización de aplicaciones y escritorio con facilidad, al tiempo que aprovecha una experiencia de varias sesiones, optimizada para Aplicaciones Microsoft 365 para Enterprise con seguridad y administración integradas para Microsoft 365.</p>
<p>Trabaje con los especialistas de FastTrack para:</p>
<ul>
<li><p>Implemente el entorno WVD Windows 10 Enterprise multi-sesión + Aplicaciones Microsoft 365 para Enterprise mediante lo siguiente:</p>
<ul>
<li><p>Imagen de Azure Marketplace</p></li>
<li><p>Imagen compartida</p></li>
<li><p>Office Implementación Toolkit (ODT)</p></li>
</ul></li>
<li><p>Configurar FSLogix</p>
<ul>
<li><p>Implementar el agente FSLogix con el contenedor de perfiles</p></li>
<li><p>Implementar el agente FSLogix con Office contenedor</p></li>
<li><p>Configurar la carpeta FSLogix con exclusiones de contenido</p></li>
</ul></li>
<li><p>Implementar Microsoft Edge</p></li>
<li><p>Implementar Microsoft Teams</p></li>
<li><p>Conectar usar Windows de escritorio virtual</p></li>
</ul>
<p><strong>Lo siguiente está fuera del ámbito</strong></p>
<ul>
<li><p>Project administración de la implementación de Escritorio virtual Windows cliente.</p></li>
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
<li><p>[Requisitos de licencias de WVD](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Redes de Azure:</p>
<ul>
<li><p>Creación de VNET &amp; Subredes</p></li>
<li><p>Firewall/Grupos de seguridad de red</p></li>
<li><p>VPN /ExpressRoute</p></li>
<li><p>Enrutamiento a Azure desde local</p></li>
<li><p>Reglas de firewall para permitir la conectividad a WVD</p>
<ul>
<li><p>[Referencia de documentos](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory Configuración general</p>
<ul>
<li><p>Estrategia de <strong>identidad (seleccione SOLO 1 de las 3 opciones siguientes)</strong></p>
<ul>
<li><p>Active Directory con Azure AD Conectar en Azure</p></li>
<li><p>Active Directory con Azure AD Conectar local a través de VPN /ER</p></li>
<li><p>Servicios de dominio de Active Directory</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
