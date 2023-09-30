# Class DiscordException

Namespace: [DSharpPlus.Exceptions](DSharpPlus.Exceptions.md)  
Assembly: DSharpPlus.dll

```csharp
public abstract class DiscordException : Exception
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[DiscordException](DSharpPlus.Exceptions.DiscordException.md)

###### Derived

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md), 
[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md), 
[RateLimitException](DSharpPlus.Exceptions.RateLimitException.md), 
[RequestSizeException](DSharpPlus.Exceptions.RequestSizeException.md), 
[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md), 
[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

## Constructors

### <a id="DSharpPlus_Exceptions_DiscordException__ctor"></a>DiscordException\(\)

```csharp
public DiscordException()
```

### <a id="DSharpPlus_Exceptions_DiscordException__ctor_System_String_"></a>DiscordException\(string\)

```csharp
public DiscordException(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Exceptions_DiscordException__ctor_System_String_System_Exception_"></a>DiscordException\(string, Exception\)

```csharp
public DiscordException(string message, Exception innerException)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

`innerException` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

## Properties

### <a id="DSharpPlus_Exceptions_DiscordException_JsonMessage"></a>JsonMessage

Gets the JSON message received.

```csharp
public virtual string? JsonMessage { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Exceptions_DiscordException_Request"></a>Request

Gets the request that caused the exception.

```csharp
public virtual HttpRequestMessage? Request { get; }
```

#### Property Value

[HttpRequestMessage](https://learn.microsoft.com/dotnet/api/system.net.http.httprequestmessage)?

### <a id="DSharpPlus_Exceptions_DiscordException_Response"></a>Response

Gets the response to the request.

```csharp
public virtual HttpResponseMessage? Response { get; }
```

#### Property Value

[HttpResponseMessage](https://learn.microsoft.com/dotnet/api/system.net.http.httpresponsemessage)?

