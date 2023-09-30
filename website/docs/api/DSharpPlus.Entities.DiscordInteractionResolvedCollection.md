# Class DiscordInteractionResolvedCollection

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a collection of Discord snowflake objects resolved from interaction arguments.

```csharp
public sealed class DiscordInteractionResolvedCollection
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordInteractionResolvedCollection](DSharpPlus.Entities.DiscordInteractionResolvedCollection.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Attachments"></a>Attachments

The resolved attachment objects, if any.

```csharp
[JsonProperty("attachments")]
public IReadOnlyDictionary<ulong, DiscordAttachment> Attachments { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Channels"></a>Channels

Gets the resolved channel objects, if any.

```csharp
[JsonProperty("channels", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordChannel> Channels { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Members"></a>Members

Gets the resolved member objects, if any.

```csharp
[JsonProperty("members", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordMember> Members { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Messages"></a>Messages

Gets the resolved message objects, if any.

```csharp
[JsonProperty("messages", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordMessage> Messages { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Roles"></a>Roles

Gets the resolved role objects, if any.

```csharp
[JsonProperty("roles", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordRole> Roles { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Users"></a>Users

Gets the resolved user objects, if any.

```csharp
[JsonProperty("users", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordUser> Users { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

