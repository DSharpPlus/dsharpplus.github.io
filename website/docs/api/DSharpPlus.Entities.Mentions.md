# Class Mentions

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Contains static instances of common mention patterns.

```csharp
public static class Mentions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Mentions](DSharpPlus.Entities.Mentions.md)

## Properties

### <a id="DSharpPlus_Entities_Mentions_All"></a>All

All possible mentions - @everyone + @here, users, and roles.

```csharp
public static IEnumerable<IMention> All { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[IMention](DSharpPlus.Entities.IMention.md)\>

### <a id="DSharpPlus_Entities_Mentions_None"></a>None

No mentions allowed.

```csharp
public static IEnumerable<IMention> None { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[IMention](DSharpPlus.Entities.IMention.md)\>

