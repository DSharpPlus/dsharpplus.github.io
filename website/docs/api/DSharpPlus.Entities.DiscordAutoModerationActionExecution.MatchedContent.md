# Property MatchedContent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_MatchedContent"></a>MatchedContent

Gets the substring in content that triggered the rule.

```csharp
[JsonProperty("matched_content", NullValueHandling = NullValueHandling.Ignore)]
public string? MatchedContent { get; }
```

### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### Remarks

<xref href="DSharpPlus.DiscordIntents.MessageContents" data-throw-if-not-resolved="false"></xref> is required to not get an empty value.

