# Class UserUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.UserUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class UserUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[UserUpdateEventArgs](DSharpPlus.EventArgs.UserUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_UserUpdateEventArgs_UserAfter"></a>UserAfter

Gets the post-update user.

```csharp
public DiscordUser UserAfter { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_EventArgs_UserUpdateEventArgs_UserBefore"></a>UserBefore

Gets the pre-update user.

```csharp
public DiscordUser UserBefore { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

