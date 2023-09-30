# Class ApplicationCommandPermissionsUpdatedEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

```csharp
public class ApplicationCommandPermissionsUpdatedEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ApplicationCommandPermissionsUpdatedEventArgs](DSharpPlus.EventArgs.ApplicationCommandPermissionsUpdatedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ApplicationCommandPermissionsUpdatedEventArgs_ApplicationId"></a>ApplicationId

The Id of the application the command was updated for.

```csharp
[JsonProperty("application_id")]
public ulong ApplicationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_EventArgs_ApplicationCommandPermissionsUpdatedEventArgs_CommandId"></a>CommandId

The Id of the command that was updated.

```csharp
[JsonProperty("id")]
public ulong CommandId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_EventArgs_ApplicationCommandPermissionsUpdatedEventArgs_GuildId"></a>GuildId

The Id of the guild the command was updated for.

```csharp
[JsonProperty("guild_id")]
public ulong GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_EventArgs_ApplicationCommandPermissionsUpdatedEventArgs_NewPermissions"></a>NewPermissions

The new permissions for the command.

```csharp
[JsonProperty("permissions")]
public IReadOnlyList<ApplicationCommandPermissionUpdate> NewPermissions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[ApplicationCommandPermissionUpdate](DSharpPlus.EventArgs.ApplicationCommandPermissionUpdate.md)\>

