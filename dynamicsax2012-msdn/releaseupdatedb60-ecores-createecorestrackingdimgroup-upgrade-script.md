﻿---
title: ReleaseUpdateDB60_EcoRes.createEcoResTrackingDimGroup Upgrade Script
TOCTitle: ReleaseUpdateDB60_EcoRes.createEcoResTrackingDimGroup Upgrade Script
ms:assetid: 18a4d45c-9cc4-a1c6-2064-536b3e82a1de
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718615(v=AX.60)
ms:contentKeyID: 49706898
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_EcoRes.createEcoResTrackingDimGroup Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_EcoRes</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>createEcoResTrackingDimGroup</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Creates new records in the EcoResTrackingDimensionGroup table. The data is created based on existing data in the InventDimGroup table. The criteria used for determining how the dimension groups are updated are specified by the user during the pre-upgrade process.</p></td>
</tr>
</tbody>
</table>


## Affected Modules and Tables

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Modules</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Product management</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Tables</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>DEL_InventDimSetup</p></td>
</tr>
<tr class="even">
<td><p>DEL_EcoResDimGroupUpgrade</p></td>
</tr>
<tr class="odd">
<td><p>DEL_EcoResTrackingDimGroupUpgrade</p></td>
</tr>
<tr class="even">
<td><p>EcoResTrackingDimensionGroup</p></td>
</tr>
</tbody>
</table>


## Remarks

The data on which the upgrade is dependent must be provided before the upgrade.

  


