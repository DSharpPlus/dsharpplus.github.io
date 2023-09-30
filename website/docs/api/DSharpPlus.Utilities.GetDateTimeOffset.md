# Method GetDateTimeOffset

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Utilities_GetDateTimeOffset_System_Int64_System_Boolean_"></a>GetDateTimeOffset\(long, bool\)

Helper method to create a <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref> from Unix time seconds for targets that do not support this natively.

```csharp
public static DateTimeOffset GetDateTimeOffset(long unixTime, bool shouldThrow = true)
```

### Parameters

`unixTime` [long](https://learn.microsoft.com/dotnet/api/system.int64)

Unix time seconds to convert.

`shouldThrow` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the method should throw on failure. Defaults to true.

### Returns

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

Calculated <xref href="System.DateTimeOffset" data-throw-if-not-resolved="false"></xref>.

