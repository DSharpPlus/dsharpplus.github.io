# Class ThreadCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ThreadCreated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ThreadCreateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ThreadCreateEventArgs](DSharpPlus.EventArgs.ThreadCreateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ThreadCreateEventArgs_Guild"></a>Guild

Gets the guild in which the thread was created.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ThreadCreateEventArgs_NewlyCreated"></a>NewlyCreated

Gets whether this thread has been newly created.

```csharp
public bool NewlyCreated { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_EventArgs_ThreadCreateEventArgs_Parent"></a>Parent

Gets the threads parent channel.

```csharp
public DiscordChannel Parent { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_ThreadCreateEventArgs_Thread"></a>Thread

Gets the thread that was created.

```csharp
public DiscordThreadChannel Thread { get; }
```

#### Property Value

[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)

