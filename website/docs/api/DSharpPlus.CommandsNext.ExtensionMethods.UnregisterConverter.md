# Method UnregisterConverter<T\>

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_UnregisterConverter__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__"></a>UnregisterConverter<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>\)

Unregisters an argument converter for specified type.

```csharp
public static void UnregisterConverter<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions)
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to unregister the converter on.

### Type Parameters

`T` 

Type for which to unregister the converter.

