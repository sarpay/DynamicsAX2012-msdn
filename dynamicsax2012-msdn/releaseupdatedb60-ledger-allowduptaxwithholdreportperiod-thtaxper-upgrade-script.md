﻿---
title: ReleaseUpdateDB60_Ledger.allowDupTaxWithholdReportPeriod_THTaxPer Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupTaxWithholdReportPeriod_THTaxPer Upgrade Script
ms:assetid: 08463d71-3d35-391c-4b27-b05449698677
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ684783(v=AX.60)
ms:contentKeyID: 49706478
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupTaxWithholdReportPeriod\_THTaxPer Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowDupTaxWithholdReportPeriod_THTaxPer</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the TaxPeriodIdx index in the TaxWithholdReportPeriod_TH table to allow for duplicate records.</p></td>
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
<td><p>TaxWithholdReportPeriod_TH</p></td>
</tr>
</tbody>
</table>


## Remarks

The DEL\_TaxWithholdPeriod field is replaced with the new TaxWithholdPeriodHead\_TH surrogate key field in the TaxPeriodIdx unique index. Initially this field contains no value. So the index is set to allow for duplicates before the field is updated with the value of the record ID field in the TaxWithholdPeriodHead\_TH table.

  


