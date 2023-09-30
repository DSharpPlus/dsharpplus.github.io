# Class DiscordEmbedBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Constructs embeds.

```csharp
public sealed class DiscordEmbedBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder__ctor"></a>DiscordEmbedBuilder\(\)

Constructs a new empty embed builder.

```csharp
public DiscordEmbedBuilder()
```

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder__ctor_DSharpPlus_Entities_DiscordEmbed_"></a>DiscordEmbedBuilder\(DiscordEmbed\)

Constructs a new embed builder using another embed as prototype.

```csharp
public DiscordEmbedBuilder(DiscordEmbed original)
```

#### Parameters

`original` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to use as prototype.

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Author"></a>Author

Gets or sets the embed's author.

```csharp
public DiscordEmbedBuilder.EmbedAuthor Author { get; set; }
```

#### Property Value

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md).[EmbedAuthor](DSharpPlus.Entities.DiscordEmbedBuilder.EmbedAuthor.md)

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Color"></a>Color

Gets or sets the embed's color.

```csharp
public Optional<DiscordColor> Color { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordColor](DSharpPlus.Entities.DiscordColor.md)\>

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Description"></a>Description

Gets or sets the embed's description.

```csharp
public string Description { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Fields"></a>Fields

Gets the embed's fields.

```csharp
public IReadOnlyList<DiscordEmbedField> Fields { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordEmbedField](DSharpPlus.Entities.DiscordEmbedField.md)\>

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Footer"></a>Footer

Gets or sets the embed's footer.

```csharp
public DiscordEmbedBuilder.EmbedFooter Footer { get; set; }
```

#### Property Value

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md).[EmbedFooter](DSharpPlus.Entities.DiscordEmbedBuilder.EmbedFooter.md)

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_ImageUrl"></a>ImageUrl

Gets or sets the embed's image url.

