# Class EnumConverter<T\>

Namespace: [DSharpPlus.CommandsNext.Converters](DSharpPlus.CommandsNext.Converters.md)  
Assembly: DSharpPlus.CommandsNext.dll

Converts a string to an enum type.

```csharp
public class EnumConverter<T> : IArgumentConverter<T>, IArgumentConverter where T : struct, IComparable, IConvertible, IFormattable
```

#### Type Parameters

`T` 

Type of enum to convert.

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EnumConverter<T\>](DSharpPlus.CommandsNext.Converters.EnumConverter\-1.md)

###### Implements

[IArgumentConverter<T\>](DSharpPlus.CommandsNext.Converters.IArgumentConverter\-1.md), 
[IArgumentConverter](DSharpPlus.CommandsNext.Converters.IArgumentConverter.md)

