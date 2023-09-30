# Method WithSubcommands

Namespace: [DSharpPlus.CommandsNext.Converters](DSharpPlus.CommandsNext.Converters.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Converters_BaseHelpFormatter_WithSubcommands_System_Collections_Generic_IEnumerable_DSharpPlus_CommandsNext_Command__"></a>WithSubcommands\(IEnumerable<Command\>\)

Sets the subcommands for this command, if applicable. This method will be called with filtered data.

```csharp
public abstract BaseHelpFormatter WithSubcommands(IEnumerable<Command> subcommands)
```

### Parameters

`subcommands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Command](DSharpPlus.CommandsNext.Command.md)\>

Subcommands for this command group.

### Returns

[BaseHelpFormatter](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md)

This help formatter.

