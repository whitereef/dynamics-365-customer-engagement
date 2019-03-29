---
title: "msdyn_msdyn_customerasset_msdyn_3dmodel Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_msdyn_customerasset_msdyn_3dmodel entity."
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
# msdyn_msdyn_customerasset_msdyn_3dmodel Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]



**Added by**: Field Service Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_msdyn_customerasset_msdyn_3dmodelset<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName||
|DisplayCollectionName||
|DisplayName||
|EntitySetName|msdyn_msdyn_customerasset_msdyn_3dmodelset|
|IsBPFEntity|False|
|LogicalCollectionName||
|LogicalName|msdyn_msdyn_customerasset_msdyn_3dmodel|
|OwnershipType|None|
|PrimaryIdAttribute|msdyn_msdyn_customerasset_msdyn_3dmodelid|
|PrimaryNameAttribute||
|SchemaName|msdyn_msdyn_customerasset_msdyn_3dmodel|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [msdyn_3dmodelid](#BKMK_msdyn_3dmodelid)
- [msdyn_customerassetid](#BKMK_msdyn_customerassetid)
- [msdyn_msdyn_customerasset_msdyn_3dmodelId](#BKMK_msdyn_msdyn_customerasset_msdyn_3dmodelId)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_msdyn_3dmodelid"></a> msdyn_3dmodelid

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_3dmodelid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_customerassetid"></a> msdyn_customerassetid

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_customerassetid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_msdyn_customerasset_msdyn_3dmodelId"></a> msdyn_msdyn_customerasset_msdyn_3dmodelId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_msdyn_customerasset_msdyn_3dmodelid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_VersionNumber"></a> VersionNumber

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="manytomany"></a>

## Many-To-Many Relationships

Relationship details provided where the msdyn_msdyn_customerasset_msdyn_3dmodel entity is the first entity in the relationship. Listed by **SchemaName**.


### <a name="BKMK_msdyn_msdyn_customerasset_msdyn_3dmodel"></a> msdyn_msdyn_customerasset_msdyn_3dmodel

See msdyn_customerasset Entity [msdyn_msdyn_customerasset_msdyn_3dmodel](msdyn_customerasset.md#BKMK_msdyn_msdyn_customerasset_msdyn_3dmodel) Many-To-Many Relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_msdyn_customerasset_msdyn_3dmodel?text=msdyn_msdyn_customerasset_msdyn_3dmodel EntityType" />