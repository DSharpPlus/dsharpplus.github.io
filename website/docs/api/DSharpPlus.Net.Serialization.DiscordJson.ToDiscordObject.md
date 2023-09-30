# Method ToDiscordObject<T\>

Namespace: [DSharpPlus.Net.Serialization](DSharpPlus.Net.Serialization.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Net_Serialization_DiscordJson_ToDiscordObject__1_Newtonsoft_Json_Linq_JToken_"></a>ToDiscordObject<T\>\(JToken\)

Converts this token into an object, passing any properties through extra <xref href="Newtonsoft.Json.JsonConverter" data-throw-if-not-resolved="false"></xref>s if
needed.

```csharp
public static T ToDiscordObject<T>(this JToken token)
```

### Parameters

`token` JToken

The token to convert

### Returns

T

The converted token

### Type Parameters

`T` 

Type to convert to

