# Method GetGuildAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetGuildAsync_System_UInt64_System_Nullable_System_Boolean__"></a>GetGuildAsync\(ulong, bool?\)

Gets a guild.
<p>Setting <code class="paramref">withCounts</code> to true will make a REST request.</p>

```csharp
public Task<DiscordGuild> GetGuildAsync(ulong id, bool? withCounts = null)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID to search for.

`withCounts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include approximate presence and member counts in the returned guild.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The requested Guild.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

