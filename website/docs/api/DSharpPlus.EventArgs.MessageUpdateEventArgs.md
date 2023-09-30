# Class MessageUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.MessageUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class MessageUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[MessageUpdateEventArgs](DSharpPlus.EventArgs.MessageUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_Author"></a>Author

Gets the author of the message.

```csharp
public DiscordUser Author { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_Channel"></a>Channel

Gets the channel this message belongs to.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_Guild"></a>Guild

Gets the guild this message belongs to.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_MentionedChannels"></a>MentionedChannels

Gets the collection of mentioned channels.

```csharp
public IReadOnlyList<DiscordChannel> MentionedChannels { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_MentionedRoles"></a>MentionedRoles

Gets the collection of mentioned roles.

```csharp
public IReadOnlyList<DiscordRole> MentionedRoles { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

#### Remarks

Only shows the mentioned roles from <xref href="DSharpPlus.DiscordClient.MessageCreated" data-throw-if-not-resolved="false"></xref>. EDITS ARE NOT INCLUDED.

### <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_MentionedUsers"></a>MentionedUsers

Gets the collection of mentioned users.

```csharp
public IReadOnlyList<DiscordUser> MentionedUsers { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_Message"></a>Message

Gets the message that was updated.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

### <a id="DSharpPlus_EventArgs_MessageUpdateEventArgs_MessageBefore"></a>MessageBefore

Gets the message before it got updated. This property will be null if the message was not cached.

```csharp
public DiscordMessage MessageBefore { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

