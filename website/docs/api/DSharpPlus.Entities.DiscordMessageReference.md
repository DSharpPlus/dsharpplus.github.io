# Class DiscordMessageReference

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents data from the original message.

```csharp
public class DiscordMessageReference
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordMessageReference](DSharpPlus.Entities.DiscordMessageReference.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordMessageReference_Channel"></a>Channel

Gets the channel of the original message.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordMessageReference_Guild"></a>Guild

Gets the guild of the original message.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordMessageReference_Message"></a>Message

Gets the original message.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordMessageReference_ToString"></a>ToString\(\)

Returns a string that represents the current object.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A string that represents the current object.

