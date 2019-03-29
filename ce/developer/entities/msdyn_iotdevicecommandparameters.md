---
title: "msdyn_iotdevicecommandparameters Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_iotdevicecommandparameters entity."
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
# msdyn_iotdevicecommandparameters Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]



**Added by**: IoT Connector for Microsoft Dynamics 365 Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_iotdevicecommandparametersset<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName||
|DisplayCollectionName||
|DisplayName||
|EntitySetName|msdyn_iotdevicecommandparametersset|
|IsBPFEntity|False|
|LogicalCollectionName||
|LogicalName|msdyn_iotdevicecommandparameters|
|OwnershipType|None|
|PrimaryIdAttribute|msdyn_iotdevicecommandparametersid|
|PrimaryNameAttribute||
|SchemaName|msdyn_iotdevicecommandparameters|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [msdyn_iotdevicecommanddefinitionid](#BKMK_msdyn_iotdevicecommanddefinitionid)
- [msdyn_iotdevicecommandparametersId](#BKMK_msdyn_iotdevicecommandparametersId)
- [msdyn_iotpropertydefinitionid](#BKMK_msdyn_iotpropertydefinitionid)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_msdyn_iotdevicecommanddefinitionid"></a> msdyn_iotdevicecommanddefinitionid

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_iotdevicecommanddefinitionid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_iotdevicecommandparametersId"></a> msdyn_iotdevicecommandparametersId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_iotdevicecommandparametersid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_msdyn_iotpropertydefinitionid"></a> msdyn_iotpropertydefinitionid

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|msdyn_iotpropertydefinitionid|
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

Relationship details provided where the msdyn_iotdevicecommandparameters entity is the first entity in the relationship. Listed by **SchemaName**.


### <a name="BKMK_msdyn_iotdevicecommandparameters"></a> msdyn_iotdevicecommandparameters

See msdyn_iotdevicecommanddefinition Entity [msdyn_iotdevicecommandparameters](msdyn_iotdevicecommanddefinition.md#BKMK_msdyn_iotdevicecommandparameters) Many-To-Many Relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_iotdevicecommandparameters?text=msdyn_iotdevicecommandparameters EntityType" />