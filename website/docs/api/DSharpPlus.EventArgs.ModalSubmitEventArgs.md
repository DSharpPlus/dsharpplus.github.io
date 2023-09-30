# Class ModalSubmitEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Fired when a modal is submitted. Note that this event is fired only if the modal is submitted by the user, and not if the modal is closed.

```csharp
public class ModalSubmitEventArgs : InteractionCreateEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[InteractionCreateEventArgs](DSharpPlus.EventArgs.InteractionCreateEventArgs.md) ← 
[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)

###### Inherited Members

[InteractionCreateEventArgs.Interaction](DSharpPlus.EventArgs.InteractionCreateEventArgs.md\#DSharpPlus\_EventArgs\_InteractionCreateEventArgs\_Interaction), 
[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ModalSubmitEventArgs_Values"></a>Values

A dictionary of submitted fields, keyed on the custom id of the input component.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<string, string> Values { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

