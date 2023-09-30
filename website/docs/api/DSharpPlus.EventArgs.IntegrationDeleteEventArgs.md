# Class IntegrationDeleteEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.IntegrationDeleted" data-throw-if-not-resolved="false"></xref>

```csharp
public sealed class IntegrationDeleteEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[IntegrationDeleteEventArgs](DSharpPlus.EventArgs.IntegrationDeleteEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_IntegrationDeleteEventArgs_Applicationid"></a>Applicationid

Gets the id of the bot or OAuth2 application for the integration.

```csharp
public ulong? Applicationid { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_EventArgs_IntegrationDeleteEventArgs_Guild"></a>Guild

Gets the guild the integration was removed from.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_IntegrationDeleteEventArgs_IntegrationId"></a>IntegrationId

Gets the id of the integration.

```csharp
public ulong IntegrationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

