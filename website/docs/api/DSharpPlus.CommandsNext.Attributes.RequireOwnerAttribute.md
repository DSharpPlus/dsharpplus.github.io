# Class RequireOwnerAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines that usage of this command is restricted to the owner of the bot.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false, Inherited = false)]
public sealed class RequireOwnerAttribute : CheckBaseAttribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md) ← 
[RequireOwnerAttribute](DSharpPlus.CommandsNext.Attributes.RequireOwnerAttribute.md)

###### Inherited Members

[CheckBaseAttribute.ExecuteCheckAsync\(CommandContext, bool\)](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md\#DSharpPlus\_CommandsNext\_Attributes\_CheckBaseAttribute\_ExecuteCheckAsync\_DSharpPlus\_CommandsNext\_CommandContext\_System\_Boolean\_)

## Methods

### <a id="DSharpPlus_CommandsNext_Attributes_RequireOwnerAttribute_ExecuteCheckAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>ExecuteCheckAsync\(CommandContext, bool\)

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

