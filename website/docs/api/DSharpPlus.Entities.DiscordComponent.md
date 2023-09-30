# Class DiscordComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

A component to attach to a message.

```csharp
[JsonConverter(typeof(DiscordComponentJsonConverter))]
public class DiscordComponent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)

###### Derived

[BaseDiscordSelectComponent](DSharpPlus.Entities.BaseDiscordSelectComponent.md), 
[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md), 
[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md), 
[DiscordLinkButtonComponent](DSharpPlus.Entities.DiscordLinkButtonComponent.md), 
[TextInputComponent](DSharpPlus.Entities.TextInputComponent.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordComponent_CustomId"></a>CustomId

The Id of this component, if applicable. Not applicable on ActionRow(s) and link buttons.

```csharp
[JsonProperty("custom_id", NullValueHandling = NullValueHandling.Ignore)]
public string CustomId { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordComponent_Type"></a>Type

The type of component this represents.

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public ComponentType Type { get; }
```

#### Property Value

[ComponentType](DSharpPlus.ComponentType.md)

