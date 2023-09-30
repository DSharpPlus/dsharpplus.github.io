# Enum LavalinkRoutePlannerType

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

```csharp
public enum LavalinkRoutePlannerType
```

###### Extension Methods

[ExtensionMethods.GetName<LavalinkRoutePlannerType\>\(LavalinkRoutePlannerType\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`BalancingIpRoutePlanner = 2` 

Route planner that selects random IP addresses from the given block.

`NanoIpRoutePlanner = 3` 

Route planner that switches the IP on every clock update.

`RotatingIpRoutePlanner = 1` 

Route planner that switches the IP on ban.

`RotatingNanoIpRoutePlanner = 4` 

Route planner that switches the IP on every clock update and rotates to next IP block on a ban as a fallback.

