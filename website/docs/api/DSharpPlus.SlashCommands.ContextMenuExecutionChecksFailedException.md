# Class ContextMenuExecutionChecksFailedException

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Thrown when a pre-execution check for a slash command fails.

```csharp
public sealed class ContextMenuExecutionChecksFailedException : Exception
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[ContextMenuExecutionChecksFailedException](DSharpPlus.SlashCommands.ContextMenuExecutionChecksFailedException.md)

## Fields

### <a id="DSharpPlus_SlashCommands_ContextMenuExecutionChecksFailedException_FailedChecks"></a>FailedChecks

The list of failed checks.

```csharp
public IReadOnlyList<ContextMenuCheckBaseAttribute> FailedChecks
```

#### Field Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[ContextMenuCheckBaseAttribute](DSharpPlus.SlashCommands.ContextMenuCheckBaseAttribute.md)\>

