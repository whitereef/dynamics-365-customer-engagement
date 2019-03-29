---
title: "msdyn_callablecontext_msdyn_playbooktemplate Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_callablecontext_msdyn_playbooktemplate entity."
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
# msdyn_callablecontext_msdyn_playbooktemplate Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]



**Added by**: Playbook Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_callablecontext_msdyn_playbooktemplateset<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName||
|DisplayCollectionName||
|DisplayName||
|EntitySetName|msdyn_callablecontext_msdyn_playbooktemplateset|
|IsBPFEntity|False|
|LogicalCollectionName||
|LogicalName|msdyn_callablecontext_msdyn_playbooktemplate|
|OwnershipType|None|
|PrimaryIdAttribute|msdyn_callablecontext_msdyn_playbooktemplateid|
|PrimaryNameAttribute||
|SchemaName|msdyn_callablecontext_msdyn_playbooktemplate|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [msdyn_callablecontext_msdyn_playbooktemplateId](#BKMK_msdyn_callablecontext_msdyn_playbooktemplateId)
- [msdyn_callablecontextid](#BKMK_msdyn_callablecontextid)
- [msdyn_playbooktemplateid](#BKMK_msdyn_playbooktemplateid)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_msdyn_callablecontext_msdyn_playbooktemplateId"></a> msdyn_callablecontext_msdyn_playbooktemplateId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_callablecontext_msdyn_playbooktemplateid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_callablecontextid"></a> msdyn_callablecontextid

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_callablecontextid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_playbooktemplateid"></a> msdyn_playbooktemplateid

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_playbooktemplateid|
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

Relationship details provided where the msdyn_callablecontext_msdyn_playbooktemplate entity is the first entity in the relationship. Listed by **SchemaName**.


### <a name="BKMK_msdyn_callablecontext_msdyn_playbooktemplate"></a> msdyn_callablecontext_msdyn_playbooktemplate

See msdyn_callablecontext Entity [msdyn_callablecontext_msdyn_playbooktemplate](msdyn_callablecontext.md#BKMK_msdyn_callablecontext_msdyn_playbooktemplate) Many-To-Many Relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_callablecontext_msdyn_playbooktemplate?text=msdyn_callablecontext_msdyn_playbooktemplate EntityType" />