# Class Formatter

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Contains markdown formatting helpers.

```csharp
public static class Formatter
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Formatter](DSharpPlus.Formatter.md)

## Methods

### <a id="DSharpPlus_Formatter_AttachedImageUrl_System_String_"></a>AttachedImageUrl\(string\)

Creates a url for using attachments in embeds. This can only be used as an Image URL, Thumbnail URL, Author icon URL or Footer icon URL.

```csharp
public static string AttachedImageUrl(string filename)
```

#### Parameters

`filename` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of attached image to display

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Formatter_BlockCode_System_String_System_String_"></a>BlockCode\(string, string\)

Creates a block of code.

```csharp
public static string BlockCode(string content, string language = "")
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Contents of the block.

`language` [string](https://learn.microsoft.com/dotnet/api/system.string)

Language to use for highlighting.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted block of code.

### <a id="DSharpPlus_Formatter_Bold_System_String_"></a>Bold\(string\)

Creates bold text.

```csharp
public static string Bold(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to bolden.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted text.

### <a id="DSharpPlus_Formatter_Colorize_System_String_DSharpPlus_AnsiColor___"></a>Colorize\(string, params AnsiColor\[\]\)

Colorizes text based using ANSI escape codes. Escape codes are only properly rendered in code blocks. Resets are inserted automatically.

```csharp
public static string Colorize(string text, params AnsiColor[] styles)
```

#### Parameters

`text` [string](https://learn.microsoft.com/dotnet/api/system.string)

The text to colorize.

`styles` [AnsiColor](DSharpPlus.AnsiColor.md)\[\]

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Formatter_EmbedlessUrl_System_Uri_"></a>EmbedlessUrl\(Uri\)

Creates a URL that won't create a link preview.

```csharp
public static string EmbedlessUrl(Uri url)
```

#### Parameters

`url` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

Url to prevent from being previewed.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted url.

### <a id="DSharpPlus_Formatter_Emoji_DSharpPlus_Entities_DiscordEmoji_"></a>Emoji\(DiscordEmoji\)

Creates a custom emoji string.

```csharp
public static string Emoji(DiscordEmoji emoji)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji to display.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted emoji.

### <a id="DSharpPlus_Formatter_InlineCode_System_String_"></a>InlineCode\(string\)

Creates inline code snippet.

```csharp
public static string InlineCode(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Contents of the snippet.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted inline code snippet.

### <a id="DSharpPlus_Formatter_Italic_System_String_"></a>Italic\(string\)

Creates italicized text.

```csharp
public static string Italic(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to italicize.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted text.

### <a id="DSharpPlus_Formatter_MaskedUrl_System_String_System_Uri_System_String_"></a>MaskedUrl\(string, Uri, string\)

Creates a masked link. This link will display as specified text, and alternatively provided alt text. This can only be used in embeds.

```csharp
public static string MaskedUrl(string text, Uri url, string alt_text = "")
```

#### Parameters

`text` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to display the link as.

`url` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

Url that the link will lead to.

`alt\_text` [string](https://learn.microsoft.com/dotnet/api/system.string)

Alt text to display on hover.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted url.

### <a id="DSharpPlus_Formatter_Mention_DSharpPlus_Entities_DiscordUser_System_Boolean_"></a>Mention\(DiscordUser, bool\)

Creates a mention for specified user or member. Can optionally specify to resolve nicknames.

```csharp
public static string Mention(DiscordUser user, bool nickname = false)
```

#### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to create mention for.

`nickname` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the mention should resolve nicknames or not.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

### <a id="DSharpPlus_Formatter_Mention_DSharpPlus_Entities_DiscordChannel_"></a>Mention\(DiscordChannel\)

Creates a mention for specified channel.

```csharp
public static string Mention(DiscordChannel channel)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to mention.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

### <a id="DSharpPlus_Formatter_Mention_DSharpPlus_Entities_DiscordRole_"></a>Mention\(DiscordRole\)

Creates a mention for specified role.

```csharp
public static string Mention(DiscordRole role)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Role to mention.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

### <a id="DSharpPlus_Formatter_Mention_DSharpPlus_Entities_DiscordApplicationCommand_"></a>Mention\(DiscordApplicationCommand\)

Creates a mention for specified application command.

```csharp
public static string Mention(DiscordApplicationCommand command)
```

#### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

Application command to mention.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

### <a id="DSharpPlus_Formatter_Sanitize_System_String_"></a>Sanitize\(string\)

Escapes all markdown formatting from specified text.

```csharp
public static string Sanitize(string text)
```

#### Parameters

`text` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to sanitize.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Sanitized text.

### <a id="DSharpPlus_Formatter_Spoiler_System_String_"></a>Spoiler\(string\)

Creates spoiler from text.

```csharp
public static string Spoiler(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to spoilerize.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted text.

### <a id="DSharpPlus_Formatter_Strike_System_String_"></a>Strike\(string\)

Creates strikethrough text.

```csharp
public static string Strike(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to strikethrough.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted text.

### <a id="DSharpPlus_Formatter_Strip_System_String_"></a>Strip\(string\)

Removes all markdown formatting from specified text.

```csharp
public static string Strip(string text)
```

#### Parameters

`text` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to strip of formatting.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatting-stripped text.

### <a id="DSharpPlus_Formatter_Timestamp_System_TimeSpan_DSharpPlus_TimestampFormat_"></a>Timestamp\(TimeSpan, TimestampFormat\)

Creates a rendered timestamp.

```csharp
public static string Timestamp(TimeSpan time, TimestampFormat format = TimestampFormat.RelativeTime)
```

#### Parameters

`time` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

The time from now.

`format` [TimestampFormat](DSharpPlus.TimestampFormat.md)

The format to render the timestamp in. Defaults to relative.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A formatted timestamp.

### <a id="DSharpPlus_Formatter_Timestamp_System_DateTime_DSharpPlus_TimestampFormat_"></a>Timestamp\(DateTime, TimestampFormat\)

Creates a rendered timestamp.

```csharp
public static string Timestamp(DateTime time, TimestampFormat format = TimestampFormat.RelativeTime)
```

#### Parameters

`time` [DateTime](https://learn.microsoft.com/dotnet/api/system.datetime)

The time from now.

`format` [TimestampFormat](DSharpPlus.TimestampFormat.md)

The format to render the timestamp in. Defaults to relative.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A formatted timestamp.

### <a id="DSharpPlus_Formatter_Timestamp_System_DateTimeOffset_DSharpPlus_TimestampFormat_"></a>Timestamp\(DateTimeOffset, TimestampFormat\)

Creates a rendered timestamp.

```csharp
public static string Timestamp(DateTimeOffset time, TimestampFormat format = TimestampFormat.RelativeTime)
```

#### Parameters

`time` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

Timestamp to format.

`format` [TimestampFormat](DSharpPlus.TimestampFormat.md)

The format to render the timestamp in. Defaults to relative.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A formatted timestamp.

### <a id="DSharpPlus_Formatter_ToBigHeader_System_String_"></a>ToBigHeader\(string\)

Creates a big header.

```csharp
public static string ToBigHeader(string value)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to display as a big header.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted header.

### <a id="DSharpPlus_Formatter_ToMediumHeader_System_String_"></a>ToMediumHeader\(string\)

Creates a medium header.

```csharp
public static string ToMediumHeader(string value)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to display as a medium header.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted header.

### <a id="DSharpPlus_Formatter_ToSmallHeader_System_String_"></a>ToSmallHeader\(string\)

Creates a small header.

```csharp
public static string ToSmallHeader(string value)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to display as a small header.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted header.

### <a id="DSharpPlus_Formatter_Underline_System_String_"></a>Underline\(string\)

Creates underlined text.

```csharp
public static string Underline(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to underline.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted text.

