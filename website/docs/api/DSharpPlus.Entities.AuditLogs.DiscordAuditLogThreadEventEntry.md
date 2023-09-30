# Class DiscordAuditLogThreadEventEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogThreadEventEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogThreadEventEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogThreadEventEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_Archived"></a>Archived

Gets a change in the thread's archived status.

```csharp
public PropertyChange<bool?> Archived { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_AutoArchiveDuration"></a>AutoArchiveDuration

Gets a change in the thread's auto archive duration.

```csharp
public PropertyChange<int?> AutoArchiveDuration { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_Flags"></a>Flags

Gets a change in channel flags

```csharp
public PropertyChange<ChannelFlags?> Flags { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ChannelFlags](DSharpPlus.ChannelFlags.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_Invitable"></a>Invitable

Gets a change in the threads invitibility

```csharp
public PropertyChange<bool?> Invitable { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_Locked"></a>Locked

Gets a change in the thread's locked status

```csharp
public PropertyChange<bool?> Locked { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_Name"></a>Name

Gets a change in the thread's name.

```csharp
public PropertyChange<string?> Name { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_PerUserRateLimit"></a>PerUserRateLimit

Gets a change in the thread's slowmode setting

```csharp
public PropertyChange<int?> PerUserRateLimit { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_Target"></a>Target

Gets the target thread.

```csharp
public DiscordThreadChannel Target { get; }
```

#### Property Value

[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogThreadEventEntry_Type"></a>Type

Gets a change in channel type.

```csharp
public PropertyChange<ChannelType?> Type { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ChannelType](DSharpPlus.ChannelType.md)?\>

