# Method GetInteractivity

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_ClientExtensions_GetInteractivity_DSharpPlus_DiscordClient_"></a>GetInteractivity\(DiscordClient\)

Retrieves the registered <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance for this client.

```csharp
public static InteractivityExtension GetInteractivity(this DiscordClient client)
```

### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

The client to retrieve an <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance from.

### Returns

[InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)

An existing <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance, or <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> if interactivity is not enabled for the <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> instance.

