---
title: "Configure mobile offline synchronization in Dynamics 365 for phones and tablets | MicrosoftDocs"
ms.custom: 
ms.date: 08/20/2019
ms.reviewer: 
ms.service: crm-online
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: article
applies_to: Dynamics 365 apps
ms.assetid: 7f992770-8c7b-48ba-806a-63a3634d209c
caps.latest.revision: 7
ms.author: mkaur
author: mduelae
manager: kvivek
search.audienceType: 
  - admin
  - customizer
  - enduser
search.app: 
  - D365CE
  - D365Sales
---

# Set up mobile offline synchronization to allow users to work in offline mode on their mobile device 

Mobile offline allows your users to use the Dynamics 365 for phones app in offline mode to interact with their data, even when they are not connected to the internet. The Dynamics 365 for phones app provides a rich offline experience and helps you to stay productive. You can use basic commands such as create, read, update, and delete when you are offline. Once you are back online, your changes are automatically synchronized with your Dynamics 365 for phones app. 

> [!Note]
> - The mobile offline feature is only available for iOS and Android devices.
> - To use the mobile offline feature, download the latest version of the Dynamics 365 for phones and tablet app from the app store. For iOS, version 13.19043.32 or later is supported; for Android, version 4.3.19043.33 or later supported.

To allows users to use this feature, a Dynamics 365 administrator will need to set up mobile offline for their organization. 
  
This offline experience uses [!INCLUDE[pn_Windows_Azure](../includes/pn-windows-azure.md)] services to periodically synchronize entities with the Dynamics 365 for phones and tablets apps so synchronized records are available when users’ mobile devices are disconnected. To enable mobile offline synchronization, follow the steps below.
 
 
## Step 1: Enable entities for mobile offline synchronization 
 
One of the first things you need to do is enable entities that will be available to mobile users when they're using the mobile app in offline mode. 
  
The following entities are available for you to enable in offline mode:  
  
- Account  

- Activity Pointer
  
- Appointment  
  
- Attachment 

- Case
  
- Competitor  
  
- Competitor Address  

- Connection

- Connection Role
  
- Contact  

- Custom Entity
  
- Email  
  
- Lead    
  
- Opportunity  
  
- Opportunity Product  

- Phone Call

- Position
  
- Product  
  
- Task 

- Team  
  
- User  

  > [!NOTE] 
  > You can disable or enable any of the above supported entities for offline mode. The next section shows you how to enable or disable an entity. 

### To enable more entities for offline:
  
1. In the **Dynamics 365- custom** app, go to **Settings** > **Customizations**.  

   > [!div class="mx-imgBorder"]
   >![Setting Customizations](media/Settings_Custom1.png "Settings Customizations")
  
2. Select **Customize the System**.  

   > [!div class="mx-imgBorder"]
   >![Select a Customize the System](media/Settings_Custom.png "Customize the System")
  
3. Expand **Entities** in the left pane.  
  
4. Select the entity you want to enable for mobile offline (for example, **Account**).  
  
5. Under **Outlook & Mobile**, select **Enable for mobile offline**. 

   > [!div class="mx-imgBorder"]
   >![Select a Customize the System](media/Settings_Custom3.png "Customize the System")
 
6. Select **Organization data download filter** to filter the data and set the freshness of the data you want to make available offline. You can set up to three criteria when you define a filter. Select the field to filter by, select an operator, then set a value. 
  
    The entities that are enabled for mobile offline by default have **Modified On** set for **Last X Days** = 10, so the data modified or created in the last 10 days will be available for downloading to mobile devices.  
  
7. Select **Save**.  
  
8. When you’re done enabling entities for mobile offline, select **Publish** so your changes take effect.  

> [!WARNING]
> Keep in mind that the amount of data you make available to users while they’re offline can affect the data usage rates for devices on cellular networks. The amount of data depends on:  
>   
> -   The number of entities you enable for mobile offline.  
> -   The number of days you specify since records were last modified.  
> -   The filters you set while creating mobile offline profiles.  
 
## Step 2: Create a mobile offline profile to determine what data will be available while offline
 
You need to create mobile offline profiles for users to configure filters that determine how much of an entity's data (and related entities' data) will be available to the user while offline.  

