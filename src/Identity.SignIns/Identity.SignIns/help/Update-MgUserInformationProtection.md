---
external help file: Microsoft.Graph.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Identity.SignIns
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mguserinformationprotection
schema: 2.0.0
---

# Update-MgUserInformationProtection

## SYNOPSIS
Update the navigation property informationProtection in users

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgUserInformationProtection -UserId <String> [-AdditionalProperties <Hashtable>]
 [-Bitlocker <IMicrosoftGraphBitlocker>]
 [-DataLossPreventionPolicies <IMicrosoftGraphDataLossPreventionPolicy[]>] [-Id <String>]
 [-Policy <IMicrosoftGraphInformationProtectionPolicy>]
 [-SensitivityLabels <IMicrosoftGraphSensitivityLabel[]>]
 [-SensitivityPolicySettings <IMicrosoftGraphSensitivityPolicySettings>]
 [-ThreatAssessmentRequests <IMicrosoftGraphThreatAssessmentRequest[]>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Update
```
Update-MgUserInformationProtection -UserId <String> -BodyParameter <IMicrosoftGraphInformationProtection1>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgUserInformationProtection -InputObject <IIdentitySignInsIdentity> [-AdditionalProperties <Hashtable>]
 [-Bitlocker <IMicrosoftGraphBitlocker>]
 [-DataLossPreventionPolicies <IMicrosoftGraphDataLossPreventionPolicy[]>] [-Id <String>]
 [-Policy <IMicrosoftGraphInformationProtectionPolicy>]
 [-SensitivityLabels <IMicrosoftGraphSensitivityLabel[]>]
 [-SensitivityPolicySettings <IMicrosoftGraphSensitivityPolicySettings>]
 [-ThreatAssessmentRequests <IMicrosoftGraphThreatAssessmentRequest[]>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgUserInformationProtection -InputObject <IIdentitySignInsIdentity>
 -BodyParameter <IMicrosoftGraphInformationProtection1> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property informationProtection in users

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

### -Bitlocker
bitlocker
To construct, see NOTES section for BITLOCKER properties and create a hash table.

```yaml
Type: IMicrosoftGraphBitlocker
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
informationProtection
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphInformationProtection1
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DataLossPreventionPolicies
.
To construct, see NOTES section for DATALOSSPREVENTIONPOLICIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphDataLossPreventionPolicy[]
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

### -Policy
informationProtectionPolicy
To construct, see NOTES section for POLICY properties and create a hash table.

```yaml
Type: IMicrosoftGraphInformationProtectionPolicy
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SensitivityLabels
.
To construct, see NOTES section for SENSITIVITYLABELS properties and create a hash table.

```yaml
Type: IMicrosoftGraphSensitivityLabel[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SensitivityPolicySettings
sensitivityPolicySettings
To construct, see NOTES section for SENSITIVITYPOLICYSETTINGS properties and create a hash table.

```yaml
Type: IMicrosoftGraphSensitivityPolicySettings
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ThreatAssessmentRequests
.
To construct, see NOTES section for THREATASSESSMENTREQUESTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphThreatAssessmentRequest[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
key: id of user

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
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphInformationProtection1
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BITLOCKER \<IMicrosoftGraphBitlocker\>: bitlocker
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[RecoveryKeys \<IMicrosoftGraphBitlockerRecoveryKey\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
    \[CreatedDateTime \<DateTime?\>\]: 
    \[DeviceId \<String\>\]: 
    \[Key \<String\>\]: 
    \[VolumeType \<String\>\]: volumeType

BODYPARAMETER \<IMicrosoftGraphInformationProtection1\>: informationProtection
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[Bitlocker \<IMicrosoftGraphBitlocker\>\]: bitlocker
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Id \<String\>\]: Read-only.
    \[RecoveryKeys \<IMicrosoftGraphBitlockerRecoveryKey\[\]\>\]: 
      \[Id \<String\>\]: Read-only.
      \[CreatedDateTime \<DateTime?\>\]: 
      \[DeviceId \<String\>\]: 
      \[Key \<String\>\]: 
      \[VolumeType \<String\>\]: volumeType
  \[DataLossPreventionPolicies \<IMicrosoftGraphDataLossPreventionPolicy\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
    \[Name \<String\>\]: 
  \[Policy \<IMicrosoftGraphInformationProtectionPolicy\>\]: informationProtectionPolicy
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Id \<String\>\]: Read-only.
    \[Labels \<IMicrosoftGraphInformationProtectionLabel\[\]\>\]: 
      \[Id \<String\>\]: Read-only.
      \[Color \<String\>\]: 
      \[Description \<String\>\]: 
      \[IsActive \<Boolean?\>\]: 
      \[Name \<String\>\]: 
      \[Parent \<IMicrosoftGraphParentLabelDetails\>\]: parentLabelDetails
        \[(Any) \<Object\>\]: This indicates any property can be added to this object.
        \[Color \<String\>\]: 
        \[Description \<String\>\]: 
        \[Id \<String\>\]: 
        \[IsActive \<Boolean?\>\]: 
        \[Name \<String\>\]: 
        \[Parent \<IMicrosoftGraphParentLabelDetails\>\]: parentLabelDetails
        \[Sensitivity \<Int32?\>\]: 
        \[Tooltip \<String\>\]: 
      \[Sensitivity \<Int32?\>\]: 
      \[Tooltip \<String\>\]: 
  \[SensitivityLabels \<IMicrosoftGraphSensitivityLabel\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
    \[ApplicableTo \<String\>\]: sensitivityLabelTarget
    \[ApplicationMode \<String\>\]: applicationMode
    \[AssignedPolicies \<IMicrosoftGraphLabelPolicy\[\]\>\]: 
      \[Id \<String\>\]: 
      \[Name \<String\>\]: 
    \[AutoLabeling \<IMicrosoftGraphAutoLabeling\>\]: autoLabeling
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Message \<String\>\]: 
      \[SensitiveTypeIds \<String\[\]\>\]: 
    \[Description \<String\>\]: 
    \[DisplayName \<String\>\]: 
    \[IsDefault \<Boolean?\>\]: 
    \[IsEndpointProtectionEnabled \<Boolean?\>\]: 
    \[LabelActions \<IMicrosoftGraphLabelActionBase\[\]\>\]: 
      \[Name \<String\>\]: 
    \[Name \<String\>\]: 
    \[Priority \<Int32?\>\]: 
    \[Sublabels \<IMicrosoftGraphSensitivityLabel\[\]\>\]: 
    \[ToolTip \<String\>\]: 
  \[SensitivityPolicySettings \<IMicrosoftGraphSensitivityPolicySettings\>\]: sensitivityPolicySettings
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Id \<String\>\]: Read-only.
    \[ApplicableTo \<String\>\]: sensitivityLabelTarget
    \[DowngradeSensitivityRequiresJustification \<Boolean?\>\]: 
    \[HelpWebUrl \<String\>\]: 
    \[IsMandatory \<Boolean?\>\]: 
  \[ThreatAssessmentRequests \<IMicrosoftGraphThreatAssessmentRequest\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
    \[Category \<String\>\]: threatCategory
    \[ContentType \<String\>\]: threatAssessmentContentType
    \[CreatedBy \<IMicrosoftGraphIdentitySet\>\]: identitySet
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Application \<IMicrosoftGraphIdentity\>\]: identity
        \[(Any) \<Object\>\]: This indicates any property can be added to this object.
        \[DisplayName \<String\>\]: The identity's display name.
Note that this may not always be available or up to date.
For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
        \[Id \<String\>\]: Unique identifier for the identity.
      \[Device \<IMicrosoftGraphIdentity\>\]: identity
      \[User \<IMicrosoftGraphIdentity\>\]: identity
    \[CreatedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
    \[ExpectedAssessment \<String\>\]: threatExpectedAssessment
    \[RequestSource \<String\>\]: threatAssessmentRequestSource
    \[Results \<IMicrosoftGraphThreatAssessmentResult\[\]\>\]: A collection of threat assessment results.
Read-only.
By default, a GET /threatAssessmentRequests/{id} does not return this property unless you apply $expand on it.
      \[Id \<String\>\]: Read-only.
      \[CreatedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
      \[Message \<String\>\]: The result message for each threat assessment.
      \[ResultType \<String\>\]: threatAssessmentResultType
    \[Status \<String\>\]: threatAssessmentStatus

DATALOSSPREVENTIONPOLICIES \<IMicrosoftGraphDataLossPreventionPolicy\[\]\>: .
  \[Id \<String\>\]: Read-only.
  \[Name \<String\>\]: 

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

POLICY \<IMicrosoftGraphInformationProtectionPolicy\>: informationProtectionPolicy
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[Labels \<IMicrosoftGraphInformationProtectionLabel\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
    \[Color \<String\>\]: 
    \[Description \<String\>\]: 
    \[IsActive \<Boolean?\>\]: 
    \[Name \<String\>\]: 
    \[Parent \<IMicrosoftGraphParentLabelDetails\>\]: parentLabelDetails
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Color \<String\>\]: 
      \[Description \<String\>\]: 
      \[Id \<String\>\]: 
      \[IsActive \<Boolean?\>\]: 
      \[Name \<String\>\]: 
      \[Parent \<IMicrosoftGraphParentLabelDetails\>\]: parentLabelDetails
      \[Sensitivity \<Int32?\>\]: 
      \[Tooltip \<String\>\]: 
    \[Sensitivity \<Int32?\>\]: 
    \[Tooltip \<String\>\]: 

SENSITIVITYLABELS \<IMicrosoftGraphSensitivityLabel\[\]\>: .
  \[Id \<String\>\]: Read-only.
  \[ApplicableTo \<String\>\]: sensitivityLabelTarget
  \[ApplicationMode \<String\>\]: applicationMode
  \[AssignedPolicies \<IMicrosoftGraphLabelPolicy\[\]\>\]: 
    \[Id \<String\>\]: 
    \[Name \<String\>\]: 
  \[AutoLabeling \<IMicrosoftGraphAutoLabeling\>\]: autoLabeling
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Message \<String\>\]: 
    \[SensitiveTypeIds \<String\[\]\>\]: 
  \[Description \<String\>\]: 
  \[DisplayName \<String\>\]: 
  \[IsDefault \<Boolean?\>\]: 
  \[IsEndpointProtectionEnabled \<Boolean?\>\]: 
  \[LabelActions \<IMicrosoftGraphLabelActionBase\[\]\>\]: 
    \[Name \<String\>\]: 
  \[Name \<String\>\]: 
  \[Priority \<Int32?\>\]: 
  \[Sublabels \<IMicrosoftGraphSensitivityLabel\[\]\>\]: 
  \[ToolTip \<String\>\]: 

SENSITIVITYPOLICYSETTINGS \<IMicrosoftGraphSensitivityPolicySettings\>: sensitivityPolicySettings
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[ApplicableTo \<String\>\]: sensitivityLabelTarget
  \[DowngradeSensitivityRequiresJustification \<Boolean?\>\]: 
  \[HelpWebUrl \<String\>\]: 
  \[IsMandatory \<Boolean?\>\]: 

THREATASSESSMENTREQUESTS \<IMicrosoftGraphThreatAssessmentRequest\[\]\>: .
  \[Id \<String\>\]: Read-only.
  \[Category \<String\>\]: threatCategory
  \[ContentType \<String\>\]: threatAssessmentContentType
  \[CreatedBy \<IMicrosoftGraphIdentitySet\>\]: identitySet
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Application \<IMicrosoftGraphIdentity\>\]: identity
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[DisplayName \<String\>\]: The identity's display name.
Note that this may not always be available or up to date.
For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      \[Id \<String\>\]: Unique identifier for the identity.
    \[Device \<IMicrosoftGraphIdentity\>\]: identity
    \[User \<IMicrosoftGraphIdentity\>\]: identity
  \[CreatedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
  \[ExpectedAssessment \<String\>\]: threatExpectedAssessment
  \[RequestSource \<String\>\]: threatAssessmentRequestSource
  \[Results \<IMicrosoftGraphThreatAssessmentResult\[\]\>\]: A collection of threat assessment results.
Read-only.
By default, a GET /threatAssessmentRequests/{id} does not return this property unless you apply $expand on it.
    \[Id \<String\>\]: Read-only.
    \[CreatedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
    \[Message \<String\>\]: The result message for each threat assessment.
    \[ResultType \<String\>\]: threatAssessmentResultType
  \[Status \<String\>\]: threatAssessmentStatus

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mguserinformationprotection](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mguserinformationprotection)
