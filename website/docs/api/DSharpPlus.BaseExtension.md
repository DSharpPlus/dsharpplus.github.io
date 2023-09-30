# Class BaseExtension

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents base for all DSharpPlus extensions. To implement your own extension, extend this class, and implement its abstract members.

```csharp
public abstract class BaseExtension
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseExtension](DSharpPlus.BaseExtension.md)

###### Derived

[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md), 
[InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md), 
[LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md), 
[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), 
[VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)

## Properties

### <a id="DSharpPlus_BaseExtension_Client"></a>Client

Gets the instance of <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> this extension is attached to.

```csharp
public DiscordClient Client { get; protected set; }
```

#### Property Value

[DiscordClient](DSharpPlus.DiscordClient.md)

## Methods

### <a id="DSharpPlus_BaseExtension_Dispose"></a>Dispose\(\)

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

```csharp
public abstract void Dispose()
```

### <a id="DSharpPlus_BaseExtension_Setup_DSharpPlus_DiscordClient_"></a>Setup\(DiscordClient\)

Initializes this extension for given <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> instance.

```csharp
protected abstract void Setup(DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Discord client to initialize for.

