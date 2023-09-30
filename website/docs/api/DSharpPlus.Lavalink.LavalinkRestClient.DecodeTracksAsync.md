# Method DecodeTracksAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkRestClient_DecodeTracksAsync_System_String___"></a>DecodeTracksAsync\(string\[\]\)

Decodes an array of base64 track strings into Lavalink track objects.

```csharp
public Task<IEnumerable<LavalinkTrack>> DecodeTracksAsync(string[] trackStrings)
```

### Parameters

`trackStrings` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

The array of base64 track strings.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)\>\>

## <a id="DSharpPlus_Lavalink_LavalinkRestClient_DecodeTracksAsync_System_Collections_Generic_List_System_String__"></a>DecodeTracksAsync\(List<string\>\)

Decodes a list of base64 track strings into Lavalink track objects.

```csharp
public Task<IEnumerable<LavalinkTrack>> DecodeTracksAsync(List<string> trackStrings)
```

### Parameters

`trackStrings` [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

The list of base64 track strings.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)\>\>

