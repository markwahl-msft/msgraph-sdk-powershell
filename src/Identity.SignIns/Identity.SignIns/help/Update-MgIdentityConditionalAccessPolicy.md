---
external help file: Microsoft.Graph.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Identity.SignIns
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgidentityconditionalaccesspolicy
schema: 2.0.0
---

# Update-MgIdentityConditionalAccessPolicy

## SYNOPSIS
Update the navigation property policies in identity

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgIdentityConditionalAccessPolicy -ConditionalAccessPolicyId <String>
 [-AdditionalProperties <Hashtable>] [-Conditions <IMicrosoftGraphConditionalAccessConditionSet1>]
 [-CreatedDateTime <DateTime>] [-Description <String>] [-DisplayName <String>]
 [-GrantControls <IMicrosoftGraphConditionalAccessGrantControls1>] [-Id <String>]
 [-ModifiedDateTime <DateTime>] [-SessionControls <IMicrosoftGraphConditionalAccessSessionControls>]
 [-State <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgIdentityConditionalAccessPolicy -ConditionalAccessPolicyId <String>
 -BodyParameter <IMicrosoftGraphConditionalAccessPolicy1> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgIdentityConditionalAccessPolicy -InputObject <IIdentitySignInsIdentity>
 [-AdditionalProperties <Hashtable>] [-Conditions <IMicrosoftGraphConditionalAccessConditionSet1>]
 [-CreatedDateTime <DateTime>] [-Description <String>] [-DisplayName <String>]
 [-GrantControls <IMicrosoftGraphConditionalAccessGrantControls1>] [-Id <String>]
 [-ModifiedDateTime <DateTime>] [-SessionControls <IMicrosoftGraphConditionalAccessSessionControls>]
 [-State <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgIdentityConditionalAccessPolicy -InputObject <IIdentitySignInsIdentity>
 -BodyParameter <IMicrosoftGraphConditionalAccessPolicy1> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property policies in identity

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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
conditionalAccessPolicy
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphConditionalAccessPolicy1
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ConditionalAccessPolicyId
key: id of conditionalAccessPolicy

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Conditions
conditionalAccessConditionSet
To construct, see NOTES section for CONDITIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphConditionalAccessConditionSet1
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedDateTime
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
Readonly.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
Specifies a display name for the conditionalAccessPolicy object.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GrantControls
conditionalAccessGrantControls
To construct, see NOTES section for GRANTCONTROLS properties and create a hash table.

```yaml
Type: IMicrosoftGraphConditionalAccessGrantControls1
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Type: IIdentitySignInsIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ModifiedDateTime
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
Readonly.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -SessionControls
conditionalAccessSessionControls
To construct, see NOTES section for SESSIONCONTROLS properties and create a hash table.

```yaml
Type: IMicrosoftGraphConditionalAccessSessionControls
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State
conditionalAccessPolicyState

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IIdentitySignInsIdentity
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphConditionalAccessPolicy1
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER \<IMicrosoftGraphConditionalAccessPolicy\>: conditionalAccessPolicy
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[Conditions \<IMicrosoftGraphConditionalAccessConditionSet\>\]: conditionalAccessConditionSet
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Applications \<IMicrosoftGraphConditionalAccessApplications\>\]: conditionalAccessApplications
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[ExcludeApplications \<String\[\]\>\]: The list of application IDs explicitly excluded from the policy.
      \[IncludeApplications \<String\[\]\>\]: The list of application IDs the policy applies to, unless explicitly excluded (in excludeApplications).
Can also be set to All.
      \[IncludeUserActions \<String\[\]\>\]: User actions to include.
For example, urn:user:registersecurityinfo
    \[ClientAppTypes \<String\[\]\>\]: Client application types included in the policy.
Possible values are: all, browser, mobileAppsAndDesktopClients, exchangeActiveSync, easSupported, other.
    \[Locations \<IMicrosoftGraphConditionalAccessLocations\>\]: conditionalAccessLocations
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[ExcludeLocations \<String\[\]\>\]: Location IDs excluded from scope of policy.
      \[IncludeLocations \<String\[\]\>\]: Location IDs in scope of policy unless explicitly excluded, All, or AllTrusted.
    \[Platforms \<IMicrosoftGraphConditionalAccessPlatforms\>\]: conditionalAccessPlatforms
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[ExcludePlatforms \<String\[\]\>\]: Possible values are: android, iOS, windows, windowsPhone, macOS, unknownFutureValue.
      \[IncludePlatforms \<String\[\]\>\]: Possible values are: android, iOS, windows, windowsPhone, macOS, all, unknownFutureValue.
    \[SignInRiskLevels \<String\[\]\>\]: Risk levels included in the policy.
Possible values are: low, medium, high, none.
    \[Users \<IMicrosoftGraphConditionalAccessUsers\>\]: conditionalAccessUsers
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[ExcludeGroups \<String\[\]\>\]: Group IDs excluded from scope of policy.
      \[ExcludeRoles \<String\[\]\>\]: Role IDs excluded from scope of policy.
      \[ExcludeUsers \<String\[\]\>\]: User IDs excluded from scope of policy and/or GuestsOrExternalUsers.
      \[IncludeGroups \<String\[\]\>\]: Group IDs in scope of policy unless explicitly excluded, or All.
      \[IncludeRoles \<String\[\]\>\]: Role IDs in scope of policy unless explicitly excluded, or All.
      \[IncludeUsers \<String\[\]\>\]: User IDs in scope of policy unless explicitly excluded, or None or All or GuestsOrExternalUsers.
  \[CreatedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
Readonly.
  \[Description \<String\>\]: 
  \[DisplayName \<String\>\]: Specifies a display name for the conditionalAccessPolicy object.
  \[GrantControls \<IMicrosoftGraphConditionalAccessGrantControls\>\]: conditionalAccessGrantControls
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[BuiltInControls \<String\[\]\>\]: List of values of built-in controls required by the policy.
Possible values: Block, Mfa, CompliantDevice, DomainJoinedDevice, ApprovedApplication, CompliantApplication
    \[CustomAuthenticationFactors \<String\[\]\>\]: List of custom controls IDs required by the policy.
For more information, see Custom controls.
    \[Operator \<String\>\]: Defines the relationship of the grant controls.
Possible values: AND, OR.
    \[TermsOfUse \<String\[\]\>\]: List of terms of use IDs required by the policy.
  \[ModifiedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
Readonly.
  \[SessionControls \<IMicrosoftGraphConditionalAccessSessionControls\>\]: conditionalAccessSessionControls
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[ApplicationEnforcedRestrictions \<IMicrosoftGraphApplicationEnforcedRestrictionsSessionControl\>\]: applicationEnforcedRestrictionsSessionControl
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[IsEnabled \<Boolean?\>\]: Specifies whether the session control is enabled.
    \[CloudAppSecurity \<IMicrosoftGraphCloudAppSecuritySessionControl\>\]: cloudAppSecuritySessionControl
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[IsEnabled \<Boolean?\>\]: Specifies whether the session control is enabled.
      \[CloudAppSecurityType \<String\>\]: cloudAppSecuritySessionControlType
    \[PersistentBrowser \<IMicrosoftGraphPersistentBrowserSessionControl\>\]: persistentBrowserSessionControl
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[IsEnabled \<Boolean?\>\]: Specifies whether the session control is enabled.
      \[Mode \<String\>\]: persistentBrowserSessionMode
    \[SignInFrequency \<IMicrosoftGraphSignInFrequencySessionControl\>\]: signInFrequencySessionControl
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[IsEnabled \<Boolean?\>\]: Specifies whether the session control is enabled.
      \[Type \<String\>\]: signinFrequencyType
      \[Value \<Int32?\>\]: The number of days or hours.
  \[State \<String\>\]: conditionalAccessPolicyState

CONDITIONS \<IMicrosoftGraphConditionalAccessConditionSet\>: conditionalAccessConditionSet
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Applications \<IMicrosoftGraphConditionalAccessApplications\>\]: conditionalAccessApplications
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[ExcludeApplications \<String\[\]\>\]: The list of application IDs explicitly excluded from the policy.
    \[IncludeApplications \<String\[\]\>\]: The list of application IDs the policy applies to, unless explicitly excluded (in excludeApplications).
Can also be set to All.
    \[IncludeUserActions \<String\[\]\>\]: User actions to include.
For example, urn:user:registersecurityinfo
  \[ClientAppTypes \<String\[\]\>\]: Client application types included in the policy.
Possible values are: all, browser, mobileAppsAndDesktopClients, exchangeActiveSync, easSupported, other.
  \[Locations \<IMicrosoftGraphConditionalAccessLocations\>\]: conditionalAccessLocations
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[ExcludeLocations \<String\[\]\>\]: Location IDs excluded from scope of policy.
    \[IncludeLocations \<String\[\]\>\]: Location IDs in scope of policy unless explicitly excluded, All, or AllTrusted.
  \[Platforms \<IMicrosoftGraphConditionalAccessPlatforms\>\]: conditionalAccessPlatforms
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[ExcludePlatforms \<String\[\]\>\]: Possible values are: android, iOS, windows, windowsPhone, macOS, unknownFutureValue.
    \[IncludePlatforms \<String\[\]\>\]: Possible values are: android, iOS, windows, windowsPhone, macOS, all, unknownFutureValue.
  \[SignInRiskLevels \<String\[\]\>\]: Risk levels included in the policy.
Possible values are: low, medium, high, none.
  \[Users \<IMicrosoftGraphConditionalAccessUsers\>\]: conditionalAccessUsers
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[ExcludeGroups \<String\[\]\>\]: Group IDs excluded from scope of policy.
    \[ExcludeRoles \<String\[\]\>\]: Role IDs excluded from scope of policy.
    \[ExcludeUsers \<String\[\]\>\]: User IDs excluded from scope of policy and/or GuestsOrExternalUsers.
    \[IncludeGroups \<String\[\]\>\]: Group IDs in scope of policy unless explicitly excluded, or All.
    \[IncludeRoles \<String\[\]\>\]: Role IDs in scope of policy unless explicitly excluded, or All.
    \[IncludeUsers \<String\[\]\>\]: User IDs in scope of policy unless explicitly excluded, or None or All or GuestsOrExternalUsers.

GRANTCONTROLS \<IMicrosoftGraphConditionalAccessGrantControls\>: conditionalAccessGrantControls
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[BuiltInControls \<String\[\]\>\]: List of values of built-in controls required by the policy.
Possible values: Block, Mfa, CompliantDevice, DomainJoinedDevice, ApprovedApplication, CompliantApplication
  \[CustomAuthenticationFactors \<String\[\]\>\]: List of custom controls IDs required by the policy.
For more information, see Custom controls.
  \[Operator \<String\>\]: Defines the relationship of the grant controls.
Possible values: AND, OR.
  \[TermsOfUse \<String\[\]\>\]: List of terms of use IDs required by the policy.

INPUTOBJECT \<IIdentitySignInsIdentity\>: Identity Parameter
  \[ActivityBasedTimeoutPolicyId \<String\>\]: key: id of activityBasedTimeoutPolicy
  \[AuthenticationContextClassReferenceId \<String\>\]: key: id of authenticationContextClassReference
  \[AuthenticationMethodId \<String\>\]: key: id of authenticationMethod
  \[AuthorizationPolicyId \<String\>\]: key: id of authorizationPolicy
  \[ClaimsMappingPolicyId \<String\>\]: key: id of claimsMappingPolicy
  \[ConditionalAccessPolicyId \<String\>\]: key: id of conditionalAccessPolicy
  \[DataLossPreventionPolicyId \<String\>\]: key: id of dataLossPreventionPolicy
  \[DataPolicyOperationId \<String\>\]: key: id of dataPolicyOperation
  \[EmailAuthenticationMethodId \<String\>\]: key: id of emailAuthenticationMethod
  \[Fido2AuthenticationMethodId \<String\>\]: key: id of fido2AuthenticationMethod
  \[HomeRealmDiscoveryPolicyId \<String\>\]: key: id of homeRealmDiscoveryPolicy
  \[IdentityProviderId \<String\>\]: key: id of identityProvider
  \[IdentityUserFlowId \<String\>\]: key: id of identityUserFlow
  \[InformationProtectionLabelId \<String\>\]: key: id of informationProtectionLabel
  \[LongRunningOperationId \<String\>\]: key: id of longRunningOperation
  \[NamedLocationId \<String\>\]: key: id of namedLocation
  \[OAuth2PermissionGrantId \<String\>\]: key: id of oAuth2PermissionGrant
  \[OrganizationId \<String\>\]: key: id of organization
  \[PasswordAuthenticationMethodId \<String\>\]: key: id of passwordAuthenticationMethod
  \[PasswordlessMicrosoftAuthenticatorAuthenticationMethodId \<String\>\]: key: id of passwordlessMicrosoftAuthenticatorAuthenticationMethod
  \[PermissionGrantConditionSetId \<String\>\]: key: id of permissionGrantConditionSet
  \[PermissionGrantPolicyId \<String\>\]: key: id of permissionGrantPolicy
  \[PhoneAuthenticationMethodId \<String\>\]: key: id of phoneAuthenticationMethod
  \[PrivateLinkResourcePolicyId \<String\>\]: key: id of privateLinkResourcePolicy
  \[RiskDetectionId \<String\>\]: key: id of riskDetection
  \[RiskyUserHistoryItemId \<String\>\]: key: id of riskyUserHistoryItem
  \[RiskyUserId \<String\>\]: key: id of riskyUser
  \[SensitivityLabelId \<String\>\]: key: id of sensitivityLabel
  \[SensitivityLabelId1 \<String\>\]: key: id of sensitivityLabel
  \[ThreatAssessmentRequestId \<String\>\]: key: id of threatAssessmentRequest
  \[ThreatAssessmentResultId \<String\>\]: key: id of threatAssessmentResult
  \[TokenIssuancePolicyId \<String\>\]: key: id of tokenIssuancePolicy
  \[TokenLifetimePolicyId \<String\>\]: key: id of tokenLifetimePolicy
  \[TrustFrameworkKeySetId \<String\>\]: key: id of trustFrameworkKeySet
  \[TrustFrameworkPolicyId \<String\>\]: key: id of trustFrameworkPolicy
  \[UserId \<String\>\]: key: id of user

SESSIONCONTROLS \<IMicrosoftGraphConditionalAccessSessionControls\>: conditionalAccessSessionControls
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[ApplicationEnforcedRestrictions \<IMicrosoftGraphApplicationEnforcedRestrictionsSessionControl\>\]: applicationEnforcedRestrictionsSessionControl
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[IsEnabled \<Boolean?\>\]: Specifies whether the session control is enabled.
  \[CloudAppSecurity \<IMicrosoftGraphCloudAppSecuritySessionControl\>\]: cloudAppSecuritySessionControl
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[IsEnabled \<Boolean?\>\]: Specifies whether the session control is enabled.
    \[CloudAppSecurityType \<String\>\]: cloudAppSecuritySessionControlType
  \[PersistentBrowser \<IMicrosoftGraphPersistentBrowserSessionControl\>\]: persistentBrowserSessionControl
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[IsEnabled \<Boolean?\>\]: Specifies whether the session control is enabled.
    \[Mode \<String\>\]: persistentBrowserSessionMode
  \[SignInFrequency \<IMicrosoftGraphSignInFrequencySessionControl\>\]: signInFrequencySessionControl
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[IsEnabled \<Boolean?\>\]: Specifies whether the session control is enabled.
    \[Type \<String\>\]: signinFrequencyType
    \[Value \<Int32?\>\]: The number of days or hours.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgidentityconditionalaccesspolicy](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgidentityconditionalaccesspolicy)

## RELATED LINKS