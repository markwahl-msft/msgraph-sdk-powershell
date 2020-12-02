---
external help file: Microsoft.Graph.Devices.CorporateManagement-help.xml
Module Name: Microsoft.Graph.Devices.CorporateManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devices.corporatemanagement/new-mgdeviceappmgtmobileappuserstatuses
schema: 2.0.0
---

# New-MgDeviceAppMgtMobileAppUserStatuses

## SYNOPSIS
Create new navigation property to userStatuses for deviceAppManagement

## SYNTAX

### CreateExpanded (Default)
```
New-MgDeviceAppMgtMobileAppUserStatuses -MobileAppId <String> [-AdditionalProperties <Hashtable>]
 [-App <IMicrosoftGraphMobileApp>] [-DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>]
 [-FailedDeviceCount <Int32>] [-Id <String>] [-InstalledDeviceCount <Int32>] [-NotInstalledDeviceCount <Int32>]
 [-UserName <String>] [-UserPrincipalName <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgDeviceAppMgtMobileAppUserStatuses -MobileAppId <String>
 -BodyParameter <IMicrosoftGraphUserAppInstallStatus> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgDeviceAppMgtMobileAppUserStatuses -InputObject <IDevicesCorporateManagementIdentity>
 [-AdditionalProperties <Hashtable>] [-App <IMicrosoftGraphMobileApp>]
 [-DeviceStatuses <IMicrosoftGraphMobileAppInstallStatus[]>] [-FailedDeviceCount <Int32>] [-Id <String>]
 [-InstalledDeviceCount <Int32>] [-NotInstalledDeviceCount <Int32>] [-UserName <String>]
 [-UserPrincipalName <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgDeviceAppMgtMobileAppUserStatuses -InputObject <IDevicesCorporateManagementIdentity>
 -BodyParameter <IMicrosoftGraphUserAppInstallStatus> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to userStatuses for deviceAppManagement

## EXAMPLES

### EXAMPLE 1
```
{{ Add code here }}
```

{{ Add output here }}

### EXAMPLE 2
```
{{ Add code here }}
```

{{ Add output here }}

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -App
An abstract class containing the base properties for Intune mobile apps.
To construct, see NOTES section for APP properties and create a hash table.

```yaml
Type: IMicrosoftGraphMobileApp
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
Contains properties for the installation status for a user.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphUserAppInstallStatus
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeviceStatuses
The install state of the app on devices.
To construct, see NOTES section for DEVICESTATUSES properties and create a hash table.

```yaml
Type: IMicrosoftGraphMobileAppInstallStatus[]
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FailedDeviceCount
Failed Device Count.

```yaml
Type: Int32
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IDevicesCorporateManagementIdentity
Parameter Sets: CreateViaIdentityExpanded, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InstalledDeviceCount
Installed Device Count.

```yaml
Type: Int32
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -MobileAppId
key: id of mobileApp

```yaml
Type: String
Parameter Sets: CreateExpanded, Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NotInstalledDeviceCount
Not installed device count.

