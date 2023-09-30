# Class ThreadMemberUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ThreadMemberUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ThreadMemberUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ThreadMemberUpdateEventArgs](DSharpPlus.EventArgs.ThreadMemberUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ThreadMemberUpdateEventArgs_Thread"></a>Thread

Gets the thread the current member was updated for.

```csharp
public DiscordThreadChannel Thread { get; }
```

#### Property Value

[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)

### <a id="DSharpPlus_EventArgs_ThreadMemberUpdateEventArgs_ThreadMember"></a>ThreadMember

Gets the thread member that was updated.

```csharp
public DiscordThreadChannelMember ThreadMember { get; }
```

#### Property Value

[DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)

