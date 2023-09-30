# Class StageInstanceUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.StageInstanceUpdated" data-throw-if-not-resolved="false"></xref>.

```csharp
public class StageInstanceUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[StageInstanceUpdateEventArgs](DSharpPlus.EventArgs.StageInstanceUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_StageInstanceUpdateEventArgs_Channel"></a>Channel

Gets the channel the stage instance is in.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_StageInstanceUpdateEventArgs_Guild"></a>Guild

Gets the guild the stage instance is in.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_StageInstanceUpdateEventArgs_StageInstanceAfter"></a>StageInstanceAfter

Gets the stage instance after the update.

```csharp
public DiscordStageInstance StageInstanceAfter { get; }
```

#### Property Value

[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)

### <a id="DSharpPlus_EventArgs_StageInstanceUpdateEventArgs_StageInstanceBefore"></a>StageInstanceBefore

Gets the stage instance before the update.

```csharp
public DiscordStageInstance StageInstanceBefore { get; }
```

#### Property Value

[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)

