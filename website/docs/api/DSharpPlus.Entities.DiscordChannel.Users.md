# Property Users

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_Users"></a>Users

Gets the list of members currently in the channel (if voice channel), or members who can see the channel (otherwise).

```csharp
[JsonIgnore]
public virtual IReadOnlyList<DiscordMember> Users { get; }
```

### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

