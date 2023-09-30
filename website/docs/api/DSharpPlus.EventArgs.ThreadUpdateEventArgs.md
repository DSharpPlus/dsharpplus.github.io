# Class ThreadUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ThreadUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ThreadUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ThreadUpdateEventArgs](DSharpPlus.EventArgs.ThreadUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ThreadUpdateEventArgs_Guild"></a>Guild

Gets the guild in which the thread was updated.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ThreadUpdateEventArgs_Parent"></a>Parent

Gets the threads parent channel.

```csharp
public DiscordChannel Parent { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_ThreadUpdateEventArgs_ThreadAfter"></a>ThreadAfter

Gets the post-update thread.

```csharp
public DiscordThreadChannel ThreadAfter { get; }
```

#### Property Value

[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)

### <a id="DSharpPlus_EventArgs_ThreadUpdateEventArgs_ThreadBefore"></a>ThreadBefore

Gets the pre-update thread.

```csharp
public DiscordThreadChannel ThreadBefore { get; }
```

#### Property Value

[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)

