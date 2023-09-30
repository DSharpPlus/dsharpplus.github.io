# Method GetGuildPreviewAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetGuildPreviewAsync_System_UInt64_"></a>GetGuildPreviewAsync\(ulong\)

Gets a guild preview

```csharp
public Task<DiscordGuildPreview> GetGuildPreviewAsync(ulong id)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildPreview](DSharpPlus.Entities.DiscordGuildPreview.md)\>

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

