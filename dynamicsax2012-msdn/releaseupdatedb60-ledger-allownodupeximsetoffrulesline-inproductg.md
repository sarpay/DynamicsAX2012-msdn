﻿---
title: ReleaseUpdateDB60_Ledger.allowNoDupEximSetOffRulesLine_INProductG
TOCTitle: ReleaseUpdateDB60_Ledger.allowNoDupEximSetOffRulesLine_INProductG
ms:assetid: 5e8d4fab-5661-8dab-a7e8-2b5c8d13c733
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719027(v=AX.60)
ms:contentKeyID: 49708567
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowNoDupEximSetOffRulesLine\_INProductG 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

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
<td><p>allowNoDupEximSetOffRulesLine_INProductG</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the index &lt;c&gt;ProductGroupSetOffRulesIdx&lt;/c&gt; in the table &lt;c&gt;EximSetOffRulesLine_IN&lt;/c&gt; not to allow duplicate records.</p></td>
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
<td><p>EXIMSETOFFRULESLINE_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the surrogate key field EximProductGroupTable RecId field of the table EximProductGroupTable\_IN, the index ProductGroupSetOffRulesIdx is reset not to allow duplicate records.

  


