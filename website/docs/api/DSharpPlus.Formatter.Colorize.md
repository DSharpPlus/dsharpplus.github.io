# Method Colorize

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Formatter_Colorize_System_String_DSharpPlus_AnsiColor___"></a>Colorize\(string, params AnsiColor\[\]\)

Colorizes text based using ANSI escape codes. Escape codes are only properly rendered in code blocks. Resets are inserted automatically.

```csharp
public static string Colorize(string text, params AnsiColor[] styles)
```

### Parameters

`text` [string](https://learn.microsoft.com/dotnet/api/system.string)

The text to colorize.

`styles` [AnsiColor](DSharpPlus.AnsiColor.md)\[\]

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

