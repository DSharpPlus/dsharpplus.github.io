# Class GuildUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.GuildUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildUpdateEventArgs](DSharpPlus.EventArgs.GuildUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildUpdateEventArgs_GuildAfter"></a>GuildAfter

Gets the guild after it was updated.

```csharp
public DiscordGuild GuildAfter { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_GuildUpdateEventArgs_GuildBefore"></a>GuildBefore

Gets the guild before it was updated.

```csharp
public DiscordGuild GuildBefore { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

