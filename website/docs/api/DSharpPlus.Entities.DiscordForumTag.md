# Class DiscordForumTag

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordForumTag : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordForumTag](DSharpPlus.Entities.DiscordForumTag.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordForumTag_EmojiId"></a>EmojiId

Gets the Id of the emoji for this tag, if applicable.

```csharp
[JsonProperty("emoji_id")]
public ulong? EmojiId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordForumTag_EmojiName"></a>EmojiName

Gets the unicode emoji for this tag, if applicable.

```csharp
[JsonProperty("emoji_name")]
public string EmojiName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordForumTag_Moderated"></a>Moderated

Gets whether this tag is moderated. Moderated tags can only be applied by users with the <xref href="DSharpPlus.Permissions.ManageThreads" data-throw-if-not-resolved="false"></xref> permission.

```csharp
[JsonProperty("moderated")]
public bool Moderated { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordForumTag_Name"></a>Name

Gets the name of this tag.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

