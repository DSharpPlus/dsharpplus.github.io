# Method Provider

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_IAutocompleteProvider_Provider_DSharpPlus_SlashCommands_AutocompleteContext_"></a>Provider\(AutocompleteContext\)

Provides autocomplete choices.

```csharp
Task<IEnumerable<DiscordAutoCompleteChoice>> Provider(AutocompleteContext ctx)
```

### Parameters

`ctx` [AutocompleteContext](DSharpPlus.SlashCommands.AutocompleteContext.md)

The autocomplete context.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAutoCompleteChoice](DSharpPlus.Entities.DiscordAutoCompleteChoice.md)\>\>

