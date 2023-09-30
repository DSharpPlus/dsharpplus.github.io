# Class SlashCooldownAttribute

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

Defines a cooldown for this command. This allows you to define how many times can users execute a specific command

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = true, Inherited = false)]
public sealed class SlashCooldownAttribute : SlashCheckBaseAttribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[SlashCheckBaseAttribute](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md) ← 
[SlashCooldownAttribute](DSharpPlus.SlashCommands.Attributes.SlashCooldownAttribute.md)

###### Inherited Members

[SlashCheckBaseAttribute.ExecuteChecksAsync\(InteractionContext\)](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md\#DSharpPlus\_SlashCommands\_SlashCheckBaseAttribute\_ExecuteChecksAsync\_DSharpPlus\_SlashCommands\_InteractionContext\_)

## Constructors

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute__ctor_System_Int32_System_Double_DSharpPlus_SlashCommands_Attributes_SlashCooldownBucketType_"></a>SlashCooldownAttribute\(int, double, SlashCooldownBucketType\)

Defines a cooldown for this command. This means that users will be able to use the command a specific number of times before they have to wait to use it again.

```csharp
public SlashCooldownAttribute(int maxUses, double resetAfter, SlashCooldownBucketType bucketType)
```

#### Parameters

`maxUses` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of times the command can be used before triggering a cooldown.

`resetAfter` [double](https://learn.microsoft.com/dotnet/api/system.double)

Number of seconds after which the cooldown is reset.

`bucketType` [SlashCooldownBucketType](DSharpPlus.SlashCommands.Attributes.SlashCooldownBucketType.md)

Type of cooldown bucket. This allows controlling whether the bucket will be cooled down per user, guild, channel, or globally.

## Properties

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute_BucketType"></a>BucketType

Gets the type of the cooldown bucket. This determines how cooldowns are applied.

```csharp
public SlashCooldownBucketType BucketType { get; }
```

#### Property Value

[SlashCooldownBucketType](DSharpPlus.SlashCommands.Attributes.SlashCooldownBucketType.md)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute_MaxUses"></a>MaxUses

Gets the maximum number of uses before this command triggers a cooldown for its bucket.

```csharp
public int MaxUses { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute_Reset"></a>Reset

Gets the time after which the cooldown is reset.

```csharp
public TimeSpan Reset { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

## Methods

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute_ExecuteChecksAsync_DSharpPlus_SlashCommands_InteractionContext_"></a>ExecuteChecksAsync\(InteractionContext\)

Checks whether this command can be executed within the current context.

```csharp
public override Task<bool> ExecuteChecksAsync(InteractionContext ctx)
```

#### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

The context.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether the checks passed.

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute_GetBucket_DSharpPlus_SlashCommands_InteractionContext_"></a>GetBucket\(InteractionContext\)

Gets a cooldown bucket for given command context.

```csharp
public SlashCommandCooldownBucket GetBucket(InteractionContext ctx)
```

#### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

Command context to get cooldown bucket for.

#### Returns

[SlashCommandCooldownBucket](DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket.md)

Requested cooldown bucket, or null if one wasn't present.

### <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute_GetRemainingCooldown_DSharpPlus_SlashCommands_InteractionContext_"></a>GetRemainingCooldown\(InteractionContext\)

Calculates the cooldown remaining for given command context.

```csharp
public TimeSpan GetRemainingCooldown(InteractionContext ctx)
```

#### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

Context for which to calculate the cooldown.

#### Returns

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Remaining cooldown, or zero if no cooldown is active.

