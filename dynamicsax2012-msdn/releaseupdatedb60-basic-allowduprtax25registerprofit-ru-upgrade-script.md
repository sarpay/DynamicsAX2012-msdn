﻿---
title: ReleaseUpdateDB60_Basic.allowDupRTax25RegisterProfit_RU Upgrade Script
TOCTitle: ReleaseUpdateDB60_Basic.allowDupRTax25RegisterProfit_RU Upgrade Script
ms:assetid: 0e86a21a-8fc6-cd9d-1fb8-180336d8a748
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ735742(v=AX.60)
ms:contentKeyID: 49706644
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Basic.allowDupRTax25RegisterProfit\_RU Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Basic</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowDupRTax25RegisterProfit_RU</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the RegisterProfitIdx index in the RTax25RegisterProfit table to allow duplicate records.</p></td>
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
<td><p>General ledger</p></td>
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
<td><p>RTax25RegisterProfit</p></td>
</tr>
</tbody>
</table>


## Remarks

The ProfitId field is replaced with the new RTax25ProfitTable surrogate key field in the RegisterProfitIdx unique index. Initially this field contains no value. So the index is set to allow duplicates before the field is updated with the value of the record field of the RTax25ProfitTable table.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).
