# Class DmChannelDeleteEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.DmChannelDeleted" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class DmChannelDeleteEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[DmChannelDeleteEventArgs](DSharpPlus.EventArgs.DmChannelDeleteEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_DmChannelDeleteEventArgs_Channel"></a>Channel

Gets the direct message channel that was deleted.

```csharp
public DiscordDmChannel Channel { get; }
```

#### Property Value

[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)

