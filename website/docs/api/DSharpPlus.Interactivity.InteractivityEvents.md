# Class InteractivityEvents

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

Contains well-defined event IDs used by the Interactivity extension.

```csharp
public static class InteractivityEvents
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[InteractivityEvents](DSharpPlus.Interactivity.InteractivityEvents.md)

## Properties

### <a id="DSharpPlus_Interactivity_InteractivityEvents_InteractivityCollectorError"></a>InteractivityCollectorError

Events pertaining to event collection.

```csharp
public static EventId InteractivityCollectorError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Interactivity_InteractivityEvents_InteractivityPaginationError"></a>InteractivityPaginationError

Events pertaining to pagination.

```csharp
public static EventId InteractivityPaginationError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Interactivity_InteractivityEvents_InteractivityPollError"></a>InteractivityPollError

Events pertaining to polling.

```csharp
public static EventId InteractivityPollError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Interactivity_InteractivityEvents_InteractivityWaitError"></a>InteractivityWaitError

Events pertaining to errors that happen during waiting for events.

```csharp
public static EventId InteractivityWaitError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Interactivity_InteractivityEvents_Misc"></a>Misc

Miscellaneous events, that do not fit in any other category.

```csharp
public static EventId Misc { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

