# Method Timestamp

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Formatter_Timestamp_System_TimeSpan_DSharpPlus_TimestampFormat_"></a>Timestamp\(TimeSpan, TimestampFormat\)

Creates a rendered timestamp.

```csharp
public static string Timestamp(TimeSpan time, TimestampFormat format = TimestampFormat.RelativeTime)
```

### Parameters

`time` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

The time from now.

`format` [TimestampFormat](DSharpPlus.TimestampFormat.md)

The format to render the timestamp in. Defaults to relative.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A formatted timestamp.

## <a id="DSharpPlus_Formatter_Timestamp_System_DateTime_DSharpPlus_TimestampFormat_"></a>Timestamp\(DateTime, TimestampFormat\)

Creates a rendered timestamp.

```csharp
public static string Timestamp(DateTime time, TimestampFormat format = TimestampFormat.RelativeTime)
```

### Parameters

`time` [DateTime](https://learn.microsoft.com/dotnet/api/system.datetime)

The time from now.

`format` [TimestampFormat](DSharpPlus.TimestampFormat.md)

The format to render the timestamp in. Defaults to relative.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A formatted timestamp.

## <a id="DSharpPlus_Formatter_Timestamp_System_DateTimeOffset_DSharpPlus_TimestampFormat_"></a>Timestamp\(DateTimeOffset, TimestampFormat\)

Creates a rendered timestamp.

```csharp
public static string Timestamp(DateTimeOffset time, TimestampFormat format = TimestampFormat.RelativeTime)
```

### Parameters

`time` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

Timestamp to format.

`format` [TimestampFormat](DSharpPlus.TimestampFormat.md)

The format to render the timestamp in. Defaults to relative.

### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A formatted timestamp.

