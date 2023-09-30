# Class ChoiceAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Adds a choice for this slash command option.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = true)]
public sealed class ChoiceAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[ChoiceAttribute](DSharpPlus.SlashCommands.ChoiceAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_ChoiceAttribute__ctor_System_String_System_String_"></a>ChoiceAttribute\(string, string\)

Adds a choice to the slash command option.

```csharp
public ChoiceAttribute(string name, string value)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the choice.

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

The value of the choice.

### <a id="DSharpPlus_SlashCommands_ChoiceAttribute__ctor_System_String_System_Int64_"></a>ChoiceAttribute\(string, long\)

Adds a choice to the slash command option.

```csharp
public ChoiceAttribute(string name, long value)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the choice.

`value` [long](https://learn.microsoft.com/dotnet/api/system.int64)

The value of the choice.

### <a id="DSharpPlus_SlashCommands_ChoiceAttribute__ctor_System_String_System_Double_"></a>ChoiceAttribute\(string, double\)

Adds a choice to the slash command option.

```csharp
public ChoiceAttribute(string name, double value)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the choice.

`value` [double](https://learn.microsoft.com/dotnet/api/system.double)

The value of the choice.

## Properties

### <a id="DSharpPlus_SlashCommands_ChoiceAttribute_Name"></a>Name

Gets the name of the choice.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_ChoiceAttribute_Value"></a>Value

Gets the value of the choice.

```csharp
public object Value { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)

