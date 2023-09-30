# Class UserSpeakingEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for UserSpeaking event.

```csharp
public class UserSpeakingEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[UserSpeakingEventArgs](DSharpPlus.EventArgs.UserSpeakingEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_UserSpeakingEventArgs_SSRC"></a>SSRC

Gets the SSRC of the audio source.

```csharp
public uint SSRC { get; }
```

#### Property Value

[uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="DSharpPlus_EventArgs_UserSpeakingEventArgs_Speaking"></a>Speaking

Gets whether this user is speaking.

```csharp
public bool Speaking { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_EventArgs_UserSpeakingEventArgs_User"></a>User

Gets the users whose speaking state changed.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

