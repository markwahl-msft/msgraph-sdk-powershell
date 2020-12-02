---
external help file: Microsoft.Graph.Teams-help.xml
Module Name: Microsoft.Graph.Teams
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/update-mgteamchannelmessage
schema: 2.0.0
---

# Update-MgTeamChannelMessage

## SYNOPSIS
Update the navigation property messages in teams

## SYNTAX

### UpdateExpanded1 (Default)
```
Update-MgTeamChannelMessage -ChannelId <String> -ChatMessageId <String> -TeamId <String>
 [-AdditionalProperties <Hashtable>] [-Attachments <IMicrosoftGraphChatMessageAttachment[]>]
 [-Body <IMicrosoftGraphItemBody>] [-ChannelIdentity <IMicrosoftGraphChannelIdentity>] [-ChatId <String>]
 [-CreatedDateTime <DateTime>] [-DeletedDateTime <DateTime>] [-Etag <String>]
 [-From <IMicrosoftGraphIdentitySet>] [-HostedContents <IMicrosoftGraphChatMessageHostedContent[]>]
 [-Id <String>] [-Importance <String>] [-LastEditedDateTime <DateTime>] [-LastModifiedDateTime <DateTime>]
 [-Locale <String>] [-Mentions <IMicrosoftGraphChatMessageMention[]>] [-MessageType <String>]
 [-PolicyViolation <IMicrosoftGraphChatMessagePolicyViolation>]
 [-Reactions <IMicrosoftGraphChatMessageReaction[]>] [-Replies <IMicrosoftGraphChatMessage[]>]
 [-ReplyToId <String>] [-Subject <String>] [-Summary <String>] [-WebUrl <String>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Update1
```
Update-MgTeamChannelMessage -ChannelId <String> -ChatMessageId <String> -TeamId <String>
 -BodyParameter <IMicrosoftGraphChatMessage> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded1
