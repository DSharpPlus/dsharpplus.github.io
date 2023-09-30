# Class DiscordIntegration

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord integration. These appear on the profile as linked 3rd party accounts.

```csharp
public class DiscordIntegration : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordIntegration_Account"></a>Account

Gets the 3rd party service account for this integration.

```csharp
[JsonProperty("account", NullValueHandling = NullValueHandling.Ignore)]
public DiscordIntegrationAccount Account { get; }
```

#### Property Value

[DiscordIntegrationAccount](DSharpPlus.Entities.DiscordIntegrationAccount.md)

### <a id="DSharpPlus_Entities_DiscordIntegration_ExpireBehavior"></a>ExpireBehavior

Gets the expiration behaviour.

```csharp
[JsonProperty("expire_behavior", NullValueHandling = NullValueHandling.Ignore)]
public int ExpireBehavior { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordIntegration_ExpireGracePeriod"></a>ExpireGracePeriod

Gets the grace period before expiring subscribers.

```csharp
[JsonProperty("expire_grace_period", NullValueHandling = NullValueHandling.Ignore)]
public int ExpireGracePeriod { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordIntegration_IsEnabled"></a>IsEnabled

Gets whether this integration is enabled.

```csharp
[JsonProperty("enabled", NullValueHandling = NullValueHandling.Ignore)]
public bool IsEnabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordIntegration_IsSyncing"></a>IsSyncing

Gets whether this integration is syncing.

```csharp
[JsonProperty("syncing", NullValueHandling = NullValueHandling.Ignore)]
public bool IsSyncing { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordIntegration_Name"></a>Name

Gets the integration name.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordIntegration_RoleId"></a>RoleId

Gets ID of the role this integration uses for subscribers.

```csharp
[JsonProperty("role_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong RoleId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordIntegration_SyncedAt"></a>SyncedAt

Gets the date and time this integration was last synced.

```csharp
[JsonProperty("synced_at", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset SyncedAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_DiscordIntegration_Type"></a>Type

Gets the integration type.

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public string Type { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordIntegration_User"></a>User

Gets the user that owns this integration.

```csharp
[JsonProperty("user", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

