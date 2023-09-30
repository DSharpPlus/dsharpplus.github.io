# Class DiscordJson

Namespace: [DSharpPlus.Net.Serialization](DSharpPlus.Net.Serialization.md)  
Assembly: DSharpPlus.dll

```csharp
public static class DiscordJson
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordJson](DSharpPlus.Net.Serialization.DiscordJson.md)

## Methods

### <a id="DSharpPlus_Net_Serialization_DiscordJson_PopulateObject_Newtonsoft_Json_Linq_JToken_System_Object_"></a>PopulateObject\(JToken, object\)

Populates an object with the values from a JSON node.

```csharp
public static void PopulateObject(JToken value, object target)
```

#### Parameters

`value` JToken

The token to populate the object with.

`target` [object](https://learn.microsoft.com/dotnet/api/system.object)

The object to populate.

### <a id="DSharpPlus_Net_Serialization_DiscordJson_SerializeObject_System_Object_"></a>SerializeObject\(object\)

Serializes the specified object to a JSON string.

```csharp
public static string SerializeObject(object value)
```

#### Parameters

`value` [object](https://learn.microsoft.com/dotnet/api/system.object)

The object to serialize.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A JSON string representation of the object.

### <a id="DSharpPlus_Net_Serialization_DiscordJson_ToDiscordObject__1_Newtonsoft_Json_Linq_JToken_"></a>ToDiscordObject<T\>\(JToken\)

Converts this token into an object, passing any properties through extra <xref href="Newtonsoft.Json.JsonConverter" data-throw-if-not-resolved="false"></xref>s if
needed.

```csharp
public static T ToDiscordObject<T>(this JToken token)
```

#### Parameters

`token` JToken

The token to convert

#### Returns

T

The converted token

#### Type Parameters

`T` 

Type to convert to

