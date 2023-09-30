# Property MentionedRoles

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_MentionedRoles"></a>MentionedRoles

Gets the collection of mentioned roles.

```csharp
public IReadOnlyList<DiscordRole> MentionedRoles { get; }
```

### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### Remarks

Only shows the mentioned roles from <xref href="DSharpPlus.DiscordClient.MessageCreated" data-throw-if-not-resolved="false"></xref>. EDITS ARE NOT INCLUDED.

