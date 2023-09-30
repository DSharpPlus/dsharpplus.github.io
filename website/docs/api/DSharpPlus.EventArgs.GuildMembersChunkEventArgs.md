# Class GuildMembersChunkEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.GuildMembersChunked" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildMembersChunkEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildMembersChunkEventArgs](DSharpPlus.EventArgs.GuildMembersChunkEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildMembersChunkEventArgs_ChunkCount"></a>ChunkCount

Gets the total amount of chunks for the request.

```csharp
public int ChunkCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_EventArgs_GuildMembersChunkEventArgs_ChunkIndex"></a>ChunkIndex

Gets the current chunk index from the response.

```csharp
public int ChunkIndex { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_EventArgs_GuildMembersChunkEventArgs_Guild"></a>Guild

Gets the guild that requested this chunk.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_GuildMembersChunkEventArgs_Members"></a>Members

Gets the collection of members returned from this chunk.

```csharp
public IReadOnlyCollection<DiscordMember> Members { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_EventArgs_GuildMembersChunkEventArgs_Nonce"></a>Nonce

Gets the unique string used to identify the request, if specified.

```csharp
public string Nonce { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_EventArgs_GuildMembersChunkEventArgs_NotFound"></a>NotFound

Gets the returned Ids that were not found in the chunk, if specified.

```csharp
public IReadOnlyCollection<ulong> NotFound { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

### <a id="DSharpPlus_EventArgs_GuildMembersChunkEventArgs_Presences"></a>Presences

Gets the collection of presences returned from this chunk, if specified.

```csharp
public IReadOnlyCollection<DiscordPresence> Presences { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordPresence](DSharpPlus.Entities.DiscordPresence.md)\>

