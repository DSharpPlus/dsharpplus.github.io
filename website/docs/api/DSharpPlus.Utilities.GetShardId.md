# Method GetShardId

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Utilities_GetShardId_System_UInt64_System_Int32_"></a>GetShardId\(ulong, int\)

Gets a shard id from a guild id and total shard count.

```csharp
public static int GetShardId(ulong guildId, int shardCount)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild id the shard is on.

`shardCount` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The total amount of shards.

### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The shard id.

