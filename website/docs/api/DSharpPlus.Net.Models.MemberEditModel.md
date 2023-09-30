# Class MemberEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class MemberEditModel : BaseEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseEditModel](DSharpPlus.Net.Models.BaseEditModel.md) ← 
[MemberEditModel](DSharpPlus.Net.Models.MemberEditModel.md)

###### Inherited Members

[BaseEditModel.AuditLogReason](DSharpPlus.Net.Models.BaseEditModel.md\#DSharpPlus\_Net\_Models\_BaseEditModel\_AuditLogReason)

## Properties

### <a id="DSharpPlus_Net_Models_MemberEditModel_CommunicationDisabledUntil"></a>CommunicationDisabledUntil

Whether this member should have communication restricted

```csharp
public Optional<DateTimeOffset?> CommunicationDisabledUntil { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?\>

### <a id="DSharpPlus_Net_Models_MemberEditModel_Deafened"></a>Deafened

Whether this user should be deafened

```csharp
public Optional<bool> Deafened { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

### <a id="DSharpPlus_Net_Models_MemberEditModel_Muted"></a>Muted

Whether this user should be muted in voice channels

```csharp
public Optional<bool> Muted { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

### <a id="DSharpPlus_Net_Models_MemberEditModel_Nickname"></a>Nickname

New nickname

```csharp
public Optional<string> Nickname { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_MemberEditModel_Roles"></a>Roles

New roles

```csharp
public Optional<List<DiscordRole>> Roles { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>\>

### <a id="DSharpPlus_Net_Models_MemberEditModel_VoiceChannel"></a>VoiceChannel

Voice channel to move this user to, set to null to kick

```csharp
public Optional<DiscordChannel> VoiceChannel { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

