# Enum PaginationDeletion

Namespace: [DSharpPlus.Interactivity.Enums](DSharpPlus.Interactivity.Enums.md)  
Assembly: DSharpPlus.Interactivity.dll

Specifies what should be done once pagination times out.

```csharp
public enum PaginationDeletion
```

###### Extension Methods

[ExtensionMethods.GetName<PaginationDeletion\>\(PaginationDeletion\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`DeleteEmojis = 0` 

Reaction emojis will be deleted on timeout.

`DeleteMessage = 2` 

The message will be completely deleted on timeout.

`KeepEmojis = 1` 

Reaction emojis will not be deleted on timeout.

