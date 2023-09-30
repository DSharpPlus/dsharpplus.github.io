# Interface IPaginationRequest

Namespace: [DSharpPlus.Interactivity.EventHandling](DSharpPlus.Interactivity.EventHandling.md)  
Assembly: DSharpPlus.Interactivity.dll

```csharp
public interface IPaginationRequest
```

## Properties

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_PageCount"></a>PageCount

Returns the number of pages.

```csharp
int PageCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_DoCleanupAsync"></a>DoCleanupAsync\(\)

Tells the request to perform cleanup.

```csharp
Task DoCleanupAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_GetButtonsAsync"></a>GetButtonsAsync\(\)

Requests the message buttons from the pagination request.

```csharp
Task<IEnumerable<DiscordButtonComponent>> GetButtonsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)\>\>

The buttons.

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_GetEmojisAsync"></a>GetEmojisAsync\(\)

Requests message emojis from pagination request.

```csharp
Task<PaginationEmojis> GetEmojisAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[PaginationEmojis](DSharpPlus.Interactivity.PaginationEmojis.md)\>

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_GetMessageAsync"></a>GetMessageAsync\(\)

Gets pagination message from this request.

```csharp
Task<DiscordMessage> GetMessageAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_GetPageAsync"></a>GetPageAsync\(\)

Returns the current page.

```csharp
Task<Page> GetPageAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_GetTaskCompletionSourceAsync"></a>GetTaskCompletionSourceAsync\(\)

Get this request's Task Completion Source.

```csharp
Task<TaskCompletionSource<bool>> GetTaskCompletionSourceAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[TaskCompletionSource](https://learn.microsoft.com/dotnet/api/system.threading.tasks.taskcompletionsource\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>\>

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_GetUserAsync"></a>GetUserAsync\(\)

Gets the user this pagination applies to.

```csharp
Task<DiscordUser> GetUserAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_NextPageAsync"></a>NextPageAsync\(\)

Tells the request to increase its index by one.

```csharp
Task NextPageAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_PreviousPageAsync"></a>PreviousPageAsync\(\)

Tells the request to decrease its index by one.

```csharp
Task PreviousPageAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_SkipLeftAsync"></a>SkipLeftAsync\(\)

Tells the request to set its index to the first page.

```csharp
Task SkipLeftAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_EventHandling_IPaginationRequest_SkipRightAsync"></a>SkipRightAsync\(\)

Tells the request to set its index to the last page.

```csharp
Task SkipRightAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

