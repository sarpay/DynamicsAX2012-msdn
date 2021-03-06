﻿---
title: ReleaseUpdateDB60_Vend.updateVendInvoiceInfoTable_IN Upgrade Script
TOCTitle: ReleaseUpdateDB60_Vend.updateVendInvoiceInfoTable_IN Upgrade Script
ms:assetid: 80600dbe-aa88-d3d1-04be-3024ce3cec36
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685902(v=AX.60)
ms:contentKeyID: 49709355
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Vend.updateVendInvoiceInfoTable\_IN Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Vend</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateVendInvoiceInfoTable_IN</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the VendInvoiceInfoTable table. The record IDs of the CustomsBillOfEntryNumberTable_IN and CustomsImportInvoiceNumberTable_IN records are now stored in place of the CustomsBillOfEntryNumber_IN and CustomsImporterInvoiceNumber_IN field values.</p></td>
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
<td><p>Accounts payable</p></td>
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
<td><p>VendInvoiceInfoTable</p></td>
</tr>
<tr class="even">
<td><p>CustomsBillOfEntryNumberTable_IN</p></td>
</tr>
<tr class="odd">
<td><p>CustomsImportInvoiceNumberTable_IN</p></td>
</tr>
</tbody>
</table>


## Deleted Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>VendInvoiceInfoTable</p></td>
<td><p>del_CustomsBillOfEntryNumber_IN</p></td>
</tr>
<tr class="even">
<td><p>VendInvoiceInfoTable</p></td>
<td><p>del_CustomsImporterInvoiceNumber_IN</p></td>
</tr>
</tbody>
</table>

  


