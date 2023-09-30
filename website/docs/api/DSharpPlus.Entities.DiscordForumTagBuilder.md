# Class DiscordForumTagBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public class DiscordForumTagBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordForumTagBuilder_FromTag_DSharpPlus_Entities_DiscordForumTag_"></a>FromTag\(DiscordForumTag\)

```csharp
public static DiscordForumTagBuilder FromTag(DiscordForumTag tag)
```

#### Parameters

`tag` [DiscordForumTag](DSharpPlus.Entities.DiscordForumTag.md)

#### Returns

[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)

### <a id="DSharpPlus_Entities_DiscordForumTagBuilder_IsModerated_System_Boolean_"></a>IsModerated\(bool\)

Sets this tag to be moderated (as in, it can only be set by users with the <xref href="DSharpPlus.Permissions.ManageThreads" data-throw-if-not-resolved="false"></xref> permission).

```csharp
public DiscordForumTagBuilder IsModerated(bool moderated = true)
```

#### Parameters

`moderated` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the tag is moderated.

#### Returns

[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)

The builder to chain calls with.

### <a id="DSharpPlus_Entities_DiscordForumTagBuilder_WithEmoji_DSharpPlus_Entities_DiscordEmoji_"></a>WithEmoji\(DiscordEmoji\)

Sets the emoji for this tag.

```csharp
public DiscordForumTagBuilder WithEmoji(DiscordEmoji emoji)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to use.

#### Returns

[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)

The builder to chain calls with.

### <a id="DSharpPlus_Entities_DiscordForumTagBuilder_WithEmojiId_System_Nullable_System_UInt64__"></a>WithEmojiId\(ulong?\)

Sets the emoji ID for this tag (which will overwrite the emoji name).

```csharp
public DiscordForumTagBuilder WithEmojiId(ulong? emojiId)
```

#### Parameters

`emojiId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

#### Returns

[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)

The builder to chain calls with.

### <a id="DSharpPlus_Entities_DiscordForumTagBuilder_WithEmojiName_System_String_"></a>WithEmojiName\(string\)

```csharp
public DiscordForumTagBuilder WithEmojiName(string emojiName)
```

#### Parameters

`emojiName` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)

The builder to chain calls with.

### <a id="DSharpPlus_Entities_DiscordForumTagBuilder_WithName_System_String_"></a>WithName\(string\)

Sets the name of this tag.

```csharp
public DiscordForumTagBuilder WithName(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the tag.

#### Returns

[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)

The builder to chain calls with.

