---
external help file: Microsoft.Graph.Teams-help.xml
Module Name: Microsoft.Graph.Teams
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/get-mgteamprimarychannelmember
schema: 2.0.0
---

# Get-MgTeamPrimaryChannelMember

## SYNOPSIS
Get members from teams

## SYNTAX

### List (Default)
```
Get-MgTeamPrimaryChannelMember -TeamId <String> [-ExpandProperty <String[]>] [-Property <String[]>]
 [-Filter <String>] [-Search <String>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>] [-PageSize <Int32>]
 [-All] [-CountVariable <String>] [<CommonParameters>]
```

### Get
```
Get-MgTeamPrimaryChannelMember -ConversationMemberId <String> -TeamId <String> [-ExpandProperty <String[]>]
 [-Property <String[]>] [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgTeamPrimaryChannelMember -InputObject <ITeamsIdentity> [-ExpandProperty <String[]>]
 [-Property <String[]>] [<CommonParameters>]
```

## DESCRIPTION
Get members from teams

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

### -All
List all pages.

```yaml
Type: SwitchParameter
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConversationMemberId
key: id of conversationMember

```yaml
Type: String
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CountVariable
Specifies a count of the total number of items in a collection.
By default, this variable will be set in the global scope.

```yaml
Type: String
Parameter Sets: List
Aliases: CV

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpandProperty
Expand related entities

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Expand

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Filter
Filter items by property values

```yaml
Type: String
Parameter Sets: List
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
Type: ITeamsIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PageSize
Sets the page size of results.

```yaml
Type: Int32
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -Property
Select properties to be returned

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Select

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Search
Search items by search phrases

```yaml
Type: String
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Sort
Order items by property values

```yaml
Type: String[]
Parameter Sets: List
Aliases: OrderBy

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TeamId
key: id of team

```yaml
Type: String
Parameter Sets: List, Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Top
Show only the first n items

```yaml
Type: Int32
Parameter Sets: List
Aliases: Limit

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -Skip
Skip the first n items

```yaml
Type: Int32
Parameter Sets: List
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.ITeamsIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphConversationMember
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

INPUTOBJECT \<ITeamsIdentity\>: Identity Parameter
  \[ChannelId \<String\>\]: key: id of channel
  \[ChatId \<String\>\]: key: id of chat
  \[ChatMessageHostedContentId \<String\>\]: key: id of chatMessageHostedContent
  \[ChatMessageId \<String\>\]: key: id of chatMessage
  \[ChatMessageId1 \<String\>\]: key: id of chatMessage
  \[ConversationMemberId \<String\>\]: key: id of conversationMember
  \[GroupId \<String\>\]: key: id of group
  \[OfferShiftRequestId \<String\>\]: key: id of offerShiftRequest
  \[OpenShiftChangeRequestId \<String\>\]: key: id of openShiftChangeRequest
  \[OpenShiftId \<String\>\]: key: id of openShift
  \[SchedulingGroupId \<String\>\]: key: id of schedulingGroup
  \[ShiftId \<String\>\]: key: id of shift
  \[SwapShiftsChangeRequestId \<String\>\]: key: id of swapShiftsChangeRequest
  \[TeamId \<String\>\]: key: id of team
  \[TeamsAppDefinitionId \<String\>\]: key: id of teamsAppDefinition
  \[TeamsAppId \<String\>\]: key: id of teamsApp
  \[TeamsAppInstallationId \<String\>\]: key: id of teamsAppInstallation
  \[TeamsAsyncOperationId \<String\>\]: key: id of teamsAsyncOperation
  \[TeamsTabId \<String\>\]: key: id of teamsTab
  \[TimeCardId \<String\>\]: key: id of timeCard
  \[TimeOffId \<String\>\]: key: id of timeOff
  \[TimeOffReasonId \<String\>\]: key: id of timeOffReason
  \[TimeOffRequestId \<String\>\]: key: id of timeOffRequest
  \[UserId \<String\>\]: key: id of user
  \[UserScopeTeamsAppInstallationId \<String\>\]: key: id of userScopeTeamsAppInstallation
  \[WorkforceIntegrationId \<String\>\]: key: id of workforceIntegration

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/get-mgteamprimarychannelmember](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/get-mgteamprimarychannelmember)
