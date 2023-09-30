# Class DiscordGuildApplicationCommandPermissions

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents the guild permissions for a application command.

```csharp
public class DiscordGuildApplicationCommandPermissions : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Constructors

### <a id="DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions__ctor_System_UInt64_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandPermission__"></a>DiscordGuildApplicationCommandPermissions\(ulong, IEnumerable<DiscordApplicationCommandPermission\>\)

Represents the guild application command permissions for a application command.

```csharp
public DiscordGuildApplicationCommandPermissions(ulong commandId, IEnumerable<DiscordApplicationCommandPermission> permissions)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the command.

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandPermission](DSharpPlus.Entities.DiscordApplicationCommandPermission.md)\>

The permissions for the application command.

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions_ApplicationId"></a>ApplicationId

Gets the id of the application the command belongs to.

```csharp
[JsonProperty("application_id")]
public ulong ApplicationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions_Guild"></a>Guild

Gets the guild.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions_GuildId"></a>GuildId

Gets the id of the guild.

```csharp
[JsonProperty("guild_id")]
public ulong GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions_Permissions"></a>Permissions

Gets the permissions for the application command in the guild.

```csharp
[JsonProperty("permissions")]
public IReadOnlyList<DiscordApplicationCommandPermission> Permissions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommandPermission](DSharpPlus.Entities.DiscordApplicationCommandPermission.md)\>

