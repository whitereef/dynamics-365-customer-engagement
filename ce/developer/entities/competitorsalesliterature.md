---
title: "CompetitorSalesLiterature Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the CompetitorSalesLiterature entity."
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
# CompetitorSalesLiterature Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]



**Added by**: Sales Solution


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/competitorsalesliteratures<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName||
|DisplayCollectionName|CompetitorSalesLiterature|
|DisplayName|CompetitorSalesLiterature|
|EntitySetName|competitorsalesliteratures|
|IsBPFEntity|False|
|LogicalCollectionName||
|LogicalName|competitorsalesliterature|
|OwnershipType|None|
|PrimaryIdAttribute|competitorsalesliteratureid|
|PrimaryNameAttribute|name|
|SchemaName|CompetitorSalesLiterature|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [CompetitorSalesLiteratureId](#BKMK_CompetitorSalesLiteratureId)
- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [Name](#BKMK_Name)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_CompetitorSalesLiteratureId"></a> CompetitorSalesLiteratureId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the sales literature for the competitor product.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|competitorsalesliteratureid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


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

- [CompetitorId](#BKMK_CompetitorId)
- [SalesLiteratureId](#BKMK_SalesLiteratureId)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CompetitorId"></a> CompetitorId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|competitorid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_SalesLiteratureId"></a> SalesLiteratureId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|salesliteratureid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


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

- [competitorsalesliterature_AsyncOperations](#BKMK_competitorsalesliterature_AsyncOperations)
- [competitorsalesliterature_MailboxTrackingFolders](#BKMK_competitorsalesliterature_MailboxTrackingFolders)
- [competitorsalesliterature_UserEntityInstanceDatas](#BKMK_competitorsalesliterature_UserEntityInstanceDatas)
- [competitorsalesliterature_BulkDeleteFailures](#BKMK_competitorsalesliterature_BulkDeleteFailures)
- [competitorsalesliterature_PrincipalObjectAttributeAccesses](#BKMK_competitorsalesliterature_PrincipalObjectAttributeAccesses)
- [userentityinstancedata_competitorsalesliterature](#BKMK_userentityinstancedata_competitorsalesliterature)


### <a name="BKMK_competitorsalesliterature_AsyncOperations"></a> competitorsalesliterature_AsyncOperations

**Added by**: System Solution Solution

Same as asyncoperation entity [competitorsalesliterature_AsyncOperations](asyncoperation.md#BKMK_competitorsalesliterature_AsyncOperations) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|asyncoperation|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|competitorsalesliterature_AsyncOperations|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: NoCascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_competitorsalesliterature_MailboxTrackingFolders"></a> competitorsalesliterature_MailboxTrackingFolders

**Added by**: System Solution Solution

Same as mailboxtrackingfolder entity [competitorsalesliterature_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_competitorsalesliterature_MailboxTrackingFolders) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|mailboxtrackingfolder|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|competitorsalesliterature_MailboxTrackingFolders|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_competitorsalesliterature_UserEntityInstanceDatas"></a> competitorsalesliterature_UserEntityInstanceDatas

**Added by**: System Solution Solution

Same as userentityinstancedata entity [competitorsalesliterature_UserEntityInstanceDatas](userentityinstancedata.md#BKMK_competitorsalesliterature_UserEntityInstanceDatas) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|userentityinstancedata|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|competitorsalesliterature_UserEntityInstanceDatas|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_competitorsalesliterature_BulkDeleteFailures"></a> competitorsalesliterature_BulkDeleteFailures

**Added by**: System Solution Solution

Same as bulkdeletefailure entity [competitorsalesliterature_BulkDeleteFailures](bulkdeletefailure.md#BKMK_competitorsalesliterature_BulkDeleteFailures) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|bulkdeletefailure|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|competitorsalesliterature_BulkDeleteFailures|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_competitorsalesliterature_PrincipalObjectAttributeAccesses"></a> competitorsalesliterature_PrincipalObjectAttributeAccesses

**Added by**: System Solution Solution

Same as principalobjectattributeaccess entity [competitorsalesliterature_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_competitorsalesliterature_PrincipalObjectAttributeAccesses) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|principalobjectattributeaccess|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|competitorsalesliterature_PrincipalObjectAttributeAccesses|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_userentityinstancedata_competitorsalesliterature"></a> userentityinstancedata_competitorsalesliterature

**Added by**: System Solution Solution

Same as userentityinstancedata entity [userentityinstancedata_competitorsalesliterature](userentityinstancedata.md#BKMK_userentityinstancedata_competitorsalesliterature) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|userentityinstancedata|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|userentityinstancedata_competitorsalesliterature|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytomany"></a>

## Many-To-Many Relationships

Relationship details provided where the CompetitorSalesLiterature entity is the first entity in the relationship. Listed by **SchemaName**.


### <a name="BKMK_competitorsalesliterature_association"></a> competitorsalesliterature_association

See salesliterature Entity [competitorsalesliterature_association](salesliterature.md#BKMK_competitorsalesliterature_association) Many-To-Many Relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.competitorsalesliterature?text=competitorsalesliterature EntityType" />