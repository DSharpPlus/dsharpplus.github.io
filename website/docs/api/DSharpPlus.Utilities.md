# Class Utilities

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Various Discord-related utilities.

```csharp
public static class Utilities
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Utilities](DSharpPlus.Utilities.md)

## Methods

### <a id="DSharpPlus_Utilities_Contains_System_String_System_Char___"></a>Contains\(string, params char\[\]\)

Checks whether this string contains given characters.

```csharp
public static bool Contains(this string str, params char[] characters)
```

#### Parameters

`str` [string](https://learn.microsoft.com/dotnet/api/system.string)

String to check.

`characters` [char](https://learn.microsoft.com/dotnet/api/system.char)\[\]

Characters to check for.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the string contained these characters.

### <a id="DSharpPlus_Utilities_GetDateTimeOffset_System_Int64_System_Boolean_"></a>GetDateTimeOffset\(long, bool\)

Helper method to create a <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref> from Unix time seconds for targets that do not support this natively.

```csharp
public static DateTimeOffset GetDateTimeOffset(long unixTime, bool shouldThrow = true)
```

#### Parameters

`unixTime` [long](https://learn.microsoft.com/dotnet/api/system.int64)

Unix time seconds to convert.

`shouldThrow` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the method should throw on failure. Defaults to true.

#### Returns

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

Calculated <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Utilities_GetDateTimeOffsetFromMilliseconds_System_Int64_System_Boolean_"></a>GetDateTimeOffsetFromMilliseconds\(long, bool\)

Helper method to create a <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref> from Unix time milliseconds for targets that do not support this natively.

```csharp
public static DateTimeOffset GetDateTimeOffsetFromMilliseconds(long unixTime, bool shouldThrow = true)
```

#### Parameters

`unixTime` [long](https://learn.microsoft.com/dotnet/api/system.int64)

Unix time milliseconds to convert.

`shouldThrow` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the method should throw on failure. Defaults to true.

#### Returns

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

Calculated <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Utilities_GetShardId_System_UInt64_System_Int32_"></a>GetShardId\(ulong, int\)

Gets a shard id from a guild id and total shard count.

```csharp
public static int GetShardId(ulong guildId, int shardCount)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild id the shard is on.

`shardCount` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The total amount of shards.

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The shard id.

### <a id="DSharpPlus_Utilities_GetSnowflakeTime_System_UInt64_"></a>GetSnowflakeTime\(ulong\)

Computes a timestamp from a given snowflake.

```csharp
public static DateTimeOffset GetSnowflakeTime(this ulong snowflake)
```

#### Parameters

`snowflake` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Snowflake to compute a timestamp from.

#### Returns

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

Computed timestamp.

### <a id="DSharpPlus_Utilities_GetUnixTime_System_DateTimeOffset_"></a>GetUnixTime\(DateTimeOffset\)

Helper method to calculate Unix time seconds from a <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref> for targets that do not support this natively.

```csharp
public static long GetUnixTime(DateTimeOffset dto)
```

#### Parameters

`dto` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

<xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref> to calculate Unix time for.

#### Returns

[long](https://learn.microsoft.com/dotnet/api/system.int64)

Calculated Unix time.

### <a id="DSharpPlus_Utilities_ToPermissionString_DSharpPlus_Permissions_"></a>ToPermissionString\(Permissions\)

Converts this <xref href="DSharpPlus.Permissions" data-throw-if-not-resolved="false"></xref> into human-readable format.

```csharp
public static string ToPermissionString(this Permissions perm)
```

#### Parameters

`perm` [Permissions](DSharpPlus.Permissions.md)

Permissions enumeration to convert.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

Human-readable permissions.

