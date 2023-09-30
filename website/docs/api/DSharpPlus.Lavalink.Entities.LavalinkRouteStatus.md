# Class LavalinkRouteStatus

Namespace: [DSharpPlus.Lavalink.Entities](DSharpPlus.Lavalink.Entities.md)  
Assembly: DSharpPlus.Lavalink.dll

```csharp
public class LavalinkRouteStatus
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkRouteStatus](DSharpPlus.Lavalink.Entities.LavalinkRouteStatus.md)

## Properties

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatus_Class"></a>Class

Gets the route planner type.

```csharp
[JsonIgnore]
public LavalinkRoutePlannerType? Class { get; }
```

#### Property Value

[LavalinkRoutePlannerType](DSharpPlus.Lavalink.LavalinkRoutePlannerType.md)?

### <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatus_Details"></a>Details

Gets the details of the route planner.

```csharp
[JsonProperty("details", NullValueHandling = NullValueHandling.Ignore)]
public LavalinkRouteStatusDetails Details { get; }
```

#### Property Value

[LavalinkRouteStatusDetails](DSharpPlus.Lavalink.Entities.LavalinkRouteStatusDetails.md)

