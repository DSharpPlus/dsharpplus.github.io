# Class ChannelTypesAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Defines allowed channel types for a channel parameter.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = false)]
public class ChannelTypesAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[ChannelTypesAttribute](DSharpPlus.SlashCommands.ChannelTypesAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_ChannelTypesAttribute__ctor_DSharpPlus_ChannelType___"></a>ChannelTypesAttribute\(params ChannelType\[\]\)

Defines allowed channel types for a channel parameter.

```csharp
public ChannelTypesAttribute(params ChannelType[] channelTypes)
```

#### Parameters

`channelTypes` [ChannelType](DSharpPlus.ChannelType.md)\[\]

The channel types to allow.

## Properties

### <a id="DSharpPlus_SlashCommands_ChannelTypesAttribute_ChannelTypes"></a>ChannelTypes

Allowed channel types.

```csharp
public IEnumerable<ChannelType> ChannelTypes { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ChannelType](DSharpPlus.ChannelType.md)\>

