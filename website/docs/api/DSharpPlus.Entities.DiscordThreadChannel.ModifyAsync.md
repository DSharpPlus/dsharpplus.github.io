# Method ModifyAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordThreadChannel_ModifyAsync_System_Action_DSharpPlus_Net_Models_ThreadChannelEditModel__"></a>ModifyAsync\(Action<ThreadChannelEditModel\>\)

Modifies the current thread.

```csharp
public Task ModifyAsync(Action<ThreadChannelEditModel> action)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ThreadChannelEditModel](DSharpPlus.Net.Models.ThreadChannelEditModel.md)\>

Action to perform on this thread

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

