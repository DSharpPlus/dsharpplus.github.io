# Class BadRequestException

Namespace: [DSharpPlus.Exceptions](DSharpPlus.Exceptions.md)  
Assembly: DSharpPlus.dll

Represents an exception thrown when a malformed request is sent.

```csharp
public class BadRequestException : DiscordException
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[DiscordException](DSharpPlus.Exceptions.DiscordException.md) ← 
[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

###### Inherited Members

[DiscordException.Request](DSharpPlus.Exceptions.DiscordException.md\#DSharpPlus\_Exceptions\_DiscordException\_Request), 
[DiscordException.Response](DSharpPlus.Exceptions.DiscordException.md\#DSharpPlus\_Exceptions\_DiscordException\_Response), 
[DiscordException.JsonMessage](DSharpPlus.Exceptions.DiscordException.md\#DSharpPlus\_Exceptions\_DiscordException\_JsonMessage)

## Properties

### <a id="DSharpPlus_Exceptions_BadRequestException_Code"></a>Code

Gets the error code for this exception.

```csharp
public int Code { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Exceptions_BadRequestException_Errors"></a>Errors

Gets the form error responses in JSON format.

```csharp
public string? Errors { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

