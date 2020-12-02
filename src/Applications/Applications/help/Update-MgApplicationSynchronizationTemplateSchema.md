---
external help file: Microsoft.Graph.Applications-help.xml
Module Name: Microsoft.Graph.Applications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.applications/update-mgapplicationsynchronizationtemplateschema
schema: 2.0.0
---

# Update-MgApplicationSynchronizationTemplateSchema

## SYNOPSIS
Update the navigation property schema in applications

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgApplicationSynchronizationTemplateSchema -ApplicationId <String> -SynchronizationTemplateId <String>
 [-AdditionalProperties <Hashtable>] [-Directories <IMicrosoftGraphDirectoryDefinition[]>] [-Id <String>]
 [-SynchronizationRules <IMicrosoftGraphSynchronizationRule[]>] [-Version <String>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgApplicationSynchronizationTemplateSchema -ApplicationId <String> -SynchronizationTemplateId <String>
 -BodyParameter <IMicrosoftGraphSynchronizationSchema> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgApplicationSynchronizationTemplateSchema -InputObject <IApplicationsIdentity>
 [-AdditionalProperties <Hashtable>] [-Directories <IMicrosoftGraphDirectoryDefinition[]>] [-Id <String>]
 [-SynchronizationRules <IMicrosoftGraphSynchronizationRule[]>] [-Version <String>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgApplicationSynchronizationTemplateSchema -InputObject <IApplicationsIdentity>
 -BodyParameter <IMicrosoftGraphSynchronizationSchema> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property schema in applications

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

### -ApplicationId
key: id of application

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

### -BodyParameter
synchronizationSchema
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphSynchronizationSchema
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Directories
.
To construct, see NOTES section for DIRECTORIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphDirectoryDefinition[]
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
Type: IApplicationsIdentity
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

### -SynchronizationRules
.
To construct, see NOTES section for SYNCHRONIZATIONRULES properties and create a hash table.

```yaml
Type: IMicrosoftGraphSynchronizationRule[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SynchronizationTemplateId
key: id of synchronizationTemplate

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

### -Version
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
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSynchronizationSchema
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER \<IMicrosoftGraphSynchronizationSchema\>: synchronizationSchema
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[Directories \<IMicrosoftGraphDirectoryDefinition\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
    \[Discoverabilities \<String\>\]: directoryDefinitionDiscoverabilities
    \[DiscoveryDateTime \<DateTime?\>\]: 
    \[Name \<String\>\]: 
    \[Objects \<IMicrosoftGraphObjectDefinition\[\]\>\]: 
      \[Attributes \<IMicrosoftGraphAttributeDefinition\[\]\>\]: 
        \[Anchor \<Boolean?\>\]: 
        \[ApiExpressions \<IMicrosoftGraphStringKeyStringValuePair\[\]\>\]: 
          \[Key \<String\>\]: 
          \[Value \<String\>\]: 
        \[CaseExact \<Boolean?\>\]: 
        \[DefaultValue \<String\>\]: 
        \[FlowNullValues \<Boolean?\>\]: 
        \[Metadata \<IMicrosoftGraphMetadataEntry\[\]\>\]: 
          \[Key \<String\>\]: 
          \[Value \<String\>\]: 
        \[Multivalued \<Boolean?\>\]: 
        \[Mutability \<String\>\]: mutability
        \[Name \<String\>\]: 
        \[ReferencedObjects \<IMicrosoftGraphReferencedObject\[\]\>\]: 
          \[ReferencedObjectName \<String\>\]: 
          \[ReferencedProperty \<String\>\]: 
        \[Required \<Boolean?\>\]: 
        \[Type \<String\>\]: attributeType
      \[Metadata \<IMicrosoftGraphMetadataEntry\[\]\>\]: 
      \[Name \<String\>\]: 
      \[SupportedApis \<String\[\]\>\]: 
    \[ReadOnly \<Boolean?\>\]: 
    \[Version \<String\>\]: 
  \[SynchronizationRules \<IMicrosoftGraphSynchronizationRule\[\]\>\]: 
    \[Editable \<Boolean?\>\]: 
    \[Id \<String\>\]: 
    \[Metadata \<IMicrosoftGraphStringKeyStringValuePair\[\]\>\]: 
    \[Name \<String\>\]: 
    \[ObjectMappings \<IMicrosoftGraphObjectMapping\[\]\>\]: 
      \[AttributeMappings \<IMicrosoftGraphAttributeMapping\[\]\>\]: 
        \[DefaultValue \<String\>\]: 
        \[ExportMissingReferences \<Boolean?\>\]: 
        \[FlowBehavior \<String\>\]: attributeFlowBehavior
        \[FlowType \<String\>\]: attributeFlowType
        \[MatchingPriority \<Int32?\>\]: 
        \[Source \<IMicrosoftGraphAttributeMappingSource\>\]: attributeMappingSource
          \[(Any) \<Object\>\]: This indicates any property can be added to this object.
          \[Expression \<String\>\]: 
          \[Name \<String\>\]: 
          \[Parameters \<IMicrosoftGraphStringKeyAttributeMappingSourceValuePair\[\]\>\]: 
            \[Key \<String\>\]: 
            \[Value \<IMicrosoftGraphAttributeMappingSource\>\]: attributeMappingSource
          \[Type \<String\>\]: attributeMappingSourceType
        \[TargetAttributeName \<String\>\]: 
      \[Enabled \<Boolean?\>\]: 
      \[FlowTypes \<String\>\]: objectFlowTypes
      \[Metadata \<IMicrosoftGraphMetadataEntry\[\]\>\]: 
      \[Name \<String\>\]: 
      \[Scope \<IMicrosoftGraphFilter\>\]: filter
        \[(Any) \<Object\>\]: This indicates any property can be added to this object.
        \[CategoryFilterGroups \<IMicrosoftGraphFilterGroup\[\]\>\]: 
          \[Clauses \<IMicrosoftGraphFilterClause\[\]\>\]: 
            \[OperatorName \<String\>\]: 
            \[SourceOperandName \<String\>\]: 
            \[TargetOperand \<IMicrosoftGraphFilterOperand\>\]: filterOperand
              \[(Any) \<Object\>\]: This indicates any property can be added to this object.
              \[Values \<String\[\]\>\]: 
          \[Name \<String\>\]: 
        \[Groups \<IMicrosoftGraphFilterGroup\[\]\>\]: 
        \[InputFilterGroups \<IMicrosoftGraphFilterGroup\[\]\>\]: 
      \[SourceObjectName \<String\>\]: 
      \[TargetObjectName \<String\>\]: 
    \[Priority \<Int32?\>\]: 
    \[SourceDirectoryName \<String\>\]: 
    \[TargetDirectoryName \<String\>\]: 
  \[Version \<String\>\]: 

DIRECTORIES \<IMicrosoftGraphDirectoryDefinition\[\]\>: .
  \[Id \<String\>\]: Read-only.
  \[Discoverabilities \<String\>\]: directoryDefinitionDiscoverabilities
  \[DiscoveryDateTime \<DateTime?\>\]: 
  \[Name \<String\>\]: 
  \[Objects \<IMicrosoftGraphObjectDefinition\[\]\>\]: 
    \[Attributes \<IMicrosoftGraphAttributeDefinition\[\]\>\]: 
      \[Anchor \<Boolean?\>\]: 
      \[ApiExpressions \<IMicrosoftGraphStringKeyStringValuePair\[\]\>\]: 
        \[Key \<String\>\]: 
        \[Value \<String\>\]: 
      \[CaseExact \<Boolean?\>\]: 
      \[DefaultValue \<String\>\]: 
      \[FlowNullValues \<Boolean?\>\]: 
      \[Metadata \<IMicrosoftGraphMetadataEntry\[\]\>\]: 
        \[Key \<String\>\]: 
        \[Value \<String\>\]: 
      \[Multivalued \<Boolean?\>\]: 
      \[Mutability \<String\>\]: mutability
      \[Name \<String\>\]: 
      \[ReferencedObjects \<IMicrosoftGraphReferencedObject\[\]\>\]: 
        \[ReferencedObjectName \<String\>\]: 
        \[ReferencedProperty \<String\>\]: 
      \[Required \<Boolean?\>\]: 
      \[Type \<String\>\]: attributeType
    \[Metadata \<IMicrosoftGraphMetadataEntry\[\]\>\]: 
    \[Name \<String\>\]: 
    \[SupportedApis \<String\[\]\>\]: 
  \[ReadOnly \<Boolean?\>\]: 
  \[Version \<String\>\]: 

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

SYNCHRONIZATIONRULES \<IMicrosoftGraphSynchronizationRule\[\]\>: .
  \[Editable \<Boolean?\>\]: 
  \[Id \<String\>\]: 
  \[Metadata \<IMicrosoftGraphStringKeyStringValuePair\[\]\>\]: 
    \[Key \<String\>\]: 
    \[Value \<String\>\]: 
  \[Name \<String\>\]: 
  \[ObjectMappings \<IMicrosoftGraphObjectMapping\[\]\>\]: 
    \[AttributeMappings \<IMicrosoftGraphAttributeMapping\[\]\>\]: 
      \[DefaultValue \<String\>\]: 
      \[ExportMissingReferences \<Boolean?\>\]: 
      \[FlowBehavior \<String\>\]: attributeFlowBehavior
      \[FlowType \<String\>\]: attributeFlowType
      \[MatchingPriority \<Int32?\>\]: 
      \[Source \<IMicrosoftGraphAttributeMappingSource\>\]: attributeMappingSource
        \[(Any) \<Object\>\]: This indicates any property can be added to this object.
        \[Expression \<String\>\]: 
        \[Name \<String\>\]: 
        \[Parameters \<IMicrosoftGraphStringKeyAttributeMappingSourceValuePair\[\]\>\]: 
          \[Key \<String\>\]: 
          \[Value \<IMicrosoftGraphAttributeMappingSource\>\]: attributeMappingSource
        \[Type \<String\>\]: attributeMappingSourceType
      \[TargetAttributeName \<String\>\]: 
    \[Enabled \<Boolean?\>\]: 
    \[FlowTypes \<String\>\]: objectFlowTypes
    \[Metadata \<IMicrosoftGraphMetadataEntry\[\]\>\]: 
      \[Key \<String\>\]: 
      \[Value \<String\>\]: 
    \[Name \<String\>\]: 
    \[Scope \<IMicrosoftGraphFilter\>\]: filter
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[CategoryFilterGroups \<IMicrosoftGraphFilterGroup\[\]\>\]: 
        \[Clauses \<IMicrosoftGraphFilterClause\[\]\>\]: 
          \[OperatorName \<String\>\]: 
          \[SourceOperandName \<String\>\]: 
          \[TargetOperand \<IMicrosoftGraphFilterOperand\>\]: filterOperand
            \[(Any) \<Object\>\]: This indicates any property can be added to this object.
            \[Values \<String\[\]\>\]: 
        \[Name \<String\>\]: 
      \[Groups \<IMicrosoftGraphFilterGroup\[\]\>\]: 
      \[InputFilterGroups \<IMicrosoftGraphFilterGroup\[\]\>\]: 
    \[SourceObjectName \<String\>\]: 
    \[TargetObjectName \<String\>\]: 
  \[Priority \<Int32?\>\]: 
  \[SourceDirectoryName \<String\>\]: 
  \[TargetDirectoryName \<String\>\]:

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.applications/update-mgapplicationsynchronizationtemplateschema](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.applications/update-mgapplicationsynchronizationtemplateschema)