```
Update-MgTeamChannelMessage -InputObject <ITeamsIdentity> [-AdditionalProperties <Hashtable>]
 [-Attachments <IMicrosoftGraphChatMessageAttachment[]>] [-Body <IMicrosoftGraphItemBody>]
 [-ChannelIdentity <IMicrosoftGraphChannelIdentity>] [-ChatId <String>] [-CreatedDateTime <DateTime>]
 [-DeletedDateTime <DateTime>] [-Etag <String>] [-From <IMicrosoftGraphIdentitySet>]
 [-HostedContents <IMicrosoftGraphChatMessageHostedContent[]>] [-Id <String>] [-Importance <String>]
 [-LastEditedDateTime <DateTime>] [-LastModifiedDateTime <DateTime>] [-Locale <String>]
 [-Mentions <IMicrosoftGraphChatMessageMention[]>] [-MessageType <String>]
 [-PolicyViolation <IMicrosoftGraphChatMessagePolicyViolation>]
 [-Reactions <IMicrosoftGraphChatMessageReaction[]>] [-Replies <IMicrosoftGraphChatMessage[]>]
 [-ReplyToId <String>] [-Subject <String>] [-Summary <String>] [-WebUrl <String>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity1
```
Update-MgTeamChannelMessage -InputObject <ITeamsIdentity> -BodyParameter <IMicrosoftGraphChatMessage>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property messages in teams

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
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Attachments
Attached files.
Attachments are currently read-only - sending attachments is not supported.
To construct, see NOTES section for ATTACHMENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatMessageAttachment[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Body
itemBody
To construct, see NOTES section for BODY properties and create a hash table.

```yaml
Type: IMicrosoftGraphItemBody
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
chatMessage
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatMessage
Parameter Sets: Update1, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ChannelId
key: id of channel

```yaml
Type: String
Parameter Sets: UpdateExpanded1, Update1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ChannelIdentity
channelIdentity
To construct, see NOTES section for CHANNELIDENTITY properties and create a hash table.

```yaml
Type: IMicrosoftGraphChannelIdentity
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ChatId
.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ChatMessageId
key: id of chatMessage

```yaml
Type: String
Parameter Sets: UpdateExpanded1, Update1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedDateTime
Read only.
Timestamp of when the chat message was created.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeletedDateTime
Read only.
Timestamp at which the chat message was deleted, or null if not deleted.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Etag
Read-only.
Version number of the chat message.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -From
identitySet
To construct, see NOTES section for FROM properties and create a hash table.

```yaml
Type: IMicrosoftGraphIdentitySet
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HostedContents
.
To construct, see NOTES section for HOSTEDCONTENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatMessageHostedContent[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Importance
.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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
Parameter Sets: UpdateViaIdentityExpanded1, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -LastEditedDateTime
Read only.
Timestamp when edits to the chat message were made.
Triggers an 'Edited' flag in the Microsoft Teams UI.
If no edits are made the value is null.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
Read only.
Timestamp when the chat message is created (initial setting) or edited, including when a reaction is added or removed.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Locale
Locale of the chat message set by the client.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Mentions
List of entities mentioned in the chat message.
Currently supports user, bot, team, channel.
To construct, see NOTES section for MENTIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatMessageMention[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MessageType
.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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

### -PolicyViolation
chatMessagePolicyViolation
To construct, see NOTES section for POLICYVIOLATION properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatMessagePolicyViolation
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Reactions
.
To construct, see NOTES section for REACTIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatMessageReaction[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Replies
.
To construct, see NOTES section for REPLIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphChatMessage[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ReplyToId
Read-only.
Id of the parent chat message or root chat message of the thread.
(Only applies to chat messages in channels not chats)

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Subject
The subject of the chat message, in plaintext.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Summary
Summary text of the chat message that could be used for push notifications and summary views or fall back views.
Only applies to channel chat messages, not chat messages in a chat.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

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
Parameter Sets: UpdateExpanded1, Update1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WebUrl
.

```yaml
Type: String
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphChatMessage
### Microsoft.Graph.PowerShell.Models.ITeamsIdentity
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

ATTACHMENTS \<IMicrosoftGraphChatMessageAttachment\[\]\>: Attached files.
Attachments are currently read-only - sending attachments is not supported.
  \[Content \<String\>\]: The content of the attachment.
If the attachment is a rich card, set the property to the rich card object.
This property and contentUrl are mutually exclusive.
  \[ContentType \<String\>\]: The media type of the content attachment.
It can have the following values: reference: Attachment is a link to another file.
Populate the contentURL with the link to the object.file: Raw file attachment.
Populate the contenturl field with the base64 encoding of the file in data: format.image/: Image type with the type of the image specified ex: image/png, image/jpeg, image/gif.
Populate the contentUrl field with the base64 encoding of the file in data: format.video/: Video type with the format specified.
Ex: video/mp4.
Populate the contentUrl field with the base64 encoding of the file in data: format.audio/: Audio type with the format specified.
Ex: audio/wmw.
Populate the contentUrl field with the base64 encoding of the file in data: format.application/card type: Rich card attachment type with the card type specifying the exact card format to use.
Set content with the json format of the card.
Supported values for card type include:application/vnd.microsoft.card.adaptive: A rich card that can contain any combination of text, speech, images,,buttons, and input fields.
Set the content property to,an AdaptiveCard object.application/vnd.microsoft.card.animation: A rich card that plays animation.
Set the content property,to an AnimationCardobject.application/vnd.microsoft.card.audio: A rich card that plays audio files.
Set the content property,to an AudioCard object.application/vnd.microsoft.card.video: A rich card that plays videos.
Set the content property,to a VideoCard object.application/vnd.microsoft.card.hero: A Hero card.
Set the content property to a HeroCard object.application/vnd.microsoft.card.thumbnail: A Thumbnail card.
Set the content property to a ThumbnailCard object.application/vnd.microsoft.com.card.receipt: A Receipt card.
Set the content property to a ReceiptCard object.application/vnd.microsoft.com.card.signin: A user Sign In card.
Set the content property to a SignInCard object.
  \[ContentUrl \<String\>\]: URL for the content of the attachment.
Supported protocols: http, https, file and data.
  \[Id \<String\>\]: Read-only.
Unique id of the attachment.
  \[Name \<String\>\]: Name of the attachment.
  \[ThumbnailUrl \<String\>\]: URL to a thumbnail image that the channel can use if it supports using an alternative, smaller form of content or contentUrl.
For example, if you set contentType to application/word and set contentUrl to the location of the Word document, you might include a thumbnail image that represents the document.
The channel could display the thumbnail image instead of the document.
When the user clicks the image, the channel would open the document.

BODY \<IMicrosoftGraphItemBody\>: itemBody
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Content \<String\>\]: The content of the item.
  \[ContentType \<String\>\]: bodyType

