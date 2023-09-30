# Method GetTemplateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetTemplateAsync_System_String_"></a>GetTemplateAsync\(string\)

Gets a guild template by the code.

```csharp
public Task<DiscordGuildTemplate> GetTemplateAsync(string code)
```

### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The guild template for the code.

