# Class StatisticsReceivedEventArgs

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents arguments for Lavalink statistics received.

```csharp
public sealed class StatisticsReceivedEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[StatisticsReceivedEventArgs](DSharpPlus.Lavalink.EventArgs.StatisticsReceivedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_Lavalink_EventArgs_StatisticsReceivedEventArgs_Statistics"></a>Statistics

Gets the Lavalink statistics received.

```csharp
public LavalinkStatistics Statistics { get; }
```

#### Property Value

[LavalinkStatistics](DSharpPlus.Lavalink.Entities.LavalinkStatistics.md)

