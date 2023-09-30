# Class DiscordConnection

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Gets a Discord connection to a 3rd party service.

```csharp
public class DiscordConnection
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordConnection](DSharpPlus.Entities.DiscordConnection.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordConnection_FriendSync"></a>FriendSync

Gets the connection will sync friends or not.

```csharp
[JsonProperty("friend_sync", NullValueHandling = NullValueHandling.Ignore)]
public bool? FriendSync { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordConnection_Id"></a>Id

Gets the id of the connection account

```csharp
[JsonProperty("id")]
public string Id { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordConnection_Integrations"></a>Integrations

Gets a collection of partial server integrations.

```csharp
[JsonProperty("integrations", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<DiscordIntegration> Integrations { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

### <a id="DSharpPlus_Entities_DiscordConnection_IsRevoked"></a>IsRevoked

Gets whether the connection is revoked.

```csharp
[JsonProperty("revoked")]
public bool IsRevoked { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordConnection_Name"></a>Name

Gets the username of the connection account.

```csharp
[JsonProperty("name")]
public string Name { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordConnection_ShowActivity"></a>ShowActivity

Gets the connection will show activity or not.

```csharp
[JsonProperty("show_activity", NullValueHandling = NullValueHandling.Ignore)]
public bool? ShowActivity { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordConnection_Type"></a>Type

Gets the service of the connection (twitch, youtube, steam, twitter, facebook, spotify, leagueoflegends, reddit)

```csharp
[JsonProperty("type")]
public string Type { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordConnection_Verified"></a>Verified

Gets the connection is verified or not.

```csharp
[JsonProperty("verified", NullValueHandling = NullValueHandling.Ignore)]
public bool? Verified { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordConnection_Visibility"></a>Visibility

Gets the visibility of the connection.

```csharp
[JsonProperty("visibility", NullValueHandling = NullValueHandling.Ignore)]
public long? Visibility { get; set; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)?

