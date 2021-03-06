﻿---
title: ReleaseUpdateDB60_HRM.updateHcmSurveyCompany
TOCTitle: ReleaseUpdateDB60_HRM.updateHcmSurveyCompany
ms:assetid: af0bffe3-20ec-dfff-8982-25335efcf272
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686556(v=AX.60)
ms:contentKeyID: 49710510
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_HRM.updateHcmSurveyCompany 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_HRM</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateHcmSurveyCompany</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Inserts records into the &lt;c&gt;HcmSurveyCompany&lt;/c&gt; table from the &lt;c&gt;HRMCompSurveyCompany&lt;/c&gt; table.</p></td>
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
<td><p>Human Resources</p></td>
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
<td><p>HcmSurveyCompany</p></td>
</tr>
<tr class="even">
<td><p>HRMCompSurveyCompany</p></td>
</tr>
</tbody>
</table>


## Remarks

This upgrade will retain the data of each company by appending the \<c\>DataAreaId\</c\> to the \<c\>SurveyCompanyId\</c\> field of the \<c\>HRMCompSurveyCompany\</c\> table to create new, unique identifiers for the \<c\>HcmSurveyCompany\</c\> table when multiple companies exist. If only one company exists, the \<c\>DataAreaId\</c\> field will not be appended.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: HRMCompSurveyCompany</p></th>
<th><p>To Table: HcmSurveyCompany</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
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
<td><p>HcmSurveyCompany</p></td>
<td><p></p></td>
<td><p></p></td>
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
<td><p>HRMCompSurveyCompany</p></td>
<td><p>*</p></td>
</tr>
</tbody>
</table>

  


