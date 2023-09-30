# Class ApplicationCommandEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for application command events.

```csharp
public sealed class ApplicationCommandEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ApplicationCommandEventArgs](DSharpPlus.EventArgs.ApplicationCommandEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ApplicationCommandEventArgs_Command"></a>Command

Gets the command that was modified.

```csharp
public DiscordApplicationCommand Command { get; }
```

#### Property Value

[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

### <a id="DSharpPlus_EventArgs_ApplicationCommandEventArgs_Guild"></a>Guild

Gets the optional guild of the command.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

