# Method GetShard

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordShardedClient_GetShard_System_UInt64_"></a>GetShard\(ulong\)

Gets a shard from a guild ID.
<p>
    If automatically sharding, this will use the <xref href="DSharpPlus.Utilities.GetShardId(System.UInt64%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref> method.
    Otherwise if manually sharding, it will instead iterate through each shard's guild caches.
</p>

```csharp
public DiscordClient GetShard(ulong guildId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID for the shard.

### Returns

[DiscordClient](DSharpPlus.DiscordClient.md)

The found <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> shard. Otherwise <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> if the shard was not found for the guild ID.

## <a id="DSharpPlus_DiscordShardedClient_GetShard_DSharpPlus_Entities_DiscordGuild_"></a>GetShard\(DiscordGuild\)

Gets a shard from a guild.
<p>
    If automatically sharding, this will use the <xref href="DSharpPlus.Utilities.GetShardId(System.UInt64%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref> method.
    Otherwise if manually sharding, it will instead iterate through each shard's guild caches.
</p>

```csharp
public DiscordClient GetShard(DiscordGuild guild)
```

### Parameters

`guild` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

The guild for the shard.

### Returns

[DiscordClient](DSharpPlus.DiscordClient.md)

The found <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> shard. Otherwise <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> if the shard was not found for the guild.

