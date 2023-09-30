# Class SlashExecutionChecksFailedException

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Thrown when a pre-execution check for a slash command fails.

```csharp
public sealed class SlashExecutionChecksFailedException : Exception
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[SlashExecutionChecksFailedException](DSharpPlus.SlashCommands.SlashExecutionChecksFailedException.md)

## Fields

### <a id="DSharpPlus_SlashCommands_SlashExecutionChecksFailedException_FailedChecks"></a>FailedChecks

The list of failed checks.

```csharp
public IReadOnlyList<SlashCheckBaseAttribute> FailedChecks
```

#### Field Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[SlashCheckBaseAttribute](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md)\>