BODYPARAMETER \<IMicrosoftGraphChatMessage1\>: chatMessage
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: Read-only.
  \[Attachments \<IMicrosoftGraphChatMessageAttachment\[\]\>\]: Attached files.
Attachments are currently read-only - sending attachments is not supported.
    \[Content \<String\>\]: The content of the attachment.
If the attachment is a rich card, set the property to the rich card object.
This property and contentUrl are mutually exclusive.
    \[ContentType \<String\>\]: The media type of the content attachment.
It can have the following values: reference: Attachment is a link to another file.
Populate the contentURL with the link to the object.file: Raw file attachment.
Populate the contenturl field with the base64 encoding of the file in data: format.image/: Image type with the type of the image specified ex: image/png, image/jpeg, image/gif.
Populate the contentUrl field with the base64 encoding of the file in data: format.video/: Video type with the format specified.
Ex: video/mp4.
Populate the contentUrl field with the base64 encoding of the file in data: format.audio/: Audio type with the format specified.
Ex: audio/wmw.
Populate the contentUrl field with the base64 encoding of the file in data: format.application/card type: Rich card attachment type with the card type specifying the exact card format to use.
Set content with the json format of the card.
Supported values for card type include:application/vnd.microsoft.card.adaptive: A rich card that can contain any combination of text, speech, images,,buttons, and input fields.
Set the content property to,an AdaptiveCard object.application/vnd.microsoft.card.animation: A rich card that plays animation.
Set the content property,to an AnimationCardobject.application/vnd.microsoft.card.audio: A rich card that plays audio files.
Set the content property,to an AudioCard object.application/vnd.microsoft.card.video: A rich card that plays videos.
Set the content property,to a VideoCard object.application/vnd.microsoft.card.hero: A Hero card.
Set the content property to a HeroCard object.application/vnd.microsoft.card.thumbnail: A Thumbnail card.
Set the content property to a ThumbnailCard object.application/vnd.microsoft.com.card.receipt: A Receipt card.
Set the content property to a ReceiptCard object.application/vnd.microsoft.com.card.signin: A user Sign In card.
Set the content property to a SignInCard object.
    \[ContentUrl \<String\>\]: URL for the content of the attachment.
Supported protocols: http, https, file and data.
    \[Id \<String\>\]: Read-only.
Unique id of the attachment.
    \[Name \<String\>\]: Name of the attachment.
    \[ThumbnailUrl \<String\>\]: URL to a thumbnail image that the channel can use if it supports using an alternative, smaller form of content or contentUrl.
For example, if you set contentType to application/word and set contentUrl to the location of the Word document, you might include a thumbnail image that represents the document.
The channel could display the thumbnail image instead of the document.
When the user clicks the image, the channel would open the document.
  \[Body \<IMicrosoftGraphItemBody\>\]: itemBody
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Content \<String\>\]: The content of the item.
    \[ContentType \<String\>\]: bodyType
  \[CreatedDateTime \<DateTime?\>\]: Read only.
Timestamp of when the chat message was created.
  \[DeletedDateTime \<DateTime?\>\]: Read only.
Timestamp at which the chat message was deleted, or null if not deleted.
  \[Etag \<String\>\]: Read-only.
