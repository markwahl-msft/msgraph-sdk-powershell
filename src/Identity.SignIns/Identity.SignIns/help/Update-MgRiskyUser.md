---
external help file: Microsoft.Graph.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Identity.SignIns
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgriskyuser
schema: 2.0.0
---

# Update-MgRiskyUser

## SYNOPSIS
Update entity in riskyUsers

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgRiskyUser -RiskyUserId <String> [-AdditionalProperties <Hashtable>]
 [-History <IMicrosoftGraphRiskyUserHistoryItem[]>] [-Id <String>] [-IsDeleted] [-IsProcessing]
 [-RiskDetail <String>] [-RiskLastUpdatedDateTime <DateTime>] [-RiskLevel <String>] [-RiskState <String>]
 [-UserDisplayName <String>] [-UserPrincipalName <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Update
```
Update-MgRiskyUser -RiskyUserId <String> -BodyParameter <IMicrosoftGraphRiskyUser> [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgRiskyUser -InputObject <IIdentitySignInsIdentity> [-AdditionalProperties <Hashtable>]
 [-History <IMicrosoftGraphRiskyUserHistoryItem[]>] [-Id <String>] [-IsDeleted] [-IsProcessing]
 [-RiskDetail <String>] [-RiskLastUpdatedDateTime <DateTime>] [-RiskLevel <String>] [-RiskState <String>]
 [-UserDisplayName <String>] [-UserPrincipalName <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgRiskyUser -InputObject <IIdentitySignInsIdentity> -BodyParameter <IMicrosoftGraphRiskyUser>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update entity in riskyUsers

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
riskyUser
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphRiskyUser
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -History
The activity related to user risk level change
To construct, see NOTES section for HISTORY properties and create a hash table.

```yaml
Type: IMicrosoftGraphRiskyUserHistoryItem[]
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

### -IsDeleted
Indicates whether the user is deleted.
Possible values are: true, false

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsProcessing
Indicates wehther a user's risky state is being processed by the backend

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: False
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

### -RiskDetail
riskDetail

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

### -RiskLastUpdatedDateTime
The date and time that the risky user was last updated.

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

### -RiskLevel
riskLevel

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

### -RiskState
riskState

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

### -RiskyUserId
key: id of riskyUser

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

### -UserDisplayName
Risky user display name.

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

### -UserPrincipalName
Risky user principal name.

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
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRiskyUser
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER \<IMicrosoftGraphRiskyUser\>: riskyUser
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[History \<IMicrosoftGraphRiskyUserHistoryItem\[\]\>\]: The activity related to user risk level change
    \[History \<IMicrosoftGraphRiskyUserHistoryItem\[\]\>\]: The activity related to user risk level change
    \[IsDeleted \<Boolean?\>\]: Indicates whether the user is deleted.
Possible values are: true, false
    \[IsProcessing \<Boolean?\>\]: Indicates wehther a user's risky state is being processed by the backend
    \[RiskDetail \<String\>\]: riskDetail
    \[RiskLastUpdatedDateTime \<DateTime?\>\]: The date and time that the risky user was last updated.
    \[RiskLevel \<String\>\]: riskLevel
    \[RiskState \<String\>\]: riskState
    \[UserDisplayName \<String\>\]: Risky user display name.
    \[UserPrincipalName \<String\>\]: Risky user principal name.
    \[Id \<String\>\]: Read-only.
    \[Activity \<IMicrosoftGraphRiskUserActivity\>\]: riskUserActivity
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Detail \<String\>\]: riskDetail
      \[EventTypes \<String\[\]\>\]: 
      \[RiskEventTypes \<String\[\]\>\]: The type of risk event detected.
    \[InitiatedBy \<String\>\]: The id of actor that does the operation.
    \[UserId \<String\>\]: The id of the user.
  \[IsDeleted \<Boolean?\>\]: Indicates whether the user is deleted.
Possible values are: true, false
  \[IsProcessing \<Boolean?\>\]: Indicates wehther a user's risky state is being processed by the backend
  \[RiskDetail \<String\>\]: riskDetail
  \[RiskLastUpdatedDateTime \<DateTime?\>\]: The date and time that the risky user was last updated.
  \[RiskLevel \<String\>\]: riskLevel
  \[RiskState \<String\>\]: riskState
  \[UserDisplayName \<String\>\]: Risky user display name.
  \[UserPrincipalName \<String\>\]: Risky user principal name.

HISTORY \<IMicrosoftGraphRiskyUserHistoryItem\[\]\>: The activity related to user risk level change
  \[History \<IMicrosoftGraphRiskyUserHistoryItem\[\]\>\]: The activity related to user risk level change
  \[IsDeleted \<Boolean?\>\]: Indicates whether the user is deleted.
Possible values are: true, false
  \[IsProcessing \<Boolean?\>\]: Indicates wehther a user's risky state is being processed by the backend
  \[RiskDetail \<String\>\]: riskDetail
  \[RiskLastUpdatedDateTime \<DateTime?\>\]: The date and time that the risky user was last updated.
  \[RiskLevel \<String\>\]: riskLevel
  \[RiskState \<String\>\]: riskState
  \[UserDisplayName \<String\>\]: Risky user display name.
  \[UserPrincipalName \<String\>\]: Risky user principal name.
  \[Id \<String\>\]: Read-only.
  \[Activity \<IMicrosoftGraphRiskUserActivity\>\]: riskUserActivity
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Detail \<String\>\]: riskDetail
    \[EventTypes \<String\[\]\>\]: 
    \[RiskEventTypes \<String\[\]\>\]: The type of risk event detected.
  \[InitiatedBy \<String\>\]: The id of actor that does the operation.
  \[UserId \<String\>\]: The id of the user.

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

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgriskyuser](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgriskyuser)
