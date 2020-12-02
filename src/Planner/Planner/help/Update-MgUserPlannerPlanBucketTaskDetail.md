---
external help file: Microsoft.Graph.Planner-help.xml
Module Name: Microsoft.Graph.Planner
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.planner/update-mguserplannerplanbuckettaskdetail
schema: 2.0.0
---

# Update-MgUserPlannerPlanBucketTaskDetail

## SYNOPSIS
Update the navigation property details in users

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgUserPlannerPlanBucketTaskDetail -PlannerBucketId <String> -PlannerPlanId <String>
 -PlannerTaskId <String> -UserId <String> [-AdditionalProperties <Hashtable>] [-Checklist <Hashtable>]
 [-Description <String>] [-Id <String>] [-PreviewType <String>] [-References <Hashtable>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgUserPlannerPlanBucketTaskDetail -PlannerBucketId <String> -PlannerPlanId <String>
 -PlannerTaskId <String> -UserId <String> -BodyParameter <IMicrosoftGraphPlannerTaskDetails> [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgUserPlannerPlanBucketTaskDetail -InputObject <IPlannerIdentity> [-AdditionalProperties <Hashtable>]
 [-Checklist <Hashtable>] [-Description <String>] [-Id <String>] [-PreviewType <String>]
 [-References <Hashtable>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgUserPlannerPlanBucketTaskDetail -InputObject <IPlannerIdentity>
 -BodyParameter <IMicrosoftGraphPlannerTaskDetails> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property details in users

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
plannerTaskDetails
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphPlannerTaskDetails
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Checklist
plannerChecklistItems

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

### -Description
Description of the task

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
Type: IPlannerIdentity
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

### -PlannerBucketId
key: id of plannerBucket

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

### -PlannerPlanId
key: id of plannerPlan

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

### -PlannerTaskId
key: id of plannerTask

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

### -PreviewType
plannerPreviewType

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

### -References
plannerExternalReferences

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPlannerTaskDetails
### Microsoft.Graph.PowerShell.Models.IPlannerIdentity
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER \<IMicrosoftGraphPlannerTaskDetails1\>: plannerTaskDetails
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[Checklist \<IMicrosoftGraphPlannerChecklistItems\>\]: plannerChecklistItems
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Description \<String\>\]: Description of the task
  \[PreviewType \<String\>\]: plannerPreviewType
  \[References \<IMicrosoftGraphPlannerExternalReferences\>\]: plannerExternalReferences
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.

INPUTOBJECT \<IPlannerIdentity\>: Identity Parameter
  \[GroupId \<String\>\]: key: id of group
  \[PlannerBucketId \<String\>\]: key: id of plannerBucket
  \[PlannerDeltaId \<String\>\]: key: id of plannerDelta
  \[PlannerPlanId \<String\>\]: key: id of plannerPlan
  \[PlannerTaskId \<String\>\]: key: id of plannerTask
  \[UserId \<String\>\]: key: id of user

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.planner/update-mguserplannerplanbuckettaskdetail](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.planner/update-mguserplannerplanbuckettaskdetail)
