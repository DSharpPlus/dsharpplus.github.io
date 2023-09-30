# Class DiscordInviteChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents the channel to which an invite is linked.

```csharp
public class DiscordInviteChannel : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordInviteChannel](DSharpPlus.Entities.DiscordInviteChannel.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordInviteChannel_Name"></a>Name

Gets the name of the channel.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteChannel_Type"></a>Type

Gets the type of the channel.

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public ChannelType Type { get; }
```

#### Property Value

[ChannelType](DSharpPlus.ChannelType.md)

