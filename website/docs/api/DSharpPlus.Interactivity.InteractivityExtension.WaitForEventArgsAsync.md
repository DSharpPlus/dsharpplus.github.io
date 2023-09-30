# Method WaitForEventArgsAsync<T\>

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForEventArgsAsync__1_System_Func___0_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForEventArgsAsync<T\>\(Func<T, bool\>, TimeSpan?\)

Waits for specific event args to be received. Make sure the appropriate <xref href="DSharpPlus.DiscordIntents" data-throw-if-not-resolved="false"></xref> are registered, if needed.

```csharp
public Task<InteractivityResult<T>> WaitForEventArgsAsync<T>(Func<T, bool> predicate, TimeSpan? timeoutoverride = null) where T : AsyncEventArgs
```

### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<T, [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<T\>\>

### Type Parameters

`T` 

