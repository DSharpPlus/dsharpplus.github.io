# Class ChannelPinsUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ChannelPinsUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ChannelPinsUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ChannelPinsUpdateEventArgs](DSharpPlus.EventArgs.ChannelPinsUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ChannelPinsUpdateEventArgs_Channel"></a>Channel

Gets the channel in which the update occurred.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_ChannelPinsUpdateEventArgs_Guild"></a>Guild

Gets the guild in which the update occurred.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ChannelPinsUpdateEventArgs_LastPinTimestamp"></a>LastPinTimestamp

Gets the timestamp of the latest pin.

```csharp
public DateTimeOffset? LastPinTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

