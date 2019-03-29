---
title: "HierarchySecurityConfiguration Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the HierarchySecurityConfiguration entity."
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
# HierarchySecurityConfiguration Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]




## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Create|POST [*org URI*]/api/data/v9.0/hierarchysecurityconfigurations<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/hierarchysecurityconfigurations(*hierarchysecuritymodelingsettingid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/hierarchysecurityconfigurations<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|HierarchySecurityConfiguration|
|DisplayCollectionName|Hierarchy Security Configurations|
|DisplayName|Hierarchy Security Configuration|
|EntitySetName|hierarchysecurityconfigurations|
|IsBPFEntity|False|
|LogicalCollectionName|hierarchysecurityconfigurations|
|LogicalName|hierarchysecurityconfiguration|
|OwnershipType|None|
|PrimaryIdAttribute|hierarchysecuritymodelingsettingid|
|PrimaryNameAttribute||
|SchemaName|HierarchySecurityConfiguration|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [EntityName](#BKMK_EntityName)
- [HierarchySecurityModelingSettingId](#BKMK_HierarchySecurityModelingSettingId)
- [ObjectTypeCode](#BKMK_ObjectTypeCode)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_EntityName"></a> EntityName

|Property|Value|
|--------|-----|
|Description|Logical entity name of the entity that is configured for hierarchy security.|
|DisplayName|Entity Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|entityname|
|MaxLength|64|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_HierarchySecurityModelingSettingId"></a> HierarchySecurityModelingSettingId

|Property|Value|
|--------|-----|
|Description|Shows the entity used for the Hierarchy Security Modeling Configuration.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|hierarchysecuritymodelingsettingid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ObjectTypeCode"></a> ObjectTypeCode

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|objecttypecode|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|



### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.hierarchysecurityconfiguration?text=hierarchysecurityconfiguration EntityType" />