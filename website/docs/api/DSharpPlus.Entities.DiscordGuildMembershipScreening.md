# Class DiscordGuildMembershipScreening

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a guild's membership screening form.

```csharp
public class DiscordGuildMembershipScreening
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildMembershipScreening_Description"></a>Description

Gets the server description shown in the screening form.

```csharp
[JsonProperty("description")]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildMembershipScreening_Fields"></a>Fields

Gets the steps in the screening form.

```csharp
[JsonProperty("form_fields")]
public IReadOnlyList<DiscordGuildMembershipScreeningField> Fields { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildMembershipScreeningField](DSharpPlus.Entities.DiscordGuildMembershipScreeningField.md)\>

### <a id="DSharpPlus_Entities_DiscordGuildMembershipScreening_Version"></a>Version

Gets when the fields were last updated.

```csharp
[JsonProperty("version")]
public DateTimeOffset Version { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

