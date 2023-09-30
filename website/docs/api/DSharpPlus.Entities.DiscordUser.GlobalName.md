# Property GlobalName

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordUser_GlobalName"></a>GlobalName

Gets this user's global display name.

```csharp
[JsonProperty("global_name", NullValueHandling = NullValueHandling.Ignore)]
public virtual string GlobalName { get; }
```

### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### Remarks

A global display name differs from a username in that it acts like a nickname, but is not specific to a single guild.
Nicknames in servers however still take precedence over global names, which take precedence over usernames.

