# Class AsyncEvent

Namespace: [DSharpPlus.AsyncEvents](DSharpPlus.AsyncEvents.md)  
Assembly: DSharpPlus.dll

Represents a non-generic base for async events.

```csharp
public abstract class AsyncEvent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[AsyncEvent](DSharpPlus.AsyncEvents.AsyncEvent.md)

###### Derived

[AsyncEvent<TSender, TArgs\>](DSharpPlus.AsyncEvents.AsyncEvent\-2.md)

## Constructors

### <a id="DSharpPlus_AsyncEvents_AsyncEvent__ctor_System_String_"></a>AsyncEvent\(string\)

```csharp
protected AsyncEvent(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

## Properties

### <a id="DSharpPlus_AsyncEvents_AsyncEvent_Name"></a>Name

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

