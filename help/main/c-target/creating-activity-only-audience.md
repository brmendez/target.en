---
keywords: audience;audience rules;create audience;creating audience;activity only;activity-only;adhoc
description: Learn how to create activity-only audiences in Adobe [!DNL Target] that are for one-time use.
title: Can I Create an Audience to Use Only Once?
feature: Audiences
exl-id: 5fe0507a-75d1-47bc-a941-8c8eeeaf3b75
---
# Create an activity-only audience

Create activity-only audiences from within the [!DNL Adobe Target] three-step guided workflow while creating an activity. These ad hoc audiences can be used in other places within the same activity, but are not stored in the [!UICONTROL Audiences Library] for use in other activities.

Activity-only audiences provide the following benefits:

* You can use activity-only audiences to create an audience that you want to use only once and you do not want to store it in the [!UICONTROL Audiences Library]. Activity-only audiences help prevent the [!UICONTROL Audiences Library] from being cluttered with audiences that you never want to use again. 
* Activity-only audiences are not visible in the [!UICONTROL Audiences Library]. Because these audiences are not visible in the library, they are shielded from unwanted changes by others in your organization.

1. While creating an [activity](/help/main/c-activities/activities.md#concept_D317A95A1AB54674BA7AB65C7985BA03), on the **[!UICONTROL Targeting]** page, click the three vertical ellipses, then click **[!UICONTROL Replace Audience]**.

   ![Step Result](assets/edit_audience.png)

1. Click **[!UICONTROL Create Audience]**.

1. Click **[!UICONTROL This activity only]**.

   ![](assets/activity-only-aud.png)
 
1. Type a descriptive audience name. 
1. Drag and drop the desired attributes into the audience builder.

   Rules make it possible to limit your audience to a subset of your site visitors. Each rule type has its own parameters. See [Categories for Audiences](/help/main/c-target/c-audiences/c-target-rules/target-rules.md#concept_E3A77E42F1644503A829B5107B20880D) for more information on configuring each type of audience rule. 
 
1. Click **[!UICONTROL Done]**.

## Considerations

Keep the following information in mind as you work with activity-only audiences:

* You can create activity-only audiences in the [!UICONTROL Visual Experience Composer] (VEC) or in the [!UICONTROL Form-Based Experience Composer]. This functionality replaces refinement rules in previous versions of [!DNL Target]. 
* You can create an activity to store in the [!UICONTROL Audience Library] for reuse in other activities or you create an activity-only audience. After saving the audience, you cannot change the audience type. 
* Refinements for existing activities are migrated to activity-only audiences. 
* Activity-only audiences have a status of [!UICONTROL Used] or [!UICONTROL Unused]. Unused activity-only audiences display until the activity is saved. If left unused and you try to save the activity, a warning message displays informing you that unused activity-only audiences will be deleted. 
* You can view audience definition details on a pop-up card accessed from the audience picker without opening the audience. 
* You can [combine multiple audiences](/help/main/c-target/combining-multiple-audiences.md#concept_A7386F1EA4394BD2AB72399C225981E5) to create activity-only audiences.
* Activity-only audiences don't support exclude rules.

  You can use the following alternatives to use exclude rules:

  * [Create and use a library audience](/help/main/c-target/c-audiences/create-audience.md) instead of an activity-only audience.
  * [Combine multiple](/help/main/c-target/combining-multiple-audiences.md#concept_A7386F1EA4394BD2AB72399C225981E5) (up to 20) library audiences into an activity-only audience. When combining audiences, include and exclude rules in individual library audiences can be used even when the combined audience is saved as an activity-only audience.
