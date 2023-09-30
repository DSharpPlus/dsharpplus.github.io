# Method DeleteGuildTemplateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteGuildTemplateAsync_System_UInt64_System_String_"></a>DeleteGuildTemplateAsync\(ulong, string\)

Deletes the template.

```csharp
public Task<DiscordGuildTemplate> DeleteGuildTemplateAsync(ulong guild_id, string code)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template to delete.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The deleted template.

