# Class ForumPostBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

A builder to create a forum post.

```csharp
public class ForumPostBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

## Constructors

### <a id="DSharpPlus_Entities_ForumPostBuilder__ctor"></a>ForumPostBuilder\(\)

Creates a new forum post builder.

```csharp
public ForumPostBuilder()
```

## Properties

### <a id="DSharpPlus_Entities_ForumPostBuilder_AppliedTags"></a>AppliedTags

The tags to apply to this post.

```csharp
public IReadOnlyList<DiscordForumTag> AppliedTags { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordForumTag](DSharpPlus.Entities.DiscordForumTag.md)\>

### <a id="DSharpPlus_Entities_ForumPostBuilder_AutoArchiveDuration"></a>AutoArchiveDuration

When to automatically archive the post.

```csharp
public AutoArchiveDuration? AutoArchiveDuration { get; set; }
```

#### Property Value

[AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)?

### <a id="DSharpPlus_Entities_ForumPostBuilder_Message"></a>Message

The message to initiate the forum post with.

```csharp
public DiscordMessageBuilder Message { get; set; }
```

#### Property Value

[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_ForumPostBuilder_Name"></a>Name

The name (or title) of the post.

```csharp
public string Name { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_ForumPostBuilder_SlowMode"></a>SlowMode

The time (in seconds) that users must wait between messages.

```csharp
public int? SlowMode { get; set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

## Methods

### <a id="DSharpPlus_Entities_ForumPostBuilder_AddTag_DSharpPlus_Entities_DiscordForumTag_"></a>AddTag\(DiscordForumTag\)

Adds a tag to the post.

```csharp
public ForumPostBuilder AddTag(DiscordForumTag tag)
```

#### Parameters

`tag` [DiscordForumTag](DSharpPlus.Entities.DiscordForumTag.md)

The tag to add.

#### Returns

[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

The builder to chain calls with.

### <a id="DSharpPlus_Entities_ForumPostBuilder_AddTags_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordForumTag__"></a>AddTags\(IEnumerable<DiscordForumTag\>\)

Adds several tags to the post.

```csharp
public ForumPostBuilder AddTags(IEnumerable<DiscordForumTag> tags)
```

#### Parameters

`tags` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordForumTag](DSharpPlus.Entities.DiscordForumTag.md)\>

The tags to add.

#### Returns

[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

The builder to chain calls with.

### <a id="DSharpPlus_Entities_ForumPostBuilder_RemoveTag_DSharpPlus_Entities_DiscordForumTag_"></a>RemoveTag\(DiscordForumTag\)

Removes a tag from the post.

```csharp
public ForumPostBuilder RemoveTag(DiscordForumTag tag)
```

#### Parameters

`tag` [DiscordForumTag](DSharpPlus.Entities.DiscordForumTag.md)

#### Returns

[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

### <a id="DSharpPlus_Entities_ForumPostBuilder_WithAutoArchiveDuration_DSharpPlus_AutoArchiveDuration_"></a>WithAutoArchiveDuration\(AutoArchiveDuration\)

Sets the auto archive duration for the post.

```csharp
public ForumPostBuilder WithAutoArchiveDuration(AutoArchiveDuration autoArchiveDuration)
```

#### Parameters

`autoArchiveDuration` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The duration in which the post will automatically archive

#### Returns

[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

The builder to chain calls with

### <a id="DSharpPlus_Entities_ForumPostBuilder_WithMessage_DSharpPlus_Entities_DiscordMessageBuilder_"></a>WithMessage\(DiscordMessageBuilder\)

Sets the message to initiate the forum post with.

```csharp
public ForumPostBuilder WithMessage(DiscordMessageBuilder message)
```

#### Parameters

`message` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The message to start the post with.

#### Returns

[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

The builder to chain calls with.

### <a id="DSharpPlus_Entities_ForumPostBuilder_WithName_System_String_"></a>WithName\(string\)

Sets the name (or title) of the post.

```csharp
public ForumPostBuilder WithName(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the post.

#### Returns

[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

The builder to chain calls with

### <a id="DSharpPlus_Entities_ForumPostBuilder_WithSlowMode_System_Int32_"></a>WithSlowMode\(int\)

Sets slowmode for the post.

```csharp
public ForumPostBuilder WithSlowMode(int slowMode)
```

#### Parameters

`slowMode` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The time in seconds to apply

#### Returns

[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

### <a id="DSharpPlus_Entities_ForumPostBuilder_WithSlowMode_System_TimeSpan_"></a>WithSlowMode\(TimeSpan\)

Sets slow mode for the post.

```csharp
public ForumPostBuilder WithSlowMode(TimeSpan slowMode)
```

#### Parameters

`slowMode` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

The slowmode delay to set.

#### Returns

[ForumPostBuilder](DSharpPlus.Entities.ForumPostBuilder.md)

The builder to chain calls with.

