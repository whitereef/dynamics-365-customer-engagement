---
title: "msdyn_resourcerequirement_systemuser Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_resourcerequirement_systemuser entity."
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
# msdyn_resourcerequirement_systemuser Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]



**Added by**: Project Service Automation Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_resourcerequirement_systemuserset<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName||
|DisplayCollectionName||
|DisplayName||
|EntitySetName|msdyn_resourcerequirement_systemuserset|
|IsBPFEntity|False|
|LogicalCollectionName||
|LogicalName|msdyn_resourcerequirement_systemuser|
|OwnershipType|None|
|PrimaryIdAttribute|msdyn_resourcerequirement_systemuserid|
|PrimaryNameAttribute||
|SchemaName|msdyn_resourcerequirement_systemuser|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [msdyn_resourcerequirement_systemuserId](#BKMK_msdyn_resourcerequirement_systemuserId)
- [msdyn_resourcerequirementid](#BKMK_msdyn_resourcerequirementid)
- [systemuserid](#BKMK_systemuserid)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_msdyn_resourcerequirement_systemuserId"></a> msdyn_resourcerequirement_systemuserId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_resourcerequirement_systemuserid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_resourcerequirementid"></a> msdyn_resourcerequirementid

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_resourcerequirementid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_systemuserid"></a> systemuserid

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

Relationship details provided where the msdyn_resourcerequirement_systemuser entity is the first entity in the relationship. Listed by **SchemaName**.


### <a name="BKMK_msdyn_resourcerequirement_systemuser"></a> msdyn_resourcerequirement_systemuser

See msdyn_resourcerequirement Entity [msdyn_resourcerequirement_systemuser](msdyn_resourcerequirement.md#BKMK_msdyn_resourcerequirement_systemuser) Many-To-Many Relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_resourcerequirement_systemuser?text=msdyn_resourcerequirement_systemuser EntityType" />