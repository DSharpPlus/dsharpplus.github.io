# Class DiscordThreadChannelMember

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public class DiscordThreadChannelMember
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_Guild"></a>Guild

Gets the guild to which this channel belongs.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_Id"></a>Id

Gets ID of the user.

```csharp
[JsonProperty("user_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong Id { get; set; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_JoinTimeStamp"></a>JoinTimeStamp

Gets timestamp when the user joined the thread.

```csharp
[JsonProperty("join_timestamp", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset? JoinTimeStamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_Member"></a>Member

Gets the DiscordMember that represents this ThreadMember. Can be a skeleton object.

```csharp
[JsonIgnore]
public DiscordMember Member { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_Thread"></a>Thread

Gets the category that contains this channel. For threads, gets the channel this thread was created in.

```csharp
[JsonIgnore]
public DiscordChannel Thread { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_ThreadId"></a>ThreadId

Gets ID of the thread.

```csharp
[JsonProperty("id", NullValueHandling = NullValueHandling.Ignore)]
public ulong ThreadId { get; set; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

## Methods

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_Equals_DSharpPlus_Entities_DiscordThreadChannelMember_"></a>Equals\(DiscordThreadChannelMember\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordThreadChannelMember e)
```

#### Parameters

`e` [DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)

<xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref>.

## Operators

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_op_Equality_DSharpPlus_Entities_DiscordThreadChannelMember_DSharpPlus_Entities_DiscordThreadChannelMember_"></a>operator ==\(DiscordThreadChannelMember, DiscordThreadChannelMember\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordThreadChannelMember e1, DiscordThreadChannelMember e2)
```

#### Parameters

`e1` [DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)

First message to compare.

`e2` [DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)

Second message to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two messages are equal.

### <a id="DSharpPlus_Entities_DiscordThreadChannelMember_op_Inequality_DSharpPlus_Entities_DiscordThreadChannelMember_DSharpPlus_Entities_DiscordThreadChannelMember_"></a>operator \!=\(DiscordThreadChannelMember, DiscordThreadChannelMember\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordThreadChannelMember" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordThreadChannelMember e1, DiscordThreadChannelMember e2)
```

#### Parameters

`e1` [DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)

First message to compare.

`e2` [DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)

Second message to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two messages are not equal.

