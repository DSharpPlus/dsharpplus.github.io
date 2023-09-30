# Class VoiceServerUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.VoiceServerUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class VoiceServerUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[VoiceServerUpdateEventArgs](DSharpPlus.EventArgs.VoiceServerUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_VoiceServerUpdateEventArgs_Endpoint"></a>Endpoint

Gets the new voice endpoint.

```csharp
public string Endpoint { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_VoiceServerUpdateEventArgs_Guild"></a>Guild

Gets the guild for which the update occurred.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_VoiceServerUpdateEventArgs_VoiceToken"></a>VoiceToken

Gets the voice connection token.

```csharp
public string VoiceToken { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

