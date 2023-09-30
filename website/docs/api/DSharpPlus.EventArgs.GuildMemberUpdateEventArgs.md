# Class GuildMemberUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.GuildMemberUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildMemberUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildMemberUpdateEventArgs](DSharpPlus.EventArgs.GuildMemberUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_AvatarHashAfter"></a>AvatarHashAfter

Gets the member's new avatar hash.

```csharp
public string AvatarHashAfter { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_AvatarHashBefore"></a>AvatarHashBefore

Gets the member's old avatar hash.

```csharp
public string AvatarHashBefore { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_CommunicationDisabledUntilAfter"></a>CommunicationDisabledUntilAfter

Gets the member's communication restriction after the update

```csharp
public DateTimeOffset? CommunicationDisabledUntilAfter { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_CommunicationDisabledUntilBefore"></a>CommunicationDisabledUntilBefore

Gets the member's communication restriction before the update

```csharp
public DateTimeOffset? CommunicationDisabledUntilBefore { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_Guild"></a>Guild

Gets the guild in which the update occurred.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_GuildAvatarHashAfter"></a>GuildAvatarHashAfter

Gets the member's new guild avatar hash.

```csharp
public string GuildAvatarHashAfter { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_GuildAvatarHashBefore"></a>GuildAvatarHashBefore

Gets the member's old guild avatar hash.

```csharp
public string GuildAvatarHashBefore { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_Member"></a>Member

Gets the member that was updated.

```csharp
public DiscordMember Member { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_MemberAfter"></a>MemberAfter

Get the member with post-update info

```csharp
public DiscordMember MemberAfter { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_MemberBefore"></a>MemberBefore

Get the member with pre-update info

```csharp
public DiscordMember MemberBefore { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_NicknameAfter"></a>NicknameAfter

Gets the member's new nickname.

```csharp
public string NicknameAfter { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_NicknameBefore"></a>NicknameBefore

Gets the member's old nickname.

```csharp
public string NicknameBefore { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_PendingAfter"></a>PendingAfter

Gets whether the member had passed membership screening after the update

```csharp
public bool? PendingAfter { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_PendingBefore"></a>PendingBefore

Gets whether the member had passed membership screening before the update

```csharp
public bool? PendingBefore { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_RolesAfter"></a>RolesAfter

Gets a collection containing post-update roles.

```csharp
public IReadOnlyList<DiscordRole> RolesAfter { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_RolesBefore"></a>RolesBefore

Gets a collection containing pre-update roles.

```csharp
public IReadOnlyList<DiscordRole> RolesBefore { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_UsernameAfter"></a>UsernameAfter

Gets the member's new username.

```csharp
public string UsernameAfter { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_GuildMemberUpdateEventArgs_UsernameBefore"></a>UsernameBefore

Gets the member's old username.

```csharp
public string UsernameBefore { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

