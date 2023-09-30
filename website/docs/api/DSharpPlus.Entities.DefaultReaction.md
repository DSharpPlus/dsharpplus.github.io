# Class DefaultReaction

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an emoji used for reacting to a forum post.

```csharp
public sealed class DefaultReaction
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DefaultReaction](DSharpPlus.Entities.DefaultReaction.md)

## Properties

### <a id="DSharpPlus_Entities_DefaultReaction_EmojiId"></a>EmojiId

The ID of the emoji, if applicable.

```csharp
[JsonProperty("emoji_id")]
public ulong? EmojiId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DefaultReaction_EmojiName"></a>EmojiName

The unicode emoji, if applicable.

```csharp
[JsonProperty("emoji_name")]
public string? EmojiName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

## Methods

### <a id="DSharpPlus_Entities_DefaultReaction_FromEmoji_DSharpPlus_Entities_DiscordEmoji_"></a>FromEmoji\(DiscordEmoji\)

Creates a DefaultReaction object from an emoji.

```csharp
public static DefaultReaction FromEmoji(DiscordEmoji emoji)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref>.

#### Returns

[DefaultReaction](DSharpPlus.Entities.DefaultReaction.md)

Create <xref href="DSharpPlus.Entities.DefaultReaction" data-throw-if-not-resolved="false"></xref> object.

