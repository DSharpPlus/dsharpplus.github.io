# Delegate AsyncEventExceptionHandler<TSender, TArgs\>

Namespace: [DSharpPlus.AsyncEvents](DSharpPlus.AsyncEvents.md)  
Assembly: DSharpPlus.dll

Provides a registration surface for a handler for exceptions raised by an async event or its registered
event handlers.

```csharp
public delegate void AsyncEventExceptionHandler<TSender, TArgs>(AsyncEvent<TSender, TArgs> @event, Exception exception, AsyncEventHandler<TSender, TArgs> handler, TSender sender, TArgs args) where TArgs : AsyncEventArgs
```

#### Parameters

`event` [AsyncEvent](DSharpPlus.AsyncEvents.AsyncEvent\-2.md)<TSender, TArgs\>

The async event that threw this exception.

`exception` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

The thrown exception.

`handler` [AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<TSender, TArgs\>

The async event handler that threw this exception.

`sender` TSender

The instance that dispatched this event.

`args` TArgs

The arguments passed to this event.

#### Type Parameters

`TSender` 

The type of the event dispatcher.

`TArgs` 

The type of the argument object for this event.

