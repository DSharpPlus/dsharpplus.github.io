# Method DeleteStageInstanceAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteStageInstanceAsync_System_UInt64_System_String_"></a>DeleteStageInstanceAsync\(ulong, string\)

Deletes a stage instance in a stage channel.

```csharp
public Task DeleteStageInstanceAsync(ulong channelId, string reason = null)
```

### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel to delete the stage instance of.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason the stage instance was deleted.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

