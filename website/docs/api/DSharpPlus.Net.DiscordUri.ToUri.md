# Method ToUri

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Net_DiscordUri_ToUri"></a>ToUri\(\)

Converts this DiscordUri into a canonical representation of a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref> if it can be represented as
such, throwing an exception otherwise.

```csharp
public Uri ToUri()
```

### Returns

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

A canonical representation of this DiscordUri.

### Exceptions

[UriFormatException](https://learn.microsoft.com/dotnet/api/system.uriformatexception)

If <xref href="DSharpPlus.Net.DiscordUri.Type" data-throw-if-not-resolved="false"></xref> is not <xref href="DSharpPlus.Net.DiscordUriType.Standard" data-throw-if-not-resolved="false"></xref>, as
    that would mean creating an invalid Uri, which would result in loss of data.

