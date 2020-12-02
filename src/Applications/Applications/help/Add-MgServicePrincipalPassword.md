---
external help file: Microsoft.Graph.Applications-help.xml
Module Name: Microsoft.Graph.Applications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.applications/add-mgserviceprincipalpassword
schema: 2.0.0
---

# Add-MgServicePrincipalPassword

## SYNOPSIS
Invoke action addPassword

## SYNTAX

### AddExpanded (Default)
```
Add-MgServicePrincipalPassword -ServicePrincipalId <String> [-AdditionalProperties <Hashtable>]
 [-PasswordCredential <IMicrosoftGraphPasswordCredential>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Add
```
Add-MgServicePrincipalPassword -ServicePrincipalId <String>
 -BodyParameter <IPathsIeboplServiceprincipalsServiceprincipalIdMicrosoftGraphAddpasswordPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### AddViaIdentityExpanded
```
Add-MgServicePrincipalPassword -InputObject <IApplicationsIdentity> [-AdditionalProperties <Hashtable>]
 [-PasswordCredential <IMicrosoftGraphPasswordCredential>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### AddViaIdentity
```
Add-MgServicePrincipalPassword -InputObject <IApplicationsIdentity>
 -BodyParameter <IPathsIeboplServiceprincipalsServiceprincipalIdMicrosoftGraphAddpasswordPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action addPassword

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
Parameter Sets: AddExpanded, AddViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IPathsIeboplServiceprincipalsServiceprincipalIdMicrosoftGraphAddpasswordPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Add, AddViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IApplicationsIdentity
Parameter Sets: AddViaIdentityExpanded, AddViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PasswordCredential
passwordCredential
To construct, see NOTES section for PASSWORDCREDENTIAL properties and create a hash table.

```yaml
Type: IMicrosoftGraphPasswordCredential
Parameter Sets: AddExpanded, AddViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServicePrincipalId
key: id of servicePrincipal

```yaml
Type: String
Parameter Sets: AddExpanded, Add
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

### Microsoft.Graph.PowerShell.Models.IApplicationsIdentity
### Microsoft.Graph.PowerShell.Models.IPathsIeboplServiceprincipalsServiceprincipalIdMicrosoftGraphAddpasswordPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPasswordCredential
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER \<IPathsIeboplServiceprincipalsServiceprincipalIdMicrosoftGraphAddpasswordPostRequestbodyContentApplicationJsonSchema\>: .
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[PasswordCredential \<IMicrosoftGraphPasswordCredential\>\]: passwordCredential
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[CustomKeyIdentifier \<Byte\[\]\>\]: Do not use.
    \[DisplayName \<String\>\]: Friendly name for the password.
Optional.
    \[EndDateTime \<DateTime?\>\]: The date and time at which the password expires represented using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
Optional.
    \[Hint \<String\>\]: Contains the first three characters of the password.
Read-only.
    \[KeyId \<String\>\]: The unique identifier for the password.
    \[SecretText \<String\>\]: Read-only; Contains the strong passwords generated by Azure AD that are 16-64 characters in length.
The generated password value is only returned during the initial POST request to addPassword.
There is no way to retrieve this password in the future.
    \[StartDateTime \<DateTime?\>\]: The date and time at which the password becomes valid.
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
Optional.

INPUTOBJECT \<IApplicationsIdentity\>: Identity Parameter
  \[AppRoleAssignmentId \<String\>\]: key: id of appRoleAssignment
  \[ApplicationId \<String\>\]: key: id of application
  \[ApplicationTemplateId \<String\>\]: key: id of applicationTemplate
  \[ConnectorGroupId \<String\>\]: key: id of connectorGroup
  \[ConnectorId \<String\>\]: key: id of connector
  \[DelegatedPermissionClassificationId \<String\>\]: key: id of delegatedPermissionClassification
  \[DirectoryDefinitionId \<String\>\]: key: id of directoryDefinition
  \[EndpointId \<String\>\]: key: id of endpoint
  \[ExtensionPropertyId \<String\>\]: key: id of extensionProperty
  \[GroupId \<String\>\]: key: id of group
  \[LicenseDetailsId \<String\>\]: key: id of licenseDetails
  \[OnPremisesAgentGroupId \<String\>\]: key: id of onPremisesAgentGroup
  \[OnPremisesAgentGroupId1 \<String\>\]: key: id of onPremisesAgentGroup
  \[OnPremisesAgentId \<String\>\]: key: id of onPremisesAgent
  \[OnPremisesAgentId1 \<String\>\]: key: id of onPremisesAgent
  \[OnPremisesPublishingProfileId \<String\>\]: key: id of onPremisesPublishingProfile
  \[PublishedResourceId \<String\>\]: key: id of publishedResource
  \[PublishedResourceId1 \<String\>\]: key: id of publishedResource
  \[ServicePrincipalId \<String\>\]: key: id of servicePrincipal
  \[SynchronizationJobId \<String\>\]: key: id of synchronizationJob
  \[SynchronizationTemplateId \<String\>\]: key: id of synchronizationTemplate
  \[UserId \<String\>\]: key: id of user

PASSWORDCREDENTIAL \<IMicrosoftGraphPasswordCredential\>: passwordCredential
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[CustomKeyIdentifier \<Byte\[\]\>\]: Do not use.
  \[DisplayName \<String\>\]: Friendly name for the password.
Optional.
  \[EndDateTime \<DateTime?\>\]: The date and time at which the password expires represented using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
Optional.
  \[Hint \<String\>\]: Contains the first three characters of the password.
Read-only.
  \[KeyId \<String\>\]: The unique identifier for the password.
  \[SecretText \<String\>\]: Read-only; Contains the strong passwords generated by Azure AD that are 16-64 characters in length.
The generated password value is only returned during the initial POST request to addPassword.
There is no way to retrieve this password in the future.
  \[StartDateTime \<DateTime?\>\]: The date and time at which the password becomes valid.
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'.
Optional.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.applications/add-mgserviceprincipalpassword](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.applications/add-mgserviceprincipalpassword)
