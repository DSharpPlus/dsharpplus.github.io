# Class SlashCommandAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Marks this method as a slash command.

```csharp
[AttributeUsage(AttributeTargets.Method, AllowMultiple = false)]
public sealed class SlashCommandAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[SlashCommandAttribute](DSharpPlus.SlashCommands.SlashCommandAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_SlashCommandAttribute__ctor_System_String_System_String_System_Boolean_System_Boolean_"></a>SlashCommandAttribute\(string, string, bool, bool\)

Marks this method as a slash command.

```csharp
public SlashCommandAttribute(string name, string description, bool defaultPermission = true, bool nsfw = false)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Sets the name of this slash command.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Sets the description of this slash command.

`defaultPermission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command should be enabled by default.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command is age restricted.

## Properties

### <a id="DSharpPlus_SlashCommands_SlashCommandAttribute_DefaultPermission"></a>DefaultPermission

Gets whether this command is enabled by default.

```csharp
public bool DefaultPermission { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_SlashCommands_SlashCommandAttribute_Description"></a>Description

Gets the description of this command.

```csharp
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_SlashCommandAttribute_NSFW"></a>NSFW

Gets whether this command is age restricted.

```csharp
public bool NSFW { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_SlashCommands_SlashCommandAttribute_Name"></a>Name

Gets the name of this command.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

