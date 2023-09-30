# Class ThreadChannelEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class ThreadChannelEditModel : ChannelEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseEditModel](DSharpPlus.Net.Models.BaseEditModel.md) ← 
[ChannelEditModel](DSharpPlus.Net.Models.ChannelEditModel.md) ← 
[ThreadChannelEditModel](DSharpPlus.Net.Models.ThreadChannelEditModel.md)

###### Inherited Members

[ChannelEditModel.Name](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Name), 
[ChannelEditModel.Position](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Position), 
[ChannelEditModel.Topic](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Topic), 
[ChannelEditModel.Nsfw](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Nsfw), 
[ChannelEditModel.Parent](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Parent), 
[ChannelEditModel.Bitrate](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Bitrate), 
[ChannelEditModel.Userlimit](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Userlimit), 
[ChannelEditModel.PerUserRateLimit](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_PerUserRateLimit), 
[ChannelEditModel.RtcRegion](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_RtcRegion), 
[ChannelEditModel.QualityMode](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_QualityMode), 
[ChannelEditModel.Type](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Type), 
[ChannelEditModel.PermissionOverwrites](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_PermissionOverwrites), 
[ChannelEditModel.DefaultAutoArchiveDuration](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_DefaultAutoArchiveDuration), 
[ChannelEditModel.Flags](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_Flags), 
[ChannelEditModel.AvailableTags](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_AvailableTags), 
[ChannelEditModel.DefaultReaction](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_DefaultReaction), 
[ChannelEditModel.DefaultThreadRateLimit](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_DefaultThreadRateLimit), 
[ChannelEditModel.DefaultSortOrder](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_DefaultSortOrder), 
[ChannelEditModel.DefaultForumLayout](DSharpPlus.Net.Models.ChannelEditModel.md\#DSharpPlus\_Net\_Models\_ChannelEditModel\_DefaultForumLayout), 
[BaseEditModel.AuditLogReason](DSharpPlus.Net.Models.BaseEditModel.md\#DSharpPlus\_Net\_Models\_BaseEditModel\_AuditLogReason)

## Properties

### <a id="DSharpPlus_Net_Models_ThreadChannelEditModel_AppliedTags"></a>AppliedTags

Sets the applied tags for the thread

```csharp
public IEnumerable<ulong> AppliedTags { set; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

### <a id="DSharpPlus_Net_Models_ThreadChannelEditModel_AutoArchiveDuration"></a>AutoArchiveDuration

Sets AutoArchiveDuration of the thread

```csharp
public AutoArchiveDuration? AutoArchiveDuration { set; }
```

#### Property Value

[AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)?

### <a id="DSharpPlus_Net_Models_ThreadChannelEditModel_Flags"></a>Flags

Sets the flags for the channel (Either PINNED or REQUIRE_TAG)

```csharp
public ChannelFlags? Flags { set; }
```

#### Property Value

[ChannelFlags](DSharpPlus.ChannelFlags.md)?

### <a id="DSharpPlus_Net_Models_ThreadChannelEditModel_IsArchived"></a>IsArchived

Sets if the thread is archived

```csharp
public bool? IsArchived { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Net_Models_ThreadChannelEditModel_Locked"></a>Locked

Sets if anyone can unarchive a thread

```csharp
public bool? Locked { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

