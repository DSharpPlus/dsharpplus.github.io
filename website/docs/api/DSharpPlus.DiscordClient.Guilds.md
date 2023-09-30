# Property Guilds

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_Guilds"></a>Guilds

Gets a dictionary of guilds that this client is in. The dictionary's key is the guild ID. Note that the
guild objects in this dictionary will not be filled in if the specific guilds aren't available (the
<xref href="DSharpPlus.DiscordClient.GuildAvailable" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.DiscordClient.GuildDownloadCompleted" data-throw-if-not-resolved="false"></xref> events haven't been fired yet)

```csharp
public override IReadOnlyDictionary<ulong, DiscordGuild> Guilds { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

