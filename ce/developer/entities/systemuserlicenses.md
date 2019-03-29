---
title: "SystemUserLicenses Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the SystemUserLicenses entity."
ms.date: 03/28/2019
ms.service: "crm-online"
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "KumarVivek"
ms.author: "kvivek"
manager: "annbe"
search.audienceType: 
  - developer
search.app: 
  - PowerApps
  - D365CE
---
# SystemUserLicenses Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]




## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/systemuserlicensescollection<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName||
|DisplayCollectionName||
|DisplayName||
|EntitySetName|systemuserlicensescollection|
|IsBPFEntity|False|
|LogicalCollectionName||
|LogicalName|systemuserlicenses|
|OwnershipType|None|
|PrimaryIdAttribute|systemuserlicenseid|
|PrimaryNameAttribute||
|SchemaName|SystemUserLicenses|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.


### <a name="BKMK_SystemUserLicenseId"></a> SystemUserLicenseId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user licenses.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|systemuserlicenseid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [LicenseId](#BKMK_LicenseId)
- [SystemUserId](#BKMK_SystemUserId)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_LicenseId"></a> LicenseId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|licenseid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_SystemUserId"></a> SystemUserId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|systemuserid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|



### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.systemuserlicenses?text=systemuserlicenses EntityType" />