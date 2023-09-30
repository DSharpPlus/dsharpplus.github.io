# Class LavalinkRouteStatusDetails

Namespace: [DSharpPlus.Lavalink.Entities](DSharpPlus.Lavalink.Entities.md)  
Assembly: DSharpPlus.Lavalink.dll

```csharp
public class LavalinkRouteStatusDetails
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkRouteStatusDetails](DSharpPlus.Lavalink.Entities.LavalinkRouteStatusDetails.md)

## Properties

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatusDetails_BlockIndex"></a>BlockIndex

Gets the information in which /64 block ips are chosen. This number increases on each ban.
<p>Only present in the <xref href="DSharpPlus.Lavalink.LavalinkRoutePlannerType.RotatingNanoIpRoutePlanner" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
[JsonProperty("blockIndex", NullValueHandling = NullValueHandling.Ignore)]
public string BlockIndex { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatusDetails_CurrentAddress"></a>CurrentAddress

Gets the current IP Address used by the planner.
<p>Only present in the <xref href="DSharpPlus.Lavalink.LavalinkRoutePlannerType.RotatingIpRoutePlanner" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
[JsonProperty("currentAddress", NullValueHandling = NullValueHandling.Ignore)]
public string CurrentAddress { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatusDetails_CurrentAddressIndex"></a>CurrentAddressIndex

Gets the current offset of the IP block.
<p>Only present in the <xref href="DSharpPlus.Lavalink.LavalinkRoutePlannerType.NanoIpRoutePlanner" data-throw-if-not-resolved="false"></xref> and the <xref href="DSharpPlus.Lavalink.LavalinkRoutePlannerType.RotatingNanoIpRoutePlanner" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
[JsonProperty("currentAddressIndex", NullValueHandling = NullValueHandling.Ignore)]
public long CurrentAddressIndex { get; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatusDetails_FailedAddresses"></a>FailedAddresses

Gets the collection of failed addresses.

```csharp
[JsonProperty("failingAddresses", NullValueHandling = NullValueHandling.Ignore)]
public IEnumerable<LavalinkFailedAddress> FailedAddresses { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[LavalinkFailedAddress](DSharpPlus.Lavalink.Entities.LavalinkFailedAddress.md)\>

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatusDetails_IpBlock"></a>IpBlock

Gets the details for the current IP block.

```csharp
[JsonProperty("ipBlock", NullValueHandling = NullValueHandling.Ignore)]
public LavalinkIpBlock IpBlock { get; }
```

#### Property Value

[LavalinkIpBlock](DSharpPlus.Lavalink.Entities.LavalinkIpBlock.md)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatusDetails_IpIndex"></a>IpIndex

Gets the current offset of the IP block.
<p>Only present in the <xref href="DSharpPlus.Lavalink.LavalinkRoutePlannerType.RotatingIpRoutePlanner" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
[JsonProperty("ipIndex", NullValueHandling = NullValueHandling.Ignore)]
public string IpIndex { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatusDetails_RotateIndex"></a>RotateIndex

Gets the number of rotations since the restart of Lavalink.
<p>Only present in the <xref href="DSharpPlus.Lavalink.LavalinkRoutePlannerType.RotatingIpRoutePlanner" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
[JsonProperty("rotateIndex", NullValueHandling = NullValueHandling.Ignore)]
public string RotateIndex { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

