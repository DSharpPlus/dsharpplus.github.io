# Class DefaultLogger

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

```csharp
public class DefaultLogger : ILogger<BaseDiscordClient>, ILogger
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DefaultLogger](DSharpPlus.DefaultLogger.md)

###### Implements

[ILogger<BaseDiscordClient\>](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.ilogger\-1), 
[ILogger](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.ilogger)

## Methods

### <a id="DSharpPlus_DefaultLogger_BeginScope__1___0_"></a>BeginScope<TState\>\(TState\)

Begins a logical operation scope.

```csharp
public IDisposable BeginScope<TState>(TState state)
```

#### Parameters

`state` TState

The identifier for the scope.

#### Returns

[IDisposable](https://learn.microsoft.com/dotnet/api/system.idisposable)

An <xref href="System.IDisposable" data-throw-if-not-resolved="false"></xref> that ends the logical operation scope on dispose.

#### Type Parameters

`TState` 

The type of the state to begin scope for.

### <a id="DSharpPlus_DefaultLogger_IsEnabled_Microsoft_Extensions_Logging_LogLevel_"></a>IsEnabled\(LogLevel\)

Checks if the given <code class="paramref">logLevel</code> is enabled.

```csharp
public bool IsEnabled(LogLevel logLevel)
```

#### Parameters

`logLevel` [LogLevel](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.loglevel)

Level to be checked.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

<code>true</code> if enabled.

### <a id="DSharpPlus_DefaultLogger_Log__1_Microsoft_Extensions_Logging_LogLevel_Microsoft_Extensions_Logging_EventId___0_System_Exception_System_Func___0_System_Exception_System_String__"></a>Log<TState\>\(LogLevel, EventId, TState, Exception, Func<TState, Exception, string\>\)

Writes a log entry.

```csharp
public void Log<TState>(LogLevel logLevel, EventId eventId, TState state, Exception exception, Func<TState, Exception, string> formatter)
```

#### Parameters

`logLevel` [LogLevel](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.loglevel)

Entry will be written on this level.

`eventId` [EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

Id of the event.

`state` TState

The entry to be written. Can be also an object.

`exception` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

The exception related to this entry.

`formatter` [Func](https://learn.microsoft.com/dotnet/api/system.func\-3)<TState, [Exception](https://learn.microsoft.com/dotnet/api/system.exception), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Function to create a <xref href="System.String" data-throw-if-not-resolved="false"></xref> message of the <code class="paramref">state</code> and <code class="paramref">exception</code>.

#### Type Parameters

`TState` 

The type of the object to be written.

