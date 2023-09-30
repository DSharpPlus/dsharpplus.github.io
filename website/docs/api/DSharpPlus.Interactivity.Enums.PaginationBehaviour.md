# Enum PaginationBehaviour

Namespace: [DSharpPlus.Interactivity.Enums](DSharpPlus.Interactivity.Enums.md)  
Assembly: DSharpPlus.Interactivity.dll

Specifies how pagination will handle advancing past the first and last pages.

```csharp
public enum PaginationBehaviour
```

###### Extension Methods

[ExtensionMethods.GetName<PaginationBehaviour\>\(PaginationBehaviour\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`Ignore = 1` 

Attempting to go beyond the first or last page will be ignored.

`WrapAround = 0` 

Going forward beyond the last page will loop back to the first page.
Likewise, going back from the first page will loop around to the last page.

