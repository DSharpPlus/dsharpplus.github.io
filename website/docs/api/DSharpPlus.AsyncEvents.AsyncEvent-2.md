# Class AsyncEvent<TSender, TArgs\>

Namespace: [DSharpPlus.AsyncEvents](DSharpPlus.AsyncEvents.md)  
Assembly: DSharpPlus.dll

Provides an implementation of an asynchronous event. Registered handlers are executed asynchronously,
in parallel, and potential exceptions are caught and sent to the specified exception handler.

```csharp
public sealed class AsyncEvent<TSender, TArgs> : AsyncEvent where TArgs : AsyncEventArgs
```

#### Type Parameters

`TSender` 

The type of the object to dispatch this event.

`TArgs` 

The type of the argument object for this event.

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[AsyncEvent](DSharpPlus.AsyncEvents.AsyncEvent.md) ← 
[AsyncEvent<TSender, TArgs\>](DSharpPlus.AsyncEvents.AsyncEvent\-2.md)

###### Inherited Members

[AsyncEvent.Name](DSharpPlus.AsyncEvents.AsyncEvent.md\#DSharpPlus\_AsyncEvents\_AsyncEvent\_Name)

## Constructors

### <a id="DSharpPlus_AsyncEvents_AsyncEvent_2__ctor_System_String_DSharpPlus_AsyncEvents_AsyncEventExceptionHandler__0__1__"></a>AsyncEvent\(string, AsyncEventExceptionHandler<TSender, TArgs\>\)

```csharp
public AsyncEvent(string name, AsyncEventExceptionHandler<TSender, TArgs> exceptionHandler)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

`exceptionHandler` [AsyncEventExceptionHandler](DSharpPlus.AsyncEvents.AsyncEventExceptionHandler\-2.md)<TSender, TArgs\>

## Methods

### <a id="DSharpPlus_AsyncEvents_AsyncEvent_2_InvokeAsync__0__1_"></a>InvokeAsync\(TSender, TArgs\)

Raises this event, invoking all registered handlers in parallel.

```csharp
public Task InvokeAsync(TSender sender, TArgs args)
```

#### Parameters

`sender` TSender

The instance that dispatched this event.

`args` TArgs

The arguments passed to this event.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_AsyncEvents_AsyncEvent_2_Register_DSharpPlus_AsyncEvents_AsyncEventHandler__0__1__"></a>Register\(AsyncEventHandler<TSender, TArgs\>\)

Registers a new handler for this event.

```csharp
public void Register(AsyncEventHandler<TSender, TArgs> handler)
```

#### Parameters

`handler` [AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<TSender, TArgs\>

#### Exceptions

[ArgumentNullException](https://learn.microsoft.com/dotnet/api/system.argumentnullexception)

Thrown if the specified handler was null.

### <a id="DSharpPlus_AsyncEvents_AsyncEvent_2_Unregister_DSharpPlus_AsyncEvents_AsyncEventHandler__0__1__"></a>Unregister\(AsyncEventHandler<TSender, TArgs\>\)

Unregisters a specific handler from this event.

```csharp
public void Unregister(AsyncEventHandler<TSender, TArgs> handler)
```

#### Parameters

`handler` [AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<TSender, TArgs\>

#### Exceptions

[ArgumentNullException](https://learn.microsoft.com/dotnet/api/system.argumentnullexception)

Thrown if the specified handler was null.

### <a id="DSharpPlus_AsyncEvents_AsyncEvent_2_UnregisterAll"></a>UnregisterAll\(\)

Unregisters all handlers from this event.

```csharp
public void UnregisterAll()
```

