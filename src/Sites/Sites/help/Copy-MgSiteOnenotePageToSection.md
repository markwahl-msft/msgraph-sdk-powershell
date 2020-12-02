---
external help file: Microsoft.Graph.Sites-help.xml
Module Name: Microsoft.Graph.Sites
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.sites/copy-mgsiteonenotepagetosection
schema: 2.0.0
---

# Copy-MgSiteOnenotePageToSection

## SYNOPSIS
Invoke action copyToSection

## SYNTAX

### CopyExpanded (Default)
```
Copy-MgSiteOnenotePageToSection -OnenotePageId <String> -SiteId <String> [-AdditionalProperties <Hashtable>]
 [-GroupId <String>] [-Id <String>] [-SiteCollectionId <String>] [-SiteId1 <String>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Copy
```
Copy-MgSiteOnenotePageToSection -OnenotePageId <String> -SiteId <String>
 -BodyParameter <IPaths1LarwmeSitesSiteIdOnenotePagesOnenotepageIdMicrosoftGraphCopytosectionPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CopyViaIdentityExpanded
```
Copy-MgSiteOnenotePageToSection [-SiteId <String>] -InputObject <ISitesIdentity>
 [-AdditionalProperties <Hashtable>] [-GroupId <String>] [-Id <String>] [-SiteCollectionId <String>] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### CopyViaIdentity
```
Copy-MgSiteOnenotePageToSection -InputObject <ISitesIdentity>
 -BodyParameter <IPaths1LarwmeSitesSiteIdOnenotePagesOnenotepageIdMicrosoftGraphCopytosectionPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action copyToSection

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
Parameter Sets: CopyExpanded, CopyViaIdentityExpanded
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
Type: IPaths1LarwmeSitesSiteIdOnenotePagesOnenotepageIdMicrosoftGraphCopytosectionPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Copy, CopyViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -GroupId
.

```yaml
Type: String
Parameter Sets: CopyExpanded, CopyViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
.

```yaml
Type: String
Parameter Sets: CopyExpanded, CopyViaIdentityExpanded
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
Type: ISitesIdentity
Parameter Sets: CopyViaIdentityExpanded, CopyViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OnenotePageId
key: id of onenotePage

```yaml
Type: String
Parameter Sets: CopyExpanded, Copy
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SiteCollectionId
.

```yaml
Type: String
Parameter Sets: CopyExpanded, CopyViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SiteId
key: id of site

```yaml
Type: String
Parameter Sets: CopyExpanded, Copy
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

```yaml
Type: String
Parameter Sets: CopyViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SiteId1
.

```yaml
Type: String
Parameter Sets: CopyExpanded
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

### Microsoft.Graph.PowerShell.Models.IPaths1LarwmeSitesSiteIdOnenotePagesOnenotepageIdMicrosoftGraphCopytosectionPostRequestbodyContentApplicationJsonSchema
### Microsoft.Graph.PowerShell.Models.ISitesIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnenoteOperation
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER \<IPaths1LarwmeSitesSiteIdOnenotePagesOnenotepageIdMicrosoftGraphCopytosectionPostRequestbodyContentApplicationJsonSchema\>: .
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[GroupId \<String\>\]: 
  \[Id \<String\>\]: 
  \[SiteCollectionId \<String\>\]: 
  \[SiteId \<String\>\]: 

INPUTOBJECT \<ISitesIdentity\>: Identity Parameter
  \[ColumnDefinitionId \<String\>\]: key: id of columnDefinition
  \[ColumnLinkId \<String\>\]: key: id of columnLink
  \[ContentTypeId \<String\>\]: key: id of contentType
  \[DriveId \<String\>\]: key: id of drive
  \[EndDateTime \<String\>\]: 
  \[GroupId \<String\>\]: key: id of group
  \[IncludePersonalNotebooks \<Boolean?\>\]: 
  \[Interval \<String\>\]: 
  \[ListId \<String\>\]: key: id of list
  \[ListItemId \<String\>\]: key: id of listItem
  \[ListItemVersionId \<String\>\]: key: id of listItemVersion
  \[NotebookId \<String\>\]: key: id of notebook
  \[OnenotePageId \<String\>\]: key: id of onenotePage
  \[OnenoteSectionId \<String\>\]: key: id of onenoteSection
  \[Path \<String\>\]: 
  \[SiteId \<String\>\]: key: id of site
  \[SiteId1 \<String\>\]: key: id of site
  \[SitePageId \<String\>\]: key: id of sitePage
  \[StartDateTime \<String\>\]: 
  \[SubscriptionId \<String\>\]: key: id of subscription
  \[UserId \<String\>\]: key: id of user

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.sites/copy-mgsiteonenotepagetosection](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.sites/copy-mgsiteonenotepagetosection)
