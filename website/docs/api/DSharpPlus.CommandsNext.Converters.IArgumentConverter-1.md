# Interface IArgumentConverter<T\>

Namespace: [DSharpPlus.CommandsNext.Converters](DSharpPlus.CommandsNext.Converters.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a converter for specific argument type.

```csharp
public interface IArgumentConverter<T> : IArgumentConverter
```

#### Type Parameters

`T` 

Type for which the converter is to be registered.

###### Implements

[IArgumentConverter](DSharpPlus.CommandsNext.Converters.IArgumentConverter.md)

## Methods

### <a id="DSharpPlus_CommandsNext_Converters_IArgumentConverter_1_ConvertAsync_System_String_DSharpPlus_CommandsNext_CommandContext_"></a>ConvertAsync\(string, CommandContext\)

Converts the raw value into the specified type.

```csharp
Task<Optional<T>> ConvertAsync(string value, CommandContext ctx)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Value to convert.

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the value will be converted.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[Optional](DSharpPlus.Entities.Optional\-1.md)<T\>\>

A structure containing information whether the value was converted, and, if so, the converted value.

