# Class DiscordForumChannelJsonConverter

Namespace: [DSharpPlus.Net.Serialization](DSharpPlus.Net.Serialization.md)  
Assembly: DSharpPlus.dll

```csharp
public class DiscordForumChannelJsonConverter : JsonConverter
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
JsonConverter ← 
[DiscordForumChannelJsonConverter](DSharpPlus.Net.Serialization.DiscordForumChannelJsonConverter.md)

###### Inherited Members

JsonConverter.WriteJson\(JsonWriter, object?, JsonSerializer\), 
JsonConverter.ReadJson\(JsonReader, Type, object?, JsonSerializer\), 
JsonConverter.CanConvert\(Type\), 
JsonConverter.CanRead, 
JsonConverter.CanWrite

## Properties

### <a id="DSharpPlus_Net_Serialization_DiscordForumChannelJsonConverter_CanWrite"></a>CanWrite

Gets a value indicating whether this <xref href="Newtonsoft.Json.JsonConverter" data-throw-if-not-resolved="false"></xref> can write JSON.

```csharp
public override bool CanWrite { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="DSharpPlus_Net_Serialization_DiscordForumChannelJsonConverter_CanConvert_System_Type_"></a>CanConvert\(Type\)

Determines whether this instance can convert the specified object type.

```csharp
public override bool CanConvert(Type objectType)
```

#### Parameters

`objectType` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type of the object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

<code>true</code> if this instance can convert the specified object type; otherwise, <code>false</code>.

### <a id="DSharpPlus_Net_Serialization_DiscordForumChannelJsonConverter_ReadJson_Newtonsoft_Json_JsonReader_System_Type_System_Object_Newtonsoft_Json_JsonSerializer_"></a>ReadJson\(JsonReader, Type, object, JsonSerializer\)

Reads the JSON representation of the object.

```csharp
public override object ReadJson(JsonReader reader, Type objectType, object existingValue, JsonSerializer serializer)
```

#### Parameters

`reader` JsonReader

The <xref href="Newtonsoft.Json.JsonReader" data-throw-if-not-resolved="false"></xref> to read from.

`objectType` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type of the object.

`existingValue` [object](https://learn.microsoft.com/dotnet/api/system.object)

The existing value of object being read.

`serializer` JsonSerializer

The calling serializer.

#### Returns

[object](https://learn.microsoft.com/dotnet/api/system.object)

The object value.

### <a id="DSharpPlus_Net_Serialization_DiscordForumChannelJsonConverter_WriteJson_Newtonsoft_Json_JsonWriter_System_Object_Newtonsoft_Json_JsonSerializer_"></a>WriteJson\(JsonWriter, object, JsonSerializer\)

Writes the JSON representation of the object.

```csharp
public override void WriteJson(JsonWriter writer, object value, JsonSerializer serializer)
```

#### Parameters

`writer` JsonWriter

The <xref href="Newtonsoft.Json.JsonWriter" data-throw-if-not-resolved="false"></xref> to write to.

`value` [object](https://learn.microsoft.com/dotnet/api/system.object)

The value.

`serializer` JsonSerializer

The calling serializer.

