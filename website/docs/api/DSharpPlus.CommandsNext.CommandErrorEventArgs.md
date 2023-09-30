# Class CommandErrorEventArgs

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents arguments for <xref href="DSharpPlus.CommandsNext.CommandsNextExtension.CommandErrored" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class CommandErrorEventArgs : CommandEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[CommandEventArgs](DSharpPlus.CommandsNext.CommandEventArgs.md) ← 
[CommandErrorEventArgs](DSharpPlus.CommandsNext.CommandErrorEventArgs.md)

###### Inherited Members

[CommandEventArgs.Context](DSharpPlus.CommandsNext.CommandEventArgs.md\#DSharpPlus\_CommandsNext\_CommandEventArgs\_Context), 
[CommandEventArgs.Command](DSharpPlus.CommandsNext.CommandEventArgs.md\#DSharpPlus\_CommandsNext\_CommandEventArgs\_Command), 
[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_CommandsNext_CommandErrorEventArgs_Exception"></a>Exception

```csharp
public Exception Exception { get; }
```

#### Property Value

[Exception](https://learn.microsoft.com/dotnet/api/system.exception)

