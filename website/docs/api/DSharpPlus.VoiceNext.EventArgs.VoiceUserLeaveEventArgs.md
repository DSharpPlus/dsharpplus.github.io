# Class VoiceUserLeaveEventArgs

Namespace: [DSharpPlus.VoiceNext.EventArgs](DSharpPlus.VoiceNext.EventArgs.md)  
Assembly: DSharpPlus.VoiceNext.dll

Arguments for <xref href="DSharpPlus.VoiceNext.VoiceNextConnection.UserLeft" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class VoiceUserLeaveEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[VoiceUserLeaveEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceUserLeaveEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceUserLeaveEventArgs_SSRC"></a>SSRC

Gets the SSRC of the user who left.

```csharp
public uint SSRC { get; }
```

#### Property Value

[uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceUserLeaveEventArgs_User"></a>User

Gets the user who left.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

