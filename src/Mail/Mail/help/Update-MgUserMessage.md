---
external help file: Microsoft.Graph.Mail-help.xml
Module Name: Microsoft.Graph.Mail
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.mail/update-mgusermessage
schema: 2.0.0
---

# Update-MgUserMessage

## SYNOPSIS
Update the navigation property messages in users

## SYNTAX

### UpdateExpanded1 (Default)
```
Update-MgUserMessage -MessageId <String> -UserId <String> [-AdditionalProperties <Hashtable>]
 [-Attachments <IMicrosoftGraphAttachment[]>] [-BccRecipients <IMicrosoftGraphRecipient[]>]
 [-Body <IMicrosoftGraphItemBody>] [-BodyPreview <String>] [-Categories <String[]>]
 [-CcRecipients <IMicrosoftGraphRecipient[]>] [-ChangeKey <String>] [-ConversationId <String>]
 [-ConversationIndexInputFile <String>] [-CreatedDateTime <DateTime>]
 [-Extensions <IMicrosoftGraphExtension[]>] [-Flag <IMicrosoftGraphFollowupFlag>]
 [-From <IMicrosoftGraphRecipient>] [-HasAttachments] [-Id <String>] [-Importance <String>]
 [-InferenceClassification <String>] [-InternetMessageHeaders <IMicrosoftGraphInternetMessageHeader[]>]
 [-InternetMessageId <String>] [-IsDeliveryReceiptRequested] [-IsDraft] [-IsRead] [-IsReadReceiptRequested]
 [-LastModifiedDateTime <DateTime>] [-Mentions <IMicrosoftGraphMention[]>]
 [-MentionsPreview <IMicrosoftGraphMentionsPreview>]
 [-MultiValueExtendedProperties <IMicrosoftGraphMultiValueLegacyExtendedProperty[]>] [-ParentFolderId <String>]
 [-ReceivedDateTime <DateTime>] [-ReplyTo <IMicrosoftGraphRecipient[]>] [-Sender <IMicrosoftGraphRecipient>]
 [-SentDateTime <DateTime>]
 [-SingleValueExtendedProperties <IMicrosoftGraphSingleValueLegacyExtendedProperty[]>] [-Subject <String>]
 [-ToRecipients <IMicrosoftGraphRecipient[]>] [-UniqueBody <IMicrosoftGraphItemBody>]
 [-UnsubscribeData <String[]>] [-UnsubscribeEnabled] [-WebLink <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Update1
```
Update-MgUserMessage -MessageId <String> -UserId <String> -BodyParameter <IMicrosoftGraphMessage1> [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded1
```
Update-MgUserMessage -InputObject <IMailIdentity> [-AdditionalProperties <Hashtable>]
 [-Attachments <IMicrosoftGraphAttachment[]>] [-BccRecipients <IMicrosoftGraphRecipient[]>]
 [-Body <IMicrosoftGraphItemBody>] [-BodyPreview <String>] [-Categories <String[]>]
 [-CcRecipients <IMicrosoftGraphRecipient[]>] [-ChangeKey <String>] [-ConversationId <String>]
 [-ConversationIndexInputFile <String>] [-CreatedDateTime <DateTime>]
 [-Extensions <IMicrosoftGraphExtension[]>] [-Flag <IMicrosoftGraphFollowupFlag>]
 [-From <IMicrosoftGraphRecipient>] [-HasAttachments] [-Id <String>] [-Importance <String>]
 [-InferenceClassification <String>] [-InternetMessageHeaders <IMicrosoftGraphInternetMessageHeader[]>]
 [-InternetMessageId <String>] [-IsDeliveryReceiptRequested] [-IsDraft] [-IsRead] [-IsReadReceiptRequested]
 [-LastModifiedDateTime <DateTime>] [-Mentions <IMicrosoftGraphMention[]>]
 [-MentionsPreview <IMicrosoftGraphMentionsPreview>]
 [-MultiValueExtendedProperties <IMicrosoftGraphMultiValueLegacyExtendedProperty[]>] [-ParentFolderId <String>]
 [-ReceivedDateTime <DateTime>] [-ReplyTo <IMicrosoftGraphRecipient[]>] [-Sender <IMicrosoftGraphRecipient>]
 [-SentDateTime <DateTime>]
 [-SingleValueExtendedProperties <IMicrosoftGraphSingleValueLegacyExtendedProperty[]>] [-Subject <String>]
 [-ToRecipients <IMicrosoftGraphRecipient[]>] [-UniqueBody <IMicrosoftGraphItemBody>]
 [-UnsubscribeData <String[]>] [-UnsubscribeEnabled] [-WebLink <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentity1
```
Update-MgUserMessage -InputObject <IMailIdentity> -BodyParameter <IMicrosoftGraphMessage1> [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property messages in users

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
The fileAttachment and itemAttachment attachments for the message.
To construct, see NOTES section for ATTACHMENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphAttachment[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BccRecipients
The Bcc: recipients for the message.
To construct, see NOTES section for BCCRECIPIENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphRecipient[]
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
message
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphMessage1
Parameter Sets: Update1, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BodyPreview
The first 255 characters of the message body.
It is in text format.

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

### -Categories
The categories associated with the item

```yaml
Type: String[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CcRecipients
The Cc: recipients for the message.
To construct, see NOTES section for CCRECIPIENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphRecipient[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ChangeKey
Identifies the version of the item.
Every time the item is changed, changeKey changes as well.
This allows Exchange to apply changes to the correct version of the object.
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

### -ConversationId
The ID of the conversation the email belongs to.

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

### -ConversationIndexInputFile
Input File for ConversationIndex (Indicates the position of the message within the conversation.)

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

### -CreatedDateTime
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'

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

### -Extensions
The collection of open extensions defined for the message.
Nullable.
To construct, see NOTES section for EXTENSIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphExtension[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Flag
followupFlag
To construct, see NOTES section for FLAG properties and create a hash table.

```yaml
Type: IMicrosoftGraphFollowupFlag
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -From
recipient
To construct, see NOTES section for FROM properties and create a hash table.

```yaml
Type: IMicrosoftGraphRecipient
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HasAttachments
Indicates whether the message has attachments.
This property doesn't include inline attachments, so if a message contains only inline attachments, this property is false.
To verify the existence of inline attachments, parse the body property to look for a src attribute, such as \<IMG src='cid:image001.jpg@01D26CD8.6C05F070'\>.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: False
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
importance

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

### -InferenceClassification
inferenceClassificationType

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
Type: IMailIdentity
Parameter Sets: UpdateViaIdentityExpanded1, UpdateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InternetMessageHeaders
A collection of message headers defined by RFC5322.
The set includes message headers indicating the network path taken by a message from the sender to the recipient.
It can also contain custom message headers that hold app data for the message.
Returned only on applying a $select query option.
Read-only.
To construct, see NOTES section for INTERNETMESSAGEHEADERS properties and create a hash table.

```yaml
Type: IMicrosoftGraphInternetMessageHeader[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InternetMessageId
The message ID in the format specified by RFC2822.

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

### -IsDeliveryReceiptRequested
Indicates whether a read receipt is requested for the message.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsDraft
Indicates whether the message is a draft.
A message is a draft if it hasn't been sent yet.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsRead
Indicates whether the message has been read.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsReadReceiptRequested
Indicates whether a read receipt is requested for the message.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'

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

### -Mentions
.
To construct, see NOTES section for MENTIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphMention[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MentionsPreview
mentionsPreview
To construct, see NOTES section for MENTIONSPREVIEW properties and create a hash table.

```yaml
Type: IMicrosoftGraphMentionsPreview
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MessageId
key: id of message

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

### -MultiValueExtendedProperties
The collection of multi-value extended properties defined for the message.
Nullable.
To construct, see NOTES section for MULTIVALUEEXTENDEDPROPERTIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphMultiValueLegacyExtendedProperty[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ParentFolderId
The unique identifier for the message's parent mailFolder.

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

### -ReceivedDateTime
The date and time the message was received.

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

### -ReplyTo
The email addresses to use when replying.
To construct, see NOTES section for REPLYTO properties and create a hash table.

```yaml
Type: IMicrosoftGraphRecipient[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Sender
recipient
To construct, see NOTES section for SENDER properties and create a hash table.

```yaml
Type: IMicrosoftGraphRecipient
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SentDateTime
The date and time the message was sent.

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

### -SingleValueExtendedProperties
The collection of single-value extended properties defined for the message.
Nullable.
To construct, see NOTES section for SINGLEVALUEEXTENDEDPROPERTIES properties and create a hash table.

```yaml
Type: IMicrosoftGraphSingleValueLegacyExtendedProperty[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Subject
The subject of the message.

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

### -ToRecipients
The To: recipients for the message.
To construct, see NOTES section for TORECIPIENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphRecipient[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UniqueBody
itemBody
To construct, see NOTES section for UNIQUEBODY properties and create a hash table.

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

### -UnsubscribeData
.

```yaml
Type: String[]
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UnsubscribeEnabled
.

```yaml
Type: SwitchParameter
Parameter Sets: UpdateExpanded1, UpdateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
key: id of user

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

### -WebLink
The URL to open the message in Outlook on the web.You can append an ispopout argument to the end of the URL to change how the message is displayed.
If ispopout is not present or if it is set to 1, then the message is shown in a popout window.
If ispopout is set to 0, then the browser will show the message in the Outlook on the web review pane.The message will open in the browser if you are logged in to your mailbox via Outlook on the web.
You will be prompted to login if you are not already logged in with the browser.This URL cannot be accessed from within an iFrame.

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

### Microsoft.Graph.PowerShell.Models.IMailIdentity
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMessage1
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

ATTACHMENTS \<IMicrosoftGraphAttachment\[\]\>: The fileAttachment and itemAttachment attachments for the message.
  \[Id \<String\>\]: Read-only.
  \[ContentType \<String\>\]: The MIME type.
  \[IsInline \<Boolean?\>\]: true if the attachment is an inline attachment; otherwise, false.
  \[LastModifiedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
  \[Name \<String\>\]: The attachment's file name.
  \[Size \<Int32?\>\]: The length of the attachment in bytes.

BCCRECIPIENTS \<IMicrosoftGraphRecipient\[\]\>: The Bcc: recipients for the message.
  \[EmailAddress \<IMicrosoftGraphEmailAddress\>\]: emailAddress
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Address \<String\>\]: The email address of the person or entity.
    \[Name \<String\>\]: The display name of the person or entity.

BODY \<IMicrosoftGraphItemBody\>: itemBody
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Content \<String\>\]: The content of the item.
  \[ContentType \<String\>\]: bodyType

BODYPARAMETER \<IMicrosoftGraphMessage\>: message
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Categories \<String\[\]\>\]: The categories associated with the item
  \[ChangeKey \<String\>\]: Identifies the version of the item.
Every time the item is changed, changeKey changes as well.
This allows Exchange to apply changes to the correct version of the object.
Read-only.
  \[CreatedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
  \[LastModifiedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
  \[Id \<String\>\]: Read-only.
  \[Attachments \<IMicrosoftGraphAttachment\[\]\>\]: The fileAttachment and itemAttachment attachments for the message.
    \[Id \<String\>\]: Read-only.
    \[ContentType \<String\>\]: The MIME type.
    \[IsInline \<Boolean?\>\]: true if the attachment is an inline attachment; otherwise, false.
    \[LastModifiedDateTime \<DateTime?\>\]: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
    \[Name \<String\>\]: The attachment's file name.
    \[Size \<Int32?\>\]: The length of the attachment in bytes.
  \[BccRecipients \<IMicrosoftGraphRecipient\[\]\>\]: The Bcc: recipients for the message.
    \[EmailAddress \<IMicrosoftGraphEmailAddress\>\]: emailAddress
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[Address \<String\>\]: The email address of the person or entity.
      \[Name \<String\>\]: The display name of the person or entity.
  \[Body \<IMicrosoftGraphItemBody\>\]: itemBody
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Content \<String\>\]: The content of the item.
    \[ContentType \<String\>\]: bodyType
  \[BodyPreview \<String\>\]: The first 255 characters of the message body.
It is in text format.
  \[CcRecipients \<IMicrosoftGraphRecipient\[\]\>\]: The Cc: recipients for the message.
  \[ConversationId \<String\>\]: The ID of the conversation the email belongs to.
  \[ConversationIndex \<Byte\[\]\>\]: Indicates the position of the message within the conversation.
  \[Extensions \<IMicrosoftGraphExtension\[\]\>\]: The collection of open extensions defined for the message.
Nullable.
    \[Id \<String\>\]: Read-only.
  \[Flag \<IMicrosoftGraphFollowupFlag\>\]: followupFlag
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[CompletedDateTime \<IMicrosoftGraphDateTimeZone\>\]: dateTimeTimeZone
      \[(Any) \<Object\>\]: This indicates any property can be added to this object.
      \[DateTime \<String\>\]: A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).
      \[TimeZone \<String\>\]: Represents a time zone, for example, 'Pacific Standard Time'.
See below for more possible values.
    \[DueDateTime \<IMicrosoftGraphDateTimeZone\>\]: dateTimeTimeZone
    \[FlagStatus \<String\>\]: followupFlagStatus
    \[StartDateTime \<IMicrosoftGraphDateTimeZone\>\]: dateTimeTimeZone
  \[From \<IMicrosoftGraphRecipient\>\]: recipient
  \[HasAttachments \<Boolean?\>\]: Indicates whether the message has attachments.
This property doesn't include inline attachments, so if a message contains only inline attachments, this property is false.
To verify the existence of inline attachments, parse the body property to look for a src attribute, such as \<IMG src='cid:image001.jpg@01D26CD8.6C05F070'\>.
  \[Importance \<String\>\]: importance
  \[InferenceClassification \<String\>\]: inferenceClassificationType
  \[InternetMessageHeaders \<IMicrosoftGraphInternetMessageHeader\[\]\>\]: A collection of message headers defined by RFC5322.
The set includes message headers indicating the network path taken by a message from the sender to the recipient.
It can also contain custom message headers that hold app data for the message. 
Returned only on applying a $select query option.
Read-only.
    \[Name \<String\>\]: Represents the key in a key-value pair.
    \[Value \<String\>\]: The value in a key-value pair.
  \[InternetMessageId \<String\>\]: The message ID in the format specified by RFC2822.
  \[IsDeliveryReceiptRequested \<Boolean?\>\]: Indicates whether a read receipt is requested for the message.
  \[IsDraft \<Boolean?\>\]: Indicates whether the message is a draft.
A message is a draft if it hasn't been sent yet.
  \[IsRead \<Boolean?\>\]: Indicates whether the message has been read.
  \[IsReadReceiptRequested \<Boolean?\>\]: Indicates whether a read receipt is requested for the message.
  \[MultiValueExtendedProperties \<IMicrosoftGraphMultiValueLegacyExtendedProperty\[\]\>\]: The collection of multi-value extended properties defined for the message.
Nullable.
    \[Id \<String\>\]: Read-only.
    \[Value \<String\[\]\>\]: A collection of property values.
  \[ParentFolderId \<String\>\]: The unique identifier for the message's parent mailFolder.
  \[ReceivedDateTime \<DateTime?\>\]: The date and time the message was received.
  \[ReplyTo \<IMicrosoftGraphRecipient\[\]\>\]: The email addresses to use when replying.
  \[Sender \<IMicrosoftGraphRecipient\>\]: recipient
  \[SentDateTime \<DateTime?\>\]: The date and time the message was sent.
  \[SingleValueExtendedProperties \<IMicrosoftGraphSingleValueLegacyExtendedProperty\[\]\>\]: The collection of single-value extended properties defined for the message.
Nullable.
    \[Id \<String\>\]: Read-only.
    \[Value \<String\>\]: A property value.
  \[Subject \<String\>\]: The subject of the message.
  \[ToRecipients \<IMicrosoftGraphRecipient\[\]\>\]: The To: recipients for the message.
  \[UniqueBody \<IMicrosoftGraphItemBody\>\]: itemBody
  \[WebLink \<String\>\]: The URL to open the message in Outlook on the web.You can append an ispopout argument to the end of the URL to change how the message is displayed.
If ispopout is not present or if it is set to 1, then the message is shown in a popout window.
If ispopout is set to 0, then the browser will show the message in the Outlook on the web review pane.The message will open in the browser if you are logged in to your mailbox via Outlook on the web.
You will be prompted to login if you are not already logged in with the browser.This URL cannot be accessed from within an iFrame.

CCRECIPIENTS \<IMicrosoftGraphRecipient\[\]\>: The Cc: recipients for the message.
  \[EmailAddress \<IMicrosoftGraphEmailAddress\>\]: emailAddress
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Address \<String\>\]: The email address of the person or entity.
    \[Name \<String\>\]: The display name of the person or entity.

EXTENSIONS \<IMicrosoftGraphExtension\[\]\>: The collection of open extensions defined for the message.
Nullable.
  \[Id \<String\>\]: Read-only.

FLAG \<IMicrosoftGraphFollowupFlag\>: followupFlag
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[CompletedDateTime \<IMicrosoftGraphDateTimeZone\>\]: dateTimeTimeZone
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[DateTime \<String\>\]: A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).
    \[TimeZone \<String\>\]: Represents a time zone, for example, 'Pacific Standard Time'.
See below for more possible values.
  \[DueDateTime \<IMicrosoftGraphDateTimeZone\>\]: dateTimeTimeZone
  \[FlagStatus \<String\>\]: followupFlagStatus
  \[StartDateTime \<IMicrosoftGraphDateTimeZone\>\]: dateTimeTimeZone

FROM \<IMicrosoftGraphRecipient\>: recipient
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[EmailAddress \<IMicrosoftGraphEmailAddress\>\]: emailAddress
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Address \<String\>\]: The email address of the person or entity.
    \[Name \<String\>\]: The display name of the person or entity.

INPUTOBJECT \<IMailIdentity\>: Identity Parameter
  \[AttachmentId \<String\>\]: key: id of attachment
  \[ExtensionId \<String\>\]: key: id of extension
  \[InferenceClassificationOverrideId \<String\>\]: key: id of inferenceClassificationOverride
  \[MailFolderId \<String\>\]: key: id of mailFolder
  \[MailFolderId1 \<String\>\]: key: id of mailFolder
  \[MentionId \<String\>\]: key: id of mention
  \[MessageId \<String\>\]: key: id of message
  \[MessageRuleId \<String\>\]: key: id of messageRule
  \[MultiValueLegacyExtendedPropertyId \<String\>\]: key: id of multiValueLegacyExtendedProperty
  \[SingleValueLegacyExtendedPropertyId \<String\>\]: key: id of singleValueLegacyExtendedProperty
  \[UserConfigurationId \<String\>\]: key: id of userConfiguration
  \[UserId \<String\>\]: key: id of user

INTERNETMESSAGEHEADERS \<IMicrosoftGraphInternetMessageHeader\[\]\>: A collection of message headers defined by RFC5322.
The set includes message headers indicating the network path taken by a message from the sender to the recipient.
It can also contain custom message headers that hold app data for the message.
Returned only on applying a $select query option.
Read-only.
  \[Name \<String\>\]: Represents the key in a key-value pair.
  \[Value \<String\>\]: The value in a key-value pair.

MULTIVALUEEXTENDEDPROPERTIES \<IMicrosoftGraphMultiValueLegacyExtendedProperty\[\]\>: The collection of multi-value extended properties defined for the message.
Nullable.
  \[Id \<String\>\]: Read-only.
  \[Value \<String\[\]\>\]: A collection of property values.

REPLYTO \<IMicrosoftGraphRecipient\[\]\>: The email addresses to use when replying.
  \[EmailAddress \<IMicrosoftGraphEmailAddress\>\]: emailAddress
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Address \<String\>\]: The email address of the person or entity.
    \[Name \<String\>\]: The display name of the person or entity.

SENDER \<IMicrosoftGraphRecipient\>: recipient
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[EmailAddress \<IMicrosoftGraphEmailAddress\>\]: emailAddress
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Address \<String\>\]: The email address of the person or entity.
    \[Name \<String\>\]: The display name of the person or entity.

SINGLEVALUEEXTENDEDPROPERTIES \<IMicrosoftGraphSingleValueLegacyExtendedProperty\[\]\>: The collection of single-value extended properties defined for the message.
Nullable.
  \[Id \<String\>\]: Read-only.
  \[Value \<String\>\]: A property value.

TORECIPIENTS \<IMicrosoftGraphRecipient\[\]\>: The To: recipients for the message.
  \[EmailAddress \<IMicrosoftGraphEmailAddress\>\]: emailAddress
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Address \<String\>\]: The email address of the person or entity.
    \[Name \<String\>\]: The display name of the person or entity.

UNIQUEBODY \<IMicrosoftGraphItemBody\>: itemBody
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Content \<String\>\]: The content of the item.
  \[ContentType \<String\>\]: bodyType

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.mail/update-mgusermessage](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.mail/update-mgusermessage)

## RELATED LINKS