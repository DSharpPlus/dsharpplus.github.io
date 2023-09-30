# Method BeginScope<TState\>

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DefaultLogger_BeginScope__1___0_"></a>BeginScope<TState\>\(TState\)

Begins a logical operation scope.

```csharp
public IDisposable BeginScope<TState>(TState state)
```

### Parameters

`state` TState

The identifier for the scope.

### Returns

[IDisposable](https://learn.microsoft.com/dotnet/api/system.idisposable)

An <xref href="System.IDisposable" data-throw-if-not-resolved="false"></xref> that ends the logical operation scope on dispose.

### Type Parameters

`TState` 

The type of the state to begin scope for.

