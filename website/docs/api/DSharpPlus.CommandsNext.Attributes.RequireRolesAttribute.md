# Class RequireRolesAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines that usage of this command is restricted to members with specified role. Note that it's much preferred to restrict access using <xref href="DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute" data-throw-if-not-resolved="false"></xref>.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false, Inherited = false)]
public sealed class RequireRolesAttribute : CheckBaseAttribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md) ← 
[RequireRolesAttribute](DSharpPlus.CommandsNext.Attributes.RequireRolesAttribute.md)

###### Inherited Members

[CheckBaseAttribute.ExecuteCheckAsync\(CommandContext, bool\)](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md\#DSharpPlus\_CommandsNext\_Attributes\_CheckBaseAttribute\_ExecuteCheckAsync\_DSharpPlus\_CommandsNext\_CommandContext\_System\_Boolean\_)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute__ctor_DSharpPlus_CommandsNext_Attributes_RoleCheckMode_System_String___"></a>RequireRolesAttribute\(RoleCheckMode, params string\[\]\)

Defines that usage of this command is restricted to members with specified role. Note that it's much preferred to restrict access using <xref href="DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute" data-throw-if-not-resolved="false"></xref>.

```csharp
public RequireRolesAttribute(RoleCheckMode checkMode, params string[] roleNames)
```

#### Parameters

`checkMode` [RoleCheckMode](DSharpPlus.CommandsNext.Attributes.RoleCheckMode.md)

Role checking mode.

`roleNames` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

Names of the role to be verified by this check.

### <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute__ctor_DSharpPlus_CommandsNext_Attributes_RoleCheckMode_System_UInt64___"></a>RequireRolesAttribute\(RoleCheckMode, params ulong\[\]\)

Defines that usage of this command is restricted to members with the specified role.
Note that it is much preferred to restrict access using <xref href="DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute" data-throw-if-not-resolved="false"></xref>.

```csharp
public RequireRolesAttribute(RoleCheckMode checkMode, params ulong[] roleIds)
```

#### Parameters

`checkMode` [RoleCheckMode](DSharpPlus.CommandsNext.Attributes.RoleCheckMode.md)

Role checking mode.

`roleIds` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\[\]

IDs of the roles to be verified by this check.

### <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute__ctor_DSharpPlus_CommandsNext_Attributes_RoleCheckMode_System_String___System_UInt64___"></a>RequireRolesAttribute\(RoleCheckMode, string\[\], ulong\[\]\)

Defines that usage of this command is restricted to members with the specified role.
Note that it is much preferred to restrict access using <xref href="DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute" data-throw-if-not-resolved="false"></xref>.

```csharp
public RequireRolesAttribute(RoleCheckMode checkMode, string[] roleNames, ulong[] roleIds)
```

#### Parameters

`checkMode` [RoleCheckMode](DSharpPlus.CommandsNext.Attributes.RoleCheckMode.md)

Role checking mode.

`roleNames` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

Names of the role to be verified by this check.

`roleIds` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\[\]

IDs of the roles to be verified by this check.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute_CheckMode"></a>CheckMode

Gets the role checking mode. Refer to <xref href="DSharpPlus.CommandsNext.Attributes.RoleCheckMode" data-throw-if-not-resolved="false"></xref> for more information.

```csharp
public RoleCheckMode CheckMode { get; }
```

#### Property Value

[RoleCheckMode](DSharpPlus.CommandsNext.Attributes.RoleCheckMode.md)

### <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute_RoleIds"></a>RoleIds

Gets the IDs of roles required to execute this command.

```csharp
public IReadOnlyList<ulong> RoleIds { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

### <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute_RoleNames"></a>RoleNames

Gets the names of roles required to execute this command.

```csharp
public IReadOnlyList<string> RoleNames { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

## Methods

### <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute_ExecuteCheckAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>ExecuteCheckAsync\(CommandContext, bool\)

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

