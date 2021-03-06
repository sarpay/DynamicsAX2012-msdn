﻿---
title: ReleaseUpdateDB60_Proj.updateProjProposalJour Upgrade Script
TOCTitle: ReleaseUpdateDB60_Proj.updateProjProposalJour Upgrade Script
ms:assetid: 65363a82-6fe0-1e7c-d4ca-cbb5cc3d740b
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719189(v=AX.60)
ms:contentKeyID: 49708728
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Proj.updateProjProposalJour Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Proj</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateProjProposalJour</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Migrates data from the DEL_ApprovedBy field to the WorkerApprovedBy field and the DEL_ProjAdministrator field to the WorkerProjAdministrator field in the ProjProposalJour table.</p></td>
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
<td><p>Project</p></td>
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
<td><p>ProjProposalJour</p></td>
</tr>
</tbody>
</table>


## Remarks

The HCMWorker table and associated tables have replaced the Employee table, that is the EmplTable table, and associated tables in Microsoft Dynamics AX 2012. This transition requires an upgrade.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: ProjProposalJour</p></th>
<th><p>To Table: ProjProposalJour</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>DEL_ApprovedBy</p></td>
<td><p>WorkerApprovedBy</p></td>
</tr>
<tr class="even">
<td><p>DEL_ProjAdministrator</p></td>
<td><p>WorkerProjAdministrator</p></td>
</tr>
</tbody>
</table>


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
<td><p>ProjProposalJour</p></td>
<td><p>WorkerApprovedBy</p></td>
<td><p>ProjWorkerRecId</p></td>
</tr>
<tr class="even">
<td><p>ProjProposalJour</p></td>
<td><p>WorkerProjAdministrator</p></td>
<td><p>ProjWorkerRecId</p></td>
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
<td><p>ProjProposalJour</p></td>
<td><p>DEL_ApprovedBy</p></td>
</tr>
<tr class="even">
<td><p>ProjProposalJour</p></td>
<td><p>DEL_ProjAdministrator</p></td>
</tr>
</tbody>
</table>

  


