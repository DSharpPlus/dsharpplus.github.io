# Method GeneratePagesInContent

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_GeneratePagesInContent_System_String_DSharpPlus_Interactivity_Enums_SplitType_"></a>GeneratePagesInContent\(string, SplitType\)

Generates pages from a string, and puts them in message content.

```csharp
public IEnumerable<Page> GeneratePagesInContent(string input, SplitType splittype = SplitType.Character)
```

### Parameters

`input` [string](https://learn.microsoft.com/dotnet/api/system.string)

Input string.

`splittype` [SplitType](DSharpPlus.Interactivity.Enums.SplitType.md)

How to split input string.

### Returns

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

