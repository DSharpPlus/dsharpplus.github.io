# Class DiscordComponentEmoji

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an emoji to add to a component.

```csharp
public sealed class DiscordComponentEmoji
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponentEmoji](DSharpPlus.Entities.DiscordComponentEmoji.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordComponentEmoji__ctor"></a>DiscordComponentEmoji\(\)

Constructs a new component emoji to add to a <xref href="DSharpPlus.Entities.DiscordComponent" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordComponentEmoji()
```

### <a id="DSharpPlus_Entities_DiscordComponentEmoji__ctor_System_UInt64_"></a>DiscordComponentEmoji\(ulong\)

Constructs a new component emoji from an emoji Id.

```csharp
public DiscordComponentEmoji(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The Id of the emoji to use. Any valid emoji Id can be passed.

### <a id="DSharpPlus_Entities_DiscordComponentEmoji__ctor_System_String_"></a>DiscordComponentEmoji\(string\)

Constructs a new component emoji from unicode.

```csharp
public DiscordComponentEmoji(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The unicode emoji to set.

### <a id="DSharpPlus_Entities_DiscordComponentEmoji__ctor_DSharpPlus_Entities_DiscordEmoji_"></a>DiscordComponentEmoji\(DiscordEmoji\)

Constructs a new component emoji from an existing <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordComponentEmoji(DiscordEmoji emoji)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to use.

## Properties

### <a id="DSharpPlus_Entities_DiscordComponentEmoji_Id"></a>Id

The Id of the emoji to use.

```csharp
[JsonProperty("id", NullValueHandling = NullValueHandling.Ignore)]
public ulong Id { get; set; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordComponentEmoji_Name"></a>Name

The name of the emoji to use. Ignored if <xref href="DSharpPlus.Entities.DiscordComponentEmoji.Id" data-throw-if-not-resolved="false"></xref> is set.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

