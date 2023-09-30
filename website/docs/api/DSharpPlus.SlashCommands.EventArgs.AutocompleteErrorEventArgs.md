# Class AutocompleteErrorEventArgs

Namespace: [DSharpPlus.SlashCommands.EventArgs](DSharpPlus.SlashCommands.EventArgs.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents arguments for a <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension.AutocompleteErrored" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class AutocompleteErrorEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[AutocompleteErrorEventArgs](DSharpPlus.SlashCommands.EventArgs.AutocompleteErrorEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_SlashCommands_EventArgs_AutocompleteErrorEventArgs_Context"></a>Context

The context of the autocomplete.

```csharp
public AutocompleteContext Context { get; }
```

#### Property Value

[AutocompleteContext](DSharpPlus.SlashCommands.AutocompleteContext.md)

### <a id="DSharpPlus_SlashCommands_EventArgs_AutocompleteErrorEventArgs_Exception"></a>Exception

The exception thrown.

```csharp
public Exception Exception { get; }
```

#### Property Value

[Exception](https://learn.microsoft.com/dotnet/api/system.exception)

### <a id="DSharpPlus_SlashCommands_EventArgs_AutocompleteErrorEventArgs_ProviderType"></a>ProviderType

The type of the provider.

```csharp
public Type ProviderType { get; }
```

#### Property Value

[Type](https://learn.microsoft.com/dotnet/api/system.type)

