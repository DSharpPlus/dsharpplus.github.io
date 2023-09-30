# Struct ArgumentBindingResult

Namespace: [DSharpPlus.CommandsNext.Converters](DSharpPlus.CommandsNext.Converters.md)  
Assembly: DSharpPlus.CommandsNext.dll

```csharp
public struct ArgumentBindingResult
```

## Constructors

### <a id="DSharpPlus_CommandsNext_Converters_ArgumentBindingResult__ctor_System_Object___System_Collections_Generic_IReadOnlyList_System_String__"></a>ArgumentBindingResult\(object?\[\], IReadOnlyList<string\>\)

```csharp
public ArgumentBindingResult(object?[] converted, IReadOnlyList<string> raw)
```

#### Parameters

`converted` [object](https://learn.microsoft.com/dotnet/api/system.object)?\[\]

`raw` [IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_CommandsNext_Converters_ArgumentBindingResult__ctor_System_Exception_"></a>ArgumentBindingResult\(Exception\)

```csharp
public ArgumentBindingResult(Exception ex)
```

#### Parameters

`ex` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

## Properties

### <a id="DSharpPlus_CommandsNext_Converters_ArgumentBindingResult_Converted"></a>Converted

```csharp
public readonly object?[] Converted { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)?\[\]

### <a id="DSharpPlus_CommandsNext_Converters_ArgumentBindingResult_IsSuccessful"></a>IsSuccessful

```csharp
public readonly bool IsSuccessful { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_Converters_ArgumentBindingResult_Raw"></a>Raw

```csharp
public readonly IReadOnlyList<string> Raw { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_CommandsNext_Converters_ArgumentBindingResult_Reason"></a>Reason

```csharp
public readonly Exception? Reason { get; }
```

#### Property Value

[Exception](https://learn.microsoft.com/dotnet/api/system.exception)?

