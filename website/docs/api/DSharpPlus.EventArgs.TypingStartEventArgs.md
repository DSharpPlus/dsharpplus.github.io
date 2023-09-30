# Class TypingStartEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.TypingStarted" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class TypingStartEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_TypingStartEventArgs_Channel"></a>Channel

Gets the channel in which the indicator was triggered.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_TypingStartEventArgs_Guild"></a>Guild

Gets the guild in which the indicator was triggered.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_TypingStartEventArgs_StartedAt"></a>StartedAt

Gets the date and time at which the user started typing.

```csharp
public DateTimeOffset StartedAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_EventArgs_TypingStartEventArgs_User"></a>User

Gets the user that started typing.
<p>This can be cast to a <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> if the typing occurred in a guild.</p>

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

