# Class ChannelEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class ChannelEditModel : BaseEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseEditModel](DSharpPlus.Net.Models.BaseEditModel.md) ← 
[ChannelEditModel](DSharpPlus.Net.Models.ChannelEditModel.md)

###### Derived

[ThreadChannelEditModel](DSharpPlus.Net.Models.ThreadChannelEditModel.md)

###### Inherited Members

[BaseEditModel.AuditLogReason](DSharpPlus.Net.Models.BaseEditModel.md\#DSharpPlus\_Net\_Models\_BaseEditModel\_AuditLogReason)

## Properties

### <a id="DSharpPlus_Net_Models_ChannelEditModel_AvailableTags"></a>AvailableTags

<p>Sets the channel's available tags.</p>

```csharp
public IEnumerable<DiscordForumTagBuilder> AvailableTags { set; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Bitrate"></a>Bitrate

Sets the voice channel's new bitrate.

```csharp
public int? Bitrate { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Net_Models_ChannelEditModel_DefaultAutoArchiveDuration"></a>DefaultAutoArchiveDuration

<p>Sets the channel's auto-archive duration.</p>

```csharp
public Optional<AutoArchiveDuration?> DefaultAutoArchiveDuration { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)?\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_DefaultForumLayout"></a>DefaultForumLayout

Sets the default layout of posts in this channel.

```csharp
public Optional<DefaultForumLayout> DefaultForumLayout { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultForumLayout](DSharpPlus.DefaultForumLayout.md)\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_DefaultReaction"></a>DefaultReaction

<p>Sets the channel's default reaction, if any.</p>

```csharp
public Optional<DefaultReaction?> DefaultReaction { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultReaction](DSharpPlus.Entities.DefaultReaction.md)?\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_DefaultSortOrder"></a>DefaultSortOrder

Sets the default sort order of posts in this channel.

```csharp
public Optional<DefaultSortOrder?> DefaultSortOrder { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultSortOrder](DSharpPlus.DefaultSortOrder.md)?\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_DefaultThreadRateLimit"></a>DefaultThreadRateLimit

<p>Sets the default slowmode of newly created threads, but does not retroactively update.</p>

```csharp
public Optional<int> DefaultThreadRateLimit { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

#### Remarks

https://discord.com/developers/docs/resources/channel#modify-channel-json-params-guild-channel

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Flags"></a>Flags

<p>Sets the channel's flags (forum channels and posts only).</p>

```csharp
public Optional<ChannelFlags> Flags { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[ChannelFlags](DSharpPlus.ChannelFlags.md)\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Name"></a>Name

Sets the channel's new name.

```csharp
public string Name { set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Nsfw"></a>Nsfw

Sets whether the channel is to be marked as NSFW.

```csharp
public bool? Nsfw { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Parent"></a>Parent

<p>Sets the parent of this channel.</p>
<p>This should be channel with <xref href="DSharpPlus.Entities.DiscordChannel.Type" data-throw-if-not-resolved="false"></xref> set to <xref href="DSharpPlus.ChannelType.Category" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public Optional<DiscordChannel> Parent { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_PerUserRateLimit"></a>PerUserRateLimit

<p>Sets the channel's new slow mode timeout.</p>
<p>Setting this to null or 0 will disable slow mode.</p>

```csharp
public Optional<int?> PerUserRateLimit { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_PermissionOverwrites"></a>PermissionOverwrites

<p>Sets the channel's permission overwrites.</p>

```csharp
public IEnumerable<DiscordOverwriteBuilder> PermissionOverwrites { set; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Position"></a>Position

Sets the channel's new position.

```csharp
public int? Position { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Net_Models_ChannelEditModel_QualityMode"></a>QualityMode

<p>Sets the voice channel's video quality.</p>

```csharp
public VideoQualityMode? QualityMode { set; }
```

#### Property Value

[VideoQualityMode](DSharpPlus.VideoQualityMode.md)?

### <a id="DSharpPlus_Net_Models_ChannelEditModel_RtcRegion"></a>RtcRegion

<p>Sets the voice channel's region override.</p>
<p>Setting this to null will set it to automatic.</p>

```csharp
public Optional<DiscordVoiceRegion> RtcRegion { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Topic"></a>Topic

Sets the channel's new topic.

```csharp
public Optional<string> Topic { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Type"></a>Type

<p>Sets the channel's type.</p>
<p>This can only be used to convert between text and news channels.</p>

```csharp
public Optional<ChannelType> Type { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[ChannelType](DSharpPlus.ChannelType.md)\>

### <a id="DSharpPlus_Net_Models_ChannelEditModel_Userlimit"></a>Userlimit

<p>Sets the voice channel's new user limit.</p>
<p>Setting this to 0 will disable the user limit.</p>

```csharp
public int? Userlimit { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

