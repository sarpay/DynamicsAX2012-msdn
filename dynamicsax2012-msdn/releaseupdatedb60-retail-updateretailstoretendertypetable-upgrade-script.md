﻿---
title: ReleaseUpdateDB60_Retail.updateRetailStoreTenderTypeTable Upgrade Script
TOCTitle: ReleaseUpdateDB60_Retail.updateRetailStoreTenderTypeTable Upgrade Script
ms:assetid: 20e4a29f-610e-95de-4a56-ac51a8063d59
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ684909(v=AX.60)
ms:contentKeyID: 49707111
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Retail.updateRetailStoreTenderTypeTable Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Retail</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateRetailStoreTenderTypeTable</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the Dimensions field to DefaultDimension field in the RetailStoreTenderTYpeTable table. Updates the LedgerDimension field to the accountRelation field in the RetailStoreTenderTYpeTable table. Updates the DifferenceAccLedgerDimension field to the differenceAccount field in the RetailStoreTenderTYpeTable table. Updates the DiffAccBigDiffLedgerDimension field to the differenceAccountForBigDifference field in thee RetailStoreTenderTYpeTable table. Updates the BankBagLedgerDimension field to BankBagAccountNumber in the RetailStoreTenderTYpeTable table. Updates the SafeAccLedgerDimension field to the safeAccountRelation in the RetailStoreTenderTYpeTable table.</p></td>
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
<td><p>Retail</p></td>
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
<td><p>DIMENSIONATTRIBUTE</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEDIRCATEGORY</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTELEVELVALUE</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTESET</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTESETITEM</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEVALUE</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTEVALUECOMBINATION</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEVALUECOMBINATIONSTATUS</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTEVALUEGROUP</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEVALUEGROUPCOMBINATION</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTEVALUEGROUPSTATUS</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONATTRIBUTEVALUESET</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONATTRIBUTEVALUESETITEM</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONFINANCIALTAG</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONHIERARCHY</p></td>
</tr>
<tr class="even">
<td><p>DIMENSIONHIERARCHYLEVEL</p></td>
</tr>
<tr class="odd">
<td><p>DIMENSIONVALUEGROUPJOURNALCONTROLSTATUS</p></td>
</tr>
<tr class="even">
<td><p>FINANCIALTAGCATEGORY</p></td>
</tr>
<tr class="odd">
<td><p>LEDGERPARAMETERS</p></td>
</tr>
<tr class="even">
<td><p>MAINACCOUNT</p></td>
</tr>
<tr class="odd">
<td><p>RETAILSTORETENDERTYPETABLE</p></td>
</tr>
</tbody>
</table>

  


