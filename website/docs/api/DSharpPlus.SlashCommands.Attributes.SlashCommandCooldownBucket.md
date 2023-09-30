# Class SlashCommandCooldownBucket

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents a cooldown bucket for commands.

```csharp
public sealed class SlashCommandCooldownBucket
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SlashCommandCooldownBucket](DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket.md)

## Properties

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_BotId"></a>BotId

The bot's ID.

```csharp
public ulong BotId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_BucketId"></a>BucketId

Gets the ID of the bucket. This is used to distinguish between cooldown buckets.

```csharp
public string BucketId { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_ChannelId"></a>ChannelId

Gets the ID of the channel with which this cooldown is associated.

```csharp
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_FullCommandName"></a>FullCommandName

The command's full name (includes groups and subcommands).

```csharp
public string FullCommandName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_GuildId"></a>GuildId

Gets the ID of the guild with which this cooldown is associated.

```csharp
public ulong GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_MaxUses"></a>MaxUses

Gets the maximum number of times this command can be used in given timespan.

```csharp
public int MaxUses { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_RemainingUses"></a>RemainingUses

Gets the remaining number of uses before the cooldown is triggered.

```csharp
public int RemainingUses { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_Reset"></a>Reset

Gets the time after which this cooldown resets.

```csharp
public TimeSpan Reset { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_ResetsAt"></a>ResetsAt

Gets the date and time at which the cooldown resets.

```csharp
public DateTimeOffset ResetsAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_UserId"></a>UserId

Gets the ID of the user with whom this cooldown is associated.

```csharp
public ulong UserId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

## Methods

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_Equals_DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_"></a>Equals\(SlashCommandCooldownBucket\)

Checks whether this <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(SlashCommandCooldownBucket other)
```

#### Parameters

`other` [SlashCommandCooldownBucket](DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket.md)

<xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_MakeId_System_String_System_UInt64_System_UInt64_System_UInt64_System_UInt64_"></a>MakeId\(string, ulong, ulong, ulong, ulong\)

Creates a bucket ID from given bucket parameters.

```csharp
public static string MakeId(string fullCommandName, ulong botId, ulong userId = 0, ulong channelId = 0, ulong guildId = 0)
```

#### Parameters

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

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Generated bucket ID.

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_ToString"></a>ToString\(\)

Returns a string representation of this command cooldown bucket.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this command cooldown bucket.

## Operators

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_op_Equality_DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_"></a>operator ==\(SlashCommandCooldownBucket, SlashCommandCooldownBucket\)

Gets whether the two <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(SlashCommandCooldownBucket bucket1, SlashCommandCooldownBucket bucket2)
```

#### Parameters

`bucket1` [SlashCommandCooldownBucket](DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket.md)

First bucket to compare.

`bucket2` [SlashCommandCooldownBucket](DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket.md)

Second bucket to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two buckets are equal.

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_op_Inequality_DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_DSharpPlus_SlashCommands_Attributes_SlashCommandCooldownBucket_"></a>operator \!=\(SlashCommandCooldownBucket, SlashCommandCooldownBucket\)

Gets whether the two <xref href="DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(SlashCommandCooldownBucket bucket1, SlashCommandCooldownBucket bucket2)
```

#### Parameters

`bucket1` [SlashCommandCooldownBucket](DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket.md)

First bucket to compare.

`bucket2` [SlashCommandCooldownBucket](DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket.md)

Second bucket to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two buckets are not equal.

