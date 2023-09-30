# Class ThreadListSyncEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ThreadListSynced" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ThreadListSyncEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ThreadListSyncEventArgs](DSharpPlus.EventArgs.ThreadListSyncEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ThreadListSyncEventArgs_Channels"></a>Channels

Gets the parent channels whose threads are being synced. May contain channels that have no active threads as well.

```csharp
public IReadOnlyList<DiscordChannel> Channels { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_EventArgs_ThreadListSyncEventArgs_CurrentMembers"></a>CurrentMembers

Gets all thread member objects, indicating which threads the current user has been added to.

```csharp
public IReadOnlyList<DiscordThreadChannelMember> CurrentMembers { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)\>

### <a id="DSharpPlus_EventArgs_ThreadListSyncEventArgs_Guild"></a>Guild

Gets the guild being synced.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ThreadListSyncEventArgs_Threads"></a>Threads

Gets all active threads in the given channels that the current user can access.

```csharp
public IReadOnlyList<DiscordThreadChannel> Threads { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

