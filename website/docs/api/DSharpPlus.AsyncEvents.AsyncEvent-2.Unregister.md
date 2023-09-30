# Method Unregister

Namespace: [DSharpPlus.AsyncEvents](DSharpPlus.AsyncEvents.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_AsyncEvents_AsyncEvent_2_Unregister_DSharpPlus_AsyncEvents_AsyncEventHandler__0__1__"></a>Unregister\(AsyncEventHandler<TSender, TArgs\>\)

Unregisters a specific handler from this event.

```csharp
public void Unregister(AsyncEventHandler<TSender, TArgs> handler)
```

### Parameters

`handler` [AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<TSender, TArgs\>

### Exceptions

[ArgumentNullException](https://learn.microsoft.com/dotnet/api/system.argumentnullexception)

Thrown if the specified handler was null.

