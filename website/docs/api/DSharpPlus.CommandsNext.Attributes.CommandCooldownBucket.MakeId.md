# Method MakeId

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Attributes_CommandCooldownBucket_MakeId_System_String_System_UInt64_System_UInt64_System_UInt64_System_UInt64_"></a>MakeId\(string, ulong, ulong, ulong, ulong\)

Creates a bucket ID from given bucket parameters.

```csharp
public static string MakeId(string fullCommandName, ulong botId, ulong userId = 0, ulong channelId = 0, ulong guildId = 0)
```

### Parameters

`fullCommandName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Full name of the command with which this cooldown is associated.

`botId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the bot with which this cooldown is associated.

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the user with which this cooldown is associated.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the channel with which this cooldown is associated.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the guild with which this cooldown is associated.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Generated bucket ID.

