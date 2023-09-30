# Method GetGatewayInfoAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_BaseDiscordClient_GetGatewayInfoAsync_System_String_"></a>GetGatewayInfoAsync\(string\)

Gets the current gateway info for the provided token.
<p>If no value is provided, the configuration value will be used instead.</p>

```csharp
public Task<GatewayInfo> GetGatewayInfoAsync(string token = null)
```

### Parameters

`token` [string](https://learn.microsoft.com/dotnet/api/system.string)

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[GatewayInfo](DSharpPlus.Net.GatewayInfo.md)\>

A gateway info object.

