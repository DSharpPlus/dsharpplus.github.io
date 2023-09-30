# Class ZombiedEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.Zombied" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ZombiedEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ZombiedEventArgs](DSharpPlus.EventArgs.ZombiedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ZombiedEventArgs_Failures"></a>Failures

Gets how many heartbeat failures have occured.

```csharp
public int Failures { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_EventArgs_ZombiedEventArgs_GuildDownloadCompleted"></a>GuildDownloadCompleted

Gets whether the zombie event occured whilst guilds are downloading.

```csharp
public bool GuildDownloadCompleted { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

