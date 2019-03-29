---
title: "UserEntityInstanceData Entity Reference (Dynamics 365 for Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the UserEntityInstanceData entity."
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
# UserEntityInstanceData Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]

Per User item instance data


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Create|POST [*org URI*]/api/data/v9.0/userentityinstancedataset<br />See [Create](/powerapps/developer/common-data-service/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/userentityinstancedataset(*userentityinstancedataid*)<br />See [Delete](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|Retrieve|GET [*org URI*]/api/data/v9.0/userentityinstancedataset(*userentityinstancedataid*)<br />See [Retrieve](/powerapps/developer/common-data-service/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/userentityinstancedataset<br />See [Query Data](/powerapps/developer/common-data-service/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|Update|PATCH [*org URI*]/api/data/v9.0/userentityinstancedataset(*userentityinstancedataid*)<br />See [Update](/powerapps/developer/common-data-service/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|UserEntityInstanceDatas|
|DisplayCollectionName|User Entity Instance Data|
|DisplayName|User Entity Instance Data|
|EntitySetName|userentityinstancedataset|
|IsBPFEntity|False|
|LogicalCollectionName|userentityinstancedatas|
|LogicalName|userentityinstancedata|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|userentityinstancedataid|
|PrimaryNameAttribute||
|SchemaName|UserEntityInstanceData|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [CommonEnd](#BKMK_CommonEnd)
- [CommonStart](#BKMK_CommonStart)
- [DueDate](#BKMK_DueDate)
- [FlagDueBy](#BKMK_FlagDueBy)
- [FlagRequest](#BKMK_FlagRequest)
- [FlagStatus](#BKMK_FlagStatus)
- [ObjectId](#BKMK_ObjectId)
- [ObjectTypeCode](#BKMK_ObjectTypeCode)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [PersonalCategories](#BKMK_PersonalCategories)
- [ReminderSet](#BKMK_ReminderSet)
- [ReminderTime](#BKMK_ReminderTime)
- [StartTime](#BKMK_StartTime)
- [ToDoItemFlags](#BKMK_ToDoItemFlags)
- [ToDoOrdinalDate](#BKMK_ToDoOrdinalDate)
- [ToDoSubOrdinal](#BKMK_ToDoSubOrdinal)
- [ToDoTitle](#BKMK_ToDoTitle)
- [UserEntityInstanceDataId](#BKMK_UserEntityInstanceDataId)


### <a name="BKMK_CommonEnd"></a> CommonEnd

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Common end date|
|DisplayName|Common end date|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|commonend|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CommonStart"></a> CommonStart

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Common start date|
|DisplayName|Common start date|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|commonstart|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_DueDate"></a> DueDate

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Due Date|
|DisplayName|Due Date|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|duedate|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_FlagDueBy"></a> FlagDueBy

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Flag due by|
|DisplayName|Flag due by|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|flagdueby|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_FlagRequest"></a> FlagRequest

|Property|Value|
|--------|-----|
|Description|Flag request|
|DisplayName|Flag Request|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|flagrequest|
|MaxLength|20|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_FlagStatus"></a> FlagStatus

|Property|Value|
|--------|-----|
|Description|Flag status.|
|DisplayName||
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|flagstatus|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_ObjectId"></a> ObjectId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the source record.|
|DisplayName|Object Id|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|objectid|
|RequiredLevel|SystemRequired|
|Targets|account,accountleads,activitymimeattachment,activityparty,adminsettingsentity,annotation,appointment,asyncoperation,attachment,attributemap,audit,bookableresource,bookableresourcebooking,bookableresourcebookingexchangesyncidmapping,bookableresourcebookingheader,bookableresourcecategory,bookableresourcecategoryassn,bookableresourcecharacteristic,bookableresourcegroup,bookingstatus,bulkdeletefailure,bulkdeleteoperation,bulkoperation,bulkoperationlog,businessunitmap,businessunitnewsarticle,calendar,calendarrule,campaign,campaignactivity,campaignactivityitem,campaignitem,campaignresponse,channelaccessprofile,channelaccessprofilerule,characteristic,childincidentcount,clientupdate,columnmapping,commitment,competitor,competitoraddress,competitorproduct,competitorsalesliterature,connection,connectionrole,connectionroleassociation,connectionroleobjecttypecode,constraintbasedgroup,contact,contactinvoices,contactleads,contactorders,contactquotes,contract,contractdetail,contracttemplate,convertrule,customeraddress,customeropportunityrole,customerrelationship,dependency,dependencynode,discount,discounttype,displaystring,displaystringmap,documentindex,duplicaterecord,duplicaterule,duplicaterulecondition,dynamicproperty,dynamicpropertyassociation,dynamicpropertyinstance,dynamicpropertyoptionsetitem,email,emailhash,emailsearch,entitlement,entitlementchannel,entitlementcontacts,entitlemententityallocationtypemapping,entitlementproducts,entitlementtemplate,entitlementtemplatechannel,entitlementtemplateproducts,entitymap,equipment,externalparty,fax,fieldpermission,fieldsecurityprofile,fileattachment,filtertemplate,goal,goalrollupquery,holidaywrapper,import,importdata,importentitymapping,importfile,importjob,importlog,importmap,incident,incidentknowledgebaserecord,incidentresolution,internaladdress,invaliddependency,invoice,invoicedetail,isvconfig,kbarticle,kbarticlecomment,kbarticletemplate,knowledgearticle,knowledgearticleincident,knowledgebaserecord,lead,leadaddress,leadcompetitors,leadproduct,leadtoopportunitysalesprocess,letter,license,list,listmember,lookupmapping,mailbox,mailmergetemplate,metric,msdynsm_marketingsitemap,msdynsm_salessitemap,msdynsm_servicessitemap,msdynsm_settingssitemap,msdyn_3dmodel,msdyn_accountpricelist,msdyn_actual,msdyn_agreement,msdyn_agreementbookingdate,msdyn_agreementbookingincident,msdyn_agreementbookingproduct,msdyn_agreementbookingservice,msdyn_agreementbookingservicetask,msdyn_agreementbookingsetup,msdyn_agreementinvoicedate,msdyn_agreementinvoiceproduct,msdyn_agreementinvoicesetup,msdyn_agreementsubstatus,msdyn_analysiscomponent,msdyn_analysisjob,msdyn_analysisresult,msdyn_analysisresultdetail,msdyn_approval,msdyn_batchjob,msdyn_bookableresourceassociation,msdyn_bookingalert,msdyn_bookingalertstatus,msdyn_bookingchange,msdyn_bookingjournal,msdyn_bookingrule,msdyn_bookingsetupmetadata,msdyn_bookingtimestamp,msdyn_bpf_2c5fe86acc8b414b8322ae571000c799,msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b,msdyn_bpf_665e73aa18c247d886bfc50499c73b82,msdyn_bpf_989e9b1857e24af18787d5143b67523b,msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3,msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39,msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d,msdyn_businessclosure,msdyn_callablecontext,msdyn_characteristicreqforteammember,msdyn_clientextension,msdyn_configuration,msdyn_contactpricelist,msdyn_contractlineinvoiceschedule,msdyn_contractlinescheduleofvalue,msdyn_customerasset,msdyn_customerassetcategory,msdyn_databaseversion,msdyn_dataexport,msdyn_delegation,msdyn_dimension,msdyn_dimensionfieldname,msdyn_entitlementapplication,msdyn_entityconfiguration,msdyn_estimate,msdyn_estimateline,msdyn_expense,msdyn_expensecategory,msdyn_expensereceipt,msdyn_fact,msdyn_fieldcomputation,msdyn_fieldservicepricelistitem,msdyn_fieldservicesetting,msdyn_fieldserviceslaconfiguration,msdyn_fieldservicesystemjob,msdyn_findworkevent,msdyn_forecastdefinition,msdyn_forecastinstance,msdyn_forecastrecurrence,msdyn_geofence,msdyn_geofenceevent,msdyn_geofencingsettings,msdyn_icebreakersconfig,msdyn_incidenttype,msdyn_incidenttypecharacteristic,msdyn_incidenttypeproduct,msdyn_incidenttypeservice,msdyn_incidenttypeservicetask,msdyn_incidenttypessetup,msdyn_incidenttype_requirementgroup,msdyn_integrationjob,msdyn_integrationjobdetail,msdyn_inventoryadjustment,msdyn_inventoryadjustmentproduct,msdyn_inventoryjournal,msdyn_inventorytransfer,msdyn_invoicefrequency,msdyn_invoicefrequencydetail,msdyn_invoicelinetransaction,msdyn_iotalert,msdyn_iotdevice,msdyn_iotdevicecategory,msdyn_iotdevicecommand,msdyn_iotdevicecommanddefinition,msdyn_iotdevicedatahistory,msdyn_iotdeviceproperty,msdyn_iotdeviceregistrationhistory,msdyn_iotpropertydefinition,msdyn_iotsettings,msdyn_journal,msdyn_journalline,msdyn_mlresultcache,msdyn_notesanalysisconfig,msdyn_opportunitylineresourcecategory,msdyn_opportunitylinetransaction,msdyn_opportunitylinetransactioncategory,msdyn_opportunitylinetransactionclassificatio,msdyn_opportunitypricelist,msdyn_orderinvoicingdate,msdyn_orderinvoicingproduct,msdyn_orderinvoicingsetup,msdyn_orderinvoicingsetupdate,msdyn_orderlineresourcecategory,msdyn_orderlinetransaction,msdyn_orderlinetransactioncategory,msdyn_orderlinetransactionclassification,msdyn_orderpricelist,msdyn_organizationalunit,msdyn_payment,msdyn_paymentdetail,msdyn_paymentmethod,msdyn_paymentterm,msdyn_playbookactivity,msdyn_playbookactivityattribute,msdyn_playbookcategory,msdyn_playbookinstance,msdyn_playbooktemplate,msdyn_postalbum,msdyn_postalcode,msdyn_postconfig,msdyn_postruleconfig,msdyn_priority,msdyn_processnotes,msdyn_productinventory,msdyn_project,msdyn_projectapproval,msdyn_projectparameter,msdyn_projectparameterpricelist,msdyn_projectpricelist,msdyn_projecttask,msdyn_projecttaskdependency,msdyn_projecttaskstatususer,msdyn_projectteam,msdyn_projectteammembersignup,msdyn_projecttransactioncategory,msdyn_purchaseorder,msdyn_purchaseorderbill,msdyn_purchaseorderproduct,msdyn_purchaseorderreceipt,msdyn_purchaseorderreceiptproduct,msdyn_purchaseordersubstatus,msdyn_quotebookingincident,msdyn_quotebookingproduct,msdyn_quotebookingservice,msdyn_quotebookingservicetask,msdyn_quotebookingsetup,msdyn_quoteinvoicingproduct,msdyn_quoteinvoicingsetup,msdyn_quotelineanalyticsbreakdown,msdyn_quotelineinvoiceschedule,msdyn_quotelineresourcecategory,msdyn_quotelinescheduleofvalue,msdyn_quotelinetransaction,msdyn_quotelinetransactioncategory,msdyn_quotelinetransactionclassification,msdyn_quotepricelist,msdyn_relationshipinsightsunifiedconfig,msdyn_requirementcharacteristic,msdyn_requirementgroup,msdyn_requirementorganizationunit,msdyn_requirementrelationship,msdyn_requirementresourcecategory,msdyn_requirementresourcepreference,msdyn_requirementstatus,msdyn_resourceassignment,msdyn_resourceassignmentdetail,msdyn_resourcecategorymarkuppricelevel,msdyn_resourcecategorypricelevel,msdyn_resourcepaytype,msdyn_resourcerequest,msdyn_resourcerequirement,msdyn_resourcerequirementdetail,msdyn_resourceterritory,msdyn_rma,msdyn_rmaproduct,msdyn_rmareceipt,msdyn_rmareceiptproduct,msdyn_rmasubstatus,msdyn_rolecompetencyrequirement,msdyn_roleutilization,msdyn_rtv,msdyn_rtvproduct,msdyn_rtvsubstatus,msdyn_scheduleboardsetting,msdyn_schedulingparameter,msdyn_servicetasktype,msdyn_shipvia,msdyn_siconfig,msdyn_solutionhealthrule,msdyn_solutionhealthruleargument,msdyn_solutionhealthruleset,msdyn_systemuserschedulersetting,msdyn_taxcode,msdyn_taxcodedetail,msdyn_teamscollaboration,msdyn_timeentry,msdyn_timegroup,msdyn_timegroupdetail,msdyn_timeoffcalendar,msdyn_timeoffrequest,msdyn_transactioncategory,msdyn_transactioncategoryclassification,msdyn_transactioncategoryhierarchyelement,msdyn_transactioncategorypricelevel,msdyn_transactionconnection,msdyn_transactionorigin,msdyn_transactiontype,msdyn_uniquenumber,msdyn_untrackedappointment,msdyn_upgraderun,msdyn_upgradestep,msdyn_upgradeversion,msdyn_userworkhistory,msdyn_wallsavedquery,msdyn_wallsavedqueryusersettings,msdyn_warehouse,msdyn_workhourtemplate,msdyn_workorder,msdyn_workordercharacteristic,msdyn_workorderdetailsgenerationqueue,msdyn_workorderincident,msdyn_workorderproduct,msdyn_workorderresourcerestriction,msdyn_workorderservice,msdyn_workorderservicetask,msdyn_workordersubstatus,msdyn_workordertype,msfp_emailtemplate,msfp_question,msfp_questionresponse,msfp_survey,msfp_surveyinvite,msfp_surveyresponse,msfp_unsubscribedrecipient,notification,opportunity,opportunityclose,opportunitycompetitors,opportunityproduct,opportunitysalesprocess,orderclose,organization,organizationstatistic,ownermapping,phonecall,phonetocaseprocess,picklistmapping,pluginassembly,plugintype,plugintypestatistic,pricelevel,principalattributeaccessmap,principalentitymap,principalobjectaccess,principalobjectattributeaccess,privilege,processsession,product,productassociation,productpricelevel,productsalesliterature,productsubstitute,publisher,publisheraddress,queue,queueitem,quote,quoteclose,quotedetail,ratingmodel,ratingvalue,recurringappointmentmaster,relationshiprole,relationshiprolemap,report,reportcategory,reportentity,reportlink,reportvisibility,resource,resourcegroup,resourcegroupexpansion,resourcespec,ribboncommand,ribboncontextgroup,ribboncustomization,ribbondiff,ribbonrule,ribbontabtocommandmap,role,roletemplate,rollupfield,routingrule,routingruleitem,salesliterature,salesliteratureitem,salesorder,salesorderdetail,salesprocessinstance,savedquery,savedqueryvisualization,sdkmessage,sdkmessagefilter,sdkmessagepair,sdkmessageprocessingstep,sdkmessageprocessingstepimage,sdkmessageprocessingstepsecureconfig,sdkmessagerequest,sdkmessagerequestfield,sdkmessageresponse,sdkmessageresponsefield,service,serviceappointment,servicecontractcontacts,serviceendpoint,sharepointdocumentlocation,sharepointsite,site,sitemap,sla,socialactivity,solution,solutioncomponent,statusmap,stringmap,subject,subscription,subscriptionmanuallytrackedobject,subscriptionsyncinfo,systemuser,systemuserbusinessunitentitymap,task,team,teammembership,template,territory,theme,timezonedefinition,timezonelocalizedname,timezonerule,topic,topichistory,topicmodel,topicmodelconfiguration,topicmodelexecutionhistory,transactioncurrency,transformationmapping,transformationparametermapping,unresolvedaddress,uom,uomschedule,userentityuisettings,userfiscalcalendar,userform,usermapping,userquery,userqueryvisualization,webresource,webwizard,wizardaccessprivilege,wizardpage,workflow,workflowdependency,workflowlog,workflowwaitsubscription|
|Type|Lookup|


### <a name="BKMK_ObjectTypeCode"></a> ObjectTypeCode

|Property|Value|
|--------|-----|
|Description|Object Type Code|
|DisplayName||
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|objecttypecode|
|MaxValue|2147483647|
|MinValue|0|
|RequiredLevel|SystemRequired|
|Type|Integer|


### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user or team who owns the user entity instance data.|
|DisplayName|Owner|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

|Property|Value|
|--------|-----|
|Description|Type of the owner of the object.|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_PersonalCategories"></a> PersonalCategories

|Property|Value|
|--------|-----|
|Description|Personal categories|
|DisplayName|personal categories|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|personalcategories|
|MaxLength|2000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ReminderSet"></a> ReminderSet

|Property|Value|
|--------|-----|
|Description|Indicates whether a reminder is set on this object.|
|DisplayName|Is Reminder set|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|reminderset|
|RequiredLevel|None|
|Type|Boolean|

#### ReminderSet Options

|Value|Label|
|-----|-----|
|1|Remind Set|
|0|Reminder Not Set|

**DefaultValue**: False



### <a name="BKMK_ReminderTime"></a> ReminderTime

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Reminder time|
|DisplayName|Reminder time|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|remindertime|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_StartTime"></a> StartTime

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Start Time|
|DisplayName|Start Time|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|starttime|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ToDoItemFlags"></a> ToDoItemFlags

|Property|Value|
|--------|-----|
|Description|To Do item flags.|
|DisplayName||
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|todoitemflags|
|MaxValue|2147483647|
|MinValue|-2147483648|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_ToDoOrdinalDate"></a> ToDoOrdinalDate

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|For internal use only.|
|DisplayName|To Do Primary Sort Date|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|todoordinaldate|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ToDoSubOrdinal"></a> ToDoSubOrdinal

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|To Do Sort Tie Breaker|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|todosubordinal|
|MaxLength|20|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ToDoTitle"></a> ToDoTitle

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|To Do Title|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|todotitle|
|MaxLength|4000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_UserEntityInstanceDataId"></a> UserEntityInstanceDataId

|Property|Value|
|--------|-----|
|Description|Unique identifier user entity|
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|userentityinstancedataid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

|Property|Value|
|--------|-----|
|Description|Name of the owner of the object.|
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
|Description||
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
|Description|Unique identifier of the business unit that owns this.|
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
|Description|Unique identifier of the team who owns this object.|
|DisplayName|Owning Team|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningteam|
|RequiredLevel|SystemRequired|
|Targets|team|
|Type|Lookup|


### <a name="BKMK_OwningUser"></a> OwningUser

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who owns this object.|
|DisplayName|Owning User|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owninguser|
|RequiredLevel|SystemRequired|
|Targets|systemuser|
|Type|Lookup|


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

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [userentityinstancedata_territory](#BKMK_userentityinstancedata_territory)
- [holidaywrapper_UserEntityInstanceDatas](#BKMK_holidaywrapper_UserEntityInstanceDatas)
- [accountleads_UserEntityInstanceDatas](#BKMK_accountleads_UserEntityInstanceDatas)
- [contactleads_UserEntityInstanceDatas](#BKMK_contactleads_UserEntityInstanceDatas)
- [userentityinstancedata_leadaddress](#BKMK_userentityinstancedata_leadaddress)
- [userentityinstancedata_lead](#BKMK_userentityinstancedata_lead)
- [dynamicproperty_UserEntityInstanceDatas](#BKMK_dynamicproperty_UserEntityInstanceDatas)
- [dynamicpropertyassociation_UserEntityInstanceDatas](#BKMK_dynamicpropertyassociation_UserEntityInstanceDatas)
- [dynamicpropertyinstance_UserEntityInstanceDatas](#BKMK_dynamicpropertyinstance_UserEntityInstanceDatas)
- [dynamicpropertyoptionsetitem_UserEntityInstanceDatas](#BKMK_dynamicpropertyoptionsetitem_UserEntityInstanceDatas)
- [userentityinstancedata_pricelevel](#BKMK_userentityinstancedata_pricelevel)
- [userentityinstancedata_product](#BKMK_userentityinstancedata_product)
- [userentityinstancedata_productassociation](#BKMK_userentityinstancedata_productassociation)
- [userentityinstancedata_productpricelevel](#BKMK_userentityinstancedata_productpricelevel)
- [productsubstitute_UserEntityInstanceDatas](#BKMK_productsubstitute_UserEntityInstanceDatas)
- [userentityinstancedata_uom](#BKMK_userentityinstancedata_uom)
- [userentityinstancedata_uomschedule](#BKMK_userentityinstancedata_uomschedule)
- [bookableresource_UserEntityInstanceDatas](#BKMK_bookableresource_UserEntityInstanceDatas)
- [bookableresourcebooking_UserEntityInstanceDatas](#BKMK_bookableresourcebooking_UserEntityInstanceDatas)
- [bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas](#BKMK_bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas)
- [bookableresourcebookingheader_UserEntityInstanceDatas](#BKMK_bookableresourcebookingheader_UserEntityInstanceDatas)
- [bookableresourcecategory_UserEntityInstanceDatas](#BKMK_bookableresourcecategory_UserEntityInstanceDatas)
- [bookableresourcecategoryassn_UserEntityInstanceDatas](#BKMK_bookableresourcecategoryassn_UserEntityInstanceDatas)
- [bookableresourcecharacteristic_UserEntityInstanceDatas](#BKMK_bookableresourcecharacteristic_UserEntityInstanceDatas)
- [bookableresourcegroup_UserEntityInstanceDatas](#BKMK_bookableresourcegroup_UserEntityInstanceDatas)
- [bookingstatus_UserEntityInstanceDatas](#BKMK_bookingstatus_UserEntityInstanceDatas)
- [characteristic_UserEntityInstanceDatas](#BKMK_characteristic_UserEntityInstanceDatas)
- [ratingmodel_UserEntityInstanceDatas](#BKMK_ratingmodel_UserEntityInstanceDatas)
- [ratingvalue_UserEntityInstanceDatas](#BKMK_ratingvalue_UserEntityInstanceDatas)
- [userentityinstancedata_bulkoperation](#BKMK_userentityinstancedata_bulkoperation)
- [userentityinstancedata_bulkoperationlog](#BKMK_userentityinstancedata_bulkoperationlog)
- [userentityinstancedata_campaign](#BKMK_userentityinstancedata_campaign)
- [userentityinstancedata_campaignactivity](#BKMK_userentityinstancedata_campaignactivity)
- [campaignactivityitem_UserEntityInstanceDatas](#BKMK_campaignactivityitem_UserEntityInstanceDatas)
- [campaignitem_UserEntityInstanceDatas](#BKMK_campaignitem_UserEntityInstanceDatas)
- [userentityinstancedata_campaignresponse](#BKMK_userentityinstancedata_campaignresponse)
- [userentityinstancedata_list](#BKMK_userentityinstancedata_list)
- [userentityinstancedata_listmember](#BKMK_userentityinstancedata_listmember)
- [userentityinstancedata_campaignactivityitem](#BKMK_userentityinstancedata_campaignactivityitem)
- [userentityinstancedata_campaignitem](#BKMK_userentityinstancedata_campaignitem)
- [msdyn_databaseversion_UserEntityInstanceDatas](#BKMK_msdyn_databaseversion_UserEntityInstanceDatas)
- [msdyn_upgraderun_UserEntityInstanceDatas](#BKMK_msdyn_upgraderun_UserEntityInstanceDatas)
- [msdyn_upgradestep_UserEntityInstanceDatas](#BKMK_msdyn_upgradestep_UserEntityInstanceDatas)
- [msdyn_upgradeversion_UserEntityInstanceDatas](#BKMK_msdyn_upgradeversion_UserEntityInstanceDatas)
- [userentityinstancedata_commitment](#BKMK_userentityinstancedata_commitment)
- [userentityinstancedata_constraintbasedgroup](#BKMK_userentityinstancedata_constraintbasedgroup)
- [userentityinstancedata_contract](#BKMK_userentityinstancedata_contract)
- [userentityinstancedata_contractdetail](#BKMK_userentityinstancedata_contractdetail)
- [userentityinstancedata_contracttemplate](#BKMK_userentityinstancedata_contracttemplate)
- [entitlement_UserEntityInstanceDatas](#BKMK_entitlement_UserEntityInstanceDatas)
- [entitlementchannel_UserEntityInstanceDatas](#BKMK_entitlementchannel_UserEntityInstanceDatas)
- [entitlementcontacts_UserEntityInstanceDatas](#BKMK_entitlementcontacts_UserEntityInstanceDatas)
- [entitlementproducts_UserEntityInstanceDatas](#BKMK_entitlementproducts_UserEntityInstanceDatas)
- [entitlementtemplate_UserEntityInstanceDatas](#BKMK_entitlementtemplate_UserEntityInstanceDatas)
- [entitlementtemplatechannel_UserEntityInstanceDatas](#BKMK_entitlementtemplatechannel_UserEntityInstanceDatas)
- [entitlementtemplateproducts_UserEntityInstanceDatas](#BKMK_entitlementtemplateproducts_UserEntityInstanceDatas)
- [userentityinstancedata_equipment](#BKMK_userentityinstancedata_equipment)
- [userentityinstancedata_incident](#BKMK_userentityinstancedata_incident)
- [incidentknowledgebaserecord_UserEntityInstanceDatas](#BKMK_incidentknowledgebaserecord_UserEntityInstanceDatas)
- [userentityinstancedata_incidentresolution](#BKMK_userentityinstancedata_incidentresolution)
- [knowledgearticleincident_UserEntityInstanceDatas](#BKMK_knowledgearticleincident_UserEntityInstanceDatas)
- [phonetocaseprocess_UserEntityInstanceDatas](#BKMK_phonetocaseprocess_UserEntityInstanceDatas)
- [userentityinstancedata_resource](#BKMK_userentityinstancedata_resource)
- [userentityinstancedata_resourcegroup](#BKMK_userentityinstancedata_resourcegroup)
- [userentityinstancedata_resourcespec](#BKMK_userentityinstancedata_resourcespec)
- [userentityinstancedata_service](#BKMK_userentityinstancedata_service)
- [userentityinstancedata_serviceappointment](#BKMK_userentityinstancedata_serviceappointment)
- [servicecontractcontacts_UserEntityInstanceDatas](#BKMK_servicecontractcontacts_UserEntityInstanceDatas)
- [topic_UserEntityInstanceDatas](#BKMK_topic_UserEntityInstanceDatas)
- [topichistory_UserEntityInstanceDatas](#BKMK_topichistory_UserEntityInstanceDatas)
- [topicmodel_UserEntityInstanceDatas](#BKMK_topicmodel_UserEntityInstanceDatas)
- [topicmodelconfiguration_UserEntityInstanceDatas](#BKMK_topicmodelconfiguration_UserEntityInstanceDatas)
- [topicmodelexecutionhistory_UserEntityInstanceDatas](#BKMK_topicmodelexecutionhistory_UserEntityInstanceDatas)
- [userentityinstancedata_site](#BKMK_userentityinstancedata_site)
- [entitlemententityallocationtypemapping_UserEntityInstanceDatas](#BKMK_entitlemententityallocationtypemapping_UserEntityInstanceDatas)
- [msdyn_callablecontext_UserEntityInstanceDatas](#BKMK_msdyn_callablecontext_UserEntityInstanceDatas)
- [msdyn_playbookactivity_UserEntityInstanceDatas](#BKMK_msdyn_playbookactivity_UserEntityInstanceDatas)
- [msdyn_playbookactivityattribute_UserEntityInstanceDatas](#BKMK_msdyn_playbookactivityattribute_UserEntityInstanceDatas)
- [msdyn_playbookcategory_UserEntityInstanceDatas](#BKMK_msdyn_playbookcategory_UserEntityInstanceDatas)
- [msdyn_playbookinstance_UserEntityInstanceDatas](#BKMK_msdyn_playbookinstance_UserEntityInstanceDatas)
- [msdyn_playbooktemplate_UserEntityInstanceDatas](#BKMK_msdyn_playbooktemplate_UserEntityInstanceDatas)
- [competitorproduct_UserEntityInstanceDatas](#BKMK_competitorproduct_UserEntityInstanceDatas)
- [competitorsalesliterature_UserEntityInstanceDatas](#BKMK_competitorsalesliterature_UserEntityInstanceDatas)
- [contactinvoices_UserEntityInstanceDatas](#BKMK_contactinvoices_UserEntityInstanceDatas)
- [contactorders_UserEntityInstanceDatas](#BKMK_contactorders_UserEntityInstanceDatas)
- [contactquotes_UserEntityInstanceDatas](#BKMK_contactquotes_UserEntityInstanceDatas)
- [userentityinstancedata_customeropportunityrole](#BKMK_userentityinstancedata_customeropportunityrole)
- [userentityinstancedata_discount](#BKMK_userentityinstancedata_discount)
- [userentityinstancedata_discounttype](#BKMK_userentityinstancedata_discounttype)
- [userentityinstancedata_invoice](#BKMK_userentityinstancedata_invoice)
- [userentityinstancedata_invoicedetail](#BKMK_userentityinstancedata_invoicedetail)
- [leadcompetitors_UserEntityInstanceDatas](#BKMK_leadcompetitors_UserEntityInstanceDatas)
- [leadproduct_UserEntityInstanceDatas](#BKMK_leadproduct_UserEntityInstanceDatas)
- [leadtoopportunitysalesprocess_UserEntityInstanceDatas](#BKMK_leadtoopportunitysalesprocess_UserEntityInstanceDatas)
- [userentityinstancedata_opportunity](#BKMK_userentityinstancedata_opportunity)
- [userentityinstancedata_opportunityclose](#BKMK_userentityinstancedata_opportunityclose)
- [opportunitycompetitors_UserEntityInstanceDatas](#BKMK_opportunitycompetitors_UserEntityInstanceDatas)
- [userentityinstancedata_opportunityproduct](#BKMK_userentityinstancedata_opportunityproduct)
- [opportunitysalesprocess_UserEntityInstanceDatas](#BKMK_opportunitysalesprocess_UserEntityInstanceDatas)
- [userentityinstancedata_orderclose](#BKMK_userentityinstancedata_orderclose)
- [productsalesliterature_UserEntityInstanceDatas](#BKMK_productsalesliterature_UserEntityInstanceDatas)
- [userentityinstancedata_quote](#BKMK_userentityinstancedata_quote)
- [userentityinstancedata_quoteclose](#BKMK_userentityinstancedata_quoteclose)
- [userentityinstancedata_quotedetail](#BKMK_userentityinstancedata_quotedetail)
- [userentityinstancedata_salesliterature](#BKMK_userentityinstancedata_salesliterature)
- [userentityinstancedata_salesliteratureitem](#BKMK_userentityinstancedata_salesliteratureitem)
- [userentityinstancedata_salesorder](#BKMK_userentityinstancedata_salesorder)
- [userentityinstancedata_salesorderdetail](#BKMK_userentityinstancedata_salesorderdetail)
- [userentityinstancedata_competitor](#BKMK_userentityinstancedata_competitor)
- [userentityinstancedata_competitorproduct](#BKMK_userentityinstancedata_competitorproduct)
- [userentityinstancedata_productsalesliterature](#BKMK_userentityinstancedata_productsalesliterature)
- [userentityinstancedata_competitorsalesliterature](#BKMK_userentityinstancedata_competitorsalesliterature)
- [userentityinstancedata_leadproduct](#BKMK_userentityinstancedata_leadproduct)
- [adminsettingsentity_UserEntityInstanceDatas](#BKMK_adminsettingsentity_UserEntityInstanceDatas)
- [msdyn_forecastdefinition_UserEntityInstanceDatas](#BKMK_msdyn_forecastdefinition_UserEntityInstanceDatas)
- [msdyn_forecastinstance_UserEntityInstanceDatas](#BKMK_msdyn_forecastinstance_UserEntityInstanceDatas)
- [msdyn_forecastrecurrence_UserEntityInstanceDatas](#BKMK_msdyn_forecastrecurrence_UserEntityInstanceDatas)
- [msdyn_relationshipinsightsunifiedconfig_UserEntityInstanceDatas](#BKMK_msdyn_relationshipinsightsunifiedconfig_UserEntityInstanceDatas)
- [msdyn_siconfig_UserEntityInstanceDatas](#BKMK_msdyn_siconfig_UserEntityInstanceDatas)
- [msdyn_untrackedappointment_UserEntityInstanceDatas](#BKMK_msdyn_untrackedappointment_UserEntityInstanceDatas)
- [msdyn_notesanalysisconfig_UserEntityInstanceDatas](#BKMK_msdyn_notesanalysisconfig_UserEntityInstanceDatas)
- [msdyn_icebreakersconfig_UserEntityInstanceDatas](#BKMK_msdyn_icebreakersconfig_UserEntityInstanceDatas)
- [msdyn_postalbum_UserEntityInstanceDatas](#BKMK_msdyn_postalbum_UserEntityInstanceDatas)
- [msdyn_postconfig_UserEntityInstanceDatas](#BKMK_msdyn_postconfig_UserEntityInstanceDatas)
- [msdyn_postruleconfig_UserEntityInstanceDatas](#BKMK_msdyn_postruleconfig_UserEntityInstanceDatas)
- [msdyn_wallsavedquery_UserEntityInstanceDatas](#BKMK_msdyn_wallsavedquery_UserEntityInstanceDatas)
- [msdyn_wallsavedqueryusersettings_UserEntityInstanceDatas](#BKMK_msdyn_wallsavedqueryusersettings_UserEntityInstanceDatas)
- [msfp_emailtemplate_UserEntityInstanceDatas](#BKMK_msfp_emailtemplate_UserEntityInstanceDatas)
- [msfp_question_UserEntityInstanceDatas](#BKMK_msfp_question_UserEntityInstanceDatas)
- [msfp_questionresponse_UserEntityInstanceDatas](#BKMK_msfp_questionresponse_UserEntityInstanceDatas)
- [msfp_survey_UserEntityInstanceDatas](#BKMK_msfp_survey_UserEntityInstanceDatas)
- [msfp_surveyinvite_UserEntityInstanceDatas](#BKMK_msfp_surveyinvite_UserEntityInstanceDatas)
- [msfp_surveyresponse_UserEntityInstanceDatas](#BKMK_msfp_surveyresponse_UserEntityInstanceDatas)
- [msfp_unsubscribedrecipient_UserEntityInstanceDatas](#BKMK_msfp_unsubscribedrecipient_UserEntityInstanceDatas)
- [msdyn_teamscollaboration_UserEntityInstanceDatas](#BKMK_msdyn_teamscollaboration_UserEntityInstanceDatas)
- [msdyn_actual_UserEntityInstanceDatas](#BKMK_msdyn_actual_UserEntityInstanceDatas)
- [msdyn_bookableresourceassociation_UserEntityInstanceDatas](#BKMK_msdyn_bookableresourceassociation_UserEntityInstanceDatas)
- [msdyn_bookingalert_UserEntityInstanceDatas](#BKMK_msdyn_bookingalert_UserEntityInstanceDatas)
- [msdyn_bookingalertstatus_UserEntityInstanceDatas](#BKMK_msdyn_bookingalertstatus_UserEntityInstanceDatas)
- [msdyn_bookingchange_UserEntityInstanceDatas](#BKMK_msdyn_bookingchange_UserEntityInstanceDatas)
- [msdyn_bookingrule_UserEntityInstanceDatas](#BKMK_msdyn_bookingrule_UserEntityInstanceDatas)
- [msdyn_bookingsetupmetadata_UserEntityInstanceDatas](#BKMK_msdyn_bookingsetupmetadata_UserEntityInstanceDatas)
- [msdyn_businessclosure_UserEntityInstanceDatas](#BKMK_msdyn_businessclosure_UserEntityInstanceDatas)
- [msdyn_clientextension_UserEntityInstanceDatas](#BKMK_msdyn_clientextension_UserEntityInstanceDatas)
- [msdyn_configuration_UserEntityInstanceDatas](#BKMK_msdyn_configuration_UserEntityInstanceDatas)
- [msdyn_organizationalunit_UserEntityInstanceDatas](#BKMK_msdyn_organizationalunit_UserEntityInstanceDatas)
- [msdyn_priority_UserEntityInstanceDatas](#BKMK_msdyn_priority_UserEntityInstanceDatas)
- [msdyn_requirementcharacteristic_UserEntityInstanceDatas](#BKMK_msdyn_requirementcharacteristic_UserEntityInstanceDatas)
- [msdyn_requirementgroup_UserEntityInstanceDatas](#BKMK_msdyn_requirementgroup_UserEntityInstanceDatas)
- [msdyn_requirementorganizationunit_UserEntityInstanceDatas](#BKMK_msdyn_requirementorganizationunit_UserEntityInstanceDatas)
- [msdyn_requirementrelationship_UserEntityInstanceDatas](#BKMK_msdyn_requirementrelationship_UserEntityInstanceDatas)
- [msdyn_requirementresourcecategory_UserEntityInstanceDatas](#BKMK_msdyn_requirementresourcecategory_UserEntityInstanceDatas)
- [msdyn_requirementresourcepreference_UserEntityInstanceDatas](#BKMK_msdyn_requirementresourcepreference_UserEntityInstanceDatas)
- [msdyn_requirementstatus_UserEntityInstanceDatas](#BKMK_msdyn_requirementstatus_UserEntityInstanceDatas)
- [msdyn_resourcerequirement_UserEntityInstanceDatas](#BKMK_msdyn_resourcerequirement_UserEntityInstanceDatas)
- [msdyn_resourcerequirementdetail_UserEntityInstanceDatas](#BKMK_msdyn_resourcerequirementdetail_UserEntityInstanceDatas)
- [msdyn_resourceterritory_UserEntityInstanceDatas](#BKMK_msdyn_resourceterritory_UserEntityInstanceDatas)
- [msdyn_scheduleboardsetting_UserEntityInstanceDatas](#BKMK_msdyn_scheduleboardsetting_UserEntityInstanceDatas)
- [msdyn_schedulingparameter_UserEntityInstanceDatas](#BKMK_msdyn_schedulingparameter_UserEntityInstanceDatas)
- [msdyn_systemuserschedulersetting_UserEntityInstanceDatas](#BKMK_msdyn_systemuserschedulersetting_UserEntityInstanceDatas)
- [msdyn_timegroup_UserEntityInstanceDatas](#BKMK_msdyn_timegroup_UserEntityInstanceDatas)
- [msdyn_timegroupdetail_UserEntityInstanceDatas](#BKMK_msdyn_timegroupdetail_UserEntityInstanceDatas)
- [msdyn_transactionorigin_UserEntityInstanceDatas](#BKMK_msdyn_transactionorigin_UserEntityInstanceDatas)
- [msdyn_workhourtemplate_UserEntityInstanceDatas](#BKMK_msdyn_workhourtemplate_UserEntityInstanceDatas)
- [msdyn_accountpricelist_UserEntityInstanceDatas](#BKMK_msdyn_accountpricelist_UserEntityInstanceDatas)
- [msdyn_approval_UserEntityInstanceDatas](#BKMK_msdyn_approval_UserEntityInstanceDatas)
- [msdyn_batchjob_UserEntityInstanceDatas](#BKMK_msdyn_batchjob_UserEntityInstanceDatas)
- [msdyn_bpf_665e73aa18c247d886bfc50499c73b82_UserEntityInstanceDatas](#BKMK_msdyn_bpf_665e73aa18c247d886bfc50499c73b82_UserEntityInstanceDatas)
- [msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d_UserEntityInstanceDatas](#BKMK_msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d_UserEntityInstanceDatas)
- [msdyn_characteristicreqforteammember_UserEntityInstanceDatas](#BKMK_msdyn_characteristicreqforteammember_UserEntityInstanceDatas)
- [msdyn_contactpricelist_UserEntityInstanceDatas](#BKMK_msdyn_contactpricelist_UserEntityInstanceDatas)
- [msdyn_contractlineinvoiceschedule_UserEntityInstanceDatas](#BKMK_msdyn_contractlineinvoiceschedule_UserEntityInstanceDatas)
- [msdyn_contractlinescheduleofvalue_UserEntityInstanceDatas](#BKMK_msdyn_contractlinescheduleofvalue_UserEntityInstanceDatas)
- [msdyn_dataexport_UserEntityInstanceDatas](#BKMK_msdyn_dataexport_UserEntityInstanceDatas)
- [msdyn_delegation_UserEntityInstanceDatas](#BKMK_msdyn_delegation_UserEntityInstanceDatas)
- [msdyn_dimension_UserEntityInstanceDatas](#BKMK_msdyn_dimension_UserEntityInstanceDatas)
- [msdyn_dimensionfieldname_UserEntityInstanceDatas](#BKMK_msdyn_dimensionfieldname_UserEntityInstanceDatas)
- [msdyn_estimate_UserEntityInstanceDatas](#BKMK_msdyn_estimate_UserEntityInstanceDatas)
- [msdyn_estimateline_UserEntityInstanceDatas](#BKMK_msdyn_estimateline_UserEntityInstanceDatas)
- [msdyn_expense_UserEntityInstanceDatas](#BKMK_msdyn_expense_UserEntityInstanceDatas)
- [msdyn_expensecategory_UserEntityInstanceDatas](#BKMK_msdyn_expensecategory_UserEntityInstanceDatas)
- [msdyn_expensereceipt_UserEntityInstanceDatas](#BKMK_msdyn_expensereceipt_UserEntityInstanceDatas)
- [msdyn_fact_UserEntityInstanceDatas](#BKMK_msdyn_fact_UserEntityInstanceDatas)
- [msdyn_fieldcomputation_UserEntityInstanceDatas](#BKMK_msdyn_fieldcomputation_UserEntityInstanceDatas)
- [msdyn_findworkevent_UserEntityInstanceDatas](#BKMK_msdyn_findworkevent_UserEntityInstanceDatas)
- [msdyn_integrationjob_UserEntityInstanceDatas](#BKMK_msdyn_integrationjob_UserEntityInstanceDatas)
- [msdyn_integrationjobdetail_UserEntityInstanceDatas](#BKMK_msdyn_integrationjobdetail_UserEntityInstanceDatas)
- [msdyn_invoicefrequency_UserEntityInstanceDatas](#BKMK_msdyn_invoicefrequency_UserEntityInstanceDatas)
- [msdyn_invoicefrequencydetail_UserEntityInstanceDatas](#BKMK_msdyn_invoicefrequencydetail_UserEntityInstanceDatas)
- [msdyn_invoicelinetransaction_UserEntityInstanceDatas](#BKMK_msdyn_invoicelinetransaction_UserEntityInstanceDatas)
- [msdyn_journal_UserEntityInstanceDatas](#BKMK_msdyn_journal_UserEntityInstanceDatas)
- [msdyn_journalline_UserEntityInstanceDatas](#BKMK_msdyn_journalline_UserEntityInstanceDatas)
- [msdyn_mlresultcache_UserEntityInstanceDatas](#BKMK_msdyn_mlresultcache_UserEntityInstanceDatas)
- [msdyn_opportunitylineresourcecategory_UserEntityInstanceDatas](#BKMK_msdyn_opportunitylineresourcecategory_UserEntityInstanceDatas)
- [msdyn_opportunitylinetransaction_UserEntityInstanceDatas](#BKMK_msdyn_opportunitylinetransaction_UserEntityInstanceDatas)
- [msdyn_opportunitylinetransactioncategory_UserEntityInstanceDatas](#BKMK_msdyn_opportunitylinetransactioncategory_UserEntityInstanceDatas)
- [msdyn_opportunitylinetransactionclassificatio_UserEntityInstanceDatas](#BKMK_msdyn_opportunitylinetransactionclassificatio_UserEntityInstanceDatas)
- [msdyn_opportunitypricelist_UserEntityInstanceDatas](#BKMK_msdyn_opportunitypricelist_UserEntityInstanceDatas)
- [msdyn_orderlineresourcecategory_UserEntityInstanceDatas](#BKMK_msdyn_orderlineresourcecategory_UserEntityInstanceDatas)
- [msdyn_orderlinetransaction_UserEntityInstanceDatas](#BKMK_msdyn_orderlinetransaction_UserEntityInstanceDatas)
- [msdyn_orderlinetransactioncategory_UserEntityInstanceDatas](#BKMK_msdyn_orderlinetransactioncategory_UserEntityInstanceDatas)
- [msdyn_orderlinetransactionclassification_UserEntityInstanceDatas](#BKMK_msdyn_orderlinetransactionclassification_UserEntityInstanceDatas)
- [msdyn_orderpricelist_UserEntityInstanceDatas](#BKMK_msdyn_orderpricelist_UserEntityInstanceDatas)
- [msdyn_processnotes_UserEntityInstanceDatas](#BKMK_msdyn_processnotes_UserEntityInstanceDatas)
- [msdyn_project_UserEntityInstanceDatas](#BKMK_msdyn_project_UserEntityInstanceDatas)
- [msdyn_projectapproval_UserEntityInstanceDatas](#BKMK_msdyn_projectapproval_UserEntityInstanceDatas)
- [msdyn_projectparameter_UserEntityInstanceDatas](#BKMK_msdyn_projectparameter_UserEntityInstanceDatas)
- [msdyn_projectparameterpricelist_UserEntityInstanceDatas](#BKMK_msdyn_projectparameterpricelist_UserEntityInstanceDatas)
- [msdyn_projectpricelist_UserEntityInstanceDatas](#BKMK_msdyn_projectpricelist_UserEntityInstanceDatas)
- [msdyn_projecttask_UserEntityInstanceDatas](#BKMK_msdyn_projecttask_UserEntityInstanceDatas)
- [msdyn_projecttaskdependency_UserEntityInstanceDatas](#BKMK_msdyn_projecttaskdependency_UserEntityInstanceDatas)
- [msdyn_projecttaskstatususer_UserEntityInstanceDatas](#BKMK_msdyn_projecttaskstatususer_UserEntityInstanceDatas)
- [msdyn_projectteam_UserEntityInstanceDatas](#BKMK_msdyn_projectteam_UserEntityInstanceDatas)
- [msdyn_projectteammembersignup_UserEntityInstanceDatas](#BKMK_msdyn_projectteammembersignup_UserEntityInstanceDatas)
- [msdyn_projecttransactioncategory_UserEntityInstanceDatas](#BKMK_msdyn_projecttransactioncategory_UserEntityInstanceDatas)
- [msdyn_quotelineanalyticsbreakdown_UserEntityInstanceDatas](#BKMK_msdyn_quotelineanalyticsbreakdown_UserEntityInstanceDatas)
- [msdyn_quotelineinvoiceschedule_UserEntityInstanceDatas](#BKMK_msdyn_quotelineinvoiceschedule_UserEntityInstanceDatas)
- [msdyn_quotelineresourcecategory_UserEntityInstanceDatas](#BKMK_msdyn_quotelineresourcecategory_UserEntityInstanceDatas)
- [msdyn_quotelinescheduleofvalue_UserEntityInstanceDatas](#BKMK_msdyn_quotelinescheduleofvalue_UserEntityInstanceDatas)
- [msdyn_quotelinetransaction_UserEntityInstanceDatas](#BKMK_msdyn_quotelinetransaction_UserEntityInstanceDatas)
- [msdyn_quotelinetransactioncategory_UserEntityInstanceDatas](#BKMK_msdyn_quotelinetransactioncategory_UserEntityInstanceDatas)
- [msdyn_quotelinetransactionclassification_UserEntityInstanceDatas](#BKMK_msdyn_quotelinetransactionclassification_UserEntityInstanceDatas)
- [msdyn_quotepricelist_UserEntityInstanceDatas](#BKMK_msdyn_quotepricelist_UserEntityInstanceDatas)
- [msdyn_resourceassignment_UserEntityInstanceDatas](#BKMK_msdyn_resourceassignment_UserEntityInstanceDatas)
- [msdyn_resourceassignmentdetail_UserEntityInstanceDatas](#BKMK_msdyn_resourceassignmentdetail_UserEntityInstanceDatas)
- [msdyn_resourcecategorymarkuppricelevel_UserEntityInstanceDatas](#BKMK_msdyn_resourcecategorymarkuppricelevel_UserEntityInstanceDatas)
- [msdyn_resourcecategorypricelevel_UserEntityInstanceDatas](#BKMK_msdyn_resourcecategorypricelevel_UserEntityInstanceDatas)
- [msdyn_resourcerequest_UserEntityInstanceDatas](#BKMK_msdyn_resourcerequest_UserEntityInstanceDatas)
- [msdyn_rolecompetencyrequirement_UserEntityInstanceDatas](#BKMK_msdyn_rolecompetencyrequirement_UserEntityInstanceDatas)
- [msdyn_roleutilization_UserEntityInstanceDatas](#BKMK_msdyn_roleutilization_UserEntityInstanceDatas)
- [msdyn_timeentry_UserEntityInstanceDatas](#BKMK_msdyn_timeentry_UserEntityInstanceDatas)
- [msdyn_timeoffcalendar_UserEntityInstanceDatas](#BKMK_msdyn_timeoffcalendar_UserEntityInstanceDatas)
- [msdyn_transactioncategory_UserEntityInstanceDatas](#BKMK_msdyn_transactioncategory_UserEntityInstanceDatas)
- [msdyn_transactioncategoryclassification_UserEntityInstanceDatas](#BKMK_msdyn_transactioncategoryclassification_UserEntityInstanceDatas)
- [msdyn_transactioncategoryhierarchyelement_UserEntityInstanceDatas](#BKMK_msdyn_transactioncategoryhierarchyelement_UserEntityInstanceDatas)
- [msdyn_transactioncategorypricelevel_UserEntityInstanceDatas](#BKMK_msdyn_transactioncategorypricelevel_UserEntityInstanceDatas)
- [msdyn_transactionconnection_UserEntityInstanceDatas](#BKMK_msdyn_transactionconnection_UserEntityInstanceDatas)
- [msdyn_transactiontype_UserEntityInstanceDatas](#BKMK_msdyn_transactiontype_UserEntityInstanceDatas)
- [msdyn_userworkhistory_UserEntityInstanceDatas](#BKMK_msdyn_userworkhistory_UserEntityInstanceDatas)
- [msdyn_3dmodel_UserEntityInstanceDatas](#BKMK_msdyn_3dmodel_UserEntityInstanceDatas)
- [msdyn_analysiscomponent_UserEntityInstanceDatas](#BKMK_msdyn_analysiscomponent_UserEntityInstanceDatas)
- [msdyn_analysisjob_UserEntityInstanceDatas](#BKMK_msdyn_analysisjob_UserEntityInstanceDatas)
- [msdyn_analysisresult_UserEntityInstanceDatas](#BKMK_msdyn_analysisresult_UserEntityInstanceDatas)
- [msdyn_analysisresultdetail_UserEntityInstanceDatas](#BKMK_msdyn_analysisresultdetail_UserEntityInstanceDatas)
- [msdyn_solutionhealthrule_UserEntityInstanceDatas](#BKMK_msdyn_solutionhealthrule_UserEntityInstanceDatas)
- [msdyn_solutionhealthruleargument_UserEntityInstanceDatas](#BKMK_msdyn_solutionhealthruleargument_UserEntityInstanceDatas)
- [msdyn_solutionhealthruleset_UserEntityInstanceDatas](#BKMK_msdyn_solutionhealthruleset_UserEntityInstanceDatas)
- [msdyn_agreement_UserEntityInstanceDatas](#BKMK_msdyn_agreement_UserEntityInstanceDatas)
- [msdyn_agreementbookingdate_UserEntityInstanceDatas](#BKMK_msdyn_agreementbookingdate_UserEntityInstanceDatas)
- [msdyn_agreementbookingincident_UserEntityInstanceDatas](#BKMK_msdyn_agreementbookingincident_UserEntityInstanceDatas)
- [msdyn_agreementbookingproduct_UserEntityInstanceDatas](#BKMK_msdyn_agreementbookingproduct_UserEntityInstanceDatas)
- [msdyn_agreementbookingservice_UserEntityInstanceDatas](#BKMK_msdyn_agreementbookingservice_UserEntityInstanceDatas)
- [msdyn_agreementbookingservicetask_UserEntityInstanceDatas](#BKMK_msdyn_agreementbookingservicetask_UserEntityInstanceDatas)
- [msdyn_agreementbookingsetup_UserEntityInstanceDatas](#BKMK_msdyn_agreementbookingsetup_UserEntityInstanceDatas)
- [msdyn_agreementinvoicedate_UserEntityInstanceDatas](#BKMK_msdyn_agreementinvoicedate_UserEntityInstanceDatas)
- [msdyn_agreementinvoiceproduct_UserEntityInstanceDatas](#BKMK_msdyn_agreementinvoiceproduct_UserEntityInstanceDatas)
- [msdyn_agreementinvoicesetup_UserEntityInstanceDatas](#BKMK_msdyn_agreementinvoicesetup_UserEntityInstanceDatas)
- [msdyn_agreementsubstatus_UserEntityInstanceDatas](#BKMK_msdyn_agreementsubstatus_UserEntityInstanceDatas)
- [msdyn_bookingjournal_UserEntityInstanceDatas](#BKMK_msdyn_bookingjournal_UserEntityInstanceDatas)
- [msdyn_bookingtimestamp_UserEntityInstanceDatas](#BKMK_msdyn_bookingtimestamp_UserEntityInstanceDatas)
- [msdyn_bpf_2c5fe86acc8b414b8322ae571000c799_UserEntityInstanceDatas](#BKMK_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799_UserEntityInstanceDatas)
- [msdyn_bpf_989e9b1857e24af18787d5143b67523b_UserEntityInstanceDatas](#BKMK_msdyn_bpf_989e9b1857e24af18787d5143b67523b_UserEntityInstanceDatas)
- [msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3_UserEntityInstanceDatas](#BKMK_msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3_UserEntityInstanceDatas)
- [msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39_UserEntityInstanceDatas](#BKMK_msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39_UserEntityInstanceDatas)
- [msdyn_customerasset_UserEntityInstanceDatas](#BKMK_msdyn_customerasset_UserEntityInstanceDatas)
- [msdyn_customerassetcategory_UserEntityInstanceDatas](#BKMK_msdyn_customerassetcategory_UserEntityInstanceDatas)
- [msdyn_entitlementapplication_UserEntityInstanceDatas](#BKMK_msdyn_entitlementapplication_UserEntityInstanceDatas)
- [msdyn_fieldservicepricelistitem_UserEntityInstanceDatas](#BKMK_msdyn_fieldservicepricelistitem_UserEntityInstanceDatas)
- [msdyn_fieldservicesetting_UserEntityInstanceDatas](#BKMK_msdyn_fieldservicesetting_UserEntityInstanceDatas)
- [msdyn_fieldserviceslaconfiguration_UserEntityInstanceDatas](#BKMK_msdyn_fieldserviceslaconfiguration_UserEntityInstanceDatas)
- [msdyn_fieldservicesystemjob_UserEntityInstanceDatas](#BKMK_msdyn_fieldservicesystemjob_UserEntityInstanceDatas)
- [msdyn_incidenttype_UserEntityInstanceDatas](#BKMK_msdyn_incidenttype_UserEntityInstanceDatas)
- [msdyn_incidenttypecharacteristic_UserEntityInstanceDatas](#BKMK_msdyn_incidenttypecharacteristic_UserEntityInstanceDatas)
- [msdyn_incidenttypeproduct_UserEntityInstanceDatas](#BKMK_msdyn_incidenttypeproduct_UserEntityInstanceDatas)
- [msdyn_incidenttypeservice_UserEntityInstanceDatas](#BKMK_msdyn_incidenttypeservice_UserEntityInstanceDatas)
- [msdyn_incidenttypeservicetask_UserEntityInstanceDatas](#BKMK_msdyn_incidenttypeservicetask_UserEntityInstanceDatas)
- [msdyn_incidenttypessetup_UserEntityInstanceDatas](#BKMK_msdyn_incidenttypessetup_UserEntityInstanceDatas)
- [msdyn_incidenttype_requirementgroup_UserEntityInstanceDatas](#BKMK_msdyn_incidenttype_requirementgroup_UserEntityInstanceDatas)
- [msdyn_inventoryadjustment_UserEntityInstanceDatas](#BKMK_msdyn_inventoryadjustment_UserEntityInstanceDatas)
- [msdyn_inventoryadjustmentproduct_UserEntityInstanceDatas](#BKMK_msdyn_inventoryadjustmentproduct_UserEntityInstanceDatas)
- [msdyn_inventoryjournal_UserEntityInstanceDatas](#BKMK_msdyn_inventoryjournal_UserEntityInstanceDatas)
- [msdyn_inventorytransfer_UserEntityInstanceDatas](#BKMK_msdyn_inventorytransfer_UserEntityInstanceDatas)
- [msdyn_orderinvoicingdate_UserEntityInstanceDatas](#BKMK_msdyn_orderinvoicingdate_UserEntityInstanceDatas)
- [msdyn_orderinvoicingproduct_UserEntityInstanceDatas](#BKMK_msdyn_orderinvoicingproduct_UserEntityInstanceDatas)
- [msdyn_orderinvoicingsetup_UserEntityInstanceDatas](#BKMK_msdyn_orderinvoicingsetup_UserEntityInstanceDatas)
- [msdyn_orderinvoicingsetupdate_UserEntityInstanceDatas](#BKMK_msdyn_orderinvoicingsetupdate_UserEntityInstanceDatas)
- [msdyn_payment_UserEntityInstanceDatas](#BKMK_msdyn_payment_UserEntityInstanceDatas)
- [msdyn_paymentdetail_UserEntityInstanceDatas](#BKMK_msdyn_paymentdetail_UserEntityInstanceDatas)
- [msdyn_paymentmethod_UserEntityInstanceDatas](#BKMK_msdyn_paymentmethod_UserEntityInstanceDatas)
- [msdyn_paymentterm_UserEntityInstanceDatas](#BKMK_msdyn_paymentterm_UserEntityInstanceDatas)
- [msdyn_postalcode_UserEntityInstanceDatas](#BKMK_msdyn_postalcode_UserEntityInstanceDatas)
- [msdyn_productinventory_UserEntityInstanceDatas](#BKMK_msdyn_productinventory_UserEntityInstanceDatas)
- [msdyn_purchaseorder_UserEntityInstanceDatas](#BKMK_msdyn_purchaseorder_UserEntityInstanceDatas)
- [msdyn_purchaseorderbill_UserEntityInstanceDatas](#BKMK_msdyn_purchaseorderbill_UserEntityInstanceDatas)
- [msdyn_purchaseorderproduct_UserEntityInstanceDatas](#BKMK_msdyn_purchaseorderproduct_UserEntityInstanceDatas)
- [msdyn_purchaseorderreceipt_UserEntityInstanceDatas](#BKMK_msdyn_purchaseorderreceipt_UserEntityInstanceDatas)
- [msdyn_purchaseorderreceiptproduct_UserEntityInstanceDatas](#BKMK_msdyn_purchaseorderreceiptproduct_UserEntityInstanceDatas)
- [msdyn_purchaseordersubstatus_UserEntityInstanceDatas](#BKMK_msdyn_purchaseordersubstatus_UserEntityInstanceDatas)
- [msdyn_quotebookingincident_UserEntityInstanceDatas](#BKMK_msdyn_quotebookingincident_UserEntityInstanceDatas)
- [msdyn_quotebookingproduct_UserEntityInstanceDatas](#BKMK_msdyn_quotebookingproduct_UserEntityInstanceDatas)
- [msdyn_quotebookingservice_UserEntityInstanceDatas](#BKMK_msdyn_quotebookingservice_UserEntityInstanceDatas)
- [msdyn_quotebookingservicetask_UserEntityInstanceDatas](#BKMK_msdyn_quotebookingservicetask_UserEntityInstanceDatas)
- [msdyn_quotebookingsetup_UserEntityInstanceDatas](#BKMK_msdyn_quotebookingsetup_UserEntityInstanceDatas)
- [msdyn_quoteinvoicingproduct_UserEntityInstanceDatas](#BKMK_msdyn_quoteinvoicingproduct_UserEntityInstanceDatas)
- [msdyn_quoteinvoicingsetup_UserEntityInstanceDatas](#BKMK_msdyn_quoteinvoicingsetup_UserEntityInstanceDatas)
- [msdyn_resourcepaytype_UserEntityInstanceDatas](#BKMK_msdyn_resourcepaytype_UserEntityInstanceDatas)
- [msdyn_rma_UserEntityInstanceDatas](#BKMK_msdyn_rma_UserEntityInstanceDatas)
- [msdyn_rmaproduct_UserEntityInstanceDatas](#BKMK_msdyn_rmaproduct_UserEntityInstanceDatas)
- [msdyn_rmareceipt_UserEntityInstanceDatas](#BKMK_msdyn_rmareceipt_UserEntityInstanceDatas)
- [msdyn_rmareceiptproduct_UserEntityInstanceDatas](#BKMK_msdyn_rmareceiptproduct_UserEntityInstanceDatas)
- [msdyn_rmasubstatus_UserEntityInstanceDatas](#BKMK_msdyn_rmasubstatus_UserEntityInstanceDatas)
- [msdyn_rtv_UserEntityInstanceDatas](#BKMK_msdyn_rtv_UserEntityInstanceDatas)
- [msdyn_rtvproduct_UserEntityInstanceDatas](#BKMK_msdyn_rtvproduct_UserEntityInstanceDatas)
- [msdyn_rtvsubstatus_UserEntityInstanceDatas](#BKMK_msdyn_rtvsubstatus_UserEntityInstanceDatas)
- [msdyn_servicetasktype_UserEntityInstanceDatas](#BKMK_msdyn_servicetasktype_UserEntityInstanceDatas)
- [msdyn_shipvia_UserEntityInstanceDatas](#BKMK_msdyn_shipvia_UserEntityInstanceDatas)
- [msdyn_taxcode_UserEntityInstanceDatas](#BKMK_msdyn_taxcode_UserEntityInstanceDatas)
- [msdyn_taxcodedetail_UserEntityInstanceDatas](#BKMK_msdyn_taxcodedetail_UserEntityInstanceDatas)
- [msdyn_timeoffrequest_UserEntityInstanceDatas](#BKMK_msdyn_timeoffrequest_UserEntityInstanceDatas)
- [msdyn_uniquenumber_UserEntityInstanceDatas](#BKMK_msdyn_uniquenumber_UserEntityInstanceDatas)
- [msdyn_warehouse_UserEntityInstanceDatas](#BKMK_msdyn_warehouse_UserEntityInstanceDatas)
- [msdyn_workorder_UserEntityInstanceDatas](#BKMK_msdyn_workorder_UserEntityInstanceDatas)
- [msdyn_workordercharacteristic_UserEntityInstanceDatas](#BKMK_msdyn_workordercharacteristic_UserEntityInstanceDatas)
- [msdyn_workorderdetailsgenerationqueue_UserEntityInstanceDatas](#BKMK_msdyn_workorderdetailsgenerationqueue_UserEntityInstanceDatas)
- [msdyn_workorderincident_UserEntityInstanceDatas](#BKMK_msdyn_workorderincident_UserEntityInstanceDatas)
- [msdyn_workorderproduct_UserEntityInstanceDatas](#BKMK_msdyn_workorderproduct_UserEntityInstanceDatas)
- [msdyn_workorderresourcerestriction_UserEntityInstanceDatas](#BKMK_msdyn_workorderresourcerestriction_UserEntityInstanceDatas)
- [msdyn_workorderservice_UserEntityInstanceDatas](#BKMK_msdyn_workorderservice_UserEntityInstanceDatas)
- [msdyn_workorderservicetask_UserEntityInstanceDatas](#BKMK_msdyn_workorderservicetask_UserEntityInstanceDatas)
- [msdyn_workordersubstatus_UserEntityInstanceDatas](#BKMK_msdyn_workordersubstatus_UserEntityInstanceDatas)
- [msdyn_workordertype_UserEntityInstanceDatas](#BKMK_msdyn_workordertype_UserEntityInstanceDatas)
- [msdyn_iotalert_UserEntityInstanceDatas](#BKMK_msdyn_iotalert_UserEntityInstanceDatas)
- [msdyn_iotdevice_UserEntityInstanceDatas](#BKMK_msdyn_iotdevice_UserEntityInstanceDatas)
- [msdyn_iotdevicecategory_UserEntityInstanceDatas](#BKMK_msdyn_iotdevicecategory_UserEntityInstanceDatas)
- [msdyn_iotdevicecommand_UserEntityInstanceDatas](#BKMK_msdyn_iotdevicecommand_UserEntityInstanceDatas)
- [msdyn_iotdevicecommanddefinition_UserEntityInstanceDatas](#BKMK_msdyn_iotdevicecommanddefinition_UserEntityInstanceDatas)
- [msdyn_iotdevicedatahistory_UserEntityInstanceDatas](#BKMK_msdyn_iotdevicedatahistory_UserEntityInstanceDatas)
- [msdyn_iotdeviceproperty_UserEntityInstanceDatas](#BKMK_msdyn_iotdeviceproperty_UserEntityInstanceDatas)
- [msdyn_iotdeviceregistrationhistory_UserEntityInstanceDatas](#BKMK_msdyn_iotdeviceregistrationhistory_UserEntityInstanceDatas)
- [msdyn_iotpropertydefinition_UserEntityInstanceDatas](#BKMK_msdyn_iotpropertydefinition_UserEntityInstanceDatas)
- [msdyn_iotsettings_UserEntityInstanceDatas](#BKMK_msdyn_iotsettings_UserEntityInstanceDatas)
- [msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b_UserEntityInstanceDatas](#BKMK_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b_UserEntityInstanceDatas)
- [msdyn_entityconfiguration_UserEntityInstanceDatas](#BKMK_msdyn_entityconfiguration_UserEntityInstanceDatas)
- [msdyn_geofence_UserEntityInstanceDatas](#BKMK_msdyn_geofence_UserEntityInstanceDatas)
- [msdyn_geofenceevent_UserEntityInstanceDatas](#BKMK_msdyn_geofenceevent_UserEntityInstanceDatas)
- [msdyn_geofencingsettings_UserEntityInstanceDatas](#BKMK_msdyn_geofencingsettings_UserEntityInstanceDatas)
- [msdynsm_marketingsitemap_UserEntityInstanceDatas](#BKMK_msdynsm_marketingsitemap_UserEntityInstanceDatas)
- [msdynsm_salessitemap_UserEntityInstanceDatas](#BKMK_msdynsm_salessitemap_UserEntityInstanceDatas)
- [msdynsm_servicessitemap_UserEntityInstanceDatas](#BKMK_msdynsm_servicessitemap_UserEntityInstanceDatas)
- [msdynsm_settingssitemap_UserEntityInstanceDatas](#BKMK_msdynsm_settingssitemap_UserEntityInstanceDatas)
- [theme_UserEntityInstanceDatas](#BKMK_theme_UserEntityInstanceDatas)
- [usermapping_UserEntityInstanceDatas](#BKMK_usermapping_UserEntityInstanceDatas)
- [knowledgearticle_UserEntityInstanceDatas](#BKMK_knowledgearticle_UserEntityInstanceDatas)
- [mailbox_userentityinstancedatas](#BKMK_mailbox_userentityinstancedatas)
- [channelaccessprofile_UserEntityInstanceDatas](#BKMK_channelaccessprofile_UserEntityInstanceDatas)
- [externalparty_UserEntityInstanceDatas](#BKMK_externalparty_UserEntityInstanceDatas)
- [profilerule_UserEntityInstanceDatas](#BKMK_profilerule_UserEntityInstanceDatas)
- [KnowledgeBaseRecord_UserEntityInstanceDatas](#BKMK_KnowledgeBaseRecord_UserEntityInstanceDatas)
- [userentityinstancedata_pluginassembly](#BKMK_userentityinstancedata_pluginassembly)
- [userentityinstancedata_letter](#BKMK_userentityinstancedata_letter)
- [userentityinstancedata_organization](#BKMK_userentityinstancedata_organization)
- [userentityinstancedata_owning_user](#BKMK_userentityinstancedata_owning_user)
- [userentityinstancedata_kbarticlecomment](#BKMK_userentityinstancedata_kbarticlecomment)
- [userentityinstancedata_processsession](#BKMK_userentityinstancedata_processsession)
- [userentityinstancedata_relationshiprolemap](#BKMK_userentityinstancedata_relationshiprolemap)
- [userentityinstancedata_sdkmessage](#BKMK_userentityinstancedata_sdkmessage)
- [userentityinstancedata_appointment](#BKMK_userentityinstancedata_appointment)
- [userentityinstancedata_contact](#BKMK_userentityinstancedata_contact)
- [userentityinstancedata_picklistmapping](#BKMK_userentityinstancedata_picklistmapping)
- [userentityinstancedata_workflow](#BKMK_userentityinstancedata_workflow)
- [userentityinstancedata_connectionrole](#BKMK_userentityinstancedata_connectionrole)
- [userentityinstancedata_sdkmessagepair](#BKMK_userentityinstancedata_sdkmessagepair)
- [userentityinstancedata_timezonelocalizedname](#BKMK_userentityinstancedata_timezonelocalizedname)
- [userentityinstancedata_savedquery](#BKMK_userentityinstancedata_savedquery)
- [userentityinstancedata_connection](#BKMK_userentityinstancedata_connection)
- [userentityinstancedata_socialactivity](#BKMK_userentityinstancedata_socialactivity)
- [userentityinstancedata_transactioncurrency](#BKMK_userentityinstancedata_transactioncurrency)
- [userentityinstancedata_importfile](#BKMK_userentityinstancedata_importfile)
- [userentityinstancedata_solution](#BKMK_userentityinstancedata_solution)
- [userentityinstancedata_transformationparametermapping](#BKMK_userentityinstancedata_transformationparametermapping)
- [userentityinstancedata_plugintype](#BKMK_userentityinstancedata_plugintype)
- [userentityinstancedata_userentityuisettings](#BKMK_userentityinstancedata_userentityuisettings)
- [userentityinstancedata_phonecall](#BKMK_userentityinstancedata_phonecall)
- [userentityinstancedata_sdkmessagerequest](#BKMK_userentityinstancedata_sdkmessagerequest)
- [userentityinstancedata_sdkmessageprocessingstepsecureconfig](#BKMK_userentityinstancedata_sdkmessageprocessingstepsecureconfig)
- [userentityinstancedata_customeraddress](#BKMK_userentityinstancedata_customeraddress)
- [userentityinstancedata_invaliddependency](#BKMK_userentityinstancedata_invaliddependency)
- [userentityinstancedata_recurringappointmentmaster](#BKMK_userentityinstancedata_recurringappointmentmaster)
- [userentityinstancedata_queueitem](#BKMK_userentityinstancedata_queueitem)
- [userentityinstancedata_reportvisibility](#BKMK_userentityinstancedata_reportvisibility)
- [userentityinstancedata_import](#BKMK_userentityinstancedata_import)
- [userentityinstancedata_goalrollupquery](#BKMK_userentityinstancedata_goalrollupquery)
- [userentityinstancedata_workflowlog](#BKMK_userentityinstancedata_workflowlog)
- [ConvertRule_userentityinstancedatas](#BKMK_ConvertRule_userentityinstancedatas)
- [userentityinstancedata_team](#BKMK_userentityinstancedata_team)
- [userentityinstancedata_ribboncustomization](#BKMK_userentityinstancedata_ribboncustomization)
- [userentityinstancedata_userqueryvisualization](#BKMK_userentityinstancedata_userqueryvisualization)
- [userentityinstancedata_businessunitnewsarticle](#BKMK_userentityinstancedata_businessunitnewsarticle)
- [userentityinstancedata_kbarticletemplate](#BKMK_userentityinstancedata_kbarticletemplate)
- [userentityinstancedata_connectionroleobjecttypecode](#BKMK_userentityinstancedata_connectionroleobjecttypecode)
- [userentityinstancedata_email](#BKMK_userentityinstancedata_email)
- [userentityinstancedata_sitemap](#BKMK_userentityinstancedata_sitemap)
- [userentityinstancedata_transformationmapping](#BKMK_userentityinstancedata_transformationmapping)
- [userentityinstancedata_fieldpermission](#BKMK_userentityinstancedata_fieldpermission)
- [userentityinstancedata_task](#BKMK_userentityinstancedata_task)
- [userentityinstancedata_savedqueryvisualization](#BKMK_userentityinstancedata_savedqueryvisualization)
- [userentityinstancedata_importlog](#BKMK_userentityinstancedata_importlog)
- [userentityinstancedata_connectionroleassociation](#BKMK_userentityinstancedata_connectionroleassociation)
- [userentityinstancedata_metric](#BKMK_userentityinstancedata_metric)
- [slabase_userentityinstancedatas](#BKMK_slabase_userentityinstancedatas)
- [userentityinstancedata_kbarticle](#BKMK_userentityinstancedata_kbarticle)
- [userentityinstancedata_annotation](#BKMK_userentityinstancedata_annotation)
- [userentityinstancedata_importentitymapping](#BKMK_userentityinstancedata_importentitymapping)
- [team_userentityinstancedata](#BKMK_team_userentityinstancedata)
- [userentityinstancedata_dependency](#BKMK_userentityinstancedata_dependency)
- [userentityinstancedata_duplicaterecord](#BKMK_userentityinstancedata_duplicaterecord)
- [userentityinstancedata_timezonedefinition](#BKMK_userentityinstancedata_timezonedefinition)
- [userentityinstancedata_calendar](#BKMK_userentityinstancedata_calendar)
- [userentityinstancedata_sdkmessageprocessingstep](#BKMK_userentityinstancedata_sdkmessageprocessingstep)
- [userentityinstancedata_systemuser](#BKMK_userentityinstancedata_systemuser)
- [userentityinstancedata_sdkmessagerequestfield](#BKMK_userentityinstancedata_sdkmessagerequestfield)
- [userentityinstancedata_plugintypestatistic](#BKMK_userentityinstancedata_plugintypestatistic)
- [userentityinstancedata_rollupfield](#BKMK_userentityinstancedata_rollupfield)
- [userentityinstancedata_relationshiprole](#BKMK_userentityinstancedata_relationshiprole)
- [userentityinstancedata_activitymimeattachment](#BKMK_userentityinstancedata_activitymimeattachment)
- [userentityinstancedata_role](#BKMK_userentityinstancedata_role)
- [userentityinstancedata_columnmapping](#BKMK_userentityinstancedata_columnmapping)
- [userentityinstancedata_publisheraddress](#BKMK_userentityinstancedata_publisheraddress)
- [userentityinstancedata_audit](#BKMK_userentityinstancedata_audit)
- [userentityinstancedata_subject](#BKMK_userentityinstancedata_subject)
- [userentityinstancedata_attributemap](#BKMK_userentityinstancedata_attributemap)
- [userentityinstancedata_lookupmapping](#BKMK_userentityinstancedata_lookupmapping)
- [userentityinstancedata_account](#BKMK_userentityinstancedata_account)
- [userentityinstancedata_sdkmessageresponsefield](#BKMK_userentityinstancedata_sdkmessageresponsefield)
- [userentityinstancedata_teammembership](#BKMK_userentityinstancedata_teammembership)
- [routingrule_userentityinstancedatas](#BKMK_routingrule_userentityinstancedatas)
- [userentityinstancedata_principalobjectattributeaccess](#BKMK_userentityinstancedata_principalobjectattributeaccess)
- [userentityinstancedata_duplicaterule](#BKMK_userentityinstancedata_duplicaterule)
- [userentityinstancedata_report](#BKMK_userentityinstancedata_report)
- [userentityinstancedata_isvconfig](#BKMK_userentityinstancedata_isvconfig)
- [userentityinstancedata_goal](#BKMK_userentityinstancedata_goal)
- [userentityinstancedata_mailmergetemplate](#BKMK_userentityinstancedata_mailmergetemplate)
- [userentityinstancedata_bulkdeleteoperation](#BKMK_userentityinstancedata_bulkdeleteoperation)
- [userentityinstancedata_sharepointsite](#BKMK_userentityinstancedata_sharepointsite)
- [userentityinstancedata_publisher](#BKMK_userentityinstancedata_publisher)
- [userentityinstancedata_businessunit](#BKMK_userentityinstancedata_businessunit)
- [userentityinstancedata_userform](#BKMK_userentityinstancedata_userform)
- [userentityinstancedata_license](#BKMK_userentityinstancedata_license)
- [userentityinstancedata_solutioncomponent](#BKMK_userentityinstancedata_solutioncomponent)
- [userentityinstancedata_reportcategory](#BKMK_userentityinstancedata_reportcategory)
- [userentityinstancedata_queue](#BKMK_userentityinstancedata_queue)
- [userentityinstancedata_duplicaterulecondition](#BKMK_userentityinstancedata_duplicaterulecondition)
- [userentityinstancedata_webresource](#BKMK_userentityinstancedata_webresource)
- [userentityinstancedata_workflowdependency](#BKMK_userentityinstancedata_workflowdependency)
- [routingruleitem_userentityinstancedatas](#BKMK_routingruleitem_userentityinstancedatas)
- [userentityinstancedata_customerrelationship](#BKMK_userentityinstancedata_customerrelationship)
- [userentityinstancedata_entitymap](#BKMK_userentityinstancedata_entitymap)
- [userentityinstancedata_fieldsecurityprofile](#BKMK_userentityinstancedata_fieldsecurityprofile)
- [userentityinstancedata_asyncoperation](#BKMK_userentityinstancedata_asyncoperation)
- [userentityinstancedata_timezonerule](#BKMK_userentityinstancedata_timezonerule)
- [userentityinstancedata_ownermapping](#BKMK_userentityinstancedata_ownermapping)
- [userentityinstancedata_activityparty](#BKMK_userentityinstancedata_activityparty)
- [userentityinstancedata_displaystring](#BKMK_userentityinstancedata_displaystring)
- [userentityinstancedata_importjob](#BKMK_userentityinstancedata_importjob)
- [userentityinstancedata_sdkmessageprocessingstepimage](#BKMK_userentityinstancedata_sdkmessageprocessingstepimage)
- [userentityinstancedata_template](#BKMK_userentityinstancedata_template)
- [userentityinstancedata_userquery](#BKMK_userentityinstancedata_userquery)
- [userentityinstancedata_bulkdeletefailure](#BKMK_userentityinstancedata_bulkdeletefailure)
- [userentityinstancedata_sharepointdocumentlocation](#BKMK_userentityinstancedata_sharepointdocumentlocation)
- [userentityinstancedata_sdkmessageresponse](#BKMK_userentityinstancedata_sdkmessageresponse)
- [userentityinstancedata_serviceendpoint](#BKMK_userentityinstancedata_serviceendpoint)
- [userentityinstancedata_reportentity](#BKMK_userentityinstancedata_reportentity)
- [userentityinstancedata_importmap](#BKMK_userentityinstancedata_importmap)
- [userentityinstancedata_fax](#BKMK_userentityinstancedata_fax)
- [userentityinstancedata_privilege](#BKMK_userentityinstancedata_privilege)
- [userentityinstancedata_sdkmessagefilter](#BKMK_userentityinstancedata_sdkmessagefilter)
- [userentityinstancedata_reportlink](#BKMK_userentityinstancedata_reportlink)


### <a name="BKMK_userentityinstancedata_territory"></a> userentityinstancedata_territory

**Added by**: Application Common Solution

See territory Entity [userentityinstancedata_territory](territory.md#BKMK_userentityinstancedata_territory) One-To-Many relationship.

### <a name="BKMK_holidaywrapper_UserEntityInstanceDatas"></a> holidaywrapper_UserEntityInstanceDatas

**Added by**: Application Common Patch Solution

See holidaywrapper Entity [holidaywrapper_UserEntityInstanceDatas](holidaywrapper.md#BKMK_holidaywrapper_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_accountleads_UserEntityInstanceDatas"></a> accountleads_UserEntityInstanceDatas

**Added by**: Lead Management Solution

See accountleads Entity [accountleads_UserEntityInstanceDatas](accountleads.md#BKMK_accountleads_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_contactleads_UserEntityInstanceDatas"></a> contactleads_UserEntityInstanceDatas

**Added by**: Lead Management Solution

See contactleads Entity [contactleads_UserEntityInstanceDatas](contactleads.md#BKMK_contactleads_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_leadaddress"></a> userentityinstancedata_leadaddress

**Added by**: Lead Management Solution

See leadaddress Entity [userentityinstancedata_leadaddress](leadaddress.md#BKMK_userentityinstancedata_leadaddress) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_lead"></a> userentityinstancedata_lead

**Added by**: Lead Management Solution

See lead Entity [userentityinstancedata_lead](lead.md#BKMK_userentityinstancedata_lead) One-To-Many relationship.

### <a name="BKMK_dynamicproperty_UserEntityInstanceDatas"></a> dynamicproperty_UserEntityInstanceDatas

**Added by**: Product Management Solution

See dynamicproperty Entity [dynamicproperty_UserEntityInstanceDatas](dynamicproperty.md#BKMK_dynamicproperty_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_dynamicpropertyassociation_UserEntityInstanceDatas"></a> dynamicpropertyassociation_UserEntityInstanceDatas

**Added by**: Product Management Solution

See dynamicpropertyassociation Entity [dynamicpropertyassociation_UserEntityInstanceDatas](dynamicpropertyassociation.md#BKMK_dynamicpropertyassociation_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_dynamicpropertyinstance_UserEntityInstanceDatas"></a> dynamicpropertyinstance_UserEntityInstanceDatas

**Added by**: Product Management Solution

See dynamicpropertyinstance Entity [dynamicpropertyinstance_UserEntityInstanceDatas](dynamicpropertyinstance.md#BKMK_dynamicpropertyinstance_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_dynamicpropertyoptionsetitem_UserEntityInstanceDatas"></a> dynamicpropertyoptionsetitem_UserEntityInstanceDatas

**Added by**: Product Management Solution

See dynamicpropertyoptionsetitem Entity [dynamicpropertyoptionsetitem_UserEntityInstanceDatas](dynamicpropertyoptionsetitem.md#BKMK_dynamicpropertyoptionsetitem_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_pricelevel"></a> userentityinstancedata_pricelevel

**Added by**: Product Management Solution

See pricelevel Entity [userentityinstancedata_pricelevel](pricelevel.md#BKMK_userentityinstancedata_pricelevel) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_product"></a> userentityinstancedata_product

**Added by**: Product Management Solution

See product Entity [userentityinstancedata_product](product.md#BKMK_userentityinstancedata_product) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_productassociation"></a> userentityinstancedata_productassociation

**Added by**: Product Management Solution

See productassociation Entity [userentityinstancedata_productassociation](productassociation.md#BKMK_userentityinstancedata_productassociation) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_productpricelevel"></a> userentityinstancedata_productpricelevel

**Added by**: Product Management Solution

See productpricelevel Entity [userentityinstancedata_productpricelevel](productpricelevel.md#BKMK_userentityinstancedata_productpricelevel) One-To-Many relationship.

### <a name="BKMK_productsubstitute_UserEntityInstanceDatas"></a> productsubstitute_UserEntityInstanceDatas

**Added by**: Product Management Solution

See productsubstitute Entity [productsubstitute_UserEntityInstanceDatas](productsubstitute.md#BKMK_productsubstitute_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_uom"></a> userentityinstancedata_uom

**Added by**: Product Management Solution

See uom Entity [userentityinstancedata_uom](uom.md#BKMK_userentityinstancedata_uom) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_uomschedule"></a> userentityinstancedata_uomschedule

**Added by**: Product Management Solution

See uomschedule Entity [userentityinstancedata_uomschedule](uomschedule.md#BKMK_userentityinstancedata_uomschedule) One-To-Many relationship.

### <a name="BKMK_bookableresource_UserEntityInstanceDatas"></a> bookableresource_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookableresource Entity [bookableresource_UserEntityInstanceDatas](bookableresource.md#BKMK_bookableresource_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_bookableresourcebooking_UserEntityInstanceDatas"></a> bookableresourcebooking_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookableresourcebooking Entity [bookableresourcebooking_UserEntityInstanceDatas](bookableresourcebooking.md#BKMK_bookableresourcebooking_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas"></a> bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookableresourcebookingexchangesyncidmapping Entity [bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas](bookableresourcebookingexchangesyncidmapping.md#BKMK_bookableresourcebookingexchangesyncidmapping_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_bookableresourcebookingheader_UserEntityInstanceDatas"></a> bookableresourcebookingheader_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookableresourcebookingheader Entity [bookableresourcebookingheader_UserEntityInstanceDatas](bookableresourcebookingheader.md#BKMK_bookableresourcebookingheader_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_bookableresourcecategory_UserEntityInstanceDatas"></a> bookableresourcecategory_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookableresourcecategory Entity [bookableresourcecategory_UserEntityInstanceDatas](bookableresourcecategory.md#BKMK_bookableresourcecategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_bookableresourcecategoryassn_UserEntityInstanceDatas"></a> bookableresourcecategoryassn_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookableresourcecategoryassn Entity [bookableresourcecategoryassn_UserEntityInstanceDatas](bookableresourcecategoryassn.md#BKMK_bookableresourcecategoryassn_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_bookableresourcecharacteristic_UserEntityInstanceDatas"></a> bookableresourcecharacteristic_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookableresourcecharacteristic Entity [bookableresourcecharacteristic_UserEntityInstanceDatas](bookableresourcecharacteristic.md#BKMK_bookableresourcecharacteristic_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_bookableresourcegroup_UserEntityInstanceDatas"></a> bookableresourcegroup_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookableresourcegroup Entity [bookableresourcegroup_UserEntityInstanceDatas](bookableresourcegroup.md#BKMK_bookableresourcegroup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_bookingstatus_UserEntityInstanceDatas"></a> bookingstatus_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See bookingstatus Entity [bookingstatus_UserEntityInstanceDatas](bookingstatus.md#BKMK_bookingstatus_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_characteristic_UserEntityInstanceDatas"></a> characteristic_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See characteristic Entity [characteristic_UserEntityInstanceDatas](characteristic.md#BKMK_characteristic_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_ratingmodel_UserEntityInstanceDatas"></a> ratingmodel_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See ratingmodel Entity [ratingmodel_UserEntityInstanceDatas](ratingmodel.md#BKMK_ratingmodel_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_ratingvalue_UserEntityInstanceDatas"></a> ratingvalue_UserEntityInstanceDatas

**Added by**: Scheduling Solution

See ratingvalue Entity [ratingvalue_UserEntityInstanceDatas](ratingvalue.md#BKMK_ratingvalue_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_bulkoperation"></a> userentityinstancedata_bulkoperation

**Added by**: Marketing Solution

See bulkoperation Entity [userentityinstancedata_bulkoperation](bulkoperation.md#BKMK_userentityinstancedata_bulkoperation) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_bulkoperationlog"></a> userentityinstancedata_bulkoperationlog

**Added by**: Marketing Solution

See bulkoperationlog Entity [userentityinstancedata_bulkoperationlog](bulkoperationlog.md#BKMK_userentityinstancedata_bulkoperationlog) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_campaign"></a> userentityinstancedata_campaign

**Added by**: Marketing Solution

See campaign Entity [userentityinstancedata_campaign](campaign.md#BKMK_userentityinstancedata_campaign) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_campaignactivity"></a> userentityinstancedata_campaignactivity

**Added by**: Marketing Solution

See campaignactivity Entity [userentityinstancedata_campaignactivity](campaignactivity.md#BKMK_userentityinstancedata_campaignactivity) One-To-Many relationship.

### <a name="BKMK_campaignactivityitem_UserEntityInstanceDatas"></a> campaignactivityitem_UserEntityInstanceDatas

**Added by**: Marketing Solution

See campaignactivityitem Entity [campaignactivityitem_UserEntityInstanceDatas](campaignactivityitem.md#BKMK_campaignactivityitem_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_campaignitem_UserEntityInstanceDatas"></a> campaignitem_UserEntityInstanceDatas

**Added by**: Marketing Solution

See campaignitem Entity [campaignitem_UserEntityInstanceDatas](campaignitem.md#BKMK_campaignitem_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_campaignresponse"></a> userentityinstancedata_campaignresponse

**Added by**: Marketing Solution

See campaignresponse Entity [userentityinstancedata_campaignresponse](campaignresponse.md#BKMK_userentityinstancedata_campaignresponse) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_list"></a> userentityinstancedata_list

**Added by**: Marketing Solution

See list Entity [userentityinstancedata_list](list.md#BKMK_userentityinstancedata_list) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_listmember"></a> userentityinstancedata_listmember

**Added by**: Marketing Solution

See listmember Entity [userentityinstancedata_listmember](listmember.md#BKMK_userentityinstancedata_listmember) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_campaignactivityitem"></a> userentityinstancedata_campaignactivityitem

**Added by**: Marketing Solution

See campaignactivityitem Entity [userentityinstancedata_campaignactivityitem](campaignactivityitem.md#BKMK_userentityinstancedata_campaignactivityitem) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_campaignitem"></a> userentityinstancedata_campaignitem

**Added by**: Marketing Solution

See campaignitem Entity [userentityinstancedata_campaignitem](campaignitem.md#BKMK_userentityinstancedata_campaignitem) One-To-Many relationship.

### <a name="BKMK_msdyn_databaseversion_UserEntityInstanceDatas"></a> msdyn_databaseversion_UserEntityInstanceDatas

**Added by**: Solution Upgrade Infrastructure Solution

See msdyn_databaseversion Entity [msdyn_databaseversion_UserEntityInstanceDatas](msdyn_databaseversion.md#BKMK_msdyn_databaseversion_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_upgraderun_UserEntityInstanceDatas"></a> msdyn_upgraderun_UserEntityInstanceDatas

**Added by**: Solution Upgrade Infrastructure Solution

See msdyn_upgraderun Entity [msdyn_upgraderun_UserEntityInstanceDatas](msdyn_upgraderun.md#BKMK_msdyn_upgraderun_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_upgradestep_UserEntityInstanceDatas"></a> msdyn_upgradestep_UserEntityInstanceDatas

**Added by**: Solution Upgrade Infrastructure Solution

See msdyn_upgradestep Entity [msdyn_upgradestep_UserEntityInstanceDatas](msdyn_upgradestep.md#BKMK_msdyn_upgradestep_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_upgradeversion_UserEntityInstanceDatas"></a> msdyn_upgradeversion_UserEntityInstanceDatas

**Added by**: Solution Upgrade Infrastructure Solution

See msdyn_upgradeversion Entity [msdyn_upgradeversion_UserEntityInstanceDatas](msdyn_upgradeversion.md#BKMK_msdyn_upgradeversion_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_commitment"></a> userentityinstancedata_commitment

**Added by**: Service Solution

See commitment Entity [userentityinstancedata_commitment](commitment.md#BKMK_userentityinstancedata_commitment) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_constraintbasedgroup"></a> userentityinstancedata_constraintbasedgroup

**Added by**: Service Solution

See constraintbasedgroup Entity [userentityinstancedata_constraintbasedgroup](constraintbasedgroup.md#BKMK_userentityinstancedata_constraintbasedgroup) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_contract"></a> userentityinstancedata_contract

**Added by**: Service Solution

See contract Entity [userentityinstancedata_contract](contract.md#BKMK_userentityinstancedata_contract) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_contractdetail"></a> userentityinstancedata_contractdetail

**Added by**: Service Solution

See contractdetail Entity [userentityinstancedata_contractdetail](contractdetail.md#BKMK_userentityinstancedata_contractdetail) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_contracttemplate"></a> userentityinstancedata_contracttemplate

**Added by**: Service Solution

See contracttemplate Entity [userentityinstancedata_contracttemplate](contracttemplate.md#BKMK_userentityinstancedata_contracttemplate) One-To-Many relationship.

### <a name="BKMK_entitlement_UserEntityInstanceDatas"></a> entitlement_UserEntityInstanceDatas

**Added by**: Service Solution

See entitlement Entity [entitlement_UserEntityInstanceDatas](entitlement.md#BKMK_entitlement_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_entitlementchannel_UserEntityInstanceDatas"></a> entitlementchannel_UserEntityInstanceDatas

**Added by**: Service Solution

See entitlementchannel Entity [entitlementchannel_UserEntityInstanceDatas](entitlementchannel.md#BKMK_entitlementchannel_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_entitlementcontacts_UserEntityInstanceDatas"></a> entitlementcontacts_UserEntityInstanceDatas

**Added by**: Service Solution

See entitlementcontacts Entity [entitlementcontacts_UserEntityInstanceDatas](entitlementcontacts.md#BKMK_entitlementcontacts_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_entitlementproducts_UserEntityInstanceDatas"></a> entitlementproducts_UserEntityInstanceDatas

**Added by**: Service Solution

See entitlementproducts Entity [entitlementproducts_UserEntityInstanceDatas](entitlementproducts.md#BKMK_entitlementproducts_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_entitlementtemplate_UserEntityInstanceDatas"></a> entitlementtemplate_UserEntityInstanceDatas

**Added by**: Service Solution

See entitlementtemplate Entity [entitlementtemplate_UserEntityInstanceDatas](entitlementtemplate.md#BKMK_entitlementtemplate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_entitlementtemplatechannel_UserEntityInstanceDatas"></a> entitlementtemplatechannel_UserEntityInstanceDatas

**Added by**: Service Solution

See entitlementtemplatechannel Entity [entitlementtemplatechannel_UserEntityInstanceDatas](entitlementtemplatechannel.md#BKMK_entitlementtemplatechannel_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_entitlementtemplateproducts_UserEntityInstanceDatas"></a> entitlementtemplateproducts_UserEntityInstanceDatas

**Added by**: Service Solution

See entitlementtemplateproducts Entity [entitlementtemplateproducts_UserEntityInstanceDatas](entitlementtemplateproducts.md#BKMK_entitlementtemplateproducts_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_equipment"></a> userentityinstancedata_equipment

**Added by**: Service Solution

See equipment Entity [userentityinstancedata_equipment](equipment.md#BKMK_userentityinstancedata_equipment) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_incident"></a> userentityinstancedata_incident

**Added by**: Service Solution

See incident Entity [userentityinstancedata_incident](incident.md#BKMK_userentityinstancedata_incident) One-To-Many relationship.

### <a name="BKMK_incidentknowledgebaserecord_UserEntityInstanceDatas"></a> incidentknowledgebaserecord_UserEntityInstanceDatas

**Added by**: Service Solution

See incidentknowledgebaserecord Entity [incidentknowledgebaserecord_UserEntityInstanceDatas](incidentknowledgebaserecord.md#BKMK_incidentknowledgebaserecord_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_incidentresolution"></a> userentityinstancedata_incidentresolution

**Added by**: Service Solution

See incidentresolution Entity [userentityinstancedata_incidentresolution](incidentresolution.md#BKMK_userentityinstancedata_incidentresolution) One-To-Many relationship.

### <a name="BKMK_knowledgearticleincident_UserEntityInstanceDatas"></a> knowledgearticleincident_UserEntityInstanceDatas

**Added by**: Service Solution

See knowledgearticleincident Entity [knowledgearticleincident_UserEntityInstanceDatas](knowledgearticleincident.md#BKMK_knowledgearticleincident_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_phonetocaseprocess_UserEntityInstanceDatas"></a> phonetocaseprocess_UserEntityInstanceDatas

**Added by**: Service Solution

See phonetocaseprocess Entity [phonetocaseprocess_UserEntityInstanceDatas](phonetocaseprocess.md#BKMK_phonetocaseprocess_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_resource"></a> userentityinstancedata_resource

**Added by**: Service Solution

See resource Entity [userentityinstancedata_resource](resource.md#BKMK_userentityinstancedata_resource) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_resourcegroup"></a> userentityinstancedata_resourcegroup

**Added by**: Service Solution

See resourcegroup Entity [userentityinstancedata_resourcegroup](resourcegroup.md#BKMK_userentityinstancedata_resourcegroup) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_resourcespec"></a> userentityinstancedata_resourcespec

**Added by**: Service Solution

See resourcespec Entity [userentityinstancedata_resourcespec](resourcespec.md#BKMK_userentityinstancedata_resourcespec) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_service"></a> userentityinstancedata_service

**Added by**: Service Solution

See service Entity [userentityinstancedata_service](service.md#BKMK_userentityinstancedata_service) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_serviceappointment"></a> userentityinstancedata_serviceappointment

**Added by**: Service Solution

See serviceappointment Entity [userentityinstancedata_serviceappointment](serviceappointment.md#BKMK_userentityinstancedata_serviceappointment) One-To-Many relationship.

### <a name="BKMK_servicecontractcontacts_UserEntityInstanceDatas"></a> servicecontractcontacts_UserEntityInstanceDatas

**Added by**: Service Solution

See servicecontractcontacts Entity [servicecontractcontacts_UserEntityInstanceDatas](servicecontractcontacts.md#BKMK_servicecontractcontacts_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_topic_UserEntityInstanceDatas"></a> topic_UserEntityInstanceDatas

**Added by**: Service Solution

See topic Entity [topic_UserEntityInstanceDatas](topic.md#BKMK_topic_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_topichistory_UserEntityInstanceDatas"></a> topichistory_UserEntityInstanceDatas

**Added by**: Service Solution

See topichistory Entity [topichistory_UserEntityInstanceDatas](topichistory.md#BKMK_topichistory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_topicmodel_UserEntityInstanceDatas"></a> topicmodel_UserEntityInstanceDatas

**Added by**: Service Solution

See topicmodel Entity [topicmodel_UserEntityInstanceDatas](topicmodel.md#BKMK_topicmodel_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_topicmodelconfiguration_UserEntityInstanceDatas"></a> topicmodelconfiguration_UserEntityInstanceDatas

**Added by**: Service Solution

See topicmodelconfiguration Entity [topicmodelconfiguration_UserEntityInstanceDatas](topicmodelconfiguration.md#BKMK_topicmodelconfiguration_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_topicmodelexecutionhistory_UserEntityInstanceDatas"></a> topicmodelexecutionhistory_UserEntityInstanceDatas

**Added by**: Service Solution

See topicmodelexecutionhistory Entity [topicmodelexecutionhistory_UserEntityInstanceDatas](topicmodelexecutionhistory.md#BKMK_topicmodelexecutionhistory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_site"></a> userentityinstancedata_site

**Added by**: Service Solution

See site Entity [userentityinstancedata_site](site.md#BKMK_userentityinstancedata_site) One-To-Many relationship.

### <a name="BKMK_entitlemententityallocationtypemapping_UserEntityInstanceDatas"></a> entitlemententityallocationtypemapping_UserEntityInstanceDatas

**Added by**: Service Patch Solution

See entitlemententityallocationtypemapping Entity [entitlemententityallocationtypemapping_UserEntityInstanceDatas](entitlemententityallocationtypemapping.md#BKMK_entitlemententityallocationtypemapping_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_callablecontext_UserEntityInstanceDatas"></a> msdyn_callablecontext_UserEntityInstanceDatas

**Added by**: Playbook Solution

See msdyn_callablecontext Entity [msdyn_callablecontext_UserEntityInstanceDatas](msdyn_callablecontext.md#BKMK_msdyn_callablecontext_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_playbookactivity_UserEntityInstanceDatas"></a> msdyn_playbookactivity_UserEntityInstanceDatas

**Added by**: Playbook Solution

See msdyn_playbookactivity Entity [msdyn_playbookactivity_UserEntityInstanceDatas](msdyn_playbookactivity.md#BKMK_msdyn_playbookactivity_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_playbookactivityattribute_UserEntityInstanceDatas"></a> msdyn_playbookactivityattribute_UserEntityInstanceDatas

**Added by**: Playbook Solution

See msdyn_playbookactivityattribute Entity [msdyn_playbookactivityattribute_UserEntityInstanceDatas](msdyn_playbookactivityattribute.md#BKMK_msdyn_playbookactivityattribute_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_playbookcategory_UserEntityInstanceDatas"></a> msdyn_playbookcategory_UserEntityInstanceDatas

**Added by**: Playbook Solution

See msdyn_playbookcategory Entity [msdyn_playbookcategory_UserEntityInstanceDatas](msdyn_playbookcategory.md#BKMK_msdyn_playbookcategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_playbookinstance_UserEntityInstanceDatas"></a> msdyn_playbookinstance_UserEntityInstanceDatas

**Added by**: Playbook Solution

See msdyn_playbookinstance Entity [msdyn_playbookinstance_UserEntityInstanceDatas](msdyn_playbookinstance.md#BKMK_msdyn_playbookinstance_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_playbooktemplate_UserEntityInstanceDatas"></a> msdyn_playbooktemplate_UserEntityInstanceDatas

**Added by**: Playbook Solution

See msdyn_playbooktemplate Entity [msdyn_playbooktemplate_UserEntityInstanceDatas](msdyn_playbooktemplate.md#BKMK_msdyn_playbooktemplate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_competitorproduct_UserEntityInstanceDatas"></a> competitorproduct_UserEntityInstanceDatas

**Added by**: Sales Solution

See competitorproduct Entity [competitorproduct_UserEntityInstanceDatas](competitorproduct.md#BKMK_competitorproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_competitorsalesliterature_UserEntityInstanceDatas"></a> competitorsalesliterature_UserEntityInstanceDatas

**Added by**: Sales Solution

See competitorsalesliterature Entity [competitorsalesliterature_UserEntityInstanceDatas](competitorsalesliterature.md#BKMK_competitorsalesliterature_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_contactinvoices_UserEntityInstanceDatas"></a> contactinvoices_UserEntityInstanceDatas

**Added by**: Sales Solution

See contactinvoices Entity [contactinvoices_UserEntityInstanceDatas](contactinvoices.md#BKMK_contactinvoices_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_contactorders_UserEntityInstanceDatas"></a> contactorders_UserEntityInstanceDatas

**Added by**: Sales Solution

See contactorders Entity [contactorders_UserEntityInstanceDatas](contactorders.md#BKMK_contactorders_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_contactquotes_UserEntityInstanceDatas"></a> contactquotes_UserEntityInstanceDatas

**Added by**: Sales Solution

See contactquotes Entity [contactquotes_UserEntityInstanceDatas](contactquotes.md#BKMK_contactquotes_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_customeropportunityrole"></a> userentityinstancedata_customeropportunityrole

**Added by**: Sales Solution

See customeropportunityrole Entity [userentityinstancedata_customeropportunityrole](customeropportunityrole.md#BKMK_userentityinstancedata_customeropportunityrole) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_discount"></a> userentityinstancedata_discount

**Added by**: Sales Solution

See discount Entity [userentityinstancedata_discount](discount.md#BKMK_userentityinstancedata_discount) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_discounttype"></a> userentityinstancedata_discounttype

**Added by**: Sales Solution

See discounttype Entity [userentityinstancedata_discounttype](discounttype.md#BKMK_userentityinstancedata_discounttype) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_invoice"></a> userentityinstancedata_invoice

**Added by**: Sales Solution

See invoice Entity [userentityinstancedata_invoice](invoice.md#BKMK_userentityinstancedata_invoice) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_invoicedetail"></a> userentityinstancedata_invoicedetail

**Added by**: Sales Solution

See invoicedetail Entity [userentityinstancedata_invoicedetail](invoicedetail.md#BKMK_userentityinstancedata_invoicedetail) One-To-Many relationship.

### <a name="BKMK_leadcompetitors_UserEntityInstanceDatas"></a> leadcompetitors_UserEntityInstanceDatas

**Added by**: Sales Solution

See leadcompetitors Entity [leadcompetitors_UserEntityInstanceDatas](leadcompetitors.md#BKMK_leadcompetitors_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_leadproduct_UserEntityInstanceDatas"></a> leadproduct_UserEntityInstanceDatas

**Added by**: Sales Solution

See leadproduct Entity [leadproduct_UserEntityInstanceDatas](leadproduct.md#BKMK_leadproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_leadtoopportunitysalesprocess_UserEntityInstanceDatas"></a> leadtoopportunitysalesprocess_UserEntityInstanceDatas

**Added by**: Sales Solution

See leadtoopportunitysalesprocess Entity [leadtoopportunitysalesprocess_UserEntityInstanceDatas](leadtoopportunitysalesprocess.md#BKMK_leadtoopportunitysalesprocess_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_opportunity"></a> userentityinstancedata_opportunity

**Added by**: Sales Solution

See opportunity Entity [userentityinstancedata_opportunity](opportunity.md#BKMK_userentityinstancedata_opportunity) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_opportunityclose"></a> userentityinstancedata_opportunityclose

**Added by**: Sales Solution

See opportunityclose Entity [userentityinstancedata_opportunityclose](opportunityclose.md#BKMK_userentityinstancedata_opportunityclose) One-To-Many relationship.

### <a name="BKMK_opportunitycompetitors_UserEntityInstanceDatas"></a> opportunitycompetitors_UserEntityInstanceDatas

**Added by**: Sales Solution

See opportunitycompetitors Entity [opportunitycompetitors_UserEntityInstanceDatas](opportunitycompetitors.md#BKMK_opportunitycompetitors_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_opportunityproduct"></a> userentityinstancedata_opportunityproduct

**Added by**: Sales Solution

See opportunityproduct Entity [userentityinstancedata_opportunityproduct](opportunityproduct.md#BKMK_userentityinstancedata_opportunityproduct) One-To-Many relationship.

### <a name="BKMK_opportunitysalesprocess_UserEntityInstanceDatas"></a> opportunitysalesprocess_UserEntityInstanceDatas

**Added by**: Sales Solution

See opportunitysalesprocess Entity [opportunitysalesprocess_UserEntityInstanceDatas](opportunitysalesprocess.md#BKMK_opportunitysalesprocess_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_orderclose"></a> userentityinstancedata_orderclose

**Added by**: Sales Solution

See orderclose Entity [userentityinstancedata_orderclose](orderclose.md#BKMK_userentityinstancedata_orderclose) One-To-Many relationship.

### <a name="BKMK_productsalesliterature_UserEntityInstanceDatas"></a> productsalesliterature_UserEntityInstanceDatas

**Added by**: Sales Solution

See productsalesliterature Entity [productsalesliterature_UserEntityInstanceDatas](productsalesliterature.md#BKMK_productsalesliterature_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_quote"></a> userentityinstancedata_quote

**Added by**: Sales Solution

See quote Entity [userentityinstancedata_quote](quote.md#BKMK_userentityinstancedata_quote) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_quoteclose"></a> userentityinstancedata_quoteclose

**Added by**: Sales Solution

See quoteclose Entity [userentityinstancedata_quoteclose](quoteclose.md#BKMK_userentityinstancedata_quoteclose) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_quotedetail"></a> userentityinstancedata_quotedetail

**Added by**: Sales Solution

See quotedetail Entity [userentityinstancedata_quotedetail](quotedetail.md#BKMK_userentityinstancedata_quotedetail) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_salesliterature"></a> userentityinstancedata_salesliterature

**Added by**: Sales Solution

See salesliterature Entity [userentityinstancedata_salesliterature](salesliterature.md#BKMK_userentityinstancedata_salesliterature) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_salesliteratureitem"></a> userentityinstancedata_salesliteratureitem

**Added by**: Sales Solution

See salesliteratureitem Entity [userentityinstancedata_salesliteratureitem](salesliteratureitem.md#BKMK_userentityinstancedata_salesliteratureitem) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_salesorder"></a> userentityinstancedata_salesorder

**Added by**: Sales Solution

See salesorder Entity [userentityinstancedata_salesorder](salesorder.md#BKMK_userentityinstancedata_salesorder) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_salesorderdetail"></a> userentityinstancedata_salesorderdetail

**Added by**: Sales Solution

See salesorderdetail Entity [userentityinstancedata_salesorderdetail](salesorderdetail.md#BKMK_userentityinstancedata_salesorderdetail) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_competitor"></a> userentityinstancedata_competitor

**Added by**: Sales Solution

See competitor Entity [userentityinstancedata_competitor](competitor.md#BKMK_userentityinstancedata_competitor) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_competitorproduct"></a> userentityinstancedata_competitorproduct

**Added by**: Sales Solution

See competitorproduct Entity [userentityinstancedata_competitorproduct](competitorproduct.md#BKMK_userentityinstancedata_competitorproduct) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_productsalesliterature"></a> userentityinstancedata_productsalesliterature

**Added by**: Sales Solution

See productsalesliterature Entity [userentityinstancedata_productsalesliterature](productsalesliterature.md#BKMK_userentityinstancedata_productsalesliterature) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_competitorsalesliterature"></a> userentityinstancedata_competitorsalesliterature

**Added by**: Sales Solution

See competitorsalesliterature Entity [userentityinstancedata_competitorsalesliterature](competitorsalesliterature.md#BKMK_userentityinstancedata_competitorsalesliterature) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_leadproduct"></a> userentityinstancedata_leadproduct

**Added by**: Sales Solution

See leadproduct Entity [userentityinstancedata_leadproduct](leadproduct.md#BKMK_userentityinstancedata_leadproduct) One-To-Many relationship.

### <a name="BKMK_adminsettingsentity_UserEntityInstanceDatas"></a> adminsettingsentity_UserEntityInstanceDatas

**Added by**: Sales Patch Solution

See adminsettingsentity Entity [adminsettingsentity_UserEntityInstanceDatas](adminsettingsentity.md#BKMK_adminsettingsentity_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_forecastdefinition_UserEntityInstanceDatas"></a> msdyn_forecastdefinition_UserEntityInstanceDatas

**Added by**: Forecasting Solution

See msdyn_forecastdefinition Entity [msdyn_forecastdefinition_UserEntityInstanceDatas](msdyn_forecastdefinition.md#BKMK_msdyn_forecastdefinition_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_forecastinstance_UserEntityInstanceDatas"></a> msdyn_forecastinstance_UserEntityInstanceDatas

**Added by**: Forecasting Solution

See msdyn_forecastinstance Entity [msdyn_forecastinstance_UserEntityInstanceDatas](msdyn_forecastinstance.md#BKMK_msdyn_forecastinstance_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_forecastrecurrence_UserEntityInstanceDatas"></a> msdyn_forecastrecurrence_UserEntityInstanceDatas

**Added by**: Forecasting Solution

See msdyn_forecastrecurrence Entity [msdyn_forecastrecurrence_UserEntityInstanceDatas](msdyn_forecastrecurrence.md#BKMK_msdyn_forecastrecurrence_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_relationshipinsightsunifiedconfig_UserEntityInstanceDatas"></a> msdyn_relationshipinsightsunifiedconfig_UserEntityInstanceDatas

**Added by**: SI Common Solution

See msdyn_relationshipinsightsunifiedconfig Entity [msdyn_relationshipinsightsunifiedconfig_UserEntityInstanceDatas](msdyn_relationshipinsightsunifiedconfig.md#BKMK_msdyn_relationshipinsightsunifiedconfig_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_siconfig_UserEntityInstanceDatas"></a> msdyn_siconfig_UserEntityInstanceDatas

**Added by**: SI Common Solution

See msdyn_siconfig Entity [msdyn_siconfig_UserEntityInstanceDatas](msdyn_siconfig.md#BKMK_msdyn_siconfig_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_untrackedappointment_UserEntityInstanceDatas"></a> msdyn_untrackedappointment_UserEntityInstanceDatas

**Added by**: AutoDataCapture Solution

See msdyn_untrackedappointment Entity [msdyn_untrackedappointment_UserEntityInstanceDatas](msdyn_untrackedappointment.md#BKMK_msdyn_untrackedappointment_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_notesanalysisconfig_UserEntityInstanceDatas"></a> msdyn_notesanalysisconfig_UserEntityInstanceDatas

**Added by**: Notesanalysis Solution

See msdyn_notesanalysisconfig Entity [msdyn_notesanalysisconfig_UserEntityInstanceDatas](msdyn_notesanalysisconfig.md#BKMK_msdyn_notesanalysisconfig_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_icebreakersconfig_UserEntityInstanceDatas"></a> msdyn_icebreakersconfig_UserEntityInstanceDatas

**Added by**: Talking points Solution

See msdyn_icebreakersconfig Entity [msdyn_icebreakersconfig_UserEntityInstanceDatas](msdyn_icebreakersconfig.md#BKMK_msdyn_icebreakersconfig_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_postalbum_UserEntityInstanceDatas"></a> msdyn_postalbum_UserEntityInstanceDatas

**Added by**: Activity Feeds Solution

See msdyn_postalbum Entity [msdyn_postalbum_UserEntityInstanceDatas](msdyn_postalbum.md#BKMK_msdyn_postalbum_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_postconfig_UserEntityInstanceDatas"></a> msdyn_postconfig_UserEntityInstanceDatas

**Added by**: Activity Feeds Solution

See msdyn_postconfig Entity [msdyn_postconfig_UserEntityInstanceDatas](msdyn_postconfig.md#BKMK_msdyn_postconfig_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_postruleconfig_UserEntityInstanceDatas"></a> msdyn_postruleconfig_UserEntityInstanceDatas

**Added by**: Activity Feeds Solution

See msdyn_postruleconfig Entity [msdyn_postruleconfig_UserEntityInstanceDatas](msdyn_postruleconfig.md#BKMK_msdyn_postruleconfig_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_wallsavedquery_UserEntityInstanceDatas"></a> msdyn_wallsavedquery_UserEntityInstanceDatas

**Added by**: Activity Feeds Solution

See msdyn_wallsavedquery Entity [msdyn_wallsavedquery_UserEntityInstanceDatas](msdyn_wallsavedquery.md#BKMK_msdyn_wallsavedquery_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_wallsavedqueryusersettings_UserEntityInstanceDatas"></a> msdyn_wallsavedqueryusersettings_UserEntityInstanceDatas

**Added by**: Activity Feeds Solution

See msdyn_wallsavedqueryusersettings Entity [msdyn_wallsavedqueryusersettings_UserEntityInstanceDatas](msdyn_wallsavedqueryusersettings.md#BKMK_msdyn_wallsavedqueryusersettings_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msfp_emailtemplate_UserEntityInstanceDatas"></a> msfp_emailtemplate_UserEntityInstanceDatas

**Added by**: Microsoft Forms Pro Solution

See msfp_emailtemplate Entity [msfp_emailtemplate_UserEntityInstanceDatas](msfp_emailtemplate.md#BKMK_msfp_emailtemplate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msfp_question_UserEntityInstanceDatas"></a> msfp_question_UserEntityInstanceDatas

**Added by**: Microsoft Forms Pro Solution

See msfp_question Entity [msfp_question_UserEntityInstanceDatas](msfp_question.md#BKMK_msfp_question_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msfp_questionresponse_UserEntityInstanceDatas"></a> msfp_questionresponse_UserEntityInstanceDatas

**Added by**: Microsoft Forms Pro Solution

See msfp_questionresponse Entity [msfp_questionresponse_UserEntityInstanceDatas](msfp_questionresponse.md#BKMK_msfp_questionresponse_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msfp_survey_UserEntityInstanceDatas"></a> msfp_survey_UserEntityInstanceDatas

**Added by**: Microsoft Forms Pro Solution

See msfp_survey Entity [msfp_survey_UserEntityInstanceDatas](msfp_survey.md#BKMK_msfp_survey_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msfp_surveyinvite_UserEntityInstanceDatas"></a> msfp_surveyinvite_UserEntityInstanceDatas

**Added by**: Active Solution Solution

See msfp_surveyinvite Entity [msfp_surveyinvite_UserEntityInstanceDatas](msfp_surveyinvite.md#BKMK_msfp_surveyinvite_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msfp_surveyresponse_UserEntityInstanceDatas"></a> msfp_surveyresponse_UserEntityInstanceDatas

**Added by**: Active Solution Solution

See msfp_surveyresponse Entity [msfp_surveyresponse_UserEntityInstanceDatas](msfp_surveyresponse.md#BKMK_msfp_surveyresponse_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msfp_unsubscribedrecipient_UserEntityInstanceDatas"></a> msfp_unsubscribedrecipient_UserEntityInstanceDatas

**Added by**: Microsoft Forms Pro Solution

See msfp_unsubscribedrecipient Entity [msfp_unsubscribedrecipient_UserEntityInstanceDatas](msfp_unsubscribedrecipient.md#BKMK_msfp_unsubscribedrecipient_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_teamscollaboration_UserEntityInstanceDatas"></a> msdyn_teamscollaboration_UserEntityInstanceDatas

**Added by**: This solution contains Office Productivity implementation Solution

See msdyn_teamscollaboration Entity [msdyn_teamscollaboration_UserEntityInstanceDatas](msdyn_teamscollaboration.md#BKMK_msdyn_teamscollaboration_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_actual_UserEntityInstanceDatas"></a> msdyn_actual_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_actual Entity [msdyn_actual_UserEntityInstanceDatas](msdyn_actual.md#BKMK_msdyn_actual_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bookableresourceassociation_UserEntityInstanceDatas"></a> msdyn_bookableresourceassociation_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_bookableresourceassociation Entity [msdyn_bookableresourceassociation_UserEntityInstanceDatas](msdyn_bookableresourceassociation.md#BKMK_msdyn_bookableresourceassociation_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bookingalert_UserEntityInstanceDatas"></a> msdyn_bookingalert_UserEntityInstanceDatas

**Added by**: Active Solution Solution

See msdyn_bookingalert Entity [msdyn_bookingalert_UserEntityInstanceDatas](msdyn_bookingalert.md#BKMK_msdyn_bookingalert_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bookingalertstatus_UserEntityInstanceDatas"></a> msdyn_bookingalertstatus_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_bookingalertstatus Entity [msdyn_bookingalertstatus_UserEntityInstanceDatas](msdyn_bookingalertstatus.md#BKMK_msdyn_bookingalertstatus_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bookingchange_UserEntityInstanceDatas"></a> msdyn_bookingchange_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_bookingchange Entity [msdyn_bookingchange_UserEntityInstanceDatas](msdyn_bookingchange.md#BKMK_msdyn_bookingchange_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bookingrule_UserEntityInstanceDatas"></a> msdyn_bookingrule_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_bookingrule Entity [msdyn_bookingrule_UserEntityInstanceDatas](msdyn_bookingrule.md#BKMK_msdyn_bookingrule_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bookingsetupmetadata_UserEntityInstanceDatas"></a> msdyn_bookingsetupmetadata_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_bookingsetupmetadata Entity [msdyn_bookingsetupmetadata_UserEntityInstanceDatas](msdyn_bookingsetupmetadata.md#BKMK_msdyn_bookingsetupmetadata_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_businessclosure_UserEntityInstanceDatas"></a> msdyn_businessclosure_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_businessclosure Entity [msdyn_businessclosure_UserEntityInstanceDatas](msdyn_businessclosure.md#BKMK_msdyn_businessclosure_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_clientextension_UserEntityInstanceDatas"></a> msdyn_clientextension_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_clientextension Entity [msdyn_clientextension_UserEntityInstanceDatas](msdyn_clientextension.md#BKMK_msdyn_clientextension_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_configuration_UserEntityInstanceDatas"></a> msdyn_configuration_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_configuration Entity [msdyn_configuration_UserEntityInstanceDatas](msdyn_configuration.md#BKMK_msdyn_configuration_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_organizationalunit_UserEntityInstanceDatas"></a> msdyn_organizationalunit_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_organizationalunit Entity [msdyn_organizationalunit_UserEntityInstanceDatas](msdyn_organizationalunit.md#BKMK_msdyn_organizationalunit_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_priority_UserEntityInstanceDatas"></a> msdyn_priority_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_priority Entity [msdyn_priority_UserEntityInstanceDatas](msdyn_priority.md#BKMK_msdyn_priority_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_requirementcharacteristic_UserEntityInstanceDatas"></a> msdyn_requirementcharacteristic_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_requirementcharacteristic Entity [msdyn_requirementcharacteristic_UserEntityInstanceDatas](msdyn_requirementcharacteristic.md#BKMK_msdyn_requirementcharacteristic_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_requirementgroup_UserEntityInstanceDatas"></a> msdyn_requirementgroup_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_requirementgroup Entity [msdyn_requirementgroup_UserEntityInstanceDatas](msdyn_requirementgroup.md#BKMK_msdyn_requirementgroup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_requirementorganizationunit_UserEntityInstanceDatas"></a> msdyn_requirementorganizationunit_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_requirementorganizationunit Entity [msdyn_requirementorganizationunit_UserEntityInstanceDatas](msdyn_requirementorganizationunit.md#BKMK_msdyn_requirementorganizationunit_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_requirementrelationship_UserEntityInstanceDatas"></a> msdyn_requirementrelationship_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_requirementrelationship Entity [msdyn_requirementrelationship_UserEntityInstanceDatas](msdyn_requirementrelationship.md#BKMK_msdyn_requirementrelationship_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_requirementresourcecategory_UserEntityInstanceDatas"></a> msdyn_requirementresourcecategory_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_requirementresourcecategory Entity [msdyn_requirementresourcecategory_UserEntityInstanceDatas](msdyn_requirementresourcecategory.md#BKMK_msdyn_requirementresourcecategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_requirementresourcepreference_UserEntityInstanceDatas"></a> msdyn_requirementresourcepreference_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_requirementresourcepreference Entity [msdyn_requirementresourcepreference_UserEntityInstanceDatas](msdyn_requirementresourcepreference.md#BKMK_msdyn_requirementresourcepreference_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_requirementstatus_UserEntityInstanceDatas"></a> msdyn_requirementstatus_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_requirementstatus Entity [msdyn_requirementstatus_UserEntityInstanceDatas](msdyn_requirementstatus.md#BKMK_msdyn_requirementstatus_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourcerequirement_UserEntityInstanceDatas"></a> msdyn_resourcerequirement_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_resourcerequirement Entity [msdyn_resourcerequirement_UserEntityInstanceDatas](msdyn_resourcerequirement.md#BKMK_msdyn_resourcerequirement_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourcerequirementdetail_UserEntityInstanceDatas"></a> msdyn_resourcerequirementdetail_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_resourcerequirementdetail Entity [msdyn_resourcerequirementdetail_UserEntityInstanceDatas](msdyn_resourcerequirementdetail.md#BKMK_msdyn_resourcerequirementdetail_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourceterritory_UserEntityInstanceDatas"></a> msdyn_resourceterritory_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_resourceterritory Entity [msdyn_resourceterritory_UserEntityInstanceDatas](msdyn_resourceterritory.md#BKMK_msdyn_resourceterritory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_scheduleboardsetting_UserEntityInstanceDatas"></a> msdyn_scheduleboardsetting_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_scheduleboardsetting Entity [msdyn_scheduleboardsetting_UserEntityInstanceDatas](msdyn_scheduleboardsetting.md#BKMK_msdyn_scheduleboardsetting_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_schedulingparameter_UserEntityInstanceDatas"></a> msdyn_schedulingparameter_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_schedulingparameter Entity [msdyn_schedulingparameter_UserEntityInstanceDatas](msdyn_schedulingparameter.md#BKMK_msdyn_schedulingparameter_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_systemuserschedulersetting_UserEntityInstanceDatas"></a> msdyn_systemuserschedulersetting_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_systemuserschedulersetting Entity [msdyn_systemuserschedulersetting_UserEntityInstanceDatas](msdyn_systemuserschedulersetting.md#BKMK_msdyn_systemuserschedulersetting_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_timegroup_UserEntityInstanceDatas"></a> msdyn_timegroup_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_timegroup Entity [msdyn_timegroup_UserEntityInstanceDatas](msdyn_timegroup.md#BKMK_msdyn_timegroup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_timegroupdetail_UserEntityInstanceDatas"></a> msdyn_timegroupdetail_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_timegroupdetail Entity [msdyn_timegroupdetail_UserEntityInstanceDatas](msdyn_timegroupdetail.md#BKMK_msdyn_timegroupdetail_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_transactionorigin_UserEntityInstanceDatas"></a> msdyn_transactionorigin_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_transactionorigin Entity [msdyn_transactionorigin_UserEntityInstanceDatas](msdyn_transactionorigin.md#BKMK_msdyn_transactionorigin_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workhourtemplate_UserEntityInstanceDatas"></a> msdyn_workhourtemplate_UserEntityInstanceDatas

**Added by**: Universal Resource Scheduling Solution

See msdyn_workhourtemplate Entity [msdyn_workhourtemplate_UserEntityInstanceDatas](msdyn_workhourtemplate.md#BKMK_msdyn_workhourtemplate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_accountpricelist_UserEntityInstanceDatas"></a> msdyn_accountpricelist_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_accountpricelist Entity [msdyn_accountpricelist_UserEntityInstanceDatas](msdyn_accountpricelist.md#BKMK_msdyn_accountpricelist_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_approval_UserEntityInstanceDatas"></a> msdyn_approval_UserEntityInstanceDatas

**Added by**: Active Solution Solution

See msdyn_approval Entity [msdyn_approval_UserEntityInstanceDatas](msdyn_approval.md#BKMK_msdyn_approval_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_batchjob_UserEntityInstanceDatas"></a> msdyn_batchjob_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_batchjob Entity [msdyn_batchjob_UserEntityInstanceDatas](msdyn_batchjob.md#BKMK_msdyn_batchjob_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bpf_665e73aa18c247d886bfc50499c73b82_UserEntityInstanceDatas"></a> msdyn_bpf_665e73aa18c247d886bfc50499c73b82_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_bpf_665e73aa18c247d886bfc50499c73b82 Entity [msdyn_bpf_665e73aa18c247d886bfc50499c73b82_UserEntityInstanceDatas](msdyn_bpf_665e73aa18c247d886bfc50499c73b82.md#BKMK_msdyn_bpf_665e73aa18c247d886bfc50499c73b82_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d_UserEntityInstanceDatas"></a> msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d Entity [msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d_UserEntityInstanceDatas](msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d.md#BKMK_msdyn_bpf_d8f9dc7f099f44db9d641dd81fbd470d_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_characteristicreqforteammember_UserEntityInstanceDatas"></a> msdyn_characteristicreqforteammember_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_characteristicreqforteammember Entity [msdyn_characteristicreqforteammember_UserEntityInstanceDatas](msdyn_characteristicreqforteammember.md#BKMK_msdyn_characteristicreqforteammember_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_contactpricelist_UserEntityInstanceDatas"></a> msdyn_contactpricelist_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_contactpricelist Entity [msdyn_contactpricelist_UserEntityInstanceDatas](msdyn_contactpricelist.md#BKMK_msdyn_contactpricelist_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_contractlineinvoiceschedule_UserEntityInstanceDatas"></a> msdyn_contractlineinvoiceschedule_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_contractlineinvoiceschedule Entity [msdyn_contractlineinvoiceschedule_UserEntityInstanceDatas](msdyn_contractlineinvoiceschedule.md#BKMK_msdyn_contractlineinvoiceschedule_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_contractlinescheduleofvalue_UserEntityInstanceDatas"></a> msdyn_contractlinescheduleofvalue_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_contractlinescheduleofvalue Entity [msdyn_contractlinescheduleofvalue_UserEntityInstanceDatas](msdyn_contractlinescheduleofvalue.md#BKMK_msdyn_contractlinescheduleofvalue_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_dataexport_UserEntityInstanceDatas"></a> msdyn_dataexport_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_dataexport Entity [msdyn_dataexport_UserEntityInstanceDatas](msdyn_dataexport.md#BKMK_msdyn_dataexport_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_delegation_UserEntityInstanceDatas"></a> msdyn_delegation_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_delegation Entity [msdyn_delegation_UserEntityInstanceDatas](msdyn_delegation.md#BKMK_msdyn_delegation_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_dimension_UserEntityInstanceDatas"></a> msdyn_dimension_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_dimension Entity [msdyn_dimension_UserEntityInstanceDatas](msdyn_dimension.md#BKMK_msdyn_dimension_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_dimensionfieldname_UserEntityInstanceDatas"></a> msdyn_dimensionfieldname_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_dimensionfieldname Entity [msdyn_dimensionfieldname_UserEntityInstanceDatas](msdyn_dimensionfieldname.md#BKMK_msdyn_dimensionfieldname_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_estimate_UserEntityInstanceDatas"></a> msdyn_estimate_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_estimate Entity [msdyn_estimate_UserEntityInstanceDatas](msdyn_estimate.md#BKMK_msdyn_estimate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_estimateline_UserEntityInstanceDatas"></a> msdyn_estimateline_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_estimateline Entity [msdyn_estimateline_UserEntityInstanceDatas](msdyn_estimateline.md#BKMK_msdyn_estimateline_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_expense_UserEntityInstanceDatas"></a> msdyn_expense_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_expense Entity [msdyn_expense_UserEntityInstanceDatas](msdyn_expense.md#BKMK_msdyn_expense_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_expensecategory_UserEntityInstanceDatas"></a> msdyn_expensecategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_expensecategory Entity [msdyn_expensecategory_UserEntityInstanceDatas](msdyn_expensecategory.md#BKMK_msdyn_expensecategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_expensereceipt_UserEntityInstanceDatas"></a> msdyn_expensereceipt_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_expensereceipt Entity [msdyn_expensereceipt_UserEntityInstanceDatas](msdyn_expensereceipt.md#BKMK_msdyn_expensereceipt_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_fact_UserEntityInstanceDatas"></a> msdyn_fact_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_fact Entity [msdyn_fact_UserEntityInstanceDatas](msdyn_fact.md#BKMK_msdyn_fact_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_fieldcomputation_UserEntityInstanceDatas"></a> msdyn_fieldcomputation_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_fieldcomputation Entity [msdyn_fieldcomputation_UserEntityInstanceDatas](msdyn_fieldcomputation.md#BKMK_msdyn_fieldcomputation_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_findworkevent_UserEntityInstanceDatas"></a> msdyn_findworkevent_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_findworkevent Entity [msdyn_findworkevent_UserEntityInstanceDatas](msdyn_findworkevent.md#BKMK_msdyn_findworkevent_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_integrationjob_UserEntityInstanceDatas"></a> msdyn_integrationjob_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_integrationjob Entity [msdyn_integrationjob_UserEntityInstanceDatas](msdyn_integrationjob.md#BKMK_msdyn_integrationjob_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_integrationjobdetail_UserEntityInstanceDatas"></a> msdyn_integrationjobdetail_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_integrationjobdetail Entity [msdyn_integrationjobdetail_UserEntityInstanceDatas](msdyn_integrationjobdetail.md#BKMK_msdyn_integrationjobdetail_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_invoicefrequency_UserEntityInstanceDatas"></a> msdyn_invoicefrequency_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_invoicefrequency Entity [msdyn_invoicefrequency_UserEntityInstanceDatas](msdyn_invoicefrequency.md#BKMK_msdyn_invoicefrequency_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_invoicefrequencydetail_UserEntityInstanceDatas"></a> msdyn_invoicefrequencydetail_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_invoicefrequencydetail Entity [msdyn_invoicefrequencydetail_UserEntityInstanceDatas](msdyn_invoicefrequencydetail.md#BKMK_msdyn_invoicefrequencydetail_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_invoicelinetransaction_UserEntityInstanceDatas"></a> msdyn_invoicelinetransaction_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_invoicelinetransaction Entity [msdyn_invoicelinetransaction_UserEntityInstanceDatas](msdyn_invoicelinetransaction.md#BKMK_msdyn_invoicelinetransaction_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_journal_UserEntityInstanceDatas"></a> msdyn_journal_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_journal Entity [msdyn_journal_UserEntityInstanceDatas](msdyn_journal.md#BKMK_msdyn_journal_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_journalline_UserEntityInstanceDatas"></a> msdyn_journalline_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_journalline Entity [msdyn_journalline_UserEntityInstanceDatas](msdyn_journalline.md#BKMK_msdyn_journalline_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_mlresultcache_UserEntityInstanceDatas"></a> msdyn_mlresultcache_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_mlresultcache Entity [msdyn_mlresultcache_UserEntityInstanceDatas](msdyn_mlresultcache.md#BKMK_msdyn_mlresultcache_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_opportunitylineresourcecategory_UserEntityInstanceDatas"></a> msdyn_opportunitylineresourcecategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_opportunitylineresourcecategory Entity [msdyn_opportunitylineresourcecategory_UserEntityInstanceDatas](msdyn_opportunitylineresourcecategory.md#BKMK_msdyn_opportunitylineresourcecategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_opportunitylinetransaction_UserEntityInstanceDatas"></a> msdyn_opportunitylinetransaction_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_opportunitylinetransaction Entity [msdyn_opportunitylinetransaction_UserEntityInstanceDatas](msdyn_opportunitylinetransaction.md#BKMK_msdyn_opportunitylinetransaction_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_opportunitylinetransactioncategory_UserEntityInstanceDatas"></a> msdyn_opportunitylinetransactioncategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_opportunitylinetransactioncategory Entity [msdyn_opportunitylinetransactioncategory_UserEntityInstanceDatas](msdyn_opportunitylinetransactioncategory.md#BKMK_msdyn_opportunitylinetransactioncategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_opportunitylinetransactionclassificatio_UserEntityInstanceDatas"></a> msdyn_opportunitylinetransactionclassificatio_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_opportunitylinetransactionclassificatio Entity [msdyn_opportunitylinetransactionclassificatio_UserEntityInstanceDatas](msdyn_opportunitylinetransactionclassificatio.md#BKMK_msdyn_opportunitylinetransactionclassificatio_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_opportunitypricelist_UserEntityInstanceDatas"></a> msdyn_opportunitypricelist_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_opportunitypricelist Entity [msdyn_opportunitypricelist_UserEntityInstanceDatas](msdyn_opportunitypricelist.md#BKMK_msdyn_opportunitypricelist_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderlineresourcecategory_UserEntityInstanceDatas"></a> msdyn_orderlineresourcecategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_orderlineresourcecategory Entity [msdyn_orderlineresourcecategory_UserEntityInstanceDatas](msdyn_orderlineresourcecategory.md#BKMK_msdyn_orderlineresourcecategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderlinetransaction_UserEntityInstanceDatas"></a> msdyn_orderlinetransaction_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_orderlinetransaction Entity [msdyn_orderlinetransaction_UserEntityInstanceDatas](msdyn_orderlinetransaction.md#BKMK_msdyn_orderlinetransaction_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderlinetransactioncategory_UserEntityInstanceDatas"></a> msdyn_orderlinetransactioncategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_orderlinetransactioncategory Entity [msdyn_orderlinetransactioncategory_UserEntityInstanceDatas](msdyn_orderlinetransactioncategory.md#BKMK_msdyn_orderlinetransactioncategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderlinetransactionclassification_UserEntityInstanceDatas"></a> msdyn_orderlinetransactionclassification_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_orderlinetransactionclassification Entity [msdyn_orderlinetransactionclassification_UserEntityInstanceDatas](msdyn_orderlinetransactionclassification.md#BKMK_msdyn_orderlinetransactionclassification_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderpricelist_UserEntityInstanceDatas"></a> msdyn_orderpricelist_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_orderpricelist Entity [msdyn_orderpricelist_UserEntityInstanceDatas](msdyn_orderpricelist.md#BKMK_msdyn_orderpricelist_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_processnotes_UserEntityInstanceDatas"></a> msdyn_processnotes_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_processnotes Entity [msdyn_processnotes_UserEntityInstanceDatas](msdyn_processnotes.md#BKMK_msdyn_processnotes_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_project_UserEntityInstanceDatas"></a> msdyn_project_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_project Entity [msdyn_project_UserEntityInstanceDatas](msdyn_project.md#BKMK_msdyn_project_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projectapproval_UserEntityInstanceDatas"></a> msdyn_projectapproval_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projectapproval Entity [msdyn_projectapproval_UserEntityInstanceDatas](msdyn_projectapproval.md#BKMK_msdyn_projectapproval_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projectparameter_UserEntityInstanceDatas"></a> msdyn_projectparameter_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projectparameter Entity [msdyn_projectparameter_UserEntityInstanceDatas](msdyn_projectparameter.md#BKMK_msdyn_projectparameter_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projectparameterpricelist_UserEntityInstanceDatas"></a> msdyn_projectparameterpricelist_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projectparameterpricelist Entity [msdyn_projectparameterpricelist_UserEntityInstanceDatas](msdyn_projectparameterpricelist.md#BKMK_msdyn_projectparameterpricelist_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projectpricelist_UserEntityInstanceDatas"></a> msdyn_projectpricelist_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projectpricelist Entity [msdyn_projectpricelist_UserEntityInstanceDatas](msdyn_projectpricelist.md#BKMK_msdyn_projectpricelist_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projecttask_UserEntityInstanceDatas"></a> msdyn_projecttask_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projecttask Entity [msdyn_projecttask_UserEntityInstanceDatas](msdyn_projecttask.md#BKMK_msdyn_projecttask_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projecttaskdependency_UserEntityInstanceDatas"></a> msdyn_projecttaskdependency_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projecttaskdependency Entity [msdyn_projecttaskdependency_UserEntityInstanceDatas](msdyn_projecttaskdependency.md#BKMK_msdyn_projecttaskdependency_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projecttaskstatususer_UserEntityInstanceDatas"></a> msdyn_projecttaskstatususer_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projecttaskstatususer Entity [msdyn_projecttaskstatususer_UserEntityInstanceDatas](msdyn_projecttaskstatususer.md#BKMK_msdyn_projecttaskstatususer_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projectteam_UserEntityInstanceDatas"></a> msdyn_projectteam_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projectteam Entity [msdyn_projectteam_UserEntityInstanceDatas](msdyn_projectteam.md#BKMK_msdyn_projectteam_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projectteammembersignup_UserEntityInstanceDatas"></a> msdyn_projectteammembersignup_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projectteammembersignup Entity [msdyn_projectteammembersignup_UserEntityInstanceDatas](msdyn_projectteammembersignup.md#BKMK_msdyn_projectteammembersignup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_projecttransactioncategory_UserEntityInstanceDatas"></a> msdyn_projecttransactioncategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_projecttransactioncategory Entity [msdyn_projecttransactioncategory_UserEntityInstanceDatas](msdyn_projecttransactioncategory.md#BKMK_msdyn_projecttransactioncategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotelineanalyticsbreakdown_UserEntityInstanceDatas"></a> msdyn_quotelineanalyticsbreakdown_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_quotelineanalyticsbreakdown Entity [msdyn_quotelineanalyticsbreakdown_UserEntityInstanceDatas](msdyn_quotelineanalyticsbreakdown.md#BKMK_msdyn_quotelineanalyticsbreakdown_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotelineinvoiceschedule_UserEntityInstanceDatas"></a> msdyn_quotelineinvoiceschedule_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_quotelineinvoiceschedule Entity [msdyn_quotelineinvoiceschedule_UserEntityInstanceDatas](msdyn_quotelineinvoiceschedule.md#BKMK_msdyn_quotelineinvoiceschedule_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotelineresourcecategory_UserEntityInstanceDatas"></a> msdyn_quotelineresourcecategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_quotelineresourcecategory Entity [msdyn_quotelineresourcecategory_UserEntityInstanceDatas](msdyn_quotelineresourcecategory.md#BKMK_msdyn_quotelineresourcecategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotelinescheduleofvalue_UserEntityInstanceDatas"></a> msdyn_quotelinescheduleofvalue_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_quotelinescheduleofvalue Entity [msdyn_quotelinescheduleofvalue_UserEntityInstanceDatas](msdyn_quotelinescheduleofvalue.md#BKMK_msdyn_quotelinescheduleofvalue_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotelinetransaction_UserEntityInstanceDatas"></a> msdyn_quotelinetransaction_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_quotelinetransaction Entity [msdyn_quotelinetransaction_UserEntityInstanceDatas](msdyn_quotelinetransaction.md#BKMK_msdyn_quotelinetransaction_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotelinetransactioncategory_UserEntityInstanceDatas"></a> msdyn_quotelinetransactioncategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_quotelinetransactioncategory Entity [msdyn_quotelinetransactioncategory_UserEntityInstanceDatas](msdyn_quotelinetransactioncategory.md#BKMK_msdyn_quotelinetransactioncategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotelinetransactionclassification_UserEntityInstanceDatas"></a> msdyn_quotelinetransactionclassification_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_quotelinetransactionclassification Entity [msdyn_quotelinetransactionclassification_UserEntityInstanceDatas](msdyn_quotelinetransactionclassification.md#BKMK_msdyn_quotelinetransactionclassification_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotepricelist_UserEntityInstanceDatas"></a> msdyn_quotepricelist_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_quotepricelist Entity [msdyn_quotepricelist_UserEntityInstanceDatas](msdyn_quotepricelist.md#BKMK_msdyn_quotepricelist_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourceassignment_UserEntityInstanceDatas"></a> msdyn_resourceassignment_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_resourceassignment Entity [msdyn_resourceassignment_UserEntityInstanceDatas](msdyn_resourceassignment.md#BKMK_msdyn_resourceassignment_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourceassignmentdetail_UserEntityInstanceDatas"></a> msdyn_resourceassignmentdetail_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_resourceassignmentdetail Entity [msdyn_resourceassignmentdetail_UserEntityInstanceDatas](msdyn_resourceassignmentdetail.md#BKMK_msdyn_resourceassignmentdetail_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourcecategorymarkuppricelevel_UserEntityInstanceDatas"></a> msdyn_resourcecategorymarkuppricelevel_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_resourcecategorymarkuppricelevel Entity [msdyn_resourcecategorymarkuppricelevel_UserEntityInstanceDatas](msdyn_resourcecategorymarkuppricelevel.md#BKMK_msdyn_resourcecategorymarkuppricelevel_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourcecategorypricelevel_UserEntityInstanceDatas"></a> msdyn_resourcecategorypricelevel_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_resourcecategorypricelevel Entity [msdyn_resourcecategorypricelevel_UserEntityInstanceDatas](msdyn_resourcecategorypricelevel.md#BKMK_msdyn_resourcecategorypricelevel_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourcerequest_UserEntityInstanceDatas"></a> msdyn_resourcerequest_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_resourcerequest Entity [msdyn_resourcerequest_UserEntityInstanceDatas](msdyn_resourcerequest.md#BKMK_msdyn_resourcerequest_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rolecompetencyrequirement_UserEntityInstanceDatas"></a> msdyn_rolecompetencyrequirement_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_rolecompetencyrequirement Entity [msdyn_rolecompetencyrequirement_UserEntityInstanceDatas](msdyn_rolecompetencyrequirement.md#BKMK_msdyn_rolecompetencyrequirement_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_roleutilization_UserEntityInstanceDatas"></a> msdyn_roleutilization_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_roleutilization Entity [msdyn_roleutilization_UserEntityInstanceDatas](msdyn_roleutilization.md#BKMK_msdyn_roleutilization_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_timeentry_UserEntityInstanceDatas"></a> msdyn_timeentry_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_timeentry Entity [msdyn_timeentry_UserEntityInstanceDatas](msdyn_timeentry.md#BKMK_msdyn_timeentry_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_timeoffcalendar_UserEntityInstanceDatas"></a> msdyn_timeoffcalendar_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_timeoffcalendar Entity [msdyn_timeoffcalendar_UserEntityInstanceDatas](msdyn_timeoffcalendar.md#BKMK_msdyn_timeoffcalendar_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_transactioncategory_UserEntityInstanceDatas"></a> msdyn_transactioncategory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_transactioncategory Entity [msdyn_transactioncategory_UserEntityInstanceDatas](msdyn_transactioncategory.md#BKMK_msdyn_transactioncategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_transactioncategoryclassification_UserEntityInstanceDatas"></a> msdyn_transactioncategoryclassification_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_transactioncategoryclassification Entity [msdyn_transactioncategoryclassification_UserEntityInstanceDatas](msdyn_transactioncategoryclassification.md#BKMK_msdyn_transactioncategoryclassification_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_transactioncategoryhierarchyelement_UserEntityInstanceDatas"></a> msdyn_transactioncategoryhierarchyelement_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_transactioncategoryhierarchyelement Entity [msdyn_transactioncategoryhierarchyelement_UserEntityInstanceDatas](msdyn_transactioncategoryhierarchyelement.md#BKMK_msdyn_transactioncategoryhierarchyelement_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_transactioncategorypricelevel_UserEntityInstanceDatas"></a> msdyn_transactioncategorypricelevel_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_transactioncategorypricelevel Entity [msdyn_transactioncategorypricelevel_UserEntityInstanceDatas](msdyn_transactioncategorypricelevel.md#BKMK_msdyn_transactioncategorypricelevel_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_transactionconnection_UserEntityInstanceDatas"></a> msdyn_transactionconnection_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_transactionconnection Entity [msdyn_transactionconnection_UserEntityInstanceDatas](msdyn_transactionconnection.md#BKMK_msdyn_transactionconnection_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_transactiontype_UserEntityInstanceDatas"></a> msdyn_transactiontype_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_transactiontype Entity [msdyn_transactiontype_UserEntityInstanceDatas](msdyn_transactiontype.md#BKMK_msdyn_transactiontype_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_userworkhistory_UserEntityInstanceDatas"></a> msdyn_userworkhistory_UserEntityInstanceDatas

**Added by**: Project Service Automation Solution

See msdyn_userworkhistory Entity [msdyn_userworkhistory_UserEntityInstanceDatas](msdyn_userworkhistory.md#BKMK_msdyn_userworkhistory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_3dmodel_UserEntityInstanceDatas"></a> msdyn_3dmodel_UserEntityInstanceDatas

**Added by**: 3D Viewer Solution

See msdyn_3dmodel Entity [msdyn_3dmodel_UserEntityInstanceDatas](msdyn_3dmodel.md#BKMK_msdyn_3dmodel_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_analysiscomponent_UserEntityInstanceDatas"></a> msdyn_analysiscomponent_UserEntityInstanceDatas

**Added by**: PowerApps Checker Solution

See msdyn_analysiscomponent Entity [msdyn_analysiscomponent_UserEntityInstanceDatas](msdyn_analysiscomponent.md#BKMK_msdyn_analysiscomponent_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_analysisjob_UserEntityInstanceDatas"></a> msdyn_analysisjob_UserEntityInstanceDatas

**Added by**: PowerApps Checker Solution

See msdyn_analysisjob Entity [msdyn_analysisjob_UserEntityInstanceDatas](msdyn_analysisjob.md#BKMK_msdyn_analysisjob_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_analysisresult_UserEntityInstanceDatas"></a> msdyn_analysisresult_UserEntityInstanceDatas

**Added by**: PowerApps Checker Solution

See msdyn_analysisresult Entity [msdyn_analysisresult_UserEntityInstanceDatas](msdyn_analysisresult.md#BKMK_msdyn_analysisresult_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_analysisresultdetail_UserEntityInstanceDatas"></a> msdyn_analysisresultdetail_UserEntityInstanceDatas

**Added by**: PowerApps Checker Solution

See msdyn_analysisresultdetail Entity [msdyn_analysisresultdetail_UserEntityInstanceDatas](msdyn_analysisresultdetail.md#BKMK_msdyn_analysisresultdetail_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_solutionhealthrule_UserEntityInstanceDatas"></a> msdyn_solutionhealthrule_UserEntityInstanceDatas

**Added by**: PowerApps Checker Solution

See msdyn_solutionhealthrule Entity [msdyn_solutionhealthrule_UserEntityInstanceDatas](msdyn_solutionhealthrule.md#BKMK_msdyn_solutionhealthrule_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_solutionhealthruleargument_UserEntityInstanceDatas"></a> msdyn_solutionhealthruleargument_UserEntityInstanceDatas

**Added by**: PowerApps Checker Solution

See msdyn_solutionhealthruleargument Entity [msdyn_solutionhealthruleargument_UserEntityInstanceDatas](msdyn_solutionhealthruleargument.md#BKMK_msdyn_solutionhealthruleargument_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_solutionhealthruleset_UserEntityInstanceDatas"></a> msdyn_solutionhealthruleset_UserEntityInstanceDatas

**Added by**: PowerApps Checker Solution

See msdyn_solutionhealthruleset Entity [msdyn_solutionhealthruleset_UserEntityInstanceDatas](msdyn_solutionhealthruleset.md#BKMK_msdyn_solutionhealthruleset_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreement_UserEntityInstanceDatas"></a> msdyn_agreement_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreement Entity [msdyn_agreement_UserEntityInstanceDatas](msdyn_agreement.md#BKMK_msdyn_agreement_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementbookingdate_UserEntityInstanceDatas"></a> msdyn_agreementbookingdate_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementbookingdate Entity [msdyn_agreementbookingdate_UserEntityInstanceDatas](msdyn_agreementbookingdate.md#BKMK_msdyn_agreementbookingdate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementbookingincident_UserEntityInstanceDatas"></a> msdyn_agreementbookingincident_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementbookingincident Entity [msdyn_agreementbookingincident_UserEntityInstanceDatas](msdyn_agreementbookingincident.md#BKMK_msdyn_agreementbookingincident_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementbookingproduct_UserEntityInstanceDatas"></a> msdyn_agreementbookingproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementbookingproduct Entity [msdyn_agreementbookingproduct_UserEntityInstanceDatas](msdyn_agreementbookingproduct.md#BKMK_msdyn_agreementbookingproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementbookingservice_UserEntityInstanceDatas"></a> msdyn_agreementbookingservice_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementbookingservice Entity [msdyn_agreementbookingservice_UserEntityInstanceDatas](msdyn_agreementbookingservice.md#BKMK_msdyn_agreementbookingservice_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementbookingservicetask_UserEntityInstanceDatas"></a> msdyn_agreementbookingservicetask_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementbookingservicetask Entity [msdyn_agreementbookingservicetask_UserEntityInstanceDatas](msdyn_agreementbookingservicetask.md#BKMK_msdyn_agreementbookingservicetask_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementbookingsetup_UserEntityInstanceDatas"></a> msdyn_agreementbookingsetup_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementbookingsetup Entity [msdyn_agreementbookingsetup_UserEntityInstanceDatas](msdyn_agreementbookingsetup.md#BKMK_msdyn_agreementbookingsetup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementinvoicedate_UserEntityInstanceDatas"></a> msdyn_agreementinvoicedate_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementinvoicedate Entity [msdyn_agreementinvoicedate_UserEntityInstanceDatas](msdyn_agreementinvoicedate.md#BKMK_msdyn_agreementinvoicedate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementinvoiceproduct_UserEntityInstanceDatas"></a> msdyn_agreementinvoiceproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementinvoiceproduct Entity [msdyn_agreementinvoiceproduct_UserEntityInstanceDatas](msdyn_agreementinvoiceproduct.md#BKMK_msdyn_agreementinvoiceproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementinvoicesetup_UserEntityInstanceDatas"></a> msdyn_agreementinvoicesetup_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementinvoicesetup Entity [msdyn_agreementinvoicesetup_UserEntityInstanceDatas](msdyn_agreementinvoicesetup.md#BKMK_msdyn_agreementinvoicesetup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_agreementsubstatus_UserEntityInstanceDatas"></a> msdyn_agreementsubstatus_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_agreementsubstatus Entity [msdyn_agreementsubstatus_UserEntityInstanceDatas](msdyn_agreementsubstatus.md#BKMK_msdyn_agreementsubstatus_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bookingjournal_UserEntityInstanceDatas"></a> msdyn_bookingjournal_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_bookingjournal Entity [msdyn_bookingjournal_UserEntityInstanceDatas](msdyn_bookingjournal.md#BKMK_msdyn_bookingjournal_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bookingtimestamp_UserEntityInstanceDatas"></a> msdyn_bookingtimestamp_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_bookingtimestamp Entity [msdyn_bookingtimestamp_UserEntityInstanceDatas](msdyn_bookingtimestamp.md#BKMK_msdyn_bookingtimestamp_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799_UserEntityInstanceDatas"></a> msdyn_bpf_2c5fe86acc8b414b8322ae571000c799_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_bpf_2c5fe86acc8b414b8322ae571000c799 Entity [msdyn_bpf_2c5fe86acc8b414b8322ae571000c799_UserEntityInstanceDatas](msdyn_bpf_2c5fe86acc8b414b8322ae571000c799.md#BKMK_msdyn_bpf_2c5fe86acc8b414b8322ae571000c799_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bpf_989e9b1857e24af18787d5143b67523b_UserEntityInstanceDatas"></a> msdyn_bpf_989e9b1857e24af18787d5143b67523b_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_bpf_989e9b1857e24af18787d5143b67523b Entity [msdyn_bpf_989e9b1857e24af18787d5143b67523b_UserEntityInstanceDatas](msdyn_bpf_989e9b1857e24af18787d5143b67523b.md#BKMK_msdyn_bpf_989e9b1857e24af18787d5143b67523b_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3_UserEntityInstanceDatas"></a> msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3 Entity [msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3_UserEntityInstanceDatas](msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3.md#BKMK_msdyn_bpf_baa0a411a239410cb8bded8b5fdd88e3_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39_UserEntityInstanceDatas"></a> msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39 Entity [msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39_UserEntityInstanceDatas](msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39.md#BKMK_msdyn_bpf_d3d97bac8c294105840e99e37a9d1c39_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_customerasset_UserEntityInstanceDatas"></a> msdyn_customerasset_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_customerasset Entity [msdyn_customerasset_UserEntityInstanceDatas](msdyn_customerasset.md#BKMK_msdyn_customerasset_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_customerassetcategory_UserEntityInstanceDatas"></a> msdyn_customerassetcategory_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_customerassetcategory Entity [msdyn_customerassetcategory_UserEntityInstanceDatas](msdyn_customerassetcategory.md#BKMK_msdyn_customerassetcategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_entitlementapplication_UserEntityInstanceDatas"></a> msdyn_entitlementapplication_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_entitlementapplication Entity [msdyn_entitlementapplication_UserEntityInstanceDatas](msdyn_entitlementapplication.md#BKMK_msdyn_entitlementapplication_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_fieldservicepricelistitem_UserEntityInstanceDatas"></a> msdyn_fieldservicepricelistitem_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_fieldservicepricelistitem Entity [msdyn_fieldservicepricelistitem_UserEntityInstanceDatas](msdyn_fieldservicepricelistitem.md#BKMK_msdyn_fieldservicepricelistitem_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_fieldservicesetting_UserEntityInstanceDatas"></a> msdyn_fieldservicesetting_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_fieldservicesetting Entity [msdyn_fieldservicesetting_UserEntityInstanceDatas](msdyn_fieldservicesetting.md#BKMK_msdyn_fieldservicesetting_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_fieldserviceslaconfiguration_UserEntityInstanceDatas"></a> msdyn_fieldserviceslaconfiguration_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_fieldserviceslaconfiguration Entity [msdyn_fieldserviceslaconfiguration_UserEntityInstanceDatas](msdyn_fieldserviceslaconfiguration.md#BKMK_msdyn_fieldserviceslaconfiguration_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_fieldservicesystemjob_UserEntityInstanceDatas"></a> msdyn_fieldservicesystemjob_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_fieldservicesystemjob Entity [msdyn_fieldservicesystemjob_UserEntityInstanceDatas](msdyn_fieldservicesystemjob.md#BKMK_msdyn_fieldservicesystemjob_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_incidenttype_UserEntityInstanceDatas"></a> msdyn_incidenttype_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_incidenttype Entity [msdyn_incidenttype_UserEntityInstanceDatas](msdyn_incidenttype.md#BKMK_msdyn_incidenttype_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_incidenttypecharacteristic_UserEntityInstanceDatas"></a> msdyn_incidenttypecharacteristic_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_incidenttypecharacteristic Entity [msdyn_incidenttypecharacteristic_UserEntityInstanceDatas](msdyn_incidenttypecharacteristic.md#BKMK_msdyn_incidenttypecharacteristic_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_incidenttypeproduct_UserEntityInstanceDatas"></a> msdyn_incidenttypeproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_incidenttypeproduct Entity [msdyn_incidenttypeproduct_UserEntityInstanceDatas](msdyn_incidenttypeproduct.md#BKMK_msdyn_incidenttypeproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_incidenttypeservice_UserEntityInstanceDatas"></a> msdyn_incidenttypeservice_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_incidenttypeservice Entity [msdyn_incidenttypeservice_UserEntityInstanceDatas](msdyn_incidenttypeservice.md#BKMK_msdyn_incidenttypeservice_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_incidenttypeservicetask_UserEntityInstanceDatas"></a> msdyn_incidenttypeservicetask_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_incidenttypeservicetask Entity [msdyn_incidenttypeservicetask_UserEntityInstanceDatas](msdyn_incidenttypeservicetask.md#BKMK_msdyn_incidenttypeservicetask_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_incidenttypessetup_UserEntityInstanceDatas"></a> msdyn_incidenttypessetup_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_incidenttypessetup Entity [msdyn_incidenttypessetup_UserEntityInstanceDatas](msdyn_incidenttypessetup.md#BKMK_msdyn_incidenttypessetup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_incidenttype_requirementgroup_UserEntityInstanceDatas"></a> msdyn_incidenttype_requirementgroup_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_incidenttype_requirementgroup Entity [msdyn_incidenttype_requirementgroup_UserEntityInstanceDatas](msdyn_incidenttype_requirementgroup.md#BKMK_msdyn_incidenttype_requirementgroup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_inventoryadjustment_UserEntityInstanceDatas"></a> msdyn_inventoryadjustment_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_inventoryadjustment Entity [msdyn_inventoryadjustment_UserEntityInstanceDatas](msdyn_inventoryadjustment.md#BKMK_msdyn_inventoryadjustment_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_inventoryadjustmentproduct_UserEntityInstanceDatas"></a> msdyn_inventoryadjustmentproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_inventoryadjustmentproduct Entity [msdyn_inventoryadjustmentproduct_UserEntityInstanceDatas](msdyn_inventoryadjustmentproduct.md#BKMK_msdyn_inventoryadjustmentproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_inventoryjournal_UserEntityInstanceDatas"></a> msdyn_inventoryjournal_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_inventoryjournal Entity [msdyn_inventoryjournal_UserEntityInstanceDatas](msdyn_inventoryjournal.md#BKMK_msdyn_inventoryjournal_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_inventorytransfer_UserEntityInstanceDatas"></a> msdyn_inventorytransfer_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_inventorytransfer Entity [msdyn_inventorytransfer_UserEntityInstanceDatas](msdyn_inventorytransfer.md#BKMK_msdyn_inventorytransfer_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderinvoicingdate_UserEntityInstanceDatas"></a> msdyn_orderinvoicingdate_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_orderinvoicingdate Entity [msdyn_orderinvoicingdate_UserEntityInstanceDatas](msdyn_orderinvoicingdate.md#BKMK_msdyn_orderinvoicingdate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderinvoicingproduct_UserEntityInstanceDatas"></a> msdyn_orderinvoicingproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_orderinvoicingproduct Entity [msdyn_orderinvoicingproduct_UserEntityInstanceDatas](msdyn_orderinvoicingproduct.md#BKMK_msdyn_orderinvoicingproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderinvoicingsetup_UserEntityInstanceDatas"></a> msdyn_orderinvoicingsetup_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_orderinvoicingsetup Entity [msdyn_orderinvoicingsetup_UserEntityInstanceDatas](msdyn_orderinvoicingsetup.md#BKMK_msdyn_orderinvoicingsetup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_orderinvoicingsetupdate_UserEntityInstanceDatas"></a> msdyn_orderinvoicingsetupdate_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_orderinvoicingsetupdate Entity [msdyn_orderinvoicingsetupdate_UserEntityInstanceDatas](msdyn_orderinvoicingsetupdate.md#BKMK_msdyn_orderinvoicingsetupdate_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_payment_UserEntityInstanceDatas"></a> msdyn_payment_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_payment Entity [msdyn_payment_UserEntityInstanceDatas](msdyn_payment.md#BKMK_msdyn_payment_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_paymentdetail_UserEntityInstanceDatas"></a> msdyn_paymentdetail_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_paymentdetail Entity [msdyn_paymentdetail_UserEntityInstanceDatas](msdyn_paymentdetail.md#BKMK_msdyn_paymentdetail_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_paymentmethod_UserEntityInstanceDatas"></a> msdyn_paymentmethod_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_paymentmethod Entity [msdyn_paymentmethod_UserEntityInstanceDatas](msdyn_paymentmethod.md#BKMK_msdyn_paymentmethod_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_paymentterm_UserEntityInstanceDatas"></a> msdyn_paymentterm_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_paymentterm Entity [msdyn_paymentterm_UserEntityInstanceDatas](msdyn_paymentterm.md#BKMK_msdyn_paymentterm_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_postalcode_UserEntityInstanceDatas"></a> msdyn_postalcode_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_postalcode Entity [msdyn_postalcode_UserEntityInstanceDatas](msdyn_postalcode.md#BKMK_msdyn_postalcode_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_productinventory_UserEntityInstanceDatas"></a> msdyn_productinventory_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_productinventory Entity [msdyn_productinventory_UserEntityInstanceDatas](msdyn_productinventory.md#BKMK_msdyn_productinventory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_purchaseorder_UserEntityInstanceDatas"></a> msdyn_purchaseorder_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_purchaseorder Entity [msdyn_purchaseorder_UserEntityInstanceDatas](msdyn_purchaseorder.md#BKMK_msdyn_purchaseorder_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_purchaseorderbill_UserEntityInstanceDatas"></a> msdyn_purchaseorderbill_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_purchaseorderbill Entity [msdyn_purchaseorderbill_UserEntityInstanceDatas](msdyn_purchaseorderbill.md#BKMK_msdyn_purchaseorderbill_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_purchaseorderproduct_UserEntityInstanceDatas"></a> msdyn_purchaseorderproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_purchaseorderproduct Entity [msdyn_purchaseorderproduct_UserEntityInstanceDatas](msdyn_purchaseorderproduct.md#BKMK_msdyn_purchaseorderproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_purchaseorderreceipt_UserEntityInstanceDatas"></a> msdyn_purchaseorderreceipt_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_purchaseorderreceipt Entity [msdyn_purchaseorderreceipt_UserEntityInstanceDatas](msdyn_purchaseorderreceipt.md#BKMK_msdyn_purchaseorderreceipt_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_purchaseorderreceiptproduct_UserEntityInstanceDatas"></a> msdyn_purchaseorderreceiptproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_purchaseorderreceiptproduct Entity [msdyn_purchaseorderreceiptproduct_UserEntityInstanceDatas](msdyn_purchaseorderreceiptproduct.md#BKMK_msdyn_purchaseorderreceiptproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_purchaseordersubstatus_UserEntityInstanceDatas"></a> msdyn_purchaseordersubstatus_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_purchaseordersubstatus Entity [msdyn_purchaseordersubstatus_UserEntityInstanceDatas](msdyn_purchaseordersubstatus.md#BKMK_msdyn_purchaseordersubstatus_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotebookingincident_UserEntityInstanceDatas"></a> msdyn_quotebookingincident_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_quotebookingincident Entity [msdyn_quotebookingincident_UserEntityInstanceDatas](msdyn_quotebookingincident.md#BKMK_msdyn_quotebookingincident_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotebookingproduct_UserEntityInstanceDatas"></a> msdyn_quotebookingproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_quotebookingproduct Entity [msdyn_quotebookingproduct_UserEntityInstanceDatas](msdyn_quotebookingproduct.md#BKMK_msdyn_quotebookingproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotebookingservice_UserEntityInstanceDatas"></a> msdyn_quotebookingservice_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_quotebookingservice Entity [msdyn_quotebookingservice_UserEntityInstanceDatas](msdyn_quotebookingservice.md#BKMK_msdyn_quotebookingservice_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotebookingservicetask_UserEntityInstanceDatas"></a> msdyn_quotebookingservicetask_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_quotebookingservicetask Entity [msdyn_quotebookingservicetask_UserEntityInstanceDatas](msdyn_quotebookingservicetask.md#BKMK_msdyn_quotebookingservicetask_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quotebookingsetup_UserEntityInstanceDatas"></a> msdyn_quotebookingsetup_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_quotebookingsetup Entity [msdyn_quotebookingsetup_UserEntityInstanceDatas](msdyn_quotebookingsetup.md#BKMK_msdyn_quotebookingsetup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quoteinvoicingproduct_UserEntityInstanceDatas"></a> msdyn_quoteinvoicingproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_quoteinvoicingproduct Entity [msdyn_quoteinvoicingproduct_UserEntityInstanceDatas](msdyn_quoteinvoicingproduct.md#BKMK_msdyn_quoteinvoicingproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_quoteinvoicingsetup_UserEntityInstanceDatas"></a> msdyn_quoteinvoicingsetup_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_quoteinvoicingsetup Entity [msdyn_quoteinvoicingsetup_UserEntityInstanceDatas](msdyn_quoteinvoicingsetup.md#BKMK_msdyn_quoteinvoicingsetup_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_resourcepaytype_UserEntityInstanceDatas"></a> msdyn_resourcepaytype_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_resourcepaytype Entity [msdyn_resourcepaytype_UserEntityInstanceDatas](msdyn_resourcepaytype.md#BKMK_msdyn_resourcepaytype_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rma_UserEntityInstanceDatas"></a> msdyn_rma_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_rma Entity [msdyn_rma_UserEntityInstanceDatas](msdyn_rma.md#BKMK_msdyn_rma_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rmaproduct_UserEntityInstanceDatas"></a> msdyn_rmaproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_rmaproduct Entity [msdyn_rmaproduct_UserEntityInstanceDatas](msdyn_rmaproduct.md#BKMK_msdyn_rmaproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rmareceipt_UserEntityInstanceDatas"></a> msdyn_rmareceipt_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_rmareceipt Entity [msdyn_rmareceipt_UserEntityInstanceDatas](msdyn_rmareceipt.md#BKMK_msdyn_rmareceipt_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rmareceiptproduct_UserEntityInstanceDatas"></a> msdyn_rmareceiptproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_rmareceiptproduct Entity [msdyn_rmareceiptproduct_UserEntityInstanceDatas](msdyn_rmareceiptproduct.md#BKMK_msdyn_rmareceiptproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rmasubstatus_UserEntityInstanceDatas"></a> msdyn_rmasubstatus_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_rmasubstatus Entity [msdyn_rmasubstatus_UserEntityInstanceDatas](msdyn_rmasubstatus.md#BKMK_msdyn_rmasubstatus_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rtv_UserEntityInstanceDatas"></a> msdyn_rtv_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_rtv Entity [msdyn_rtv_UserEntityInstanceDatas](msdyn_rtv.md#BKMK_msdyn_rtv_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rtvproduct_UserEntityInstanceDatas"></a> msdyn_rtvproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_rtvproduct Entity [msdyn_rtvproduct_UserEntityInstanceDatas](msdyn_rtvproduct.md#BKMK_msdyn_rtvproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_rtvsubstatus_UserEntityInstanceDatas"></a> msdyn_rtvsubstatus_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_rtvsubstatus Entity [msdyn_rtvsubstatus_UserEntityInstanceDatas](msdyn_rtvsubstatus.md#BKMK_msdyn_rtvsubstatus_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_servicetasktype_UserEntityInstanceDatas"></a> msdyn_servicetasktype_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_servicetasktype Entity [msdyn_servicetasktype_UserEntityInstanceDatas](msdyn_servicetasktype.md#BKMK_msdyn_servicetasktype_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_shipvia_UserEntityInstanceDatas"></a> msdyn_shipvia_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_shipvia Entity [msdyn_shipvia_UserEntityInstanceDatas](msdyn_shipvia.md#BKMK_msdyn_shipvia_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_taxcode_UserEntityInstanceDatas"></a> msdyn_taxcode_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_taxcode Entity [msdyn_taxcode_UserEntityInstanceDatas](msdyn_taxcode.md#BKMK_msdyn_taxcode_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_taxcodedetail_UserEntityInstanceDatas"></a> msdyn_taxcodedetail_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_taxcodedetail Entity [msdyn_taxcodedetail_UserEntityInstanceDatas](msdyn_taxcodedetail.md#BKMK_msdyn_taxcodedetail_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_timeoffrequest_UserEntityInstanceDatas"></a> msdyn_timeoffrequest_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_timeoffrequest Entity [msdyn_timeoffrequest_UserEntityInstanceDatas](msdyn_timeoffrequest.md#BKMK_msdyn_timeoffrequest_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_uniquenumber_UserEntityInstanceDatas"></a> msdyn_uniquenumber_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_uniquenumber Entity [msdyn_uniquenumber_UserEntityInstanceDatas](msdyn_uniquenumber.md#BKMK_msdyn_uniquenumber_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_warehouse_UserEntityInstanceDatas"></a> msdyn_warehouse_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_warehouse Entity [msdyn_warehouse_UserEntityInstanceDatas](msdyn_warehouse.md#BKMK_msdyn_warehouse_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workorder_UserEntityInstanceDatas"></a> msdyn_workorder_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workorder Entity [msdyn_workorder_UserEntityInstanceDatas](msdyn_workorder.md#BKMK_msdyn_workorder_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workordercharacteristic_UserEntityInstanceDatas"></a> msdyn_workordercharacteristic_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workordercharacteristic Entity [msdyn_workordercharacteristic_UserEntityInstanceDatas](msdyn_workordercharacteristic.md#BKMK_msdyn_workordercharacteristic_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workorderdetailsgenerationqueue_UserEntityInstanceDatas"></a> msdyn_workorderdetailsgenerationqueue_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workorderdetailsgenerationqueue Entity [msdyn_workorderdetailsgenerationqueue_UserEntityInstanceDatas](msdyn_workorderdetailsgenerationqueue.md#BKMK_msdyn_workorderdetailsgenerationqueue_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workorderincident_UserEntityInstanceDatas"></a> msdyn_workorderincident_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workorderincident Entity [msdyn_workorderincident_UserEntityInstanceDatas](msdyn_workorderincident.md#BKMK_msdyn_workorderincident_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workorderproduct_UserEntityInstanceDatas"></a> msdyn_workorderproduct_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workorderproduct Entity [msdyn_workorderproduct_UserEntityInstanceDatas](msdyn_workorderproduct.md#BKMK_msdyn_workorderproduct_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workorderresourcerestriction_UserEntityInstanceDatas"></a> msdyn_workorderresourcerestriction_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workorderresourcerestriction Entity [msdyn_workorderresourcerestriction_UserEntityInstanceDatas](msdyn_workorderresourcerestriction.md#BKMK_msdyn_workorderresourcerestriction_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workorderservice_UserEntityInstanceDatas"></a> msdyn_workorderservice_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workorderservice Entity [msdyn_workorderservice_UserEntityInstanceDatas](msdyn_workorderservice.md#BKMK_msdyn_workorderservice_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workorderservicetask_UserEntityInstanceDatas"></a> msdyn_workorderservicetask_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workorderservicetask Entity [msdyn_workorderservicetask_UserEntityInstanceDatas](msdyn_workorderservicetask.md#BKMK_msdyn_workorderservicetask_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workordersubstatus_UserEntityInstanceDatas"></a> msdyn_workordersubstatus_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workordersubstatus Entity [msdyn_workordersubstatus_UserEntityInstanceDatas](msdyn_workordersubstatus.md#BKMK_msdyn_workordersubstatus_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_workordertype_UserEntityInstanceDatas"></a> msdyn_workordertype_UserEntityInstanceDatas

**Added by**: Field Service Solution

See msdyn_workordertype Entity [msdyn_workordertype_UserEntityInstanceDatas](msdyn_workordertype.md#BKMK_msdyn_workordertype_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotalert_UserEntityInstanceDatas"></a> msdyn_iotalert_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotalert Entity [msdyn_iotalert_UserEntityInstanceDatas](msdyn_iotalert.md#BKMK_msdyn_iotalert_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotdevice_UserEntityInstanceDatas"></a> msdyn_iotdevice_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotdevice Entity [msdyn_iotdevice_UserEntityInstanceDatas](msdyn_iotdevice.md#BKMK_msdyn_iotdevice_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotdevicecategory_UserEntityInstanceDatas"></a> msdyn_iotdevicecategory_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotdevicecategory Entity [msdyn_iotdevicecategory_UserEntityInstanceDatas](msdyn_iotdevicecategory.md#BKMK_msdyn_iotdevicecategory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotdevicecommand_UserEntityInstanceDatas"></a> msdyn_iotdevicecommand_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotdevicecommand Entity [msdyn_iotdevicecommand_UserEntityInstanceDatas](msdyn_iotdevicecommand.md#BKMK_msdyn_iotdevicecommand_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotdevicecommanddefinition_UserEntityInstanceDatas"></a> msdyn_iotdevicecommanddefinition_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotdevicecommanddefinition Entity [msdyn_iotdevicecommanddefinition_UserEntityInstanceDatas](msdyn_iotdevicecommanddefinition.md#BKMK_msdyn_iotdevicecommanddefinition_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotdevicedatahistory_UserEntityInstanceDatas"></a> msdyn_iotdevicedatahistory_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotdevicedatahistory Entity [msdyn_iotdevicedatahistory_UserEntityInstanceDatas](msdyn_iotdevicedatahistory.md#BKMK_msdyn_iotdevicedatahistory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotdeviceproperty_UserEntityInstanceDatas"></a> msdyn_iotdeviceproperty_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotdeviceproperty Entity [msdyn_iotdeviceproperty_UserEntityInstanceDatas](msdyn_iotdeviceproperty.md#BKMK_msdyn_iotdeviceproperty_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotdeviceregistrationhistory_UserEntityInstanceDatas"></a> msdyn_iotdeviceregistrationhistory_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotdeviceregistrationhistory Entity [msdyn_iotdeviceregistrationhistory_UserEntityInstanceDatas](msdyn_iotdeviceregistrationhistory.md#BKMK_msdyn_iotdeviceregistrationhistory_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotpropertydefinition_UserEntityInstanceDatas"></a> msdyn_iotpropertydefinition_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotpropertydefinition Entity [msdyn_iotpropertydefinition_UserEntityInstanceDatas](msdyn_iotpropertydefinition.md#BKMK_msdyn_iotpropertydefinition_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_iotsettings_UserEntityInstanceDatas"></a> msdyn_iotsettings_UserEntityInstanceDatas

**Added by**: IoT Connector for Microsoft Dynamics 365 Solution

See msdyn_iotsettings Entity [msdyn_iotsettings_UserEntityInstanceDatas](msdyn_iotsettings.md#BKMK_msdyn_iotsettings_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b_UserEntityInstanceDatas"></a> msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b_UserEntityInstanceDatas

**Added by**: Connected Field Service for Microsoft Dynamics 365 Solution

See msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b Entity [msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b_UserEntityInstanceDatas](msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b.md#BKMK_msdyn_bpf_477c16f59170487b8b4dc895c5dcd09b_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_entityconfiguration_UserEntityInstanceDatas"></a> msdyn_entityconfiguration_UserEntityInstanceDatas

**Added by**: Geofence Management Solution

See msdyn_entityconfiguration Entity [msdyn_entityconfiguration_UserEntityInstanceDatas](msdyn_entityconfiguration.md#BKMK_msdyn_entityconfiguration_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_geofence_UserEntityInstanceDatas"></a> msdyn_geofence_UserEntityInstanceDatas

**Added by**: Geofence Management Solution

See msdyn_geofence Entity [msdyn_geofence_UserEntityInstanceDatas](msdyn_geofence.md#BKMK_msdyn_geofence_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_geofenceevent_UserEntityInstanceDatas"></a> msdyn_geofenceevent_UserEntityInstanceDatas

**Added by**: Geofence Management Solution

See msdyn_geofenceevent Entity [msdyn_geofenceevent_UserEntityInstanceDatas](msdyn_geofenceevent.md#BKMK_msdyn_geofenceevent_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdyn_geofencingsettings_UserEntityInstanceDatas"></a> msdyn_geofencingsettings_UserEntityInstanceDatas

**Added by**: Geofence Management Solution

See msdyn_geofencingsettings Entity [msdyn_geofencingsettings_UserEntityInstanceDatas](msdyn_geofencingsettings.md#BKMK_msdyn_geofencingsettings_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdynsm_marketingsitemap_UserEntityInstanceDatas"></a> msdynsm_marketingsitemap_UserEntityInstanceDatas

**Added by**: Trial Site Map Customization Solution

See msdynsm_marketingsitemap Entity [msdynsm_marketingsitemap_UserEntityInstanceDatas](msdynsm_marketingsitemap.md#BKMK_msdynsm_marketingsitemap_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdynsm_salessitemap_UserEntityInstanceDatas"></a> msdynsm_salessitemap_UserEntityInstanceDatas

**Added by**: Trial Site Map Customization Solution

See msdynsm_salessitemap Entity [msdynsm_salessitemap_UserEntityInstanceDatas](msdynsm_salessitemap.md#BKMK_msdynsm_salessitemap_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdynsm_servicessitemap_UserEntityInstanceDatas"></a> msdynsm_servicessitemap_UserEntityInstanceDatas

**Added by**: Trial Site Map Customization Solution

See msdynsm_servicessitemap Entity [msdynsm_servicessitemap_UserEntityInstanceDatas](msdynsm_servicessitemap.md#BKMK_msdynsm_servicessitemap_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_msdynsm_settingssitemap_UserEntityInstanceDatas"></a> msdynsm_settingssitemap_UserEntityInstanceDatas

**Added by**: Trial Site Map Customization Solution

See msdynsm_settingssitemap Entity [msdynsm_settingssitemap_UserEntityInstanceDatas](msdynsm_settingssitemap.md#BKMK_msdynsm_settingssitemap_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_theme_UserEntityInstanceDatas"></a> theme_UserEntityInstanceDatas

See theme Entity [theme_UserEntityInstanceDatas](theme.md#BKMK_theme_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_usermapping_UserEntityInstanceDatas"></a> usermapping_UserEntityInstanceDatas

See usermapping Entity [usermapping_UserEntityInstanceDatas](usermapping.md#BKMK_usermapping_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_knowledgearticle_UserEntityInstanceDatas"></a> knowledgearticle_UserEntityInstanceDatas

See knowledgearticle Entity [knowledgearticle_UserEntityInstanceDatas](knowledgearticle.md#BKMK_knowledgearticle_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_mailbox_userentityinstancedatas"></a> mailbox_userentityinstancedatas

See mailbox Entity [mailbox_userentityinstancedatas](mailbox.md#BKMK_mailbox_userentityinstancedatas) One-To-Many relationship.

### <a name="BKMK_channelaccessprofile_UserEntityInstanceDatas"></a> channelaccessprofile_UserEntityInstanceDatas

See channelaccessprofile Entity [channelaccessprofile_UserEntityInstanceDatas](channelaccessprofile.md#BKMK_channelaccessprofile_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_externalparty_UserEntityInstanceDatas"></a> externalparty_UserEntityInstanceDatas

See externalparty Entity [externalparty_UserEntityInstanceDatas](externalparty.md#BKMK_externalparty_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_profilerule_UserEntityInstanceDatas"></a> profilerule_UserEntityInstanceDatas

See channelaccessprofilerule Entity [profilerule_UserEntityInstanceDatas](channelaccessprofilerule.md#BKMK_profilerule_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_KnowledgeBaseRecord_UserEntityInstanceDatas"></a> KnowledgeBaseRecord_UserEntityInstanceDatas

See knowledgebaserecord Entity [KnowledgeBaseRecord_UserEntityInstanceDatas](knowledgebaserecord.md#BKMK_KnowledgeBaseRecord_UserEntityInstanceDatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_pluginassembly"></a> userentityinstancedata_pluginassembly

See pluginassembly Entity [userentityinstancedata_pluginassembly](pluginassembly.md#BKMK_userentityinstancedata_pluginassembly) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_letter"></a> userentityinstancedata_letter

See letter Entity [userentityinstancedata_letter](letter.md#BKMK_userentityinstancedata_letter) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_organization"></a> userentityinstancedata_organization

See organization Entity [userentityinstancedata_organization](organization.md#BKMK_userentityinstancedata_organization) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_owning_user"></a> userentityinstancedata_owning_user

See systemuser Entity [userentityinstancedata_owning_user](systemuser.md#BKMK_userentityinstancedata_owning_user) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_kbarticlecomment"></a> userentityinstancedata_kbarticlecomment

See kbarticlecomment Entity [userentityinstancedata_kbarticlecomment](kbarticlecomment.md#BKMK_userentityinstancedata_kbarticlecomment) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_processsession"></a> userentityinstancedata_processsession

See processsession Entity [userentityinstancedata_processsession](processsession.md#BKMK_userentityinstancedata_processsession) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_relationshiprolemap"></a> userentityinstancedata_relationshiprolemap

See relationshiprolemap Entity [userentityinstancedata_relationshiprolemap](relationshiprolemap.md#BKMK_userentityinstancedata_relationshiprolemap) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessage"></a> userentityinstancedata_sdkmessage

See sdkmessage Entity [userentityinstancedata_sdkmessage](sdkmessage.md#BKMK_userentityinstancedata_sdkmessage) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_appointment"></a> userentityinstancedata_appointment

See appointment Entity [userentityinstancedata_appointment](appointment.md#BKMK_userentityinstancedata_appointment) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_contact"></a> userentityinstancedata_contact

See contact Entity [userentityinstancedata_contact](contact.md#BKMK_userentityinstancedata_contact) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_picklistmapping"></a> userentityinstancedata_picklistmapping

See picklistmapping Entity [userentityinstancedata_picklistmapping](picklistmapping.md#BKMK_userentityinstancedata_picklistmapping) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_workflow"></a> userentityinstancedata_workflow

See workflow Entity [userentityinstancedata_workflow](workflow.md#BKMK_userentityinstancedata_workflow) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_connectionrole"></a> userentityinstancedata_connectionrole

See connectionrole Entity [userentityinstancedata_connectionrole](connectionrole.md#BKMK_userentityinstancedata_connectionrole) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessagepair"></a> userentityinstancedata_sdkmessagepair

See sdkmessagepair Entity [userentityinstancedata_sdkmessagepair](sdkmessagepair.md#BKMK_userentityinstancedata_sdkmessagepair) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_timezonelocalizedname"></a> userentityinstancedata_timezonelocalizedname

See timezonelocalizedname Entity [userentityinstancedata_timezonelocalizedname](timezonelocalizedname.md#BKMK_userentityinstancedata_timezonelocalizedname) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_savedquery"></a> userentityinstancedata_savedquery

See savedquery Entity [userentityinstancedata_savedquery](savedquery.md#BKMK_userentityinstancedata_savedquery) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_connection"></a> userentityinstancedata_connection

See connection Entity [userentityinstancedata_connection](connection.md#BKMK_userentityinstancedata_connection) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_socialactivity"></a> userentityinstancedata_socialactivity

See socialactivity Entity [userentityinstancedata_socialactivity](socialactivity.md#BKMK_userentityinstancedata_socialactivity) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_transactioncurrency"></a> userentityinstancedata_transactioncurrency

See transactioncurrency Entity [userentityinstancedata_transactioncurrency](transactioncurrency.md#BKMK_userentityinstancedata_transactioncurrency) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_importfile"></a> userentityinstancedata_importfile

See importfile Entity [userentityinstancedata_importfile](importfile.md#BKMK_userentityinstancedata_importfile) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_solution"></a> userentityinstancedata_solution

See solution Entity [userentityinstancedata_solution](solution.md#BKMK_userentityinstancedata_solution) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_transformationparametermapping"></a> userentityinstancedata_transformationparametermapping

See transformationparametermapping Entity [userentityinstancedata_transformationparametermapping](transformationparametermapping.md#BKMK_userentityinstancedata_transformationparametermapping) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_plugintype"></a> userentityinstancedata_plugintype

See plugintype Entity [userentityinstancedata_plugintype](plugintype.md#BKMK_userentityinstancedata_plugintype) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_userentityuisettings"></a> userentityinstancedata_userentityuisettings

See userentityuisettings Entity [userentityinstancedata_userentityuisettings](userentityuisettings.md#BKMK_userentityinstancedata_userentityuisettings) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_phonecall"></a> userentityinstancedata_phonecall

See phonecall Entity [userentityinstancedata_phonecall](phonecall.md#BKMK_userentityinstancedata_phonecall) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessagerequest"></a> userentityinstancedata_sdkmessagerequest

See sdkmessagerequest Entity [userentityinstancedata_sdkmessagerequest](sdkmessagerequest.md#BKMK_userentityinstancedata_sdkmessagerequest) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessageprocessingstepsecureconfig"></a> userentityinstancedata_sdkmessageprocessingstepsecureconfig

See sdkmessageprocessingstepsecureconfig Entity [userentityinstancedata_sdkmessageprocessingstepsecureconfig](sdkmessageprocessingstepsecureconfig.md#BKMK_userentityinstancedata_sdkmessageprocessingstepsecureconfig) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_customeraddress"></a> userentityinstancedata_customeraddress

See customeraddress Entity [userentityinstancedata_customeraddress](customeraddress.md#BKMK_userentityinstancedata_customeraddress) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_invaliddependency"></a> userentityinstancedata_invaliddependency

See invaliddependency Entity [userentityinstancedata_invaliddependency](invaliddependency.md#BKMK_userentityinstancedata_invaliddependency) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_recurringappointmentmaster"></a> userentityinstancedata_recurringappointmentmaster

See recurringappointmentmaster Entity [userentityinstancedata_recurringappointmentmaster](recurringappointmentmaster.md#BKMK_userentityinstancedata_recurringappointmentmaster) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_queueitem"></a> userentityinstancedata_queueitem

See queueitem Entity [userentityinstancedata_queueitem](queueitem.md#BKMK_userentityinstancedata_queueitem) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_reportvisibility"></a> userentityinstancedata_reportvisibility

See reportvisibility Entity [userentityinstancedata_reportvisibility](reportvisibility.md#BKMK_userentityinstancedata_reportvisibility) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_import"></a> userentityinstancedata_import

See import Entity [userentityinstancedata_import](import.md#BKMK_userentityinstancedata_import) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_goalrollupquery"></a> userentityinstancedata_goalrollupquery

See goalrollupquery Entity [userentityinstancedata_goalrollupquery](goalrollupquery.md#BKMK_userentityinstancedata_goalrollupquery) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_workflowlog"></a> userentityinstancedata_workflowlog

See workflowlog Entity [userentityinstancedata_workflowlog](workflowlog.md#BKMK_userentityinstancedata_workflowlog) One-To-Many relationship.

### <a name="BKMK_ConvertRule_userentityinstancedatas"></a> ConvertRule_userentityinstancedatas

See convertrule Entity [ConvertRule_userentityinstancedatas](convertrule.md#BKMK_ConvertRule_userentityinstancedatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_team"></a> userentityinstancedata_team

See team Entity [userentityinstancedata_team](team.md#BKMK_userentityinstancedata_team) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_ribboncustomization"></a> userentityinstancedata_ribboncustomization

See ribboncustomization Entity [userentityinstancedata_ribboncustomization](ribboncustomization.md#BKMK_userentityinstancedata_ribboncustomization) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_userqueryvisualization"></a> userentityinstancedata_userqueryvisualization

See userqueryvisualization Entity [userentityinstancedata_userqueryvisualization](userqueryvisualization.md#BKMK_userentityinstancedata_userqueryvisualization) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_businessunitnewsarticle"></a> userentityinstancedata_businessunitnewsarticle

See businessunitnewsarticle Entity [userentityinstancedata_businessunitnewsarticle](businessunitnewsarticle.md#BKMK_userentityinstancedata_businessunitnewsarticle) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_kbarticletemplate"></a> userentityinstancedata_kbarticletemplate

See kbarticletemplate Entity [userentityinstancedata_kbarticletemplate](kbarticletemplate.md#BKMK_userentityinstancedata_kbarticletemplate) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_connectionroleobjecttypecode"></a> userentityinstancedata_connectionroleobjecttypecode

See connectionroleobjecttypecode Entity [userentityinstancedata_connectionroleobjecttypecode](connectionroleobjecttypecode.md#BKMK_userentityinstancedata_connectionroleobjecttypecode) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_email"></a> userentityinstancedata_email

See email Entity [userentityinstancedata_email](email.md#BKMK_userentityinstancedata_email) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sitemap"></a> userentityinstancedata_sitemap

See sitemap Entity [userentityinstancedata_sitemap](sitemap.md#BKMK_userentityinstancedata_sitemap) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_transformationmapping"></a> userentityinstancedata_transformationmapping

See transformationmapping Entity [userentityinstancedata_transformationmapping](transformationmapping.md#BKMK_userentityinstancedata_transformationmapping) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_fieldpermission"></a> userentityinstancedata_fieldpermission

See fieldpermission Entity [userentityinstancedata_fieldpermission](fieldpermission.md#BKMK_userentityinstancedata_fieldpermission) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_task"></a> userentityinstancedata_task

See task Entity [userentityinstancedata_task](task.md#BKMK_userentityinstancedata_task) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_savedqueryvisualization"></a> userentityinstancedata_savedqueryvisualization

See savedqueryvisualization Entity [userentityinstancedata_savedqueryvisualization](savedqueryvisualization.md#BKMK_userentityinstancedata_savedqueryvisualization) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_importlog"></a> userentityinstancedata_importlog

See importlog Entity [userentityinstancedata_importlog](importlog.md#BKMK_userentityinstancedata_importlog) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_connectionroleassociation"></a> userentityinstancedata_connectionroleassociation

See connectionroleassociation Entity [userentityinstancedata_connectionroleassociation](connectionroleassociation.md#BKMK_userentityinstancedata_connectionroleassociation) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_metric"></a> userentityinstancedata_metric

See metric Entity [userentityinstancedata_metric](metric.md#BKMK_userentityinstancedata_metric) One-To-Many relationship.

### <a name="BKMK_slabase_userentityinstancedatas"></a> slabase_userentityinstancedatas

See sla Entity [slabase_userentityinstancedatas](sla.md#BKMK_slabase_userentityinstancedatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_kbarticle"></a> userentityinstancedata_kbarticle

See kbarticle Entity [userentityinstancedata_kbarticle](kbarticle.md#BKMK_userentityinstancedata_kbarticle) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_annotation"></a> userentityinstancedata_annotation

See annotation Entity [userentityinstancedata_annotation](annotation.md#BKMK_userentityinstancedata_annotation) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_importentitymapping"></a> userentityinstancedata_importentitymapping

See importentitymapping Entity [userentityinstancedata_importentitymapping](importentitymapping.md#BKMK_userentityinstancedata_importentitymapping) One-To-Many relationship.

### <a name="BKMK_team_userentityinstancedata"></a> team_userentityinstancedata

See team Entity [team_userentityinstancedata](team.md#BKMK_team_userentityinstancedata) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_dependency"></a> userentityinstancedata_dependency

See dependency Entity [userentityinstancedata_dependency](dependency.md#BKMK_userentityinstancedata_dependency) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_duplicaterecord"></a> userentityinstancedata_duplicaterecord

See duplicaterecord Entity [userentityinstancedata_duplicaterecord](duplicaterecord.md#BKMK_userentityinstancedata_duplicaterecord) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_timezonedefinition"></a> userentityinstancedata_timezonedefinition

See timezonedefinition Entity [userentityinstancedata_timezonedefinition](timezonedefinition.md#BKMK_userentityinstancedata_timezonedefinition) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_calendar"></a> userentityinstancedata_calendar

See calendar Entity [userentityinstancedata_calendar](calendar.md#BKMK_userentityinstancedata_calendar) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessageprocessingstep"></a> userentityinstancedata_sdkmessageprocessingstep

See sdkmessageprocessingstep Entity [userentityinstancedata_sdkmessageprocessingstep](sdkmessageprocessingstep.md#BKMK_userentityinstancedata_sdkmessageprocessingstep) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_systemuser"></a> userentityinstancedata_systemuser

See systemuser Entity [userentityinstancedata_systemuser](systemuser.md#BKMK_userentityinstancedata_systemuser) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessagerequestfield"></a> userentityinstancedata_sdkmessagerequestfield

See sdkmessagerequestfield Entity [userentityinstancedata_sdkmessagerequestfield](sdkmessagerequestfield.md#BKMK_userentityinstancedata_sdkmessagerequestfield) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_plugintypestatistic"></a> userentityinstancedata_plugintypestatistic

See plugintypestatistic Entity [userentityinstancedata_plugintypestatistic](plugintypestatistic.md#BKMK_userentityinstancedata_plugintypestatistic) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_rollupfield"></a> userentityinstancedata_rollupfield

See rollupfield Entity [userentityinstancedata_rollupfield](rollupfield.md#BKMK_userentityinstancedata_rollupfield) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_relationshiprole"></a> userentityinstancedata_relationshiprole

See relationshiprole Entity [userentityinstancedata_relationshiprole](relationshiprole.md#BKMK_userentityinstancedata_relationshiprole) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_activitymimeattachment"></a> userentityinstancedata_activitymimeattachment

See activitymimeattachment Entity [userentityinstancedata_activitymimeattachment](activitymimeattachment.md#BKMK_userentityinstancedata_activitymimeattachment) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_role"></a> userentityinstancedata_role

See role Entity [userentityinstancedata_role](role.md#BKMK_userentityinstancedata_role) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_columnmapping"></a> userentityinstancedata_columnmapping

See columnmapping Entity [userentityinstancedata_columnmapping](columnmapping.md#BKMK_userentityinstancedata_columnmapping) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_publisheraddress"></a> userentityinstancedata_publisheraddress

See publisheraddress Entity [userentityinstancedata_publisheraddress](publisheraddress.md#BKMK_userentityinstancedata_publisheraddress) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_audit"></a> userentityinstancedata_audit

See audit Entity [userentityinstancedata_audit](audit.md#BKMK_userentityinstancedata_audit) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_subject"></a> userentityinstancedata_subject

See subject Entity [userentityinstancedata_subject](subject.md#BKMK_userentityinstancedata_subject) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_attributemap"></a> userentityinstancedata_attributemap

See attributemap Entity [userentityinstancedata_attributemap](attributemap.md#BKMK_userentityinstancedata_attributemap) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_lookupmapping"></a> userentityinstancedata_lookupmapping

See lookupmapping Entity [userentityinstancedata_lookupmapping](lookupmapping.md#BKMK_userentityinstancedata_lookupmapping) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_account"></a> userentityinstancedata_account

See account Entity [userentityinstancedata_account](account.md#BKMK_userentityinstancedata_account) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessageresponsefield"></a> userentityinstancedata_sdkmessageresponsefield

See sdkmessageresponsefield Entity [userentityinstancedata_sdkmessageresponsefield](sdkmessageresponsefield.md#BKMK_userentityinstancedata_sdkmessageresponsefield) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_teammembership"></a> userentityinstancedata_teammembership

See teammembership Entity [userentityinstancedata_teammembership](teammembership.md#BKMK_userentityinstancedata_teammembership) One-To-Many relationship.

### <a name="BKMK_routingrule_userentityinstancedatas"></a> routingrule_userentityinstancedatas

See routingrule Entity [routingrule_userentityinstancedatas](routingrule.md#BKMK_routingrule_userentityinstancedatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_principalobjectattributeaccess"></a> userentityinstancedata_principalobjectattributeaccess

See principalobjectattributeaccess Entity [userentityinstancedata_principalobjectattributeaccess](principalobjectattributeaccess.md#BKMK_userentityinstancedata_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_duplicaterule"></a> userentityinstancedata_duplicaterule

See duplicaterule Entity [userentityinstancedata_duplicaterule](duplicaterule.md#BKMK_userentityinstancedata_duplicaterule) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_report"></a> userentityinstancedata_report

See report Entity [userentityinstancedata_report](report.md#BKMK_userentityinstancedata_report) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_isvconfig"></a> userentityinstancedata_isvconfig

See isvconfig Entity [userentityinstancedata_isvconfig](isvconfig.md#BKMK_userentityinstancedata_isvconfig) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_goal"></a> userentityinstancedata_goal

See goal Entity [userentityinstancedata_goal](goal.md#BKMK_userentityinstancedata_goal) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_mailmergetemplate"></a> userentityinstancedata_mailmergetemplate

See mailmergetemplate Entity [userentityinstancedata_mailmergetemplate](mailmergetemplate.md#BKMK_userentityinstancedata_mailmergetemplate) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_bulkdeleteoperation"></a> userentityinstancedata_bulkdeleteoperation

See bulkdeleteoperation Entity [userentityinstancedata_bulkdeleteoperation](bulkdeleteoperation.md#BKMK_userentityinstancedata_bulkdeleteoperation) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sharepointsite"></a> userentityinstancedata_sharepointsite

See sharepointsite Entity [userentityinstancedata_sharepointsite](sharepointsite.md#BKMK_userentityinstancedata_sharepointsite) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_publisher"></a> userentityinstancedata_publisher

See publisher Entity [userentityinstancedata_publisher](publisher.md#BKMK_userentityinstancedata_publisher) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_businessunit"></a> userentityinstancedata_businessunit

See businessunit Entity [userentityinstancedata_businessunit](businessunit.md#BKMK_userentityinstancedata_businessunit) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_userform"></a> userentityinstancedata_userform

See userform Entity [userentityinstancedata_userform](userform.md#BKMK_userentityinstancedata_userform) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_license"></a> userentityinstancedata_license

See license Entity [userentityinstancedata_license](license.md#BKMK_userentityinstancedata_license) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_solutioncomponent"></a> userentityinstancedata_solutioncomponent

See solutioncomponent Entity [userentityinstancedata_solutioncomponent](solutioncomponent.md#BKMK_userentityinstancedata_solutioncomponent) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_reportcategory"></a> userentityinstancedata_reportcategory

See reportcategory Entity [userentityinstancedata_reportcategory](reportcategory.md#BKMK_userentityinstancedata_reportcategory) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_queue"></a> userentityinstancedata_queue

See queue Entity [userentityinstancedata_queue](queue.md#BKMK_userentityinstancedata_queue) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_duplicaterulecondition"></a> userentityinstancedata_duplicaterulecondition

See duplicaterulecondition Entity [userentityinstancedata_duplicaterulecondition](duplicaterulecondition.md#BKMK_userentityinstancedata_duplicaterulecondition) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_webresource"></a> userentityinstancedata_webresource

See webresource Entity [userentityinstancedata_webresource](webresource.md#BKMK_userentityinstancedata_webresource) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_workflowdependency"></a> userentityinstancedata_workflowdependency

See workflowdependency Entity [userentityinstancedata_workflowdependency](workflowdependency.md#BKMK_userentityinstancedata_workflowdependency) One-To-Many relationship.

### <a name="BKMK_routingruleitem_userentityinstancedatas"></a> routingruleitem_userentityinstancedatas

See routingruleitem Entity [routingruleitem_userentityinstancedatas](routingruleitem.md#BKMK_routingruleitem_userentityinstancedatas) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_customerrelationship"></a> userentityinstancedata_customerrelationship

See customerrelationship Entity [userentityinstancedata_customerrelationship](customerrelationship.md#BKMK_userentityinstancedata_customerrelationship) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_entitymap"></a> userentityinstancedata_entitymap

See entitymap Entity [userentityinstancedata_entitymap](entitymap.md#BKMK_userentityinstancedata_entitymap) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_fieldsecurityprofile"></a> userentityinstancedata_fieldsecurityprofile

See fieldsecurityprofile Entity [userentityinstancedata_fieldsecurityprofile](fieldsecurityprofile.md#BKMK_userentityinstancedata_fieldsecurityprofile) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_asyncoperation"></a> userentityinstancedata_asyncoperation

See asyncoperation Entity [userentityinstancedata_asyncoperation](asyncoperation.md#BKMK_userentityinstancedata_asyncoperation) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_timezonerule"></a> userentityinstancedata_timezonerule

See timezonerule Entity [userentityinstancedata_timezonerule](timezonerule.md#BKMK_userentityinstancedata_timezonerule) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_ownermapping"></a> userentityinstancedata_ownermapping

See ownermapping Entity [userentityinstancedata_ownermapping](ownermapping.md#BKMK_userentityinstancedata_ownermapping) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_activityparty"></a> userentityinstancedata_activityparty

See activityparty Entity [userentityinstancedata_activityparty](activityparty.md#BKMK_userentityinstancedata_activityparty) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_displaystring"></a> userentityinstancedata_displaystring

See displaystring Entity [userentityinstancedata_displaystring](displaystring.md#BKMK_userentityinstancedata_displaystring) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_importjob"></a> userentityinstancedata_importjob

See importjob Entity [userentityinstancedata_importjob](importjob.md#BKMK_userentityinstancedata_importjob) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessageprocessingstepimage"></a> userentityinstancedata_sdkmessageprocessingstepimage

See sdkmessageprocessingstepimage Entity [userentityinstancedata_sdkmessageprocessingstepimage](sdkmessageprocessingstepimage.md#BKMK_userentityinstancedata_sdkmessageprocessingstepimage) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_template"></a> userentityinstancedata_template

See template Entity [userentityinstancedata_template](template.md#BKMK_userentityinstancedata_template) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_userquery"></a> userentityinstancedata_userquery

See userquery Entity [userentityinstancedata_userquery](userquery.md#BKMK_userentityinstancedata_userquery) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_bulkdeletefailure"></a> userentityinstancedata_bulkdeletefailure

See bulkdeletefailure Entity [userentityinstancedata_bulkdeletefailure](bulkdeletefailure.md#BKMK_userentityinstancedata_bulkdeletefailure) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sharepointdocumentlocation"></a> userentityinstancedata_sharepointdocumentlocation

See sharepointdocumentlocation Entity [userentityinstancedata_sharepointdocumentlocation](sharepointdocumentlocation.md#BKMK_userentityinstancedata_sharepointdocumentlocation) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessageresponse"></a> userentityinstancedata_sdkmessageresponse

See sdkmessageresponse Entity [userentityinstancedata_sdkmessageresponse](sdkmessageresponse.md#BKMK_userentityinstancedata_sdkmessageresponse) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_serviceendpoint"></a> userentityinstancedata_serviceendpoint

See serviceendpoint Entity [userentityinstancedata_serviceendpoint](serviceendpoint.md#BKMK_userentityinstancedata_serviceendpoint) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_reportentity"></a> userentityinstancedata_reportentity

See reportentity Entity [userentityinstancedata_reportentity](reportentity.md#BKMK_userentityinstancedata_reportentity) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_importmap"></a> userentityinstancedata_importmap

See importmap Entity [userentityinstancedata_importmap](importmap.md#BKMK_userentityinstancedata_importmap) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_fax"></a> userentityinstancedata_fax

See fax Entity [userentityinstancedata_fax](fax.md#BKMK_userentityinstancedata_fax) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_privilege"></a> userentityinstancedata_privilege

See privilege Entity [userentityinstancedata_privilege](privilege.md#BKMK_userentityinstancedata_privilege) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_sdkmessagefilter"></a> userentityinstancedata_sdkmessagefilter

See sdkmessagefilter Entity [userentityinstancedata_sdkmessagefilter](sdkmessagefilter.md#BKMK_userentityinstancedata_sdkmessagefilter) One-To-Many relationship.

### <a name="BKMK_userentityinstancedata_reportlink"></a> userentityinstancedata_reportlink

See reportlink Entity [userentityinstancedata_reportlink](reportlink.md#BKMK_userentityinstancedata_reportlink) One-To-Many relationship.

### See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.userentityinstancedata?text=userentityinstancedata EntityType" />