# Class CommandArgument

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

```csharp
public sealed class CommandArgument
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandArgument](DSharpPlus.CommandsNext.CommandArgument.md)

## Properties

### <a id="DSharpPlus_CommandsNext_CommandArgument_CustomAttributes"></a>CustomAttributes

Gets the custom attributes attached to this argument.

```csharp
public IReadOnlyCollection<Attribute> CustomAttributes { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute)\>

### <a id="DSharpPlus_CommandsNext_CommandArgument_DefaultValue"></a>DefaultValue

Gets this argument's default value.

```csharp
public object? DefaultValue { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)?

### <a id="DSharpPlus_CommandsNext_CommandArgument_Description"></a>Description

Gets this argument's description.

```csharp
public string? Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_CommandsNext_CommandArgument_IsCatchAll"></a>IsCatchAll

Gets whether this argument catches all remaining arguments.

```csharp
public bool IsCatchAll { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_CommandArgument_IsOptional"></a>IsOptional

Gets whether this argument is optional.

```csharp
public bool IsOptional { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_CommandArgument_Name"></a>Name

Gets this argument's name.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_CommandsNext_CommandArgument_Type"></a>Type

Gets this argument's type.

```csharp
public Type Type { get; }
```

#### Property Value

[Type](https://learn.microsoft.com/dotnet/api/system.type)

