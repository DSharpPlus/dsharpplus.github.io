# Method GetRole

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetRole_System_UInt64_"></a>GetRole\(ulong\)

Gets a role from this guild by its ID.

```csharp
public DiscordRole GetRole(ulong id)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the role to get.

### Returns

[DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Requested role.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

