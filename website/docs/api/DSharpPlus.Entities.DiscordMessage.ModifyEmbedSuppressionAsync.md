# Method ModifyEmbedSuppressionAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessage_ModifyEmbedSuppressionAsync_System_Boolean_"></a>ModifyEmbedSuppressionAsync\(bool\)

Modifies the visibility of embeds in this message.

```csharp
public Task ModifyEmbedSuppressionAsync(bool hideEmbeds)
```

### Parameters

`hideEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to hide all embeds.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

