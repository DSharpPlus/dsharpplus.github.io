# Method RegisterConverter<T\>

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterConverter__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__DSharpPlus_CommandsNext_Converters_IArgumentConverter___0__"></a>RegisterConverter<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>, IArgumentConverter<T\>\)

Registers an argument converter for specified type.

```csharp
public static void RegisterConverter<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, IArgumentConverter<T> converter)
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register the converter on.

`converter` [IArgumentConverter](DSharpPlus.CommandsNext.Converters.IArgumentConverter\-1.md)<T\>

Converter to register.

### Type Parameters

`T` 

Type for which to register the converter.

