# Method GetSlashCommands

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_ExtensionMethods_GetSlashCommands_DSharpPlus_DiscordClient_"></a>GetSlashCommands\(DiscordClient\)

Gets the slash commands module for this client.

```csharp
public static SlashCommandsExtension GetSlashCommands(this DiscordClient client)
```

### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Client to get slash commands for.

### Returns

[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)

The module, or null if not activated.

