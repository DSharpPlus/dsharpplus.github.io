# Class SessionBucket

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

Represents the bucket limits for identifying to Discord.
<p>This is only relevant for clients that are manually sharding.</p>

```csharp
public class SessionBucket
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SessionBucket](DSharpPlus.Net.SessionBucket.md)

## Properties

### <a id="DSharpPlus_Net_SessionBucket_MaxConcurrency"></a>MaxConcurrency

Gets the maximum amount of shards that can boot concurrently.

```csharp
[JsonProperty("max_concurrency")]
public int MaxConcurrency { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Net_SessionBucket_Remaining"></a>Remaining

Gets the remaining amount of sessions for this token.

```csharp
[JsonProperty("remaining")]
public int Remaining { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Net_SessionBucket_ResetAfter"></a>ResetAfter

Gets the datetime when the <xref href="DSharpPlus.Net.SessionBucket.Remaining" data-throw-if-not-resolved="false"></xref> will reset.

```csharp
[JsonIgnore]
public DateTimeOffset ResetAfter { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Net_SessionBucket_Total"></a>Total

Gets the total amount of sessions per token.

```csharp
[JsonProperty("total")]
public int Total { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_Net_SessionBucket_ToString"></a>ToString\(\)

Returns a string that represents the current object.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A string that represents the current object.

