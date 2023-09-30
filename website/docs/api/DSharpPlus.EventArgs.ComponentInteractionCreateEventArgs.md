# Class ComponentInteractionCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.ComponentInteractionCreated" data-throw-if-not-resolved="false"></xref>.

```csharp
public class ComponentInteractionCreateEventArgs : InteractionCreateEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[InteractionCreateEventArgs](DSharpPlus.EventArgs.InteractionCreateEventArgs.md) ← 
[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)

###### Inherited Members

[InteractionCreateEventArgs.Interaction](DSharpPlus.EventArgs.InteractionCreateEventArgs.md\#DSharpPlus\_EventArgs\_InteractionCreateEventArgs\_Interaction), 
[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_Channel"></a>Channel

The channel this interaction was invoked in.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_Guild"></a>Guild

The guild this interaction was invoked on, if any.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_GuildLocale"></a>GuildLocale

The guild's locale that the user invoked in.

```csharp
public string GuildLocale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_Id"></a>Id

The Id of the component that was interacted with.

```csharp
public string Id { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_Locale"></a>Locale

The locale of the user that invoked this interaction.

```csharp
public string Locale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_Message"></a>Message

The message this interaction is attached to.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

### <a id="DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_User"></a>User

The user that invoked this interaction.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_Values"></a>Values

The value(s) selected. Only applicable to SelectMenu components.

```csharp
public string[] Values { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

