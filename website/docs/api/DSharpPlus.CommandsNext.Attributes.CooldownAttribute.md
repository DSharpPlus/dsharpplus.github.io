# Class CooldownAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines a cooldown for this command. This allows you to define how many times can users execute a specific command

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = true, Inherited = false)]
public sealed class CooldownAttribute : CheckBaseAttribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md) ← 
[CooldownAttribute](DSharpPlus.CommandsNext.Attributes.CooldownAttribute.md)

###### Inherited Members

[CheckBaseAttribute.ExecuteCheckAsync\(CommandContext, bool\)](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md\#DSharpPlus\_CommandsNext\_Attributes\_CheckBaseAttribute\_ExecuteCheckAsync\_DSharpPlus\_CommandsNext\_CommandContext\_System\_Boolean\_)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute__ctor_System_Int32_System_Double_DSharpPlus_CommandsNext_Attributes_CooldownBucketType_"></a>CooldownAttribute\(int, double, CooldownBucketType\)

Defines a cooldown for this command. This means that users will be able to use the command a specific number of times before they have to wait to use it again.

```csharp
public CooldownAttribute(int maxUses, double resetAfter, CooldownBucketType bucketType)
```

#### Parameters

`maxUses` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of times the command can be used before triggering a cooldown.

`resetAfter` [double](https://learn.microsoft.com/dotnet/api/system.double)

Number of seconds after which the cooldown is reset.

`bucketType` [CooldownBucketType](DSharpPlus.CommandsNext.Attributes.CooldownBucketType.md)

Type of cooldown bucket. This allows controlling whether the bucket will be cooled down per user, guild, channel, or globally.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute_BucketType"></a>BucketType

Gets the type of the cooldown bucket. This determines how cooldowns are applied.

```csharp
public CooldownBucketType BucketType { get; }
```

#### Property Value

[CooldownBucketType](DSharpPlus.CommandsNext.Attributes.CooldownBucketType.md)

### <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute_MaxUses"></a>MaxUses

Gets the maximum number of uses before this command triggers a cooldown for its bucket.

```csharp
public int MaxUses { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute_Reset"></a>Reset

Gets the time after which the cooldown is reset.

```csharp
public TimeSpan Reset { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

## Methods

### <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute_ExecuteCheckAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>ExecuteCheckAsync\(CommandContext, bool\)

Asynchronously checks whether this command can be executed within given context.

```csharp
public override Task<bool> ExecuteCheckAsync(CommandContext ctx, bool help)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context to check execution ability for.

`help` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this check is being executed from help or not. This can be used to probe whether command can be run without setting off certain fail conditions (such as cooldowns).

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether the command can be executed in given context.

### <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute_GetBucket_DSharpPlus_CommandsNext_CommandContext_"></a>GetBucket\(CommandContext\)

Gets a cooldown bucket for given command context.

```csharp
public CommandCooldownBucket GetBucket(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Command context to get cooldown bucket for.

#### Returns

[CommandCooldownBucket](DSharpPlus.CommandsNext.Attributes.CommandCooldownBucket.md)

Requested cooldown bucket, or null if one wasn't present.

### <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute_GetRemainingCooldown_DSharpPlus_CommandsNext_CommandContext_"></a>GetRemainingCooldown\(CommandContext\)

Calculates the cooldown remaining for given command context.

```csharp
public TimeSpan GetRemainingCooldown(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context for which to calculate the cooldown.

#### Returns

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Remaining cooldown, or zero if no cooldown is active.

