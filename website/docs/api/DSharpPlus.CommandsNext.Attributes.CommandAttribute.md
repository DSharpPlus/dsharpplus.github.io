# Class CommandAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Marks this method as a command.

```csharp
[AttributeUsage(AttributeTargets.Method, AllowMultiple = false)]
public sealed class CommandAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[CommandAttribute](DSharpPlus.CommandsNext.Attributes.CommandAttribute.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_CommandAttribute__ctor"></a>CommandAttribute\(\)

Marks this method as a command, using the method's name as command name.

```csharp
public CommandAttribute()
```

### <a id="DSharpPlus_CommandsNext_Attributes_CommandAttribute__ctor_System_String_"></a>CommandAttribute\(string\)

Marks this method as a command with specified name.

```csharp
public CommandAttribute(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of this command.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_CommandAttribute_Name"></a>Name

Gets the name of this command.

```csharp
public string? Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

