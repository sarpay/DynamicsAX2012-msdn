﻿---
title: ReleaseUpdateDB60_Ledger.updateGDL_TaxRepLines_BookType Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.updateGDL_TaxRepLines_BookType Upgrade Script
ms:assetid: e3fca052-a2f6-3719-4eba-911809ecf8e0
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737361(v=AX.60)
ms:contentKeyID: 49711802
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.updateGDL\_TaxRepLines\_BookType Upgrade Script 


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
<td><p>updateGDL_TaxRepLines_BookType</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Populates the TaxReportLines.TaxBookType field values based on the corresponding TaxTrans.TaxDirection field values.</p></td>
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
<td><p>TaxReportLines</p></td>
</tr>
</tbody>
</table>


## Remarks

The TaxReportLines.TaxBookType is set to the TaxBookType\_ES::IncomingTax value if the value of the corresponding TaxTrans.TaxDirection field is the TaxDirection::IncomingTax value or the TaxDirection::TaxExemptPurchase value. The TaxReportLines.TaxBookType is set to the TaxBookType\_ES::OutgoingTax value if the value of the corresponding TaxTrans.TaxDirection field is the TaxDirection::OutgoingTax or TaxDirection::TaxExemptSales value.

## New Tables or Fields

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
<th><p>Extended Data Type</p>
<p>-or- Base Enum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>TaxReportLines</p></td>
<td><p>TaxBookType</p></td>
<td><p>TaxBookType_ES</p></td>
</tr>
</tbody>
</table>

  


