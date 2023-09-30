# Class DiscordGuildTemplate

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public class DiscordGuildTemplate
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_Code"></a>Code

Gets the template code.

```csharp
[JsonProperty("code", NullValueHandling = NullValueHandling.Ignore)]
public string Code { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_CreatedAt"></a>CreatedAt

Date the template was created.

```csharp
[JsonProperty("created_at", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset CreatedAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_Creator"></a>Creator

Gets the creator of the template.

```csharp
[JsonProperty("creator", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUser Creator { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_CreatorId"></a>CreatorId

Gets the ID of the creator of the template.

```csharp
[JsonProperty("creator_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong CreatorId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_Description"></a>Description

Gets the description of the template.

```csharp
[JsonProperty("description", NullValueHandling = NullValueHandling.Ignore)]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_IsDirty"></a>IsDirty

Gets whether the template has not synced changes.

```csharp
[JsonProperty("is_dirty", NullValueHandling = NullValueHandling.Ignore)]
public bool? IsDirty { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_Name"></a>Name

Gets the name of the template.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_SourceGuild"></a>SourceGuild

Gets the source guild.

```csharp
[JsonProperty("serialized_source_guild", NullValueHandling = NullValueHandling.Ignore)]
public DiscordGuild SourceGuild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_SourceGuildId"></a>SourceGuildId

Gets the ID of the source guild.

```csharp
[JsonProperty("source_guild_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong SourceGuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_UpdatedAt"></a>UpdatedAt

Date the template was updated.

```csharp
[JsonProperty("updated_at", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset UpdatedAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_DiscordGuildTemplate_UsageCount"></a>UsageCount

Gets the number of times the template has been used.

```csharp
[JsonProperty("usage_count", NullValueHandling = NullValueHandling.Ignore)]
public int UsageCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

