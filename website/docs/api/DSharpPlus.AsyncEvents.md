# Namespace DSharpPlus.AsyncEvents

### Classes

[AsyncEvent](DSharpPlus.AsyncEvents.AsyncEvent.md)

Represents a non-generic base for async events.

[AsyncEvent<TSender, TArgs\>](DSharpPlus.AsyncEvents.AsyncEvent\-2.md)

Provides an implementation of an asynchronous event. Registered handlers are executed asynchronously,
in parallel, and potential exceptions are caught and sent to the specified exception handler.

[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md)

A base class for arguments passed to an event handler.

### Delegates

[AsyncEventExceptionHandler<TSender, TArgs\>](DSharpPlus.AsyncEvents.AsyncEventExceptionHandler\-2.md)

Provides a registration surface for a handler for exceptions raised by an async event or its registered
event handlers.

[AsyncEventHandler<TSender, TArgs\>](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)

Provides a registration surface for asynchronous events using C# language event syntax.

