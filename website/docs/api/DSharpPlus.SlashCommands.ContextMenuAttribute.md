# Class ContextMenuAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Marks this method as a context menu.

```csharp
[AttributeUsage(AttributeTargets.Method, AllowMultiple = false)]
public sealed class ContextMenuAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[ContextMenuAttribute](DSharpPlus.SlashCommands.ContextMenuAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_ContextMenuAttribute__ctor_DSharpPlus_ApplicationCommandType_System_String_System_Boolean_System_Boolean_"></a>ContextMenuAttribute\(ApplicationCommandType, string, bool, bool\)

Marks this method as a context menu.

```csharp
public ContextMenuAttribute(ApplicationCommandType type, string name, bool defaultPermission = true, bool nsfw = false)
```

#### Parameters

`type` [ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

The type of the context menu.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the context menu.

`defaultPermission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command should be enabled by default.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command is age restricted.

## Properties

### <a id="DSharpPlus_SlashCommands_ContextMenuAttribute_DefaultPermission"></a>DefaultPermission

Gets whether this command is enabled by default.

```csharp
public bool DefaultPermission { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_SlashCommands_ContextMenuAttribute_NSFW"></a>NSFW

Gets whether this command is age restricted.

```csharp
public bool NSFW { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_SlashCommands_ContextMenuAttribute_Name"></a>Name

Gets the name of this context menu.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_ContextMenuAttribute_Type"></a>Type

Gets the type of this context menu.

```csharp
public ApplicationCommandType Type { get; }
```

#### Property Value

[ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

