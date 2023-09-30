# Class DiscordMessageActivity

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Rich Presence activity.

```csharp
public class DiscordMessageActivity
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordMessageActivity](DSharpPlus.Entities.DiscordMessageActivity.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordMessageActivity_PartyId"></a>PartyId

Gets the party id of the activity.

```csharp
[JsonProperty("party_id")]
public string PartyId { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageActivity_Type"></a>Type

Gets the activity type.

```csharp
[JsonProperty("type")]
public MessageActivityType Type { get; }
```

#### Property Value

[MessageActivityType](DSharpPlus.MessageActivityType.md)

