# Method ConvertArgument<T\>

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_ConvertArgument__1_System_String_DSharpPlus_CommandsNext_CommandContext_"></a>ConvertArgument<T\>\(string, CommandContext\)

Converts a string to specified type.

```csharp
public Task<object> ConvertArgument<T>(string value, CommandContext ctx)
```

### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Value to convert.

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which to convert to.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[object](https://learn.microsoft.com/dotnet/api/system.object)\>

Converted object.

### Type Parameters

`T` 

Type to convert to.

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_ConvertArgument_System_String_DSharpPlus_CommandsNext_CommandContext_System_Type_"></a>ConvertArgument\(string?, CommandContext, Type\)

Converts a string to specified type.

```csharp
public Task<object> ConvertArgument(string? value, CommandContext ctx, Type type)
```

### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Value to convert.

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which to convert to.

`type` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type to convert to.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[object](https://learn.microsoft.com/dotnet/api/system.object)\>

Converted object.

