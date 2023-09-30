# Method ListVoiceRegionsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ListVoiceRegionsAsync"></a>ListVoiceRegionsAsync\(\)

Gets the voice regions for this guild.

```csharp
public Task<IReadOnlyList<DiscordVoiceRegion>> ListVoiceRegionsAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>\>

Voice regions available for this guild.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

