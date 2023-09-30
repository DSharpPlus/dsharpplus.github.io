# Class SlashCheckBaseAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

The base class for a pre-execution check for a slash command.

```csharp
public abstract class SlashCheckBaseAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[SlashCheckBaseAttribute](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md)

###### Derived

[SlashCooldownAttribute](DSharpPlus.SlashCommands.Attributes.SlashCooldownAttribute.md), 
[SlashRequireBotPermissionsAttribute](DSharpPlus.SlashCommands.Attributes.SlashRequireBotPermissionsAttribute.md), 
[SlashRequireDirectMessageAttribute](DSharpPlus.SlashCommands.Attributes.SlashRequireDirectMessageAttribute.md), 
[SlashRequireGuildAttribute](DSharpPlus.SlashCommands.Attributes.SlashRequireGuildAttribute.md), 
[SlashRequireOwnerAttribute](DSharpPlus.SlashCommands.Attributes.SlashRequireOwnerAttribute.md), 
[SlashRequirePermissionsAttribute](DSharpPlus.SlashCommands.Attributes.SlashRequirePermissionsAttribute.md), 
[SlashRequireUserPermissionsAttribute](DSharpPlus.SlashCommands.Attributes.SlashRequireUserPermissionsAttribute.md)

## Methods

### <a id="DSharpPlus_SlashCommands_SlashCheckBaseAttribute_ExecuteChecksAsync_DSharpPlus_SlashCommands_InteractionContext_"></a>ExecuteChecksAsync\(InteractionContext\)

Checks whether this command can be executed within the current context.

```csharp
public abstract Task<bool> ExecuteChecksAsync(InteractionContext ctx)
```

#### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

The context.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether the checks passed.

