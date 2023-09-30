# Property Members

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_Members"></a>Members

Gets a dictionary of all the members that belong to this guild. The dictionary's key is the member ID.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordMember> Members { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

