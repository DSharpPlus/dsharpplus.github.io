# Enum MessageFlags

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents additional features of a message.

```csharp
[Flags]
public enum MessageFlags
```

###### Extension Methods

[ExtensionMethods.GetName<MessageFlags\>\(MessageFlags\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_), 
[MessageFlagExtensions.HasMessageFlag\(MessageFlags, MessageFlags\)](DSharpPlus.MessageFlagExtensions.md\#DSharpPlus\_MessageFlagExtensions\_HasMessageFlag\_DSharpPlus\_MessageFlags\_DSharpPlus\_MessageFlags\_)

## Fields

`ContainsSuspiciousThirdPartyLink = 1024` 

Indicates that the message contains a link (usually to a file) that will prompt the user
with a precautionary message saying that the link may be unsafe.

`Crossposted = 1` 

Whether this message is the original message that was published from a news channel to subscriber channels.

`Ephemeral = 64` 

The message is only visible to the user who invoked the interaction.

`FailedToMentionSomeRolesInThread = 256` 

Indicates that some roles mentioned in the message could not be added to the current thread.

`IsCrosspost = 2` 

Whether this message is crossposted (automatically posted in a subscriber channel).

`Loading = 128` 

The message is an interaction response and the bot is "thinking".

`SourceMessageDeleted = 8` 

The source message for this crosspost has been deleted.

`SuppressedEmbeds = 4` 

Whether any embeds in the message are hidden.

`SupressNotifications = 4096` 

Indicates that this message will supress push notifications.
Mentions in the message will still have a mention indicator, however.

`Urgent = 16` 

The message came from the urgent message system.

