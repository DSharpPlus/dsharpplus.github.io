# Class VoiceStateUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.VoiceStateUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class VoiceStateUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[VoiceStateUpdateEventArgs](DSharpPlus.EventArgs.VoiceStateUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_VoiceStateUpdateEventArgs_After"></a>After

Gets the voice state post-update.

```csharp
public DiscordVoiceState After { get; }
```

#### Property Value

[DiscordVoiceState](DSharpPlus.Entities.DiscordVoiceState.md)

### <a id="DSharpPlus_EventArgs_VoiceStateUpdateEventArgs_Before"></a>Before

Gets the voice state pre-update.

```csharp
public DiscordVoiceState Before { get; }
```

#### Property Value

[DiscordVoiceState](DSharpPlus.Entities.DiscordVoiceState.md)

### <a id="DSharpPlus_EventArgs_VoiceStateUpdateEventArgs_Channel"></a>Channel

Gets the related voice channel.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_VoiceStateUpdateEventArgs_Guild"></a>Guild

Gets the guild in which the update occurred.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_VoiceStateUpdateEventArgs_SessionId"></a>SessionId

Gets the ID of voice session.

```csharp
public string SessionId { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_VoiceStateUpdateEventArgs_User"></a>User

Gets the user whose voice state was updated.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

