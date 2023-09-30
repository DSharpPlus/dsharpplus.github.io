# Class GuildRoleDeleteEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.GuildRoleDeleted" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildRoleDeleteEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildRoleDeleteEventArgs](DSharpPlus.EventArgs.GuildRoleDeleteEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildRoleDeleteEventArgs_Guild"></a>Guild

Gets the guild in which the role was deleted.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_GuildRoleDeleteEventArgs_Role"></a>Role

Gets the role that was deleted.

```csharp
public DiscordRole Role { get; }
```

#### Property Value

[DiscordRole](DSharpPlus.Entities.DiscordRole.md)

