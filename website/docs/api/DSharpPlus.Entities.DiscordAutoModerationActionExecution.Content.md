# Property Content

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_Content"></a>Content

Gets the content of the message.

```csharp
[JsonProperty("content", NullValueHandling = NullValueHandling.Ignore)]
public string? Content { get; }
```

### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### Remarks

<xref href="DSharpPlus.DiscordIntents.MessageContents" data-throw-if-not-resolved="false"></xref> is required to not get an empty value.

