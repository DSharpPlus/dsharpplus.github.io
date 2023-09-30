# Class DiscordEmbedProvider

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an embed provider.

```csharp
public sealed class DiscordEmbedProvider
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbedProvider](DSharpPlus.Entities.DiscordEmbedProvider.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbedProvider_Name"></a>Name

Gets the name of the provider.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbedProvider_Url"></a>Url

Gets the url of the provider.

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public Uri Url { get; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