Version number of the chat message.
  \[From \<IMicrosoftGraphIdentitySet\>\]: identitySet
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Application \<IMicrosoftGraphIdentity\>\]: identity
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[DisplayName \<String\>\]: The identity's display name.
Note that this may not always be available or up to date.
For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      \[Id \<String\>\]: Unique identifier for the identity.
    \[Device \<IMicrosoftGraphIdentity\>\]: identity
    \[User \<IMicrosoftGraphIdentity\>\]: identity
  \[HostedContents \<IMicrosoftGraphChatMessageHostedContent1\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
  \[Importance \<String\>\]: 
  \[LastEditedDateTime \<DateTime?\>\]: Read only.
Timestamp when edits to the chat message were made.
Triggers an 'Edited' flag in the Microsoft Teams UI.
If no edits are made the value is null.
  \[LastModifiedDateTime \<DateTime?\>\]: Read only.
Timestamp when the chat message is created (initial setting) or edited, including when a reaction is added or removed.
  \[Locale \<String\>\]: Locale of the chat message set by the client.
  \[Mentions \<IMicrosoftGraphChatMessageMention\[\]\>\]: List of entities mentioned in the chat message.
Currently supports user, bot, team, channel.
    \[Id \<Int32?\>\]: Index of an entity being mentioned in the specified chatMessage.
Matches the {index} value in the corresponding \<at id='{index}'\> tag in the message body.
    \[MentionText \<String\>\]: String used to represent the mention.
For example, a user's display name, a team name.
    \[Mentioned \<IMicrosoftGraphIdentitySet\>\]: identitySet
  \[MessageType \<String\>\]: 
  \[PolicyViolation \<IMicrosoftGraphChatMessagePolicyViolation\>\]: chatMessagePolicyViolation
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[DlpAction \<String\>\]: chatMessagePolicyViolationDlpActionTypes
    \[JustificationText \<String\>\]: Justification text provided by the sender of the message when overriding a policy violation.
    \[PolicyTip \<IMicrosoftGraphChatMessagePolicyViolationPolicyTip\>\]: chatMessagePolicyViolationPolicyTip
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[ComplianceUrl \<String\>\]: The URL a user can visit to read about the data loss prevention policies for the organization.
(ie, policies about what users shouldn't say in chats)
      \[GeneralText \<String\>\]: Explanatory text shown to the sender of the message.
      \[MatchedConditionDescriptions \<String\[\]\>\]: The list of improper data in the message that was detected by the data loss prevention app.
Each DLP app defines its own conditions, examples include 'Credit Card Number' and 'Social Security Number'.
    \[UserAction \<String\>\]: chatMessagePolicyViolationUserActionTypes
    \[VerdictDetails \<String\>\]: chatMessagePolicyViolationVerdictDetailsTypes
  \[Reactions \<IMicrosoftGraphChatMessageReaction\[\]\>\]: 
    \[CreatedDateTime \<DateTime?\>\]: 
    \[ReactionType \<String\>\]: 
    \[User \<IMicrosoftGraphIdentitySet\>\]: identitySet
  \[Replies \<IMicrosoftGraphChatMessage1\[\]\>\]: 
  \[ReplyToId \<String\>\]: Read-only.
Id of the parent chat message or root chat message of the thread.
(Only applies to chat messages in channels not chats)
  \[Subject \<String\>\]: The subject of the chat message, in plaintext.
  \[Summary \<String\>\]: Summary text of the chat message that could be used for push notifications and summary views or fall back views.
Only applies to channel chat messages, not chat messages in a chat.
  \[WebUrl \<String\>\]: 

FROM \<IMicrosoftGraphIdentitySet\>: identitySet
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Application \<IMicrosoftGraphIdentity\>\]: identity
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[DisplayName \<String\>\]: The identity's display name.
Note that this may not always be available or up to date.
For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
    \[Id \<String\>\]: Unique identifier for the identity.
  \[Device \<IMicrosoftGraphIdentity\>\]: identity
  \[User \<IMicrosoftGraphIdentity\>\]: identity

HOSTEDCONTENTS \<IMicrosoftGraphChatMessageHostedContent1\[\]\>: .
  \[Id \<String\>\]: Read-only.

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

MENTIONS \<IMicrosoftGraphChatMessageMention\[\]\>: List of entities mentioned in the chat message.
Currently supports user, bot, team, channel.
  \[Id \<Int32?\>\]: Index of an entity being mentioned in the specified chatMessage.
Matches the {index} value in the corresponding \<at id='{index}'\> tag in the message body.
  \[MentionText \<String\>\]: String used to represent the mention.
For example, a user's display name, a team name.
  \[Mentioned \<IMicrosoftGraphIdentitySet\>\]: identitySet
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Application \<IMicrosoftGraphIdentity\>\]: identity
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[DisplayName \<String\>\]: The identity's display name.
Note that this may not always be available or up to date.
For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      \[Id \<String\>\]: Unique identifier for the identity.
    \[Device \<IMicrosoftGraphIdentity\>\]: identity
    \[User \<IMicrosoftGraphIdentity\>\]: identity

