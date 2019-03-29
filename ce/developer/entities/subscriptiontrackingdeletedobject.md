---
title: "SubscriptionTrackingDeletedObject Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the SubscriptionTrackingDeletedObject entity."
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
# SubscriptionTrackingDeletedObject Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]

For internal use only.


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/subscriptiontrackingdeletedobjects<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|SubscriptionTrackingDeletedObjects|
|DisplayCollectionName|Tracking information for deleted entities|
|DisplayName|Tracking information for deleted entities|
|EntitySetName|subscriptiontrackingdeletedobjects|
|IsBPFEntity|False|
|LogicalCollectionName|subscriptiontrackingdeletedobjects|
|LogicalName|subscriptiontrackingdeletedobject|
|OwnershipType|None|
|PrimaryIdAttribute|timestamp|
|PrimaryNameAttribute||
|SchemaName|SubscriptionTrackingDeletedObject|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [DeleteTime](#BKMK_DeleteTime)
- [IsLogicalDelete](#BKMK_IsLogicalDelete)


### <a name="BKMK_DeleteTime"></a> DeleteTime

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Shows the date and time when the record was created. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|deletetime|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_IsLogicalDelete"></a> IsLogicalDelete

|Property|Value|
|--------|-----|
|Description|Indicates whether solution aware entity record is logical delete or not|
|DisplayName|Is Logical Delete|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|islogicaldelete|
|RequiredLevel|None|
|Type|Boolean|

#### IsLogicalDelete Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False


<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [ObjectId](#BKMK_ObjectId)
- [ObjectTypeCode](#BKMK_ObjectTypeCode)
- [TimeStamp](#BKMK_TimeStamp)


### <a name="BKMK_ObjectId"></a> ObjectId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|objectid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ObjectTypeCode"></a> ObjectTypeCode

|Property|Value|
|--------|-----|
|Description|Type of entity that was deleted.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|objecttypecode|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_TimeStamp"></a> TimeStamp

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timestamp|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|SystemRequired|
|Type|BigInt|



### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.subscriptiontrackingdeletedobject?text=subscriptiontrackingdeletedobject EntityType" />