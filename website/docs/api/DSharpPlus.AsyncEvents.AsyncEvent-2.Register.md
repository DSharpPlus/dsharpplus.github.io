# Method Register

Namespace: [DSharpPlus.AsyncEvents](DSharpPlus.AsyncEvents.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_AsyncEvents_AsyncEvent_2_Register_DSharpPlus_AsyncEvents_AsyncEventHandler__0__1__"></a>Register\(AsyncEventHandler<TSender, TArgs\>\)

Registers a new handler for this event.

```csharp
public void Register(AsyncEventHandler<TSender, TArgs> handler)
```

### Parameters

`handler` [AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<TSender, TArgs\>

### Exceptions

[ArgumentNullException](https://learn.microsoft.com/dotnet/api/system.argumentnullexception)

Thrown if the specified handler was null.

