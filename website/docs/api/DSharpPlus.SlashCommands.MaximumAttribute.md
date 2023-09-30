# Class MaximumAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Sets a maximum value for this slash command option. Only valid for <xref href="System.Int64" data-throw-if-not-resolved="false"></xref> or <xref href="System.Double" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = false)]
public class MaximumAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[MaximumAttribute](DSharpPlus.SlashCommands.MaximumAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_MaximumAttribute__ctor_System_Int64_"></a>MaximumAttribute\(long\)

Sets a maximum value for this slash command option. Only valid for <xref href="System.Int64" data-throw-if-not-resolved="false"></xref> or <xref href="System.Double" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
public MaximumAttribute(long value)
```

#### Parameters

`value` [long](https://learn.microsoft.com/dotnet/api/system.int64)

### <a id="DSharpPlus_SlashCommands_MaximumAttribute__ctor_System_Double_"></a>MaximumAttribute\(double\)

Sets a maximum value for this slash command option. Only valid for <xref href="System.Int64" data-throw-if-not-resolved="false"></xref> or <xref href="System.Double" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
public MaximumAttribute(double value)
```

#### Parameters

`value` [double](https://learn.microsoft.com/dotnet/api/system.double)

## Properties

### <a id="DSharpPlus_SlashCommands_MaximumAttribute_Value"></a>Value

The value.

```csharp
public object Value { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)