```yaml
Type: Int32
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserName
User name.

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserPrincipalName
User Principal Name.

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IDevicesCorporateManagementIdentity
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserAppInstallStatus
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUserAppInstallStatus
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

APP \<IMicrosoftGraphMobileApp\>: An abstract class containing the base properties for Intune mobile apps.
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[Assignments \<IMicrosoftGraphMobileAppAssignment\[\]\>\]: The list of group assignments for this mobile app.
    \[Id \<String\>\]: Read-only.
    \[Intent \<String\>\]: installIntent
    \[Settings \<IMicrosoftGraphMobileAppAssignmentSettings\>\]: Abstract class to contain properties used to assign a mobile app to a group.
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Source \<String\>\]: deviceAndAppManagementAssignmentSource
    \[SourceId \<String\>\]: The identifier of the source of the assignment.
    \[Target \<IMicrosoftGraphDeviceAndAppManagementAssignmentTarget\>\]: Base type for assignment targets.
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[DeviceAndAppManagementAssignmentFilterId \<String\>\]: The Id of the filter for the target assignment.
      \[DeviceAndAppManagementAssignmentFilterType \<String\>\]: deviceAndAppManagementAssignmentFilterType
  \[Categories \<IMicrosoftGraphMobileAppCategory\[\]\>\]: The list of categories for this app.
    \[Id \<String\>\]: Read-only.
    \[DisplayName \<String\>\]: The name of the app category.
    \[LastModifiedDateTime \<DateTime?\>\]: The date and time the mobileAppCategory was last modified.
  \[CreatedDateTime \<DateTime?\>\]: The date and time the app was created.
  \[DependentAppCount \<Int32?\>\]: The total number of dependencies the child app has.
  \[Description \<String\>\]: The description of the app.
  \[Developer \<String\>\]: The developer of the app.
  \[DeviceStatuses \<IMicrosoftGraphMobileAppInstallStatus\[\]\>\]: The list of installation states for this mobile app.
    \[Id \<String\>\]: Read-only.
    \[App \<IMicrosoftGraphMobileApp\>\]: An abstract class containing the base properties for Intune mobile apps.
    \[DeviceId \<String\>\]: Device ID
    \[DeviceName \<String\>\]: Device name
    \[DisplayVersion \<String\>\]: Human readable version of the application
    \[ErrorCode \<Int32?\>\]: The error code for install or uninstall failures.
    \[InstallState \<String\>\]: resultantAppState
    \[InstallStateDetail \<String\>\]: resultantAppStateDetail
    \[LastSyncDateTime \<DateTime?\>\]: Last sync date time
    \[MobileAppInstallStatusValue \<String\>\]: resultantAppState
    \[OSDescription \<String\>\]: OS Description
    \[OSVersion \<String\>\]: OS Version
    \[UserName \<String\>\]: Device User Name
    \[UserPrincipalName \<String\>\]: User Principal Name
  \[DisplayName \<String\>\]: The admin provided or imported title of the app.
  \[InformationUrl \<String\>\]: The more information Url.
  \[InstallSummary \<IMicrosoftGraphMobileAppInstallSummary\>\]: Contains properties for the installation summary of a mobile app.
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Id \<String\>\]: Read-only.
    \[FailedDeviceCount \<Int32?\>\]: Number of Devices that have failed to install this app.
    \[FailedUserCount \<Int32?\>\]: Number of Users that have 1 or more device that failed to install this app.
    \[InstalledDeviceCount \<Int32?\>\]: Number of Devices that have successfully installed this app.
    \[InstalledUserCount \<Int32?\>\]: Number of Users whose devices have all succeeded to install this app.
    \[NotApplicableDeviceCount \<Int32?\>\]: Number of Devices that are not applicable for this app.
    \[NotApplicableUserCount \<Int32?\>\]: Number of Users whose devices were all not applicable for this app.
    \[NotInstalledDeviceCount \<Int32?\>\]: Number of Devices that does not have this app installed.
    \[NotInstalledUserCount \<Int32?\>\]: Number of Users that have 1 or more devices that did not install this app.
    \[PendingInstallDeviceCount \<Int32?\>\]: Number of Devices that have been notified to install this app.
    \[PendingInstallUserCount \<Int32?\>\]: Number of Users that have 1 or more device that have been notified to install this app and have 0 devices with failures.
  \[IsAssigned \<Boolean?\>\]: The value indicating whether the app is assigned to at least one group.
  \[IsFeatured \<Boolean?\>\]: The value indicating whether the app is marked as featured by the admin.
  \[LargeIcon \<IMicrosoftGraphMimeContent\>\]: Contains properties for a generic mime content.
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Type \<String\>\]: Indicates the content mime type.
    \[Value \<Byte\[\]\>\]: The byte array that contains the actual content.
  \[LastModifiedDateTime \<DateTime?\>\]: The date and time the app was last modified.
  \[Notes \<String\>\]: Notes for the app.
  \[Owner \<String\>\]: The owner of the app.
  \[PrivacyInformationUrl \<String\>\]: The privacy statement Url.
  \[Publisher \<String\>\]: The publisher of the app.
  \[PublishingState \<String\>\]: mobileAppPublishingState
  \[Relationships \<IMicrosoftGraphMobileAppRelationship\[\]\>\]: The set of direct relationships for this app.
    \[Id \<String\>\]: Read-only.
    \[TargetDisplayName \<String\>\]: The target mobile app's display name.
    \[TargetDisplayVersion \<String\>\]: The target mobile app's display version.
    \[TargetId \<String\>\]: The target mobile app's app id.
    \[TargetPublisher \<String\>\]: The target mobile app's publisher.
    \[TargetType \<String\>\]: mobileAppRelationshipType
  \[RoleScopeTagIds \<String\[\]\>\]: List of scope tag ids for this mobile app.
  \[SupersededAppCount \<Int32?\>\]: The total number of apps this app is directly or indirectly superseded by.
  \[SupersedingAppCount \<Int32?\>\]: The total number of apps this app directly or indirectly supersedes.
  \[UploadState \<Int32?\>\]: The upload state.
Possible values are: 0 - \`Not Ready\`, 1 - \`Ready\`, 2 - \`Processing\`.
  \[UserStatuses \<IMicrosoftGraphUserAppInstallStatus\[\]\>\]: The list of installation states for this mobile app.
    \[Id \<String\>\]: Read-only.
    \[App \<IMicrosoftGraphMobileApp\>\]: An abstract class containing the base properties for Intune mobile apps.
    \[DeviceStatuses \<IMicrosoftGraphMobileAppInstallStatus\[\]\>\]: The install state of the app on devices.
    \[FailedDeviceCount \<Int32?\>\]: Failed Device Count.
    \[InstalledDeviceCount \<Int32?\>\]: Installed Device Count.
    \[NotInstalledDeviceCount \<Int32?\>\]: Not installed device count.
    \[UserName \<String\>\]: User name.
    \[UserPrincipalName \<String\>\]: User Principal Name.

BODYPARAMETER \<IMicrosoftGraphUserAppInstallStatus\>: Contains properties for the installation status for a user.
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[App \<IMicrosoftGraphMobileApp\>\]: An abstract class containing the base properties for Intune mobile apps.
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Id \<String\>\]: Read-only.
    \[Assignments \<IMicrosoftGraphMobileAppAssignment\[\]\>\]: The list of group assignments for this mobile app.
      \[Id \<String\>\]: Read-only.
      \[Intent \<String\>\]: installIntent
      \[Settings \<IMicrosoftGraphMobileAppAssignmentSettings\>\]: Abstract class to contain properties used to assign a mobile app to a group.
        \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Source \<String\>\]: deviceAndAppManagementAssignmentSource
      \[SourceId \<String\>\]: The identifier of the source of the assignment.
      \[Target \<IMicrosoftGraphDeviceAndAppManagementAssignmentTarget\>\]: Base type for assignment targets.
        \[(Any) \<Object\>\]: This indicates any property can be added to this object.
        \[DeviceAndAppManagementAssignmentFilterId \<String\>\]: The Id of the filter for the target assignment.
        \[DeviceAndAppManagementAssignmentFilterType \<String\>\]: deviceAndAppManagementAssignmentFilterType
    \[Categories \<IMicrosoftGraphMobileAppCategory\[\]\>\]: The list of categories for this app.
      \[Id \<String\>\]: Read-only.
      \[DisplayName \<String\>\]: The name of the app category.
      \[LastModifiedDateTime \<DateTime?\>\]: The date and time the mobileAppCategory was last modified.
    \[CreatedDateTime \<DateTime?\>\]: The date and time the app was created.
    \[DependentAppCount \<Int32?\>\]: The total number of dependencies the child app has.
    \[Description \<String\>\]: The description of the app.
    \[Developer \<String\>\]: The developer of the app.
    \[DeviceStatuses \<IMicrosoftGraphMobileAppInstallStatus\[\]\>\]: The list of installation states for this mobile app.
      \[Id \<String\>\]: Read-only.
      \[App \<IMicrosoftGraphMobileApp\>\]: An abstract class containing the base properties for Intune mobile apps.
      \[DeviceId \<String\>\]: Device ID
      \[DeviceName \<String\>\]: Device name
      \[DisplayVersion \<String\>\]: Human readable version of the application
      \[ErrorCode \<Int32?\>\]: The error code for install or uninstall failures.
      \[InstallState \<String\>\]: resultantAppState
      \[InstallStateDetail \<String\>\]: resultantAppStateDetail
      \[LastSyncDateTime \<DateTime?\>\]: Last sync date time
      \[MobileAppInstallStatusValue \<String\>\]: resultantAppState
      \[OSDescription \<String\>\]: OS Description
      \[OSVersion \<String\>\]: OS Version
      \[UserName \<String\>\]: Device User Name
      \[UserPrincipalName \<String\>\]: User Principal Name
    \[DisplayName \<String\>\]: The admin provided or imported title of the app.
    \[InformationUrl \<String\>\]: The more information Url.
    \[InstallSummary \<IMicrosoftGraphMobileAppInstallSummary\>\]: Contains properties for the installation summary of a mobile app.
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Id \<String\>\]: Read-only.
      \[FailedDeviceCount \<Int32?\>\]: Number of Devices that have failed to install this app.
      \[FailedUserCount \<Int32?\>\]: Number of Users that have 1 or more device that failed to install this app.
      \[InstalledDeviceCount \<Int32?\>\]: Number of Devices that have successfully installed this app.
      \[InstalledUserCount \<Int32?\>\]: Number of Users whose devices have all succeeded to install this app.
      \[NotApplicableDeviceCount \<Int32?\>\]: Number of Devices that are not applicable for this app.
      \[NotApplicableUserCount \<Int32?\>\]: Number of Users whose devices were all not applicable for this app.
      \[NotInstalledDeviceCount \<Int32?\>\]: Number of Devices that does not have this app installed.
      \[NotInstalledUserCount \<Int32?\>\]: Number of Users that have 1 or more devices that did not install this app.
      \[PendingInstallDeviceCount \<Int32?\>\]: Number of Devices that have been notified to install this app.
      \[PendingInstallUserCount \<Int32?\>\]: Number of Users that have 1 or more device that have been notified to install this app and have 0 devices with failures.
    \[IsAssigned \<Boolean?\>\]: The value indicating whether the app is assigned to at least one group.
    \[IsFeatured \<Boolean?\>\]: The value indicating whether the app is marked as featured by the admin.
    \[LargeIcon \<IMicrosoftGraphMimeContent\>\]: Contains properties for a generic mime content.
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Type \<String\>\]: Indicates the content mime type.
      \[Value \<Byte\[\]\>\]: The byte array that contains the actual content.
    \[LastModifiedDateTime \<DateTime?\>\]: The date and time the app was last modified.
    \[Notes \<String\>\]: Notes for the app.
    \[Owner \<String\>\]: The owner of the app.
    \[PrivacyInformationUrl \<String\>\]: The privacy statement Url.
    \[Publisher \<String\>\]: The publisher of the app.
    \[PublishingState \<String\>\]: mobileAppPublishingState
    \[Relationships \<IMicrosoftGraphMobileAppRelationship\[\]\>\]: The set of direct relationships for this app.
      \[Id \<String\>\]: Read-only.
      \[TargetDisplayName \<String\>\]: The target mobile app's display name.
      \[TargetDisplayVersion \<String\>\]: The target mobile app's display version.
      \[TargetId \<String\>\]: The target mobile app's app id.
      \[TargetPublisher \<String\>\]: The target mobile app's publisher.
      \[TargetType \<String\>\]: mobileAppRelationshipType
    \[RoleScopeTagIds \<String\[\]\>\]: List of scope tag ids for this mobile app.
    \[SupersededAppCount \<Int32?\>\]: The total number of apps this app is directly or indirectly superseded by.
    \[SupersedingAppCount \<Int32?\>\]: The total number of apps this app directly or indirectly supersedes.
    \[UploadState \<Int32?\>\]: The upload state.
Possible values are: 0 - \`Not Ready\`, 1 - \`Ready\`, 2 - \`Processing\`.
    \[UserStatuses \<IMicrosoftGraphUserAppInstallStatus\[\]\>\]: The list of installation states for this mobile app.
  \[DeviceStatuses \<IMicrosoftGraphMobileAppInstallStatus\[\]\>\]: The install state of the app on devices.
  \[FailedDeviceCount \<Int32?\>\]: Failed Device Count.
  \[InstalledDeviceCount \<Int32?\>\]: Installed Device Count.
  \[NotInstalledDeviceCount \<Int32?\>\]: Not installed device count.
  \[UserName \<String\>\]: User name.
  \[UserPrincipalName \<String\>\]: User Principal Name.

DEVICESTATUSES \<IMicrosoftGraphMobileAppInstallStatus\[\]\>: The install state of the app on devices.
  \[Id \<String\>\]: Read-only.
  \[App \<IMicrosoftGraphMobileApp\>\]: An abstract class containing the base properties for Intune mobile apps.
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Id \<String\>\]: Read-only.
    \[Assignments \<IMicrosoftGraphMobileAppAssignment\[\]\>\]: The list of group assignments for this mobile app.
      \[Id \<String\>\]: Read-only.
      \[Intent \<String\>\]: installIntent
      \[Settings \<IMicrosoftGraphMobileAppAssignmentSettings\>\]: Abstract class to contain properties used to assign a mobile app to a group.
        \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Source \<String\>\]: deviceAndAppManagementAssignmentSource
      \[SourceId \<String\>\]: The identifier of the source of the assignment.
      \[Target \<IMicrosoftGraphDeviceAndAppManagementAssignmentTarget\>\]: Base type for assignment targets.
        \[(Any) \<Object\>\]: This indicates any property can be added to this object.
        \[DeviceAndAppManagementAssignmentFilterId \<String\>\]: The Id of the filter for the target assignment.
        \[DeviceAndAppManagementAssignmentFilterType \<String\>\]: deviceAndAppManagementAssignmentFilterType
    \[Categories \<IMicrosoftGraphMobileAppCategory\[\]\>\]: The list of categories for this app.
      \[Id \<String\>\]: Read-only.
      \[DisplayName \<String\>\]: The name of the app category.
      \[LastModifiedDateTime \<DateTime?\>\]: The date and time the mobileAppCategory was last modified.
    \[CreatedDateTime \<DateTime?\>\]: The date and time the app was created.
    \[DependentAppCount \<Int32?\>\]: The total number of dependencies the child app has.
    \[Description \<String\>\]: The description of the app.
    \[Developer \<String\>\]: The developer of the app.
    \[DeviceStatuses \<IMicrosoftGraphMobileAppInstallStatus\[\]\>\]: The list of installation states for this mobile app.
    \[DisplayName \<String\>\]: The admin provided or imported title of the app.
    \[InformationUrl \<String\>\]: The more information Url.
    \[InstallSummary \<IMicrosoftGraphMobileAppInstallSummary\>\]: Contains properties for the installation summary of a mobile app.
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Id \<String\>\]: Read-only.
      \[FailedDeviceCount \<Int32?\>\]: Number of Devices that have failed to install this app.
      \[FailedUserCount \<Int32?\>\]: Number of Users that have 1 or more device that failed to install this app.
      \[InstalledDeviceCount \<Int32?\>\]: Number of Devices that have successfully installed this app.
      \[InstalledUserCount \<Int32?\>\]: Number of Users whose devices have all succeeded to install this app.
      \[NotApplicableDeviceCount \<Int32?\>\]: Number of Devices that are not applicable for this app.
      \[NotApplicableUserCount \<Int32?\>\]: Number of Users whose devices were all not applicable for this app.
      \[NotInstalledDeviceCount \<Int32?\>\]: Number of Devices that does not have this app installed.
      \[NotInstalledUserCount \<Int32?\>\]: Number of Users that have 1 or more devices that did not install this app.
      \[PendingInstallDeviceCount \<Int32?\>\]: Number of Devices that have been notified to install this app.
      \[PendingInstallUserCount \<Int32?\>\]: Number of Users that have 1 or more device that have been notified to install this app and have 0 devices with failures.
    \[IsAssigned \<Boolean?\>\]: The value indicating whether the app is assigned to at least one group.
    \[IsFeatured \<Boolean?\>\]: The value indicating whether the app is marked as featured by the admin.
    \[LargeIcon \<IMicrosoftGraphMimeContent\>\]: Contains properties for a generic mime content.
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Type \<String\>\]: Indicates the content mime type.
      \[Value \<Byte\[\]\>\]: The byte array that contains the actual content.
    \[LastModifiedDateTime \<DateTime?\>\]: The date and time the app was last modified.
    \[Notes \<String\>\]: Notes for the app.
    \[Owner \<String\>\]: The owner of the app.
    \[PrivacyInformationUrl \<String\>\]: The privacy statement Url.
    \[Publisher \<String\>\]: The publisher of the app.
    \[PublishingState \<String\>\]: mobileAppPublishingState
    \[Relationships \<IMicrosoftGraphMobileAppRelationship\[\]\>\]: The set of direct relationships for this app.
      \[Id \<String\>\]: Read-only.
      \[TargetDisplayName \<String\>\]: The target mobile app's display name.
      \[TargetDisplayVersion \<String\>\]: The target mobile app's display version.
      \[TargetId \<String\>\]: The target mobile app's app id.
      \[TargetPublisher \<String\>\]: The target mobile app's publisher.
      \[TargetType \<String\>\]: mobileAppRelationshipType
    \[RoleScopeTagIds \<String\[\]\>\]: List of scope tag ids for this mobile app.
    \[SupersededAppCount \<Int32?\>\]: The total number of apps this app is directly or indirectly superseded by.
    \[SupersedingAppCount \<Int32?\>\]: The total number of apps this app directly or indirectly supersedes.
    \[UploadState \<Int32?\>\]: The upload state.
Possible values are: 0 - \`Not Ready\`, 1 - \`Ready\`, 2 - \`Processing\`.
    \[UserStatuses \<IMicrosoftGraphUserAppInstallStatus\[\]\>\]: The list of installation states for this mobile app.
      \[Id \<String\>\]: Read-only.
      \[App \<IMicrosoftGraphMobileApp\>\]: An abstract class containing the base properties for Intune mobile apps.
      \[DeviceStatuses \<IMicrosoftGraphMobileAppInstallStatus\[\]\>\]: The install state of the app on devices.
      \[FailedDeviceCount \<Int32?\>\]: Failed Device Count.
      \[InstalledDeviceCount \<Int32?\>\]: Installed Device Count.
      \[NotInstalledDeviceCount \<Int32?\>\]: Not installed device count.
      \[UserName \<String\>\]: User name.
      \[UserPrincipalName \<String\>\]: User Principal Name.
  \[DeviceId \<String\>\]: Device ID
  \[DeviceName \<String\>\]: Device name
  \[DisplayVersion \<String\>\]: Human readable version of the application
  \[ErrorCode \<Int32?\>\]: The error code for install or uninstall failures.
  \[InstallState \<String\>\]: resultantAppState
  \[InstallStateDetail \<String\>\]: resultantAppStateDetail
  \[LastSyncDateTime \<DateTime?\>\]: Last sync date time
  \[MobileAppInstallStatusValue \<String\>\]: resultantAppState
  \[OSDescription \<String\>\]: OS Description
  \[OSVersion \<String\>\]: OS Version
  \[UserName \<String\>\]: Device User Name
  \[UserPrincipalName \<String\>\]: User Principal Name

INPUTOBJECT \<IDevicesCorporateManagementIdentity\>: Identity Parameter
  \[AndroidManagedAppProtectionId \<String\>\]: key: id of androidManagedAppProtection
  \[AppLogCollectionRequestId \<String\>\]: key: id of appLogCollectionRequest
  \[BundleId \<String\>\]: 
  \[Count \<Int64?\>\]: 
  \[DefaultManagedAppProtectionId \<String\>\]: key: id of defaultManagedAppProtection
  \[DeviceAppManagementTaskId \<String\>\]: key: id of deviceAppManagementTask
  \[DeviceCompliancePolicyStateId \<String\>\]: key: id of deviceCompliancePolicyState
  \[DeviceConfigurationStateId \<String\>\]: key: id of deviceConfigurationState
  \[DeviceEnrollmentConfigurationId \<String\>\]: key: id of deviceEnrollmentConfiguration
  \[DeviceId \<String\>\]: 
  \[DeviceInstallStateId \<String\>\]: key: id of deviceInstallState
  \[DeviceLogCollectionResponseId \<String\>\]: key: id of deviceLogCollectionResponse
  \[DeviceManagementTroubleshootingEventId \<String\>\]: key: id of deviceManagementTroubleshootingEvent
  \[EnrollmentConfigurationAssignmentId \<String\>\]: key: id of enrollmentConfigurationAssignment
  \[EnterpriseCodeSigningCertificateId \<String\>\]: key: id of enterpriseCodeSigningCertificate
  \[IosLobAppProvisioningConfigurationAssignmentId \<String\>\]: key: id of iosLobAppProvisioningConfigurationAssignment
  \[IosLobAppProvisioningConfigurationId \<String\>\]: key: id of iosLobAppProvisioningConfiguration
  \[IosManagedAppProtectionId \<String\>\]: key: id of iosManagedAppProtection
  \[ManagedAppOperationId \<String\>\]: key: id of managedAppOperation
  \[ManagedAppPolicyId \<String\>\]: key: id of managedAppPolicy
  \[ManagedAppRegistrationId \<String\>\]: key: id of managedAppRegistration
  \[ManagedAppStatusId \<String\>\]: key: id of managedAppStatus
  \[ManagedDeviceId \<String\>\]: key: id of managedDevice
  \[ManagedDeviceMobileAppConfigurationAssignmentId \<String\>\]: key: id of managedDeviceMobileAppConfigurationAssignment
  \[ManagedDeviceMobileAppConfigurationDeviceStatusId \<String\>\]: key: id of managedDeviceMobileAppConfigurationDeviceStatus
  \[ManagedDeviceMobileAppConfigurationId \<String\>\]: key: id of managedDeviceMobileAppConfiguration
  \[ManagedDeviceMobileAppConfigurationStateId \<String\>\]: key: id of managedDeviceMobileAppConfigurationState
  \[ManagedDeviceMobileAppConfigurationUserStatusId \<String\>\]: key: id of managedDeviceMobileAppConfigurationUserStatus
  \[ManagedEBookAssignmentId \<String\>\]: key: id of managedEBookAssignment
  \[ManagedEBookCategoryId \<String\>\]: key: id of managedEBookCategory
  \[ManagedEBookId \<String\>\]: key: id of managedEBook
  \[ManagedMobileAppId \<String\>\]: key: id of managedMobileApp
  \[MdmWindowsInformationProtectionPolicyId \<String\>\]: key: id of mdmWindowsInformationProtectionPolicy
  \[MobileAppAssignmentId \<String\>\]: key: id of mobileAppAssignment
  \[MobileAppCategoryId \<String\>\]: key: id of mobileAppCategory
  \[MobileAppId \<String\>\]: key: id of mobileApp
  \[MobileAppInstallStatusId \<String\>\]: key: id of mobileAppInstallStatus
  \[MobileAppIntentAndStateId \<String\>\]: key: id of mobileAppIntentAndState
  \[MobileAppProvisioningConfigGroupAssignmentId \<String\>\]: key: id of mobileAppProvisioningConfigGroupAssignment
  \[MobileAppRelationshipId \<String\>\]: key: id of mobileAppRelationship
  \[MobileAppTroubleshootingEventId \<String\>\]: key: id of mobileAppTroubleshootingEvent
  \[OfficeClientConfigurationAssignmentId \<String\>\]: key: id of officeClientConfigurationAssignment
  \[OfficeClientConfigurationId \<String\>\]: key: id of officeClientConfiguration
  \[PolicySetAssignmentId \<String\>\]: key: id of policySetAssignment
  \[PolicySetId \<String\>\]: key: id of policySet
  \[PolicySetItemId \<String\>\]: key: id of policySetItem
  \[SecurityBaselineSettingStateId \<String\>\]: key: id of securityBaselineSettingState
  \[SecurityBaselineStateId \<String\>\]: key: id of securityBaselineState
  \[SideLoadingKeyId \<String\>\]: key: id of sideLoadingKey
  \[Status \<String\>\]: 
  \[TargetedManagedAppConfigurationId \<String\>\]: key: id of targetedManagedAppConfiguration
  \[TargetedManagedAppPolicyAssignmentId \<String\>\]: key: id of targetedManagedAppPolicyAssignment
  \[UserAppInstallStatusId \<String\>\]: key: id of userAppInstallStatus
  \[UserId \<String\>\]: key: id of user
  \[UserId1 \<String\>\]: key: id of user
  \[UserInstallStateSummaryId \<String\>\]: key: id of userInstallStateSummary
  \[UserPrincipalName \<String\>\]: 
  \[VppTokenId \<String\>\]: key: id of vppToken
  \[WindowsDefenderApplicationControlSupplementalPolicyAssignmentId \<String\>\]: key: id of windowsDefenderApplicationControlSupplementalPolicyAssignment
  \[WindowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId \<String\>\]: key: id of windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus
  \[WindowsDefenderApplicationControlSupplementalPolicyId \<String\>\]: key: id of windowsDefenderApplicationControlSupplementalPolicy
  \[WindowsDeviceMalwareStateId \<String\>\]: key: id of windowsDeviceMalwareState
  \[WindowsInformationProtectionDeviceRegistrationId \<String\>\]: key: id of windowsInformationProtectionDeviceRegistration
  \[WindowsInformationProtectionPolicyId \<String\>\]: key: id of windowsInformationProtectionPolicy
  \[WindowsInformationProtectionWipeActionId \<String\>\]: key: id of windowsInformationProtectionWipeAction

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devices.corporatemanagement/new-mgdeviceappmgtmobileappuserstatuses](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devices.corporatemanagement/new-mgdeviceappmgtmobileappuserstatuses)
