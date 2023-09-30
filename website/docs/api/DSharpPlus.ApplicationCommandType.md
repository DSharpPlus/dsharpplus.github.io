# Enum ApplicationCommandType

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents the type of an <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

```csharp
public enum ApplicationCommandType
```

###### Extension Methods

[ExtensionMethods.GetName<ApplicationCommandType\>\(ApplicationCommandType\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`AutoCompleteRequest = 4` 

Inbound only: An auto-complete option is being interacted with.

`MessageContextMenu = 3` 

This command is registered as a message context menu, and is applicable when interacting with a message.

`SlashCommand = 1` 

This command is registered as a slash-command, aka "Chat Input".

`UserContextMenu = 2` 

This command is registered as a user context menu, and is applicable when interacting a user.

