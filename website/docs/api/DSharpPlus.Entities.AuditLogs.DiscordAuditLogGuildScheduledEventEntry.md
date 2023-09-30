# Class DiscordAuditLogGuildScheduledEventEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogGuildScheduledEventEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogGuildScheduledEventEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogGuildScheduledEventEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Constructors

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry__ctor"></a>DiscordAuditLogGuildScheduledEventEntry\(\)

```csharp
public DiscordAuditLogGuildScheduledEventEntry()
```

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_Channel"></a>Channel

Gets the channel the event was changed to.

```csharp
public PropertyChange<DiscordChannel?> Channel { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_Description"></a>Description

Gets the description change of the event.

```csharp
public PropertyChange<string?> Description { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_ImageHash"></a>ImageHash

Gets the change in image hash.

```csharp
public PropertyChange<string?> ImageHash { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_Location"></a>Location

Gets the change in event location, if it's an external event.

```csharp
public PropertyChange<string?> Location { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_Name"></a>Name

Gets a change in the event's name

```csharp
public PropertyChange<string?> Name { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_PrivacyLevel"></a>PrivacyLevel

Gets change in privacy level.

```csharp
public PropertyChange<ScheduledGuildEventPrivacyLevel?> PrivacyLevel { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_Status"></a>Status

Gets the change in status.

```csharp
public PropertyChange<ScheduledGuildEventStatus?> Status { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ScheduledGuildEventStatus](DSharpPlus.Entities.ScheduledGuildEventStatus.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_Target"></a>Target

Gets the target event. Note that this will only have the ID specified if it is not cached.

```csharp
public DiscordScheduledGuildEvent Target { get; }
```

#### Property Value

[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildScheduledEventEntry_Type"></a>Type

Gets the change of type for the event.

```csharp
public PropertyChange<ScheduledGuildEventType?> Type { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ScheduledGuildEventType](DSharpPlus.Entities.ScheduledGuildEventType.md)?\>

