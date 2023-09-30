# Class StageInstanceCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.StageInstanceCreated" data-throw-if-not-resolved="false"></xref>.

```csharp
public class StageInstanceCreateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[StageInstanceCreateEventArgs](DSharpPlus.EventArgs.StageInstanceCreateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_StageInstanceCreateEventArgs_Channel"></a>Channel

Gets the channel the stage instance was created in.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_StageInstanceCreateEventArgs_Guild"></a>Guild

Gets the guild the stage instance was created in.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_StageInstanceCreateEventArgs_StageInstance"></a>StageInstance

Gets the stage instance that was created.

```csharp
public DiscordStageInstance StageInstance { get; }
```

#### Property Value

[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)

