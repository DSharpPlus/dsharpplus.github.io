# Method SuppressNotifications

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_SuppressNotifications"></a>SuppressNotifications\(\)

Applies <xref href="DSharpPlus.MessageFlags.SupressNotifications" data-throw-if-not-resolved="false"></xref> to the message.

```csharp
IDiscordMessageBuilder SuppressNotifications()
```

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### Remarks

As per <xref href="DSharpPlus.MessageFlags.SupressNotifications" data-throw-if-not-resolved="false"></xref>, this does not change the message's allowed mentions
(controlled by <xref href="DSharpPlus.Entities.IDiscordMessageBuilder.AddMentions(System.Collections.Generic.IEnumerable%7bDSharpPlus.Entities.IMention%7d)" data-throw-if-not-resolved="false"></xref>), but instead prevents a mention from triggering a push notification.

