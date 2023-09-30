# Constructor DiscordComponentEmoji

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordComponentEmoji__ctor"></a>DiscordComponentEmoji\(\)

Constructs a new component emoji to add to a <xref href="DSharpPlus.Entities.DiscordComponent" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordComponentEmoji()
```

## <a id="DSharpPlus_Entities_DiscordComponentEmoji__ctor_System_UInt64_"></a>DiscordComponentEmoji\(ulong\)

Constructs a new component emoji from an emoji Id.

```csharp
public DiscordComponentEmoji(ulong id)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The Id of the emoji to use. Any valid emoji Id can be passed.

## <a id="DSharpPlus_Entities_DiscordComponentEmoji__ctor_System_String_"></a>DiscordComponentEmoji\(string\)

Constructs a new component emoji from unicode.

```csharp
public DiscordComponentEmoji(string name)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The unicode emoji to set.

## <a id="DSharpPlus_Entities_DiscordComponentEmoji__ctor_DSharpPlus_Entities_DiscordEmoji_"></a>DiscordComponentEmoji\(DiscordEmoji\)

Constructs a new component emoji from an existing <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordComponentEmoji(DiscordEmoji emoji)
```

### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to use.

