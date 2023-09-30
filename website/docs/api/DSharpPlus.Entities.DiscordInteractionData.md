# Class DiscordInteractionData

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents the inner data payload of a <xref href="DSharpPlus.Entities.DiscordInteraction" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class DiscordInteractionData : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordInteractionData](DSharpPlus.Entities.DiscordInteractionData.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordInteractionData_ComponentType"></a>ComponentType

The type of component that invoked this interaction, if applicable.

```csharp
[JsonProperty("component_type", NullValueHandling = NullValueHandling.Ignore)]
public ComponentType ComponentType { get; }
```

#### Property Value

[ComponentType](DSharpPlus.ComponentType.md)

### <a id="DSharpPlus_Entities_DiscordInteractionData_Components"></a>Components

Components on this interaction. Only applies to modal interactions.

```csharp
public IReadOnlyList<DiscordActionRowComponent> Components { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionData_CustomId"></a>CustomId

The Id of the component that invoked this interaction, or the Id of the modal the interaction was spawned from.

```csharp
[JsonProperty("custom_id", NullValueHandling = NullValueHandling.Ignore)]
public string CustomId { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInteractionData_Name"></a>Name

Gets the name of the invoked interaction.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInteractionData_Options"></a>Options

Gets the parameters and values of the invoked interaction.

```csharp
[JsonProperty("options", NullValueHandling = NullValueHandling.Ignore)]
public IEnumerable<DiscordInteractionDataOption> Options { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordInteractionDataOption](DSharpPlus.Entities.DiscordInteractionDataOption.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionData_Resolved"></a>Resolved

Gets the Discord snowflake objects resolved from this interaction's arguments.

```csharp
[JsonProperty("resolved", NullValueHandling = NullValueHandling.Ignore)]
public DiscordInteractionResolvedCollection Resolved { get; }
```

#### Property Value

[DiscordInteractionResolvedCollection](DSharpPlus.Entities.DiscordInteractionResolvedCollection.md)

### <a id="DSharpPlus_Entities_DiscordInteractionData_Title"></a>Title

The title of the modal, if applicable.

```csharp
[JsonProperty("title", NullValueHandling = NullValueHandling.Ignore)]
public string Title { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInteractionData_Type"></a>Type

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public ApplicationCommandType Type { get; }
```

#### Property Value

[ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

### <a id="DSharpPlus_Entities_DiscordInteractionData_Values"></a>Values

```csharp
[JsonProperty("values", NullValueHandling = NullValueHandling.Ignore)]
public string[] Values { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

