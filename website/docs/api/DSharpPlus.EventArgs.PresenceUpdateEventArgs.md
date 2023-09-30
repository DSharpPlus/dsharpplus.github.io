# Class PresenceUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.PresenceUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class PresenceUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[PresenceUpdateEventArgs](DSharpPlus.EventArgs.PresenceUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_PresenceUpdateEventArgs_Activity"></a>Activity

Gets the user's new game.

```csharp
public DiscordActivity Activity { get; }
```

#### Property Value

[DiscordActivity](DSharpPlus.Entities.DiscordActivity.md)

### <a id="DSharpPlus_EventArgs_PresenceUpdateEventArgs_PresenceAfter"></a>PresenceAfter

Gets the user's new presence.

```csharp
public DiscordPresence PresenceAfter { get; }
```

#### Property Value

[DiscordPresence](DSharpPlus.Entities.DiscordPresence.md)

### <a id="DSharpPlus_EventArgs_PresenceUpdateEventArgs_PresenceBefore"></a>PresenceBefore

Gets the user's old presence.

```csharp
public DiscordPresence PresenceBefore { get; }
```

#### Property Value

[DiscordPresence](DSharpPlus.Entities.DiscordPresence.md)

### <a id="DSharpPlus_EventArgs_PresenceUpdateEventArgs_Status"></a>Status

Gets the user's status.

```csharp
public UserStatus Status { get; }
```

#### Property Value

[UserStatus](DSharpPlus.Entities.UserStatus.md)

### <a id="DSharpPlus_EventArgs_PresenceUpdateEventArgs_User"></a>User

Gets the user whose presence was updated.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_EventArgs_PresenceUpdateEventArgs_UserAfter"></a>UserAfter

Gets the user after the presence update.

```csharp
public DiscordUser UserAfter { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_EventArgs_PresenceUpdateEventArgs_UserBefore"></a>UserBefore

Gets the user prior to presence update.

```csharp
public DiscordUser UserBefore { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

