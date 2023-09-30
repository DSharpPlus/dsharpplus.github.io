# Class SlashCommandGroupAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Marks this class a slash command group.

```csharp
[AttributeUsage(AttributeTargets.Class, AllowMultiple = false)]
public sealed class SlashCommandGroupAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[SlashCommandGroupAttribute](DSharpPlus.SlashCommands.SlashCommandGroupAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_SlashCommandGroupAttribute__ctor_System_String_System_String_System_Boolean_System_Boolean_"></a>SlashCommandGroupAttribute\(string, string, bool, bool\)

Marks this class as a slash command group.

```csharp
public SlashCommandGroupAttribute(string name, string description, bool defaultPermission = true, bool nsfw = false)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Sets the name of this command group.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Sets the description of this command group.

`defaultPermission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether this command group is enabled on default.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command group is age restricted.

## Properties

### <a id="DSharpPlus_SlashCommands_SlashCommandGroupAttribute_DefaultPermission"></a>DefaultPermission

Gets whether this command is enabled on default.

```csharp
public bool DefaultPermission { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_SlashCommands_SlashCommandGroupAttribute_Description"></a>Description

Gets the description of this slash command group.

```csharp
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_SlashCommandGroupAttribute_NSFW"></a>NSFW

Gets whether this command is age restricted.

```csharp
public bool NSFW { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_SlashCommands_SlashCommandGroupAttribute_Name"></a>Name

Gets the name of this slash command group.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

