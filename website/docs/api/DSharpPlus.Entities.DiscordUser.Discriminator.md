# Property Discriminator

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordUser_Discriminator"></a>Discriminator

Gets the user's 4-digit discriminator.

```csharp
[JsonProperty("discriminator", NullValueHandling = NullValueHandling.Ignore)]
public virtual string Discriminator { get; }
```

### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### Remarks

As of May 15th, 2023, Discord has begun phasing out discriminators in favor of handles (@username); this property will return "0" for migrated accounts.

