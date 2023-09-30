# Method RegisterUserFriendlyTypeName<T\>

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterUserFriendlyTypeName__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__System_String_"></a>RegisterUserFriendlyTypeName<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>, string\)

Registers a user-friendly type name.

```csharp
public static void RegisterUserFriendlyTypeName<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, string value)
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register the name on.

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name to register.

### Type Parameters

`T` 

Type to register the name for.

