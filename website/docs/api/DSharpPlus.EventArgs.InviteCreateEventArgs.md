# Class InviteCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.InviteCreated" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class InviteCreateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[InviteCreateEventArgs](DSharpPlus.EventArgs.InviteCreateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_InviteCreateEventArgs_Channel"></a>Channel

Gets the channel that the invite is for.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_InviteCreateEventArgs_Guild"></a>Guild

Gets the guild that created the invite.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_InviteCreateEventArgs_Invite"></a>Invite

Gets the created invite.

```csharp
public DiscordInvite Invite { get; }
```

#### Property Value

[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)

