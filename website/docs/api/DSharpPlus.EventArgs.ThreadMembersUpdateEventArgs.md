# Class ThreadMembersUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ThreadMembersUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ThreadMembersUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ThreadMembersUpdateEventArgs](DSharpPlus.EventArgs.ThreadMembersUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ThreadMembersUpdateEventArgs_AddedMembers"></a>AddedMembers

Gets the members who were added to the thread.

```csharp
public IReadOnlyList<DiscordThreadChannelMember> AddedMembers { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)\>

### <a id="DSharpPlus_EventArgs_ThreadMembersUpdateEventArgs_Guild"></a>Guild

Gets the guild.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ThreadMembersUpdateEventArgs_MemberCount"></a>MemberCount

Gets the approximate number of members in the thread, capped at 50.

```csharp
public int MemberCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_EventArgs_ThreadMembersUpdateEventArgs_RemovedMembers"></a>RemovedMembers

Gets the members who were removed from the thread. These could be skeleton objects depending on cache state.

```csharp
public IReadOnlyList<DiscordMember> RemovedMembers { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_EventArgs_ThreadMembersUpdateEventArgs_Thread"></a>Thread

Gets the thread associated with the member changes.

```csharp
public DiscordThreadChannel Thread { get; }
```

#### Property Value

[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)