```csharp
public string ImageUrl { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Thumbnail"></a>Thumbnail

Gets or sets the embed's thumbnail.

```csharp
public DiscordEmbedBuilder.EmbedThumbnail Thumbnail { get; set; }
```

#### Property Value

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md).[EmbedThumbnail](DSharpPlus.Entities.DiscordEmbedBuilder.EmbedThumbnail.md)

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Timestamp"></a>Timestamp

Gets or sets the embed's timestamp.

```csharp
public DateTimeOffset? Timestamp { get; set; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Title"></a>Title

Gets or sets the embed's title.

```csharp
public string Title { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Url"></a>Url

Gets or sets the url for the embed's title.

```csharp
public string Url { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_AddField_System_String_System_String_System_Boolean_"></a>AddField\(string, string, bool\)

Adds a field to this embed.

```csharp
public DiscordEmbedBuilder AddField(string name, string value, bool inline = false)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the field to add.

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Value of the field to add.

`inline` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the field is to be inline or not.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_Build"></a>Build\(\)

Constructs a new embed from data supplied to this builder.

```csharp
public DiscordEmbed Build()
```

#### Returns

[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

New discord embed.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_ClearFields"></a>ClearFields\(\)

Removes all fields from this embed.

```csharp
public DiscordEmbedBuilder ClearFields()
```

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_RemoveFieldAt_System_Int32_"></a>RemoveFieldAt\(int\)

Removes a field of the specified index from this embed.

```csharp
public DiscordEmbedBuilder RemoveFieldAt(int index)
```

#### Parameters

`index` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Index of the field to remove.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_RemoveFieldRange_System_Int32_System_Int32_"></a>RemoveFieldRange\(int, int\)

Removes fields of the specified range from this embed.

```csharp
public DiscordEmbedBuilder RemoveFieldRange(int index, int count)
```

#### Parameters

`index` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Index of the first field to remove.

`count` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of fields to remove.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithAuthor_System_String_System_String_System_String_"></a>WithAuthor\(string, string, string\)

Sets the embed's author.

```csharp
public DiscordEmbedBuilder WithAuthor(string name = null, string url = null, string iconUrl = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Author's name.

`url` [string](https://learn.microsoft.com/dotnet/api/system.string)

Author's url.

`iconUrl` [string](https://learn.microsoft.com/dotnet/api/system.string)

Author icon's url.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithColor_DSharpPlus_Entities_DiscordColor_"></a>WithColor\(DiscordColor\)

Sets the embed's color.

```csharp
public DiscordEmbedBuilder WithColor(DiscordColor color)
```

#### Parameters

`color` [DiscordColor](DSharpPlus.Entities.DiscordColor.md)

Embed color to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithDescription_System_String_"></a>WithDescription\(string\)

Sets the embed's description.

```csharp
public DiscordEmbedBuilder WithDescription(string description)
```

#### Parameters

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithFooter_System_String_System_String_"></a>WithFooter\(string, string\)

Sets the embed's footer.

```csharp
public DiscordEmbedBuilder WithFooter(string text = null, string iconUrl = null)
```

#### Parameters

`text` [string](https://learn.microsoft.com/dotnet/api/system.string)

Footer's text.

`iconUrl` [string](https://learn.microsoft.com/dotnet/api/system.string)

Footer icon's url.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithImageUrl_System_String_"></a>WithImageUrl\(string\)

Sets the embed's image url.

```csharp
public DiscordEmbedBuilder WithImageUrl(string url)
```

#### Parameters

`url` [string](https://learn.microsoft.com/dotnet/api/system.string)

Image url to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithImageUrl_System_Uri_"></a>WithImageUrl\(Uri\)

Sets the embed's image url.

```csharp
public DiscordEmbedBuilder WithImageUrl(Uri url)
```

#### Parameters

`url` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

Image url to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithThumbnail_System_String_System_Int32_System_Int32_"></a>WithThumbnail\(string, int, int\)

Sets the embed's thumbnail.

```csharp
public DiscordEmbedBuilder WithThumbnail(string url, int height = 0, int width = 0)
```

#### Parameters

`url` [string](https://learn.microsoft.com/dotnet/api/system.string)

Thumbnail url to set.

`height` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The height of the thumbnail to set.

`width` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The width of the thumbnail to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithThumbnail_System_Uri_System_Int32_System_Int32_"></a>WithThumbnail\(Uri, int, int\)

Sets the embed's thumbnail.

```csharp
public DiscordEmbedBuilder WithThumbnail(Uri url, int height = 0, int width = 0)
```

#### Parameters

`url` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

Thumbnail url to set.

`height` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The height of the thumbnail to set.

`width` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The width of the thumbnail to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithTimestamp_System_Nullable_System_DateTimeOffset__"></a>WithTimestamp\(DateTimeOffset?\)

Sets the embed's timestamp.

```csharp
public DiscordEmbedBuilder WithTimestamp(DateTimeOffset? timestamp)
```

#### Parameters

`timestamp` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Timestamp to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithTimestamp_System_Nullable_System_DateTime__"></a>WithTimestamp\(DateTime?\)

Sets the embed's timestamp.

```csharp
public DiscordEmbedBuilder WithTimestamp(DateTime? timestamp)
```

#### Parameters

`timestamp` [DateTime](https://learn.microsoft.com/dotnet/api/system.datetime)?

Timestamp to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithTimestamp_System_UInt64_"></a>WithTimestamp\(ulong\)

Sets the embed's timestamp based on a snowflake.

```csharp
public DiscordEmbedBuilder WithTimestamp(ulong snowflake)
```

#### Parameters

`snowflake` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Snowflake to calculate timestamp from.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithTitle_System_String_"></a>WithTitle\(string\)

Sets the embed's title.

```csharp
public DiscordEmbedBuilder WithTitle(string title)
```

#### Parameters

`title` [string](https://learn.microsoft.com/dotnet/api/system.string)

Title to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithUrl_System_String_"></a>WithUrl\(string\)

Sets the embed's title url.

```csharp
public DiscordEmbedBuilder WithUrl(string url)
```

#### Parameters

`url` [string](https://learn.microsoft.com/dotnet/api/system.string)

Title url to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_WithUrl_System_Uri_"></a>WithUrl\(Uri\)

Sets the embed's title url.

```csharp
public DiscordEmbedBuilder WithUrl(Uri url)
```

#### Parameters

`url` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

Title url to set.

#### Returns

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

This embed builder.

## Operators

### <a id="DSharpPlus_Entities_DiscordEmbedBuilder_op_Implicit_DSharpPlus_Entities_DiscordEmbedBuilder__DSharpPlus_Entities_DiscordEmbed"></a>implicit operator DiscordEmbed\(DiscordEmbedBuilder\)

Implicitly converts this builder to an embed.

```csharp
public static implicit operator DiscordEmbed(DiscordEmbedBuilder builder)
```

#### Parameters

`builder` [DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

Builder to convert.

#### Returns

[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

