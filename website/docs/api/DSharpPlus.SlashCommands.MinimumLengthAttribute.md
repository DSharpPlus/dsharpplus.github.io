# Class MinimumLengthAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Sets a minimum allowed length for this slash command option. Only valid for <xref href="System.String" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = false)]
public class MinimumLengthAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[MinimumLengthAttribute](DSharpPlus.SlashCommands.MinimumLengthAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_MinimumLengthAttribute__ctor_System_Int32_"></a>MinimumLengthAttribute\(int\)

Sets a minimum allowed length for this slash command option. Only valid for <xref href="System.String" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
public MinimumLengthAttribute(int value)
```

#### Parameters

`value` [int](https://learn.microsoft.com/dotnet/api/system.int32)

## Properties

### <a id="DSharpPlus_SlashCommands_MinimumLengthAttribute_Value"></a>Value

The value.

```csharp
public int Value { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

