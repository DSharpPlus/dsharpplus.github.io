# Constructor SlashCooldownAttribute

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute__ctor_System_Int32_System_Double_DSharpPlus_SlashCommands_Attributes_SlashCooldownBucketType_"></a>SlashCooldownAttribute\(int, double, SlashCooldownBucketType\)

Defines a cooldown for this command. This means that users will be able to use the command a specific number of times before they have to wait to use it again.

```csharp
public SlashCooldownAttribute(int maxUses, double resetAfter, SlashCooldownBucketType bucketType)
```

### Parameters

`maxUses` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of times the command can be used before triggering a cooldown.

`resetAfter` [double](https://learn.microsoft.com/dotnet/api/system.double)

Number of seconds after which the cooldown is reset.

`bucketType` [SlashCooldownBucketType](DSharpPlus.SlashCommands.Attributes.SlashCooldownBucketType.md)

Type of cooldown bucket. This allows controlling whether the bucket will be cooled down per user, guild, channel, or globally.

