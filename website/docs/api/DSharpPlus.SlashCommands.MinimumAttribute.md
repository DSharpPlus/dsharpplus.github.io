# Class MinimumAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Sets a minimum value for this slash command option. Only valid for <xref href="System.Int64" data-throw-if-not-resolved="false"></xref> or <xref href="System.Double" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
[AttributeUsage(AttributeTargets.Parameter, AllowMultiple = false)]
public class MinimumAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[MinimumAttribute](DSharpPlus.SlashCommands.MinimumAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_MinimumAttribute__ctor_System_Int64_"></a>MinimumAttribute\(long\)

Sets a minimum value for this slash command option. Only valid for <xref href="System.Int64" data-throw-if-not-resolved="false"></xref> or <xref href="System.Double" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
public MinimumAttribute(long value)
```

#### Parameters

`value` [long](https://learn.microsoft.com/dotnet/api/system.int64)

### <a id="DSharpPlus_SlashCommands_MinimumAttribute__ctor_System_Double_"></a>MinimumAttribute\(double\)

Sets a minimum value for this slash command option. Only valid for <xref href="System.Int64" data-throw-if-not-resolved="false"></xref> or <xref href="System.Double" data-throw-if-not-resolved="false"></xref> parameters.

```csharp
public MinimumAttribute(double value)
```

#### Parameters

`value` [double](https://learn.microsoft.com/dotnet/api/system.double)

## Properties

### <a id="DSharpPlus_SlashCommands_MinimumAttribute_Value"></a>Value

The value.

```csharp
public object Value { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)