> [!NOTE] 
> -  A user must have a security role that has Read permissions on the mobile offline profile to be able to use their mobile device in offline mode.
  
1. Go to Power Platform Admin center, [https://admin.powerplatform.microsoft.com](https://admin.powerplatform.microsoft.com) and sign-in as an admin.

2. On the right, select **Environments**.

   > [!div class="mx-imgBorder"]
   >![Select a Enviroment](media/offline_admincenter_enviroments.png "Select a Enviroment")
 
3. Choose an enviroment and then select **Settings**.

   > [!div class="mx-imgBorder"]
   >![Enviroment settings](media/offline_open_an_enviroment.png "Enviroment settings")
 
4. Under **Users + Permissions**, select **Mobile configuration**.

   > [!div class="mx-imgBorder"]
   >![Mobile configuration setting](media/offline_mobile_config_settings.png "Mobile configuration settings")
  
5. On the next screen, select **Mobile Offline Profiles**.  

   > [!div class="mx-imgBorder"]
   >![Mobile Offline Profile screen](media/mobileofflineprofile.png "Mobile Offline Profile screen")

6. Select **New** to create a new mobile offline profile. If you already have one that you want to edit, select it from the list.  
  
7. Enter a name and description for your mobile offline profile. Select **Save** to create the mobile offline profile so you can continue to edit it.  
    
   > [!div class="mx-imgBorder"]
   >![Name your mobile offline profile](media/namemobileofflineprofile.png "Name your mobile offline profile")
  
  
8. In the **MOBILE OFFLINE PROFILE DETAILS** area, select **Add Mobile Offline Profile item record** to create a new mobile offline profile item. You need to create a mobile offline profile item for each entity you want to make available for this mobile offline profile.  

   > [!div class="mx-imgBorder"]
   >![Enter Mobile Offline Profile Item details](media/namemobileofflineprofile2.png "Enter Mobile Offline Profile Item details")
  
9. Enter a name and select an entity. Only entities that you enabled (in **Step 1**) for mobile offline appear in this list.  

   > [!div class="mx-imgBorder"]
   >![Enter Mobile Offline Profile Item name](media/profileitemname1.png "Enter Profile Item name")
 

   Select a **Data Download Filter** based on the ownership type for the entity.
 
**User or Team**
  
   - **Download related data only**. Make related data for this entity available offline. If you don’t set any relationships, no records for this entity will be available.  
  
   - **All records**. Make all records for this entity available offline.  
  
   - **Other data filter**. Make only the specified records for this entity available offline.  
  
   If you select **Other records**, you can choose from the following:  
  
   - **Download my records**. Make only your records available offline.  
  
   - **Download my team’s records**. Make your team’s records available offline.  
  
   - **Download my business unit’s records**. Make your business unit’s records available offline.  
  
 **Organization**  
  
   - **Download related data only**. Make related data for this entity available offline. If you don’t set any relationships, no records for this entity will be available.  
  
   - **All records**. Make all records for this entity available offline.  
  
 **Business**  
  
   - **Download related data only**. Make related data for this entity available offline. If you don’t set any relationships, no records for this entity will be available.  
  
   - **All records**. Make all records for this entity available offline.  
  
   - **Other records**. Make only the specified records for this entity available offline.  
  
   If you select **Other records**, you can choose from the following:  
  
   - **Download my business unit’s records**. Make your business unit’s records available offline.  
  
 **None**  
  
   - **Download related data only**. Make related data for this entity available offline. If you don’t set any relationships, no records for this entity will be available.  
    
Admins can define a custom filter based on the following rules. You can create filters up to three levels.  
    

 |  |
 |---------|
 |equal     |
 |not equal     |
 |gt – greater than|  
 |ge – greater than or equal to|  
 |le – less than or equal to|  
 |lt – less than|  
 |like|  
 |not-like|  
 |in|  
 |not-in|  
 |null|  
 |not-null|  
 |eq-userid|  
 |ne-userid|  
 |eq-userteams|  
 |eq-useroruserteams|  
 |eq-useroruserhierarchy|  
 |eq-useroruserhierarchyandteams|  
 |eq-businessid|  
 |ne-businessid|  
 |eq-userlanguage|  
 |begins-with|  
 |not-begin-with|  
 |ends-with|  
 |not-end-with|
  
10. Select **Save** to create the mobile offline profile item so you can continue editing it.  
  
11. In the **MOBILE OFFLINE PROFILE ITEM ASSOCIATIONS DETAILS** area, select **Add Mobile Offline Profile Item Association record** to create a new mobile offline profile item association. You need to create a mobile offline profile item association for each related record you want to make available offline. In addition, you need to include any related entities in this mobile offline profile.  
  
     For example, if you create a mobile offline profile item association from the Lead entity, you need to add the Lead entity to this mobile offline profile.  
     
   > [!div class="mx-imgBorder"]
   >![Add Lead entity to offline profile](media/addleadentity1.png "Add Lead entity to offline profile")
  
12. Enter a name for the mobile offline profile item association, select a relationship, and then select **Save**.  
  
    When you’re done adding mobile offline profile item associations to the mobile offline profile item, select **Save & Close** on the **MOBILE OFFLINE PROFILE ITEM ASSOCIATION** screen.  
  
14. When you’re done adding mobile offline profile item details to the mobile offline profile item, select **Save** at the lower right corner of the **MOBILE OFFLINE PROFILE ITEM** window.  
 
### Step 2.1: Add users to a mobile offline profile 

Once you have created a mobile offline profile, you can start adding users to the profile.  
  
> [!NOTE]
> You can add a user to only one mobile offline profile.
> Each time user is added to the mobile offline profile, mobile offline profile need to be published again. 
  
1.  If it’s not already open, open the mobile offline profile you want to add users to.  
 
2.  In the **USERS** area, select **Add User record** to add a new user.  

   > [!div class="mx-imgBorder"]
   >![Add a user](media/adduser1.png "Add a user")
  
3.  Select the lookup field that appears and select a user to add to this mobile offline profile.  
  
4.  When you’re done adding users, select **Save** icon in the lower right corner of the screen.  

### Step 2.2: Publish a mobile offline profile

To make a mobile offline profile available to users so they can get the mobile offline experience you've defined for them, you need to publish the profile.  
  
1. If it’s not already open, open the mobile offline profile you want to publish.  
  
2. When you’re done adding users and making any other changes to the mobile offline profile, select **Publish** so the data you specified can start syncing with your users’ mobile devices.  

   > [!div class="mx-imgBorder"]
   >![Publish offline profile](media/publishprofile1.png "Publish offline profile")
  
> [!TIP]
> **Solution export and import**  
>   
>  When exporting a solution that includes a mobile offline profile, always select the **Include entity metadata** check box for each entity you export.  
>   
>  After importing the solution into the target organization, publish all mobile offline profiles.  

### Step 2.3: Set conflict detection for mobile offline  

1. In the **Dynamics 365 - custom** app, go to **Settings** > **Administration** > **System Settings**.

   > [!div class="mx-imgBorder"]
   >![Settings pages](media/settings-admin.png "Setting page")

2. To configure conflict resolution behavior, select **Mobile Client**.

   > [!div class="mx-imgBorder"]
   >![Set conflict detection for mobile offline](media/detectconflict1.png "Set conflict detection for mobile offline")


When there is a mismatch of data between client and server, conflict errors occur. To resolve those, you can choose one of the following settings:

- Select **No** - Conflict detection for mobile offline is turned off, so whatever changes are made by a user in offline mode are automatically synced to the server when the user is back online, and client wins over server.

- Select **Yes** - Server wins over client.

## Step 3: Enable the app module for offline

Enable mobile offline for a specific app from MyApps page.

1. In the **Dynamics 365 - custom** app, go to **Settings** > **My Apps**.

   > [!div class="mx-imgBorder"]
   >![My Apps in Settings](media/My_Apps.png "Go to My Apps in Settings")

2. From the list of published apps, select **More Options** and then choose, **OPEN IN APP DESIGNER** to open the app designer to add or edit componets.

   > [!div class="mx-imgBorder"]
   >![Open App Designer](media/OpenAppDesigner2.png "Open App Designer")

3. Select the the **Properties** tab, and scroll down to select **Enable Mobile Offline** and then choose a mobile offline profile.

   > [!div class="mx-imgBorder"]
   >![Enable mobile offline for the app](media/OpenAppDesigner1.png "Enable mobile offline for the app")
   
   > [!NOTE] 
   > You can add more than one profile for an app module.

4. At the top choose **Save** and then **Publish**.

## Tips

Here are a few things to keep in mind about mobile offline synchronization:  
  
- Mobile offline synchronization with mobile devices occurs periodically. A synchronization cycle could last for several minutes, depending on Azure network latency, the volume of data that’s set for synchronization, and mobile network speed. Users can still use the mobile apps during synchronization.  
  
- The time for initial metadata download is determined by the number of total entities in offline-enabled app modules. Make sure to enable only those entities and app modules for offline that are necessary to optimize the experience for end users. 
  
- Ensure that any view that you want to work in offline doesn’t reference the entities that are not offline-enabled. For example, assuming Account is in the offline profile, then an Account view that references the primary contact when Contact is not in the profile will not be available.

- Changes to a user’s security privileges are updated during the next synchronization cycle. Until that time, users can continue to access data according to their previous security privileges, but any changes they make will be validated during the synchronization to the Dynamics 365 server. If they no longer have privileges to make changes for a record, they will receive an error and the record won’t be created, updated, or deleted.

- Any changes to a user’s privilege to view a record won’t take effect on the mobile device until the next synchronization cycle.
  
  
## Limitations and recommendations 

### Organization data filter 
It is recommended that you have at least one rule defined for all mobile offline-enabled entity for org filters, if you are using the entities across profiles.  By default, this value is set to last 10 days for most of the offline-enabled entities.

 > [!div class="mx-imgBorder"]
 >![Edit org data filter](media/datafilter_1.png "Edit org data filter")


### Profile filters 

**Profile limitations**

|Profile details |Limitation|  
|-------------|---------|  
|User in profile|	2,000|
|Relationship defined for each entity|Maximum of 10 relationships. And maximum of one many to many (M:M) or one to many (1:M) relationships within those 10 relationships. If any custom entities demand this scenario, then revisit the data model. No circular references or self-references are supported.|


### Profile filter rules recommendation 

Ensure that you have configured at least one of the Profile rules for each entity to download its data. 
  
|Customization |Recommendation|  
|-------------|---------|  
|All Records|	If you are selecting this filter, you cannot define any other filter rule.|
|Download Related Data only|If you are selecting this filter, you cannot define any other filter rule. Ensure that the entity has been defined as a Profile Item Association entity also.|
|Other Data Filter - if selected, then select at least one of these options: **Download my Records**, **Download my team records**, or **Download my business unit**  |	If you want to define this filter you have to pick at least one of the given options. It is highly recommended to not have Business Unit level filter for an entity unless there is a strong justification. It is recommended for a master data scenario with a small data set like Country codes. |
|Custom Data Filter |<=3 filters can be defined in the custom data filter. |


### Data volume recommendation 


The recommended data volume should be <=  10,000 records per user subscription.

## Known issues

- When you change the business unit of a user, then the user is removed from the mobile offline profile.

- **Business Process Flows**: Business process flows are not supported for mobile offline. When you are offline, business process flows grids and views will not be available and business process flows will not be rendered on records that are opened in offline mode. If a record containing a business process flow was loaded prior to going offline, business process flow functions, such as move next or move previous will not work. Business process flows support the ability to branch to a different set of stages, based on conditions defined on fields of the record. In offline mode, these conditions to determine the next set of stages in the business process flows will not be evaluated.

- **Qualify a lead**: When a lead created in mobile offline is qualified and when the user goes online, the business process stage will still show the  qualify stage. The user will have to manually click **Next stage** to move to the next stage.


- **Views** are not supported for the following entities in offline mode: 

  - Email

  - Task

  - Appointment

  - Fax

  - Phonecall

  - Letter

  - Serviceappointment

  - Campaignresponse

  - Campaignactivity

  - Recurringappointmentmaster

  - Socialactivity

  Any views that have linked entities (related entity) that are not available offline are also not supported. 




