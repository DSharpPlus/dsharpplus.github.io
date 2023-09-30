# Class DiscordAuditLogIntegrationEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogIntegrationEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogIntegrationEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogIntegrationEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogIntegrationEntry_EnableEmoticons"></a>EnableEmoticons

Gets the description of emoticons' change.

```csharp
public PropertyChange<bool?> EnableEmoticons { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogIntegrationEntry_ExpireBehavior"></a>ExpireBehavior

Gets the description of expire behavior change.

```csharp
public PropertyChange<int?> ExpireBehavior { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogIntegrationEntry_ExpireGracePeriod"></a>ExpireGracePeriod

Gets the description of expire grace period's change.

```csharp
public PropertyChange<int?> ExpireGracePeriod { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogIntegrationEntry_Name"></a>Name

Gets the name of the integration.

```csharp
public PropertyChange<string> Name { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogIntegrationEntry_Type"></a>Type

Gets the type of the integration.

```csharp
public PropertyChange<string> Type { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

