# Class ThreadDeleteEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ThreadDeleted" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ThreadDeleteEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ThreadDeleteEventArgs](DSharpPlus.EventArgs.ThreadDeleteEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ThreadDeleteEventArgs_Guild"></a>Guild

Gets the guild this thread belonged to.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ThreadDeleteEventArgs_Parent"></a>Parent

Gets the threads parent channel.

```csharp
public DiscordChannel Parent { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_ThreadDeleteEventArgs_Thread"></a>Thread

Gets the thread that was deleted.

```csharp
public DiscordThreadChannel Thread { get; }
```

#### Property Value

[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)

