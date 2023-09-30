# Struct RestResponse

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

Represents a response sent by the remote HTTP party.

```csharp
public record struct RestResponse
```

## Properties

### <a id="DSharpPlus_Net_RestResponse_Response"></a>Response

Gets the contents of the response sent by the remote party.

```csharp
public readonly string? Response { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Net_RestResponse_ResponseCode"></a>ResponseCode

Gets the response code sent by the remote party.

```csharp
public readonly HttpStatusCode? ResponseCode { get; }
```

#### Property Value

[HttpStatusCode](https://learn.microsoft.com/dotnet/api/system.net.httpstatuscode)?

