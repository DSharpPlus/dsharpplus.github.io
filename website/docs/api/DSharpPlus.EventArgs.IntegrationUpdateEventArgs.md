# Class IntegrationUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.IntegrationUpdated" data-throw-if-not-resolved="false"></xref>

```csharp
public sealed class IntegrationUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[IntegrationUpdateEventArgs](DSharpPlus.EventArgs.IntegrationUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_IntegrationUpdateEventArgs_Guild"></a>Guild

Gets the guild the integration was updated in.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_IntegrationUpdateEventArgs_Integration"></a>Integration

Gets the integration.

```csharp
public DiscordIntegration Integration { get; }
```

#### Property Value

[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

