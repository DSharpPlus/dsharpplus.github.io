# Class CheckBaseAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a base for all command pre-execution check attributes.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = true, Inherited = true)]
public abstract class CheckBaseAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)

###### Derived

[CooldownAttribute](DSharpPlus.CommandsNext.Attributes.CooldownAttribute.md), 
[RequireBotPermissionsAttribute](DSharpPlus.CommandsNext.Attributes.RequireBotPermissionsAttribute.md), 
[RequireDirectMessageAttribute](DSharpPlus.CommandsNext.Attributes.RequireDirectMessageAttribute.md), 
[RequireGuildAttribute](DSharpPlus.CommandsNext.Attributes.RequireGuildAttribute.md), 
[RequireNsfwAttribute](DSharpPlus.CommandsNext.Attributes.RequireNsfwAttribute.md), 
[RequireOwnerAttribute](DSharpPlus.CommandsNext.Attributes.RequireOwnerAttribute.md), 
[RequirePermissionsAttribute](DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute.md), 
[RequirePrefixesAttribute](DSharpPlus.CommandsNext.Attributes.RequirePrefixesAttribute.md), 
[RequireReferencedMessageAttribute](DSharpPlus.CommandsNext.Attributes.RequireReferencedMessageAttribute.md), 
[RequireRolesAttribute](DSharpPlus.CommandsNext.Attributes.RequireRolesAttribute.md), 
[RequireUserPermissionsAttribute](DSharpPlus.CommandsNext.Attributes.RequireUserPermissionsAttribute.md)

## Methods

### <a id="DSharpPlus_CommandsNext_Attributes_CheckBaseAttribute_ExecuteCheckAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>ExecuteCheckAsync\(CommandContext, bool\)

Asynchronously checks whether this command can be executed within given context.

```csharp
public abstract Task<bool> ExecuteCheckAsync(CommandContext ctx, bool help)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context to check execution ability for.

`help` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this check is being executed from help or not. This can be used to probe whether command can be run without setting off certain fail conditions (such as cooldowns).

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether the command can be executed in given context.

