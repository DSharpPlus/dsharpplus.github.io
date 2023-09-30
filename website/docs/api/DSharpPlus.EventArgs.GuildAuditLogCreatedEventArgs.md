# Class GuildAuditLogCreatedEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

```csharp
public class GuildAuditLogCreatedEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildAuditLogCreatedEventArgs](DSharpPlus.EventArgs.GuildAuditLogCreatedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildAuditLogCreatedEventArgs_AuditLogEntry"></a>AuditLogEntry

Created audit log entry.

```csharp
public DiscordAuditLogEntry AuditLogEntry { get; }
```

#### Property Value

[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md)

### <a id="DSharpPlus_EventArgs_GuildAuditLogCreatedEventArgs_Guild"></a>Guild

Guild where audit log entry was created.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

