---
external help file: Microsoft.Graph.Identity.SignIns-help.xml
Module Name: Microsoft.Graph.Identity.SignIns
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgtrustframework
schema: 2.0.0
---

# Update-MgTrustFramework

## SYNOPSIS
Update trustFramework

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgTrustFramework [-AdditionalProperties <Hashtable>] [-KeySets <IMicrosoftGraphTrustFrameworkKeySet[]>]
 [-Policies <IMicrosoftGraphTrustFrameworkPolicy[]>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgTrustFramework -BodyParameter <IMicrosoftGraphTrustFramework> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Update trustFramework

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
Parameter Sets: UpdateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
trustFramework
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphTrustFramework
Parameter Sets: Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -KeySets
.
To construct, see NOTES section for KEYSETS properties and create a hash table.

```yaml
Type: IMicrosoftGraphTrustFrameworkKeySet[]
Parameter Sets: UpdateExpanded
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

### -Policies
.
To construct, see NOTES section for POLICIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphTrustFrameworkPolicy[]
Parameter Sets: UpdateExpanded
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTrustFramework
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER \<IMicrosoftGraphTrustFramework\>: trustFramework
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[KeySets \<IMicrosoftGraphTrustFrameworkKeySet\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
    \[Keys \<IMicrosoftGraphTrustFrameworkKey\[\]\>\]: 
      \[D \<String\>\]: 
      \[Dp \<String\>\]: 
      \[Dq \<String\>\]: 
      \[E \<String\>\]: 
      \[Exp \<Int64?\>\]: 
      \[K \<String\>\]: 
      \[Kid \<String\>\]: 
      \[Kty \<String\>\]: 
      \[N \<String\>\]: 
      \[Nbf \<Int64?\>\]: 
      \[P \<String\>\]: 
      \[Q \<String\>\]: 
      \[Qi \<String\>\]: 
      \[Use \<String\>\]: 
      \[X5C \<String\[\]\>\]: 
      \[X5T \<String\>\]: 
  \[Policies \<IMicrosoftGraphTrustFrameworkPolicy\[\]\>\]: 
    \[Id \<String\>\]: Read-only.

KEYSETS \<IMicrosoftGraphTrustFrameworkKeySet\[\]\>: .
  \[Id \<String\>\]: Read-only.
  \[Keys \<IMicrosoftGraphTrustFrameworkKey\[\]\>\]: 
    \[D \<String\>\]: 
    \[Dp \<String\>\]: 
    \[Dq \<String\>\]: 
    \[E \<String\>\]: 
    \[Exp \<Int64?\>\]: 
    \[K \<String\>\]: 
    \[Kid \<String\>\]: 
    \[Kty \<String\>\]: 
    \[N \<String\>\]: 
    \[Nbf \<Int64?\>\]: 
    \[P \<String\>\]: 
    \[Q \<String\>\]: 
    \[Qi \<String\>\]: 
    \[Use \<String\>\]: 
    \[X5C \<String\[\]\>\]: 
    \[X5T \<String\>\]: 

POLICIES \<IMicrosoftGraphTrustFrameworkPolicy\[\]\>: .
  \[Id \<String\>\]: Read-only.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgtrustframework](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.signins/update-mgtrustframework)
