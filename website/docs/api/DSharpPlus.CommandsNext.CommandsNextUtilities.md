# Class CommandsNextUtilities

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Various CommandsNext-related utilities.

```csharp
public static class CommandsNextUtilities
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandsNextUtilities](DSharpPlus.CommandsNext.CommandsNextUtilities.md)

## Methods

### <a id="DSharpPlus_CommandsNext_CommandsNextUtilities_GetMentionPrefixLength_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_"></a>GetMentionPrefixLength\(DiscordMessage, DiscordUser\)

Checks whether the message contains a specified mention prefix.

```csharp
public static int GetMentionPrefixLength(this DiscordMessage msg, DiscordUser user)
```

#### Parameters

`msg` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to check.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to check for.

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Positive number if the prefix is present, -1 otherwise.

### <a id="DSharpPlus_CommandsNext_CommandsNextUtilities_GetStringPrefixLength_DSharpPlus_Entities_DiscordMessage_System_String_System_StringComparison_"></a>GetStringPrefixLength\(DiscordMessage, string, StringComparison\)

Checks whether the message has a specified string prefix.

```csharp
public static int GetStringPrefixLength(this DiscordMessage msg, string str, StringComparison comparisonType = StringComparison.Ordinal)
```

#### Parameters

`msg` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to check.

`str` [string](https://learn.microsoft.com/dotnet/api/system.string)

String to check for.

`comparisonType` [StringComparison](https://learn.microsoft.com/dotnet/api/system.stringcomparison)

Method of string comparison for the purposes of finding prefixes.

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Positive number if the prefix is present, -1 otherwise.

