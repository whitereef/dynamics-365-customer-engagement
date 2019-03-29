---
title: "BookableResourceBookingExchangeSyncIdMapping Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the BookableResourceBookingExchangeSyncIdMapping entity."
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
# BookableResourceBookingExchangeSyncIdMapping Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]

The mapping used to keep track of the IDs for items synced between Dynamics 365 Bookable Resource Booking and Exchange.

**Added by**: Scheduling Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Create|POST [*org URI*]/api/data/v9.0/bookableresourcebookingexchangesyncidmappings<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/bookableresourcebookingexchangesyncidmappings(*bookableresourcebookingexchangesyncidmappingid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|Retrieve|GET [*org URI*]/api/data/v9.0/bookableresourcebookingexchangesyncidmappings(*bookableresourcebookingexchangesyncidmappingid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/bookableresourcebookingexchangesyncidmappings<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|Update|PATCH [*org URI*]/api/data/v9.0/bookableresourcebookingexchangesyncidmappings(*bookableresourcebookingexchangesyncidmappingid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|BookableResourceBookingExchangeSyncIdMappings|
|DisplayCollectionName|Bookable Resource Booking to Exchange Id Mappings|
|DisplayName|Bookable Resource Booking to Exchange Id Mapping|
|EntitySetName|bookableresourcebookingexchangesyncidmappings|
|IsBPFEntity|False|
|LogicalCollectionName|bookableresourcebookingexchangesyncidmappings|
|LogicalName|bookableresourcebookingexchangesyncidmapping|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|bookableresourcebookingexchangesyncidmappingid|
|PrimaryNameAttribute|name|
|SchemaName|BookableResourceBookingExchangeSyncIdMapping|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [BookableResourceBookingExchangeSyncIdMappingId](#BKMK_BookableResourceBookingExchangeSyncIdMappingId)
- [BookableResourceBookingId](#BKMK_BookableResourceBookingId)
- [ExchangeEntryId](#BKMK_ExchangeEntryId)
- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [IsDeletedInExchange](#BKMK_IsDeletedInExchange)
- [LastSyncError](#BKMK_LastSyncError)
- [LastSyncErrorCode](#BKMK_LastSyncErrorCode)
- [LastSyncErrorOccurredOn](#BKMK_LastSyncErrorOccurredOn)
- [Name](#BKMK_Name)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [Retries](#BKMK_Retries)
- [SyncStatus](#BKMK_SyncStatus)
- [SyncVersionNumber](#BKMK_SyncVersionNumber)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UserId](#BKMK_UserId)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_BookableResourceBookingExchangeSyncIdMappingId"></a> BookableResourceBookingExchangeSyncIdMappingId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|bookableresourcebookingexchangesyncidmappingid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_BookableResourceBookingId"></a> BookableResourceBookingId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|bookableresourcebookingid|
|RequiredLevel|None|
|Type|Uniqueidentifier|


### <a name="BKMK_ExchangeEntryId"></a> ExchangeEntryId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|exchangeentryid|
|MaxLength|1024|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|--------|-----|
|Description|Sequence number of the import that created this record.|
|DisplayName|Import Sequence Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|importsequencenumber|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_IsDeletedInExchange"></a> IsDeletedInExchange

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|isdeletedinexchange|
|RequiredLevel|None|
|Type|Boolean|

#### IsDeletedInExchange Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_LastSyncError"></a> LastSyncError

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|lastsyncerror|
|MaxLength|2048|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_LastSyncErrorCode"></a> LastSyncErrorCode

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|lastsyncerrorcode|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_LastSyncErrorOccurredOn"></a> LastSyncErrorOccurredOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Last Sync Error Time|
|DisplayName|Last Sync Error Time|
|Format|DateAndTime|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|lastsyncerroroccurredon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_Name"></a> Name

|Property|Value|
|--------|-----|
|Description|name|
|DisplayName|name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|name|
|MaxLength|100|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time that the record was migrated.|
|DisplayName|Record Created On|
|Format|DateOnly|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|overriddencreatedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|--------|-----|
|Description|Owner Id|
|DisplayName|Owner|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

**Added by**: Active Solution Solution

|Property|Value|
|--------|-----|
|Description|Owner Id Type|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_Retries"></a> Retries

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|retries|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_SyncStatus"></a> SyncStatus

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|syncstatus|
|RequiredLevel|None|
|Type|Picklist|

#### SyncStatus Options

|Value|Label|
|-----|-----|
|0|Completed|
|1|Retry|
|2|Pending|



### <a name="BKMK_SyncVersionNumber"></a> SyncVersionNumber

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|syncversionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|


### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Time Zone Rule Version Number|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timezoneruleversionnumber|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_UserId"></a> UserId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|userid|
|RequiredLevel|None|
|Targets||
|Type|Lookup|


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|--------|-----|
|Description|Time zone code that was in use when the record was created.|
|DisplayName|UTC Conversion Time Zone Code|
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|utcconversiontimezonecode|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the record.|
|DisplayName|Created By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByName"></a> CreatedByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the record.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who modified the record.|
|DisplayName|Modified By|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the record was modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who modified the record.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

|Property|Value|
|--------|-----|
|Description|Name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

|Property|Value|
|--------|-----|
|Description|Yomi name of the owner|
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

|Property|Value|
|--------|-----|
|Description|Unique identifier for the business unit that owns the record|
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
|Description|Unique identifier for the team that owns the record.|
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
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|--------|-----|
|Description|Version Number|
|DisplayName|Version Number|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [bookableresourcebookingexchangesyncidmapping_SyncErrors](#BKMK_bookableresourcebookingexchangesyncidmapping_SyncErrors)
- [bookableresourcebookingexchangesyncidmapping_AsyncOperations](#BKMK_bookableresourcebookingexchangesyncidmapping_AsyncOperations)
- [bookableresourcebookingexchangesyncidmapping_MailboxTrackingFolders](#BKMK_bookableresourcebookingexchangesyncidmapping_MailboxTrackingFolders)
- [bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas](#BKMK_bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas)
- [bookableresourcebookingexchangesyncidmapping_BulkDeleteFailures](#BKMK_bookableresourcebookingexchangesyncidmapping_BulkDeleteFailures)
- [bookableresourcebookingexchangesyncidmapping_PrincipalObjectAttributeAccesses](#BKMK_bookableresourcebookingexchangesyncidmapping_PrincipalObjectAttributeAccesses)


### <a name="BKMK_bookableresourcebookingexchangesyncidmapping_SyncErrors"></a> bookableresourcebookingexchangesyncidmapping_SyncErrors

**Added by**: System Solution Solution

Same as syncerror entity [bookableresourcebookingexchangesyncidmapping_SyncErrors](syncerror.md#BKMK_bookableresourcebookingexchangesyncidmapping_SyncErrors) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|syncerror|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|bookableresourcebookingexchangesyncidmapping_SyncErrors|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_bookableresourcebookingexchangesyncidmapping_AsyncOperations"></a> bookableresourcebookingexchangesyncidmapping_AsyncOperations

**Added by**: System Solution Solution

Same as asyncoperation entity [bookableresourcebookingexchangesyncidmapping_AsyncOperations](asyncoperation.md#BKMK_bookableresourcebookingexchangesyncidmapping_AsyncOperations) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|asyncoperation|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|bookableresourcebookingexchangesyncidmapping_AsyncOperations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_bookableresourcebookingexchangesyncidmapping_MailboxTrackingFolders"></a> bookableresourcebookingexchangesyncidmapping_MailboxTrackingFolders

**Added by**: System Solution Solution

Same as mailboxtrackingfolder entity [bookableresourcebookingexchangesyncidmapping_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_bookableresourcebookingexchangesyncidmapping_MailboxTrackingFolders) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|mailboxtrackingfolder|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|bookableresourcebookingexchangesyncidmapping_MailboxTrackingFolders|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas"></a> bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas

**Added by**: System Solution Solution

Same as userentityinstancedata entity [bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas](userentityinstancedata.md#BKMK_bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|userentityinstancedata|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_bookableresourcebookingexchangesyncidmapping_BulkDeleteFailures"></a> bookableresourcebookingexchangesyncidmapping_BulkDeleteFailures

**Added by**: System Solution Solution

Same as bulkdeletefailure entity [bookableresourcebookingexchangesyncidmapping_BulkDeleteFailures](bulkdeletefailure.md#BKMK_bookableresourcebookingexchangesyncidmapping_BulkDeleteFailures) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|bulkdeletefailure|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|bookableresourcebookingexchangesyncidmapping_BulkDeleteFailures|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_bookableresourcebookingexchangesyncidmapping_PrincipalObjectAttributeAccesses"></a> bookableresourcebookingexchangesyncidmapping_PrincipalObjectAttributeAccesses

**Added by**: System Solution Solution

Same as principalobjectattributeaccess entity [bookableresourcebookingexchangesyncidmapping_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_bookableresourcebookingexchangesyncidmapping_PrincipalObjectAttributeAccesses) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|principalobjectattributeaccess|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|bookableresourcebookingexchangesyncidmapping_PrincipalObjectAttributeAccesses|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [lk_bookableresourcebookingexchangesyncidmapping_createdby](#BKMK_lk_bookableresourcebookingexchangesyncidmapping_createdby)
- [lk_bookableresourcebookingexchangesyncidmapping_createdonbehalfby](#BKMK_lk_bookableresourcebookingexchangesyncidmapping_createdonbehalfby)
- [lk_bookableresourcebookingexchangesyncidmapping_modifiedby](#BKMK_lk_bookableresourcebookingexchangesyncidmapping_modifiedby)
- [lk_bookableresourcebookingexchangesyncidmapping_modifiedonbehalfby](#BKMK_lk_bookableresourcebookingexchangesyncidmapping_modifiedonbehalfby)
- [user_bookableresourcebookingexchangesyncidmapping](#BKMK_user_bookableresourcebookingexchangesyncidmapping)
- [team_bookableresourcebookingexchangesyncidmapping](#BKMK_team_bookableresourcebookingexchangesyncidmapping)
- [business_unit_bookableresourcebookingexchangesyncidmapping](#BKMK_business_unit_bookableresourcebookingexchangesyncidmapping)


### <a name="BKMK_lk_bookableresourcebookingexchangesyncidmapping_createdby"></a> lk_bookableresourcebookingexchangesyncidmapping_createdby

**Added by**: System Solution Solution

See systemuser Entity [lk_bookableresourcebookingexchangesyncidmapping_createdby](systemuser.md#BKMK_lk_bookableresourcebookingexchangesyncidmapping_createdby) One-To-Many relationship.

### <a name="BKMK_lk_bookableresourcebookingexchangesyncidmapping_createdonbehalfby"></a> lk_bookableresourcebookingexchangesyncidmapping_createdonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_bookableresourcebookingexchangesyncidmapping_createdonbehalfby](systemuser.md#BKMK_lk_bookableresourcebookingexchangesyncidmapping_createdonbehalfby) One-To-Many relationship.

### <a name="BKMK_lk_bookableresourcebookingexchangesyncidmapping_modifiedby"></a> lk_bookableresourcebookingexchangesyncidmapping_modifiedby

**Added by**: System Solution Solution

See systemuser Entity [lk_bookableresourcebookingexchangesyncidmapping_modifiedby](systemuser.md#BKMK_lk_bookableresourcebookingexchangesyncidmapping_modifiedby) One-To-Many relationship.

### <a name="BKMK_lk_bookableresourcebookingexchangesyncidmapping_modifiedonbehalfby"></a> lk_bookableresourcebookingexchangesyncidmapping_modifiedonbehalfby

**Added by**: System Solution Solution

See systemuser Entity [lk_bookableresourcebookingexchangesyncidmapping_modifiedonbehalfby](systemuser.md#BKMK_lk_bookableresourcebookingexchangesyncidmapping_modifiedonbehalfby) One-To-Many relationship.

### <a name="BKMK_user_bookableresourcebookingexchangesyncidmapping"></a> user_bookableresourcebookingexchangesyncidmapping

**Added by**: System Solution Solution

See systemuser Entity [user_bookableresourcebookingexchangesyncidmapping](systemuser.md#BKMK_user_bookableresourcebookingexchangesyncidmapping) One-To-Many relationship.

### <a name="BKMK_team_bookableresourcebookingexchangesyncidmapping"></a> team_bookableresourcebookingexchangesyncidmapping

**Added by**: System Solution Solution

See team Entity [team_bookableresourcebookingexchangesyncidmapping](team.md#BKMK_team_bookableresourcebookingexchangesyncidmapping) One-To-Many relationship.

### <a name="BKMK_business_unit_bookableresourcebookingexchangesyncidmapping"></a> business_unit_bookableresourcebookingexchangesyncidmapping

**Added by**: System Solution Solution

See businessunit Entity [business_unit_bookableresourcebookingexchangesyncidmapping](businessunit.md#BKMK_business_unit_bookableresourcebookingexchangesyncidmapping) One-To-Many relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.bookableresourcebookingexchangesyncidmapping?text=bookableresourcebookingexchangesyncidmapping EntityType" />