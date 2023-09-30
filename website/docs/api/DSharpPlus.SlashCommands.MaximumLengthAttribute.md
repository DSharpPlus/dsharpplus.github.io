# Class MaximumLengthAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Sets a maximum allowed length for this slash command option. Only valid for <xref href="System.String" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = false)]
public class MaximumLengthAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[MaximumLengthAttribute](DSharpPlus.SlashCommands.MaximumLengthAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_MaximumLengthAttribute__ctor_System_Int32_"></a>MaximumLengthAttribute\(int\)

Sets a maximum allowed length for this slash command option. Only valid for <xref href="System.String" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
public MaximumLengthAttribute(int value)
```

#### Parameters

`value` [int](https://learn.microsoft.com/dotnet/api/system.int32)

## Properties

### <a id="DSharpPlus_SlashCommands_MaximumLengthAttribute_Value"></a>Value

The value.

```csharp
public int Value { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

