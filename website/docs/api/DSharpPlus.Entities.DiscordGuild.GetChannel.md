# Method GetChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetChannel_System_UInt64_"></a>GetChannel\(ulong\)

Gets a channel from this guild by its ID.

```csharp
public DiscordChannel GetChannel(ulong id)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the channel to get.

### Returns

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Requested channel.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

