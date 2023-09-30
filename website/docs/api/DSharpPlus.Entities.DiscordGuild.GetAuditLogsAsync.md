# Method GetAuditLogsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetAuditLogsAsync_System_Nullable_System_Int32__DSharpPlus_Entities_DiscordMember_System_Nullable_DSharpPlus_Entities_AuditLogs_AuditLogActionType__"></a>GetAuditLogsAsync\(int?, DiscordMember, AuditLogActionType?\)

Gets audit log entries for this guild.

```csharp
public IAsyncEnumerable<DiscordAuditLogEntry> GetAuditLogsAsync(int? limit = 100, DiscordMember byMember = null, AuditLogActionType? actionType = null)
```

### Parameters

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Maximum number of entries to fetch. Defaults to 100

`byMember` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

Filter by member responsible.

`actionType` [AuditLogActionType](DSharpPlus.Entities.AuditLogs.AuditLogActionType.md)?

Filter by action type.

### Returns

[IAsyncEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.iasyncenumerable\-1)<[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md)\>

A collection of requested audit log entries.

### Remarks

If you set <code class="paramref">limit</code> to null, it will fetch all entries. This may take a while as it will result in multiple api calls

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ViewAuditLog" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

