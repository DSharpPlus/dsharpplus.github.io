# Class GuildRoleUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.GuildRoleUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildRoleUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildRoleUpdateEventArgs](DSharpPlus.EventArgs.GuildRoleUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildRoleUpdateEventArgs_Guild"></a>Guild

Gets the guild in which the update occurred.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_GuildRoleUpdateEventArgs_RoleAfter"></a>RoleAfter

Gets the post-update role.

```csharp
public DiscordRole RoleAfter { get; }
```

#### Property Value

[DiscordRole](DSharpPlus.Entities.DiscordRole.md)

### <a id="DSharpPlus_EventArgs_GuildRoleUpdateEventArgs_RoleBefore"></a>RoleBefore

Gets the pre-update role.

```csharp
public DiscordRole RoleBefore { get; }
```

#### Property Value

[DiscordRole](DSharpPlus.Entities.DiscordRole.md)

