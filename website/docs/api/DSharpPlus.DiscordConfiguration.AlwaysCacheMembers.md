# Property AlwaysCacheMembers

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordConfiguration_AlwaysCacheMembers"></a>AlwaysCacheMembers

Sets whether the client should attempt to cache members if exclusively using unprivileged intents.
<p>
    This will only take effect if there are no <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref>
    intents specified. Otherwise, this will always be overwritten to true.
</p>
<p>Defaults to true.</p>

```csharp
public bool AlwaysCacheMembers { set; }
```

### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

