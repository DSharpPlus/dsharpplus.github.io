# Class SlashRequireGuildAttribute

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

Defines that this slash command is only usable within a guild.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false, Inherited = false)]
public sealed class SlashRequireGuildAttribute : SlashCheckBaseAttribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[SlashCheckBaseAttribute](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md) ← 
[SlashRequireGuildAttribute](DSharpPlus.SlashCommands.Attributes.SlashRequireGuildAttribute.md)

###### Inherited Members

[SlashCheckBaseAttribute.ExecuteChecksAsync\(InteractionContext\)](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md\#DSharpPlus\_SlashCommands\_SlashCheckBaseAttribute\_ExecuteChecksAsync\_DSharpPlus\_SlashCommands\_InteractionContext\_)

## Constructors

### <a id="DSharpPlus_SlashCommands_Attributes_SlashRequireGuildAttribute__ctor"></a>SlashRequireGuildAttribute\(\)

Defines that this command is only usable within a guild.

```csharp
public SlashRequireGuildAttribute()
```

## Methods

### <a id="DSharpPlus_SlashCommands_Attributes_SlashRequireGuildAttribute_ExecuteChecksAsync_DSharpPlus_SlashCommands_InteractionContext_"></a>ExecuteChecksAsync\(InteractionContext\)

Runs checks.

```csharp
public override Task<bool> ExecuteChecksAsync(InteractionContext ctx)
```

#### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

