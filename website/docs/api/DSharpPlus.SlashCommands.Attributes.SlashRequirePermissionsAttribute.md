# Class SlashRequirePermissionsAttribute

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

Defines that usage of this slash command is restricted to members with specified permissions. This check also verifies that the bot has the same permissions.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false, Inherited = false)]
public sealed class SlashRequirePermissionsAttribute : SlashCheckBaseAttribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[SlashCheckBaseAttribute](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md) ← 
[SlashRequirePermissionsAttribute](DSharpPlus.SlashCommands.Attributes.SlashRequirePermissionsAttribute.md)

###### Inherited Members

[SlashCheckBaseAttribute.ExecuteChecksAsync\(InteractionContext\)](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md\#DSharpPlus\_SlashCommands\_SlashCheckBaseAttribute\_ExecuteChecksAsync\_DSharpPlus\_SlashCommands\_InteractionContext\_)

## Constructors

### <a id="DSharpPlus_SlashCommands_Attributes_SlashRequirePermissionsAttribute__ctor_DSharpPlus_Permissions_System_Boolean_"></a>SlashRequirePermissionsAttribute\(Permissions, bool\)

Defines that usage of this command is restricted to members with specified permissions. This check also verifies that the bot has the same permissions.

```csharp
public SlashRequirePermissionsAttribute(Permissions permissions, bool ignoreDms = true)
```

#### Parameters

`permissions` [Permissions](DSharpPlus.Permissions.md)

Permissions required to execute this command.

`ignoreDms` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets this check's behaviour in DMs. True means the check will always pass in DMs, whereas false means that it will always fail.

## Properties

### <a id="DSharpPlus_SlashCommands_Attributes_SlashRequirePermissionsAttribute_IgnoreDms"></a>IgnoreDms

Gets or sets this check's behaviour in DMs. True means the check will always pass in DMs, whereas false means that it will always fail.

```csharp
public bool IgnoreDms { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_SlashCommands_Attributes_SlashRequirePermissionsAttribute_Permissions"></a>Permissions

Gets the permissions required by this attribute.

```csharp
public Permissions Permissions { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)

## Methods

### <a id="DSharpPlus_SlashCommands_Attributes_SlashRequirePermissionsAttribute_ExecuteChecksAsync_DSharpPlus_SlashCommands_InteractionContext_"></a>ExecuteChecksAsync\(InteractionContext\)

Runs checks.

```csharp
public override Task<bool> ExecuteChecksAsync(InteractionContext ctx)
```

#### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