POLICYVIOLATION \<IMicrosoftGraphChatMessagePolicyViolation\>: chatMessagePolicyViolation
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[DlpAction \<String\>\]: chatMessagePolicyViolationDlpActionTypes
  \[JustificationText \<String\>\]: Justification text provided by the sender of the message when overriding a policy violation.
  \[PolicyTip \<IMicrosoftGraphChatMessagePolicyViolationPolicyTip\>\]: chatMessagePolicyViolationPolicyTip
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[ComplianceUrl \<String\>\]: The URL a user can visit to read about the data loss prevention policies for the organization.
(ie, policies about what users shouldn't say in chats)
    \[GeneralText \<String\>\]: Explanatory text shown to the sender of the message.
    \[MatchedConditionDescriptions \<String\[\]\>\]: The list of improper data in the message that was detected by the data loss prevention app.
Each DLP app defines its own conditions, examples include 'Credit Card Number' and 'Social Security Number'.
  \[UserAction \<String\>\]: chatMessagePolicyViolationUserActionTypes
  \[VerdictDetails \<String\>\]: chatMessagePolicyViolationVerdictDetailsTypes

REACTIONS \<IMicrosoftGraphChatMessageReaction\[\]\>: .
  \[CreatedDateTime \<DateTime?\>\]: 
  \[ReactionType \<String\>\]: 
  \[User \<IMicrosoftGraphIdentitySet\>\]: identitySet
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Application \<IMicrosoftGraphIdentity\>\]: identity
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[DisplayName \<String\>\]: The identity's display name.
Note that this may not always be available or up to date.
For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      \[Id \<String\>\]: Unique identifier for the identity.
    \[Device \<IMicrosoftGraphIdentity\>\]: identity
    \[User \<IMicrosoftGraphIdentity\>\]: identity

REPLIES \<IMicrosoftGraphChatMessage1\[\]\>: .
  \[Id \<String\>\]: Read-only.
  \[Attachments \<IMicrosoftGraphChatMessageAttachment\[\]\>\]: Attached files.
Attachments are currently read-only - sending attachments is not supported.
    \[Content \<String\>\]: The content of the attachment.
If the attachment is a rich card, set the property to the rich card object.
This property and contentUrl are mutually exclusive.
    \[ContentType \<String\>\]: The media type of the content attachment.
It can have the following values: reference: Attachment is a link to another file.
Populate the contentURL with the link to the object.file: Raw file attachment.
Populate the contenturl field with the base64 encoding of the file in data: format.image/: Image type with the type of the image specified ex: image/png, image/jpeg, image/gif.
Populate the contentUrl field with the base64 encoding of the file in data: format.video/: Video type with the format specified.
Ex: video/mp4.
Populate the contentUrl field with the base64 encoding of the file in data: format.audio/: Audio type with the format specified.
Ex: audio/wmw.
Populate the contentUrl field with the base64 encoding of the file in data: format.application/card type: Rich card attachment type with the card type specifying the exact card format to use.
Set content with the json format of the card.
Supported values for card type include:application/vnd.microsoft.card.adaptive: A rich card that can contain any combination of text, speech, images,,buttons, and input fields.
Set the content property to,an AdaptiveCard object.application/vnd.microsoft.card.animation: A rich card that plays animation.
Set the content property,to an AnimationCardobject.application/vnd.microsoft.card.audio: A rich card that plays audio files.
Set the content property,to an AudioCard object.application/vnd.microsoft.card.video: A rich card that plays videos.
Set the content property,to a VideoCard object.application/vnd.microsoft.card.hero: A Hero card.
Set the content property to a HeroCard object.application/vnd.microsoft.card.thumbnail: A Thumbnail card.
Set the content property to a ThumbnailCard object.application/vnd.microsoft.com.card.receipt: A Receipt card.
Set the content property to a ReceiptCard object.application/vnd.microsoft.com.card.signin: A user Sign In card.
Set the content property to a SignInCard object.
    \[ContentUrl \<String\>\]: URL for the content of the attachment.
Supported protocols: http, https, file and data.
    \[Id \<String\>\]: Read-only.
Unique id of the attachment.
    \[Name \<String\>\]: Name of the attachment.
    \[ThumbnailUrl \<String\>\]: URL to a thumbnail image that the channel can use if it supports using an alternative, smaller form of content or contentUrl.
