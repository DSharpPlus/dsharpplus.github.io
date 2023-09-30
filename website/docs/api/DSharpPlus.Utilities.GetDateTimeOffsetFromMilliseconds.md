# Method GetDateTimeOffsetFromMilliseconds

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Utilities_GetDateTimeOffsetFromMilliseconds_System_Int64_System_Boolean_"></a>GetDateTimeOffsetFromMilliseconds\(long, bool\)

Helper method to create a <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref> from Unix time milliseconds for targets that do not support this natively.

```csharp
public static DateTimeOffset GetDateTimeOffsetFromMilliseconds(long unixTime, bool shouldThrow = true)
```

### Parameters

`unixTime` [long](https://learn.microsoft.com/dotnet/api/system.int64)

Unix time milliseconds to convert.

`shouldThrow` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the method should throw on failure. Defaults to true.

### Returns

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

Calculated <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref>.

