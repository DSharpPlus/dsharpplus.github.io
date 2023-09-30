# Property UserPermissions

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_UserPermissions"></a>UserPermissions

Gets the permissions of the user who invoked the command in this channel.
<p>Only sent on the resolved channels of interaction responses for application commands.</p>

```csharp
[JsonProperty("permissions")]
public Permissions? UserPermissions { get; }
```

### Property Value

[Permissions](DSharpPlus.Permissions.md)?
