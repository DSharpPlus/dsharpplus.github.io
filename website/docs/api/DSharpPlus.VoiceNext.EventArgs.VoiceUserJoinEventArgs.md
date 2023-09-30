# Class VoiceUserJoinEventArgs

Namespace: [DSharpPlus.VoiceNext.EventArgs](DSharpPlus.VoiceNext.EventArgs.md)  
Assembly: DSharpPlus.VoiceNext.dll

Arguments for <xref href="DSharpPlus.VoiceNext.VoiceNextConnection.UserJoined" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class VoiceUserJoinEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[VoiceUserJoinEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceUserJoinEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceUserJoinEventArgs_SSRC"></a>SSRC

Gets the SSRC of the user who joined.

```csharp
public uint SSRC { get; }
```

#### Property Value

[uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceUserJoinEventArgs_User"></a>User

Gets the user who left.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

