# Class GroupAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Marks this class as a command group.

```csharp
[AttributeUsage(AttributeTargets.Class, AllowMultiple = false)]
public sealed class GroupAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[GroupAttribute](DSharpPlus.CommandsNext.Attributes.GroupAttribute.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_GroupAttribute__ctor"></a>GroupAttribute\(\)

Marks this class as a command group, using the class' name as group name.

```csharp
public GroupAttribute()
```

### <a id="DSharpPlus_CommandsNext_Attributes_GroupAttribute__ctor_System_String_"></a>GroupAttribute\(string\)

Marks this class as a command group with specified name.

```csharp
public GroupAttribute(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of this group.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_GroupAttribute_Name"></a>Name

Gets the name of this group.

```csharp
public string? Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

