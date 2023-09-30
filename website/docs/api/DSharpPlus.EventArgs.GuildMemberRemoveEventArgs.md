# Class GuildMemberRemoveEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.GuildMemberRemoved" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildMemberRemoveEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildMemberRemoveEventArgs](DSharpPlus.EventArgs.GuildMemberRemoveEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildMemberRemoveEventArgs_Guild"></a>Guild

Gets the guild the member was removed from.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_GuildMemberRemoveEventArgs_Member"></a>Member

Gets the member that was removed.

```csharp
public DiscordMember Member { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

