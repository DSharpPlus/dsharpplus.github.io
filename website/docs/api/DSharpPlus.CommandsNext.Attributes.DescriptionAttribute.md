# Class DescriptionAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Gives this command, group, or argument a description, which is used when listing help.

```csharp
[AttributeUsage(AttributeTargets.Class|AttributeTargets.Method|AttributeTargets.Parameter, AllowMultiple = false)]
public sealed class DescriptionAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[DescriptionAttribute](DSharpPlus.CommandsNext.Attributes.DescriptionAttribute.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_DescriptionAttribute__ctor_System_String_"></a>DescriptionAttribute\(string\)

Gives this command, group, or argument a description, which is used when listing help.

```csharp
public DescriptionAttribute(string description)
```

#### Parameters

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_DescriptionAttribute_Description"></a>Description

Gets the description for this command, group, or argument.

```csharp
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

