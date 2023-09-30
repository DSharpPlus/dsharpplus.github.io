# Class DiscordAuditLogInviteEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogInviteEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogInviteEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogInviteEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogInviteEntry_ChannelChange"></a>ChannelChange

Gets the description of invite's target channel change.

```csharp
public PropertyChange<DiscordChannel> ChannelChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogInviteEntry_CodeChange"></a>CodeChange

Gets the description of invite's code change.

```csharp
public PropertyChange<string> CodeChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogInviteEntry_InviterChange"></a>InviterChange

Gets the description of invite's inviting member change.

```csharp
public PropertyChange<DiscordMember> InviterChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogInviteEntry_MaxAgeChange"></a>MaxAgeChange

Gets the description of invite's max age change.

```csharp
public PropertyChange<int?> MaxAgeChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogInviteEntry_MaxUsesChange"></a>MaxUsesChange

Gets the description of invite's max use count change.

```csharp
public PropertyChange<int?> MaxUsesChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogInviteEntry_Target"></a>Target

Gets the affected invite.

```csharp
public DiscordInvite Target { get; }
```

#### Property Value

[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogInviteEntry_TemporaryChange"></a>TemporaryChange

Gets the description of invite's temporariness change.

```csharp
public PropertyChange<bool?> TemporaryChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogInviteEntry_UsesChange"></a>UsesChange

Gets the description of invite's use count change.

```csharp
public PropertyChange<int?> UsesChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

