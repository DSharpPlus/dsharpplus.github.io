# Method InvokeAsync

Namespace: [DSharpPlus.AsyncEvents](DSharpPlus.AsyncEvents.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_AsyncEvents_AsyncEvent_2_InvokeAsync__0__1_"></a>InvokeAsync\(TSender, TArgs\)

Raises this event, invoking all registered handlers in parallel.

```csharp
public Task InvokeAsync(TSender sender, TArgs args)
```

### Parameters

`sender` TSender

The instance that dispatched this event.

`args` TArgs

The arguments passed to this event.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

