# Enum ButtonPaginationBehavior

Namespace: [DSharpPlus.Interactivity.Enums](DSharpPlus.Interactivity.Enums.md)  
Assembly: DSharpPlus.Interactivity.dll

Represents options of how to handle pagination timing out.

```csharp
public enum ButtonPaginationBehavior
```

###### Extension Methods

[ExtensionMethods.GetName<ButtonPaginationBehavior\>\(ButtonPaginationBehavior\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`DeleteButtons = 3` 

The buttons should be removed entirely when pagination times out.

`DeleteMessage = 2` 

The entire message should be deleted when pagination times out.

`Disable = 0` 

The buttons should be disabled when pagination times out.

`Ignore = 1` 

The buttons should be left as is when pagination times out.

