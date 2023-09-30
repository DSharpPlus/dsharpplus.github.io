# Class ScheduledGuildEventEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class ScheduledGuildEventEditModel : BaseEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseEditModel](DSharpPlus.Net.Models.BaseEditModel.md) ← 
[ScheduledGuildEventEditModel](DSharpPlus.Net.Models.ScheduledGuildEventEditModel.md)

###### Inherited Members

[BaseEditModel.AuditLogReason](DSharpPlus.Net.Models.BaseEditModel.md\#DSharpPlus\_Net\_Models\_BaseEditModel\_AuditLogReason)

## Properties

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_Channel"></a>Channel

The new channel ID of the event. This must be set to null for external events.

```csharp
public Optional<DiscordChannel?> Channel { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)?\>

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_Description"></a>Description

The new description of the event.

```csharp
public Optional<string> Description { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_EndTime"></a>EndTime

The new end time of the event.

```csharp
public Optional<DateTimeOffset> EndTime { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)\>

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_Metadata"></a>Metadata

The new metadata of the event.

```csharp
public Optional<DiscordScheduledGuildEventMetadata> Metadata { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordScheduledGuildEventMetadata](DSharpPlus.Entities.DiscordScheduledGuildEventMetadata.md)\>

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_Name"></a>Name

The new name of the event.

```csharp
public Optional<string> Name { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_PrivacyLevel"></a>PrivacyLevel

The new privacy of the event.

```csharp
public Optional<ScheduledGuildEventPrivacyLevel> PrivacyLevel { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)\>

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_StartTime"></a>StartTime

The new time of the event.

```csharp
public Optional<DateTimeOffset> StartTime { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)\>

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_Status"></a>Status

The new status of the event.

```csharp
public Optional<ScheduledGuildEventStatus> Status { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[ScheduledGuildEventStatus](DSharpPlus.Entities.ScheduledGuildEventStatus.md)\>

### <a id="DSharpPlus_Net_Models_ScheduledGuildEventEditModel_Type"></a>Type

The type of the event.

```csharp
public Optional<ScheduledGuildEventType> Type { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[ScheduledGuildEventType](DSharpPlus.Entities.ScheduledGuildEventType.md)\>

