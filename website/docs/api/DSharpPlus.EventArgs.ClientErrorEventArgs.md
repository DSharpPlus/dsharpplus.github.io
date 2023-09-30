# Class ClientErrorEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ClientErrored" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class ClientErrorEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ClientErrorEventArgs](DSharpPlus.EventArgs.ClientErrorEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ClientErrorEventArgs_EventName"></a>EventName

Gets the name of the event that threw the exception.

```csharp
public string EventName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_ClientErrorEventArgs_Exception"></a>Exception

Gets the exception thrown by the client.

```csharp
public Exception Exception { get; }
```

#### Property Value

[Exception](https://learn.microsoft.com/dotnet/api/system.exception)

