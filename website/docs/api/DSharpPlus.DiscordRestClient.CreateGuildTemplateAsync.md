# Method CreateGuildTemplateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGuildTemplateAsync_System_UInt64_System_String_System_String_"></a>CreateGuildTemplateAsync\(ulong, string, string\)

Creates a guild template.

```csharp
public Task<DiscordGuildTemplate> CreateGuildTemplateAsync(ulong guild_id, string name, string description = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the template.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description of the template.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template created.

