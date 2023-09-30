# Class ContextMenuErrorEventArgs

Namespace: [DSharpPlus.SlashCommands.EventArgs](DSharpPlus.SlashCommands.EventArgs.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents arguments for a <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension.ContextMenuErrored" data-throw-if-not-resolved="false"></xref>

```csharp
public class ContextMenuErrorEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[ContextMenuErrorEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuErrorEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_SlashCommands_EventArgs_ContextMenuErrorEventArgs_Context"></a>Context

The context of the command.

```csharp
public ContextMenuContext Context { get; }
```

#### Property Value

[ContextMenuContext](DSharpPlus.SlashCommands.ContextMenuContext.md)

### <a id="DSharpPlus_SlashCommands_EventArgs_ContextMenuErrorEventArgs_Exception"></a>Exception

The exception thrown.

```csharp
public Exception Exception { get; }
```

#### Property Value

[Exception](https://learn.microsoft.com/dotnet/api/system.exception)

