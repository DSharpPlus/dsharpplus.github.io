# Method ModifyGuildTemplateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildTemplateAsync_System_UInt64_System_String_System_String_System_String_"></a>ModifyGuildTemplateAsync\(ulong, string, string, string\)

Modifies the template's metadata.

```csharp
public Task<DiscordGuildTemplate> ModifyGuildTemplateAsync(ulong guild_id, string code, string name = null, string description = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The template's code.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the template.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description of the template.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template modified.

