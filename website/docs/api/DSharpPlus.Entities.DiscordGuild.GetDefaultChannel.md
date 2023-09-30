# Method GetDefaultChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetDefaultChannel"></a>GetDefaultChannel\(\)

<p>Gets the default channel for this guild.</p>
<p>Default channel is the first channel current member can see.</p>

```csharp
public DiscordChannel GetDefaultChannel()
```

### Returns

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

This member's default guild.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

