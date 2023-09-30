# Method WaitForCustomComponentPaginationAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForCustomComponentPaginationAsync_DSharpPlus_Interactivity_EventHandling_IPaginationRequest_"></a>WaitForCustomComponentPaginationAsync\(IPaginationRequest\)

Waits for custom button-based pagination request to finish.
<br />
This does <i><b>not</b></i> invoke <xref href="DSharpPlus.Interactivity.EventHandling.IPaginationRequest.DoCleanupAsync" data-throw-if-not-resolved="false"></xref>.

```csharp
public Task WaitForCustomComponentPaginationAsync(IPaginationRequest request)
```

### Parameters

`request` [IPaginationRequest](DSharpPlus.Interactivity.EventHandling.IPaginationRequest.md)

The request to wait for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

