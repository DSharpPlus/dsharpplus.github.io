# Class UnknownEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.UnknownEvent" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class UnknownEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[UnknownEventArgs](DSharpPlus.EventArgs.UnknownEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_UnknownEventArgs_EventName"></a>EventName

Gets the event's name.

```csharp
public string EventName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_UnknownEventArgs_Json"></a>Json

Gets the event's data.

```csharp
public string Json { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

