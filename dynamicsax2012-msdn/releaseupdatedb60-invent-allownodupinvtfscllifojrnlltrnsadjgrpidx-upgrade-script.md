﻿---
title: ReleaseUpdateDB60_Invent.allowNoDupInvtFsclLIFOJrnllTrnsAdjGrpIdx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Invent.allowNoDupInvtFsclLIFOJrnllTrnsAdjGrpIdx Upgrade Script
ms:assetid: cba4b166-aa62-269f-f023-254d0cd38513
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719670(v=AX.60)
ms:contentKeyID: 49711236
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Invent.allowNoDupInvtFsclLIFOJrnllTrnsAdjGrpIdx Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Invent</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupInvtFsclLIFOJrnllTrnsAdjGrpIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the GroupItemYearIdx index in the InventFiscalLIFOJournalTransAdj table not to allow for duplicate records.</p></td>
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
<td><p>Inventory management</p></td>
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
<td><p>InventFiscalLIFOJournalTransAdj</p></td>
</tr>
</tbody>
</table>


## Remarks

The name of this method is truncated from allowNoDupInventFiscalLIFOJournalTransAdjGroupItemYearIdx. After updating the surrogate key InventFiscalLIFOGroup field with the value of the RecId field of the InventFiscalLIFOGroup table, the GroupItemYearIdx index is reset not to allow for duplicate records.

  


