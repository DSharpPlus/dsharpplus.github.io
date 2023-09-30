# Class DiscordAuditLogWebhookEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogWebhookEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogWebhookEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogWebhookEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogWebhookEntry_ApplicationIdChange"></a>ApplicationIdChange

Gets the change in application ID.

```csharp
public PropertyChange<ulong?> ApplicationIdChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogWebhookEntry_AvatarHashChange"></a>AvatarHashChange

Gets the description of webhook's avatar change.

```csharp
public PropertyChange<string> AvatarHashChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogWebhookEntry_ChannelChange"></a>ChannelChange

Gets the description of webhook's target channel change.

```csharp
public PropertyChange<DiscordChannel> ChannelChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogWebhookEntry_NameChange"></a>NameChange

Gets the description of webhook's name change.

```csharp
public PropertyChange<string> NameChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogWebhookEntry_Target"></a>Target

Gets the affected webhook.

```csharp
public DiscordWebhook Target { get; }
```

#### Property Value

[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogWebhookEntry_TypeChange"></a>TypeChange

Gets the description of webhook's type change.

```csharp
public PropertyChange<int?> TypeChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

