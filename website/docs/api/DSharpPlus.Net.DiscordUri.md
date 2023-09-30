# Class DiscordUri

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

An URI in a Discord embed doesn't necessarily conform to the RFC 3986. If it uses the <code>attachment://</code>
protocol, it mustn't contain a trailing slash to be interpreted correctly as an embed attachment reference by
Discord.

```csharp
[JsonConverter(typeof(DiscordUri.DiscordUriJsonConverter))]
public class DiscordUri
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordUri](DSharpPlus.Net.DiscordUri.md)

## Properties

### <a id="DSharpPlus_Net_DiscordUri_Type"></a>Type

The type of this URI.

```csharp
public DiscordUriType Type { get; }
```

#### Property Value

[DiscordUriType](DSharpPlus.Net.DiscordUriType.md)

## Methods

### <a id="DSharpPlus_Net_DiscordUri_ToString"></a>ToString\(\)

Returns a string representation of this DiscordUri.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

This DiscordUri, as a string.

### <a id="DSharpPlus_Net_DiscordUri_ToUri"></a>ToUri\(\)

Converts this DiscordUri into a canonical representation of a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref> if it can be represented as
such, throwing an exception otherwise.

```csharp
public Uri ToUri()
```

#### Returns

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

A canonical representation of this DiscordUri.

#### Exceptions

[UriFormatException](https://learn.microsoft.com/dotnet/api/system.uriformatexception)

If <xref href="DSharpPlus.Net.DiscordUri.Type" data-throw-if-not-resolved="false"></xref> is not <xref href="DSharpPlus.Net.DiscordUriType.Standard" data-throw-if-not-resolved="false"></xref>, as
    that would mean creating an invalid Uri, which would result in loss of data.

