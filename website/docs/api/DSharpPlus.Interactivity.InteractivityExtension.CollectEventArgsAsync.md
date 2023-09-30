# Method CollectEventArgsAsync<T\>

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_CollectEventArgsAsync__1_System_Func___0_System_Boolean__System_Nullable_System_TimeSpan__"></a>CollectEventArgsAsync<T\>\(Func<T, bool\>, TimeSpan?\)

```csharp
public Task<ReadOnlyCollection<T>> CollectEventArgsAsync<T>(Func<T, bool> predicate, TimeSpan? timeoutoverride = null) where T : AsyncEventArgs
```

### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<T, [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<T\>\>

### Type Parameters

`T` 

