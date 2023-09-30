# Method AddComponents

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddComponents_DSharpPlus_Entities_DiscordComponent___"></a>AddComponents\(params DiscordComponent\[\]\)

Adds components to this message. Each call should append to a new row.

```csharp
IDiscordMessageBuilder AddComponents(params DiscordComponent[] components)
```

### Parameters

`components` [DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\[\]

Components to add.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddComponents_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordComponent__"></a>AddComponents\(IEnumerable<DiscordComponent\>\)

Adds components to this message. Each call should append to a new row.

```csharp
IDiscordMessageBuilder AddComponents(IEnumerable<DiscordComponent> components)
```

### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\>

Components to add.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

## <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddComponents_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordActionRowComponent__"></a>AddComponents\(IEnumerable<DiscordActionRowComponent\>\)

Adds an action row component to this message.

```csharp
IDiscordMessageBuilder AddComponents(IEnumerable<DiscordActionRowComponent> components)
```

### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)\>

Action row to add to this message. Should contain child components.

### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

