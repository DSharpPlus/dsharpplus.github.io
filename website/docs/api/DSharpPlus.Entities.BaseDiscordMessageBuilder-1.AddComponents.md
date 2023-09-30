# Method AddComponents

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddComponents_DSharpPlus_Entities_DiscordComponent___"></a>AddComponents\(params DiscordComponent\[\]\)

Adds a row of components to a message, up to 5 components per row, and up to 5 rows per message.

```csharp
public T AddComponents(params DiscordComponent[] components)
```

### Parameters

`components` [DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\[\]

The components to add to the message.

### Returns

T

The current builder to be chained.

### Exceptions

[ArgumentOutOfRangeException](https://learn.microsoft.com/dotnet/api/system.argumentoutofrangeexception)

No components were passed.

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddComponents_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordActionRowComponent__"></a>AddComponents\(IEnumerable<DiscordActionRowComponent\>\)

Appends several rows of components to the message

```csharp
public T AddComponents(IEnumerable<DiscordActionRowComponent> components)
```

### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)\>

The rows of components to add, holding up to five each.

### Returns

T

## <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddComponents_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordComponent__"></a>AddComponents\(IEnumerable<DiscordComponent\>\)

Adds a row of components to a message, up to 5 components per row, and up to 5 rows per message.

```csharp
public T AddComponents(IEnumerable<DiscordComponent> components)
```

### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\>

The components to add to the message.

### Returns

T

The current builder to be chained.

### Exceptions

[ArgumentOutOfRangeException](https://learn.microsoft.com/dotnet/api/system.argumentoutofrangeexception)

No components were passed.

