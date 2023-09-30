# Property ExemptRoles

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordAutoModerationRule_ExemptRoles"></a>ExemptRoles

Gets ids of roles that will not trigger the rule.

```csharp
[JsonProperty("exempt_roles", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<ulong>? ExemptRoles { get; }
```

### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>?

### Remarks

Maximum of 20.

