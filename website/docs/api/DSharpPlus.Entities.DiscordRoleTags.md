# Class DiscordRoleTags

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a discord role tags.

```csharp
public class DiscordRoleTags
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordRoleTags](DSharpPlus.Entities.DiscordRoleTags.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordRoleTags_BotId"></a>BotId

Gets the id of the bot this role belongs to.

```csharp
[JsonProperty("bot_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? BotId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordRoleTags_IntegrationId"></a>IntegrationId

Gets the id of the integration this role belongs to.

```csharp
[JsonProperty("integration_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? IntegrationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordRoleTags_IsPremiumSubscriber"></a>IsPremiumSubscriber

Gets whether this is the guild's premium subscriber role.

```csharp
[JsonIgnore]
public bool IsPremiumSubscriber { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

