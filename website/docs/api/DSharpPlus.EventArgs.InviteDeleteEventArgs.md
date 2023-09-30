# Class InviteDeleteEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.InviteDeleted" data-throw-if-not-resolved="false"></xref>

```csharp
public sealed class InviteDeleteEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[InviteDeleteEventArgs](DSharpPlus.EventArgs.InviteDeleteEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_InviteDeleteEventArgs_Channel"></a>Channel

Gets the channel that the invite was for.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_InviteDeleteEventArgs_Guild"></a>Guild

Gets the guild that deleted the invite.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_InviteDeleteEventArgs_Invite"></a>Invite

Gets the deleted invite.

```csharp
public DiscordInvite Invite { get; }
```

#### Property Value

[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)

