# Method GetUnixTime

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Utilities_GetUnixTime_System_DateTimeOffset_"></a>GetUnixTime\(DateTimeOffset\)

Helper method to calculate Unix time seconds from a <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref> for targets that do not support this natively.

```csharp
public static long GetUnixTime(DateTimeOffset dto)
```

### Parameters

`dto` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

<xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref> to calculate Unix time for.

### Returns

[long](https://learn.microsoft.com/dotnet/api/system.int64)

Calculated Unix time.

