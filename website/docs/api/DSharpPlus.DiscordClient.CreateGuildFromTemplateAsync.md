# Method CreateGuildFromTemplateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_CreateGuildFromTemplateAsync_System_String_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__"></a>CreateGuildFromTemplateAsync\(string, string, Optional<Stream\>\)

Creates a guild from a template. This requires the bot to be in less than 10 guilds total.

```csharp
public Task<DiscordGuild> CreateGuildFromTemplateAsync(string code, string name, Optional<Stream> icon = default)
```

### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The template code.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the guild.

`icon` [Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Stream containing the icon for the guild.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The created guild.

### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

