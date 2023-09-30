# Class RequirePermissionsAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines that usage of this command is restricted to members with specified permissions. This check also verifies that the bot has the same permissions.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false, Inherited = false)]
public sealed class RequirePermissionsAttribute : CheckBaseAttribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md) ← 
[RequirePermissionsAttribute](DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute.md)

###### Inherited Members

[CheckBaseAttribute.ExecuteCheckAsync\(CommandContext, bool\)](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md\#DSharpPlus\_CommandsNext\_Attributes\_CheckBaseAttribute\_ExecuteCheckAsync\_DSharpPlus\_CommandsNext\_CommandContext\_System\_Boolean\_)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_RequirePermissionsAttribute__ctor_DSharpPlus_Permissions_System_Boolean_"></a>RequirePermissionsAttribute\(Permissions, bool\)

Defines that usage of this command is restricted to members with specified permissions. This check also verifies that the bot has the same permissions.

```csharp
public RequirePermissionsAttribute(Permissions permissions, bool ignoreDms = true)
```

#### Parameters

`permissions` [Permissions](DSharpPlus.Permissions.md)

Permissions required to execute this command.

`ignoreDms` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets this check's behaviour in DMs. True means the check will always pass in DMs, whereas false means that it will always fail.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_RequirePermissionsAttribute_IgnoreDms"></a>IgnoreDms

Gets this check's behaviour in DMs. True means the check will always pass in DMs, whereas false means that it will always fail.

```csharp
public bool IgnoreDms { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_Attributes_RequirePermissionsAttribute_Permissions"></a>Permissions

Gets the permissions required by this attribute.

```csharp
public Permissions Permissions { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)

## Methods

### <a id="DSharpPlus_CommandsNext_Attributes_RequirePermissionsAttribute_ExecuteCheckAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>ExecuteCheckAsync\(CommandContext, bool\)

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

