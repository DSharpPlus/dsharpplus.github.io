# Class OptionAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Marks this parameter as an option for a slash command.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = false)]
public sealed class OptionAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[OptionAttribute](DSharpPlus.SlashCommands.OptionAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_OptionAttribute__ctor_System_String_System_String_System_Boolean_"></a>OptionAttribute\(string, string, bool\)

Marks this parameter as an option for a slash command.

```csharp
public OptionAttribute(string name, string description, bool autocomplete = false)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the option.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the option.

`autocomplete` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this option should autocomplete.

## Properties

### <a id="DSharpPlus_SlashCommands_OptionAttribute_Autocomplete"></a>Autocomplete

Gets whether this option should autocomplete.

```csharp
public bool Autocomplete { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_SlashCommands_OptionAttribute_Description"></a>Description

Gets the description of this option.

```csharp
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_OptionAttribute_Name"></a>Name

Gets the name of this option.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