For example, if you set contentType to application/word and set contentUrl to the location of the Word document, you might include a thumbnail image that represents the document.
The channel could display the thumbnail image instead of the document.
When the user clicks the image, the channel would open the document.
  \[Body \<IMicrosoftGraphItemBody\>\]: itemBody
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Content \<String\>\]: The content of the item.
    \[ContentType \<String\>\]: bodyType
  \[CreatedDateTime \<DateTime?\>\]: Read only.
Timestamp of when the chat message was created.
  \[DeletedDateTime \<DateTime?\>\]: Read only.
Timestamp at which the chat message was deleted, or null if not deleted.
  \[Etag \<String\>\]: Read-only.
Version number of the chat message.
  \[From \<IMicrosoftGraphIdentitySet\>\]: identitySet
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Application \<IMicrosoftGraphIdentity\>\]: identity
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[DisplayName \<String\>\]: The identity's display name.
Note that this may not always be available or up to date.
For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using delta.
      \[Id \<String\>\]: Unique identifier for the identity.
    \[Device \<IMicrosoftGraphIdentity\>\]: identity
    \[User \<IMicrosoftGraphIdentity\>\]: identity
  \[HostedContents \<IMicrosoftGraphChatMessageHostedContent1\[\]\>\]: 
    \[Id \<String\>\]: Read-only.
  \[Importance \<String\>\]: 
  \[LastEditedDateTime \<DateTime?\>\]: Read only.
Timestamp when edits to the chat message were made.
Triggers an 'Edited' flag in the Microsoft Teams UI.
If no edits are made the value is null.
  \[LastModifiedDateTime \<DateTime?\>\]: Read only.
Timestamp when the chat message is created (initial setting) or edited, including when a reaction is added or removed.
  \[Locale \<String\>\]: Locale of the chat message set by the client.
  \[Mentions \<IMicrosoftGraphChatMessageMention\[\]\>\]: List of entities mentioned in the chat message.
Currently supports user, bot, team, channel.
    \[Id \<Int32?\>\]: Index of an entity being mentioned in the specified chatMessage.
Matches the {index} value in the corresponding \<at id='{index}'\> tag in the message body.
    \[MentionText \<String\>\]: String used to represent the mention.
For example, a user's display name, a team name.
    \[Mentioned \<IMicrosoftGraphIdentitySet\>\]: identitySet
  \[MessageType \<String\>\]: 
  \[PolicyViolation \<IMicrosoftGraphChatMessagePolicyViolation\>\]: chatMessagePolicyViolation
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[DlpAction \<String\>\]: chatMessagePolicyViolationDlpActionTypes
    \[JustificationText \<String\>\]: Justification text provided by the sender of the message when overriding a policy violation.
    \[PolicyTip \<IMicrosoftGraphChatMessagePolicyViolationPolicyTip\>\]: chatMessagePolicyViolationPolicyTip
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[ComplianceUrl \<String\>\]: The URL a user can visit to read about the data loss prevention policies for the organization.
(ie, policies about what users shouldn't say in chats)
      \[GeneralText \<String\>\]: Explanatory text shown to the sender of the message.
      \[MatchedConditionDescriptions \<String\[\]\>\]: The list of improper data in the message that was detected by the data loss prevention app.
Each DLP app defines its own conditions, examples include 'Credit Card Number' and 'Social Security Number'.
    \[UserAction \<String\>\]: chatMessagePolicyViolationUserActionTypes
    \[VerdictDetails \<String\>\]: chatMessagePolicyViolationVerdictDetailsTypes
  \[Reactions \<IMicrosoftGraphChatMessageReaction\[\]\>\]: 
    \[CreatedDateTime \<DateTime?\>\]: 
    \[ReactionType \<String\>\]: 
    \[User \<IMicrosoftGraphIdentitySet\>\]: identitySet
  \[Replies \<IMicrosoftGraphChatMessage1\[\]\>\]: 
  \[ReplyToId \<String\>\]: Read-only.
Id of the parent chat message or root chat message of the thread.
(Only applies to chat messages in channels not chats)
  \[Subject \<String\>\]: The subject of the chat message, in plaintext.
  \[Summary \<String\>\]: Summary text of the chat message that could be used for push notifications and summary views or fall back views.
Only applies to channel chat messages, not chat messages in a chat.
  \[WebUrl \<String\>\]:

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/update-mgteamchannelmessage](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.teams/update-mgteamchannelmessage)

## RELATED LINKS