# Class MessageCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.MessageCreated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class MessageCreateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[MessageCreateEventArgs](DSharpPlus.EventArgs.MessageCreateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_MessageCreateEventArgs_Author"></a>Author

Gets the author of the message.

```csharp
public DiscordUser Author { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_EventArgs_MessageCreateEventArgs_Channel"></a>Channel

Gets the channel this message belongs to.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_MessageCreateEventArgs_Guild"></a>Guild

Gets the guild this message belongs to.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_MessageCreateEventArgs_MentionedChannels"></a>MentionedChannels

Gets the collection of mentioned channels.

```csharp
public IReadOnlyList<DiscordChannel> MentionedChannels { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_EventArgs_MessageCreateEventArgs_MentionedRoles"></a>MentionedRoles

Gets the collection of mentioned roles.

```csharp
public IReadOnlyList<DiscordRole> MentionedRoles { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_EventArgs_MessageCreateEventArgs_MentionedUsers"></a>MentionedUsers

Gets the collection of mentioned users.

```csharp
public IReadOnlyList<DiscordUser> MentionedUsers { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_EventArgs_MessageCreateEventArgs_Message"></a>Message

Gets the message that was created.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

