# Method CreateGuildFromTemplateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGuildFromTemplateAsync_System_String_System_String_System_String_"></a>CreateGuildFromTemplateAsync\(string, string, string\)

Creates a guild from a template. This requires the bot to be in less than 10 guilds total.

```csharp
public Task<DiscordGuild> CreateGuildFromTemplateAsync(string code, string name, string icon)
```

### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The template code.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the guild.

`icon` [string](https://learn.microsoft.com/dotnet/api/system.string)

Stream containing the icon for the guild.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The created guild.

