# Class DiscordMessageInteraction

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents the message interaction data sent when a message is an interaction response.

```csharp
public class DiscordMessageInteraction : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordMessageInteraction](DSharpPlus.Entities.DiscordMessageInteraction.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordMessageInteraction_Name"></a>Name

Gets the name of the <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageInteraction_Type"></a>Type

Gets the type of the interaction.

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public InteractionType Type { get; }
```

#### Property Value

[InteractionType](DSharpPlus.InteractionType.md)

### <a id="DSharpPlus_Entities_DiscordMessageInteraction_User"></a>User

Gets the user who invoked the interaction.

```csharp
[JsonProperty("user", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

