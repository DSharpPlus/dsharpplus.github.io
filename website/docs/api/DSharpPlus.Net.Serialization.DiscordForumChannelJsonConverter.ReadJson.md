# Method ReadJson

Namespace: [DSharpPlus.Net.Serialization](DSharpPlus.Net.Serialization.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Net_Serialization_DiscordForumChannelJsonConverter_ReadJson_Newtonsoft_Json_JsonReader_System_Type_System_Object_Newtonsoft_Json_JsonSerializer_"></a>ReadJson\(JsonReader, Type, object, JsonSerializer\)

Reads the JSON representation of the object.

```csharp
public override object ReadJson(JsonReader reader, Type objectType, object existingValue, JsonSerializer serializer)
```

### Parameters

`reader` JsonReader

The <xref href="Newtonsoft.Json.JsonReader" data-throw-if-not-resolved="false"></xref> to read from.

`objectType` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type of the object.

`existingValue` [object](https://learn.microsoft.com/dotnet/api/system.object)

The existing value of object being read.

`serializer` JsonSerializer

The calling serializer.

### Returns

[object](https://learn.microsoft.com/dotnet/api/system.object)

The object value.

