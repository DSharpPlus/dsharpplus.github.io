# Struct LavalinkFailedAddress

Namespace: [DSharpPlus.Lavalink.Entities](DSharpPlus.Lavalink.Entities.md)  
Assembly: DSharpPlus.Lavalink.dll

```csharp
public struct LavalinkFailedAddress
```

## Properties

### <a id="DSharpPlus_Lavalink_Entities_LavalinkFailedAddress_Address"></a>Address

Gets the failed address IP.

```csharp
[JsonProperty("address", NullValueHandling = NullValueHandling.Ignore)]
public readonly string Address { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkFailedAddress_FailingTime"></a>FailingTime

Gets the DateTime format of the failing address.

```csharp
[JsonProperty("failingTime", NullValueHandling = NullValueHandling.Ignore)]
public readonly string FailingTime { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkFailedAddress_FailingTimestamp"></a>FailingTimestamp

Gets the failing timestamp in miliseconds.

```csharp
[JsonProperty("failingTimestamp", NullValueHandling = NullValueHandling.Ignore)]
public readonly ulong FailingTimestamp { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

