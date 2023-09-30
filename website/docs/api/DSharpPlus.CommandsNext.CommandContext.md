# Class CommandContext

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a context in which a command is executed.

```csharp
public sealed class CommandContext
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

## Properties

### <a id="DSharpPlus_CommandsNext_CommandContext_Channel"></a>Channel

Gets the channel in which the execution was triggered,

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_CommandsNext_CommandContext_Client"></a>Client

Gets the client which received the message.

```csharp
public DiscordClient Client { get; }
```

#### Property Value

[DiscordClient](DSharpPlus.DiscordClient.md)

### <a id="DSharpPlus_CommandsNext_CommandContext_Command"></a>Command

Gets the command that is being executed.

```csharp
public Command? Command { get; }
```

#### Property Value

[Command](DSharpPlus.CommandsNext.Command.md)?

### <a id="DSharpPlus_CommandsNext_CommandContext_CommandsNext"></a>CommandsNext

Gets the CommandsNext service instance that handled this command.

```csharp
public CommandsNextExtension CommandsNext { get; }
```

#### Property Value

[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)

### <a id="DSharpPlus_CommandsNext_CommandContext_Guild"></a>Guild

Gets the guild in which the execution was triggered. This property is null for commands sent over direct messages.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_CommandsNext_CommandContext_Member"></a>Member

Gets the member who triggered the execution. This property is null for commands sent over direct messages.

```csharp
public DiscordMember? Member { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)?

### <a id="DSharpPlus_CommandsNext_CommandContext_Message"></a>Message

Gets the message that triggered the execution.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

### <a id="DSharpPlus_CommandsNext_CommandContext_Overload"></a>Overload

Gets the overload of the command that is being executed.

```csharp
public CommandOverload Overload { get; }
```

#### Property Value

[CommandOverload](DSharpPlus.CommandsNext.CommandOverload.md)

### <a id="DSharpPlus_CommandsNext_CommandContext_Prefix"></a>Prefix

Gets the prefix used to invoke the command.

```csharp
public string Prefix { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_CommandsNext_CommandContext_RawArgumentString"></a>RawArgumentString

Gets the raw string from which the arguments were extracted.

```csharp
public string RawArgumentString { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_CommandsNext_CommandContext_RawArguments"></a>RawArguments

Gets the list of raw arguments passed to the command.

```csharp
public IReadOnlyList<string> RawArguments { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_CommandsNext_CommandContext_Services"></a>Services

Gets the service provider for this CNext instance.

```csharp
public IServiceProvider Services { get; }
```

#### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

### <a id="DSharpPlus_CommandsNext_CommandContext_User"></a>User

Gets the user who triggered the execution.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Methods

### <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_System_String_"></a>RespondAsync\(string\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message to respond with.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_DSharpPlus_Entities_DiscordEmbed_"></a>RespondAsync\(DiscordEmbed\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(DiscordEmbed embed)
```

#### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>RespondAsync\(string, DiscordEmbed\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(string content, DiscordEmbed embed)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message to respond with.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_DSharpPlus_Entities_DiscordMessageBuilder_"></a>RespondAsync\(DiscordMessageBuilder\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(DiscordMessageBuilder builder)
```

#### Parameters

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The Discord Message builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>RespondAsync\(Action<DiscordMessageBuilder\>\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(Action<DiscordMessageBuilder> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The Discord Message builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_CommandsNext_CommandContext_TriggerTypingAsync"></a>TriggerTypingAsync\(\)

Triggers typing in the channel containing the message that triggered the command.

```csharp
public Task TriggerTypingAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

