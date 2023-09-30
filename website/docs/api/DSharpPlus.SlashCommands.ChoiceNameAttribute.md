# Class ChoiceNameAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Sets the name for this enum choice.

```csharp
[AttributeUsage(AttributeTargets.All, AllowMultiple = false)]
public sealed class ChoiceNameAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[ChoiceNameAttribute](DSharpPlus.SlashCommands.ChoiceNameAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_ChoiceNameAttribute__ctor_System_String_"></a>ChoiceNameAttribute\(string\)

Sets the name for this enum choice.

```csharp
public ChoiceNameAttribute(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name for this enum choice.

## Properties

### <a id="DSharpPlus_SlashCommands_ChoiceNameAttribute_Name"></a>Name

The name.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

