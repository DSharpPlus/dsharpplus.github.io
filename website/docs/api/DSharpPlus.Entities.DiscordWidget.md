# Class DiscordWidget

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord guild's widget.

```csharp
public class DiscordWidget : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordWidget](DSharpPlus.Entities.DiscordWidget.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordWidget_Channels"></a>Channels

Gets a list of widget channels.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordChannel> Channels { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Entities_DiscordWidget_Guild"></a>Guild

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordWidget_InstantInviteUrl"></a>InstantInviteUrl

Gets the guild's invite URL.

```csharp
[JsonProperty("instant_invite", NullValueHandling = NullValueHandling.Ignore)]
public string InstantInviteUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWidget_Members"></a>Members

Gets a list of online members.

```csharp
[JsonProperty("members", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<DiscordWidgetMember> Members { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordWidgetMember](DSharpPlus.Entities.DiscordWidgetMember.md)\>

### <a id="DSharpPlus_Entities_DiscordWidget_Name"></a>Name

Gets the guild's name.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWidget_PresenceCount"></a>PresenceCount

Gets the number of online members.

```csharp
[JsonProperty("presence_count", NullValueHandling = NullValueHandling.Ignore)]
public int PresenceCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

