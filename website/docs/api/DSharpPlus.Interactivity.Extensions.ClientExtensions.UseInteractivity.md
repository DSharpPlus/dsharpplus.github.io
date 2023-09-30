# Method UseInteractivity

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_ClientExtensions_UseInteractivity_DSharpPlus_DiscordClient_DSharpPlus_Interactivity_InteractivityConfiguration_"></a>UseInteractivity\(DiscordClient, InteractivityConfiguration\)

Enables interactivity for this <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> instance.

```csharp
public static InteractivityExtension UseInteractivity(this DiscordClient client, InteractivityConfiguration configuration = null)
```

### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

The client to enable interactivity for.

`configuration` [InteractivityConfiguration](DSharpPlus.Interactivity.InteractivityConfiguration.md)

A configuration instance. Default configuration values will be used if none is provided.

### Returns

[InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)

A brand new <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity has already been enabled for the client instance.

