# Constructor CooldownAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute__ctor_System_Int32_System_Double_DSharpPlus_CommandsNext_Attributes_CooldownBucketType_"></a>CooldownAttribute\(int, double, CooldownBucketType\)

Defines a cooldown for this command. This means that users will be able to use the command a specific number of times before they have to wait to use it again.

```csharp
public CooldownAttribute(int maxUses, double resetAfter, CooldownBucketType bucketType)
```

### Parameters

`maxUses` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of times the command can be used before triggering a cooldown.

`resetAfter` [double](https://learn.microsoft.com/dotnet/api/system.double)

Number of seconds after which the cooldown is reset.

`bucketType` [CooldownBucketType](DSharpPlus.CommandsNext.Attributes.CooldownBucketType.md)

Type of cooldown bucket. This allows controlling whether the bucket will be cooled down per user, guild, channel, or globally.

