# Method Mention

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Formatter_Mention_DSharpPlus_Entities_DiscordUser_System_Boolean_"></a>Mention\(DiscordUser, bool\)

Creates a mention for specified user or member. Can optionally specify to resolve nicknames.

```csharp
public static string Mention(DiscordUser user, bool nickname = false)
```

### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to create mention for.

`nickname` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the mention should resolve nicknames or not.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

## <a id="DSharpPlus_Formatter_Mention_DSharpPlus_Entities_DiscordChannel_"></a>Mention\(DiscordChannel\)

Creates a mention for specified channel.

```csharp
public static string Mention(DiscordChannel channel)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to mention.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

## <a id="DSharpPlus_Formatter_Mention_DSharpPlus_Entities_DiscordRole_"></a>Mention\(DiscordRole\)

Creates a mention for specified role.

```csharp
public static string Mention(DiscordRole role)
```

### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Role to mention.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

## <a id="DSharpPlus_Formatter_Mention_DSharpPlus_Entities_DiscordApplicationCommand_"></a>Mention\(DiscordApplicationCommand\)

Creates a mention for specified application command.

```csharp
public static string Mention(DiscordApplicationCommand command)
```

### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

Application command to mention.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Formatted mention.

