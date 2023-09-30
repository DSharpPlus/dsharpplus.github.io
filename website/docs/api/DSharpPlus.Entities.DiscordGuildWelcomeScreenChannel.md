# Class DiscordGuildWelcomeScreenChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a channel in a welcome screen

```csharp
public class DiscordGuildWelcomeScreenChannel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordGuildWelcomeScreenChannel](DSharpPlus.Entities.DiscordGuildWelcomeScreenChannel.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordGuildWelcomeScreenChannel__ctor_System_UInt64_System_String_DSharpPlus_Entities_DiscordEmoji_"></a>DiscordGuildWelcomeScreenChannel\(ulong, string, DiscordEmoji\)

```csharp
public DiscordGuildWelcomeScreenChannel(ulong channelId, string description, DiscordEmoji emoji = null)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildWelcomeScreenChannel_ChannelId"></a>ChannelId

Gets the id of the channel.

```csharp
[JsonProperty("channel_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordGuildWelcomeScreenChannel_Description"></a>Description

Gets the description shown for the channel.

```csharp
[JsonProperty("description", NullValueHandling = NullValueHandling.Ignore)]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildWelcomeScreenChannel_EmojiId"></a>EmojiId

Gets the emoji id if the emoji is custom, when applicable.

```csharp
[JsonProperty("emoji_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? EmojiId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordGuildWelcomeScreenChannel_EmojiName"></a>EmojiName

Gets the name of the emoji if custom or the unicode character if standard, when applicable.

```csharp
[JsonProperty("emoji_name", NullValueHandling = NullValueHandling.Ignore)]
public string EmojiName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

