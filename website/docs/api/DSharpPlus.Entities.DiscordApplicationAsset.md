# Class DiscordApplicationAsset

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an asset for an OAuth2 application.

```csharp
public sealed class DiscordApplicationAsset : DiscordAsset
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordAsset](DSharpPlus.Entities.DiscordAsset.md) ← 
[DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)

###### Inherited Members

[DiscordAsset.Id](DSharpPlus.Entities.DiscordAsset.md\#DSharpPlus\_Entities\_DiscordAsset\_Id), 
[DiscordAsset.Url](DSharpPlus.Entities.DiscordAsset.md\#DSharpPlus\_Entities\_DiscordAsset\_Url)

## Properties

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_Application"></a>Application

Gets the application this asset belongs to.

```csharp
public DiscordApplication Application { get; }
```

#### Property Value

[DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_Name"></a>Name

Gets the asset's name.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_Type"></a>Type

Gets the asset's type.

```csharp
[JsonProperty("type")]
public ApplicationAssetType Type { get; }
```

#### Property Value

[ApplicationAssetType](DSharpPlus.Entities.ApplicationAssetType.md)

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_Url"></a>Url

Gets the Url of this asset.

```csharp
public override Uri Url { get; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

## Methods

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_Equals_DSharpPlus_Entities_DiscordApplicationAsset_"></a>Equals\(DiscordApplicationAsset\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordApplicationAsset e)
```

#### Parameters

`e` [DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)

<xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordApplication" data-throw-if-not-resolved="false"></xref>.

## Operators

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_op_Equality_DSharpPlus_Entities_DiscordApplicationAsset_DSharpPlus_Entities_DiscordApplicationAsset_"></a>operator ==\(DiscordApplicationAsset, DiscordApplicationAsset\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordApplicationAsset e1, DiscordApplicationAsset e2)
```

#### Parameters

`e1` [DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)

First application asset to compare.

`e2` [DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)

Second application asset to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two application assets not equal.

### <a id="DSharpPlus_Entities_DiscordApplicationAsset_op_Inequality_DSharpPlus_Entities_DiscordApplicationAsset_DSharpPlus_Entities_DiscordApplicationAsset_"></a>operator \!=\(DiscordApplicationAsset, DiscordApplicationAsset\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordApplicationAsset" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordApplicationAsset e1, DiscordApplicationAsset e2)
```

#### Parameters

`e1` [DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)

First application asset to compare.

`e2` [DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)

Second application asset to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two application assets are not equal.

