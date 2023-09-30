# Constructor InvalidOverloadException

Namespace: [DSharpPlus.CommandsNext.Exceptions](DSharpPlus.CommandsNext.Exceptions.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Exceptions_InvalidOverloadException__ctor_System_String_System_Reflection_MethodInfo_System_Reflection_ParameterInfo_"></a>InvalidOverloadException\(string, MethodInfo, ParameterInfo?\)

Creates a new <xref href="DSharpPlus.CommandsNext.Exceptions.InvalidOverloadException" data-throw-if-not-resolved="false"></xref>.

```csharp
public InvalidOverloadException(string message, MethodInfo method, ParameterInfo? parameter)
```

### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

Exception message.

`method` [MethodInfo](https://learn.microsoft.com/dotnet/api/system.reflection.methodinfo)

Method that caused the problem.

`parameter` [ParameterInfo](https://learn.microsoft.com/dotnet/api/system.reflection.parameterinfo)?

Method argument that caused the problem.

## <a id="DSharpPlus_CommandsNext_Exceptions_InvalidOverloadException__ctor_System_String_System_Reflection_MethodInfo_"></a>InvalidOverloadException\(string, MethodInfo\)

Creates a new <xref href="DSharpPlus.CommandsNext.Exceptions.InvalidOverloadException" data-throw-if-not-resolved="false"></xref>.

```csharp
public InvalidOverloadException(string message, MethodInfo method)
```

### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

Exception message.

`method` [MethodInfo](https://learn.microsoft.com/dotnet/api/system.reflection.methodinfo)

Method that caused the problem.

