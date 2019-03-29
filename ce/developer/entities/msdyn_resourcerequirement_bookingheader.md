---
title: "msdyn_resourcerequirement_bookingheader Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_resourcerequirement_bookingheader entity."
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
# msdyn_resourcerequirement_bookingheader Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]



**Added by**: Project Service Automation Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_resourcerequirement_bookingheaderset<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName||
|DisplayCollectionName||
|DisplayName||
|EntitySetName|msdyn_resourcerequirement_bookingheaderset|
|IsBPFEntity|False|
|LogicalCollectionName||
|LogicalName|msdyn_resourcerequirement_bookingheader|
|OwnershipType|None|
|PrimaryIdAttribute|msdyn_resourcerequirement_bookingheaderid|
|PrimaryNameAttribute||
|SchemaName|msdyn_resourcerequirement_bookingheader|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [bookableresourcebookingheaderid](#BKMK_bookableresourcebookingheaderid)
- [msdyn_resourcerequirement_bookingheaderId](#BKMK_msdyn_resourcerequirement_bookingheaderId)
- [msdyn_resourcerequirementid](#BKMK_msdyn_resourcerequirementid)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_bookableresourcebookingheaderid"></a> bookableresourcebookingheaderid

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|bookableresourcebookingheaderid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_resourcerequirement_bookingheaderId"></a> msdyn_resourcerequirement_bookingheaderId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_resourcerequirement_bookingheaderid|
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

Relationship details provided where the msdyn_resourcerequirement_bookingheader entity is the first entity in the relationship. Listed by **SchemaName**.


### <a name="BKMK_msdyn_resourcerequirement_bookingheader"></a> msdyn_resourcerequirement_bookingheader

See msdyn_resourcerequirement Entity [msdyn_resourcerequirement_bookingheader](msdyn_resourcerequirement.md#BKMK_msdyn_resourcerequirement_bookingheader) Many-To-Many Relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_resourcerequirement_bookingheader?text=msdyn_resourcerequirement_bookingheader EntityType" />