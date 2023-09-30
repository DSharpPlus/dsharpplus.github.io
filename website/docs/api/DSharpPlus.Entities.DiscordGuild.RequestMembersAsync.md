# Method RequestMembersAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_RequestMembersAsync_System_String_System_Int32_System_Nullable_System_Boolean__System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>RequestMembersAsync\(string, int, bool?, IEnumerable<ulong\>, string\)

Requests that Discord send a list of guild members based on the specified arguments. This method will fire the <xref href="DSharpPlus.DiscordClient.GuildMembersChunked" data-throw-if-not-resolved="false"></xref> event.
<p>If no arguments aside from <code class="paramref">presences</code> and <code class="paramref">nonce</code> are specified, this will request all guild members.</p>

```csharp
public Task RequestMembersAsync(string query = "", int limit = 0, bool? presences = null, IEnumerable<ulong> userIds = null, string nonce = null)
```

### Parameters

`query` [string](https://learn.microsoft.com/dotnet/api/system.string)

Filters the returned members based on what the username starts with. Either this or <code class="paramref">userIds</code> must not be null.
    The <code class="paramref">limit</code> must also be greater than 0 if this is specified.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Total number of members to request. This must be greater than 0 if <code class="paramref">query</code> is specified.

`presences` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include the <xref href="DSharpPlus.EventArgs.GuildMembersChunkEventArgs.Presences" data-throw-if-not-resolved="false"></xref> associated with the fetched members.

`userIds` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

Whether to limit the request to the specified user ids. Either this or <code class="paramref">query</code> must not be null.

`nonce` [string](https://learn.microsoft.com/dotnet/api/system.string)

The unique string to identify the response.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

