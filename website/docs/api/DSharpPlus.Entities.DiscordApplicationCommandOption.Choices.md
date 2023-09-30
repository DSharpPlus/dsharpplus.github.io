# Property Choices

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_Choices"></a>Choices

Gets the optional choices for this command parameter. Not applicable for auto-complete options.

```csharp
[JsonProperty("choices", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyCollection<DiscordApplicationCommandOptionChoice> Choices { get; }
```

### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordApplicationCommandOptionChoice](DSharpPlus.Entities.DiscordApplicationCommandOptionChoice.md)\>

