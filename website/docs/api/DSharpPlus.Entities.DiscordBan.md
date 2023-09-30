# Class DiscordBan

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord ban

```csharp
public class DiscordBan
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordBan](DSharpPlus.Entities.DiscordBan.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordBan_Reason"></a>Reason

Gets the reason for the ban

```csharp
[JsonProperty("reason", NullValueHandling = NullValueHandling.Ignore)]
public string Reason { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordBan_User"></a>User

Gets the banned user

```csharp
[JsonIgnore]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

