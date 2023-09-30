# Class DiscordEmoji

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord emoji.

```csharp
public class DiscordEmoji : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

###### Derived

[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmoji_IsAnimated"></a>IsAnimated

Gets whether this emoji is animated.

```csharp
[JsonProperty("animated")]
public bool IsAnimated { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordEmoji_IsAvailable"></a>IsAvailable

Gets whether the emoji is available for use.
An emoji may not be available due to loss of server boost.

```csharp
[JsonProperty("available", NullValueHandling = NullValueHandling.Ignore)]
public bool IsAvailable { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordEmoji_IsManaged"></a>IsManaged

Gets whether this emoji is managed by an integration.

```csharp
[JsonProperty("managed")]
public bool IsManaged { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordEmoji_Name"></a>Name

Gets the name of this emoji.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmoji_RequiresColons"></a>RequiresColons

Gets whether this emoji requires colons to use.

```csharp
[JsonProperty("require_colons")]
public bool RequiresColons { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordEmoji_Roles"></a>Roles

Gets IDs the roles this emoji is enabled for.

```csharp
[JsonIgnore]
public IReadOnlyList<ulong> Roles { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

### <a id="DSharpPlus_Entities_DiscordEmoji_Url"></a>Url

Gets the image URL of this emoji.

```csharp
[JsonIgnore]
public string Url { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_Entities_DiscordEmoji_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordEmoji_Equals_DSharpPlus_Entities_DiscordEmoji_"></a>Equals\(DiscordEmoji\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordEmoji e)
```

#### Parameters

`e` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

<xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordEmoji_FromGuildEmote_DSharpPlus_BaseDiscordClient_System_UInt64_"></a>FromGuildEmote\(BaseDiscordClient, ulong\)

Creates an emoji object from a guild emote.

```csharp
public static DiscordEmoji FromGuildEmote(BaseDiscordClient client, ulong id)
```

#### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Id of the emote.

#### Returns

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Create <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### <a id="DSharpPlus_Entities_DiscordEmoji_FromName_DSharpPlus_BaseDiscordClient_System_String_System_Boolean_"></a>FromName\(BaseDiscordClient, string, bool\)

Creates an emoji object from emote name that includes colons (eg. :thinking:). This method also supports
skin tone variations (eg. :ok_hand::skin-tone-2:), standard emoticons (eg. :D), as well as guild emoji
(still specified by :name:).

```csharp
public static DiscordEmoji FromName(BaseDiscordClient client, string name, bool includeGuilds = true)
```

#### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the emote to find, including colons (eg. :thinking:).

`includeGuilds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Should guild emojis be included in the search.

#### Returns

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Create <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### <a id="DSharpPlus_Entities_DiscordEmoji_FromUnicode_DSharpPlus_BaseDiscordClient_System_String_"></a>FromUnicode\(BaseDiscordClient, string\)

Creates an emoji object from a unicode entity.

```csharp
public static DiscordEmoji FromUnicode(BaseDiscordClient client, string unicodeEntity)
```

#### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`unicodeEntity` [string](https://learn.microsoft.com/dotnet/api/system.string)

Unicode entity to create the object from.

#### Returns

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Create <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### <a id="DSharpPlus_Entities_DiscordEmoji_FromUnicode_System_String_"></a>FromUnicode\(string\)

Creates an emoji object from a unicode entity.

```csharp
public static DiscordEmoji FromUnicode(string unicodeEntity)
```

#### Parameters

`unicodeEntity` [string](https://learn.microsoft.com/dotnet/api/system.string)

Unicode entity to create the object from.

#### Returns

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Create <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### <a id="DSharpPlus_Entities_DiscordEmoji_GetDiscordName"></a>GetDiscordName\(\)

Gets emoji's name in non-Unicode format (eg. :thinking: instead of the Unicode representation of the emoji).

```csharp
public string GetDiscordName()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmoji_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordEmoji_IsValidUnicode_System_String_"></a>IsValidUnicode\(string\)

Checks whether specified unicode entity is a valid unicode emoji.

```csharp
public static bool IsValidUnicode(string unicodeEntity)
```

#### Parameters

`unicodeEntity` [string](https://learn.microsoft.com/dotnet/api/system.string)

Entity to check.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether it's a valid emoji.

### <a id="DSharpPlus_Entities_DiscordEmoji_ToString"></a>ToString\(\)

Returns a string representation of this emoji.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this emoji.

### <a id="DSharpPlus_Entities_DiscordEmoji_TryFromGuildEmote_DSharpPlus_BaseDiscordClient_System_UInt64_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromGuildEmote\(BaseDiscordClient, ulong, out DiscordEmoji\)

Attempts to create an emoji object from a guild emote.

```csharp
public static bool TryFromGuildEmote(BaseDiscordClient client, ulong id, out DiscordEmoji emoji)
```

#### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Id of the emote.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

### <a id="DSharpPlus_Entities_DiscordEmoji_TryFromName_DSharpPlus_BaseDiscordClient_System_String_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromName\(BaseDiscordClient, string, out DiscordEmoji\)

Attempts to create an emoji object from emote name that includes colons (eg. :thinking:). This method also
supports skin tone variations (eg. :ok_hand::skin-tone-2:), standard emoticons (eg. :D), as well as guild
emoji (still specified by :name:).

```csharp
public static bool TryFromName(BaseDiscordClient client, string name, out DiscordEmoji emoji)
```

#### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the emote to find, including colons (eg. :thinking:).

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

### <a id="DSharpPlus_Entities_DiscordEmoji_TryFromName_DSharpPlus_BaseDiscordClient_System_String_System_Boolean_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromName\(BaseDiscordClient, string, bool, out DiscordEmoji\)

Attempts to create an emoji object from emote name that includes colons (eg. :thinking:). This method also
supports skin tone variations (eg. :ok_hand::skin-tone-2:), standard emoticons (eg. :D), as well as guild
emoji (still specified by :name:).

```csharp
public static bool TryFromName(BaseDiscordClient client, string name, bool includeGuilds, out DiscordEmoji emoji)
```

#### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the emote to find, including colons (eg. :thinking:).

`includeGuilds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Should guild emojis be included in the search.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

### <a id="DSharpPlus_Entities_DiscordEmoji_TryFromUnicode_DSharpPlus_BaseDiscordClient_System_String_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromUnicode\(BaseDiscordClient, string, out DiscordEmoji\)

Attempts to create an emoji object from a unicode entity.

```csharp
public static bool TryFromUnicode(BaseDiscordClient client, string unicodeEntity, out DiscordEmoji emoji)
```

#### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`unicodeEntity` [string](https://learn.microsoft.com/dotnet/api/system.string)

Unicode entity to create the object from.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

### <a id="DSharpPlus_Entities_DiscordEmoji_TryFromUnicode_System_String_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromUnicode\(string, out DiscordEmoji\)

Attempts to create an emoji object from a unicode entity.

```csharp
public static bool TryFromUnicode(string unicodeEntity, out DiscordEmoji emoji)
```

#### Parameters

`unicodeEntity` [string](https://learn.microsoft.com/dotnet/api/system.string)

Unicode entity to create the object from.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

## Operators

### <a id="DSharpPlus_Entities_DiscordEmoji_op_Equality_DSharpPlus_Entities_DiscordEmoji_DSharpPlus_Entities_DiscordEmoji_"></a>operator ==\(DiscordEmoji, DiscordEmoji\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordEmoji e1, DiscordEmoji e2)
```

#### Parameters

`e1` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

First emoji to compare.

`e2` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Second emoji to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two emoji are equal.

### <a id="DSharpPlus_Entities_DiscordEmoji_op_Implicit_DSharpPlus_Entities_DiscordEmoji__System_String"></a>implicit operator string\(DiscordEmoji\)

Implicitly converts this emoji to its string representation.

```csharp
public static implicit operator string(DiscordEmoji e1)
```

#### Parameters

`e1` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji to convert.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmoji_op_Inequality_DSharpPlus_Entities_DiscordEmoji_DSharpPlus_Entities_DiscordEmoji_"></a>operator \!=\(DiscordEmoji, DiscordEmoji\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordEmoji e1, DiscordEmoji e2)
```

#### Parameters

`e1` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

First emoji to compare.

`e2` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Second emoji to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two emoji are not equal.

