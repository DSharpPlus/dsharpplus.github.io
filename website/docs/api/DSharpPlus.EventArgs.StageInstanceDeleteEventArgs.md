# Class StageInstanceDeleteEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.StageInstanceDeleted" data-throw-if-not-resolved="false"></xref>.

```csharp
public class StageInstanceDeleteEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[StageInstanceDeleteEventArgs](DSharpPlus.EventArgs.StageInstanceDeleteEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_StageInstanceDeleteEventArgs_Channel"></a>Channel

Gets the channel the stage instance was in.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_StageInstanceDeleteEventArgs_Guild"></a>Guild

Gets the guild the stage instance was in.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_StageInstanceDeleteEventArgs_StageInstance"></a>StageInstance

Gets the stage instance that was deleted.

```csharp
public DiscordStageInstance StageInstance { get; }
```

#### Property Value

[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)

