---
title: "MailboxTrackingCategory Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the MailboxTrackingCategory entity."
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
# MailboxTrackingCategory Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]

Stores data about what categories for a mailbox are tracked


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Create|POST [*org URI*]/api/data/v9.0/mailboxtrackingcategories<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/mailboxtrackingcategories(*mailboxtrackingcategoryid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|Retrieve|GET [*org URI*]/api/data/v9.0/mailboxtrackingcategories(*mailboxtrackingcategoryid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/mailboxtrackingcategories<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|Update|PATCH [*org URI*]/api/data/v9.0/mailboxtrackingcategories(*mailboxtrackingcategoryid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|MailboxTrackingCategories|
|DisplayCollectionName|Mailbox Tracking Categories|
|DisplayName|Mailbox Tracking Category|
|EntitySetName|mailboxtrackingcategories|
|IsBPFEntity|False|
|LogicalCollectionName|mailboxtrackingcategories|
|LogicalName|mailboxtrackingcategory|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|mailboxtrackingcategoryid|
|PrimaryNameAttribute||
|SchemaName|MailboxTrackingCategory|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [CategoryOnboardingStatus](#BKMK_CategoryOnboardingStatus)
- [ExchangeCategoryColor](#BKMK_ExchangeCategoryColor)
- [ExchangeCategoryId](#BKMK_ExchangeCategoryId)
- [ExchangeCategoryName](#BKMK_ExchangeCategoryName)
- [MailboxId](#BKMK_MailboxId)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)


### <a name="BKMK_CategoryOnboardingStatus"></a> CategoryOnboardingStatus

|Property|Value|
|--------|-----|
|Description|Information to indicate whether the category has been created in Exchange or not.|
|DisplayName|Category on boarding Status|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|categoryonboardingstatus|
|MaxValue|2147483647|
|MinValue|0|
|RequiredLevel|SystemRequired|
|Type|Integer|


### <a name="BKMK_ExchangeCategoryColor"></a> ExchangeCategoryColor

|Property|Value|
|--------|-----|
|Description|Color for category in Exchange.|
|DisplayName|Color for category in Exchange.|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|exchangecategorycolor|
|MaxValue|25|
|MinValue|0|
|RequiredLevel|SystemRequired|
|Type|Integer|


### <a name="BKMK_ExchangeCategoryId"></a> ExchangeCategoryId

|Property|Value|
|--------|-----|
|Description|Category Id for a category in Exchange|
|DisplayName|Exchange Category Id|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|exchangecategoryid|
|RequiredLevel|None|
|Type|Uniqueidentifier|


### <a name="BKMK_ExchangeCategoryName"></a> ExchangeCategoryName

|Property|Value|
|--------|-----|
|Description|Exchange Category Name|
|DisplayName|Exchange Category Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|exchangecategoryname|
|MaxLength|512|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_MailboxId"></a> MailboxId

|Property|Value|
|--------|-----|
|Description|Mailbox id associated with this record.|
|DisplayName|MailboxId|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|mailboxid|
|RequiredLevel|SystemRequired|
|Targets|organization|
|Type|Lookup|


### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|--------|-----|
|Description|Enter the user or team who is assigned to manage the record. This field is updated every time the record is assigned to a different user.|
|DisplayName|Owner|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|owner|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedOn](#BKMK_CreatedOn)
- [MailboxTrackingCategoryId](#BKMK_MailboxTrackingCategoryId)
- [ModifiedOn](#BKMK_ModifiedOn)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the entry was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_MailboxTrackingCategoryId"></a> MailboxTrackingCategoryId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|mailboxtrackingcategoryid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the entry was last modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

|Property|Value|
|--------|-----|
|Description|Unique identifier of the business unit that owns the category.|
|DisplayName|Owning Business Unit|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningbusinessunit|
|RequiredLevel|None|
|Targets|businessunit|
|Type|Lookup|


### <a name="BKMK_OwningTeam"></a> OwningTeam

|Property|Value|
|--------|-----|
|Description|Unique identifier of the team who owns the category.|
|DisplayName|Owning Team|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningteam|
|RequiredLevel|None|
|Targets|team|
|Type|Lookup|


### <a name="BKMK_OwningUser"></a> OwningUser

|Property|Value|
|--------|-----|
|Description|Unique identifier for the user that owns the record.|
|DisplayName|Owning User|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owninguser|
|RequiredLevel|None|
|Targets||
|Type|Lookup|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [businessunit_mailboxtrackingcategory](#BKMK_businessunit_mailboxtrackingcategory)
- [Mailbox_mailboxtrackingcategory](#BKMK_Mailbox_mailboxtrackingcategory)
- [team_mailboxtrackingcategory](#BKMK_team_mailboxtrackingcategory)


### <a name="BKMK_businessunit_mailboxtrackingcategory"></a> businessunit_mailboxtrackingcategory

See businessunit Entity [businessunit_mailboxtrackingcategory](businessunit.md#BKMK_businessunit_mailboxtrackingcategory) One-To-Many relationship.

### <a name="BKMK_Mailbox_mailboxtrackingcategory"></a> Mailbox_mailboxtrackingcategory

See mailbox Entity [Mailbox_mailboxtrackingcategory](mailbox.md#BKMK_Mailbox_mailboxtrackingcategory) One-To-Many relationship.

### <a name="BKMK_team_mailboxtrackingcategory"></a> team_mailboxtrackingcategory

See team Entity [team_mailboxtrackingcategory](team.md#BKMK_team_mailboxtrackingcategory) One-To-Many relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.mailboxtrackingcategory?text=mailboxtrackingcategory EntityType" />