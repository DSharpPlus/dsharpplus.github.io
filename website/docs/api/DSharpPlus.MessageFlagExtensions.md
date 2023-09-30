# Class MessageFlagExtensions

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

```csharp
public static class MessageFlagExtensions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[MessageFlagExtensions](DSharpPlus.MessageFlagExtensions.md)

## Methods

### <a id="DSharpPlus_MessageFlagExtensions_HasMessageFlag_DSharpPlus_MessageFlags_DSharpPlus_MessageFlags_"></a>HasMessageFlag\(MessageFlags, MessageFlags\)

Calculates whether these message flags contain a specific flag.

```csharp
public static bool HasMessageFlag(this MessageFlags baseFlags, MessageFlags flag)
```

#### Parameters

`baseFlags` [MessageFlags](DSharpPlus.MessageFlags.md)

The existing flags.

`flag` [MessageFlags](DSharpPlus.MessageFlags.md)

The flags to search for.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

