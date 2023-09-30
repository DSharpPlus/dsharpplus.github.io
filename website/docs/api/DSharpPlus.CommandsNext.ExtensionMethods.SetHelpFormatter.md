# Method SetHelpFormatter<T\>

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_SetHelpFormatter__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__"></a>SetHelpFormatter<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>\)

Sets the help formatter to use with the default help command.

```csharp
public static void SetHelpFormatter<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions) where T : BaseHelpFormatter
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to set the help formatter on.

### Type Parameters

`T` 

Type of the formatter to use.

