# Method MaskedUrl

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Formatter_MaskedUrl_System_String_System_Uri_System_String_"></a>MaskedUrl\(string, Uri, string\)

Creates a masked link. This link will display as specified text, and alternatively provided alt text. This can only be used in embeds.

```csharp
public static string MaskedUrl(string text, Uri url, string alt_text = "")
```

### Parameters

`text` [string](https://learn.microsoft.com/dotnet/api/system.string)

Text to display the link as.

`url` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

Url that the link will lead to.

`alt\_text` [string](https://learn.microsoft.com/dotnet/api/system.string)

Alt text to display on hover.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted url.

