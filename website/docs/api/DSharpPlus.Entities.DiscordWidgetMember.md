# Class DiscordWidgetMember

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a member within a Discord guild's widget.

```csharp
public class DiscordWidgetMember
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordWidgetMember](DSharpPlus.Entities.DiscordWidgetMember.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordWidgetMember_Avatar"></a>Avatar

Gets the member's avatar.

```csharp
[JsonProperty("avatar", NullValueHandling = NullValueHandling.Ignore)]
public string Avatar { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWidgetMember_AvatarUrl"></a>AvatarUrl

Gets the member's avatar url.

```csharp
[JsonProperty("avatar_url", NullValueHandling = NullValueHandling.Ignore)]
public string AvatarUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWidgetMember_Discriminator"></a>Discriminator

Gets the member's discriminator.

```csharp
[JsonProperty("discriminator", NullValueHandling = NullValueHandling.Ignore)]
public string Discriminator { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWidgetMember_Id"></a>Id

Gets the member's identifier within the widget.

```csharp
[JsonProperty("id", NullValueHandling = NullValueHandling.Ignore)]
public ulong Id { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordWidgetMember_Status"></a>Status

Gets the member's online status.

```csharp
[JsonProperty("status", NullValueHandling = NullValueHandling.Ignore)]
public string Status { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWidgetMember_Username"></a>Username

Gets the member's username.

```csharp
[JsonProperty("username", NullValueHandling = NullValueHandling.Ignore)]
public string Username { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

