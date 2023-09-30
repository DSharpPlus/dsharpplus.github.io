# Class RequirePrefixesAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines that usage of this command is only allowed with specific prefixes.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false, Inherited = false)]
public sealed class RequirePrefixesAttribute : CheckBaseAttribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md) ← 
[RequirePrefixesAttribute](DSharpPlus.CommandsNext.Attributes.RequirePrefixesAttribute.md)

###### Inherited Members

[CheckBaseAttribute.ExecuteCheckAsync\(CommandContext, bool\)](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md\#DSharpPlus\_CommandsNext\_Attributes\_CheckBaseAttribute\_ExecuteCheckAsync\_DSharpPlus\_CommandsNext\_CommandContext\_System\_Boolean\_)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_RequirePrefixesAttribute__ctor_System_String___"></a>RequirePrefixesAttribute\(params string\[\]\)

Defines that usage of this command is only allowed with specific prefixes.

```csharp
public RequirePrefixesAttribute(params string[] prefixes)
```

#### Parameters

`prefixes` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

Prefixes with which the execution of this command is allowed.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_RequirePrefixesAttribute_Prefixes"></a>Prefixes

Gets the array of prefixes with which execution of this command is allowed.

```csharp
public string[] Prefixes { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

### <a id="DSharpPlus_CommandsNext_Attributes_RequirePrefixesAttribute_ShowInHelp"></a>ShowInHelp

<p>Gets or sets default help behaviour for this check. When this is enabled, invoking help without matching prefix will show the commands.</p>
<p>Defaults to false.</p>

```csharp
public bool ShowInHelp { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="DSharpPlus_CommandsNext_Attributes_RequirePrefixesAttribute_ExecuteCheckAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>ExecuteCheckAsync\(CommandContext, bool\)

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

