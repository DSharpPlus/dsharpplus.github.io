# Method ModifyAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_ModifyAsync_System_Action_DSharpPlus_Net_Models_ChannelEditModel__"></a>ModifyAsync\(Action<ChannelEditModel\>\)

Modifies the current channel.

```csharp
public Task ModifyAsync(Action<ChannelEditModel> action)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ChannelEditModel](DSharpPlus.Net.Models.ChannelEditModel.md)\>

Action to perform on this channel

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

