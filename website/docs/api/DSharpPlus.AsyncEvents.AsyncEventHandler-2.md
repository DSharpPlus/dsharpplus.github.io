# Delegate AsyncEventHandler<TSender, TArgs\>

Namespace: [DSharpPlus.AsyncEvents](DSharpPlus.AsyncEvents.md)  
Assembly: DSharpPlus.dll

Provides a registration surface for asynchronous events using C# language event syntax.

```csharp
public delegate Task AsyncEventHandler<in TSender, in TArgs>(TSender sender, TArgs args) where TArgs : AsyncEventArgs
```

#### Parameters

`sender` TSender

The instance that dispatched this event.

`args` TArgs

The arguments passed to this event.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Type Parameters

`TSender` 

The type of the event dispatcher.

`TArgs` 

The type of the argument object for this event.

