# Method ListVoiceRegionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_BaseDiscordClient_ListVoiceRegionsAsync"></a>ListVoiceRegionsAsync\(\)

Gets a list of regions

```csharp
public Task<IReadOnlyList<DiscordVoiceRegion>> ListVoiceRegionsAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>\>

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

