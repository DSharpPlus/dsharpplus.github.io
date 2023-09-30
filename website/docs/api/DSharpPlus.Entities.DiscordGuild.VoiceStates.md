# Property VoiceStates

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_VoiceStates"></a>VoiceStates

Gets a dictionary of all the voice states for this guilds. The key for this dictionary is the ID of the user
the voice state corresponds to.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordVoiceState> VoiceStates { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordVoiceState](DSharpPlus.Entities.DiscordVoiceState.md)\>

