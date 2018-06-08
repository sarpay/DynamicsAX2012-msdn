﻿---
title: ReleaseUpdateDB60_EcoRes.createEcoResProductVariantSize Upgrade Script
TOCTitle: ReleaseUpdateDB60_EcoRes.createEcoResProductVariantSize Upgrade Script
ms:assetid: f844f39f-f476-d48d-428a-5c4c734110de
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737626(v=AX.60)
ms:contentKeyID: 49712319
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_EcoRes.createEcoResProductVariantSize Upgrade Script 


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
<td><p>createEcoResProductVariantSize</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Populates the EcoResProductVariantSize table with information from the InventSize table through the DEL_EcoResProdUpgradeSize table.</p></td>
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
<td><p>EcoResProductVariantDimensionValue</p></td>
</tr>
<tr class="even">
<td><p>EcoResProductVariantSize</p></td>
</tr>
<tr class="odd">
<td><p>DEL_EcoResProdUpgradeVariant</p></td>
</tr>
<tr class="even">
<td><p>EcoResProductDimensionAttribute</p></td>
</tr>
<tr class="odd">
<td><p>EcoResDistinctProductVariant</p></td>
</tr>
<tr class="even">
<td><p>EcoResSize</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).
