# Class DiscordReaction

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a reaction to a message.

```csharp
public class DiscordReaction
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordReaction](DSharpPlus.Entities.DiscordReaction.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordReaction_Count"></a>Count

Gets the total number of users who reacted with this emoji.

```csharp
[JsonProperty("count", NullValueHandling = NullValueHandling.Ignore)]
public int Count { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordReaction_Emoji"></a>Emoji

Gets the emoji used to react to this message.

```csharp
[JsonProperty("emoji", NullValueHandling = NullValueHandling.Ignore)]
public DiscordEmoji Emoji { get; }
```

#### Property Value

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

### <a id="DSharpPlus_Entities_DiscordReaction_IsMe"></a>IsMe

Gets whether the current user reacted with this emoji.

```csharp
[JsonProperty("me", NullValueHandling = NullValueHandling.Ignore)]
public bool IsMe { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

