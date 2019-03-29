---
title: "ConnectionRoleAssociation Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the ConnectionRoleAssociation entity."
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
# ConnectionRoleAssociation Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]




## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/connectionroleassociations<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName||
|DisplayCollectionName||
|DisplayName||
|EntitySetName|connectionroleassociations|
|IsBPFEntity|False|
|LogicalCollectionName||
|LogicalName|connectionroleassociation|
|OwnershipType|None|
|PrimaryIdAttribute|connectionroleassociationid|
|PrimaryNameAttribute||
|SchemaName|ConnectionRoleAssociation|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [AssociatedConnectionRoleId](#BKMK_AssociatedConnectionRoleId)
- [ConnectionRoleAssociationId](#BKMK_ConnectionRoleAssociationId)
- [ConnectionRoleId](#BKMK_ConnectionRoleId)


### <a name="BKMK_AssociatedConnectionRoleId"></a> AssociatedConnectionRoleId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|associatedconnectionroleid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ConnectionRoleAssociationId"></a> ConnectionRoleAssociationId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the connection role association.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|connectionroleassociationid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ConnectionRoleId"></a> ConnectionRoleId

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|connectionroleid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.


### <a name="BKMK_VersionNumber"></a> VersionNumber

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

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.


### <a name="BKMK_userentityinstancedata_connectionroleassociation"></a> userentityinstancedata_connectionroleassociation

Same as userentityinstancedata entity [userentityinstancedata_connectionroleassociation](userentityinstancedata.md#BKMK_userentityinstancedata_connectionroleassociation) Many-To-One relationship.

|Property|Value|
|--------|-----|
|ReferencingEntity|userentityinstancedata|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|userentityinstancedata_connectionroleassociation|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytomany"></a>

## Many-To-Many Relationships

Relationship details provided where the ConnectionRoleAssociation entity is the first entity in the relationship. Listed by **SchemaName**.


### <a name="BKMK_connectionroleassociation_association"></a> connectionroleassociation_association

See connectionrole Entity [connectionroleassociation_association](connectionrole.md#BKMK_connectionroleassociation_association) Many-To-Many Relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.connectionroleassociation?text=connectionroleassociation EntityType" />