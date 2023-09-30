# Class DiscordVoiceRegion

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents information about a Discord voice server region.

```csharp
public class DiscordVoiceRegion
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_Id"></a>Id

Gets the unique ID for the region.

```csharp
[JsonProperty("id", NullValueHandling = NullValueHandling.Ignore)]
public string Id { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_IsCustom"></a>IsCustom

Gets whether this is a custom voice region.

```csharp
[JsonProperty("custom", NullValueHandling = NullValueHandling.Ignore)]
public bool IsCustom { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_IsDeprecated"></a>IsDeprecated

Gets whether this voice region is deprecated.

```csharp
[JsonProperty("deprecated", NullValueHandling = NullValueHandling.Ignore)]
public bool IsDeprecated { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_IsOptimal"></a>IsOptimal

Gets whether this region is the most optimal for the current user.

```csharp
[JsonProperty("optimal", NullValueHandling = NullValueHandling.Ignore)]
public bool IsOptimal { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_IsVIP"></a>IsVIP

Gets whether this is a VIP-only region.

```csharp
[JsonProperty("vip", NullValueHandling = NullValueHandling.Ignore)]
public bool IsVIP { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_Name"></a>Name

Gets the name of the region.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_SampleHostname"></a>SampleHostname

Gets an example server hostname for this region.

```csharp
[JsonProperty("sample_hostname", NullValueHandling = NullValueHandling.Ignore)]
public string SampleHostname { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_SamplePort"></a>SamplePort

Gets an example server port for this region.

```csharp
[JsonProperty("sample_port", NullValueHandling = NullValueHandling.Ignore)]
public int SamplePort { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_Equals_DSharpPlus_Entities_DiscordVoiceRegion_"></a>Equals\(DiscordVoiceRegion\)

Gets whether two <xref href="DSharpPlus.Entities.DiscordVoiceRegion" data-throw-if-not-resolved="false"></xref>s are equal.

```csharp
public bool Equals(DiscordVoiceRegion region)
```

#### Parameters

`region` [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

The region to compare with.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_Equals_System_Object_"></a>Equals\(object\)

Determines whether the specified object is equal to the current object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

The object to compare with the current object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

<a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if the specified object  is equal to the current object; otherwise, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">false</a>.

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_GetHashCode"></a>GetHashCode\(\)

Serves as the default hash function.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

A hash code for the current object.

## Operators

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_op_Equality_DSharpPlus_Entities_DiscordVoiceRegion_DSharpPlus_Entities_DiscordVoiceRegion_"></a>operator ==\(DiscordVoiceRegion, DiscordVoiceRegion\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordVoiceRegion" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordVoiceRegion left, DiscordVoiceRegion right)
```

#### Parameters

`left` [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

First voice region to compare.

`right` [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

Second voice region to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two voice regions are equal.

### <a id="DSharpPlus_Entities_DiscordVoiceRegion_op_Inequality_DSharpPlus_Entities_DiscordVoiceRegion_DSharpPlus_Entities_DiscordVoiceRegion_"></a>operator \!=\(DiscordVoiceRegion, DiscordVoiceRegion\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordVoiceRegion" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordVoiceRegion left, DiscordVoiceRegion right)
```

#### Parameters

`left` [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

First voice region to compare.

`right` [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

Second voice region to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two voice regions are not equal.

