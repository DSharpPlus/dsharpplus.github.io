# Class IntegrationCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.IntegrationCreated" data-throw-if-not-resolved="false"></xref>

```csharp
public sealed class IntegrationCreateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[IntegrationCreateEventArgs](DSharpPlus.EventArgs.IntegrationCreateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_IntegrationCreateEventArgs_Guild"></a>Guild

Gets the guild the integration was added to.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_IntegrationCreateEventArgs_Integration"></a>Integration

Gets the integration.

```csharp
public DiscordIntegration Integration { get; }
```

#### Property Value

[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

